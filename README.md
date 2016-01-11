# PocketMine-Windows-x86-PHP7-launcher
PHP 7-based PocketMine launcher (for Win x86)

This launcher must be need vcredist x86 (or x86)
before you launch the program, please setup vcredist
https://www.microsoft.com/en-us/download/details.aspx?id=48145

You can download of the 'Download ZIP'
I added some plug-ins and some patch for PocketMine-MP.phar

If you seen this error, you must install right vcredist.
----------------------------------
'/usr/bin/php/php.exe: error while loading shared libraries: VCRUNTIME140.dll: cannot open shared object file: No such file or dire ctory bin\php\php.exe: Exit 127'

(mean if you are installed x86, so you need x64 or if you are installed x64, so you need x86)

Launcher version
----------------------------------
- PHP 7.0.1 official x86
- PocketMine 1.6 (API 2.0.0) 
- MC:PE 0.13.1 Support

Plugins Descript
----------------------------------
- DevTools - Plug-in extract to soruce and, package to phar(for PHP7)
- EntityManager - This is a plug-in that allows you to move entities in PocketMine-MP
- SpawningPool - increase the multi-core computing power (parallel computing)
- PlayHarder - Hunger and experience in PocketMine 
- MyDearest - Automatic Reboot and Re-run (for windows launcher support)
- ExternalIPChecker - Show External Ip when server started
- CommandDefender - Prevent 'command bombard' and 'chat bombard' on PocketMine
- CraftingTableFix - CraftingItem Problem fix
- Farms - Crops growth control in PocketMine
- MoreTrees - Increases the amount of tree on PocketMine
- BenchMark - Show location in-game screen
- Gentleman - Block expletives chat in PocketMine

PHAR Patched
----------------------------------
- Fixed "error: assert($this->namedtag->Item instanceof CompoundTag)" problem
- Fixed Async CompressedPacket initialize (__construct array, serialize -> unserialize applied)
- I compared php7 branch and mcpe0.12 branch and fixed conflict problem

[Special Thanks] if(Team); Peoples (https://github.com/if-Team)

[추신] 한국어 버전이 필요하시면 MCPE KOREA를 참조해주세요 (っ´▽`)っ
