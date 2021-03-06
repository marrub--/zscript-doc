# Classes

Here is a full tree of all classes in ZScript as of GZDoom 4.2.1. There
are 1471 classes total.

```
Object
├ ActorIterator
├ AltHud
├ BaseStatusBar
│ ├ DoomStatusBar
│ ├ HereticStatusBar
│ ├ HexenStatusBar
│ ├ SBarInfoWrapper
│ └ StrifeStatusBar
├ BlockLinesIterator
├ BlockThingsIterator
├ Bot
├ BrokenLines
├ DynamicValueInterpolator
├ HUDFont
├ HUDMessageBase
├ InterBackground
├ InventoryBarState
├ LevelCompatibility
├ LinearValueInterpolator
├ LineIdIterator
├ LineTracer
├ Menu
│ ├ ConversationMenu
│ ├ EnterKey
│ ├ GenericMenu
│ │ └ ReadThisMenu
│ ├ ListMenu
│ │ ├ LoadSaveMenu
│ │ │ ├ LoadMenu
│ │ │ └ SaveMenu
│ │ └ PlayerMenu
│ ├ MessageBoxMenu
│ ├ OptionMenu
│ │ ├ ColorpickerMenu
│ │ ├ CompatibilityMenu
│ │ ├ GameplayMenu
│ │ ├ GLTextureGLOptions
│ │ ├ JoystickConfigMenu
│ │ ├ NewPlayerMenu
│ │ ├ os_Menu
│ │ ├ ReverbEdit
│ │ ├ ReverbSave
│ │ ├ ReverbSelect
│ │ └ VideoModeMenu
│ └ TextEnterMenu
├ MenuDescriptor
│ ├ ListMenuDescriptor
│ └ OptionMenuDescriptor
├ MenuItemBase
│ ├ ListMenuItem
│ │ ├ ListMenuItemPlayerDisplay
│ │ │ └ PlayerMenuPlayerDisplay
│ │ ├ ListMenuItemSelectable
│ │ │ ├ ListMenuItemPatchItem
│ │ │ ├ ListMenuItemPlayerNameBox
│ │ │ ├ ListMenuItemSlider
│ │ │ ├ ListMenuItemTextItem
│ │ │ └ ListMenuItemValueText
│ │ ├ ListMenuItemStaticPatch
│ │ │ └ ListMenuItemStaticPatchCentered
│ │ └ ListMenuItemStaticText
│ │   └ ListMenuItemStaticTextCentered
│ └ OptionMenuItem
│   ├ OptionMenuFieldBase
│   │ ├ OptionMenuItemNumberField
│   │ └ OptionMenuItemTextField
│   │   ├ OptionMenuItemPlayerNameField
│   │   └ os_SearchField
│   ├ OptionMenuItemColorPicker
│   ├ OptionMenuItemControlBase
│   │ ├ OptionMenuItemControl
│   │ └ OptionMenuItemMapControl
│   ├ OptionMenuItemOptionBase
│   │ ├ OptionMenuItemInverter
│   │ ├ OptionMenuItemJoyMap
│   │ ├ OptionMenuItemOption
│   │ │ └ os_AnyOrAllOption
│   │ ├ OptionMenuItemPlayerClassItem
│   │ ├ OptionMenuItemPlayerColorItem
│   │ ├ OptionMenuItemPlayerGenderItem
│   │ ├ OptionMenuItemPlayerSkinItem
│   │ ├ OptionMenuItemPlayerSwitchOnPickupItem
│   │ ├ OptionMenuItemPlayerTeamItem
│   │ ├ OptionMenuItemReverbOption
│   │ └ OptionMenuItemReverbSaveSelect
│   ├ OptionMenuItemScreenResolution
│   ├ OptionMenuItemStaticText
│   ├ OptionMenuItemStaticTextSwitchable
│   ├ OptionMenuItemSubMenu
│   │ ├ OptionMenuItemCommand
│   │ │ └ OptionMenuItemSafeCommand
│   │ ├ OptionMenuItemJoyConfigMenu
│   │ ├ OptionMenuItemLabeledSubmenu
│   │ └ OptionMenuItemReverbSelect
│   └ OptionMenuSliderBase
│     ├ OptionMenuItemAutoaimSlider
│     ├ OptionMenuItemPlayerColorSlider
│     ├ OptionMenuItemSlider
│     │ └ OptionMenuItemScaleSlider
│     ├ OptionMenuItemSliderReverbEditOption
│     ├ OptionMenuSliderJoyDeadZone
│     ├ OptionMenuSliderJoyScale
│     ├ OptionMenuSliderJoySensitivity
│     └ OptionMenuSliderVar
├ os_Query
├ PointLightFlickerRandomAdditive
├ PointLightFlickerRandomAttenuated
├ PSprite
├ ScriptUtil
├ SectorTagIterator
├ SeqNode
├ Shape2D
├ Shape2DTransform
├ SpotState
├ StaticEventHandler
│ └ EventHandler
├ StatusScreen
│ ├ CoopStatusScreen
│ ├ DeathmatchStatusScreen
│ └ DoomStatusScreen
│   └ RavenStatusScreen
├ Thinker
│ ├ Actor
│ │ ├ AlienAspClimber
│ │ ├ AlienBubbleColumn
│ │ ├ AlienCeilingBubble
│ │ ├ AlienChunkLarge
│ │ ├ AlienChunkSmall
│ │ ├ AlienFloorBubble
│ │ ├ AlienSpiderLight
│ │ ├ AmbientSound
│ │ │ └ AmbientSoundNoGravity
│ │ ├ AmmoFiller
│ │ ├ Anvil
│ │ ├ Arachnotron
│ │ │ └ StealthArachnotron
│ │ ├ ArachnotronPlasma
│ │ ├ Archvile
│ │ │ └ StealthArchvile
│ │ ├ ArchvileFire
│ │ ├ Arrow
│ │ ├ AxeBlood
│ │ ├ AxePuff
│ │ │ └ AxePuffGlow
│ │ ├ Bang4Cloud
│ │ ├ BaronBall
│ │ ├ BaronOfHell
│ │ │ ├ Flembrane
│ │ │ ├ HellKnight
│ │ │ │ └ StealthHellKnight
│ │ │ └ StealthBaron
│ │ ├ BarricadeColumn
│ │ ├ Bat
│ │ ├ Beast
│ │ ├ BeastBall
│ │ ├ BFGBall
│ │ │ └ LAZBall
│ │ ├ BFGExtra
│ │ ├ BigTree
│ │ │ └ ChexBananaTree
│ │ ├ BigTree2
│ │ ├ Bishop
│ │ ├ BishopBlur
│ │ ├ BishopFX
│ │ ├ BishopMissile
│ │ ├ BishopPainBlur
│ │ ├ BishopPuff
│ │ ├ BlastEffect
│ │ ├ BlasterPuff
│ │ ├ BlasterSmoke
│ │ ├ Blood
│ │ ├ BloodPool
│ │ ├ BloodscourgeDrop
│ │ ├ BloodSplash
│ │ ├ BloodSplashBase
│ │ ├ BloodSplatter
│ │ ├ BloodyTwitch
│ │ │ └ NonsolidTwitch
│ │ ├ BlueTorch
│ │ │ └ ChexSlimeFountain
│ │ ├ BossBrain
│ │ ├ BossEye
│ │ ├ BrainStem
│ │ ├ BrassTorch
│ │ ├ BridgeBall
│ │ ├ BulletPuff
│ │ ├ BurningBarrel
│ │ ├ BurningBowl
│ │ ├ BurningBrazier
│ │ ├ Cacodemon
│ │ │ ├ DeadCacodemon
│ │ │ └ StealthCacodemon
│ │ ├ CacodemonBall
│ │ ├ CageLight
│ │ ├ CajunBodyNode
│ │ ├ CajunTrace
│ │ ├ Candelabra
│ │ │ └ ChexGasTank
│ │ ├ Candle
│ │ ├ Candlestick
│ │ │ └ ChexChemicalFlask
│ │ ├ CavePillarBottom
│ │ ├ CavePillarTop
│ │ ├ CeilingChain
│ │ ├ CeilingTurret
│ │ ├ Centaur
│ │ │ ├ CentaurLeader
│ │ │ └ CentaurMash
│ │ ├ CentaurFX
│ │ ├ CentaurShield
│ │ ├ CentaurSword
│ │ ├ CFlameFloor
│ │ ├ ChaingunGuy
│ │ │ └ StealthChaingunGuy
│ │ ├ ChimneyStack
│ │ ├ CircleFlame
│ │ ├ ClericBoss
│ │ ├ Clink
│ │ ├ ColonGibs
│ │ ├ ColorSetter
│ │ ├ Column
│ │ │ └ ChexLandingLight
│ │ ├ CommanderKeen
│ │ ├ Computer
│ │ ├ CorpseBit
│ │ ├ CorpseBloodDrip
│ │ ├ CrossbowFX1
│ │ │ ├ CrossbowFX2
│ │ │ └ CrossbowFX3
│ │ ├ CrossbowFX4
│ │ ├ Crusader
│ │ ├ CrusaderMissile
│ │ ├ CStaffMissile
│ │ ├ CStaffPuff
│ │ ├ CustomBridge
│ │ │ ├ Bridge
│ │ │ └ ZBridge
│ │ ├ CustomSprite
│ │ ├ Cyberdemon
│ │ ├ Dart
│ │ │ └ PoisonDart
│ │ ├ DeadAcolyte
│ │ ├ DeadCrusader
│ │ ├ DeadMarine
│ │ ├ DeadPeasant
│ │ ├ DeadReaver
│ │ ├ DeadRebel
│ │ ├ DeadStick
│ │ │ └ ChexTallFlower2
│ │ ├ DeadStrifePlayer
│ │ ├ Decal
│ │ ├ Demon
│ │ │ ├ DeadDemon
│ │ │ ├ FlemoidusCycloptisCommonus
│ │ │ ├ Spectre
│ │ │ └ StealthDemon
│ │ ├ Demon1
│ │ │ ├ Demon1Mash
│ │ │ └ Demon2
│ │ │   └ Demon2Mash
│ │ ├ Demon1FX1
│ │ ├ Demon2FX1
│ │ ├ DemonChunk
│ │ │ ├ Demon1Chunk1
│ │ │ ├ Demon1Chunk2
│ │ │ ├ Demon1Chunk3
│ │ │ ├ Demon1Chunk4
│ │ │ ├ Demon1Chunk5
│ │ │ ├ Demon2Chunk1
│ │ │ ├ Demon2Chunk2
│ │ │ ├ Demon2Chunk3
│ │ │ ├ Demon2Chunk4
│ │ │ └ Demon2Chunk5
│ │ ├ Dirt1
│ │ ├ Dirt2
│ │ ├ Dirt3
│ │ ├ Dirt4
│ │ ├ Dirt5
│ │ ├ Dirt6
│ │ ├ DirtClump
│ │ ├ DoomBuilderCamera
│ │ ├ DoomImp
│ │ │ ├ ArmoredFlemoidusBipedicus
│ │ │ ├ DeadDoomImp
│ │ │ └ StealthDoomImp
│ │ ├ DoomImpBall
│ │ ├ DoomUnusedStates
│ │ ├ Dragon
│ │ ├ DragonExplosion
│ │ ├ DragonFireball
│ │ ├ DynamicLight
│ │ │ ├ PointLight
│ │ │ │ ├ PointLightAdditive
│ │ │ │ ├ PointLightAttenuated
│ │ │ │ ├ PointLightFlicker
│ │ │ │ │ ├ PointLightFlickerAdditive
│ │ │ │ │ ├ PointLightFlickerAttenuated
│ │ │ │ │ └ PointLightFlickerSubtractive
│ │ │ │ ├ PointLightFlickerRandom
│ │ │ │ │ └ PointLightFlickerRandomSubtractive
│ │ │ │ ├ PointLightPulse
│ │ │ │ │ ├ PointLightPulseAdditive
│ │ │ │ │ ├ PointLightPulseAttenuated
│ │ │ │ │ └ PointLightPulseSubtractive
│ │ │ │ ├ PointLightSubtractive
│ │ │ │ ├ SectorPointLight
│ │ │ │ │ ├ SectorPointLightAdditive
│ │ │ │ │ ├ SectorPointLightAttenuated
│ │ │ │ │ └ SectorPointLightSubtractive
│ │ │ │ └ SVELight
│ │ │ │   ├ SVELight7958
│ │ │ │   ├ SVELight7959
│ │ │ │   ├ SVELight7960
│ │ │ │   ├ SVELight7961
│ │ │ │   ├ SVELight7962
│ │ │ │   ├ SVELight7964
│ │ │ │   ├ SVELight7965
│ │ │ │   ├ SVELight7971
│ │ │ │   ├ SVELight7972
│ │ │ │   ├ SVELight7973
│ │ │ │   └ SVELight7974
│ │ │ ├ SpotLight
│ │ │ │ ├ SectorSpotLight
│ │ │ │ │ ├ SectorSpotLightAdditive
│ │ │ │ │ ├ SectorSpotLightAttenuated
│ │ │ │ │ └ SectorSpotLightSubtractive
│ │ │ │ ├ SpotLightAdditive
│ │ │ │ ├ SpotLightAttenuated
│ │ │ │ ├ SpotLightFlicker
│ │ │ │ │ ├ SpotLightFlickerAdditive
│ │ │ │ │ ├ SpotLightFlickerAttenuated
│ │ │ │ │ └ SpotLightFlickerSubtractive
│ │ │ │ ├ SpotLightFlickerRandom
│ │ │ │ │ ├ SpotLightFlickerRandomAdditive
│ │ │ │ │ ├ SpotLightFlickerRandomAttenuated
│ │ │ │ │ └ SpotLightFlickerRandomSubtractive
│ │ │ │ ├ SpotLightPulse
│ │ │ │ │ ├ SpotLightPulseAdditive
│ │ │ │ │ ├ SpotLightPulseAttenuated
│ │ │ │ │ └ SpotLightPulseSubtractive
│ │ │ │ └ SpotLightSubtractive
│ │ │ └ VavoomLight
│ │ │   ├ VavoomLightColor
│ │ │   └ VavoomLightWhite
│ │ ├ ElectricBolt
│ │ ├ EntityNest
│ │ ├ EntityPod
│ │ ├ Ettin
│ │ │ └ EttinMash
│ │ ├ EttinMace
│ │ ├ EvilEye
│ │ │ └ ChexChemicalBurner
│ │ ├ ExplosiveBarrel
│ │ ├ ExplosiveBarrel2
│ │ ├ FadeSetter
│ │ ├ FastProjectile
│ │ │ ├ BlasterFX1
│ │ │ ├ CFlameMissile
│ │ │ └ MageWandMissile
│ │ ├ FatShot
│ │ ├ Fatso
│ │ │ └ StealthFatso
│ │ ├ Feather
│ │ ├ FighterBoss
│ │ ├ FireBall
│ │ ├ FireBomb
│ │ ├ FireDemon
│ │ ├ FireDemonMissile
│ │ ├ FireDemonRock1
│ │ │ ├ FireDemonRock2
│ │ │ ├ FireDemonRock3
│ │ │ ├ FireDemonRock4
│ │ │ └ FireDemonRock5
│ │ ├ FireDemonSplotch1
│ │ │ └ FireDemonSplotch2
│ │ ├ FireDroplet
│ │ ├ FireThing
│ │ ├ FlameLargeTemp
│ │ ├ FlameMissile
│ │ │ └ FastFlameMissile
│ │ ├ FlamePuff
│ │ │ └ FlamePuff2
│ │ ├ FlameSmallTemp
│ │ ├ FloatingSkull
│ │ ├ FogPatchSmall
│ │ │ └ FogPatchMedium
│ │ │   └ FogPatchLarge
│ │ ├ FogSpawner
│ │ ├ ForceFieldGuard
│ │ ├ FrostMissile
│ │ │ └ IceShard
│ │ ├ FSwordFlame
│ │ ├ FSwordMissile
│ │ ├ GauntletPuff1
│ │ │ └ GauntletPuff2
│ │ ├ GibbedMarine
│ │ │ └ GibbedMarineExtra
│ │ ├ GlassJunk
│ │ ├ GlassShard
│ │ │ ├ SGShard0
│ │ │ ├ SGShard1
│ │ │ ├ SGShard2
│ │ │ ├ SGShard3
│ │ │ ├ SGShard4
│ │ │ ├ SGShard5
│ │ │ ├ SGShard6
│ │ │ ├ SGShard7
│ │ │ ├ SGShard8
│ │ │ └ SGShard9
│ │ ├ GoldWandFX1
│ │ │ ├ GoldWandFX2
│ │ │ └ GoldWandPuff2
│ │ ├ GoldWandPuff1
│ │ ├ GreenTorch
│ │ │ └ ChexCivilian1
│ │ ├ Grenade
│ │ ├ GrenadeSmokeTrail
│ │ ├ HammerMissile
│ │ ├ HammerPuff
│ │ ├ HangBNoBrain
│ │ ├ HangNoGuts
│ │ ├ HangTLookingDown
│ │ ├ HangTLookingUp
│ │ ├ HangTNoBrain
│ │ ├ HangTSkull
│ │ ├ HateTarget
│ │ ├ HeadCandles
│ │ ├ HeadFX1
│ │ ├ HeadFX2
│ │ ├ HeadFX3
│ │ ├ HeadOnAStick
│ │ ├ HeadsOnAStick
│ │ │ └ ChexTallFlower
│ │ ├ HeartColumn
│ │ ├ HeartsInTank
│ │ ├ HEGrenade
│ │ ├ Heresiarch
│ │ ├ HereticImp
│ │ │ └ HereticImpLeader
│ │ ├ HereticImpBall
│ │ ├ HereticImpChunk1
│ │ ├ HereticImpChunk2
│ │ ├ HolyMissile
│ │ ├ HolyMissilePuff
│ │ ├ HolyPuff
│ │ ├ HolySpirit
│ │ ├ HolyTail
│ │ │ └ HolyTailTrail
│ │ ├ HornRodFX1
│ │ ├ HornRodFX2
│ │ ├ HugeTorch
│ │ ├ HWaterDrip
│ │ ├ IceChunk
│ │ ├ IceFXPuff
│ │ ├ IceGuy
│ │ ├ IceGuyBit
│ │ ├ IceGuyFX
│ │ ├ IceGuyFX2
│ │ ├ IceGuyWisp1
│ │ │ └ IceGuyWisp2
│ │ ├ Inquisitor
│ │ ├ InquisitorArm
│ │ ├ InquisitorShot
│ │ ├ InterpolationPoint
│ │ ├ InterpolationSpecial
│ │ ├ Inventory
│ │ │ ├ Ammo
│ │ │ │ ├ Cell
│ │ │ │ │ ├ CellPack
│ │ │ │ │ ├ PhasingZorch
│ │ │ │ │ └ PhasingZorchPack
│ │ │ │ ├ Clip
│ │ │ │ │ ├ ClipBox
│ │ │ │ │ ├ MiniZorchPack
│ │ │ │ │ └ MiniZorchRecharge
│ │ │ │ ├ ClipOfBullets
│ │ │ │ │ └ BoxOfBullets
│ │ │ │ ├ ElectricBolts
│ │ │ │ ├ EnergyPod
│ │ │ │ │ └ EnergyPack
│ │ │ │ ├ HEGrenadeRounds
│ │ │ │ ├ Mana1
│ │ │ │ ├ Mana2
│ │ │ │ ├ MiniMissiles
│ │ │ │ │ └ CrateOfMissiles
│ │ │ │ ├ PhosphorusGrenadeRounds
│ │ │ │ ├ PoisonBolts
│ │ │ │ ├ RocketAmmo
│ │ │ │ │ ├ PropulsorZorch
│ │ │ │ │ ├ PropulsorZorchPack
│ │ │ │ │ └ RocketBox
│ │ │ │ └ Shell
│ │ │ │   ├ LargeZorchPack
│ │ │ │   ├ LargeZorchRecharge
│ │ │ │   └ ShellBox
│ │ │ ├ Armor
│ │ │ │ ├ BasicArmor
│ │ │ │ ├ BasicArmorBonus
│ │ │ │ │ └ ArmorBonus
│ │ │ │ │   └ SlimeRepellent
│ │ │ │ ├ BasicArmorPickup
│ │ │ │ │ ├ BlueArmor
│ │ │ │ │ │ ├ BlueArmorForMegasphere
│ │ │ │ │ │ └ SuperChexArmor
│ │ │ │ │ ├ GreenArmor
│ │ │ │ │ │ └ ChexArmor
│ │ │ │ │ ├ LeatherArmor
│ │ │ │ │ └ MetalArmor
│ │ │ │ └ HexenArmor
│ │ │ │   ├ AmuletOfWarding
│ │ │ │   ├ FalconShield
│ │ │ │   ├ MeshArmor
│ │ │ │   └ PlatinumHelm
│ │ │ ├ ArtiBoostArmor
│ │ │ ├ ArtiDarkServant
│ │ │ ├ ArtiHealingRadius
│ │ │ ├ ArtiPoisonBag
│ │ │ │ ├ ArtiPoisonBag1
│ │ │ │ ├ ArtiPoisonBag2
│ │ │ │ ├ ArtiPoisonBag3
│ │ │ │ ├ ArtiPoisonBagGiver
│ │ │ │ └ ArtiPoisonBagShooter
│ │ │ ├ ArtiTeleport
│ │ │ ├ ArtiTeleportOther
│ │ │ ├ BackpackItem
│ │ │ │ ├ AmmoSatchel
│ │ │ │ └ Backpack
│ │ │ │   └ Zorchpack
│ │ │ ├ BeldinsRing
│ │ │ ├ BrokenPowerCoupling
│ │ │ ├ Coin
│ │ │ │ ├ Gold10
│ │ │ │ ├ Gold25
│ │ │ │ ├ Gold300
│ │ │ │ └ Gold50
│ │ │ ├ Communicator
│ │ │ ├ DegninOre
│ │ │ ├ DehackedPickup
│ │ │ ├ DummyStrifeItem
│ │ │ │ ├ AmmoFillup
│ │ │ │ ├ CloseDoor222
│ │ │ │ ├ HealthFillup
│ │ │ │ ├ OpenDoor222
│ │ │ │ ├ OpenDoor224
│ │ │ │ ├ RaiseAlarm
│ │ │ │ ├ SlideshowStarter
│ │ │ │ ├ SVEOpenDoor225
│ │ │ │ ├ UpgradeAccuracy
│ │ │ │ └ UpgradeStamina
│ │ │ ├ Ear
│ │ │ ├ FakeInventory
│ │ │ ├ FlameThrowerParts
│ │ │ ├ GuardUniform
│ │ │ ├ GunTraining
│ │ │ ├ Health
│ │ │ │ ├ CrystalVial
│ │ │ │ ├ HealthBonus
│ │ │ │ │ └ GlassOfWater
│ │ │ │ ├ MaxHealth
│ │ │ │ ├ Medikit
│ │ │ │ │ └ BowlOfVegetables
│ │ │ │ ├ MegasphereHealth
│ │ │ │ ├ Soulsphere
│ │ │ │ │ └ SuperchargeBreakfast
│ │ │ │ └ Stimpack
│ │ │ │   └ BowlOfFruit
│ │ │ ├ HealthPickup
│ │ │ │ ├ ArtiHealth
│ │ │ │ ├ ArtiSuperHealth
│ │ │ │ ├ MedicalKit
│ │ │ │ ├ MedPatch
│ │ │ │ └ SurgeryKit
│ │ │ ├ HealthTraining
│ │ │ ├ Info
│ │ │ ├ InterrogatorReport
│ │ │ ├ Key
│ │ │ │ ├ DoomKey
│ │ │ │ │ ├ BlueCard
│ │ │ │ │ │ └ ChexBlueCard
│ │ │ │ │ ├ BlueSkull
│ │ │ │ │ ├ RedCard
│ │ │ │ │ │ └ ChexRedCard
│ │ │ │ │ ├ RedSkull
│ │ │ │ │ ├ YellowCard
│ │ │ │ │ │ └ ChexYellowCard
│ │ │ │ │ └ YellowSkull
│ │ │ │ ├ HexenKey
│ │ │ │ │ ├ KeyAxe
│ │ │ │ │ ├ KeyCastle
│ │ │ │ │ ├ KeyCave
│ │ │ │ │ ├ KeyDungeon
│ │ │ │ │ ├ KeyEmerald
│ │ │ │ │ ├ KeyFire
│ │ │ │ │ ├ KeyHorn
│ │ │ │ │ ├ KeyRusted
│ │ │ │ │ ├ KeySilver
│ │ │ │ │ ├ KeySteel
│ │ │ │ │ └ KeySwamp
│ │ │ │ ├ PrisonPass
│ │ │ │ └ StrifeKey
│ │ │ │   ├ BaseKey
│ │ │ │   ├ BlueCrystalKey
│ │ │ │   ├ BrassKey
│ │ │ │   ├ CatacombKey
│ │ │ │   ├ ChapelKey
│ │ │ │   ├ CoreKey
│ │ │ │   ├ FactoryKey
│ │ │ │   ├ GoldKey
│ │ │ │   ├ GovsKey
│ │ │ │   ├ IDBadge
│ │ │ │   ├ IDCard
│ │ │ │   ├ MaulerKey
│ │ │ │   ├ MilitaryID
│ │ │ │   ├ MineKey
│ │ │ │   ├ NewKey5
│ │ │ │   ├ OracleKey
│ │ │ │   ├ OrderKey
│ │ │ │   ├ Passcard
│ │ │ │   ├ Power1Key
│ │ │ │   ├ Power2Key
│ │ │ │   ├ Power3Key
│ │ │ │   ├ PrisonKey
│ │ │ │   ├ RedCrystalKey
│ │ │ │   ├ SecurityKey
│ │ │ │   ├ SeveredHand
│ │ │ │   ├ SilverKey
│ │ │ │   └ WarehouseKey
│ │ │ ├ MapRevealer
│ │ │ │ ├ Allmap
│ │ │ │ │ └ ComputerAreaMap
│ │ │ │ └ StrifeMap
│ │ │ ├ OfferingChalice
│ │ │ ├ OfficersUniform
│ │ │ ├ OraclePass
│ │ │ ├ Powerup
│ │ │ │ ├ PowerBuddha
│ │ │ │ ├ PowerDamage
│ │ │ │ ├ PowerDoubleFiringSpeed
│ │ │ │ ├ PowerDrain
│ │ │ │ ├ PowerFlight
│ │ │ │ ├ PowerFrightener
│ │ │ │ ├ PowerHighJump
│ │ │ │ ├ PowerInfiniteAmmo
│ │ │ │ ├ PowerInvisibility
│ │ │ │ │ ├ PowerGhost
│ │ │ │ │ └ PowerShadow
│ │ │ │ ├ PowerInvulnerable
│ │ │ │ ├ PowerIronFeet
│ │ │ │ │ └ PowerMask
│ │ │ │ ├ PowerLightAmp
│ │ │ │ │ └ PowerTorch
│ │ │ │ ├ PowerMinotaur
│ │ │ │ ├ PowerMorph
│ │ │ │ ├ PowerProtection
│ │ │ │ ├ PowerReflection
│ │ │ │ ├ PowerRegeneration
│ │ │ │ ├ PowerScanner
│ │ │ │ ├ PowerSpeed
│ │ │ │ ├ PowerStrength
│ │ │ │ ├ PowerTargeter
│ │ │ │ ├ PowerTimeFreezer
│ │ │ │ └ PowerWeaponLevel2
│ │ │ ├ PowerupGiver
│ │ │ │ ├ ArtiFly
│ │ │ │ ├ ArtiInvulnerability
│ │ │ │ ├ ArtiInvulnerability2
│ │ │ │ ├ ArtiSpeedBoots
│ │ │ │ ├ ArtiTorch
│ │ │ │ ├ BlurSphere
│ │ │ │ ├ EnvironmentalSuit
│ │ │ │ ├ Infrared
│ │ │ │ ├ InvulnerabilitySphere
│ │ │ │ ├ RadSuit
│ │ │ │ │ └ SlimeProofSuit
│ │ │ │ ├ Scanner
│ │ │ │ ├ ShadowArmor
│ │ │ │ └ Targeter
│ │ │ ├ ProgLevelEnder
│ │ │ ├ PuzzleItem
│ │ │ │ ├ PuzzBook1
│ │ │ │ ├ PuzzBook2
│ │ │ │ ├ PuzzCWeapon
│ │ │ │ ├ PuzzFlameMask
│ │ │ │ ├ PuzzFWeapon
│ │ │ │ ├ PuzzGear1
│ │ │ │ ├ PuzzGear2
│ │ │ │ ├ PuzzGear3
│ │ │ │ ├ PuzzGear4
│ │ │ │ ├ PuzzGemBig
│ │ │ │ ├ PuzzGemBlue1
│ │ │ │ ├ PuzzGemBlue2
│ │ │ │ ├ PuzzGemGreen1
│ │ │ │ ├ PuzzGemGreen2
│ │ │ │ ├ PuzzGemRed
│ │ │ │ ├ PuzzMWeapon
│ │ │ │ └ PuzzSkull
│ │ │ ├ QuestItem
│ │ │ │ ├ QuestItem1
│ │ │ │ ├ QuestItem10
│ │ │ │ ├ QuestItem11
│ │ │ │ ├ QuestItem12
│ │ │ │ ├ QuestItem13
│ │ │ │ ├ QuestItem14
│ │ │ │ ├ QuestItem15
│ │ │ │ ├ QuestItem16
│ │ │ │ ├ QuestItem17
│ │ │ │ ├ QuestItem18
│ │ │ │ ├ QuestItem19
│ │ │ │ ├ QuestItem2
│ │ │ │ ├ QuestItem20
│ │ │ │ ├ QuestItem21
│ │ │ │ ├ QuestItem22
│ │ │ │ ├ QuestItem23
│ │ │ │ ├ QuestItem24
│ │ │ │ ├ QuestItem25
│ │ │ │ ├ QuestItem26
│ │ │ │ ├ QuestItem27
│ │ │ │ ├ QuestItem28
│ │ │ │ ├ QuestItem29
│ │ │ │ ├ QuestItem3
│ │ │ │ ├ QuestItem30
│ │ │ │ ├ QuestItem31
│ │ │ │ ├ QuestItem4
│ │ │ │ ├ QuestItem5
│ │ │ │ ├ QuestItem6
│ │ │ │ ├ QuestItem7
│ │ │ │ ├ QuestItem8
│ │ │ │ └ QuestItem9
│ │ │ ├ RainTracker
│ │ │ ├ ScoreItem
│ │ │ │ ├ EvilSceptre
│ │ │ │ └ UnholyBible
│ │ │ ├ StateProvider
│ │ │ │ ├ CustomInventory
│ │ │ │ │ ├ ArtiBlastRadius
│ │ │ │ │ ├ ArtiBoostMana
│ │ │ │ │ ├ ArtiEgg
│ │ │ │ │ ├ ArtiPork
│ │ │ │ │ ├ Berserk
│ │ │ │ │ ├ Mana3
│ │ │ │ │ └ Megasphere
│ │ │ │ └ Weapon
│ │ │ │   ├ Beak
│ │ │ │   │ └ BeakPowered
│ │ │ │   ├ Chainsaw
│ │ │ │   │ └ SuperBootspork
│ │ │ │   ├ ClericWeapon
│ │ │ │   │ ├ CWeapFlame
│ │ │ │   │ ├ CWeapMace
│ │ │ │   │ ├ CWeapStaff
│ │ │ │   │ └ CWeapWraithverge
│ │ │ │   ├ DoomWeapon
│ │ │ │   │ ├ BFG9000
│ │ │ │   │ │ └ LAZDevice
│ │ │ │   │ ├ Chaingun
│ │ │ │   │ │ └ RapidZorcher
│ │ │ │   │ ├ Pistol
│ │ │ │   │ │ └ MiniZorcher
│ │ │ │   │ ├ PlasmaRifle
│ │ │ │   │ │ └ PhasingZorcher
│ │ │ │   │ ├ RocketLauncher
│ │ │ │   │ │ └ ZorchPropulsor
│ │ │ │   │ ├ Shotgun
│ │ │ │   │ │ └ LargeZorcher
│ │ │ │   │ └ SuperShotgun
│ │ │ │   │   └ SuperLargeZorcher
│ │ │ │   ├ FighterWeapon
│ │ │ │   │ ├ FWeapAxe
│ │ │ │   │ ├ FWeapFist
│ │ │ │   │ ├ FWeapHammer
│ │ │ │   │ └ FWeapQuietus
│ │ │ │   ├ Fist
│ │ │ │   │ └ Bootspoon
│ │ │ │   ├ Gauntlets
│ │ │ │   │ └ GauntletsPowered
│ │ │ │   ├ HereticWeapon
│ │ │ │   │ ├ Blaster
│ │ │ │   │ │ └ BlasterPowered
│ │ │ │   │ ├ Crossbow
│ │ │ │   │ │ └ CrossbowPowered
│ │ │ │   │ ├ GoldWand
│ │ │ │   │ │ └ GoldWandPowered
│ │ │ │   │ ├ Mace
│ │ │ │   │ │ └ MacePowered
│ │ │ │   │ ├ SkullRod
│ │ │ │   │ │ └ SkullRodPowered
│ │ │ │   │ └ Staff
│ │ │ │   │   └ StaffPowered
│ │ │ │   ├ MageWeapon
│ │ │ │   │ ├ MWeapBloodscourge
│ │ │ │   │ ├ MWeapFrost
│ │ │ │   │ ├ MWeapLightning
│ │ │ │   │ └ MWeapWand
│ │ │ │   ├ PhoenixRod
│ │ │ │   │ └ PhoenixRodPowered
│ │ │ │   ├ Sigil
│ │ │ │   │ ├ Sigil1
│ │ │ │   │ ├ Sigil2
│ │ │ │   │ ├ Sigil3
│ │ │ │   │ ├ Sigil4
│ │ │ │   │ └ Sigil5
│ │ │ │   ├ Snout
│ │ │ │   ├ StrifeWeapon
│ │ │ │   │ ├ AssaultGun
│ │ │ │   │ ├ FlameThrower
│ │ │ │   │ ├ Mauler
│ │ │ │   │ │ └ Mauler2
│ │ │ │   │ ├ MiniMissileLauncher
│ │ │ │   │ ├ PunchDagger
│ │ │ │   │ ├ StrifeCrossbow
│ │ │ │   │ │ └ StrifeCrossbow2
│ │ │ │   │ └ StrifeGrenadeLauncher
│ │ │ │   │   └ StrifeGrenadeLauncher2
│ │ │ │   └ WeaponGiver
│ │ │ │     └ AssaultGunStanding
│ │ │ ├ SVEBlueChalice
│ │ │ ├ SVEFlagSpotBlue
│ │ │ ├ SVEFlagSpotRed
│ │ │ ├ SVETalismanPowerup
│ │ │ ├ SVETalismanRed
│ │ │ │ ├ SVETalismanBlue
│ │ │ │ └ SVETalismanGreen
│ │ │ ├ TeleporterBeacon
│ │ │ ├ WeaponHolder
│ │ │ └ WeaponPiece
│ │ │   ├ ClericWeaponPiece
│ │ │   │ ├ CWeaponPiece1
│ │ │   │ ├ CWeaponPiece2
│ │ │   │ └ CWeaponPiece3
│ │ │   ├ FighterWeaponPiece
│ │ │   │ ├ FWeaponPiece1
│ │ │   │ ├ FWeaponPiece2
│ │ │   │ └ FWeaponPiece3
│ │ │   └ MageWeaponPiece
│ │ │     ├ MWeaponPiece1
│ │ │     ├ MWeaponPiece2
│ │ │     └ MWeaponPiece3
│ │ ├ InvisibleBridge
│ │ │ ├ InvisibleBridge16
│ │ │ ├ InvisibleBridge32
│ │ │ └ InvisibleBridge8
│ │ ├ Ironlich
│ │ ├ ItemFog
│ │ ├ KlaxonWarningLight
│ │ ├ KneelingGuy
│ │ ├ Knight
│ │ │ └ KnightGhost
│ │ ├ KnightAxe
│ │ │ └ RedAxe
│ │ ├ Korax
│ │ ├ KoraxBolt
│ │ ├ KoraxSpirit
│ │ ├ LargeTorch
│ │ ├ LavaSmoke
│ │ ├ LavaSplash
│ │ ├ Leaf1
│ │ │ └ Leaf2
│ │ ├ LeafSpawner
│ │ ├ LightBrownFluorescent
│ │ ├ LightGlobe
│ │ ├ LightGoldFluorescent
│ │ ├ Lightning
│ │ │ └ LightningCeiling
│ │ │   └ LightningFloor
│ │ ├ LightningZap
│ │ ├ LightSilverFluorescent
│ │ ├ LittleFly
│ │ ├ LiveStick
│ │ ├ Loremaster
│ │ ├ LoreShot
│ │ ├ LoreShot2
│ │ ├ LostSoul
│ │ │ ├ BetaSkull
│ │ │ ├ ChexSoul
│ │ │ └ DeadLostSoul
│ │ ├ MaceFX1
│ │ │ ├ MaceFX2
│ │ │ └ MaceFX3
│ │ ├ MaceFX4
│ │ ├ Macil1
│ │ │ └ Macil2
│ │ ├ MageBoss
│ │ ├ MageStaffFX2
│ │ ├ MageWandSmoke
│ │ ├ MapMarker
│ │ ├ MapSpot
│ │ │ ├ FS_Mapspot
│ │ │ └ MapSpotGravity
│ │ ├ MaulerPuff
│ │ ├ MaulerTorpedo
│ │ ├ MaulerTorpedoWave
│ │ ├ MBFHelperDog
│ │ ├ Meat
│ │ │ └ Junk
│ │ ├ Meat2
│ │ │ └ NonsolidMeat2
│ │ ├ Meat3
│ │ │ └ NonsolidMeat3
│ │ ├ Meat4
│ │ │ └ NonsolidMeat4
│ │ ├ Meat5
│ │ │ └ NonsolidMeat5
│ │ ├ MediumTorch
│ │ ├ Merchant
│ │ │ ├ Armorer
│ │ │ ├ BarKeep
│ │ │ ├ Medic
│ │ │ └ WeaponSmith
│ │ ├ MetalPot
│ │ ├ MiniMissile
│ │ ├ Minotaur
│ │ │ └ MinotaurFriend
│ │ ├ MinotaurFX1
│ │ │ └ MinotaurFX2
│ │ │   └ MinotaurFX3
│ │ ├ MinotaurSmoke
│ │ ├ MinotaurSmokeExit
│ │ ├ MorphedMonster
│ │ │ ├ Chicken
│ │ │ └ Pig
│ │ ├ MorphProjectile
│ │ │ ├ EggFX
│ │ │ └ PorkFX
│ │ ├ Mug
│ │ ├ Mummy
│ │ │ ├ MummyGhost
│ │ │ └ MummyLeader
│ │ │   └ MummyLeaderGhost
│ │ ├ MummyFX1
│ │ ├ MummySoul
│ │ ├ Oracle
│ │ ├ OutsideLamp
│ │ ├ PainElemental
│ │ ├ PalmTree
│ │ ├ ParticleFountain
│ │ │ ├ BlackParticleFountain
│ │ │ ├ BlueParticleFountain
│ │ │ ├ GreenParticleFountain
│ │ │ ├ PurpleParticleFountain
│ │ │ ├ RedParticleFountain
│ │ │ ├ WhiteParticleFountain
│ │ │ └ YellowParticleFountain
│ │ ├ PathFollower
│ │ │ ├ ActorMover
│ │ │ └ MovingCamera
│ │ ├ PatrolPoint
│ │ ├ PatrolSpecial
│ │ ├ PhoenixFX1
│ │ ├ PhoenixFX2
│ │ ├ PhoenixPuff
│ │ ├ PhosphorousFire
│ │ ├ PhosphorousGrenade
│ │ ├ PickupFlash
│ │ ├ PileOfGuts
│ │ ├ PillarAlienPower
│ │ ├ PillarAztec
│ │ ├ PillarAztecDamaged
│ │ ├ PillarAztecRuined
│ │ ├ PillarHugeTech
│ │ ├ PillarTechno
│ │ ├ Piston
│ │ ├ Pitcher
│ │ ├ PlasmaBall
│ │ │ ├ PhaseZorchMissile
│ │ │ └ PlasmaBall1
│ │ │   └ PlasmaBall2
│ │ ├ PlayerPawn
│ │ │ ├ ChickenPlayer
│ │ │ ├ ClericPlayer
│ │ │ ├ DoomPlayer
│ │ │ │ └ ChexPlayer
│ │ │ ├ FighterPlayer
│ │ │ ├ HereticPlayer
│ │ │ ├ MagePlayer
│ │ │ ├ PigPlayer
│ │ │ ├ PlayerChunk
│ │ │ │ ├ BloodyFighterSkull
│ │ │ │ ├ BloodySkull
│ │ │ │ └ IceChunkHead
│ │ │ └ StrifePlayer
│ │ ├ PlayerSpeedTrail
│ │ ├ Pod
│ │ ├ PodGenerator
│ │ ├ PodGoo
│ │ ├ PointPuller
│ │ ├ PointPusher
│ │ ├ PoisonBag
│ │ │ └ ZPoisonShroom
│ │ ├ PoisonBolt
│ │ ├ PoisonCloud
│ │ ├ PoleLantern
│ │ ├ Pot
│ │ ├ PottedTree
│ │ ├ Pottery1
│ │ │ ├ Pottery2
│ │ │ └ Pottery3
│ │ ├ PotteryBit
│ │ ├ PowerCoupling
│ │ ├ PowerCrystal
│ │ ├ Programmer
│ │ ├ ProgrammerBase
│ │ ├ ProjectileBlade
│ │ ├ Puffy
│ │ ├ PunchPuff
│ │ ├ QuietusDrop
│ │ ├ RainPillar
│ │ ├ RandomSpawner
│ │ ├ RatBuddy
│ │ ├ RealGibs
│ │ │ └ Gibs
│ │ ├ Reaver
│ │ ├ RebelBoots
│ │ ├ RebelHelmet
│ │ ├ RebelShirt
│ │ ├ RedTorch
│ │ ├ Revenant
│ │ │ └ StealthRevenant
│ │ ├ RevenantTracer
│ │ ├ RevenantTracerSmoke
│ │ ├ Ripper
│ │ ├ RipperBall
│ │ ├ Rock1
│ │ ├ Rock2
│ │ ├ Rock3
│ │ ├ Rocket
│ │ │ └ PropulsorMissile
│ │ ├ RocketSmokeTrail
│ │ ├ RocketTrail
│ │ ├ Rubble1
│ │ ├ Rubble2
│ │ ├ Rubble3
│ │ ├ Rubble4
│ │ ├ Rubble5
│ │ ├ Rubble6
│ │ ├ Rubble7
│ │ ├ Rubble8
│ │ ├ SacrificedGuy
│ │ ├ ScriptedMarine
│ │ │ ├ MarineBFG
│ │ │ ├ MarineChaingun
│ │ │ ├ MarineChainsaw
│ │ │ ├ MarineFist
│ │ │ │ ├ MarineBerserk
│ │ │ │ └ MarineRocket
│ │ │ ├ MarinePistol
│ │ │ ├ MarinePlasma
│ │ │ ├ MarineRailgun
│ │ │ ├ MarineShotgun
│ │ │ └ MarineSSG
│ │ ├ SecretTrigger
│ │ ├ SectorAction
│ │ │ ├ MusicChanger
│ │ │ ├ SecActDamage3D
│ │ │ ├ SecActDamageCeiling
│ │ │ ├ SecActDamageFloor
│ │ │ ├ SecActDeath3D
│ │ │ ├ SecActDeathCeiling
│ │ │ ├ SecActDeathFloor
│ │ │ ├ SecActEnter
│ │ │ ├ SecActExit
│ │ │ ├ SecActEyesAboveC
│ │ │ ├ SecActEyesBelowC
│ │ │ ├ SecActEyesDive
│ │ │ ├ SecActEyesSurface
│ │ │ ├ SecActHitCeil
│ │ │ ├ SecActHitFakeFloor
│ │ │ ├ SecActHitFloor
│ │ │ ├ SecActUse
│ │ │ └ SecActUseWall
│ │ ├ SectorFlagSetter
│ │ ├ SectorSilencer
│ │ ├ SecurityCamera
│ │ │ └ AimingCamera
│ │ ├ Sentinel
│ │ ├ SentinelFX1
│ │ │ └ SentinelFX2
│ │ ├ Serpent
│ │ │ └ SerpentLeader
│ │ ├ SerpentFX
│ │ ├ SerpentGib1
│ │ │ ├ SerpentGib2
│ │ │ └ SerpentGib3
│ │ ├ SerpentHead
│ │ ├ ShortBlueTorch
│ │ │ └ ChexLightColumn
│ │ ├ ShortBush
│ │ ├ ShortGreenColumn
│ │ │ └ ChexSubmergedPlant
│ │ ├ ShortGreenTorch
│ │ │ └ ChexCivilian2
│ │ ├ ShortRedColumn
│ │ │ └ ChexMineCart
│ │ ├ ShortRedTorch
│ │ │ └ ChexCivilian3
│ │ ├ ShotgunGuy
│ │ │ ├ DeadShotgunGuy
│ │ │ ├ FlemoidusBipedicus
│ │ │ └ StealthShotgunGuy
│ │ ├ SigilBanner
│ │ ├ SkullColumn
│ │ │ └ ChexFlagOnPole
│ │ ├ SkyPicker
│ │ ├ SkyViewpoint
│ │ │ ├ SkyCamCompat
│ │ │ └ StackPoint
│ │ │   ├ LowerStackLookOnly
│ │ │   └ UpperStackLookOnly
│ │ ├ SlimeChunk
│ │ ├ SlimeSplash
│ │ ├ SludgeChunk
│ │ ├ SludgeSplash
│ │ ├ SmallBloodPool
│ │ ├ SmallTorchLit
│ │ ├ SmallTorchUnlit
│ │ ├ Snake
│ │ ├ SnakeProjA
│ │ │ └ SnakeProjB
│ │ ├ SnoutPuff
│ │ ├ SorcBall
│ │ │ ├ SorcBall1
│ │ │ ├ SorcBall2
│ │ │ └ SorcBall3
│ │ ├ Sorcerer1
│ │ ├ Sorcerer2
│ │ ├ Sorcerer2FX1
│ │ ├ Sorcerer2FX2
│ │ ├ Sorcerer2FXSpark
│ │ ├ Sorcerer2Telefade
│ │ ├ SorcererFX1
│ │ ├ SorcFX1
│ │ ├ SorcFX2
│ │ │ └ SorcFX2T1
│ │ ├ SorcFX3
│ │ ├ SorcFX3Explosion
│ │ ├ SorcFX4
│ │ ├ SorcSpark1
│ │ ├ SoundEnvironment
│ │ ├ SoundSequence
│ │ │ ├ HereticSoundSequence1
│ │ │ ├ HereticSoundSequence10
│ │ │ ├ HereticSoundSequence2
│ │ │ ├ HereticSoundSequence3
│ │ │ ├ HereticSoundSequence4
│ │ │ ├ HereticSoundSequence5
│ │ │ ├ HereticSoundSequence6
│ │ │ ├ HereticSoundSequence7
│ │ │ ├ HereticSoundSequence8
│ │ │ └ HereticSoundSequence9
│ │ ├ SoundSequenceSlot
│ │ ├ SoundWaterfall
│ │ ├ SoundWind
│ │ │ └ SoundWindHexen
│ │ ├ Spark
│ │ ├ SpawnFire
│ │ ├ SpawnShot
│ │ ├ SpecialSpot
│ │ │ ├ BossSpot
│ │ │ ├ BossTarget
│ │ │ └ MaceSpawner
│ │ ├ SpectralLightningBase
│ │ │ ├ SpectralLightningBall1
│ │ │ │ └ SpectralLightningBall2
│ │ │ ├ SpectralLightningDeath1
│ │ │ │ ├ SpectralLightningBigV1
│ │ │ │ │ └ SpectralLightningBigV2
│ │ │ │ └ SpectralLightningSpot
│ │ │ ├ SpectralLightningDeath2
│ │ │ │ └ SpectralLightningBigBall1
│ │ │ │   └ SpectralLightningBigBall2
│ │ │ ├ SpectralLightningDeathShort
│ │ │ │ └ SpectralLightningV1
│ │ │ │   └ SpectralLightningV2
│ │ │ └ SpectralLightningH1
│ │ │   ├ SpectralLightningH2
│ │ │   └ SpectralLightningH3
│ │ ├ SpectralLightningHTail
│ │ ├ SpectralMonster
│ │ │ ├ AlienSpectre1
│ │ │ │ ├ AlienSpectre2
│ │ │ │ ├ AlienSpectre3
│ │ │ │ ├ AlienSpectre4
│ │ │ │ └ AlienSpectre5
│ │ │ ├ EntityBoss
│ │ │ └ EntitySecond
│ │ ├ SpiderMastermind
│ │ ├ SRock1
│ │ ├ SRock2
│ │ ├ SRock3
│ │ ├ SRock4
│ │ ├ SStalactiteBig
│ │ ├ SStalactiteSmall
│ │ ├ SStalagmiteBig
│ │ ├ SStalagmiteSmall
│ │ ├ StaffPuff
│ │ │ └ BeakPuff
│ │ ├ StaffPuff2
│ │ ├ Stalagmite
│ │ ├ Stalagtite
│ │ │ └ ChexAppleTree
│ │ ├ Stalker
│ │ ├ Statue
│ │ ├ StatueRuined
│ │ ├ StickInWater
│ │ ├ Stool
│ │ ├ StrifeBishop
│ │ ├ StrifeBurningBarrel
│ │ ├ StrifeCandelabra
│ │ ├ StrifeHumanoid
│ │ │ ├ Acolyte
│ │ │ │ ├ AcolyteBlue
│ │ │ │ ├ AcolyteDGreen
│ │ │ │ ├ AcolyteGold
│ │ │ │ ├ AcolyteGray
│ │ │ │ ├ AcolyteLGreen
│ │ │ │ ├ AcolyteRed
│ │ │ │ ├ AcolyteRust
│ │ │ │ ├ AcolyteShadow
│ │ │ │ ├ AcolyteTan
│ │ │ │ └ AcolyteToBe
│ │ │ ├ Beggar
│ │ │ │ ├ Beggar1
│ │ │ │ ├ Beggar2
│ │ │ │ ├ Beggar3
│ │ │ │ ├ Beggar4
│ │ │ │ └ Beggar5
│ │ │ ├ Peasant
│ │ │ │ ├ Peasant1
│ │ │ │ ├ Peasant10
│ │ │ │ ├ Peasant11
│ │ │ │ ├ Peasant12
│ │ │ │ ├ Peasant13
│ │ │ │ ├ Peasant14
│ │ │ │ ├ Peasant15
│ │ │ │ ├ Peasant16
│ │ │ │ ├ Peasant17
│ │ │ │ ├ Peasant18
│ │ │ │ ├ Peasant19
│ │ │ │ ├ Peasant2
│ │ │ │ ├ Peasant20
│ │ │ │ ├ Peasant21
│ │ │ │ ├ Peasant22
│ │ │ │ ├ Peasant3
│ │ │ │ ├ Peasant4
│ │ │ │ ├ Peasant5
│ │ │ │ ├ Peasant6
│ │ │ │ ├ Peasant7
│ │ │ │ ├ Peasant8
│ │ │ │ └ Peasant9
│ │ │ ├ Rebel
│ │ │ │ ├ Rebel1
│ │ │ │ ├ Rebel2
│ │ │ │ ├ Rebel3
│ │ │ │ ├ Rebel4
│ │ │ │ ├ Rebel5
│ │ │ │ └ Rebel6
│ │ │ └ Zombie
│ │ ├ StrifePuff
│ │ │ ├ MiniMissilePuff
│ │ │ └ StrifeSpark
│ │ ├ SummoningDoll
│ │ ├ SurgeryCrab
│ │ ├ SVEOreSpawner
│ │ ├ SwitchableDecoration
│ │ │ ├ BatSpawner
│ │ │ ├ FlameLarge
│ │ │ │ └ FlameLarge2
│ │ │ ├ FlameSmall
│ │ │ │ └ FlameSmall2
│ │ │ ├ SwitchingDecoration
│ │ │ │ ├ ZGemPedestal
│ │ │ │ └ ZWingedStatueNoSkull
│ │ │ ├ ZCauldron
│ │ │ │ └ ZCauldronUnlit
│ │ │ ├ ZFireBull
│ │ │ │ └ ZFireBullUnlit
│ │ │ ├ ZTwinedTorch
│ │ │ │ └ ZTwinedTorchUnlit
│ │ │ └ ZWallTorch
│ │ │   └ ZWallTorchUnlit
│ │ ├ TableShit1
│ │ ├ TableShit10
│ │ ├ TableShit2
│ │ ├ TableShit3
│ │ ├ TableShit4
│ │ ├ TableShit5
│ │ ├ TableShit6
│ │ ├ TableShit7
│ │ ├ TableShit8
│ │ ├ TableShit9
│ │ ├ TallBush
│ │ ├ TallGreenColumn
│ │ │ └ ChexCavernStalagmite
│ │ ├ TallRedColumn
│ │ │ └ ChexCavernColumn
│ │ ├ Tank1
│ │ ├ Tank2
│ │ ├ Tank3
│ │ ├ Tank4
│ │ ├ Tank5
│ │ ├ Tank6
│ │ ├ TargetPractice
│ │ ├ TechLamp
│ │ ├ TechLamp2
│ │ ├ TechLampBrass
│ │ ├ TechLampSilver
│ │ ├ TechPillar
│ │ │ └ ChexSpaceship
│ │ ├ TeleGlitter1
│ │ │ └ TeleGlitter2
│ │ ├ TeleGlitterGenerator1
│ │ ├ TeleGlitterGenerator2
│ │ ├ TeleportDest
│ │ │ └ TeleportDest2
│ │ │   └ TeleportDest3
│ │ ├ TeleportFog
│ │ ├ TeleportSwirl
│ │ ├ TeleSmoke
│ │ ├ TelOtherFX1
│ │ │ ├ TelOtherFX2
│ │ │ ├ TelOtherFX3
│ │ │ ├ TelOtherFX4
│ │ │ └ TelOtherFX5
│ │ ├ Templar
│ │ ├ ThrowingBomb
│ │ ├ ThrustFloor
│ │ │ ├ ThrustFloorDown
│ │ │ └ ThrustFloorUp
│ │ ├ TorchTree
│ │ │ └ ChexOrangeTree
│ │ ├ Tray
│ │ ├ TreeDestructible
│ │ ├ TreeStub
│ │ ├ Tub
│ │ ├ Unknown
│ │ │ └ SpeakerIcon
│ │ ├ Volcano
│ │ ├ VolcanoBlast
│ │ ├ VolcanoTBlast
│ │ ├ WaterBottle
│ │ ├ WaterDrip
│ │ ├ WaterDropOnFloor
│ │ ├ WaterfallSplash
│ │ ├ WaterFountain
│ │ ├ WaterSplash
│ │ ├ WaterSplashBase
│ │ ├ WaterZone
│ │ ├ Whirlwind
│ │ ├ Wizard
│ │ ├ WizardFX1
│ │ ├ WolfensteinSS
│ │ ├ WoodenBarrel
│ │ ├ Wraith
│ │ │ └ WraithBuried
│ │ ├ WraithFX1
│ │ ├ WraithFX2
│ │ ├ WraithFX3
│ │ ├ WraithFX4
│ │ │ └ WraithFX5
│ │ ├ WraithvergeDrop
│ │ ├ ZArmorChunk
│ │ ├ ZBannerTattered
│ │ ├ ZBarrel
│ │ ├ ZBell
│ │ ├ ZBlueCandle
│ │ ├ ZBucket
│ │ ├ ZCandle
│ │ ├ ZChainBit32
│ │ ├ ZChainBit64
│ │ ├ ZChainEndHeart
│ │ ├ ZChainEndHook1
│ │ ├ ZChainEndHook2
│ │ ├ ZChainEndSkull
│ │ ├ ZChainEndSpike
│ │ ├ ZChandelier
│ │ ├ ZChandelierUnlit
│ │ ├ ZCorpseHanging
│ │ ├ ZCorpseKabob
│ │ ├ ZCorpseLynched
│ │ ├ ZCorpseLynchedNoHeart
│ │ ├ ZCorpseSitting
│ │ ├ ZCorpseSleeping
│ │ ├ ZIronMaiden
│ │ ├ ZLog
│ │ ├ ZMossCeiling1
│ │ ├ ZMossCeiling2
│ │ ├ ZombieMan
│ │ │ ├ DeadZombieMan
│ │ │ ├ FlemoidusCommonus
│ │ │ └ StealthZombieMan
│ │ ├ ZombieSpawner
│ │ ├ ZRock1
│ │ ├ ZRock2
│ │ ├ ZRock3
│ │ ├ ZRock4
│ │ ├ ZRockBlack
│ │ ├ ZRockBrown1
│ │ ├ ZRockBrown2
│ │ ├ ZRubble1
│ │ ├ ZRubble2
│ │ ├ ZRubble3
│ │ ├ ZShroomLarge1
│ │ ├ ZShroomLarge2
│ │ ├ ZShroomLarge3
│ │ ├ ZShroomSmall1
│ │ ├ ZShroomSmall2
│ │ ├ ZShroomSmall3
│ │ ├ ZShroomSmall4
│ │ ├ ZShroomSmall5
│ │ ├ ZShrub1
│ │ ├ ZShrub2
│ │ ├ ZStalactiteIceLarge
│ │ ├ ZStalactiteIceMedium
│ │ ├ ZStalactiteIceSmall
│ │ ├ ZStalactiteIceTiny
│ │ ├ ZStalactiteLarge
│ │ ├ ZStalactiteMedium
│ │ ├ ZStalactiteSmall
│ │ ├ ZStalagmiteIceLarge
│ │ ├ ZStalagmiteIceMedium
│ │ ├ ZStalagmiteIceSmall
│ │ ├ ZStalagmiteIceTiny
│ │ ├ ZStalagmiteLarge
│ │ ├ ZStalagmiteMedium
│ │ ├ ZStalagmitePillar
│ │ ├ ZStalagmiteSmall
│ │ ├ ZStatueGargoyleBlueShort
│ │ ├ ZStatueGargoyleBlueTall
│ │ ├ ZStatueGargoyleDarkRedShort
│ │ ├ ZStatueGargoyleDarkRedTall
│ │ ├ ZStatueGargoyleGreenShort
│ │ ├ ZStatueGargoyleGreenTall
│ │ ├ ZStatueGargoyleRedShort
│ │ ├ ZStatueGargoyleRedTall
│ │ ├ ZStatueGargoyleRustShort
│ │ ├ ZStatueGargoyleRustTall
│ │ ├ ZStatueGargoyleStripeTall
│ │ ├ ZStatueGargoyleTanShort
│ │ ├ ZStatueGargoyleTanTall
│ │ ├ ZStumpBare
│ │ ├ ZStumpBurned
│ │ ├ ZStumpSwamp1
│ │ ├ ZStumpSwamp2
│ │ ├ ZSuitOfArmor
│ │ ├ ZSwampVine
│ │ ├ ZTombstoneBigCross
│ │ ├ ZTombstoneBrianP
│ │ ├ ZTombstoneBrianR
│ │ ├ ZTombstoneCrossCircle
│ │ ├ ZTombstoneRIP
│ │ ├ ZTombstoneShane
│ │ ├ ZTombstoneSmallCross
│ │ ├ ZTree
│ │ ├ ZTreeDead
│ │ ├ ZTreeGnarled1
│ │ ├ ZTreeGnarled2
│ │ ├ ZTreeLarge1
│ │ ├ ZTreeLarge2
│ │ ├ ZTreeSwamp120
│ │ ├ ZTreeSwamp150
│ │ ├ ZVasePillar
│ │ ├ ZWingedStatue
│ │ └ ZXmasTree
│ └ SectorEffect
│   ├ Lighting
│   └ Mover
│     ├ MovingCeiling
│     │ └ Ceiling
│     └ MovingFloor
│       └ Floor
└ ThinkerIterator
```

<!-- EOF -->
