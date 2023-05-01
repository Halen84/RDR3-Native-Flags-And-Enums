## Natives that use this enum
| Name                                               | Hash               |
|----------------------------------------------------|--------------------|
| POPULATION::\_ADD\_AMBIENT\_AVOIDANCE\_RESTRICTION | 0xB56D41A694E42E86 |
| POPULATION::\_ADD\_AMBIENT\_SPAWN\_RESTRICTION     | 0x18262CAFEBB5FBE1 |
## Enum
```cpp
enum PedFilterFlags
{
	PFF_NoFlag = 0,
	PFF_Beha_Unalerted = 1,
	PFF_Beha_Fleeing = 2,
	PFF_Beha_Attacking = 4,
	PFF_Beha_BaitAttracted = 8,
	PFF_Beha_FollowingOrders = 16,
	PFF_WildSmallAnimals = 32,
	PFF_WildMediumAnimals = 64,
	PFF_WildLargeAnimals = 128,
	PFF_DomesticatedAnimals = 256,
	PFF_AquaticAnimals = 512,
	PFF_Birds = 1024,
	PFF_Horses = 2048,
	PFF_DangerousAnimals = 4096,
	PFF_Humans = 8192,
	PFF_Law = 16384,
	PFF_Town = 32768,
	PFF_ScenarioPeds = 65536,
	PFF_Beha_Whistled = 131072,
	PFF_PlayerHorse = 262144,
	PFF_PersChars = 524288,
	PFF_Guards = 1048576,
	PFF_Beha_Scavenger = 2097152,
	PFF_Alligators = 4194304,
	PFF_0xE85D9A3A = 8388608,
	PFF_WildMediumAndLargeAnimals = PFF_WildMediumAnimals | PFF_WildLargeAnimals,
	PFF_WildAnimals = PFF_WildSmallAnimals | PFF_WildMediumAndLargeAnimals,
	PFF_GroundAnimals = PFF_WildAnimals | PFF_DomesticatedAnimals,
	PFF_AllAnimals = PFF_GroundAnimals | PFF_AquaticAnimals | PFF_Birds,
	PFF_AllPeds = PFF_AllAnimals | PFF_Humans,
	PFF_AllBehaviours = PFF_Beha_Unalerted | PFF_Beha_Fleeing | PFF_Beha_Attacking | PFF_Beha_BaitAttracted | PFF_Beha_FollowingOrders | PFF_Beha_Whistled | PFF_Beha_Scavenger,
};
```