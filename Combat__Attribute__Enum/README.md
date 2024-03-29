## Natives that use this enum
| Name                               | Hash               |
|------------------------------------|--------------------|
| PED::SET\_PED\_COMBAT\_ATTRIBUTES  | 0x9F7794730795E019 |
| PED::\_GET\_PED\_COMBAT\_ATTRIBUTE | 0xCC2B20596E29E4E3 |
## Enum
```cpp
enum Combat__Attribute__Enum
{
	CA_USE_COVER = 0,
	CA_USE_VEHICLE = 1,
	CA_DO_DRIVEBYS = 2,
	CA_LEAVE_VEHICLES = 3,
	CA_STRAFE_BASED_ON_TARGET_PROXIMITY = 4,
	CA_ALWAYS_FIGHT = 5,
	CA_FLEE_WHILST_IN_VEHICLE = 6,
	CA_JUST_FOLLOW_VEHICLE = 7,
	CA_ALLOW_STRAFE_BREAKUP = 8,
	CA_WILL_SCAN_FOR_DEAD_PEDS = 9,
	CA_0x793BF941 = 10,
	CA_JUST_SEEK_COVER = 11,
	CA_BLIND_FIRE_IN_COVER = 12,
	CA_COVER_SEARCH_IN_ARC_AWAY_FROM_TARGET = 13,
	CA_CAN_INVESTIGATE = 14,
	CA_CAN_USE_RADIO = 15,
	CA_STRAFE_DUE_TO_BULLET_EVENTS = 16,
	CA_ALWAYS_FLEE = 17,
	CA_0x934F1825 = 18,
	CA_0x70F392F0 = 19,
	CA_CAN_TAUNT_IN_VEHICLE = 20,
	CA_CAN_CHASE_TARGET_ON_FOOT = 21,
	CA_WILL_DRAG_INJURED_PEDS_TO_SAFETY = 22,
	CA_0x42843828 = 23,
	CA_USE_PROXIMITY_FIRING_RATE = 24,
	CA_DISABLE_SECONDARY_TARGET = 25,
	CA_DISABLE_ENTRY_REACTIONS = 26,
	CA_PERFECT_ACCURACY = 27,
	CA_CAN_USE_FRUSTRATED_ADVANCE = 28,
	CA_MOVE_TO_LOCATION_BEFORE_COVER_SEARCH = 29,
	CA_CAN_SHOOT_WITHOUT_LOS = 30,
	CA_MAINTAIN_MIN_DISTANCE_TO_TARGET = 31,
	CA_0xBC6BB720 = 32,
	CA_0x8D3F251D = 33,
	CA_ALLOW_PROJECTILE_SWAPS_AFTER_REPEATED_THROWS = 34,
	CA_DISABLE_PINNED_DOWN = 35,
	CA_DISABLE_PIN_DOWN_OTHERS = 36,
	CA_OPEN_COMBAT_WHEN_DEFENSIVE_AREA_IS_REACHED = 37,
	CA_DISABLE_BULLET_REACTIONS = 38,
	CA_CAN_BUST = 39,
	CA_IGNORED_BY_OTHER_PEDS_WHEN_WANTED = 40,
	CA_CAN_COMMANDEER_VEHICLES = 41,
	CA_CAN_FLANK = 42,
	CA_SWITCH_TO_ADVANCE_IF_CANT_FIND_COVER = 43,
	CA_SWITCH_TO_DEFENSIVE_IF_IN_COVER = 44,
	CA_CLEAR_PRIMARY_DEFENSIVE_AREA_WHEN_REACHED = 45,
	CA_CAN_FIGHT_ARMED_PEDS_WHEN_NOT_ARMED = 46,
	CA_ENABLE_TACTICAL_POINTS_WHEN_DEFENSIVE = 47,
	CA_DISABLE_COVER_ARC_ADJUSTMENTS = 48,
	CA_USE_ENEMY_ACCURACY_SCALING = 49,
	CA_CAN_CHARGE = 50,
	CA_REMOVE_AREA_SET_WILL_ADVANCE_WHEN_DEFENSIVE_AREA_REACHED = 51,
	CA_USE_VEHICLE_ATTACK = 52,
	CA_USE_VEHICLE_ATTACK_IF_VEHICLE_HAS_MOUNTED_GUNS = 53,
	CA_ALWAYS_EQUIP_BEST_WEAPON = 54,
	CA_CAN_SEE_UNDERWATER_PEDS = 55,
	CA_DISABLE_AIM_AT_AI_TARGETS_IN_HELIS = 56,
	CA_DISABLE_SEEK_DUE_TO_LINE_OF_SIGHT = 57,
	CA_DISABLE_FLEE_FROM_COMBAT = 58,
	CA_DISABLE_TARGET_CHANGES_DURING_VEHICLE_PURSUIT = 59,
	CA_CAN_THROW_SMOKE_GRENADE = 60,
	CA_UNUSED6 = 61,
	CA_CLEAR_AREA_SET_DEFENSIVE_IF_DEFENSIVE_CANNOT_BE_REACHED = 62,
	CA_UNUSED7 = 63,
	CA_DISABLE_BLOCK_FROM_PURSUE_DURING_VEHICLE_CHASE = 64,
	CA_DISABLE_SPIN_OUT_DURING_VEHICLE_CHASE = 65,
	CA_DISABLE_CRUISE_IN_FRONT_DURING_BLOCK_DURING_VEHICLE_CHASE = 66,
	CA_CAN_IGNORE_BLOCKED_LOS_WEIGHTING = 67,
	CA_DISABLE_REACT_TO_BUDDY_SHOT = 68,
	CA_PREFER_NAVMESH_DURING_VEHICLE_CHASE = 69,
	CA_ALLOWED_TO_AVOID_OFFROAD_DURING_VEHICLE_CHASE = 70,
	CA_PERMIT_CHARGE_BEYOND_DEFENSIVE_AREA = 71,
	CA_USE_ROCKETS_AGAINST_VEHICLES_ONLY = 72,
	CA_DISABLE_TACTICAL_POINTS_WITHOUT_CLEAR_LOS = 73,
	CA_DISABLE_PULL_ALONGSIDE_DURING_VEHICLE_CHASE = 74,
	CA_0xB53C7137 = 75,
	CA_UNUSED8 = 76,
	CA_DISABLE_RESPONDED_TO_THREAT_BROADCAST = 77,
	CA_DISABLE_ALL_RANDOMS_FLEE = 78,
	CA_WILL_GENERATE_DEAD_PED_SEEN_SCRIPT_EVENTS = 79,
	CA_UNUSED9 = 80,
	CA_FORCE_STRAFE = 81,
	CA_UNUSED10 = 82,
	CA_0x2060C16F = 83,
	CA_0x98669E6C = 84,
	CA_0x6E44A6F2 = 85,
	CA_0xC6A191DB = 86,
	CA_0x57C8EF37 = 87,
	CA_0xA265A9FC = 88,
	CA_0xE3FA8ABB = 89,
	CA_0x9AA00F0F = 90,
	CA_USE_RANGE_BASED_WEAPON_SELECTION = 91,
	CA_0x8AF8D68D = 92,
	CA_PREFER_MELEE = 93,
	CA_UNUSED11 = 94,
	CA_UNUSED12 = 95,
	CA_0x64BBB208 = 96,
	CA_0x625F4C52 = 97,
	CA_0x945B1F0C = 98,
	CA_UNUSED13 = 99,
	CA_UNUSED14 = 100,
	CA_RESTRICT_IN_VEHICLE_AIMING_TO_CURRENT_SIDE = 101,
	CA_UNUSED15 = 102,
	CA_UNUSED16 = 103,
	CA_UNUSED17 = 104,
	CA_CAN_CRUISE_AND_BLOCK_IN_VEHICLE = 105,
	CA_PREFER_AIR_COMBAT_WHEN_IN_AIRCRAFT = 106,
	CA_ALLOW_DOG_FIGHTING = 107,
	CA_PREFER_NON_AIRCRAFT_TARGETS = 108,
	CA_PREFER_KNOWN_TARGETS_WHEN_COMBAT_CLOSEST_TARGET = 109,
	CA_0x875B82F3 = 110,
	CA_0x1CB77C49 = 111,
	CA_0x8EB01547 = 112,
	CA_USE_INFINITE_CLIPS = 113,
	CA_CAN_EXECUTE_TARGET = 114,
	CA_DISABLE_RETREAT_DUE_TO_TARGET_PROXIMITY = 115,
	CA_PREFER_DUAL_WIELD = 116,
	CA_WILL_CUT_FREE_HOGTIED_PEDS = 117,
	CA_TRY_TO_FORCE_SURRENDER = 118,
	CA_0x0136E7B6 = 119,
	CA_0x797D7A1A = 120,
	CA_0x97B4A6E4 = 121,
	CA_0x1FAAD7AF = 122,
	CA_0x492B880F = 123,
	CA_0xBE151581 = 124,
	CA_QUIT_WHEN_TARGET_FLEES_INTERACTION_FIGHT = 125,
	CA_0xAC5E5497 = 126,
	CA_0xE300164C = 127,
	CA_0xC82D4787 = 128,
	CA_0x31E0808F = 129,
	CA_0x0A9A7130 = 130,
	CA_PREVENT_UNSAFE_PROJECTILE_THROWS = 131,
	CA_0xA55AD510 = 132,
	CA_DISABLE_BLANK_SHOTS = 133,
	CA_0xA78BB3BD = 134,
};
```
