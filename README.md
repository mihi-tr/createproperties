# Createproperties

Create Properties helps you to create your ```app.properties``` from a html
project using mozillas l10n.

Mozilla recommends using [l10n to localize web 
apps](https://developer.mozilla.org/en-US/Apps/Build/Localization/Getting_started_with_app_localization).
The process asks you to define keys in your html files that will then be
translated in a ```app.properties``` file.  ```createproperties.py``` is a
simple python script that helps you to create your initial app.properties.

## Installation

```createproperties.py``` depends on lxml - make sure you have it installed
either through your package manager or through ```pip install lxml```


Download [createproperties.py](createproperties.py) from github.

## Usage

```
python2 createproperties.py /path/to/my/app/*.html > /path/to/my/app/locales/en/app.properties
```

## Contribute

```createproperties.py``` is very simple and barebone. Help making it
better by filing issues, contributing code and working on better concepts.
All Contributions welcome.


