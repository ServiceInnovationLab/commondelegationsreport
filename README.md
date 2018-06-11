# commondelegationsreport
Closure report from early Common Delegations work (Datacom)

This report was the final closure report from early Common Delegations work commissioned by DIA and done by Datacom. It doesn't represent current Lab (Service Innovation) thinking and was not developed to meet the needs of the life events or integrated services. It does have some useful use cases and history that may be helpful. 

The earlier “Common/Central Delegations” prototype work was found to be unfit for the Lab to adopt as a reusable component in the original state for several reasons: 1) it was too specifically tied to RealMe (an extension only), 2) the functionality tried to serve all possible scenarios without actively being applied to any single use case, 3) it was too complex for existing life event requirements, 4) it is a relatively heavy Java application, which doesn’t easily sit alongside more modern web based development languages used by the life events to date, and 5) it was tied to the ForgeRock software stack, making it difficult for any other IAM to integrate. The software and final report were published with some clean up on the Service Innovation Lab github for future considerations, and the End of Life functionality requirements were met by their vendor in a much more lightweight way appropriate to user needs.

See code at Central Delegations Service prototype (https://github.com/ServiceInnovationLab/cds_platform), and using Wildfly Swarm (Java EE microservice) (https://github.com/ServiceInnovationLab/CentralDelegationService).
