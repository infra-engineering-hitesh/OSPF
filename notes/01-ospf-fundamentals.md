# OSPF Fundamentals

OSPF:
- Link-state protocol
- Uses Dijkstra SPF algorithm
- Protocol Number: 89

Router Types:

Internal Router:
- All interfaces same area

ABR:
- Connects multiple areas
- Creates Type 3 LSAs

ASBR:
- Redistributes routes
- Creates Type 5 LSAs

Backbone Router:
- Participates in Area 0

Area 0:
- Backbone area
- Inter-area traffic traverses Area 0
