# OSPF Area Types

Standard Area

Allows:
- Type1
- Type2
- Type3
- Type5

---------------------

Stub Area

Allows:
- Type1
- Type2
- Type3
- Default Route

Blocks:
- Type5

Restrictions:
- No ASBR

Purpose:
- Reduce routing table size

---------------------

Totally Stub

Allows:
- Default Route

Blocks:
- Type3
- Type5

Smallest LSDB

---------------------

NSSA

Allows:
- Local Redistribution
- Type7

Blocks:
- Incoming Type5

ABR converts:

Type7
 ↓
Type5
