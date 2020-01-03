# Presentation

## Start /  what have we done

* Intro to the overall problem we are trying to solve with out program.
* Demo the app walkthrough the intended idea behind the frontend vs what they actually delivered, (Perhabs Nikolaj Can Draw some basic UI in paint for slides)
* Show slides about the backend and frontend communication VIA the contract with pictures. 
    * Explain the idea behind it, a brief overview of gRPC.
* Explain the idea behind the backend
    * extra methods incase it was needed?
    * keeping it simple
    * mainly just an sql getter thingy (whats the name?)
    * very little if no logic in the current implementation (properbly because of lack of development from the frontend team?)


## What we would have liked to implement

* Logging
    * we had some logging initially, but after being introduced to promethues/the other one, which were focused on the front end part, we decided to would be better to let the frontend team be in charge of this section, they dicovered that Azure provided the neccesarry tools anyway. We later discovered it would have been a good idea to keep logging in the backend either find prebuild logging software or rebuild or own one, to make it easier to locate errors if any, especially if the error casuses a crash, it would make it easier and faster to fix the issue if we had logs to look through.
* Sub system / docker
    * We could improve on our current platform by splitting it up into microservices and have it run in a containerized system. This would help us make it modulized and there by easier to maintain and scale if need be, at the cost of a slight increased development time and a varied deployment cost (show them the Paas and IaaS pictures).
    * Docker would also allow us to deal with a potential load issue by using their docker swarm technology (insert more info here.)
* CD
    * Being apple to quickly deploy a fix to an error without going through the deployment phase manually.
