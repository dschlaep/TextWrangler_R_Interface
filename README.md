# TextWrangler interface to R

The content of this repository offers support for easier coding in R when using TextWrangler as the text editor.

The content is based on previous work. I modified and/or expanded on their great work for my own specific use cases.
	- Jonathan Marc Bearak [website](http://bearak.org/code/text/index.html)
	- Gene Cutler [r-sig-mac contribution](https://stat.ethz.ch/pipermail/r-sig-mac/2005-December/002520.html)
	- Jelmer Borst [masci blog](http://macsci.jelmerborst.nl/files/textwrangler_and_r.php#unique-entry-id-2)
	- Jean Thioulouse [Apple Script](http://pbil.univ-lyon1.fr/JTHome/SendSelToR.txt)
	
	
## Setup
Consult Jonathan Marc Bearak's [website](http://bearak.org/code/text/index.html) for details on use and setup.

- Adding R features to TextWrangler
	- R language
		- Copy R.plist to ~/Library/Application Support/TextWrangler/Language Modules/
		- Set in preferences -> Languages, and add a new suffix mapping (e.g., .r to R language)
	- R helper scripts
		- Copy to ~/Library/Application Support/TextWrangler/Scripts/
		- Assign a shortcut by going to the Window menu in TextWrangler, then choose Palettes -> Scripts and assign a shortcut
- Adding Auto-complete see [bbautocomplete](http://c-command.com/bbautocomplete/)


## How to contribute to this repository
You can help us in different ways:

1. Reporting [issues](https://github.com/dschlaep/TextWrangler_R_Interface/issues)
2. Contributing code and sending a [pull request](https://github.com/dschlaep/TextWrangler_R_Interface/pulls)
