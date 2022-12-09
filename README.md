# STAR

Stock Assessment Results (STAR) is a new framework to organize
[GFCM](https://www.fao.org/gfcm/en/) stock assessment results.

It streamlines and automates the **information flow** from stock assessments to
scientific advice, strengthens **quality assurance** and **data dissemination**.

The central part of the framework will be the STAR database, scheduled to launch
in 2021. It will serve as a foundation to provide a variety of
quality-controlled data products related to the management of fisheries in the
Mediterranean and the Black Sea.

<a href="#star"><img src="diagram.png" width="800"></a>

An R package [gfcmSTAR](https://github.com/gfcm/gfcmSTAR) is used by STAR
administrators to manage the template-to-database import pipeline and quality
control.

## Download newest Excel STAR template

**Version 2.1.3**

*09 Dec 2022*

[STAR_template.xlsx](../../releases/download/2.1.3/STAR_template.xlsx)

Minor changes introduced in version 2.1.3:

**Metadata sheet**
* Revised Reference Points for "F or E target",  now allowing for the values: Fe40, Fb40, Fb35, Fspr40, F/M.

**TimeSeries sheet**
* Time series table extended by 3 new columns (Fishing_lower2, Fishing2, Fishing_upper2) .
* Added the dropdown field "Fishing Exploitation Indicator 2", accepting the values F/Fgt and E/E40. 

Main new features introduced in version 2:

* New input fields - Countries, Assessment Type, and Reporting Year
* Automatic calculations of B0.33, B0.66, and Stock Status text
* Advice output is now more closely aligned with the final Table of Advice

See [NEWS.md](NEWS.md) for a full list of user-visible changes.

## User documentation

Guidelines for users are provided in four places:

1. Overview of the STAR framework and wider context in the launch event
   [presentation](2021_01_18_launch_event.pdf)
2. Usage comments within the
   [Excel STAR template](../../raw/main/STAR_template.xlsx) sheets
3. Sheet highlighting the [logic](logic.pdf) behind the Excel formulas
4. Changes between versions are listed in the [NEWS.md](NEWS.md) file

**Note on version numbering**

The Excel STAR template has a three-part version number: *major.minor.patch*.
These are incremented based on the following rules:

* MAJOR version when database structure needs to be changed
* MINOR version when R import function needs to be changed
* PATCH version when changes are backwards compatible
