## Natives that use this enum
| Name                                   | Hash               |
|----------------------------------------|--------------------|
| PED::ADD\_SCENARIO\_BLOCKING\_AREA     | 0x1B5C85C612E5256E |
| PED::\_ADD\_SCENARIO\_BLOCKING\_VOLUME | 0x4C39C95AE5DB1329 |
## Enum
```cpp
enum eScenarioBlockingFlags
{
	SBF_CANCEL_ACTIVE = 1,
	SBF_BLOCK_PLAYER = 2,
	SBF_BLOCK_AI_PEDS = 4,
	SBF_BLOCK_VEHICLES = 8,
	SBF_BLOCK_RANSACK_SCENARIOS = 16,
	SBF_UGC_ONLY = 32,
	SBF_BLOCK_PEDS = SBF_BLOCK_PLAYER | SBF_BLOCK_AI_PEDS,
	SBF_DEFAULT = SBF_BLOCK_PEDS | SBF_CANCEL_ACTIVE | SBF_BLOCK_VEHICLES,
};
```