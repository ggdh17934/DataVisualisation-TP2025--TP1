# TP1 — Critique and redesign

## Part 1: Georgia DPH case study

The Columbia/Sabin Center account reports that a May 13, 2020 news report
identified a DPH graphic covering the five most affected Georgia counties.
Dates were arranged by case magnitude rather than time, with higher values
clustered on the left. This gave the visual impression of sustained decline.
The governor's spokesperson described an error and said it was corrected;
critics questioned intent. The visual distortion is demonstrable, but this
analysis does not treat intent as established.

**Perception:** viewers normally read a time axis from earlier to later.
Reordering dates breaks that expectation while retaining a familiar trend shape.
**Tufte's integrity principle:** even correct counts mislead when their positions
imply a relationship the data do not support. **Clarity and comparison:** an
irregular date sequence makes genuine changes over time difficult to compare.
**Context and storytelling:** a decline-shaped display can suggest improvement
relevant to reopening decisions, while omitting chronological fluctuations.
The axes, ordering, scope and source should support the message rather than
manufacture it. Smoothing must also be labeled so readers see what was derived.

Reference: [Columbia/Sabin Center case study](https://climate.law.columbia.edu/content/covid-19-data-misrepresented-georgia-health-department).
Its search-indexed text was available when the linked page returned 404.

## Part 2: Our three views

1. The exploratory line shows unmodified daily Georgia increments during May.
2. The educational recreation uses May 1–14, sorts counts descending and treats
   the resulting dates as categories. The apparent decline follows from sorting,
   not from a time trend. It is clearly labeled as an intentionally misleading
   exercise, not an authentic historical DPH image.
3. The explanatory view restores time order and shows raw data plus a trailing
   seven-day mean. The mean is calculated before filtering May so the first
   days have a complete history. The annotation marks **May 13 reporting of
   the controversy**, not an assumed exact original publication date.

The original graphic covered five counties; our assignment recreation uses
the Georgia statewide USAFacts series, including unallocated county cases.
It reproduces the ordering problem, not the exact original county values.
The USAFacts historical file contains later revisions and is not guaranteed
to equal the figures visible in the original May 2020 DPH snapshot.
Daily increments are net changes in reported cumulative totals; retrospective
corrections can produce negative values, which are not silently clipped.

Source: [USAFacts case CSV](https://static.usafacts.org/public/data/covid-19/covid_confirmed_usafacts.csv).
Assignment: https://github.com/ahmed3991/DataVisualisation-TP2025/blob/main/TP1/TP1.md
