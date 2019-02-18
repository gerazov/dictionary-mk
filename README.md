# dictionary-mk
## Macedonian Spellcheck Dictionary

This dictionary is ported from the [Open Office Macedonian dictionary extension](https://extensions.openoffice.org/en/project/macedonian-spellchecker-dictionary) and originally developed by the [Free/Libre Software Organisation of Macedonia (OSSM)](https://www.slobodensoftver.org.mk/).

I've updated the `.aff` so that `hunspell` doesn't give an error.

To include the Macedonian locale for your `hunspell` spell checker all you have to do is copy the `mk_MK.dic` and `mk_MK.aff` files to your `hunspell` dictionary folder. You can find this folder using `hunspell -D`. For my Arch based Manjaro install it was `/usr/share/hunspell/`.
