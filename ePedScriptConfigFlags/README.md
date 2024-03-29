## Natives that use this enum
| Name                        | Hash               |
|-----------------------------|--------------------|
| PED::SET\_PED\_CONFIG\_FLAG | 0x1913FE4CBF41C463 |
| PED::GET\_PED\_CONFIG\_FLAG | 0x7EE53118C892B513 |
## Enum
```cpp
enum ePedScriptConfigFlags
{
	PCF_AllowMedicsToAttend = 0,
	PCF_0x24B45566 = 1,
	PCF_DontAllowToBeDraggedOutOfVehicle = 2,
	PCF_GetOutUndriveableVehicle = 3,
	PCF_HasBounty = 4,
	PCF_WillFlyThroughWindscreen = 5,
	PCF_DontInfluenceWantedLevel = 6,
	PCF_DisableLockonToRandomPeds = 7,
	PCF_AllowLockonToFriendlyPlayers = 8,
	PCF_KilledByStealth = 9,
	PCF_KilledByTakedown = 10,
	PCF_Knockedout = 11,
	PCF_IsAimingGun = 12,
	PCF_ForcedAim = 13,
	PCF_OpenDoorArmIK = 14,
	PCF_DontActivateRagdollFromVehicleImpact = 15,
	PCF_DontActivateRagdollFromBulletImpact = 16,
	PCF_DontActivateRagdollFromExplosions = 17,
	PCF_DontActivateRagdollFromFire = 18,
	PCF_DontActivateRagdollFromElectrocution = 19,
	PCF_KeepWeaponHolsteredUnlessFired = 20,
	PCF_ForceControlledKnockout = 21,
	PCF_FallsOutOfVehicleWhenKilled = 22,
	PCF_GetOutBurningVehicle = 23,
	PCF_RunFromFiresAndExplosions = 24,
	PCF_TreatAsPlayerDuringTargeting = 25,
	PCF_DisableMelee = 26,
	PCF_DisableUnarmedDrivebys = 27,
	PCF_JustGetsPulledOutWhenElectrocuted = 28,
	PCF_DisableMeleeHitReactions = 29,
	PCF_WillNotHotwireLawEnforcementVehicle = 30,
	PCF_WillCommandeerRatherThanJack = 31,
	PCF_ForcePedToFaceLeftInCover = 32,
	PCF_ForcePedToFaceRightInCover = 33,
	PCF_BlockPedFromTurningInCover = 34,
	PCF_KeepRelationshipGroupAfterCleanUp = 35,
	PCF_ForcePedToBeDragged = 36,
	PCF_PreventPedFromReactingToBeingJacked = 37,
	PCF_RemoveDeadExtraFarAway = 38,
	PCF_ArrestResult = 39,
	PCF_CanAttackFriendly = 40,
	PCF_WillJackAnyPlayer = 41,
	PCF_WillJackWantedPlayersRatherThanStealCar = 42,
	PCF_DisableLadderClimbing = 43,
	PCF_CowerInsteadOfFlee = 44,
	PCF_CanActivateRagdollWhenVehicleUpsideDown = 45,
	PCF_AlwaysRespondToCriesForHelp = 46,
	PCF_DisableBloodPoolCreation = 47,
	PCF_ShouldFixIfNoCollision = 48,
	PCF_CanPerformArrest = 49,
	PCF_CanPerformUncuff = 50,
	PCF_CanBeArrested = 51,
	PCF_PlayerPreferFrontSeatMP = 52,
	PCF_DontEnterVehiclesInPlayersGroup = 53,
	PCF_PreventAllMeleeTaunts = 54,
	PCF_ForceDirectEntry = 55,
	PCF_AlwaysSeeApproachingVehicles = 56,
	PCF_CanDiveAwayFromApproachingVehicles = 57,
	PCF_AllowPlayerToInterruptVehicleEntryExit = 58,
	PCF_OnlyAttackLawIfPlayerIsWanted = 59,
	PCF_PedsJackingMeDontGetIn = 60,
	PCF_PedIgnoresAnimInterruptEvents = 61,
	PCF_IsInCustody = 62,
	PCF_ForceStandardBumpReactionThresholds = 63,
	PCF_LawWillOnlyAttackIfPlayerIsWanted = 64,
	PCF_PreventAutoShuffleToDriversSeat = 65,
	PCF_UseKinematicModeWhenStationary = 66,
	PCF_PlayerIsWeird = 67,
	PCF_DoNothingWhenOnFootByDefault = 68,
	PCF_DontReactivateRagdollOnPedCollisionWhenDead = 69,
	PCF_DontActivateRagdollOnVehicleCollisionWhenDead = 70,
	PCF_HasBeenInArmedCombat = 71,
	PCF_Avoidance_Ignore_All = 72,
	PCF_Avoidance_Ignored_by_All = 73,
	PCF_Avoidance_Ignore_Group1 = 74,
	PCF_Avoidance_Member_of_Group1 = 75,
	PCF_ForcedToUseSpecificGroupSeatIndex = 76,
	PCF_DisableExplosionReactions = 77,
	PCF_WaitingForPlayerControlInterrupt = 78,
	PCF_ForcedToStayInCover = 79,
	PCF_GeneratesSoundEvents = 80,
	PCF_0x5BE341F1 = 81, // PCF_[K-L]*
	PCF_AllowToBeTargetedInAVehicle = 82,
	PCF_WaitForDirectEntryPointToBeFreeWhenExiting = 83,
	PCF_OnlyRequireOnePressToExitVehicle = 84,
	PCF_ForceExitToSkyDive = 85,
	PCF_DisableExitToSkyDive = 86,
	PCF_DisablePedAvoidance = 87,
	PCF_0x4BF2D721 = 88,
	PCF_DisablePanicInVehicle = 89,
	PCF_AllowedToDetachTrailer = 90,
	PCF_ForceSkinCharacterCloth = 91,
	PCF_LeaveEngineOnWhenExitingVehicles = 92,
	PCF_PhoneDisableTextingAnimations = 93,
	PCF_PhoneDisableTalkingAnimations = 94,
	PCF_PhoneDisableCameraAnimations = 95,
	PCF_DisableBlindFiringInShotReactions = 96,
	PCF_AllowNearbyCoverUsage = 97,
	PCF_CanAttackNonWantedPlayerAsLaw = 98,
	PCF_WillTakeDamageWhenVehicleCrashes = 99,
	PCF_AICanDrivePlayerAsRearPassenger = 100,
	PCF_PlayerCanJackFriendlyPlayers = 101,
	PCF_AIDriverAllowFriendlyPassengerSeatEntry = 102,
	PCF_AllowMissionPedToUseInjuredMovement = 103,
	PCF_PreventUsingLowerPrioritySeats = 104,
	PCF_TeleportToLeaderVehicle = 105,
	PCF_Avoidance_Ignore_WeirdPedBuffer = 106,
	PCF_DontBlipCop = 107,
	PCF_KillWhenTrapped = 108,
	PCF_AvoidTearGas = 109,
	PCF_OnlyUseForcedSeatWhenEnteringHeliInGroup = 110,
	PCF_DisableWeirdPedEvents = 111,
	PCF_ShouldChargeNow = 112,
	PCF_DisableShockingEvents = 113,
	PCF_0x38D6E079 = 114,
	PCF_DisableShockingDrivingOnPavementEvents = 115,
	PCF_ShouldThrowSmokeGrenadeNow = 116,
	PCF_ForceInitialPeekInCover = 117,
	PCF_DisableJumpingFromVehiclesAfterLeader = 118,
	PCF_ShoutToGroupOnPlayerMelee = 119,
	PCF_IgnoredByAutoOpenDoors = 120,
	PCF_ForceIgnoreMeleeActiveCombatant = 121,
	PCF_CheckLoSForSoundEvents = 122,
	PCF_CanSayFollowedByPlayerAudio = 123,
	PCF_ActivateRagdollFromMinorPlayerContact = 124,
	PCF_ForcePoseCharacterCloth = 125,
	PCF_HasClothCollisionBounds = 126,
	PCF_DontBehaveLikeLaw = 127,
	PCF_DisablePoliceInvestigatingBody = 128,
	PCF_LowerPriorityOfWarpSeats = 129,
	PCF_DisableTalkTo = 130,
	PCF_DontBlip = 131,
	PCF_IgnoreLegIkRestrictions = 132,
	PCF_ForceNoTimesliceIntelligenceUpdate = 133,
	PCF_0x36E3CAE1 = 134,
	PCF_NotAllowedToJackAnyPlayers = 135,
	PCF_CannotBeMounted = 136,
	PCF_CannotBeTakenDown = 137,
	PCF_OneShotWillKillPed = 138,
	PCF_0xF6076F5C = 139,
	PCF_IsDraftAnimal = 140,
	PCF_DisablePlayerAutoHolster = 141,
	PCF_0x8B989605 = 142,
	PCF_0x9239BD41 = 143,
	PCF_DisableHorseMPAutoFlee = 144,
	PCF_EnableHorseMPAutoFleeInSP = 145,
	PCF_CantWitnessCrimes = 146,
	PCF_0xDB25067C = 147, // PCF_Disable*
	PCF_0x0DD984BE = 148,
	PCF_0x1A4C248B = 149, // PCF_Allow*
	PCF_ForceBleeding = 150,
	PCF_0xB11C76E8 = 151,
	PCF_0x79114A20 = 152,
	PCF_0x23E3351E = 153,
	PCF_UseFollowLeaderThreatResponse = 154,
	PCF_EnableCompanionAIAnalysis = 155,
	PCF_EnableCompanionAISupport = 156,
	PCF_DisableCompanionDragging = 157,
	PCF_RequestStealthMovement = 158,
	PCF_0xF95CE6DA = 159,
	PCF_DisableDragDamage = 160,
	PCF_IsWhistling = 161,
	PCF_AlwaysLeaveTrainUponArrival = 162,
	PCF_UseSloMoBloodVfx = 163,
	PCF_0x10E66933 = 164,
	PCF_0x63DA4710 = 165,
	PCF_DontTeleportWithGroup = 166,
	PCF_ShouldBeOnMount = 167,
	PCF_EnableShockingEvents = 168,
	PCF_DisableGrappleByPlayer = 169,
	PCF_DisableGrappleByAi = 170,
	PCF_0x6868B572 = 171,
	PCF_ForceDeepSurfaceCheck = 172,
	PCF_0xE0892826 = 173,
	PCF_DisableEvasiveStep = 174,
	PCF_SwappingReins = 175,
	PCF_EnableAllyRevive = 176,
	PCF_EnableEvasiveScanner = 177,
	PCF_AllowNonTempExceptionEvents = 178,
	PCF_0x605C7288 = 179,
	PCF_PreventDraggedOutOfCarThreatResponse = 180,
	PCF_DisableDeepSurfaceAnims = 181,
	PCF_DontBlipNotSynced = 182,
	PCF_IsDuckingInVehicle = 183,
	PCF_PreventAutoShuffleToTurretSeat = 184,
	PCF_DisableEventInteriorStatusCheck = 185,
	PCF_CorpseIsPersistent = 186,
	PCF_ForceMeleeDamage = 187,
	PCF_0x66114902 = 188,
	PCF_0xB94900F7 = 189, // PCF_[D-E]*
	PCF_0x405A7A35 = 190,
	PCF_0x497EDECE = 191,
	PCF_DisableShootingAt = 192,
	PCF_0x87C5E494 = 193,
	PCF_ShouldPedFollowersIgnoreWaypointMBR = 194,
	PCF_0x308D5751 = 195,
	PCF_0xE821E96B = 196,
	PCF_0xBE339BF1 = 197,
	PCF_0x8590C200 = 198,
	PCF_0x9C65B372 = 199,
	PCF_BroadcastRepondedToThreatWhenGoingToPointShooting = 200,
	PCF_0x11CB5DCC = 201,
	PCF_0x88F47BBF = 202,
	PCF_0x11D9FB08 = 203,
	PCF_0x435F091E = 204,
	PCF_0x34D49B13 = 205,
	PCF_0xB78E3FC8 = 206,
	PCF_FlamingHoovesActive = 207,
	PCF_0x010FB89C = 208,
	PCF_0xC44343FA = 209,
	PCF_0xCEBE76AE = 210,
	PCF_GiveAmbientDefaultTaskIfMissionPed = 211,
	PCF_0x9C8397DB = 212,
	PCF_DisableCounterAttacks = 213,
	PCF_0x3B611ABF = 214, // PCF_C*
	PCF_0xBFC10292 = 215,
	PCF_DontConfrontCriminal = 216,
	PCF_SupressShockingEvents = 217,
	PCF_DisablePickups = 218,
	PCF_0x30675AE3 = 219,
	PCF_0x81BE4E79 = 220,
	PCF_0x5F20A08D = 221,
	PCF_EnableIntimidationDragging = 222,
	PCF_IsCriticalCorpse = 223,
	PCF_DisableMeleeTargetSwitch = 224,
	PCF_0x0C5FB46A = 225, // PCF_[P-R]*
	PCF_DisableAIWeaponBlocking = 226,
	PCF_0x43176C67 = 227,
	PCF_0x5752DFD6 = 228,
	PCF_0xC8249A24 = 229,
	PCF_KeepTasksAfterCleanUp = 230,
	PCF_AllowMinorReactionsAsMissionPed = 231,
	PCF_ForceDieInCar = 232,
	PCF_PedIsEnemyToPlayer = 233,
	PCF_NeverDoScenarioExitProbeChecks = 234,
	PCF_NeverDoScenarioNavChecks = 235,
	PCF_ForceSynchronousScenarioExitChecking = 236,
	PCF_ForcePlayNormalScenarioExitOnNextScriptCommand = 237,
	PCF_ForcePlayImmediateScenarioExitOnNextScriptCommand = 238,
	PCF_ForcePlayFleeScenarioExitOnNextScriptCommand = 239,
	PCF_0xC0C73A04 = 240,
	PCF_0x6DEDF3DE = 241,
	PCF_0x59BEF34E = 242,
	PCF_BlockDeadBodyShockingEventsWhenDead = 243,
	PCF_DontAttackPlayerWithoutWantedLevel = 244,
	PCF_DontActivateRagdollFromAnyPedImpact = 245,
	PCF_ForcePedLoadCover = 246,
	PCF_BlockCoweringInCover = 247,
	PCF_BlockPeekingInCover = 248,
	PCF_BlockWeaponSwitching = 249,
	PCF_StopWeaponFiringOnImpact = 250,
	PCF_0x946BACEC = 251,
	PCF_SteerAroundDeadBodies = 252,
	PCF_0x132E88AD = 253, // PCF_C*
	PCF_0x17B799AE = 254,
	PCF_SteersAroundPeds = 255,
	PCF_SteersAroundVehicles = 256,
	PCF_BlocksPathingWhenDead = 257,
	PCF_0x96AA3A9B = 258,
	PCF_CanAmbientHeadtrack = 259,
	PCF_IsScuba = 260,
	PCF_ResetLastVehicleOnVehicleExit = 261,
	PCF_AllowPedInVehiclesOverrideTaskFlags = 262,
	PCF_NoCriticalHits = 263,
	PCF_UpperBodyDamageAnimsOnly = 264,
	PCF_DrownsInWater = 265,
	PCF_DiesInstantlyWhenSwimming = 266,
	PCF_DrownsInSinkingVehicle = 267,
	PCF_DisableWeaponBlocking = 268,
	PCF_StayInCarOnJack = 269,
	PCF_CanBeShotInVehicle = 270,
	PCF_SuppressLowLODRagdollSwitchWhenCorpseSettles = 271,
	PCF_TreatAsAmbientPedForDriverLockOn = 272,
	PCF_NeverEverTargetThisPed = 273,
	PCF_AllowPlayerLockOnIfFriendly = 274,
	PCF_UseCameraHeadingForDesiredDirectionLockOnTest = 275,
	PCF_TargettableWithNoLos = 276,
	PCF_0x5FE313B3 = 277, // PCF_Disable*
	PCF_0xB0D28E2E = 278, // PCF_[C-D]*
	PCF_NeverLeavesGroup = 279,
	PCF_DontEnterLeadersVehicle = 280,
	PCF_BlockGroupPedAimedAtResponse = 281,
	PCF_WillRemainOnBoatAfterMissionEnds = 282,
	PCF_DisableInjuredRiderResponse = 283,
	PCF_0x9C118A4B = 284, // PCF_Block*
	PCF_ForcePlayDirectedNormalScenarioExitOnNextScriptCommand = 285,
	PCF_DisableEvasiveDives = 286,
	PCF_AllowMissionDriverlessDraftAnimalResponse = 287,
	PCF_0x4B822D03 = 288,
	PCF_TreatDislikeAsHateWhenInCombat = 289,
	PCF_TreatNonFriendlyAsHateWhenInCombat = 290,
	PCF_CanPlayInCarIdles = 291,
	PCF_0xA5E8F092 = 292,
	PCF_0x40EB5604 = 293,
	PCF_DisableDriverlessDraftAnimalResponse = 294,
	PCF_DisableInTrafficAvoidance = 295,
	PCF_DisableAllAvoidance = 296,
	PCF_ForceInteractionLockonOnTargetPed = 297,
	PCF_0x58C8629F = 298,
	PCF_0x7BE8B923 = 299,
	PCF_DisablePlayerHorseLeading = 300,
	PCF_DisableInteractionLockonOnTargetPed = 301,
	PCF_DisableMeleeKnockout = 302,
	PCF_0x5CBBBA25 = 303,
	PCF_0x8D86008F = 304,
	PCF_DisableHeadGore = 305,
	PCF_DisableLimbGore = 306,
	PCF_DisableMountSpawning = 307,
	PCF_AllowILOWithWeapon = 308,
	PCF_0x4885CFA9 = 309, // PCF_[P-R]*
	PCF_CanBeLassoedByFriendlyPlayers = 310,
	PCF_0x1C112278 = 311,
	PCF_DisableHorseGunshotFleeResponse = 312,
	PCF_DontFindTransportToFollowLeader = 313,
	PCF_ForceHogtieOfUnconciousPedToCarryAround = 314,
	PCF_0xD38AEF95 = 315, // PCF_[G-I]*
	PCF_DontStopForTrains = 316,
	PCF_0x8E385F10 = 317,
	PCF_PreventScavengers = 318,
	PCF_EnableAsVehicleTransitionDestination = 319,
	PCF_0x743C18A9 = 320,
	PCF_0x4325A091 = 321,
	PCF_0x95B6BA5B = 322,
	PCF_UseRacingLines = 323,
	PCF_0x8D1AEDEF = 324,
	PCF_0xC0CCD94A = 325,
	PCF_0x4938756F = 326,
	PCF_0x6E6BF9A7 = 327,
	PCF_0x5E9A5F16 = 328,
	PCF_0xD8D066F2 = 329,
	PCF_0x7C7AF264 = 330, // PCF_Disable*
	PCF_0x9663C8F2 = 331, // PCF_[G-I]*
	PCF_IsInStationaryScenario = 332,
	PCF_0x27394ECA = 333,
	PCF_0x23029D96 = 334,
	PCF_0x381A643F = 335,
	PCF_ForceInjuredMovement = 336,
	PCF_DontExitVehicleIfNoDraftAnimals = 337,
	PCF_0xEEA5619C = 338,
	PCF_0x9E57DC18 = 339,
	PCF_DisableAllMeleeTakedowns = 340,
	PCF_ForceDismountLeft = 341,
	PCF_ForceDismountRight = 342,
	PCF_0x8FD863AF = 343,
	PCF_0x345B8591 = 344,
	PCF_0xE64EEB72 = 345,
	PCF_0x0CA2A010 = 346,
	PCF_IsSanctionedShooter = 347,
	PCF_0x3ED9A585 = 348,
	PCF_0x072C1C6D = 349,
	PCF_0x88BDD64C = 350,
	PCF_DisableIntimidationBackingAway = 351,
	PCF_0x93AB4714 = 352,
	PCF_0xA662EDB3 = 353,
	PCF_0x28CBCEC7 = 354,
	PCF_0xEEBAF435 = 355,
	PCF_BlockRobberyInteractionEscape = 356,
	PCF_0xA983D113 = 357,
	PCF_0x61EA3683 = 358,
	PCF_AllowInCombatInteractionLockonOnTargetPed = 359,
	PCF_0xF8AF9E5C = 360,
	PCF_IgnoreWeaponDegradation = 361,
	PCF_0xC92D591B = 362,
	PCF_0x51801A92 = 363,
	PCF_0x8B88F526 = 364,
	PCF_0x0E185496 = 365,
	PCF_DisableVehicleTransitions = 366,
	PCF_0x0E3CB695 = 367,
	PCF_0x696695E0 = 368,
	PCF_0x58D4CF33 = 369,
	PCF_DisableDeadEyeTagging = 370,
	PCF_0xAB673A85 = 371,
	PCF_0xDCB2DCC0 = 372,
	PCF_AllowSlipstream = 373,
	PCF_0x2E58B068 = 374,
	PCF_0x121018F9 = 375,
	PCF_0xDFA8EBA4 = 376,
	PCF_0x7E01056D = 377,
	PCF_0x42736B4A = 378,
	PCF_0x5213A517 = 379,
	PCF_0xE68FAAFB = 380,
	PCF_0x248CF998 = 381,
	PCF_0xCA56246D = 382,
	PCF_0xB65C7C8B = 383,
	PCF_0x00888CD6 = 384,
	PCF_0x6B749DC5 = 385,
	PCF_0x03AA190E = 386,
	PCF_0x913B0D20 = 387,
	PCF_DisableFatallyWoundedBehaviour = 388,
	PCF_0xB80AFE95 = 389,
	PCF_0xF8276C9A = 390,
	PCF_0x0E7F44B9 = 391,
	PCF_0x2255F330 = 392,
	PCF_0x96B7B497 = 393,
	PCF_DisableInteractionWithAnimals = 394,
	PCF_0x665CE445 = 395,
	PCF_0x29BBB477 = 396,
	PCF_DisableStuckResponse = 397,
	PCF_0x1E1E8BA7 = 398, // PCF_[B-C]*
	PCF_0x3A95125A = 399,
	PCF_0x3EECBCF6 = 400,
	PCF_0x198B5351 = 401,
	PCF_0xCA2DF96D = 402,
	PCF_0x21ADF5CB = 403,
	PCF_0x0E674773 = 404,
	PCF_0xCEAE53FA = 405,
	PCF_ForceOfferItemOnReceivingRobberyInteraction = 406,
	PCF_0x0F79BB17 = 407,
	PCF_IsPerformingEmote = 408,
	PCF_IsPerformingWeaponEmote = 409,
	PCF_0x4AFE2C68 = 410,
	PCF_0xBB887117 = 411,
	PCF_BlockHorsePromptsForTargetPed = 412,
	PCF_0xD291BB15 = 413,
	PCF_0x7B05BE6D = 414,
	PCF_0x3FA067F1 = 415,
	PCF_StealthCoverEnter = 416,
	PCF_DisableEagleEyeHighlight = 417,
	PCF_0xC8ACAA6C = 418,
	PCF_BlockMountHorsePrompt = 419,
	PCF_IsKickingDoor = 420,
	PCF_AllowDoorBargingUnderCombat = 421,
	PCF_0x3AB3C6E2 = 422,
	PCF_0x86C10CF4 = 423,
	PCF_0x4F63DCAE = 424,
	PCF_0x08F50AC5 = 425,
	PCF_0x7BA0E975 = 426,
	PCF_DisableDrunkDecay = 427,
	PCF_0xC0ACCB2D = 428,
	PCF_KnockOutDuringHogtie = 429,
	PCF_0x0B237FF1 = 430,
	PCF_0xA5CB7C09 = 431,
	PCF_DisableGaitReduction = 432,
	PCF_0x785D4043 = 433,
	PCF_0x41EB527E = 434,
	PCF_AlwaysRejectPlayerRobberyAttempt = 435,
	PCF_0x553A6EF0 = 436,
	PCF_DisableWeatherConditionPerceptionChecks = 437,
	_PCF_SetHorseFleeCommandDisabled = 438, // PCF_0x14013CF9
	_PCF_SetHorseStayCommandDisabled = 439, // PCF_0x8519377E
	_PCF_SetHorseFollowCommandDisabled = 440, // PCF_0xDBD31C9C
	PCF_0xB61CE793 = 441,
	_PCF_DisableHorseFleeILO = 442, // PCF_0x78525B66
	PCF_0x9F42C50C = 443,
	PCF_0x16A14D9A = 444,
	PCF_DisableDoorBarge = 445,
	PCF_DisableDoorInteractionTask = 446,
	PCF_0xA1040728 = 447,
	PCF_TreatAsMissionPopTypeForSpeech = 448,
	PCF_0x5CD355BD = 449,
	PCF_0xA82B421F = 450,
	PCF_HorseDontEvaluateRiderForDamageChecks = 451,
	PCF_0x9909D028 = 452,
	PCF_0x43429291 = 453,
	PCF_0x089C3B7F = 454,
	PCF_0xBB0F2E64 = 455,
	PCF_ForcePedKnockOut = 456,
	PCF_0xD5AB81E2 = 457,
	PCF_0xFD170B10 = 458,
	PCF_0xCD4DCBEC = 459,
	PCF_ForceWitnessIntimidationOnNextInteraction = 460,
	PCF_0xD09EEF14 = 461,
	PCF_0xC3BB03BA = 462,
	PCF_0xC2322EDE = 463,
	PCF_0x219138E7 = 464,
	PCF_0x873F6A00 = 465,
	PCF_0xA9C6E67F = 466,
	PCF_DisableHonorModifiers = 467,
	PCF_0xC6540731 = 468,
	PCF_0x5A314A89 = 469,
	PCF_0x691431BD = 470,
	PCF_DisableHorseKick = 471,
	PCF_DisableSittingScenarios = 472,
	PCF_DisableAutoSittingScenarios = 473,
	PCF_DisableRestingScenarios = 474,
	PCF_DisableAutoRestingScenarios = 475,
	PCF_RejectTrafficCalloutDisputes = 476,
	PCF_CanInteractWithPlayerEvenIfInputsDisabled = 477,
	PCF_0x957D269D = 478,
	PCF_0x9BF41BF2 = 479,
	PCF_0xC78D54C4 = 480,
	PCF_0x6DEA76B1 = 481,
	PCF_0xC7A80079 = 482,
	PCF_0xED575704 = 483,
	PCF_0x154BFF03 = 484,
	PCF_0xB40114AF = 485,
	PCF_0x6A84551F = 486,
	PCF_0x2621982A = 487,
	PCF_DiesInstantlyToMeleeFromAnimals = 488,
	PCF_0xF9EE4C8A = 489,
	PCF_0xF2A1A360 = 490,
	PCF_0xDB937F2C = 491,
	PCF_0x391CCB82 = 492,
	PCF_0xA58B6703 = 493,
	PCF_0x5BD8B9DC = 494,
	PCF_0xF8CF513A = 495,
	PCF_0x110F10D1 = 496,
	PCF_0x0FB07F5A = 497,
	PCF_0xC79F7785 = 498,
	PCF_BlockWhistleEvents = 499,
	PCF_0xC9CCA1E4 = 500,
	PCF_0x5F75066E = 501,
	PCF_0x5B64E56A = 502,
	PCF_DisableSpecialGreetChains = 503,
	PCF_0x253C4B25 = 504,
	PCF_AllowRobberyWhenInjured = 505,
	PCF_RunToTransport = 506,
	PCF_0xE98C1598 = 507,
	PCF_0x66B3CA93 = 508,
	PCF_0xE1B40374 = 509,
	PCF_DisableConfrontCriminalTowardsThisPed = 510,
	PCF_0xFF691D47 = 511,
	PCF_0xA91A8F5D = 512,
	PCF_0x07221A26 = 513,
	PCF_DisableFriendlyAmbientAnimalFollowing = 514,
	PCF_DisableReloadMultiplier = 515,
	PCF_0x6C3E1067 = 516,
	PCF_AllowPersistenceOverride = 517,
	PCF_DisableWalkAway = 518,
	PCF_0xE6AC71E1 = 519,
	PCF_0x43C121FD = 520,
	PCF_0x8186B12C = 521,
	PCF_DontFleeFromDroppedAnimals = 522,
	PCF_0x9D56AF0A = 523,
	PCF_0x2F8FCCA7 = 524,
	PCF_0xD06E62C8 = 525,
	PCF_DisableTacticalAnalysis = 526,
	PCF_0xED829B99 = 527,
	PCF_0xF1DEE14D = 528,
	PCF_0xDD0B572E = 529,
	PCF_0x41F0C11C = 530,
	PCF_0x6FE93B06 = 531,
	PCF_0x760D1D40 = 532,
	PCF_0x508CC0C1 = 533,
	PCF_0x09CAAAC1 = 534,
	PCF_0xEFF1BFD7 = 535,
	PCF_0x97D22E0F = 536,
	PCF_CannotSwapReins = 537,
	PCF_0x94928F59 = 538,
	PCF_0x13377872 = 539,
	PCF_FollowLeaderRunToEnterTransport = 540,
	PCF_PlayerCorpse = 541,
	PCF_0x4ECF4D1E = 542,
	PCF_0x32F7554D = 543,
	PCF_0xB13329B4 = 544,
	PCF_DontCreateCombatBlip = 545,
	PCF_0x7F409486 = 546,
	PCF_0x665E5AB5 = 547,
	PCF_0xE357C75E = 548,
	PCF_0xD5BFF570 = 549,
	PCF_DisableAndBreakAimLockOntoThisPed = 550,
	PCF_0x75943079 = 551,
	PCF_0x74F95F2E = 552,
	PCF_0x7BA7E665 = 553,
	PCF_0x544E47DB = 554,
	PCF_0xC9A8DCFC = 555,
	PCF_0x41C9EEAA = 556,
	PCF_0xFC543F7D = 557,
	PCF_0x27298865 = 558,
	PCF_0xF46AD61C = 559,
	PCF_EnableMountCoverForPedInMP = 560,
	PCF_EnableHorseCollectPlantInteractionInMP = 561,
	PCF_0x74064B79 = 562,
	PCF_0x3090EC16 = 563,
	PCF_0x12300BC5 = 564,
	PCF_IsValidForVehicleSeatStow = 565,
	PCF_EnableSpecialActionBranches = 566,
	PCF_DisableHorseShunting = 567,
	PCF_0xCF2BF977 = 568,
	PCF_CanBeAttackedByFriendlyPed = 569,
	PCF_0xAE180F85 = 570,
	PCF_0xEB0A3629 = 571,
	PCF_0x67843207 = 572,
	PCF_0xFFEDA2A0 = 573,
	PCF_0xB6B446DB = 574,
	PCF_DisableGuardAI = 575,
	PCF_0xF965A657 = 576,
	PCF_0x65CB2911 = 577,
	PCF_0x47030DBE = 578,
	PCF_0x04F84B32 = 579,
	PCF_IsTranquilized = 580,
	PCF_0x811D6F58 = 581,
	PCF_AllowStudyInMP = 582,
	PCF_0x107B0522 = 583,
	PCF_DisableInjuredMovement = 584,
	PCF_RagdollFloatsIndefinitely = 585,
	PCF_0x938B8DD8 = 586,
	PCF_0xB6CE7423 = 587,
	PCF_0xD6A8CBCA = 588,
	PCF_0x4DE6C4FB = 589,
	PCF_0x64624B35 = 590,
	PCF_0x4E549A84 = 591,
	PCF_0x38F1812A = 592,
	PCF_0x7115FE4E = 593,
	PCF_0x683E58D5 = 594,
	PCF_AllowAutoSwitchToProjectiles = 595,
	PCF_0x43CFCCB3 = 596,
	PCF_0x2FDAD8E5 = 597,
	PCF_0x5A17DA53 = 598,
	PCF_DisableScenarioWarpWeaponDestruction = 599,
	PCF_EnableProjectileAccuracy = 600,
	PCF_0x2C666858 = 601,
	PCF_0x640FF990 = 602,
};
```