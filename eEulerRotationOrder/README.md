## Natives that use this enum
| Name                                                              | Hash               |
|-------------------------------------------------------------------|--------------------|
| CAM::GET\_CAM\_ROT                                                | 0x9BF96B57254E7889 |
| CAM::SET\_CAM\_ROT                                                | 0x63DFA6810AD78719 |
| CAM::GET\_GAMEPLAY\_CAM\_ROT                                      | 0x0252D2B5582957A6 |
| CAM::GET\_FINAL\_RENDERED\_CAM\_ROT                               | 0x602685BD85DD26CA |
| CAM::CREATE\_CAM\_WITH\_PARAMS                                    | 0x40C23491CE83708E |
| CAM::CREATE\_CAMERA\_WITH\_PARAMS                                 | 0x98B99B9F27E2D60B |
| CAM::SET\_CAM\_PARAMS                                             | 0xA47BBFFFB83D4D0A |
| CAM::ADD\_CAM\_SPLINE\_NODE                                       | 0xF1F57F9D230F9CD1 |
| CAM::PLAY\_CAM\_ANIM                                              | 0xA263DDF694D563F6 |
| ENTITY::GET\_ENTITY\_ROTATION                                     | 0xE09CAF86C32CB48F |
| ENTITY::SET\_ENTITY\_ROTATION                                     | 0x9CC8314DFEDE441E |
| PED::GET\_ANIM\_INITIAL\_OFFSET\_POSITION                         | 0xBE22B26DD764C040 |
| PED::GET\_ANIM\_INITIAL\_OFFSET\_ROTATION                         | 0x4B805E6046EE9E47 |
| TASK::TASK\_PLAY\_ANIM\_ADVANCED                                  | 0x83CDB10EA29B370B |
| TASK::TASK\_MOVE\_NETWORK\_ADVANCED\_BY\_NAME\_WITH\_INIT\_PARAMS | 0x7B6A04F98BBAFB2C |
| OBJECT::CREATE\_PICKUP\_ROTATE                                    | 0x891804727E0A98B7 |
| SHAPETEST::START\_SHAPE\_TEST\_BOX                                | 0xFE466162C4401D18 |
## Enum
```cpp
enum eEulerRotationOrder
{
	CAM_EULER_XYZ = 0,
	CAM_EULER_XZY = 1,
	CAM_EULER_YXZ = 2,
	CAM_EULER_YZX = 3,
	CAM_EULER_ZXY = 4,
	CAM_EULER_ZYX = 5,
};
```