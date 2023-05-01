## Natives that use this enum
```
ANIMSCENE::_CREATE_ANIM_SCENE (0x1FCA98E33C1437B3)
```
## Enum
```cpp
enum eAnimSceneFlag
{
	ASF_NONE = 0,
	ASF_LOOPING = (1 << 0),
	ASF_HOLD_AT_END = (1 << 1),
	ASF_AUTO_START_WHEN_LOADED = (1 << 2),
	ASF_BLOCK_TIME_SLICING = (1 << 3),
	ASF_ENABLE_RESUME_FROM_LAST_CHECKPOINT = (1 << 4),
	ASF_ABORT_SCENE_ON_REQUIRED_ENTITY_REMOVAL = (1 << 5),
	ASF_ADAPT_TO_TERRAIN = (1 << 6),
	ASF_FORCE_DISPLAY_IN_DEBUG_BAR = (1 << 7),
	ASF_BLOCK_SKIPPING = (1 << 8),
	ASF_ALLOW_LARGE_IMPACT_BREAKOUTS = (1 << 9),
	ASF_PREVENT_IGNORING_COLLISION_WITH_PARENT = (1 << 10),
	ASF_ENABLE_LETTER_BOX = (1 << 11),
	ASF_DISABLE_SCREEN_EVENTS_IF_NO_PLAYER = (1 << 12),
	ASF_PRESERVE_CAMERA_ON_PLAYER_REMOVAL = (1 << 13),
	ASF_MP_FORCE_SCREEN_EVENTS_IF_NO_PLAYER = (1 << 14),
	ASF_MP_RESTRICT_SCOPE_TO_SCRIPT_PARTICIPANTS = (1 << 15)
};
```