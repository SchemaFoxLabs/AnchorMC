## SubServer:
 [+|-] Practice

Core Change: optimize some technology debt,Improve core performance,Design Roadmap

#### Gameplay
[+] New KnockBack System and Misplace + Delay position packet send
[+] Optimized Pearl and all projectiles vanilla yaw offset and force removed "glow(0.3,0.3,0.3)"(be OpenSource at future)
[+]  - Feat: Hits(Boxing)'s Hits Display On nametag(Customizable)
[+]  - Feat: Custom Fake Corpse style Free for all players
[~]  - Feat: Multi Kits Support in queue
[+]  - Feat: New Get Ping tool  /ping <player>
[+]  - Feat: Practice Settings restructuring
[+]  - Kit: BedFight
[+]  - Kit: FinalFight
[+]  - Kit: BuildUHC
[-] Remove 14CPS Limit
[-] Remove Old Ranks and permission model


#### Tech Upgrade
[+] [Spigot Core replacement](https://github.com/error-nullindex/BambooSpigot)
[+] Rebuild Skript for single thread performance enhance,Native YAML support,"wait" syntax optimization(For anti repeat task bukkit creation),etc.
[+] Add SkPacketManager for native Packet control
[+] Add FightEnhancePatch for KnockBack Customize
[+] New AntiCheat in developing
[+] Improve movement position update speed
[+|-] Data structure optimize

#### Refactor
[+] Rebuild RecastPractice(SakuraFox) Skript Practice:
		 - YAML Config
		 - Practice Settings
		 - Variables cleaning
		 - Multi Page stackoverflow fix
		 - NullpointerExpectation Fix(When "fight end" variable cannot clean on server stopped)


#### Fix and Improvements
[+]  - Feat: Requeue experience optimization:
		 ~ Faster requeue
		 ~ Faster container opening speed
[+] Solved issue when FireBall Fight Requeue: Player enter the void arena
[-] Deleted unsafe plugins

Maps are no any changes,used original in Practice serverclient

---

Future Iteration:
 - PartyPVP
 - Global Knockback Refinement
 - Kit: BlockPlacement
 - Kit: MLG Rush
 - Kit: Flame
 - Kit: Spleef
 - Kit: Bridger
 - Kit: Combo Fly
 - Event: Sumo Event
 - Event: Random Fight
 - Event: Sky Killer
 - Event: Ninja
 - Event: Escape the serial killer
 - Event: Typing
 - More map replacement
