---
layout: default.liquid
title: Contributing
---
# Contributing

## translation
To translate, you don't need any programming structure. Copy the template_lang.lng and put it into the lang folder.

Next, rename the template_lang.lng in the lang folder to the name of your translation language, with the first character being possible capital, eg Burmese.

You can then translate contents according to these rules.
* Translation content is separated by an equal sign (`=`).
* The left part of the string is the identifyer (ID) that is used internally in the game. Therefore, you must not translate the ID, the first left part of the string.
* The right and the last part of the string is the content that you need to be translated.
* Dynamic variable starts with a left brace `{` and ends with a right brace `}`, with the variable number being in the middle of the opening and closing braces. As such, you must not translate the variable numbers, for instance, `{1} health`. In this context, you don't have to translate the `{1}` because it is the variable which will be replaced itself with the value.

If new IDs are available because of an update, they will be written in changelog, therefore translators are recommended to read the change log, the translation section at least.