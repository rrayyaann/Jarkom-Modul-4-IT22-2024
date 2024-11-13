# Lapres Pratikum Jarkom-Modul-4-IT22-2024

**KELOMPOK IT22**
| Nama | NRP |
|---------------------------|------------|
|Muhamad Arrayyan | 5027231014 |
|Fadlillah Cantika Sari Hermawan | 5027231042 |


|  PIC | Aplikasi | Metode |
|--------|----------|----------|
|  Muhamad Arrayyan  | GNS3 | CIDR |
|  Fadlillah Cantika Sari Hermawan |  CPT | VLSM |

<details>

<summary>Gambar Topologi</summary>

## CIDR Topologi @ GNS3 
<img width="1500" alt="topo-gns" src="https://github.com/user-attachments/assets/5739fa93-2403-4279-952a-49fcd23f6b7c">

## VLSM Topologi @ CPT
<img width="1500" alt="topo-cpt" src="https://github.com/user-attachments/assets/e9ac9975-039c-4074-a082-67893d9d9164">

</details>

## Settingan Config
<details>

<summary>Detail Configure</summary>

## Konfigurasi
### 1
```jsx
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.244.1.1
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 192.244.2.1
	netmask 255.255.255.0

auto eth3
iface eth3 inet static
	address 192.244.3.1
	netmask 255.255.255.0

auto eth4
iface eth4 inet static
	address 192.244.4.1
	netmask 255.255.255.0

up iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.244.0.0/16
```

### 2
```jsx
auto eth0
iface eth0 inet static
	address 192.244.1.2
	netmask 255.255.255.0
	gateway 192.244.1.1
```
### 3
```jsx
auto eth0
iface eth0 inet static
	address 192.244.1.3
	netmask 255.255.255.0
	gateway 192.244.1.1
```
</details>



