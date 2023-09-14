## Natives that use this enum
| Name                                   | Hash               |
|----------------------------------------|--------------------|
| OBJECT::DOOR\_SYSTEM\_SET\_DOOR\_STATE | 0x6BAB9442830C7F53 |
| OBJECT::DOOR\_SYSTEM\_GET\_DOOR\_STATE | 0x160AA1B32F6139B8 |
## Enum
```cpp
enum DoorScriptState
{
	DOORSTATE_INVALID = -1,
	DOORSTATE_UNLOCKED = 0,
	DOORSTATE_LOCKED_UNBREAKABLE = 1,
	DOORSTATE_LOCKED_BREAKABLE = 2,
	DOORSTATE_NUM = 3,
};
```
