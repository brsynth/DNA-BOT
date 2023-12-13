## Unreleased

## 4.1.0 (2023-09-05)

### Fix

- **dnabot_app**: fix deprecated iteritems

## 4.0.0 (2023-09-05)

### Feat

- keep the thermo lid closed at 4°C after execution
- refine plate roles
- **dnabot_gui**: add thermo lid option + improve layout
- **clip_tempalte...**: add overnight thermocycler option
- **default_settings.yaml**: add parameters
- print out the deck representation
- add thermocycler lid management option
- add thermocycler lid management option
- output plate positions on deck
- **clip_template_APIv2.8**: move destination plate to slot 7

### Fix

- simplify keeping sample at 4°C
- key in __PARAMETERS dict
- simplified way of handling thermo lid
- better labels for plates
- import slots module
- prevent changing dir for writing metadata info
- **templates**: improve metadata info

## 3.1.0 (2022-02-22)

### Feat

- **dnabot_gui**: add a vertical scroll bar
- edits for integrating transformation step using 12 well corning plate
- **template_ot2_scripts**: add new script for 12 well corning well plate

### Fix

- **templates**: update transformation with thermocycler template
- correct default parameter values

## 3.0.0 (2022-02-21)

### Feat

- introduce purification parameters
- different pcr plate depending of the step
- dynamically set labware IDs
- provide default values from yaml file

### Fix

- **dnabot_gui**: handle correctly int values
- update default settings
- **templates**: fix keys
- **dnabot_app**: get absolute path
- wrong path in the user_settings dict
- nicely ends when input paths are missing
- stop crashing when output dir is not defined

## v2.0.0 (2021-09-29)

### Feat

- **dnabot**: add yaml environment
- **dnabot**: files to include in the package
- **dnabot**: specify package versions
- **dnabot**: setup for dnabot
- **dnabot**: recipe folder for dnabot
- **dnabot_app**: enable to set all options using CLI
- relax the constraints to detect RBS linkers

### Fix

- **dnabot**: import module from dnabot
- **dnabot**: discard test constructs_clip_run_info.csv (contain variable path)
- **dnabot**: specify paths with Pathlib

## v1.0.0 (2019-11-28)
