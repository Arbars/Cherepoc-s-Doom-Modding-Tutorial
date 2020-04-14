Движок Doom
===========

Словосочетание **Движок Doom** относится к той части программы, что даёт возможность запускать игры **Doom** и **Doom II**, в отличии от наборов данных этих игр. In a strict sense, the engine is the [[Wikipedia:Executable|executable]] elements of the games, based on the corresponding [[Wikipedia:Source code|source code]], as opposed to [[WAD]] and [[lump]] files. Various [[Versions of Doom and Doom II|versions]] of the engine were released by id Software for the PC games, one per release but often shared by both games, as the same executables are used for both, only renamed accordingly.

The engine is composed of a [[Doom rendering engine|rendering engine]] which structures game levels and handles movement, effects, and obstructions during play, and an auxiliary [[Doom networking component]] to connect computers during [[multiplayer]] games. Additionally, the engine includes a [[sound]] management system, of which, unlike the rendering and networking functionality, the sources were not fully released to the public, as they included [[Wikipedia:Proprietary software|proprietary]] code written by [[Paul Radek]].

The latest version of the engine released for the games is the one included with [[Versions of Doom and Doom II|version 1.9]] of each game, although slightly modified versions were later issued with [[The Ultimate Doom]] and then [[Final Doom]] ([[John Carmack]], the main programmer, was not really involved in those two releases, and they are marked as "v1.9" notwithstanding the differences). The released source code, that includes some differences from the DOS incarnations to make the code more portable, is conveniently marked as version 1.10.

Note that id sometimes officially refers to the Doom engine as '''id Tech 1''' in their new game engine naming scheme, which was established after work began on the engine known as {{wp|id Tech 5}}, which powered ''{{wp|Rage (video game)|Rage}}''. This enumeration also contained the engine for [[Doom 3]], known as [[id Tech 4]], [[id Tech 6]] which powers [[Doom (2016)]], and the newest [[id Tech 7]] engine used by [[Doom Eternal]].

== As a game engine ==

In a more abstract sense, the ''Doom engine'' is the use of the [[Doom source code]] or the executable parts as a starting point for another game. This aspect is similar to the more novel concept of [[Wikipedia:Game engine|game engine]], although the Doom games precede the concept and, while designed with greater [[Wikipedia:Mod (computer gaming)|moddability]] than many earlier [[Wikipedia:First person shooter|FPS]] titles such as [[Wolfenstein 3D]], the Doom engine differs from newer game engines in that it does not offer a definite core separated from the game-specific rules, and does not provide the greater degree of hardware abstraction most newer engines offer. It has provided developers an engine which is to be used as a modifiable example, rather than a multi-platform core to be used as a base.

=== Use in ports and other games ===

Aside from the seminal [[Doom games]], the engine has been used for several commercial games:

*[[Heretic]] (1994): A [[wikipedia:Fantasy|fantasy]] themed [[shareware]] game developed by [[Raven Software]] and published by [[id Software]], arranged into three episodes like [[Doom]]. The engine is based on [[Versions of Doom and Doom II#v1.2|Doom version 1.2]] and adds flying (for the [[player]]), the ability to look up and down, an inventory system allowing the user to select when to use certain [[item]]s and power-ups, and [[monster]]s with multiple ranged attacks.
** Heretic: Shadow of the Serpent Riders (1995): An expanded release of Heretic prepared for distribution in retail stores, much like [[The Ultimate Doom]] is in regard to Doom (and likewise free for those with a registered copy of the shareware game), adding two extra episodes plus another three additional bonus levels.

*[[Hexen]] (1995): The second fantasy game title by Raven Software published by id Software. It is the sequel to Heretic and the engine is based on Heretic's. It adds distinct player classes with varying attributes, class-custom weapons with progressive power, a scripting language permitting customized game behavior, and a hub system allowing the player to return to previous levels as an alternative to the linear episode system.
**[[Hexen: Deathkings of the Dark Citadel]] (1996): An expansion for use with Hexen providing additional levels, by the same authors, released as a separate product.

*[[Strife]] (1996): A science fiction game developed by [[Rogue Entertainment]] and published by [[Velocity Incorporated|Velocity]]. Its engine is based on [[Versions of Doom and Doom II#v1.666|version 1.666]] of the Doom engine, and the game includes [[Wikipedia:Non-playing character|NPCs]] the player can interact with and accept missions from, a degree of player character progression, and a particularly non-linear hub system.

*[[Chex Quest]] (1996): A modification of The Ultimate Doom styled after the [[Wikipedia:Chex|Chex Cereal]] brand, developed by [[Wikipedia:Digital Café|Digital Café]] and included in cereal boxes as a promotional bonus item. The game uses an engine based on the source code for The Ultimate Doom, modified to accommodate some necessary changes.

*[[Hacx]] (1997): A full stand-alone modification of [[Doom II]] [[Versions of Doom and Doom II#v1.9|version 1.9]], developed by [[Banjo Software]]. Unlike the games listed above, its developers relied on reverse engineering instead of the source code, although it includes extensive and comprehensive changes to the behavior of [[monster]]s and weapons. Hacx was eventually released as an add-on for Doom II, free of charge.

Additionally, the engine has been [[Commercial games|adapted by various developers]] to run custom versions of the [[Wikipedia:Personal computer|PC]] games, or modifications of them, on various systems and environments, notably gaming consoles.

=== Fan community variants ===

With [[John Carmack]]'s release of the [[Doom source code]] in 1997, the Doom games and community have benefited from ports and modifications of the engine developed by many people around the world. These engines can run the original [[Doom games]] and sometimes other games using the engine as a base (see above). These versions produced by programmers among the fan community are commonly known as [[source port]]s, as distinguished from the engines included with the games. 

==== Vanilla Doom ====

As a result of the distinction between the official and fan-made engines, the name ''[[Wikipedia:Vanilla software|vanilla]] Doom'' (or ''vanilla [[Heretic]]'', etc.) is sometimes used by fans, especially by regular [[source port]] users and developers, to describe the original executables themselves, the act of playing with the original executables, or a feature, phenomenon, or [[add-on]] that complies with the standard engine to one degree or another (either being strictly compatible, or not having or using characteristics found only in source ports). 
