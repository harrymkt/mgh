---
layout: default.liquid
title: To Do List
---
# To Do List
This list contains code improvements or libraries that are still need to be defined, added, used, modified, replaced or otherwise changed in order to get the best possible working.
{%assign nol="There are currently no tasks left."%}
## Translation system
Currently, we used a private translation system which features including dynamic variables and using IDs, fallback dictionary if the translated ID is not found for the current selected language, and so on. Unfortunately, this system is at least for now, but not the advance level. This system is not ideal for the following reasons:
1. The system's dynamic variables feature is not good enough to translate. For example, `a {1} is {2}, about {3} tiles away`. In this case, `{2}` is the variable which tells the direction, in front, behind, etc. However, we cannot subtranslate the part such as `in front`, `behind`, etc, because the dynamic variables feature can only translate once for a given ID. Either we must find a good system for this task, or use the messages instead of IDs, which could have more control over the translations, but we will still have the problem of lower and upper case for the messages again in this one, so we need to decide the best use of system for the translation.
2. We could also use the regular expression provided by NVGT to determine the location of the translation strings by using wildcards all over the messages while the dynamic variables system is still being used but with improvements because in the regular expression patterns we don't need to use the regular replace functions, since it already finds a matching pattern and replaces itself. If we made it, then it will be a hundred percent reliable translation system, but it requires learning and additional time because the regular expression patterns are tricky, so any help would be appreciated. Using this system will avoid having to change to message base translation.