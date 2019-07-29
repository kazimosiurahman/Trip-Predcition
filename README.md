# Trip-Predcition
The ability to predict the cancellation of a Trip depending on various attributes


When a user places a new order, our order allocation system sends a notification to multiple drivers at the same time. The first driver who responds to the order is then assigned to. This driver could then complete the order. However, the driver could have rejected the order after being assigned to, in this case the order is considered `not completed`. In other scenarios, the user could cancel before any driver have responded or even after a driver has responded. In this case the order is also considered `not completed`. To summarize, the order is considered `completed` if and only if a driver responded and completed the delivery before the user cancels the order. A lot of known and unknown factors influence the probability of an order completion. Being able to estimate such probability early on have enormous benefits
