---
title: "To Do List"
---
# %title%
This list contains code improvements or libraries that are still need to be defined, added, used, modified, replaced or otherwise changed in order to get the best possible working and are beneficial to display in public interestry.

## Translation system{#translation}
Currently, we have a private translation system but it is not used yet, which features including dynamic variables and using IDs, fallback dictionary if the translated ID is not found for the current selected language, and so on. Unfortunately, this system is at least for now, but not the advance level. This system is not ideal for the following reasons:
1. The system's dynamic variables feature is not good enough to translate. For example, `a {1} is {2}, about {3} tiles away`. In this case, `{2}` is the variable which tells the direction, in front, behind, etc. However, we cannot subtranslate the part such as `in front`, `behind`, etc, because the dynamic variables feature can only translate once for a given ID. Either we must find a good system for this task, or use the messages instead of IDs, which could have more control over the translations, but we will still have the problem of lower and upper case for the messages again in this one, so we need to decide the best use of system for the translation.
2. We could also use the regular expression provided by NVGT to determine the location of the translation strings by using wildcards all over the messages while the dynamic variables system is still being used but with improvements, because in the regular expression patterns we don't need to use the regular replace functions, since it already finds a matching pattern and replaces itself. If we made it, then it will be a hundred percent reliable translation system, but it requires learning and additional time because the regular expression patterns are tricky, so any help would be appreciated. Using this system will avoid having to change to message base translation.

We're not sitting after asking your suggestions related to the translation. Instead, we're also discussing about the regular expression usage with the global NVGT community and looking for each of their response.

Until then, the translation system cannot be added into the game. The reason is that who will be using translation system if the directions as well as necessary informations can't be translated, such as directions (behind, in front, left, right, north, south), so it is why we have made up to only add the system after which the problem is solved.