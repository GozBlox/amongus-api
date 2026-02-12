# What is The Skeld Map:

<p align="center">
  <img src="https://raw.githubusercontent.com/GozBlox/amongus-api/main/theskeldmap.png" width="400" />
</p>

<h1 align="center">The Skeld</h1>

Skeld is the first map created in Among Us in 2018. The map contains 14 areas and 19 tasks divided into 4 sections and these sections are:
- Common Task
- Short Task
- Long Task
- Visual Tasks

And these are the 14 areas in **The Skeld** Map:
- **Cafeteria (Spawn Location)**
- **Admin**
- **MedBay**
- **Upper Engine**
- **Security**
- **Reactor**
- **Lower Engine**
- **Electrical**
- **Storage**
- **Communications**
- **Shields**
- **Navigation**
- **O2**
- **Weapons**

## Common Task:
Common Tasks are tasks shared by all Crewmates, and these tasks are:
- **Fixing Wires**
- **Swipe Card**

Swipe Card is located in **Admin** (South East of Cafeteria)

Fixing Wiring is located in **Cafeteria/Security/Electrical/Navigation/Admin**

**Fixing Wiring have 3 stages to finish and these are the stages:**

| Location Name | 1st Stage rate | 2nd Stage rate | 3rd Stage rate |
|--------------|---------------|---------------|---------------|
| Admin        | 15%           | 30%           | 5%            |
| Storage      | 30%           | 20%           | 0%            |
| Cafeteria    | 0%            | 20%           | 30%           |
| Navigation   | 5%            | 30%           | 15%           |
| Electrical   | 50%           | 0%            | 0%            |
| Security     | 0%            | 0%            | 50%           |

```
Stages Information are from Among Us Wiki
```

And this the last of change to get a common task if its was set in **Lobby Settings** like this:
- [x] Common Task: 1

| Task Name | Chance |
|--------|-------|
| Swipe Card | 50% |
| Fixing Wiring | 50% |

- [x] Common Task: 2

| Task Name | Chance |
|--------|-------|
| Swipe Card | 100% |
| Fixing Wiring | 100% |

if you're impostor to make sure that the **Swipe Card** or **Fixing Wiring** is avaliable open **Task List** and you will find:
- [x] Admin: Swipe Card

or

- [x] Location: Fixing Wiring (0/3)

or you can find both if Common Task are 2

if you become impostor use this map:

```
Electrical (1st stage):
├── Navigation (2nd stage)
├── Cafeteria (2nd stage)
├── Admin (2nd stage)
├── Storage (2nd stage)
│
└──── Security (3rd stage)
└──── Cafeteria (3rd stage)
└──── Navigation (3rd stage)
└──── Admin (3rd stage)
-------------------------------
Storage (1st stage):
├── Navigation (2nd stage)
├── Cafeteria (2nd stage)
├── Admin (2nd stage)
│
└──── Security (3rd stage)
└──── Cafeteria (3rd stage)
└──── Navigation (3rd stage)
└──── Admin (3rd stage)
-------------------------------
Admin (1st stage):
├── Navigation (2nd stage)
├── Cafeteria (2nd stage)
├── Storage (2nd stage)
│
└──── Security (3rd stage)
└──── Cafeteria (3rd stage)
└──── Navigation (3rd stage)
-------------------------------
Navigation (1st stage):
├── Cafeteria (2nd stage)
├── Admin (2nd stage)
├── Storage (2nd stage)
│
└──── Security (3rd stage)
└──── Cafeteria (3rd stage)
└──── Admin (3rd stage)
```
**Don't forgot to choose 2nd stage/3rd stage by yourself, this is the best method to fake or catch the impostors faking wiring (even if its there in the task list**

## Short Tasks:
**Short Tasks** is the tasks that take short time to finish such as: **Divert Power** and here the list of **Short Tasks** with their location:

- [Divert Power](tasks/divertpower.md) (1st stage at electrical, 2nd stage could be at lower/upper engine, security, communications, shields, navigation, o2, weapons) and these are the change to get the 2nd stage in different locations**:

| 2nd Stage | Chance |
|--------|-------|
| Upper Engine | 12.50% |
| Lower Engine | 12.50% |
| Security | 12.50% |
| Communications | 12.50% |
| Shields | 12.50% |
| Navigation | 12.50% |
| O2 | 12.50% |
| Weapons | 12.50% |

- [Stabilize Steering](tasks/stabilize_steering.md) **(NNavigation)**
- [Clean O2 Filter](tasks/cleano2filter.md) **(O2)**
- [Calibrate Distributor](tasks/calibrate_distributor.md) **(Electrical)**
- [Clean Vent](tasks/cleanvent.md) **(Located in all areas that have vent)**
- [Clear Asteroids](tasks/clear_asteroids.md) **(Weapons)**
- [Prime Shields](tasks/primeshields.md) **(Shields)**
- [Download Data](tasks/download_data.md) **(Can be located at: Cafeteria, Weapons, Navigation, Communications, Electrical)**
- [Upload Data](tasks/upload_data.md) **(Admin)**
  - Remember that [Download Data](tasks/download_data.md) is the 1st stage of [Upload Data](tasks/upload_data.md)

- [Unlock Manifolds](tasks/unlock_manifolds.md) **(Reactor)**
- [Chart Course](tasks/chart_source.md) **Navigation**

## Long Tasks:
**Long Tasks** are the tasks that takes long time to finish such as: [Start Reactor](tasks/start_reactor.md) and here the list of **Long Tasks** in **The Skeld**:
- [Start Reactor](tasks/start_reactor.md) **(Reactor)**
- [Submit Scan](tasks/submit_scan.md) **(MedBay)**
- [Inspect Sample](tasks/inspect_sample.md) **(MedBay)**
- [Empty Garbage](tasks/empty_garbage.md) **(1st stage in cafeteria or o2 and the o2 one called Empty Cache and the cafeteria one called Empty Garbage, and the 2nd stage at Storage)** 
- [Fuel Engines](tasks/fuel_engines.md) **(1st stage at upper engine, 2nd stage at lower engine)**
- [Align Engine Output](tasks/align_engine_output.md) **(1st stage at upper engine, 2nd stage at lower engine)**

## Visual Tasks:
**Visual Tasks** are the tasks that can make you safe or clear to proof you are aren't impostor, sometimes some lobbies disabling this feature, however there only one **Task** that can make you clear even if the **Visual Tasks** are off and we are gonna show the list of the visual tasks and that one task:

- [Clear Asteroids](tasks/clear_asteroids.md) **(This Task at Weapons and you to make yourself clear the visuals need to be on, so the players can see you doing the task)**

- [Submit Scan](tasks/submit_scan.md) **(At Medbay, and this the only task that you can do or make yourself clear even if Visuals are off, but how??, when you do the Submit Scan, you will move slowly and a movement that impostor can't do, and to make sure he isn't faking, if you have the task and you saw someone doing it, try to click use in the task and if you saw, someone is doing the scan with his exact name, means he's safe and doing scan, however, the ghosts can do the scan and prevent the alive players from doing it, the players have to wait until the ghost complete the scan, also the alive players can see which ghost player is doing the scan)**

- [Prime Shields](tasks/primeshields.md) **(This tasks located in shields, and if its visuals: on very required, to see if someone doing the task, see the lights that outside the map in shields, there two wide lights close to the vent outside the map, if you saw the lights on while the player doing the task, he's 100% safe)**

- [Empty Garbage](tasks/empty_garbage.md) **(there are 2 stages to finish, first one, it could be in O2 or North of Cafeteria closer to download, doing it, it will unlock the 2nd stage in storage and this is the important, visuals on is required to see the trash getting out the map, if visuals on and you saw no trash is out, VOTE HIM, when you finish the task the trash will be throwed out the map and you can see it ONLY IF VISUALS ARE ON)**

## Connected Vents:
<p align="center">
  <img src="https://raw.githubusercontent.com/GozBlox/amongus-api/main/mapvent.png" width="400" />
</p>
- Vents that are the same color mean you can go through them, such as Security, MedBay, Electrical 