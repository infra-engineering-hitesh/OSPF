# Stub vs NSSA

Stub:

Blocks:
- Type5

Allows:
- Default route
- Type1
- Type2
- Type3

Redistribution:
- NO

ASBR:
- Not Allowed

---------------------

NSSA:

Blocks:
- Incoming Type5

Allows:
- Local redistribution

Uses:
- Type7

ASBR:
- Allowed

Conversion:

Type7
 ↓
ABR
 ↓
Type5
