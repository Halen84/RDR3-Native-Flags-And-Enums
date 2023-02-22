## Natives that use this enum
```
TASK::TASK_FLEE_COORD (0x58428248BF4B64E4)
TASK::TASK_FLEE_PED (0xFD45175A6DFD7CE9)
TASK::TASK_SMART_FLEE_PED (0x22B0D0E37CCB840D)
TASK::TASK_SMART_FLEE_COORD (0x94587F17E9C365D5)
TASK::_TASK_FLEE_FROM_COORD (0x6879FF208ED87F2A)
TASK::_TASK_FLEE_FROM_PED (0x7B74D8EEDE9B5727)
```
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