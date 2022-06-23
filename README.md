# Leviathan
A fractal, scalable, and setting agnostic framework for modeling societal structures in roleplaying games

## Scope
This project is intended to allow simple societal simulations at a level of detail consistent with role-playing games (RPGs). Sometimnes player characters (PCs) want to manage their own holdings - to explore what it could be like to lead any organization in whatever setting.

## Principles

### Fractal and Scalable
The Leviathan system is based on societal groups in a lograithmic scale (base 10). The size ($n$) varies from size 0 ($10^0=1$; an individual) to any positive integer ($n \in \[ 0, \infty)$). For example, a holding at size $n=6$ equates to an approximate scale of $10^6$ (1,000,000). Supposing that the holding of interest is size $n$, much play will only involve interacting with organizations one size larger ($n+1$) and one size smaller ($n-1$). Naturally infrastructure and actions scale with the size of the holding - some actions only make sense for very small or very large holding sizes.

### Setting Agnostic
Organized societies in RPGs can exist in many times, places, and technology levels, and operate under whatever rules a given setting cleaves to. The core engine is intentionally setting agnostic, with *setting* information (holding types, actions, infrastrucutre, etc.) provided in plain text .json and .csv files. Similarly, because folks enjoy playing RPGs with a nearly infinite variety of rule sets, many simulation engine operations are abstracted to allow users to specify *rulesets* using plain text .json and .csv files. The intent is to enable users to use published (e.g., D&D5e, World of Darkness, Savage Worlds) or custom *rulesets* as desired.

### Community Centered & Open Source
This project is on a public repository and accessible to the public commons. The fundamental action primitives identified in the *Documentation* are explicitly written for easy and accessible customization and creative use through input *rulesets*. Any individual or company is encouraged to use the Leviathan engine as they wish, whether that is simply changing *settings* 

## Documentation
The documentation of the Leviathan engine is here. Documentation for specific rulesets is elsewhere (TBD).

## Feature Roadmap
No time tables,  express or implied, are promised here. Since this is a passion project it requires... passion from the developers. Time will tell.
### Near Term
- Interface control for specifying *settings*
- Interface control for specifying *rulesets*
- Basic command prompt interface for simulating the holdings
### Long Term
- Example *settings* and *rulesets*
- A graphical user interface (perhaps with a web-based interface)

## Programming
The majority of the engine will be written in Python 3.X. The code in this repository will presume a virtual environment and will list all external library dependencies in 'requirements.txt'. Conversion to Cython or something similar will be considered in the future.

## Distribution
For now, the Leviathan engine is distributable through this repository. In the future a Python package may be made available.
