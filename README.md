# Subscleaner

## Dependencies

This script depends on [chardet](https://github.com/chardet/chardet) and [pysrt](https://github.com/byroot/pysrt).
Install them via pip3:
```
pip3 install --user pysrt chardet
```
or via virtual environment.

## Installation
Clone the repo and run
```
python3 setup.py install --user 
```
or `chmod +x` the script and copy it in a $PATH directory.

## Usage

Run the script giving as arguments the subtitle files. In case some ads are found inside the file, the old file is moved to <basename>.bak and the new file written with the same name.
Example:

```
subscleaner building_on_the_past.en.srt
```

