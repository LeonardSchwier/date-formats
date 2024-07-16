# date-formats
As part of my PhD research, I needed to translate different international dates into a common format (YYYY-MM-DD).

This repository includes a version of the mapping table  I used for translation. It includes many of the most common languages (e.g., English, German, French, Spanish, Mandarin, Polish and others).

The data in the column _DateOriginal_ includes years and months (no days though). The column _DateTransformed_ includes the standardized date (YYYY-MM-DD).
- The column _type_ specifies which day is set: for _start_, the first day of that month and for _end_, the last day of that month
- If no month is given (so only the year), _start_ is interpreted as _first day of that year_ and _end_ as _last day of that year_

The dates range from 1970-01-01 until 2023-12-01.

**Included languages**:
- English
- German
- French
- Spanish
- Serbian
- Czech
- Mandarin
- Thai
- Hindi
- Arabic
- Russian
- Ukrainian
- and others

**Disclaimer**: I cannot guarantee the accuracy of the translations. Please create a pull request if you want to add any additional or modify any existing translations.
