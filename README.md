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

## Prefix IP 
Kelompok kami memiliki prefix IP `192.244`

# Spreadsheet
https://docs.google.com/spreadsheets/d/1nslt1sHwc9l-T5B9iu9ZCbg4ardvPgQ_4LDYq8eaeOc/edit?usp=sharing

# GNS-CIDR
<details>

<summary>Gambar Topologi GNS-CIDR</summary>

## CIDR Topologi @ GNS3 
<img width="1500" alt="topo-gns" src="https://github.com/user-attachments/assets/5739fa93-2403-4279-952a-49fcd23f6b7c">

</details>

## Penggabungan Subnet 
### `Rute Subnet`
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/3e0dd9d8-eec8-49b4-b44a-b8a0111c8bcb">

#### Subneting
<img width="1500" alt="SUBNETING" src="https://github.com/user-attachments/assets/a079680f-6f43-4427-9b8a-15596134f4ec">

### `Penggabungan 1`
<img width="1500" alt="SUB B" src="https://github.com/user-attachments/assets/6313150e-2265-4a4f-8734-8512a8c10154">

#### Tabel 1
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/41bdc393-954e-4030-a1c2-e8f5912b4bba">

### `Penggabungan 2`
<img width="1500" alt="SUB C" src="https://github.com/user-attachments/assets/5fa15230-6150-4ea5-97f3-36a680bd1975">

#### Tabel 2
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/ce75ee31-4762-4e19-83da-025c6808dff4">

### `Penggabungan 3`
<img width="1500" alt="SUB D" src="https://github.com/user-attachments/assets/e4242d32-91f7-4aea-a276-cc9e50b7e298">

#### Tabel 3
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/3968fc65-ed8f-4c4a-86fa-3f3574989951">

### `Penggabungan 4`
<img width="1500" alt="SUB E" src="https://github.com/user-attachments/assets/6a555eba-ec6a-4333-997b-fb15f75ae827">

#### Tabel 4
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/91ccc8d2-42ff-4f86-a667-82798599d1dc">

### `Penggabungan 5`
<img width="1500" alt="SUB F" src="https://github.com/user-attachments/assets/245efa47-36d3-4096-873d-c1dea4ce2102">

#### Tabel 5
<img width="1500" alt="SUB F" src="https://github.com/user-attachments/assets/8f152193-db4f-46a4-a54a-254dbc538adc">

### `Penggabungan 6`
<img width="1500" alt="SUB G" src="https://github.com/user-attachments/assets/318c0111-e5d9-44c5-8f1b-338d7d4fea6f">

#### Tabel 6
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/39031e85-5222-44aa-b5e8-905e145c24a5">

### `Penggabungan 7`
<img width="1500" alt="SUB H" src="https://github.com/user-attachments/assets/2f52b43e-594b-4832-97fc-19dc5439441c">

#### Tabel 7
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/1a39ca9b-9cd6-4602-a440-46ddeee931e3">

### `Penggabungan 8`
<img width="1500" alt="SUB I" src="https://github.com/user-attachments/assets/491146b3-070f-44db-9ecf-5df1ce22d325">

#### Tabel 8
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/60d08579-00ca-46ca-81b5-f19c8c7c64b8">

### `Penggabungan 9`
<img width="1500" alt="SUB J" src="https://github.com/user-attachments/assets/d803b93d-d983-49b8-a1e8-a24f8aa35aa7">

#### Tabel 9
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/1e43d3c4-a251-453e-a9b6-9d3aa66d1249">

Didapatkan netmask akhir pada I1 adalah `/15`

## Pembagian IP CIDR


## Tree CIDR 
<img width="1500" alt="rute" src="https://github.com/user-attachments/assets/37924367-14ca-4c2c-a03d-a8200e4dc7f7">

## Routing
Lakukan konfigurasi berikut pada GNS3, 
#### Aura
```
auto eth0
iface eth0 inet dhcp

#A20 Aura-Denken
auto eth1
iface eth1 inet static
	address 10.67.1.1
	netmask 255.255.255.252

#A9 Aura-Eisen
auto eth2
iface eth2 inet static
	address 10.65.128.1
	netmask 255.255.255.252

#A1 Aura-Frieren
auto eth3
iface eth3 inet static
	address 10.66.128.1
	netmask 255.255.255.252
```

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

## CPT-VLSM
<details>

<summary>Gambar Topologi CPT-VLSM</summary>

## VLSM Topologi @ CPT
<img width="1500" alt="topo-cpt" src="https://github.com/user-attachments/assets/e9ac9975-039c-4074-a082-67893d9d9164">

</details>




