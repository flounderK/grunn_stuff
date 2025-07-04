# grunn_stuff

```mermaid
 flowchart TD
    HedgeClippers --> HedgeShortcut(Hedge Shortcut)
    HedgeClippers --> Hammer
    HedgeClippers --> ChurchGateKey
    ChurchGateKey --> ChurchAccess
    ChurchAccess --> WellAccess
    WellAccess --> TriggerRain
    HedgeShortcut --> ToiletPaper
    ToiletPaper --> BathroomTent
    BathroomKey --> BathroomAccess 
    BathroomAccess --> BathroomTent
    BathroomTent --> BlueCoin
    BlueCoin --> TriggerRain
    MazeAccess --> MazeCrossing
    TriggerRain -->|Creates a path| MazeCrossing
    Plank -->|Creates a path| MazeCrossing
    MazeCrossing --> Maze 
    Compass --> Maze
    Maze --> TallIdol[Tall Idol]
    Hammer --> TallIdol
    HedgeShortcut -->|Optional Path| StormDrain
    StormDrain --> Trowel
    Trowel -->|Optional Location near gas station gazebo| Lighter
    Park --> HiddenParkEntrance[Hidden Park Entrance opens from park % complete]
    Trowel -->|Optional, contributes towards| HiddenParkEntrance
    TriggerRain -->|Optional, contributes towards| HiddenParkEntrance
    Hammer -->SmashSkelleton[Smash any skelleton]
    SmashSkelleton --> Bone
    Bone --> HappyDog
    HappyDog --> ParkThornEntranceAccess
    Lighter --> ParkThornEntranceAccess
    ParkThornEntranceAccess --> ParkAccess
    HappyDog --> SailBoatToy
    ParkAccess --> Park
    Paddle --> ParkAccess
    GasStationAccess -->|Optional| Lighter
    HiddenParkEntrance --> SecretStore
    Lighter --> SecretStore
    Plank --> BridgeShortcut
    SecretStore --> OfficeKeyA
    SecretStore --> ComputerDisk
    SecretStore --> GoldMedal
    SecretStore --> Compass
    FerryAccess --> ShortIdol
    SailBoatToy -->ShortIdol
    GasStationAccess --> GnomeShortcut
    GnomeShortcut --> GnomeIdol
    Hammer --> SmashGnome
    SmashGnome --> GnomeShortcut
    ChurchAccess --> ChurchDoorknob
    ChurchDoorknob --> ChurchShortcut
    ChurchShortcut --> MagicTrumpet
    MagicTrumpet --> ShyIdol
    OfficeKeyA --> GasStationOfficeAccess
    OfficeKeyB --> GasStationOfficeAccess
    Saturday --> OfficeKeyB
    Hammer --> OfficeKeyB
    GasStationOfficeAccess --> ComputerAccess
    ComputerAccess --> Apple
    ComputerAccess --> HouseTeleportAccess
    ComputerDisk -->HouseTeleportAccess
    HouseTeleportAccess --> ChurchMidnightKey
    ChurchMidnightKey --> CryptAccess
    FlowerGem -->CryptAccess
    WaterMysteryPlants --> FlowerGem
    CryptAccess --> CryptSolve 
    ShortIdol --> CryptSolve
    TallIdol --> CryptSolve
    ShyIdol -->CryptSolve
    GnomeIdol -->CryptSolve
    Lighter --> PurifiedStone
    CryptSolve --> DemonDefeat
    Sword --> DemonDefeat
    PurifiedStone -->DemonDefeat
    Apple --> Worm
    Worm --> SecretKey
```
