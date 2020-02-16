# bmw-g-series-coding
Information on coding BMW G series vehicles with a focus on the G20 

## Getting Started
### Get either Launcher Pro or EsysX. You can also do some of these items via bimmercode expert mode
Launcher pro - https://mega.nz/#!H9AlBZKQ!-gkBqTBmYDTe_btjbxWhD4ZjvxpHrvv7kh1WesW1l5g

### If using esys and not bimmercode, then continue here once you have EsysX or Launcher Pro
https://www.bimmerfest.com/forums/sh...php?p=10193333

*NOTE: Do NOT follow the charity donation instructions in the link above. Instead, email tokenmaster directly per the PDF linked earlier*

### Once you have all the software installed, go here
 https://www.bimmerfest.com/forums/sh...d.php?t=983245

### Cheat Code repository
https://github.com/packetpilot/bmw-f/tree/master/cheats 

If you neeed to manually update them, you can copy them to `C:\Program Files (x86)\TokenMaster\E-Sys Launcher PRO\FDLCodes` on windows

### Selecting Cheat Code Authors
In Launcher Pro go to Settings -> cheat codes -> and select `Almaretto` and `jokinawa`. Disable the reest

## Items I have coded with existing cheat codes:
| Name                         |  ECU                  |
| ---------------------------- | --------------------- |
| Remove legal disclaimers     | HU_MGU                |
| Auto Start Stop Memory       | DME                   |
| Active Sound Dynamics Off    |                       |
| Air Conditioner Memory       |                       |
| video in motion              | HU_MGU                |
| full SMS text display        | HU_MGU                |
| video in motion              | HU_MGU                |
| enable coasting/sailing      | HU_MGU                |
| 5x Turn Indicator            | HU_MGU                |
| m startup animation          | HU_MGU                |
| close trunk from fob         | HKFM2                 |
| close trunk from door switch | HKFM2                 |
| speedometer correction       | DKOMBI                |
| comfort+ driving mode        | BDC_BODY, HU_MGU, SAS2|
| Lane change assistance       | BDC_BODY, HU_MGU, SAS2|


### Coded items without currently existing cheat codes
| Name                                       |  ECU        | Property                     | Value           |
| ------------------------------------------ | ----------- | ---------------------------- | --------------- |
| auto steering wheel heater when cold (1/3) | HU_MGU      | AKT_Auto_Lenkrad             | aktiv           |
| auto steering wheel heater when cold (2/3) | BDC_BODY    | LHZ_CCM_IKF                  | aktiv           |
| auto steering wheel heater when cold (3/3) | BDC_BODY    | IKF_ENABLE                   | ikf_alle_sitze  |
| lane change assistance (1/3)               | BDC_BODY    | SPURWECHSEL_ASSISTENT        | aktiv           |
| lane change assistance (2/3)               | HU_MGU      | SPURWECHSELASSISTENT         | gen_1           |
| lane change assistance (3/3)               | SAS2        | C_SWA_VORHANDED              | NR001_VORHANDEN |
| Driver's seat heat distribution (1/3)      | SM2         | SHZ_TYP                      | werte 02        |
| Driver's seat heat distribution (2/3)      | BDC_BODY    | SITZHEIZUNG_FRONT_schichtung | active          |
| Driver's seat heat distribution (3/3)      | BDC_BODY    | SITZHEIZUNG_FOND_schichtung  | active          |


### Items that I am Testing/Verifying
| Name                            |  ECU                               | Instructions                                 |
| ------------------------------- | ---------------------------------- | -------------------------------------------- |
| Flashing Brake Force Display    | BDC_BODY                           | apply cheat code                             |
| anti-dazzle/no glare high beams | BDC_BODY, KAFAS4, HU_MGU, FLM, FLM | VO Code to remove 5AC, then code listed ECUs |


### Items I am still researching or waiting on bmw updates to fix/enable
* full ///M gauges, HUD, idrive settings, etc. current implementations I have seen are not complete
* heated seats via remote start
* heated steering wheel via remote start


### I don't believe are possible due to hardware restrictions
* Enable blue lights in headlamps (laser lights) - the US lights have a white bulb there, not blue
* full LED headlight brightness (EU spec) - after coding my FLM to ECE values nothing changed, and no values related to brightness were altered
* full Laser light brightness (EU spec) - same reason as above

### More details can be found on my Bimmerpost forum post
* https://g20.bimmerpost.com/forums/showthread.php?t=1673049