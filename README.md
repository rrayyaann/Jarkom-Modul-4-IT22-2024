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
<img width="1500" alt="IT22 Tree CIDR" src="https://github.com/user-attachments/assets/b2f97321-5e2c-4ce8-bb33-85fca830a6e3">


## Settingan Config
<details>

<summary>Detail Configure</summary>

## Konfigurasi Pusat
### Hololive (Gateway)
```jsx
#A1
auto eth1
iface eth1 inet static
    address 192.245.16.1
    netmask 255.255.255.252

#A9
auto eth2
iface eth2 inet static
    address 192.244.160.1
    netmask 255.255.255.252

#A16
auto eth3
iface eth3 inet static
    address 192.244.64.1
    netmask 255.255.255.252

```

## Konfigurasi Kiri

### Holo-EN (Gateway)
```jsx
#A1
auto eth0
iface eth0 inet static
    address 192.245.16.2
    netmask 255.255.255.252
    gateway 192.245.16.1

#A2
auto eth1
iface eth1 inet static
    address 192.245.4.1
    netmask 255.255.255.252

#A7
auto eth2
iface eth2 inet static
    address 192.245.8.33
    netmask 255.255.255.252

```

### Holo-Myth (Gateway)
```jsx
#A2
auto eth0
iface eth0 inet static
    address 192.245.4.2
    netmask 255.255.255.252
    gateway 192.245.4.1

#A3
auto eth1
iface eth1 inet static
    address 192.245.0.1
    netmask 255.255.254.0


#A4
auto eth2
iface eth2 inet static
    address 192.245.2.129
    netmask 255.255.255.248

```

### Gura_Ame_Ina (Client)
```jsx
#A3
auto eth0
iface eth0 inet static
    address 192.245.0.3
    netmask 255.255.254.0
    gateway 192.245.0.1

```

### Kiara_Calli (Client)
```jsx
#A3
auto eth0
iface eth0 inet static
    address 192.245.0.2 
    netmask 255.255.254.0
    gateway 192.245.0.1

```

### Holo Advent (Gateway)
```jsx
#A7
auto eth0
iface eth0 inet static
    address 192.245.8.34
    netmask 255.255.255.252
    gateway 192.245.8.33

#A8
auto eth1
iface eth1 inet static
    address 192.245.8.1
    netmask 255.255.255.224

```

### FuwaMoco (Client)
```jsx
#A8
auto eth0
iface eth0 inet static
    address 192.245.8.2
    netmask 255.255.255.224
    gateway 192.245.8.1

```

### Shiori_Nerissa (Client)
```jsx
#A8
auto eth1
iface eth1 inet static
    address 192.245.8.3
    netmask 255.255.255.224
    gateway 192.245.8.1

```

### Biboo (Client)
```jsx
#A8
auto eth2
iface eth2 inet static
    address 192.245.8.4
    netmask 255.255.255.224
    gateway 192.245.8.1

```

### Project-Hope (Gateway)
```jsx
#A4
auto eth0
iface eth0 inet static
    address 192.245.2.130
    netmask 255.255.255.248
    gateway 192.245.2.129

#A5
auto eth1
iface eth1 inet static
    address 192.245.2.65
    netmask 255.255.255.248

```

### Irys (Client)
```jsx
#A5
auto eth0
iface eth0 inet static
    address 192.245.2.66
    netmask 255.255.255.248
    gateway 192.245.2.65

```

### Holo-Council (Gateway)
```jsx
#A4
auto eth0
iface eth0 inet static
    address 192.245.2.131
    netmask 255.255.255.248
    gateway 192.245.2.129

#A6
auto eth1
iface eth1 inet static
    address 192.245.2.1
    netmask 255.255.255.192

```

### Kronii_Mumei (Client)
```jsx
#A6
auto eth0
iface eth0 inet static
    address 192.245.2.2
    netmask 255.255.255.192
    gateway 192.245.2.1

```

### Bae_Fauna (Client)
```jsx
#A6
auto eth0
iface eth0 inet static
    address 192.245.2.3
    netmask 255.255.255.192
    gateway 192.245.2.1

```

## Konfigurasi Kanan
### Holo-ID (Gateway)
```
#A9
auto eth0
iface eth0 inet static
    address 192.244.160.2
    netmask 255.255.255.252

#A10
auto eth1
iface eth1 inet static
    address 192.244.132.1
    netmask 255.255.255.252

#A12
auto eth2
iface eth2 inet static
    address 192.244.136.65
    netmask 255.255.255.252

#A14
auto eth3
iface eth3 inet static
    address 192.244.146.1
    netmask 255.255.255.252

```

### AREA15 (Gateway)
```
#A10
auto eth0
iface eth0 inet static
    address 192.244.132.2
    netmask 255.255.255.252
    gateway 192.244.132.1

#A11
auto eth1
iface eth1 inet static
    address 192.244.128.1
    netmask 255.255.252.0

```

### lofi (Client)
```jsx
#A11
auto eth0
iface eth0 inet static
    address 192.244.128.4
    netmask 255.255.252.0
    gateway 192.244.128.1

```

### Moona (Client)
```jsx
#A11
auto eth0
iface eth0 inet static
    address 192.244.128.3
    netmask 255.255.252.0
    gateway 192.244.128.1

```

### Risu (Client)
```jsx
#A11
auto eth0
iface eth0 inet static
    address 192.244.128.2
    netmask 255.255.252.0
    gateway 192.244.128.1

```

### holoro (Gateway)
```jsx
#A12
auto eth0
iface eth0 inet static
    address 192.244.136.66
    netmask 255.255.255.252
    gateway 192.244.136.65

#A13
auto eth1
iface eth1 inet static
    address 192.244.136.1
    netmask 255.255.255.192

```

### Ollie (Client)
```jsx
#A13
auto eth0
iface eth0 inet static
    address 192.244.136.2
    netmask 255.255.252.192
    gateway 192.244.136.1
```

### Anya (Client)
```jsx
#A13
auto eth0
iface eth0 inet static
    address 192.244.136.3
    netmask 255.255.252.192
    gateway 192.244.136.1

```

### Reine (Client)
```jsx
#A13
auto eth0
iface eth0 inet static
    address 192.244.136.4
    netmask 255.255.255.192
    gateway 192.244.136.1
```

### holoh3ro (Gateway)
```jsx
#A14
auto eth0
iface eth0 inet static
    address 192.244.146.2
    netmask 255.255.255.252
    gateway 192.244.146.1

#A15
auto eth1
iface eth1 inet static
    address 192.244.144.1
    netmask 255.255.254.0

```

### Zeta (Client)
```jsx
#A15
auto eth0
iface eth0 inet static
    address 192.244.144.2
    netmask 255.255.254.0
    gateway 192.244.144.1

```

### Kaela (Client)
```jsx
#A15
auto eth0
iface eth0 inet static
    address 192.244.144.3
    netmask 255.255.254.0
    gateway 192.244.144.1

```

### Kobo (Client)
```jsx
#A15
auto eth0
iface eth0 inet static
    address 192.244.144.4
    netmask 255.255.254.0
    gateway 192.244.144.1

```

## Konfigurasi Bawah
### Holo-JP (Gateway)
```jsx
#A16
auto eth0
iface eth0 inet static
    address 192.244.64.2
    netmask 255.255.255.252

#A17
auto eth1
iface eth1 inet static
    address 192.244.16.1
    netmask 255.255.255.252

```

### DEV_IS (Gateway)
```jsx
#A17
auto eth0
iface eth0 inet static
    address 192.244.16.3
    netmask 255.255.255.252
    gateway 192.244.16.1

#A18
auto eth1
iface eth1 inet static
    address 192.244.32.1
    netmask 255.255.255.240

```

### Ririka_Raden (Client)
```jsx
#A18
auto eth0
iface eth0 inet static
    address 192.244.32.2
    netmask 255.255.255.240
    gateway 192.244.32.1

```

### Ao (Client)
```jsx
#A18
auto eth0
iface eth0 inet static
    address 192.244.32.3
    netmask 255.255.255.240
    gateway 192.244.32.1

```

### Hajime_Kanade (Client)
```jsx
#A18
auto eth0
iface eth0 inet static
    address 192.244.32.4
    netmask 255.255.255.240
    gateway 192.244.32.1

```

### GEN:0 (Gateway)
```jsx
#A17
auto eth0
iface eth0 inet static
    address 192.244.16.2
    netmask 255.255.255.248
    gateway 192.244.16.1

#A19
auto eth1
iface eth1 inet static
    address 192.244.0.1
    netmask 255.255.248.0

```

### MiComet (Client)
```jsx
#A19
auto eth0
iface eth0 inet static
    address 192.244.0.2
    netmask 255.255.248.0
    gateway 192.244.0.1

```

### Sora_Robo_AZKi (Client)
```jsx
#A19
auto eth0
iface eth0 inet static
    address 192.244.0.3
    netmask 255.255.248.0
    gateway 192.244.0.1

```

### GEN:1 (Gateway)
```jsx
#A19
auto eth0
iface eth0 inet static
    address 192.244.0.4
    netmask 255.255.248.0
    gateway 

#A20
auto eth1
iface eth1 inet static
    address 192.244.8.1
    netmask 255.255.254.0

#A21
auto eth2
iface eth2 inet static
    address 192.244.10.129
    netmask 255.255.255.252

```

### FBK_Matsuri (Client)
```jsx
#A20
auto eth0
iface eth0 inet static
    address 192.244.8.2
    netmask 255.255.254.0
    gateway 192.244.8.1

```

### Aki_Hachama (Client)
```jsx
#A20
auto eth0
iface eth0 inet static
    address 192.244.8.3
    netmask 255.255.248.0
    gateway 192.244.8.1

```

### Gamers (Gateway)
```jsx
#A21
auto eth0
iface eth0 inet static
    address 192.244.10.130
    netmask 255.255.255.252
    gateway 192.244.10.129

#A22
auto eth1
iface eth1 inet static
    address 192.244.10.1
    netmask 255.255.255.128

```

### Korone (Client)
```jsx
#A22
auto eth0
iface eth0 inet static
    address 192.244.10.2
    netmask 255.255.255.128
    gateway 192.244.10.1

```

### Okayu (Client)
```jsx
#A22
auto eth0
iface eth0 inet static
    address 192.244.10.3
    netmask 255.255.255.128
    gateway 192.244.10.1

```

### Mio (Client)
```jsx
#A22
auto eth0
iface eth0 inet static
    address 192.244.10.4
    netmask 255.255.255.128
    gateway 192.244.10.1

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

