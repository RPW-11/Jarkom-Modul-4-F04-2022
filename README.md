# Jarkom-Modul-4-F04-2022

## Anggota

- Hilmi Zharfan Rachmadi - 5025201268
- Ida Bagus Kade Rainata Putra Wibawa - 5025201235 (Mengerjakan Labelling, Perhitungan CIDR, Perhitungan VLSM, Implementasi di Cisco Packet Tracer)
- Naufal Faadhilah - 5025201221

## Konfigurasi GNS3

```txt
    # The Resonance

    auto eth0
    iface eth0 inet dhcp

    # A16 - The Order
    auto eth1
    iface eth1 inet static
        address 192.201.11.217
        netmask 255.255.255.252

    # A17 -  The Beast
    auto eth2
    iface eth2 inet static
        address 192.201.11.225
        netmask 255.255.255.252

    # A17 -  The Magical
    auto eth3
    iface eth3 inet static
        address 192.201.11.221
        netmask 255.255.255.252

    # A15 -  The Instrument
    auto eth4
    iface eth4 inet static
        address 192.201.11.213
        netmask 255.255.255.252

    # --------------------------------------------

    # The Beast

    # A18 - The Resonance
    auto eth0
    iface eth0 inet static
        address 192.201.11.226
        netmask 255.255.255.252
        gateway 192.201.11.225

    # --------------------------------------------

    # The Magical

    # A17 - The Resonance
    auto eth0
    iface eth0 inet static
        address 192.201.11.222
        netmask 255.255.255.252

    # A14 - Haines - Corvekt
    auto eth1
    iface eth1 inet static
        address 192.201.6.1
        netmask 255.255.254.0

    # --------------------------------------------

    # Ashaf

    # A13 - The Order
    auto eth0
    iface eth0 inet static
        address 192.201.11.130
        netmask 255.255.255.192
        gateway 192.201.11.129

    # --------------------------------------------

    # The Order

    # A16 - The Resonance
    auto eth0
    iface eth0 inet static
        address 192.201.11.218
        netmask 255.255.255.252

    # A13 - Ashaf
    auto eth1
    iface eth1 inet static
        address 192.201.11.129
        netmask 255.255.255.192

    # A12 - The Minister
    auto eth2
    iface eth2 inet static
        address 192.201.11.209
        netmask 255.255.255.252

    # --------------------------------------------


    # The Minister

    # A12 - The Order
    auto eth0
    iface eth0 inet static
        address 192.201.11.210
        netmask 255.255.255.252

    # A6 - Guiedeau 
    auto eth1
    iface eth1 inet static
        address 192.201.0.1
        netmask 255.255.252.0

    # A5 - The Dauntless 
    auto eth2
    iface eth2 inet static
        address 192.201.11.197
        netmask 255.255.255.252

    # --------------------------------------------

    # Guideau

    # A6 - The Minister
    auto eth0
    iface eth0 inet static
        address 192.201.0.2
        netmask 255.255.252.0
        gateway 192.201.0.1

    # --------------------------------------------

    # The Dauntless 

    # A5 -  The Minister
    auto eth0
    iface eth0 inet static
        address 192.201.11.198
        netmask 255.255.255.252

    # A1 -  Johan - Phanora
    auto eth1
    iface eth1 inet static
        address 192.201.8.1
        netmask 255.255.255.0

    # --------------------------------------------

    # Haines

    # A14 - The Magical
    auto eth0
    iface eth0 inet static
        address 192.201.6.3
        netmask 255.255.254.0
        gateway 192.201.6.1

    # --------------------------------------------

    # Corvekt

    # A14 - The Magical
    auto eth0
    iface eth0 inet static
        address 192.201.6.2
        netmask 255.255.254.0
        gateway 192.201.6.1

    # --------------------------------------------

    # Phanora

    # A1 - TheDauntless
    auto eth0
    iface eth0 inet static
        address 192.201.8.2
        netmask 255.255.255.0
        gateway 192.201.8.1

    # --------------------------------------------

    # Johan

    # A1 - The Dauntless
    auto eth0
    iface eth0 inet static
        address 192.201.8.3
        netmask 255.255.255.0
        gateway 192.201.8.1

    # --------------------------------------------

    # Keith

    # A7 - The Firefist
    auto eth0
    iface eth0 inet static
        address 192.201.9.3
        netmask 255.255.255.0
        gateway 192.201.9.2

    # --------------------------------------------

    # The Firefist

    # A10 - The Instrument
    auto eth0
    iface eth0 inet static
        address 192.201.11.206
        netmask 255.255.255.252

    # A7 - Keith - The Queen
    auto eth1
    iface eth1 inet static
        address 192.201.9.1
        netmask 255.255.255.0

    # A8 - Oakleave
    auto eth2
    iface eth2 inet static
        address 192.201.4.1
        netmask 255.255.254.0

    # --------------------------------------------

    # The Instrument

    # A10 - The Resonance
    auto eth0
    iface eth0 inet static
        address 192.201.11.214
        netmask 255.255.255.252

    # A7 - The Profound
    auto eth1
    iface eth1 inet static
        address 192.201.11.201
        netmask 255.255.255.252

    # A10 - The Firefist
    auto eth2
    iface eth2 inet static
        address 192.201.11.205
        netmask 255.255.255.252

    # A8 - Matt Cugat
    auto eth3
    iface eth3 inet static
        address 192.201.11.1
        netmask 255.255.255.128

    # --------------------------------------------

    # Matt Cugat

    # A8 - The Instrument
    auto eth0
    iface eth0 inet static
        address 192.201.11.2
        netmask 255.255.255.128
        gateway 192.201.11.1

    # --------------------------------------------

    # The Profound

    # A9 - The Instrument
    auto eth0
    iface eth0 inet static
        address 192.201.11.202
        netmask 255.255.255.252

    # A4 - Spendrow
    auto eth1
    iface eth1 inet static
        address 192.201.10.129
        netmask 255.255.255.128

    # A3 - Helga
    auto eth2
    iface eth2 inet static
        address 192.201.10.1
        netmask 255.255.255.128


    # --------------------------------------------

    # Spendrow

    # A4 - The Profound
    auto eth0
    iface eth0 inet static
        address 192.201.10.130
        netmask 255.255.255.128
        gateway 192.201.10.129


    # --------------------------------------------

    # Helga

    # A3 - The Profound
    auto eth0
    iface eth0 inet static
        address 192.201.10.2
        netmask 255.255.255.128
        gateway 192.201.10.1


    # --------------------------------------------

    # Oakleave

    # A8 - The Firefist
    auto eth0
    iface eth0 inet static
        address 192.201.4.2
        netmask 255.255.254.0
        gateway 192.201.4.1


    # --------------------------------------------

    # The Queen

    # A7 - Keith - The Firefist
    auto eth0
    iface eth0 inet static
        address 192.201.9.2
        netmask 255.255.255.0

    # A2 - The Witch
    auto eth1
    iface eth1 net static
        address 192.201.11.193
        netmask 255.255.255.252

    # --------------------------------------------

    # The Witch

    # A2 - The Queen
    auto eth0
    iface eth0 inet static
        address 192.201.11.194
        netmask 255.255.255.252
        gateway 192.201.11.193

    # --------------------------------------------
```

## Routing Script

```txt
    # The Order
    route add -net 192.201.0.0 netmask 255.255.252.0 gw 192.201.11.210
    route add -net 192.201.8.0 netmask 255.255.255.0 gw 192.201.11.210
    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.217

    # ------------------------------------------------------------

    # The Resonance
    route add -net 192.201.11.128 netmask 255.255.255.128 gw 192.201.11.218
    route add -net 192.201.0.0 netmask 255.255.252.0 gw 192.201.11.218
    route add -net 192.201.8.0 netmask 255.255.255.0 gw 192.201.11.218

    # ------------------------------------------------------------

    # The Magical
    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.221

    # ------------------------------------------------------------

    # The Minister
    # 0.0.0.0/0 via 192.201.11.209
    # 192.201.8.0/24 via 192.201.11.198

    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.209
    route add -net 192.201.8.0 netmask 255.255.255.0 gw 192.201.11.198

    # ------------------------------------------------------------

    # The Dauntless
    # 0.0.0.0/0 via 192.201.11.197

    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.197

    # ------------------------------------------------------------

    # The Instrument
    # 192.201.10.0/24 via 192.201.11.202
    # 192.201.4.0/23 via 192.201.11.206
    # 192.201.9.0/24 via 192.201.11.206
    # 192.201.11.192/30 via 192.201.11.206
    # 0.0.0.0/0 via 192.201.11.213

    route add -net 192.201.10.0 netmask 255.255.255.0 gw 192.201.11.202
    route add -net 192.201.4.0 netmask 255.255.254.0 gw 192.201.11.206
    route add -net 192.201.9.0 netmask 255.255.255.0 gw 192.201.11.206
    route add -net 192.201.11.192 netmask 255.255.255.252 gw 192.201.11.206
    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.213

    # ------------------------------------------------------------

    # The Profound
    # 0.0.0.0/0 via 192.201.11.201

    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.201

    # ------------------------------------------------------------

    # The Firefist
    # 0.0.0.0/0 via 192.201.11.205
    # 192.201.11.192/30 via 192.201.9.2

    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.11.205
    route add -net 192.201.11.192 netmask 255.255.255.252 gw 192.201.9.2

    # ------------------------------------------------------------

    # The Queen
    # 0.0.0.0/0 via 192.201.9.1

    route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.201.9.1

    # ------------------------------------------------------------
```

## Kendala

- Teman saya Naufal Faadhilah mengalami kesulitan dalam re-import GNS3 nya (layarnya hanya hitam).
- Salah satu teman saya memiliki masalah dengan orang tuanya.
