<span lang="fr">[Traduction française](README_fr.md)</span> <span lang="ht">[Tradiksyon kreyòl Ayisyen an](README_ht.md)</span>
# haitian-creole-braille
Contains Liblouis tables, NVDA add-on, and related tools for Haitian Creole Braille.

## What is this?
This repository contains a Braille table compatible with Liblouis which can translate Braille for Haitian Creole.

## How to use the table
We provide two versions of the table. One is the Liblouis table file which can be included with any Liblouis table directory, and one is a packaged version for NVDA which can be easily installed into any compatible version of NVDA to immediately add the table.

### How to use the NVDA version
The NVDA Braille table is compatible with NVDA 2024.3 or newer. Download the latest version of the NVDA addon [here](https://s.seeinghands.org/haitianbraillenvdalatest) or see all versions available on the [releases page](https://github.com/seeing-hands/haitian-creole-braille/releases). Once you have downloaded the package, go to the NVDA menu, tools menu, add-on store, and select to install an add-on from an external source. Browse to the file you downloaded and follow the steps. Once you restart NVDA, the Haitian Braille table can be selected by going to NVDA's Braille settings.

### How to use the standalone Liblouis version
Download the latest version of the Liblouis table file [here](https://s.seeinghands.org/haitianbrailleliblouislatest) or see all versions available on the [releases page](https://github.com/seeing-hands/haitian-creole-braille/releases). The table is a single file which must be placed in the tables directory where your version of Liblouis searches by default. Where that directory is depends on where you have installed Liblouis. On Unix-like systems, this is usually /usr/share/liblouis/tables, but it may be somewhere else. Once there, you can select the ht-ht-g1.ctb file in any client program of Liblouis and translate using the rules for Haitian Creole.

## Support and feedback
If you have problems using this table, find its translations to be incorrect, or want to talk to those who created it, you can reach the team by sending email to haitianbraille@seeinghands.org.