This is a lesson on tidying data, remixed from [Jenny Bryan's similar lesson using "Lord of the Rings" data](https://github.com/jennybc/lotr-tidy). Most text is Jenny's :)

Specifically, what to do when a conceptual variable is spread out over multiple data frames and across 2 or more variables in a data frame.

  * [01-intro](https://apreshill.github.io/bakeoff-tidy/01-intro.html) shows untidy and tidy data. Then we demonstrate how tidy data is more useful for analysis and visualization. Includes references, resources, and exercises.
      * Data used: [number of desserts baked in "The Great British Bake Off"](https://github.com/apreshill/bakeoff) by challenge (signature versus showstopper) and type (cakes versus pies/tarts).
  * [02-gather](https://apreshill.github.io/bakeoff-tidy/02-gather.html) shows __how__ to tidy data, using `gather()` from the `tidyr` package. Includes references, resources, and exercises.
      * Data used: [number of desserts baked in "The Great British Bake Off"](https://github.com/apreshill/bakeoff) by challenge (signature versus showstopper) and type (cakes versus pies/tarts).
      * Choice of 3 different datasets for exercises: [Bachelor/Bachelorette from 538](https://github.com/fivethirtyeight/data/tree/master/bachelorette), [PDX Bike Counts](https://docs.google.com/spreadsheets/d/1urP-ZA0Pd25_JZZ18hkGPlDEUQusBp49XmLzwpZ-2ag/edit?usp=sharing), or the [538 Flying Etiquette Survey](https://github.com/fivethirtyeight/data/tree/master/flying-etiquette-survey).
  * [03-spread](https://apreshill.github.io/bakeoff-tidy/03-spread.html) shows __how__ to untidy data, using `spread()` from the `tidyr` package. This might be useful at the end of an analysis, for preparing figures or tables.
      * Data used: [Bachelor/Bachelorette from 538](https://github.com/fivethirtyeight/data/tree/master/bachelorette).
  * [04-tidy-bonus-content](04-tidy-bonus-content.md) is not part of the lesson but may be useful as learners try to apply the principles of tidy data in more general settings. Includes links to packages used. *It is out of date!*
