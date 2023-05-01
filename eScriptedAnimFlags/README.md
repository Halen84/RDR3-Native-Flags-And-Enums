## Natives that use this enum
```
TASK::TASK_PLAY_ANIM (0xEA47FE3719165B94)
TASK::TASK_PLAY_ANIM_ADVANCED (0x83CDB10EA29B370B)
```
## Enum
```cpp
enum eScriptedAnimFlags
{
	AF_LOOPING = (1 << 0),
	AF_HOLD_LAST_FRAME = (1 << 1),
	AF_NOT_INTERRUPTABLE = (1 << 2),
	AF_UPPERBODY = (1 << 3),
	AF_SECONDARY = (1 << 4),
	AF_ABORT_ON_PED_MOVEMENT = (1 << 5),
	AF_ADDITIVE = (1 << 6),
	AF_OVERRIDE_PHYSICS = (1 << 7),
	AF_EXTRACT_INITIAL_OFFSET = (1 << 8),
	AF_EXIT_AFTER_INTERRUPTED = (1 << 9),
	AF_TAG_SYNC_IN = (1 << 10),
	AF_TAG_SYNC_OUT = (1 << 11),
	AF_TAG_SYNC_CONTINUOUS = (1 << 12),
	AF_FORCE_START = (1 << 13),
	AF_USE_KINEMATIC_PHYSICS = (1 << 14),
	AF_USE_MOVER_EXTRACTION = (1 << 15),
	AF_DONT_SUPPRESS_LOCO = (1 << 16),
	AF_ENDS_IN_DEAD_POSE = (1 << 17),
	AF_ACTIVATE_RAGDOLL_ON_COLLISION = (1 << 18),
	AF_DONT_EXIT_ON_DEATH = (1 << 19),
	AF_ABORT_ON_WEAPON_DAMAGE = (1 << 20),
	AF_DISABLE_FORCED_PHYSICS_UPDATE = (1 << 21),
	AF_GESTURE = (1 << 22),
	AF_SKIP_IF_BLOCKED_BY_HIGHER_PRIORITY_TASK = (1 << 23),
	AF_USE_ABSOLUTE_MOVER = (1 << 24),
	AF_0xC57F16E7 = (1 << 25),
	AF_UPPERBODY_TAGS = (1 << 26),
	AF_PROCESS_ATTACHMENTS_ON_START = (1 << 27),
	AF_EXPAND_PED_CAPSULE_FROM_SKELETON = (1 << 28),
	AF_BLENDOUT_WRT_LAST_FRAME = (1 << 29),
	AF_DISABLE_PHYSICAL_ACTIVATION = (1 << 30),
	AF_DISABLE_RELEASE_EVENTS = (1 << 31),
	//AF_0x70F38514 = 32, // ?
};
```