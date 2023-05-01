## Natives that use this enum
| Name                                            | Hash               |
|-------------------------------------------------|--------------------|
| PED::\_GET\_PED\_MOTIVATION                     | 0x42688E94E96FD9B4 |
| PED::\_SET\_PED\_MOTIVATION                     | 0x06D26A96CA1BCA75 |
| PED::\_GET\_IS\_PED\_MOTIVATION\_STATE\_ENABLED | 0x33FA048675821DA7 |
| PED::\_SET\_PED\_MOTIVATION\_STATE\_OVERRIDE    | 0x2EB75FB86C41F026 |
| PED::\_SET\_PED\_MOTIVATION\_MODIFIER           | 0xA1EB5D029E0191D3 |
## Enum
```cpp
enum PedMotivationState
{
	TOILET_STATE = 0,
	FEAR_STATE = 1,
	ANGRY_STATE = 2,
	AGITATION_STATE = 3,
	HUNGRY_STATE = 4,
	TIRED_STATE = 5,
	SAD_STATE = 6,
	BRAVE_STATE = 7,
	OFFER_ITEM_STATE = 8,
	SUSPICION = 9,
	DRUNK_STATE = 10,
};
```