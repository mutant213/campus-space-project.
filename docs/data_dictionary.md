# Data Dictionary

The file data/sample/campus_spaces.csv contains synthetic teaching data about 12 campus study spaces.

| Column | Type | Meaning |
|---|---|---|
| space_id | Text | Unique identifier for each study space, such as S101. |
| building | Text | Building where the space is located, such as Building A. |
| space_type | Text | Category of space: Quiet study, Group study, Computer lab, or Lounge. |
| seats | Integer | Total number of seats in the space. |
| occupied | Integer | Number of seats occupied during the observation. |
| noise_level | Text | Observed noise category: Low, Medium, or High. |

The script calculates available seats as seats minus occupied.
Overall occupancy is total occupied seats divided by total seats, expressed as a percentage.
The busiest observed space has the highest proportion of occupied seats.
