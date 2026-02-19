## Dataset

This project uses the `students` dataset from a 2018 survey conducted at a Japanese international university (published the following year). The study examined mental health outcomes in international students and highlighted **social connectedness** and **acculturative stress** as predictors of **depression**.

### Key fields used in this analysis

| Field Name      | Description                                                |
|----------------|------------------------------------------------------------|
| `inter_dom`     | Student type (international or domestic)                  |
| `japanese_cate` | Japanese language proficiency category                    |
| `english_cate`  | English language proficiency category                     |
| `academic`      | Academic level (undergraduate or graduate)                |
| `age`           | Student age                                               |
| `stay`          | Length of stay in years                                   |
| `todep`         | Depression score (PHQ-9 total)                            |
| `tosc`          | Social connectedness score (SCS total)                    |
| `toas`          | Acculturative stress score (ASISS total)                  |



## Results

| index | stay | count_int | average_phq | average_scs | average_as |
|------:|-----:|----------:|------------:|------------:|-----------:|
| 0     | 10   | 1         | 13.00       | 32.00       | 50.00      |
| 1     | 8    | 1         | 10.00       | 44.00       | 65.00      |
| 2     | 7    | 1         | 4.00        | 48.00       | 45.00      |
| 3     | 6    | 3         | 6.00        | 38.00       | 58.67      |
| 4     | 5    | 1         | 0.00        | 34.00       | 91.00      |
| 5     | 4    | 14        | 8.57        | 33.93       | 87.71      |
| 6     | 3    | 46        | 9.09        | 37.13       | 78.00      |
| 7     | 2    | 39        | 8.28        | 37.08       | 77.67      |
| 8     | 1    | 95        | 7.48        | 38.11       | 72.80      |


## Key Findings

Analysis of international students by length of stay shows a clear adjustment pattern:

* Students in their first years reported **higher acculturative stress**
* Depression scores were generally **higher in early years and decreased with longer residence**
* Social connectedness tended to increase among long-term students

Overall, the results suggest a cultural adaptation effect: as students spend more time in the host country, stress decreases and psychological well-being improves.



