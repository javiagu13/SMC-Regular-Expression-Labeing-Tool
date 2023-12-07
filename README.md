# Samsung Medical Center Regex Curation Tool

### Instructions

#### Requirements
 - Python 3.10 or 3.11

#### Installation:

1-Install the requirements
```
python -m pip install pip --upgrade
python -m pip install -r requirements.txt
```
#### Running:

1-In order to perform labeling do the following:

```
python fns/label.py config/smc.yml --findlog true
```

#### Explanation:
The .yml files in config define the regular expressions, you can add as many config files as you wish and it will perform the labeling





Written by Javier Aguirre at 2023-12-05, Samsung Medical Center, Smart Health Lab, Seoul