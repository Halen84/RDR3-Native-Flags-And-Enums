## Natives that use this enum
```
UIFEED::UI_FEED_CLEAR_CHANNEL (0xDD1232B332CBB9E7)
UIFEED::UI_FEED_GET_CURRENT_MESSAGE (0xC17F69E1418CD11F)
UIFEED::_UI_FEED_GET_MESSAGE_STATE (0x59FA676177DBE4C9)
```
## Enum
```cpp
enum eUIFeedChannel
{
	kFeedChannel_Invalid = 0,
	kFeedChannel_Help = 1,
	kFeedChannel_Location = 2,
	kFeedChannel_Objective = 3,
	kFeedChannel_Subtitle = 4,
	kFeedChannel_Ticker = 5,
	kFeedChannel_Toast = 6,
	kFeedChannel_Isolated = 7,
	kFeedChannel_Transportation = 8,
	kFeedChannel_MissionName = 9,
	kFeedChannel_ReticleMessage = 10,
	kFeedChannel_Shards = 11,
	kFeedChannel_ScoretimerMessage = 12,
	kFeedChannel_VoiceChat = 13,
	kFeedChannel_Count = 14,
};
```