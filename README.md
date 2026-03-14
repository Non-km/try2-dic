## Movie
| Attribute | Data Type | Description | Constraints |
|---|---|---|---|
| movie_id | serial | id of the movie | primary key |
| category_id | integer | category id of the movie | Not Null |
| title | varchar(255) | title of the movie | Not Null |
| duration | integer | Movie time length | Not Null |
| dub_language | varchar(255) | dub language of the movie | Not Null |
| sub_language | varchar(255) | sub language of the movie | Not Null |

## Customer
| Attribute | Data Type | Description | Constraints |
|---|---|---|---|
| customer_id | serial | id of the customer | primary key |
| firstname | varchar(255) | firstname of customer | Not Null |
| surename | varchar(255) | surename of user | Not Null |
