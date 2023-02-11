# Project REST-Rant

REST-Rant is an app where users can review restaurants.
Method

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

|Method  |     Path                 |                      Purpose                     |
|--------|--------------------------|--------------------------------------------------|
| GET    | /                        | Homepage                                         |
| GET    | /places                  | Places index page                                |
| POST   | /places                  | Create new place                                 |
| GET    | /places/new              | form page for creating for a new place           |
| GET    | /places/:id              | Details about a particular place                 |
| PUT    | /places/:id/edit         | Form page for editing an existing place          |
| DELETE | /places/:id              | Delete a particular place                        |
| POST   | /places/:id/rant         | Create a rant (comment) about a particular place |
| DELETE | /places/:id/rant/:rantId | Delete a rant (comment) about a particular place |
| GET    | *                        | 404 page (matches any route not defined above)   |
