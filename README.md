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
https://docs.google.com/spreadsheets/d/1I0JeKBu676l78l9ndJAvOM8RIORIdB6g9E8O-eWfgJg/edit?usp=sharing

# GNS-CIDR
<details>

<summary>Gambar Topologi GNS-CIDR</summary>

## CIDR Topologi @ GNS3 
<img width="1500" alt="topo-gns" src="https://github.com/user-attachments/assets/5739fa93-2403-4279-952a-49fcd23f6b7c">

</details>

# GNS-CIDR
<details>

<summary>Dokumentasi CIDR</summary>
![image](https://github.com/user-attachments/assets/5cc996c5-9cfc-4d16-8f38-496798a0b322)


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

#### Didapatkan netmask akhir pada J1 adalah `/15`

## Pembagian IP CIDR
<img width="1500" alt="Pembagian IP - CIDR" src="https://github.com/user-attachments/assets/804b7df1-2aba-45f9-886a-38b5757917af">

## Tree CIDR 
<img width="1500" alt="IT22 Tree CIDR" src="https://github.com/user-attachments/assets/1a1304cb-1c13-472a-a795-cf50989b4d3f">

## Routing
Lakukan konfigurasi berikut pada GNS3, 
#### Hololive
```



```

## Settingan Config
<details>

<summary>Detail Configure</summary>

## Konfigurasi Kiri
## Konfigurasi Bawah
## Konfigurasi Kanan
### Hololive (Gateway)
```jsx
#A15
auto eth1
iface eth1 inet static
    address 10.76.66.5
    netmask 255.255.255.252

#A1
auto eth2
iface eth2 inet static
    address 10.77.4.5
    netmask 255.255.255.252

#A8
auto eth3
iface eth3 inet static
    address 10.76.10.25
    netmask 255.255.255.252
```

### Holo-EN (Gateway)
```jsx
#A15
auto eth0
iface eth0 inet static
    address 10.76.66.6
    netmask 255.255.255.252
    gateway 10.76.66.5

#A16
auto eth1
iface eth1 inet static
    address 10.76.66.1
    netmask 255.255.255.252

#A21
auto eth2
iface eth2 inet static
    address 10.76.16.33
    netmask 255.255.255.252
```

### Holo-Myth (Gateway)
```jsx
#A16
auto eth0
iface eth0 inet static
    address 10.76.66.2
    netmask 255.255.255.252
    gateway 10.76.66.1

#A17
auto eth1
iface eth1 inet static
    address 10.76.64.1
    netmask 255.255.254.0


#A19
auto eth2
iface eth2 inet static
    address 10.76.32.65
    netmask 255.255.255.248
```

### Gura_Ame_Ina (Client)
```jsx
#A17
auto eth0
iface eth0 inet static
    address 10.76.64.2
    netmask 255.255.254.0
    gateway 10.76.64.1
```

### Kiara_Calli (Client)
```jsx
#A17
auto eth0
iface eth0 inet static
    address 10.76.64.3
    netmask 255.255.254.0
    gateway 10.76.64.1
```

### Holo Advent (Gateway)
```jsx
#A21
auto eth0
iface eth0 inet static
    address 10.76.16.34
    netmask 255.255.255.252
    gateway 10.76.16.33

#A22
auto eth1
iface eth1 inet static
    address 10.76.16.1
    netmask 255.255.255.224
```

### FuwaMoco (Client)
```jsx
#A22
auto eth0
iface eth0 inet static
    address 10.76.16.2
    netmask 255.255.255.224
    gateway 10.76.16.1
```

### Shiori_Nerissa (Client)
```jsx
#A22
auto eth0
iface eth0 inet static
    address 10.76.16.3
    netmask 255.255.255.224
    gateway 10.76.16.1
```

### Biboo (Client)
```jsx
#A22
auto eth0
iface eth0 inet static
    address 10.76.16.4
    netmask 255.255.255.224
    gateway 10.76.16.1
```

### Project-Hope (Gateway)
```jsx
#A19
auto eth0
iface eth0 inet static
    address 10.76.32.66
    netmask 255.255.255.248
    gateway 10.76.32.65

#A18
auto eth1
iface eth1 inet static
    address 10.76.32.73
    netmask 255.255.255.248
```

### Irys (Client)
```jsx
#A18
auto eth0
iface eth0 inet static
    address 10.76.32.74
    netmask 255.255.255.248
    gateway 10.76.32.73
```

### Holo-Council (Gateway)
```jsx
#A19
auto eth0
iface eth0 inet static
    address 10.76.32.67
    netmask 255.255.255.248
    gateway 10.76.32.65

#A20
auto eth1
iface eth1 inet static
    address 10.76.32.1
    netmask 255.255.255.192
```

### Kronii_Mumei (Client)
```jsx
#A20
auto eth0
iface eth0 inet static
    address 10.76.32.2
    netmask 255.255.255.192
    gateway 10.76.32.1
```

### Bae_Fauna (Client)
```jsx
#A20
auto eth0
iface eth0 inet static
    address 10.76.32.3
    netmask 255.255.255.192
    gateway 10.76.32.1
```

### Holo-ID (Gateway)
```
#A1
auto eth0
iface eth0 inet static
    address 10.77.4.6
    netmask 255.255.255.252

#A2
auto eth1
iface eth1 inet static
    address 10.77.4.1
    netmask 255.255.255.252

#A4
auto eth2
iface eth2 inet static
    address 10.77.16.65
    netmask 255.255.255.252

#A6
auto eth3
iface eth3 inet static
    address 10.77.34.1
    netmask 255.255.255.252
```

### AREA15 (Gateway)
```
#A2
auto eth0
iface eth0 inet static
    address 10.77.4.2
    netmask 255.255.255.252
    gateway 10.76.4.1

#A3
auto eth1
iface eth1 inet static
    address 10.77.0.1
    netmask 255.255.252.0
```

### lofi (Client)
```jsx
#A3
auto eth0
iface eth0 inet static
    address 10.77.0.2
    netmask 255.255.252.0
    gateway 10.77.0.1
```

### Moona (Client)
```jsx
#A3
auto eth0
iface eth0 inet static
    address 10.77.0.3
    netmask 255.255.252.0
    gateway 10.77.0.1
```

### Risu (Client)
```jsx
#A3
auto eth0
iface eth0 inet static
    address 10.77.0.4
    netmask 255.255.252.0
    gateway 10.77.0.1
```

### holoro (Gateway)
```jsx
#A4
auto eth0
iface eth0 inet static
    address 10.77.16.66
    netmask 255.255.255.252
    gateway 10.77.16.65

#A5
auto eth1
iface eth1 inet static
    address 10.77.16.1
    netmask 255.255.252.192
```

### Ollie (Client)
```jsx
#A5
auto eth0
iface eth0 inet static
    address 10.77.16.2
    netmask 255.255.252.192
    gateway 10.77.16.1
```

### Anya (Client)
```jsx
#A5
auto eth0
iface eth0 inet static
    address 10.77.16.3
    netmask 255.255.252.192
    gateway 10.77.16.1
```

### Reine (Client)
```jsx
#A5
auto eth0
iface eth0 inet static
    address 10.77.16.4
    netmask 255.255.252.192
    gateway 10.77.16.1
```

### holoh3ro (Gateway)
```jsx
#A6
auto eth0
iface eth0 inet static
    address 10.77.34.2
    netmask 255.255.255.252
    gateway 10.77.34.1

#A7
auto eth1
iface eth1 inet static
    address 10.77.32.1
    netmask 255.255.254.0
```

### Zeta (Client)
```jsx
#A7
auto eth0
iface eth0 inet static
    address 10.77.32.2
    netmask 255.255.254.0
    gateway 10.77.32.1
```

### Kaela (Client)
```jsx
#A7
auto eth0
iface eth0 inet static
    address 10.77.32.3
    netmask 255.255.254.0
    gateway 10.77.32.1
```

### Kobo (Client)
```jsx
#A7
auto eth0
iface eth0 inet static
    address 10.77.32.4
    netmask 255.255.254.0
    gateway 10.77.32.1
```

### Holo-JP (Gateway)
```jsx
#A8
auto eth0
iface eth0 inet static
    address 10.76.10.25
    netmask 255.255.255.252

#A9
auto eth1
iface eth1 inet static
    address 10.76.10.1
    netmask 255.255.255.252
```

### DEV_IS (Gateway)
```jsx
#A9
auto eth0
iface eth0 inet static
    address 10.76.10.2
    netmask 255.255.255.252
    gateway 10.76.10.1

#A10
auto eth1
iface eth1 inet static
    address 10.76.10.9
    netmask 255.255.255.240
```

### Ririka_Raden (Client)
```jsx
#A10
auto eth0
iface eth0 inet static
    address 10.76.10.10
    netmask 255.255.255.240
    gateway 10.76.10.9
```

### Ao (Client)
```jsx
#A10
auto eth0
iface eth0 inet static
    address 10.76.10.11
    netmask 255.255.255.240
    gateway 10.76.10.9
```

### Hajime_Kanade (Client)
```jsx
#A10
auto eth0
iface eth0 inet static
    address 10.76.10.12
    netmask 255.255.255.240
    gateway 10.76.10.9
```

### GEN:0 (Gateway)
```jsx
#A9
auto eth0
iface eth0 inet static
    address 10.76.10.3
    netmask 255.255.255.252
    gateway 10.76.10.1

#A11
auto eth1
iface eth1 inet static
    address 10.76.0.1
    netmask 255.255.248.0
```

### MiComet (Client)
```jsx
#A11
auto eth0
iface eth0 inet static
    address 10.76.0.2
    netmask 255.255.248.0
    gateway 10.76.0.1
```

### Sora_Robo_AZKi (Client)
```jsx
#A11
auto eth0
iface eth0 inet static
    address 10.76.0.3
    netmask 255.255.248.0
    gateway 10.76.0.1
```

### GEN:1 (Gateway)
```jsx
#A11
auto eth0
iface eth0 inet static
    address 10.76.0.4
    netmask 255.255.248.0
    gateway 10.76.0.1

#A12
auto eth1
iface eth1 inet static
    address 10.76.8.1
    netmask 255.255.254.0

#A13
auto eth2
iface eth2 inet static
    address 10.76.4.129
    netmask 255.255.255.252
```

### FBK_Matsuri (Client)
```jsx
#A12
auto eth0
iface eth0 inet static
    address 10.76.8.2
    netmask 255.255.248.0
    gateway 10.76.8.1
```

### Aki_Hachama (Client)
```jsx
#A12
auto eth0
iface eth0 inet static
    address 10.76.8.3
    netmask 255.255.248.0
    gateway 10.76.8.1
```

### Gamers (Gateway)
```jsx
#A13
auto eth0
iface eth0 inet static
    address 10.76.4.130
    netmask 255.255.255.252
    gateway 10.76.4.129

#A14
auto eth1
iface eth1 inet static
    address 10.76.4.1
    netmask 255.255.255.128
```

### Korone (Client)
```jsx
#A14
auto eth0
iface eth0 inet static
    address 10.76.4.2
    netmask 255.255.255.128
    gateway 10.76.4.1
```

### Okayu (Client)
```jsx
#A14
auto eth0
iface eth0 inet static
    address 10.76.4.3
    netmask 255.255.255.128
    gateway 10.76.4.1
```

### Mio (Client)
```jsx
#A14
auto eth0
iface eth0 inet static
    address 10.76.4.4
    netmask 255.255.255.128
    gateway 10.76.4.1

```
</details>

## CPT-VLSM
<details>

<summary>Gambar Topologi CPT-VLSM</summary>

## VLSM Topologi @ CPT
<img width="1500" alt="topo-cpt" src="https://github.com/user-attachments/assets/e9ac9975-039c-4074-a082-67893d9d9164">

</details>

## VSLM Tabel Subnetting

| Subnet | Network ID       | Netmask              | Broadcast         | Range IP                       |
|--------|-------------------|----------------------|-------------------|--------------------------------|
| A1     | 192.244.0.0      | /30 (255.255.255.252) | 192.244.0.3      | 192.244.0.1 - 192.244.0.2      |
| A2     | 192.244.0.4      | /30 (255.255.255.252) | 192.244.0.7      | 192.244.0.5 - 192.244.0.6      |
| A3     | 192.244.0.8      | /23 (255.255.254.0)   | 192.244.1.255    | 192.244.0.9 - 192.244.1.254    |
| A4     | 192.244.2.0      | /30 (255.255.255.252) | 192.244.2.3      | 192.244.2.1 - 192.244.2.2      |
| A5     | 192.244.2.4      | /30 (255.255.255.252) | 192.244.2.7      | 192.244.2.5 - 192.244.2.6      |
| A6     | 192.244.2.8      | /26 (255.255.255.192) | 192.244.2.63     | 192.244.2.9 - 192.244.2.62     |
| A7     | 192.244.2.64     | /30 (255.255.255.252) | 192.244.2.67     | 192.244.2.65 - 192.244.2.66    |
| A8     | 192.244.2.68     | /27 (255.255.255.224) | 192.244.2.95     | 192.244.2.69 - 192.244.2.94    |
| A9     | 192.244.2.96     | /30 (255.255.255.252) | 192.244.2.99     | 192.244.2.97 - 192.244.2.98    |
| A10    | 192.244.2.100    | /30 (255.255.255.252) | 192.244.2.103    | 192.244.2.101 - 192.244.2.102  |
| A11    | 192.244.2.104    | /22 (255.255.252.0)   | 192.244.3.255    | 192.244.2.105 - 192.244.3.254  |
| A12    | 192.244.4.0      | /30 (255.255.255.252) | 192.244.4.3      | 192.244.4.1 - 192.244.4.2      |
| A13    | 192.244.4.4      | /26 (255.255.255.192) | 192.244.4.63     | 192.244.4.5 - 192.244.4.62     |
| A14    | 192.244.4.64     | /30 (255.255.255.252) | 192.244.4.67     | 192.244.4.65 - 192.244.4.66    |
| A15    | 192.244.4.68     | /23 (255.255.254.0)   | 192.244.5.255    | 192.244.4.69 - 192.244.5.254   |
| A16    | 192.244.6.0      | /30 (255.255.255.252) | 192.244.6.3      | 192.244.6.1 - 192.244.6.2      |
| A17    | 192.244.6.4      | /28 (255.255.255.240) | 192.244.6.15     | 192.244.6.5 - 192.244.6.14     |
| A18    | 192.244.6.16     | /21 (255.255.248.0)   | 192.244.7.255    | 192.244.6.17 - 192.244.7.254   |
| A19    | 192.244.8.0      | /23 (255.255.254.0)   | 192.244.9.255    | 192.244.8.1 - 192.244.9.254    |
| A20    | 192.244.10.0     | /23 (255.255.254.0)   | 192.244.10.255   | 192.244.10.1 - 192.244.10.254  |
| A21    | 192.244.11.0     | /25 (255.255.255.128) | 192.244.11.127   | 192.244.11.1 - 192.244.11.126  |
| A22    | 192.244.11.128   | /19 (255.255.224.0)   | 192.244.15.255   | 192.244.11.129 - 192.244.15.254|

## Tree Subnetting VSLM CPT
![image](https://github.com/user-attachments/assets/a35f3693-f7b2-49ae-a034-1ca3f561080c)

