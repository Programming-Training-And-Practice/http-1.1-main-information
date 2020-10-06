# HTTP/1.1.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Pros.](#pros)
* [Cons.](#cons)
* [Help](#help)





## About.





## Documentation.





## Pros.
* Simplicity in development.
* Wide support.
* State-Less.





## Cons.
* Ineffective resource usage. Open a new TCP connection to a server at each request.
* It does not compress headers (which are plaintext).
* Communication rigidity. It only works whit Request/Response mechanism (no server push). 
* Duplication Of Data.
* Message Overhead (not binary, is plaintext).
* Average Performance.
* Lack of Resilience (no Back Pressure).





## Help.
