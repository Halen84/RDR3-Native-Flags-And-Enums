## Natives that use this enum
| Name                                                       | Hash                |
|------------------------------------------------------------|---------------------|
| WEAPON::GIVE\_WEAPON\_TO\_PED                              | 0x5E3BDDBCB83F3D84  |
| WEAPON::GIVE\_WEAPON\_TO\_PED\_WITH\_OPTIONS               | 0xBE7E42B07FD317AC  |
| WEAPON::\_SET\_FORCE\_CURRENT\_WEAPON\_INTO\_COCKED\_STATE | 0x5230D3F6EE56CFE6  |
| WEAPON::SET\_CURRENT\_PED\_WEAPON                          | 0xADF692B254977C0C  |
| WEAPON::GET\_CURRENT\_PED\_WEAPON                          | 0x3A87E44BB9A01D54  |
| WEAPON::GET\_CURRENT\_PED\_WEAPON\_ENTITY\_INDEX           | 0x3B390A939AF0B5FC  |
| WEAPON::GET\_PED\_WEAPON\_GUID\_AT\_ATTACH\_POINT          | 0x6929E22158E52265  |
| WEAPON::\_SET\_PED\_WEAPON\_ATTACH\_POINT\_VISIBILITY      | 0x67E21ACC5C0C970C  |
| WEAPON::MAKE\_PED\_DROP\_WEAPON                            | 0xCEF4C65DE502D367  |
| WEAPON::\_GET\_WEAPON\_ATTACH\_POINT                       | 0xCAD4FE9398820D24  |
| PLAYER::\_0xCFFC3ECCD7A5CCEB                               | 0xCFFC3ECCD7A5CCEB  |
## Enum
```cpp
enum eWeaponAttachPoint
{
	WEAPON_ATTACH_POINT_INVALID = -1,
	WEAPON_ATTACH_POINT_HAND_PRIMARY = 0,
	WEAPON_ATTACH_POINT_HAND_SECONDARY = 1,
	WEAPON_ATTACH_POINT_PISTOL_R = 2,
	MAX_HAND_WEAPON_ATTACH_POINTS = 2,
	WEAPON_ATTACH_POINT_PISTOL_L = 3,
	WEAPON_ATTACH_POINT_KNIFE = 4,
	WEAPON_ATTACH_POINT_LASSO = 5,
	WEAPON_ATTACH_POINT_THROWER = 6,
	WEAPON_ATTACH_POINT_BOW = 7,
	WEAPON_ATTACH_POINT_BOW_ALTERNATE = 8,
	WEAPON_ATTACH_POINT_RIFLE = 9,
	WEAPON_ATTACH_POINT_RIFLE_ALTERNATE = 10,
	WEAPON_ATTACH_POINT_LANTERN = 11,
	WEAPON_ATTACH_POINT_TEMP_LANTERN = 12,
	WEAPON_ATTACH_POINT_MELEE = 13,
	MAX_SYNCED_WEAPON_ATTACH_POINTS = 13,
	WEAPON_ATTACH_POINT_HIP = 14,
	WEAPON_ATTACH_POINT_BOOT = 15,
	WEAPON_ATTACH_POINT_BACK = 16,
	WEAPON_ATTACH_POINT_FRONT = 17,
	WEAPON_ATTACH_POINT_SHOULDERSLING = 18,
	WEAPON_ATTACH_POINT_LEFTBREAST = 19,
	WEAPON_ATTACH_POINT_RIGHTBREAST = 20,
	WEAPON_ATTACH_POINT_LEFTARMPIT = 21,
	WEAPON_ATTACH_POINT_RIGHTARMPIT = 22,
	WEAPON_ATTACH_POINT_LEFTARMPIT_RIFLE = 23,
	WEAPON_ATTACH_POINT_SATCHEL = 24,
	WEAPON_ATTACH_POINT_LEFTARMPIT_BOW = 25,
	WEAPON_ATTACH_POINT_RIGHT_HAND_EXTRA = 26,
	WEAPON_ATTACH_POINT_LEFT_HAND_EXTRA = 27,
	WEAPON_ATTACH_POINT_RIGHT_HAND_AUX = 28,
	MAX_WEAPON_ATTACH_POINTS = 29,
};
```
