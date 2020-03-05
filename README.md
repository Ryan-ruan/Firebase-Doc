#### differience between AWS and Firebase

## AWS - Amazon Web Services

Pro

- all-in-one solution
- many different services
- Lambda’s performance is also very strong
- pay-per-use service
- entire ecosystem is made to be all-inclusive

cons

- slight learning curve
- larger team friendly with a large suite of products

## Firebase

Pro

- unique services eg: traffic management services
- easy to scale
- lower learning curve

cons

- difficult to query larger datasets
- no relational data

---

| \    | AWS                                                                                                                                             | Firebase                                                                                           |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Pros | - all-in-one solution <br> - many different services<br> - Lambda’s performance <br> - pay-per-use service<br> - all-inclusive entire ecosystem | - unique services eg: traffic management services <br> - easy to scale <br> - lower learning curve |
| Cons | - slight learning curve <br> - larger team friendly with a large suite of products                                                              | - difficult to query larger datasets<br> - no relational data                                      |

---

#### Serverless Architecture?

A serverless architecture is essentially a microservice architecture. Whenever an event occurs, a code or function is executed. The server runs when something happens. The code only wakes up when it receives a request. It’s not persistent and running all day, all week.

It only uses resources when it needs to. The benefit of this is that each function has its own responsibility, and none of it overlaps, making things cleaner and less finicky.

A traditional server usually features a single server that has a variety of responsibilities within its codebase. When a request goes in, the server executes some processes and a response is given.
This one server can be responsible for several different functions. This could include authentication, writing files, watching users, etc. You can see why this might be a hectic model for running a server.
