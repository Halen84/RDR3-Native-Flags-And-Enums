## Natives that use this enum
| Name                                                  | Hash               |
|-------------------------------------------------------|--------------------|
| UIFEED::\_UI\_FEED\_GET\_MESSAGE\_STATE               | 0x59FA676177DBE4C9 |
| UISTICKYFEED::\_UI\_STICKY\_FEED\_GET\_MESSAGE\_STATE | 0x07954320D77F6A3D |
## Enum
```cpp
enum eUIMessageState
{
	kMessageState_Initializing = 0,
	kMessageState_InQueue = 1,
	kMessageState_WaitingToShow = 2,
	kMessageState_Entering = 3,
	kMessageState_Showing = 4,
	kMessageState_Exiting = 5,
	kMessageState_Complete = 6,
	kMessageState_Count = 7,
};
```
