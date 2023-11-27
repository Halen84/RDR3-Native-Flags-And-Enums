## Natives that use this enum
| Name                                  | Hash               |
|---------------------------------------|--------------------|
| ENTITY::\_GET\_ENTITY\_CARRYING\_FLAG | 0x808077647856DE62 |
| ENTITY::\_SET\_ENTITY\_CARRYING\_FLAG | 0x18FF3110CF47115D |
## Enum
```cpp
enum CCarryingFlags__Flags
{
	CanBeHogtied = 0,
	CanBeCutFree = 1,
	CanBeCarriedOnFoot = 2,
	CanBeCarriedOnMount = 3,
	CanBeDropped = 4,
	CanFleeFromTargetOnCutFree = 5,
	CanFightTargetOnCutFree = 6,
	CanBeCarriedWhenDead = 7,
	CanBeAttackedByAIWhenPerformingACarryAction = 8,
	CanCarryAnything = 9,
	MapBlipEnabled = 10,
	_0x7C937666 = 11,
	CanBeCarriedByHumanAI = 12,
	CanBeTargetedWhenCarriableOrTransitioningToCarriable = 13,
	CanBePlacedOnMount = 14,
	_0x65B590BA = 15,
	AllowFallbackActions = 16,
	CanBeCarriedWhenDeadIfAmbient = 17,
	_0xA297B179 = 18,
	DisablePromptLOSChecks = 19,
	_0x9A03270E = 20,
	IsInstantPickup = 21,
	IsAutoPickup = 22,
	ForceAllowWarpToSafeGroundLocation = 23,
	_0xE1BE8944 = 24,
	_0x66555722 = 25,
	_0x613B2BA8 = 26, // CARRYING_FLAG_PICKUPS_IGNORE_HEIGHT_RESTRICTIONS
	CleanUpWhenNotCarried = 27,
	_0xBDBF542C = 28,
	BlockKnockOffPedVariationsFromCarriableInteractions = 29,
	_0xD732DC6E = 30,
	CanBeHitWhenCarriable = 31,
	_0x0995A131 = 32,
	_0x3067588E = 33,
	DisableCarriableInteractionsOnThisMount = 34,
	ForceFallbackActions = 35,
	_0xE492F85C = 36,
	ForceHidePromptGroup = 37,
	_0xAAB56B7E = 38,
	_0x44731D1E = 39,
};
```