# Data Dictionary

The `campus_spaces.csv` file contains synthetic teaching data describing observed use of campus study spaces.

| Column        | Description                                           | Data Type | Example      |
| ------------- | ----------------------------------------------------- | --------- | ------------ |
| `space_id`    | Unique identifier for the campus space.               | Character | `S103`       |
| `building`    | Building where the space is located.                  | Character | `Library`    |
| `space_type`  | Type or category of campus space.                     | Character | `Study Room` |
| `seats`       | Total number of seats available in the space.         | Numeric   | `24`         |
| `occupied`    | Number of seats occupied when the space was observed. | Numeric   | `18`         |
| `noise_level` | Observed noise level of the space.                    | Character | `Quiet`      |

## Notes

* The records are **synthetic teaching data** and do not represent real campus users or locations.
* `occupied` represents the number of seats in use at the time of observation.
* The occupancy rate for a space can be calculated as `occupied / seats`.
* The sample data contains 12 records.

