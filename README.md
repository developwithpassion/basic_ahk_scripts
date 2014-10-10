#basic_ahk_scripts

This is a basic set of scripts lifted from my earlier sets of autohotkey scripts. A simple expansion script is written to merge common headers and footers around the main script files. The main script files are named:

* ahk[name].erb

Only edit the files with a .erb extension, the rest are all generated during the expansion process.

##Usage

1. Do a bundle install to install the expansions gem
2. Run:

```bash
expands
```

The generated ahk scripts will be named generated_[name]. Double click on them to startup the script
