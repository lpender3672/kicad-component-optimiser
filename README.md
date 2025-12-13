# kicad-component-optimiser
Having extended passive components increases cost but is typically required for good circuit performance.

This plugin aims to optimise component selection through series/parallel combinations of basic passive parts.
This also allows users to enter directly calculated values and the plugin will automatically select parts 

# goals
* Read part and value from schematic
* Write parts and values to schematic
* Connect to JLCPCB database to get readily available parts
* Write an optimiser to recreate component values from series/parallel combinations of basic parts.
* Include user defined allowable tolerance
* Include price penalty for large series/parallel combinations increased board space
* Include price penalty for extended parts
* Look at adding other part sources

# extension: global optimising
Instead of performing lots of local cost optimisation problems within user defined tolerance constraints, it would be better to global optimisation.
To do this however, the solver needs deep understanding of performance objectives and constraints.

## 
* work out how well posed a given circuit optimisation is
* ask for objective/constraints to make well posed
* minimise price/performance with pyspice model
* 
* add active components to pyspice?


