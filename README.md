# Leviathan
A fractal, scalable, and setting agnostic framework for modeling societal structures in roleplaying games

## Scope
This project is intended to allow simple societal simulations at a level of detail consistent with table-top role-playing games (TTRPG). Sometimnes PCs want to manage their own holdings - to explore what it could be like to lead any organization in whatever setting.

## Key Principles

### Fractal and Scalable
The overall system is based on societal groups in a lograithmic scale (base 10), varying from size 0 (1; an individual) to any positive integer. For example, a holding at size 6 equates to an approximate scale of $10^6$ (1,000,000). Supposing that the holding of interest is size $n$, most interesting play will only involve interacting with organizations one size larger ($n+1$) and one size smaller ($n-1$). Naturally infrastructure and actions scale with the size of the holding - some actions only make sense for very small or very large holding sizes.

### Setting Agnostic
Organized societies in TTRPGs can exist in many times, places, and technology levels, and operate under whatever rules a given setting cleaves to. The core engine is intentionally setting agnostic, with setting-specific information (holding types, actions, infrastrucutre, etc.) provided in .json and .csv files. Similarly, because folks enjoy playing their TTRPGs with a nearly infinite variety of rule sets, many simulation engine operations are abstracted to allow users to specify rulesets using .json and .csv files. The intent is to enable users to use D&D5e, World of Darkness, Savage Worlds, or whatever ruleset they please.
