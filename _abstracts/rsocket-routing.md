---
layout: page
theme: RSocket Routing
title: Reactive Architectures with RSocket Routing Broker
conf1: "[SpringOne Platform 2019](https://springone.io/2019/sessions/reactive-architectures-with-rsocket-and-spring-cloud-gateway)"
conf1_pair: Spencer Gibb
conf1_youtube: PfbycN_eqhg
---

Spring Cloud Gateway introduced a flexible API for configuring the edge service of our applications. 
Built upon Project Reactor, Spring WebFlux, and Spring Boot 2.0, Spring Cloud Gateway provided a modern and efficient architecture to handle a large number of concurrent requests. 
However, as with all things reactive in the Java stack, features like back pressure were only effective within the scope of the JVM. 
Once a request entered the network, all bets were off.

The RSocket protocol allows us to overcome this limitation by extending the capabilities of reactive architectures down to the network level. 
In this talk, we’ll provide an overview of the key benefits of RSocket-based networking and introduce the integration of Spring Cloud Gateway with RSocket. 
We’ll discuss the benefits of this integration, including the impact on speed, scalability, security, and more. 
We’ll also discuss use cases, and show how you can leverage this new technology in your applications.