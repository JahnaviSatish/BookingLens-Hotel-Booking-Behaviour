PERSON 1- WORK DONE

| Part  | Work                              | Status |
| ----- | --------------------------------- | ------ |
| **A** | Load H1 + H2                      | ✅      |
|       | Add `Hotel` column                | ✅      |
|       | Merge datasets                    | ✅      |
|       | Verify 119,390 original rows      | ✅      |
| **B** | Dtypes / structure                | ✅      |
|       | Missing values                    | ✅      |
|       | Hidden `NULL`s                    | ✅      |
|       | Categorical/whitespace inspection | ✅      |
|       | Duplicate inspection              | ✅      |
|       | Numerical ranges                  | ✅      |
|       | ADR anomalies                     | ✅      |
| **C** | Whitespace cleaning               | ✅      |
|       | Agent/Company missing values      | ✅      |
|       | Children missing values           | ✅      |
|       | Country missing values            | ✅      |
|       | Remove exact duplicates           | ✅      |
|       | Investigate unusual Adults        | ✅      |
|       | Handle negative ADR               | ✅      |
|       | Retain/flag zero & extreme ADR    | ✅      |
| **D** | `ArrivalDate`                     | ✅      |
|       | `TotalNights`                     | ✅      |
|       | `TotalGuests`                     | ✅      |
|       | `LeadTimeBand`                    | ✅      |
| **E** | Five-number summary               | ✅      |
|       | Mean / Median                     | ✅      |
|       | Variance                          | ✅      |
|       | Standard deviation                | ✅      |
|       | Skewness                          | ✅      |
|       | Kurtosis                          | ✅      |
|       | Correlation                       | ✅      |
|       | Covariance                        | ✅      |

REPORT OF WHAT WAS DONE
| Cleaning operation   | Result                          |
| -------------------- | ------------------------------- |
| H1 + H2 merged       | 119,390 original rows           |
| Whitespace           | Removed from categorical values |
| Agent/Company `NULL` | Converted to `Not Applicable`   |
| Missing Children     | 4 values handled                |
| Missing Country      | Handled as `Unknown`            |
| Exact duplicates     | 31,994 removed                  |
| Negative ADR         | 1 invalid value handled         |
| Zero ADR             | Retained                        |
| Extreme ADR          | Retained and flagged            |
| Feature engineering  | 4 new variables created         |
| Final dataset        | 87,396 rows × 36 columns        |

 #################################################################################
PERSON 2
