## Natives that use this enum
| Name                                            | Hash               |
|-------------------------------------------------|--------------------|
| TASK::TASK\_ENTER\_VEHICLE                      | 0xC20E50AA46D09CA8 |
| TASK::TASK\_LEAVE\_VEHICLE                      | 0xD3DBCE61A490BE02 |
| TASK::TASK\_LEAVE\_ANY\_VEHICLE                 | 0x504D54DF3F6F2247 |
| TASK::TASK\_MOUNT\_ANIMAL                       | 0x92DB0739813C5186 |
| TASK::TASK\_DISMOUNT\_ANIMAL                    | 0x48E92D3DDE23C23A |
| TASK::TASK\_DISEMBARK\_NEAREST\_TRAIN\_CARRIAGE | 0x0A11F3BDEC03ED5F |
## Enum
```cpp
enum eEnterExitVehicleFlags
{
	ECF_NONE = 0,
	ECF_RESUME_IF_INTERRUPTED = (1 << 0),
	ECF_WARP_ENTRY_POINT = (1 << 1),
	ECF_INTERRUPT_DURING_GET_IN = (1 << 2),
	ECF_JACK_ANYONE = (1 << 3),
	ECF_WARP_PED = (1 << 4),
	ECF_INTERRUPT_DURING_GET_OUT = (1 << 5),
	ECF_DONT_WAIT_FOR_VEHICLE_TO_STOP = (1 << 6),
	ECF_ALLOW_EXTERIOR_ENTRY = (1 << 7),
	ECF_DONT_CLOSE_DOOR = (1 << 8),
	ECF_WARP_IF_DOOR_IS_BLOCKED = (1 << 9),
	ECF_ENTER_USING_NAVMESH = (1 << 10),
	ECF_JUMP_OUT = (1 << 12),
	ECF_PREFER_DISMOUNT_SIDE_WITH_FEWER_PEDS = (1 << 14),
	ECF_DONT_DEFAULT_WARP_IF_DOOR_BLOCKED = (1 << 16),
	ECF_USE_LEFT_ENTRY = (1 << 17),
	ECF_USE_RIGHT_ENTRY = (1 << 18),
	ECF_JUST_PULL_PED_OUT = (1 << 19),
	ECF_BLOCK_SEAT_SHUFFLING = (1 << 20),
	ECF_WARP_IF_SHUFFLE_LINK_IS_BLOCKED = (1 << 22),
	ECF_DONT_JACK_ANYONE = (1 << 23),
	ECF_WAIT_FOR_ENTRY_POINT_TO_BE_CLEAR = (1 << 24),
	ECF_USE_HITCH_DISMOUNT_VARIANT = (1 << 25),
	ECF_EXIT_SEAT_ON_TO_VEHICLE = (1 << 26),
	ECF_ALLOW_SCRIPTED_TASK_ABORT = (1 << 27),
	ECF_WILL_SHOOT_AT_TARGET_PEDS = (1 << 28),
	ECF_INTERRUPT_ALWAYS = (1 << 29),
	ECF_IGNORE_ENTRY_FROM_CLOSEST_POINT = (1 << 30),
	ECF_ALLOW_JACK_PLAYER_PED_ONLY = (1 << 31),
};
```