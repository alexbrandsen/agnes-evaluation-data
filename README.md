# agnes-evaluation-data
Data collected during 2019 evaluation of the AGNES system.

## [Queries](queries-and-reformulations.csv)

This file contains all the queries and query reformulations the users performed, including the task they wanted to solve, time taken on different elements, and some other metrics. 

### Column headings

| Heading        | Explanation           |
| ------------- |-------------|
| id      | Auto-number ID | 
| user       | User ID      | 
| user_group  | User group (aca = academic, com = commercial, gov = government)      | 
| session_query_number  | Query number for this user session      |
| global_query_number  | Overall query number      |
| new_or_refinement  | Whether the query is a new query or a query refinement      |
| refinement_type  | Which refinement type (gen = generalising, ref = reformulation, spec = specialisation)      |
| user_goal_or_question  | The task or question the user was trying to complete      |
| quasi_query  | The query the user entered, in quasi-code      |
| qty_query_elements  | How many elements were involved in the query      |
| time_spent_on_query  | Time spent on creating the query in the querybuilder and if applicable, selecting facets (in seconds)      |
| time_spent_per_element  | Time spent per query element (in seconds)      |
| time_spent_on_map  | Time spent on map features (in seconds)      |
| time_spent_on_results  | Time spent looking through and evaluating results (in seconds)      |
| query_matches_reference_query  | If a predefined task; does the query match the reference query      |
| number_of_results  | Number of results returned for query      |
| preview_clicks  | How many times the user clicked a preview link      |
| dans_clicks  | How many times the user clicked a DANS link      |
| archis_clicks  | How many times the user clicked an ARCHIS link      |

