## Chapter 1 Introducing event streams

* An event is anything that we can observe occurring at a particular point in time.
* A continuous event stream is an unterminated succession of individual events, ordered by the point in time at which each event occurred.
* Many software systems are heavily influenced by the idea of event streams, including application-level logging, web analytics, and publish/subscribe messaging.
* In the classic era of data processing, business operated a disparate set of on-premises systems feeding into a data warehouse. These systems feature high latency, heavily siloed data, and many point-to-point connections between systems.
* In the hybrid era of data processing, businesses operate a hodgepodge of transactional and analytics systems. There are disparate data silos, but also attempts at 'log everything' approaches with Hadoop and/or systems monitoring.
* The unified log era proposes that businesses restructure around an append only log to which all events are generated by our applications; software systems should communicate with each other in an uncoupled way through the unified log.
* Use cases for this unified architecture include customer feedback loops, holistic systems monitoring, and hot swapping data application versions.
