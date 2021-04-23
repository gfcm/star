Version 2.1.1 (2021-04-23)
--------------------------

**Vocabularies sheet**

* Added 3-Alpha Species Code.

---

Version 2.1.0 (2021-04-20)
--------------------------

**Metadata and TimeSeries sheets**

* Moved dimensions (age or length at recruitment, Fbar age or length) from
  Metadata to TimeSeries.

**Advice sheet**

* GSA codes are formatted as comma-separated without spaces.

* Improved format for Current Levels, Reference Points, and Quantitative Status,
  using period as decimal separator, independent of user locale.

* Removed locale-dependent 0.00 format from Current Levels and Quantitative
  Status.

---

Version 2.0.0 (2021-04-12)
--------------------------

**Metadata sheet**

* Added Countries.

* Added Assessment Type.

* Added Reporting Year.

* Formatted GSA cells as text in Metadata, to make them easier to type directly.

* Changed label Assessment Year -> Reference Year.

* Quantitative Status is only calculated if Validation Status is Quantitative.

* Rearranged B reference point section to a flat layout.

* Rearranged VPA-Type Model and Forecast Included to a horizontal layout.

* Stock Status Text is calculated automatically, instead of requiring user
  input.

* B0.33 and B0.66 are calculated automatically, instead of requiring user input.


**TimeSeries sheet**

* Renamed sheet Summary -> TimeSeries.

* Rearranged unit cells, so they are close to the corresponding columns.

* Changed label Fishing Pressure Type -> Exploitation Unit.

* Removed Effort_lower, Effort, and Effort_upper columns.


**Vocabularies sheet**

* Added Countries.

* Added Assessment Type.

* Extended Year range from 2021 to 2025.

* Changed Exploitation Unit options to F, HR, and Effort.

* Removed Stock Status.


**Advice sheet**

* Added intermediate calculations to shorten formulas.

* B0.33 and B0.66 are not exported as Reference Points, but do form the basis of
  the Stock Status.

* Formatted Fc and Quantitative Status to 0.00 format, with trailing zeroes.

* Quantitative Status with respect to F is reported as F/Fref or E/Eref, rather
  than F/Ftarget.

* Quantitative Status with respect to B is based on Bmsy, Bpa, and Blim - not on
  B0.33 or B0.66.

* Added GSA_Countries, containing comma-separated GSA Names and Countries.

---

Version 1.0.0 (2021-01-15)
--------------------------

* First version of the Excel STAR template.

* Launched at joint plenary session of the Mediterranean stock assessment
  working groups (2021-01-18).
