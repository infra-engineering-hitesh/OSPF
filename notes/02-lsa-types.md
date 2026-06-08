# OSPF LSA Types

Type 1 - Router LSA
Created By:
- Every router

Scope:
- Inside area only

Purpose:
- Describe router interfaces and links

---------------------

Type 2 - Network LSA

Created By:
- DR

Scope:
- Area local

Purpose:
- Multi-access network representation

---------------------

Type 3 - Summary LSA

Created By:
- ABR

Purpose:
- Inter-area routes

Flow:

Area 1
 Type1/2
   ↓
 ABR
   ↓
 Type3
   ↓
 Area0

---------------------

Type 5 - External LSA

Created By:
- ASBR

Purpose:
- Advertise redistributed routes

Examples:
- Static
- BGP
- Connected
- EIGRP

Flooding:
- Normal OSPF areas

Blocked:
- Stub
- Totally Stub
- NSSA

---------------------

Type 7 - NSSA External

Created By:
- ASBR inside NSSA

Purpose:
- Local redistribution inside NSSA

Conversion:

Type7
  ↓
ABR
  ↓
Type5
