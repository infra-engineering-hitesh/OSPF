# LSA Flow

Area 1 Loopback:

R1 Loopback
    ↓
Type1

ABR (R2)
    ↓
Creates Type3

Area0
    ↓

ABR (R3)
    ↓

Area2

---------------------

External Route Flow

Static Route
     ↓

ASBR

redistribute static

     ↓

Type5

Flood OSPF

---------------------

NSSA Flow

Connected Route

R4

redistribute connected

    ↓

Type7

ABR

    ↓

Type5

Other Areas
