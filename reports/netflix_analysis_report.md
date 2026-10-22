# Netflix Movies and TV Shows Data Analysis

## 1. Project Overview

This project analyzes Netflix title metadata using Python and Pandas.
The objective is to understand the data, identify quality issues,
analyze content categories, and produce a reliable report.

## 2. Dataset Overview

- Total records: 8807
- Total columns: 12
- Content types: {'Movie': 6131, 'TV Show': 2676}

## 3. Data Quality

### Missing Values

show_id            0
type               0
title              0
director        2634
cast             825
country          831
date_added        10
release_year       0
rating             4
duration           3
listed_in          0
description        0

### Exact Duplicate Rows Remaining

0

## 4. Key Findings

### Content Types

type
Movie      6131
TV Show    2676

### Top Genre Labels

listed_in
International Movies        2752
Dramas                      2427
Comedies                    1674
International TV Shows      1351
Documentaries                869
Action & Adventure           859
TV Dramas                    763
Independent Movies           756
Children & Family Movies     641
Romantic Movies              616

### Titles Added by Year

date_added
2008       2
2009       2
2010       1
2011      13
2012       3
2013      11
2014      24
2015      82
2016     429
2017    1188
2018    1649
2019    2016
2020    1879
2021    1498

## 5. Visualizations

- content_types.png
- top_genres.png
- titles_added_by_year.png

## 6. Limitations

This dataset contains content metadata, not Netflix sales,
revenue, or viewership figures. Genre totals count title-genre
associations, so one title may appear in multiple genres.
The findings reflect the downloaded dataset version.

## 7. Verification

The reported values are calculated from the processed dataset.
Review the cleaning notebook and original CSV to validate
the data-cleaning decisions and remaining data-quality issues.

## 8. Conclusion

The analysis examined 8,807 Netflix titles across 12 columns, including 6,131 movies and 2,676 TV shows. International Movies, Dramas, and Comedies were the three most frequent genre labels in the dataset.

The data-quality assessment identified missing information in several columns, particularly director, cast, and country. These missing values should be handled according to the needs of each analysis rather than automatically deleting the affected records.

The dataset also shows variation in the number of titles added to Netflix across the years represented in the data. These figures describe the downloaded dataset and should not be interpreted as current catalogue size, viewing popularity, or revenue.

Overall, this project demonstrates how Python, Pandas, data visualization, and AI-assisted prompt engineering can support data understanding, cleaning, analysis, and reporting. All numerical claims should be checked against the actual dataset before the report is submitted.