---
title: Translation
weight: 20
layout: doc
---
# %title%
To translate, copy the English files and folders (en). For the most update English version we recommend [downloading from this link](https://github.com/gamemgh/langs/releases/download/lang/en.zip).

Note: Language codes must be always lowercase. You can use upper case for country codes. For example, en-US means en is language code, and US is the country code, so US can be uppercase.

Note 2: config.toml is the file require to provide you and your language information.

## Updated keys
English translations might have new keys or existing keys updated. To view the updated keys ordered by date, visit [updated translation keys page](https://github.com/gamemgh/langs/blob/main/keys.md)

If there is a new file added you have to copy that new file. Otherwise, if existing or new keys are updated, you have to look at above link for the list (just remember the last date you downloaded English file). Carefully copy each updated or new keys if the file already exists.

## Config file
Config file has the following keys:

Main keys; these are keys that are directly put at the top of the file:
- `name`: Your language full name

Author keys; the following is a list of keys that must be put in the `author` section:
- `name`: Your name or group of names.
- `homepage`: Your website, or contact link, or email. If it is email, start with the prefix `mailto:` before your email.
