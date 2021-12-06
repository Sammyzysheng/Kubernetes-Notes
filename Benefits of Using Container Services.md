### Velocity
Definition: The number of requests you can process while maintain a highly available services\
Achieved by:\
1. Immutability
3. Declarative configuration
4. Online Self-healing systems
#### Immutability
create a new image instead of modifying on the existing one
#### Declarative configuration
The configuation of kubernetes is the desired state of the system
#### Online Self-healing systems
continuous to t ake actions to make the current statrte matches the desired state
### Scaling
#### Decoupling
Decoupled Architectiure: each component is seperated from other components by defined APIs ad service load balnaces\
Decouple components via load balancers: easy to svale the programs that make up the service\
Decouple components via APIs: easy to sacle the development teams
#### Easy Scaling for applications and clusters
Kubernetes can simplify forecasting future compute costs\
Suppose kubenetes has decoupled 3 services, then the growth rate can be predicted by aggregate growth rate which reduces statistical noise
#### Scaling Development Teams
**Pods**: a group of containers ( can group different container images  into a single deployable unit)\
**Namaspaces** provide  isolation and access control (each microservice can control the degree to which other services interact with it)\
**Ingress objects** provide an easy to use front end that combine multiple microservices into a single API Surface area\
### Abstracting your Infrastruecture
1. seperate developers from specific machines
2. applications are portable across a wide variety of environments
### Efficiency
1. applications can run in same machine without impacting each other
2. reduce human efforst to manager bash scripts, apt updates and configuration management

