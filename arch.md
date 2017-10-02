### Heroku Architecture

Heroku is a cloud platform based on a **managed container system**, with integrated data services and a powerful ecosystem, for deploying and running modern apps. 

The Heroku developer experience is an **app-centric approach for software delivery**, integrated with today’s most popular developer tools and workflows.

![heroky platform](img/hplatform.png)

![heroky platform](img/heroku-arch-2.png)

 
 <div style="page-break-after: always;"></div>

**Flow**

![heroky platform](img/heroku-arch-2.gif)

----

**Heroku Runtime**

Heroku runs your apps inside **dynos** — smart containers on a reliable, fully managed runtime environment.

Developers deploy their code written in Node, Ruby, Java, PHP, Python, Go, Scala, or Clojure to a build system which produces an app that's ready for execution. 

The system and language stacks are monitored, patched, and upgraded, so it's always ready and up-to-date. The runtime keeps apps running without any manual intervention.

-----

**Scale**

![heroky platform](img/heroku-scale-1.gif)

-----

**Developer-centric**

At Heroku, we believe that developers are the most important part of transforming every company into an apps company. That’s why a great developer experience has always been at the very heart of what we do. 

Heroku understands what adds value to developers and what gets in the way. 

We move all the mundane tasks out of the way and add features and functionality that **delight and inspire developers** to do their best work.

-----

**App-centric**

The Heroku Platform is designed so you can focus on what matters the most: the app. 

Getting apps out in the wild, in front of real users, and then iterating fast, is what can make or break companies. 

Heroku lets companies of all sizes embrace the value of apps, not the hassle of hardware, nor the distraction of servers — virtual or otherwise.


-----

**Production-centric**

The Heroku Platform is great for the early part of the app lifecycle, but it really shines when you go into production. 

Heroku seamlessly supports every step of the app lifecycle — build, run, manage and scale. 

Heroku Postgres provides **trusted database options at terabyte scale**. Dyno choices to suit your needs, including performance dynos for your highest traffic apps — all scalable in an instant.

 Heroku keeps the **kernel up-to-date** with the **latest security patches**. All backed by the **trust and reliability of Salesforce**.

-----


**Data Services and Ecosystem**

Heroku Elements let developers extend their apps with Add-ons, customize their application stack with Buildpacks and jumpstart their projects with Buttons. 

Add-ons are 3rd party cloud services that developers can use to immediately extend their apps with a range of functionality such as data stores, logging, monitoring and more. 

Heroku provides three fully-managed data service Add-ons: **Heroku Postgres, Heroku Redis, and Apache Kafka** on Heroku.

----

**Heroku Developer Experience (DX)**

The Heroku Developer Experience is an app-centric approach to software delivery so developers can focus on creating and continuously delivering applications, without being distracted by servers or infrastructure.

 Developers deploy directly from popular tools like **Git, GitHub or Continuous Integration (CI) systems**. The intuitive web-based Heroku Dashboard makes it easy to manage your app and gain greater visibility into performance.

----

**Heroku Operational Experience (OpEx)**

The Heroku Operational Experience is a key component of the platform. It helps developers through **troubleshooting and remediation of common issues** and customizing their ops experience to quickly identify and address negative trends in their application health. 

Threshold Alerting and Autoscaling:

Heroku provides **a set of tools to alert you** if something goes wrong, or to automatically scale your web dynos if the response time for web requests exceeds a threshold you specify.

 Application metrics, Threshold Alerting, and Autoscaling are some of the features you get access to with no extra cost.

----

### Runtime

**Smart Containers**

The Heroku platform runs your apps inside smart containers called **dynos**. 

Dynos work in tight coordination with the dyno manager to provide a range of benefits to your app like security, isolation, and scalability.

**Container Orchestration**

The dyno manager, a part of the Heroku Runtime, coordinates and manages all your app’s dynos. Failed dynos are cycled and all components are reset and refreshed upon a redeploy. If there are any failures in the underlying hardware, all your dynos are moved to a new location without any manual intervention.

----

**Log Aggregation**

The Heroku Runtime aggregates logs from the output streams of your app, system components, and backing services and sends them into a single channel using Heroku’s Logplex. Heroku aggregates three categories of logs for your app: app logs, system logs, and API logs.

**HTTP Routing and load-balancing**

A set of routers automatically routes HTTP requests from your app’s hostname(s) to your web dynos. The router uses a **random selection algorithm** to distribute traffic across your web dynos.

----

**Release Management**

With every code deploy a new release is created and stored on Heroku. You can list the history of releases, and use **rollbacks** to revert to prior releases for backing out of bad deploys.

**Configuration Management**

Configuration may vary between different environments. Heroku uses config vars to keep track of environment configurations. Each time a config var is updated, it creates a new release so you can can roll back to any previous release to have the config vars restored.

----

**SSL and Certificate Management**

Heroku SSL and Automated Certificate Management are included at **no additional charge** on any app using paid dynos. 

The Heroku router terminates SSL for your app’s custom domains. With Automated Certificate Management, a TLS certificate is generated for your custom domains automatically.


**Horizontal and Vertical Scaling**

You can **horizontally** scale any app running on Standard or Performance dynos by **increasing the number of dynos** from the Heroku Dashboard or CLI.

You can change dyno types to **vertically** scale your app by running on dynos with more CPU and memory capacity.




![h1](img/h1.png)
----

![h2](img/h2.png)
----

![h3](img/h3.png)
----


![h4](img/h4.png)
----


![h5](img/h5.png)
----




![h7](img/h7.png)
----


![h8](img/h8.png)
----

![h9](img/h9.png)

[More details](ps.md)
----

![h10](img/h10.png)
----


![h11](img/h11.png)
----

![h12](img/h12.png)
----
![h13](img/h13.png)
----


#### Resources

1. [Platform](https://www.heroku.com/platform)
2. [Runtime](https://www.heroku.com/platform/runtime)


