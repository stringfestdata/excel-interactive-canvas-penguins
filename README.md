# Interactive canvas dashboards in Excel: Palmer Penguins

A Stringfest Analytics exercise for exploring Excel's interactive-canvas skill with Copilot.

## Files

- `penguins-canvas-start.xlsx`: one worksheet with the `Penguins` table, 344 observations and eight variables. It contains the starting data, not a completed dashboard.
- `practice-prompts.txt`: the creation prompt, a targeted revision, and calculation checks.

## Follow along

1. Download the repository ZIP and extract it. Open the workbook and save a working copy.
2. Open Copilot in Excel with workbook editing available. Check **Manage plugins & skills > Visualization** for **interactive-canvas**. Availability depends on your account and rollout. See [Microsoft's built-in skills guide](https://support.microsoft.com/en-us/excel/copilot/copilot-in-excel-built-in-skills).
3. Send the creation prompt. If needed, type `@` and select the skill from the picker. The generated layout can differ between runs.
4. Check the unfiltered figures: 344 observations, 342 nonblank body-mass measurements, mean body mass 4,201.8 g (one decimal). Species counts: Adelie 152, Chinstrap 68, Gentoo 124.
5. Filter to Gentoo: 124 observations, 123 nonblank body-mass measurements, mean 5,076.0 g. Reset the filters and confirm the original totals return. Test a source edit in your working copy and undo it after checking the dashboard.

For the full walkthrough, comparisons and training resources, visit [Stringfest Analytics](https://stringfestanalytics.com/).

## Data and attribution

Data collected by Dr. Kristen Gorman and the Palmer Station Long Term Ecological Research Program. Palmer Penguins package by Allison Horst, Alison Hill, and Kristen Gorman: [project and citations](https://allisonhorst.github.io/palmerpenguins/), [source CSV](https://github.com/allisonhorst/palmerpenguins/blob/main/inst/extdata/penguins.csv).

The Palmer Penguins data are available under CC0. This workbook retains every source observation and converts the source's `NA` markers to blank cells. Numeric measurements remain numeric. Bill and flipper lengths are in millimeters; body mass is in grams. The eight fields are species, island, bill length, bill depth, flipper length, body mass, sex, and year. These are sampled penguins, not a census of wild populations.
