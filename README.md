The dataset contains 10153 rows and 12 columns representing various airlines flights details .
This dataset consists of substantial missing data across most columns—particularly in days_left, airline, and stops, each having over 300 missing entries—highlighting the need for careful imputation or data-cleaning before meaningful analysis.
The column with the highest proportion of missing values is days_left at 3.12%, followed by airline (2.99%) and stops (2.98%).
Vistara is the most frequent airline in this dataset, suggesting that the dataset has more records related to Vistara flights
UK-836 has the highest frequency with 1111 occurrences.
Other frequent flights include UK-838 (1059), UK-832 (1054), and UK-822 (719).
These flights seem to dominate the dataset, indicating they are either more popular or have more data entries.
The majority of flights (~95%) have one stop, while non-stop (zero stops) flights are rare, and two or more stops are extremely uncommon.
Most flights arrive in the Evening (3,043) and Night (2,971), while Late Night (175) and Early Morning (418) arrivals are very rare.
As seen there are no duplicates found in the dataset.
if the index was missing means there no valid point to replace index with something,It does not affect the dataset because we have nearly 10000 rows, removing 126 rows means we are not losing the 1% of data from our dataset.
A positive trend → longer flights usually cost more.
Business class points appear higher priced than Economy for same duration.
Some overlap: short flights can be expensive (e.g., premium busy routes).
General upward trend: As duration increases, ticket price increases.
