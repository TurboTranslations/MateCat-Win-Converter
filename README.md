<p align="center"><img src="http://i.imgur.com/o7gUQ7G.png"></p>

# MateCat Win Converter

MateCat Win Converter helps [MateCat Filters](https://github.com/matecat/MateCat-Filters) supporting more formats doing some auxiliary file conversions.

## Getting started

You cannot use MateCat Win Converter alone you need a MateCat Filters instance up and running. For more information on MateCat Filters check the [dedicated repository](https://github.com/matecat/MateCat-Filters).

Check the required dependencies:

* In order to support legacy Office formats (like doc, ppt, xls) you need Microsoft Office 2010 or later installed.
* In order to support OCR of image formats you need the OCR Console by Nuance.
* In order to support PDFs you need an API key from [CloundConvert](https://cloudconvert.com/). You can obtain one creating a new free account [here](https://cloudconvert.com/user/registration).

Create a config file in the same folder of the executable and carefully set all the parameters. See `App.sample.config` for a configuration example.

Ensure to have MateCat Filters properly configured to connect to the MateCat Win Converter instance you are creating. For more info [read the documentation](https://github.com/matecat/MateCat-Filters/wiki/Build-and-run) in the MateCat Filters wiki.

*That's it!* Now you are ready to run MateCat Win Converter and MateCat Filters to convert all your files!
