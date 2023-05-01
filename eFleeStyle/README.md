## Natives that use this enum
| Name                            | Hash               |
|---------------------------------|--------------------|
| TASK::TASK\_FLEE\_COORD         | 0x58428248BF4B64E4 |
| TASK::TASK\_FLEE\_PED           | 0xFD45175A6DFD7CE9 |
| TASK::TASK\_SMART\_FLEE\_PED    | 0x22B0D0E37CCB840D |
| TASK::TASK\_SMART\_FLEE\_COORD  | 0x94587F17E9C365D5 |
| TASK::\_TASK\_FLEE\_FROM\_COORD | 0x6879FF208ED87F2A |
| TASK::\_TASK\_FLEE\_FROM\_PED   | 0x7B74D8EEDE9B5727 |
## Enum
```cpp
enum eFleeStyle
{
	NervousRetreat = 0,
	AnnoyedRetreat = 1,
	PotentialThreat = 2,
	MajorThreat = 3,
	ClearTheArea = 4,
	MortallyInjured = 5,
	CalmRetreat = 6,
	InjuredRider = 7,
	IntimidatedRetreat = 8,
	HorseTamingQuick = 9,
	HorseTamingSlow = 10,
	StolenVehicleRetreat = 11,
	CautiousRetreat = 12,
};
```