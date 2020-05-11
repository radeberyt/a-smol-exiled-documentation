# Information
EXILED is a framework to create and use plugins in SCP: SL.
That's not an offical documentation.

# Events
### Every event. (EXILED 1.10.0)

- PlayerBanEvent
- CheckRoundEndEvent
- UsedMedicalItemEvent
- CancelMedicalItemEvent
- PlayerInteractEvent
- SpawnRagdollEvent
- Scp106CreatedPortalEvent
- DecontaminationEvent
- ItemChangedEvent
- Scp079LvlGainEvent
- WarheadKeycardAccessEvent
- UseMedicalItemEvent
- Scp096EnrageEvent
- Scp096CalmEvent
- PlayerJoinEvent
- Scp079ExpGainEvent
- PlayerLeaveEvent
- GeneratorFinishedEvent
- GeneratorInsertedEvent
- AnnounceDecontaminationEvent
- AnnounceScpTerminationEvent
- AnnounceNtfEntranceEvent
- WarheadDetonationEvent
- DoorInteractEvent
- ElevatorInteractEvent
- GeneratorEjectedEvent
- WarheadCancelledEvent
- LockerInteractEvent
- TriggerTeslaEvent
- Scp914UpgradeEvent
- GeneratorUnlockEvent
- GeneratorOpenedEvent
- GeneratorClosedEvent
- WarheadStartEvent
- ConsoleCommandEvent
- PlayerHurtEvent
- PlaceBloodEvent
- Scp106ContainEvent
- Scp914ActivationEvent
- Scp914KnobChangeEvent
- FemurEnterEvent
- SyncDataEvent
- RoundStartEvent
- PlayerSpawnEvent
- PreAuthEvent
- RoundRestartEvent
- RemoteAdminCommandEvent
- CheaterReportEvent
- WaitingForPlayersEvent
- TeamRespawnEvent
- PlayerBannedEvent
- RoundEndEvent
- PlayerReloadEvent
- PocketDimDeathEvent
- PocketDimEscapedEvent
- StartItemsEvent
- GrenadeThrownEvent
- DropItemEvent
- ItemDroppedEvent
- PickupItemEvent
- PlayerHandcuffedEvent
- PlayerHandcuffFreedEvent
- Scp079TriggerTeslaEvent
- CheckEscapeEvent
- IntercomSpeakEvent
- LateShootEvent
- ShootEvent
- Scp106TeleportEvent
- PocketDimDamageEvent
- PocketDimEnterEvent
- SetGroupEvent
- SetClassEvent
- PlayerDeathEvent
- PlaceDecalEvent

# Log methods

- Info(message)
- Debug(message)
- Warn(message)
- Error(message)

# Extensions

### Cassie
- Cassie.CassieMessage(message, makeHold, makeNoise)
- Cassie.DelayedCassieMessage(message, makeHold, makeNoise, delay)
### Item
- IsAmmo(item)
- IsWeapon(type, checkMicro)
- IsSCP(item)
- IsThrowable(item)
- IsMedical(item)
- IsUtility(item)
- IsKeycard(type)
### im rly tired and don't want write map methods
### Player
- player.cs contains rly big code, u can see methods here => https://github.com/galaxy119/EXILED/blob/master/EXILED_Main/Extensions/Player.cs
### SCP-079
- GetExperience(player)
- SetExperience(player, amount)
- AddExperience(player, amount)
- GetLevel(player)
- SetLevel(player)
- GetEnergy(player)
- SetEnergy(player, amount)
- AddEnergy(player, amount)
- GetMaxEnergy(Player)
- SetMaxEnergy(player, amount)
- GetLockedDoors(player)
- SetLockedDoors(player, lockedDoors)
- AddLockedDoor(player, doorName)
- RemoveLockedDoor(player, doorName)
- GetSpeaker(player)
- SetSpeaker(player, speaker, lookAtRotation)
- GetCamera(player)
- GetCameras()
- SetCamera(player, camera, lookAtRotation)
