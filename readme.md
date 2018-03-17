# Awesome Domain-Driven Design [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Domain-Driven Design (DDD), Command Query Responsibility Segregation (CQRS), Event Sourcing, and Event Storming resources.

**Check out my [blog](https://buildplease.com) and [weekly DDD newsletter](https://buildplease.com/pages/dddweekly/) or say hi on [Twitter](https://twitter.com/heynickc)!**

**[Domain-Driven Design (DDD)](https://en.m.wikipedia.org/wiki/Domain-driven_design)** is an approach to software development for complex needs by connecting the implementation to an evolving model.  The premise of Domain-Driven Design is the following:

- placing the project's primary focus on the core domain and domain logic
- basing complex designs on a model of the domain
- initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems

The term was coined by Eric Evans in his book of the same title.

**[Command Query Responsibility Segregation (CQRS)](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/)** is simply the creation of two objects where there was previously only one. The separation occurs based upon whether the methods are a command or a query (the same definition that is used by Meyer in Command and Query Separation, a command is any method that mutates state and a query is any method that returns a value).

**[Event Sourcing](http://www.martinfowler.com/eaaDev/EventSourcing.html)** the fundamental idea of Event Sourcing is that of ensuring every change to the state of an application is captured in an event object, and that these event objects are themselves stored in the sequence they were applied for the same lifetime as the application state itself.

**[Event Storming](https://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)** is a workshop format for quickly exploring complex business domains.

## Contents

- [Books](#books)
- [Training Courses](#training-courses)
- [Video Collections](#video-collections)
- [Community Resources](#community-resources)
- [Blogs](#blogs)
- [Sample Projects](#sample-projects)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Podcasts and Interviews](#podcasts-and-interviews)
- [Conferences](#conferences)
- [User Groups](#user-groups)

## Books

- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215) - The canonical book that coined the term Domain-Driven Design.  Also known as the "Blue Book."
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) - A summary of the patterns and definitions of DDD.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - Tangentially connected to DDD, describes the importance of the Ubiquitous Language and working together with domain experts, along with lots of technical details.
- [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) - Also a canonical book presenting a top-down approach to understanding Domain-Driven Design.  Also known as the "Red Book."
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - Very good starter book before you read [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) or [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - A software architect’s digest of core practices, pragmatically applied.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - Discover how a Living Documentation can help you in all aspects of your projects, from the business goals to the business domain knowledge, architecture and design, processes and deployment, even if you hate writing documentation.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - The deepest tutorial and explanation about EventStorming, straight from the inventor.
- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - An infographic on the anatomy of Domain-Driven Design.
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - Exploring CQRS and Event Sourcing.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - Domain Driven Design Quickly is a short, quick-readable summary and introduction to the fundamentals of DDD.
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles, Tactical Design, and Bounded Context Integration.
- [CQRS](https://leanpub.com/cqrs) - Notes by Mark Nijhof from his experiences learning DDD and CQRS from Greg Young.  There is an extensive sample project that accompanies this book.
- [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) - Describes three strategies for getting started with DDD when you have a big commitment to legacy systems.
- [Secure by Design (early access)](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80) - Shows how to use Domain-Driven Design to avoid security vulnerabilities.
- [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) - A walkthrough of using EventStorming and other modeling techniques to build a CQRS and Event Sourcing-based prototype for a fictional business domain.
- [Versioning in an Event Sourced System](https://leanpub.com/esversioning) - Have you had troubles with versioning an Event Sourced system? Just getting into a new Event Sourced system for the first time? This book is the definitive guide of how to handle versioning over long periods of time.
- [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) - Writing Great Specifications is an example-rich tutorial that teaches you how to write good Gherkin specification documents that take advantage of Specification by Example's benefits.
- [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) - A 68 pages long free ebook on what DDD, CQRS and event-sourcing are, and how they fit each other.
- [Specification by Example](https://www.manning.com/books/specification-by-example) - This book distills from the experience of leading teams worldwide effective ways to specify, test, and deliver software in short, iterative delivery cycles. Case studies in this book range from small web startups to large financial institutions, working in many processes including XP, Scrum, and Kanban.
- [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) - A walkthrough of using Domain-Driven Design with Event Sourcing and CQRS using ASP.NET Core and SQL Server in production.
- [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) - Domain-Driven Rails describes 11 techniques (from Bounded Contexts to Event Sourcing) that you can use separately and together in new and old Rails apps to achieve better architecture.

## Training Courses

- [Domain Language eLearning](http://elearn.domainlanguage.com/) - Using our video lessons with Eric Evans, author of the original book on Domain-Driven Design (DDD), teach yourself techniques for evolving practical models that improve your software — not just your documents.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - These videos include the entirety of Greg Young's DDD, CQRS, and Event Sourcing class.
- [Distilling Domain-Driven Design](https://forcomprehension.com/) - Vaughn Vernon's online training course.
- [Advanced Distributed Systems Design](https://5757066.flickrocket.com/us/) - Live training from Udi Dahan.  Udi's live training schedule can be found [here](http://udidahan.com/training/).
- [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) - Introduction to Event Sourcing and CQRS.
- [Event Sourcery](https://eventsourcery.com/) - Introduction to DDD, CQRS, and Event Sourcing.
- [Mixter](https://github.com/DevLyon/mixter) - CQRS and Event Sourcing Koans.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - Teaches the fundamentals of Domain-Driven Design (DDD) through a demonstration of customer interactions and a complex demo application, along with advice from Eric Evans.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - A descriptive, in-depth walk-through for applying Domain-Driven Design principles in practice.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing) - This course covers DDD analysis patterns helpful in discovering the top-level architecture of a business domain. Architects and developers will find details of implementation patterns such as Domain Model, CQRS, and Event Sourcing.
- [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) - Introduction to DDD, fundamentals of CQRS & Event Sourcing for Ruby/Rails developers.

## Video Collections

- [DDD Europe](https://dddeurope.com) - Recordings of talks given at DDD Europe.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - Searching DDD returns various talks given by Greg Young, Alberto Brandolini, and Dan North, etc.
- [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) - A YouTube collection of talks given by Alberto Brandolini on Event Storming.
- [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) - A YouTube collection of various talks given by Greg Young.
- [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) - Recordings of the talks given at the Explore DDD conferece.

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) - An active mailing list and an excellent resource to ask questions and learn fine-grained details about DDD/CQRS.
- [Domain Driven Design Yahoo Group](https://groups.yahoo.com/neo/groups/domaindrivendesign/conversations/messages) - This group is for discussion of the domain-driven style of designing software, and the book by Eric Evans, Domain-Driven Design: Tackling Complexity in the Heart of Business Software. Questions and discussion of the book content is welcome here, as well as sharing of experiences applying DDD, and discussions of the topic in general.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - The place to discuss Domain-Driven Design, CQRS, Event Sourcing, Model Storming, Hexagonal Architecture, Distributed Systems, Reactive... in the context of PHP.
- [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - A subreddit for Ruby developers interested in Domain-Driven Design.
- [EventStormers Google+ Community](https://plus.google.com/u/0/communities/113258571348605620818) - A public discussion group for everybody interested in EventStorming, and related themes.
- [DDD/CQRS/ES Slack](https://ddd-cqrs-es.herokuapp.com/) - A slack team for those who want to chat about Domain-Driven Design, CQRS, Event Sourcing and sometimes random things. Main channel is language and framework agnostic.
- [Domain StoryTelling Slack](https://domainstorytelling.slack.com) - A slack team about Domain StoryTelling. It is currently invite only, but you can ask [@hofstef](https://twitter.com/hofstef) for an invitation. The homepage is at [domainstorytelling.org](http://domainstorytelling.org/).
- [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) - Software Engineering Stack Exchange questions tagged *domain-driven-design*.
- [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) - Code Review Stack Exchange questions tagged *domain-driven-design*.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) - Stack Overflow questions tagged *domain-driven-design*.
- [Quora](https://www.quora.com/pinned/Domain-Driven-Design-DDD) - Questions tagged *domain-driven-design*.

## Blogs

- [Nick Chamberlain](https://buildplease.com) - Helpful development and design advice for .NET developers.
- [DDD Weekly](http://dddweekly.com) - Weekly curated links related to DDD/CQRS/ES.
- [Daniel Whittaker](http://danielwhittaker.me) - Want to learn about CQRS and Event Sourcing? This blog is packed with step-by-step articles to give you a head start.
- [Cyrille Martraire](http://cyrille.martraire.com) - Being so immersed in finance while still in love with programming, I’m naturally a big fan of Domain-Driven Design by Eric Evans, along with TDD, BDD and agile/XP practices.
- [Jimmy Bogard](https://lostechies.com/jimmybogard/) - I focus on DDD, distributed systems, and any other acronym-centric design/architecture/methodology.
- [CodeBetter](http://codebetter.com) - CodeBetter.Com exists in order to help foster awareness of better practices, superior tools, proven methodologies and techniques within the software development community.
- [Greg Young](https://goodenoughsoftware.net/) - Good Enough Software is By Definition Good Enough.
- [InfoQ Blog](https://www.infoq.com/domaindrivendesign/) - Domain-Driven Design Content on InfoQ.
- [Dan North](https://dannorth.net/blog/) - Inventor of Behavior-Driven Design.  Blogs and talks about Event Storming also.
- [Mike Mogosanu](http://blog.sapiensworks.com) - Maintainable code is a business advantage.  Creator of Domain Map: The Domain Modeling Tool - Easy And Powerful Domain Driven Design.
- [Christian Posta](http://blog.christianposta.com) - Principal Middleware Architect @ Red Hat, open-source enthusiast, committer @ Apache, Cloud, Integration, Kubernetes, Docker, OpenShift, Fabric8.
- [Vladimir Khorikov](http://enterprisecraftsmanship.com) - Pluralsight author.  Blogs about software development principles and best practices.
- [TechBeacon](http://techbeacon.com/) - Articles on TechBeacon tagged *domain driven design*.
- [Derek Comartin](http://codeopinion.com) - Articles under the category *Domain Driven Design*.
- [Alberto Brandolini](https://ziobrando.blogspot.it) - Inventor of Event Storming. Asserting that problems cannot be solved with the same mindset that originated them, Alberto switches perspective frequently assuming the architect, mentor, coach, manager or developer point of view.
- [Jérémie Chassaing](http://thinkbeforecoding.com/) - Various articles about DDD/CQRS.  Implemented Greg Young's SimpleCQRS sample in F#.
- [Vaughn Vernon](https://vaughnvernon.co) - Vaughn Vernon understands the unique demands of software development and the challenges you face as you improve your craft in a fast-paced industry.
- [Vladik Khononov](http://vladikk.com/) - Various DDD-related articles.
- [Eventsourcing Publications](https://blog.eventsourcing.com) - Practical event sourcing.
- [Jef Claes](http://www.jefclaes.be/) - Excellent articles and talks on Domain-Driven Design.
- [Udi Dahan](http://udidahan.com/articles/) - From the creator of NServiceBus.
- [Chris Patterson](https://lostechies.com/chrispatterson/) - From the creator of the MassTransit distributed application framework.
- [Aaron Stannard](http://www.aaronstannard.com/) - From the CTO and co-founder of Petabridge, developers of the Akka.NET Actor Model framework.
- [Roger Johansson](https://rogeralsing.com/) - Mostly C#, DDD, and Akka.NET.
- [Konrad Garus](http://squirrel.pl/blog/) - Ranting and Programming in Java, Clojure, and JavaScript.  Articles tagged under *cqrs*.
- [Oasis Digital](http://blog.oasisdigital.com/category/cqrs/) - Content by Oasis Digital tagged under *cqrs*.
- [Adaptech](http://adaptechsolutions.net/blog/) - Adaptech Solutions blog.  Our founder, Adam Dymitruk, debated the merits of CQRS with Greg Young before Greg coined the term. Adam and business partner Robert Reppel are among the leading practitioners of event-sourced microservices.
- [Lev Gorodinski](http://gorodinski.com/) - Several articles about DDD from 2013, which are still relevant.
- [Dino Esposito](https://software2cents.wordpress.com/) - Software architect, trainer, book author.  Author of [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/).
- [Dan Bergh Johnsson "Dear Junior"](http://dearjunior.blogspot.se/search/label/domain%20driven%20design) - Domain-Driven Design mixed with security, and agile in general. Written as fictional letters to a younger programmer.
- [the native web](https://www.thenativeweb.io/blog/2017-10-25-09-46-ddd-and-co-part-1-whats-wrong-with-crud/) - DDD & Co. series
- [Arkency](https://blog.arkency.com/) - Various DDD, CQRS, Event Sourcing related articles from Ruby experts.

## Sample Projects

- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Reactive Trader Cloud by Adaptive Consulting.
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d) - Example of Domain Driven Design for the game of checkers. There are two files: a scratch file with a series of designs, and a final version.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) - Greg Young's "Simplest Thing" CQRS with Event Sourcing project.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://naa4e.codeplex.com/SourceControl/latest) by Dino Esposito.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) - Sample code from CQRS Journey.
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) - Domain Driven Design, CQRS, & Event Sourcing Example using GetEventStore, CommonDomain, NServiceBus, Entity Framework, SQL Server, SignalR.
- [Scritchy](https://github.com/ToJans/Scritchy) - CQRS without the Plumbing, [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - These are the sample Bounded Contexts from the book "Implementing Domain-Driven Design" by Vaughn Vernon: [http://vaughnvernon.co/?page_id=168](http://vaughnvernon.co/?page_id=168).
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon: [http://vaughnvernon.co/?page_id=168](http://vaughnvernon.co/?page_id=168).
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) - Demo project to implement the CQRS and Event Sourcing patterns in Scala-Akka.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) - DDD-CQRS sample v2.0 project that helps you with starting out advanced domain modeling using Spring, JPA and testing.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) - Sample implementation in PHP.
- [Fohjin](https://github.com/MarkNijhof/Fohjin) - Example project that accompanies Mark Nijhof's [CQRS](https://leanpub.com/cqrs) book.
- [Lokad IDDD Sample](https://github.com/Lokad/lokad-iddd-sample) - This is a .NET Sample Project to accompany Event Sourcing materials from the book by Vaughn Vernon: Implementing Domain-Driven Design.
- [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) - ContosoUniversity on ASP.NET Core with Full .NET Framework.
- [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
- [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) (Java) - A simplified (in memory) example of Event Sourcing and CQRS implementation for Java code (modeled for banking domain use cases).
- [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) - A pragmatic application of Event Sourcing and CQRS in Java with good references for common related problems, e.g. event ordering and idempotency.
- [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) - A sample application in PHP built with Symfony 3 and Vue.js.
- [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) - Sample event sourced application with Command Query Responsibility Segregation
- [wolkenkit-todomvc](https://github.com/thenativeweb/wolkenkit-todomvc) - TodoMVC built with DDD, CQRS and event-sourcing
- [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) - An idiomatic F# implementation of Domain-Driven Design
- [Complete example of Domain-Driven Design enterprise application](https://github.com/michal-michaluk/factory) - Complete example of Domain-Driven Design enterprise application built on Spring Boot and Hibernate, backed by event storming analysis.

## Libraries and Frameworks

- [Event Store](https://geteventstore.com) - The open-source, functional database with Complex Event Processing in JavaScript.
- [Axon Framework](http://www.axonframework.org/) - The axon framework is focused on making life easier for developers that want to create a java application based on the CQRS principles.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - Described in this video: [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NEventStore](https://github.com/NEventStore/NEventStore) - A persistence library used to abstract different storage implementations when using event sourcing as storage mechanism.
- [Projac](https://github.com/yreynhout/Projac) - Projac is a set of projection libraries that allow you to write projections targetting various backing stores.
- [Streamstone](https://github.com/yevhen/Streamstone) - Event Store for Azure Table Storage.
- [Value](https://github.com/tpierrain/Value) - Help you to easily implement Value Types in your C# projects without making errors nor polluting your domain logic with boiler-plate code.
- [Cirqus](https://github.com/d60/Cirqus) - d60 event sourcing + CQRS framework.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) - Lightweight infrastructure for doing eventsourcing using aggregates.
- [JESA](https://github.com/yreynhout/JESA) -  Event sourced aggregates for Java.
- [EventFlow](https://github.com/eventflow/EventFlow) - Async/await first CQRS+ES and DDD framework for .NET http://geteventflow.net/.
- [cqrs.js](http://cqrs.js.org) - CQRS implementations in node.js.  Includes [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [Eventsourcing](https://eventsourcing.com) - Business event capture and querying framework.
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) CQRS on Windows Azure.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) - A set of building blocks that enable you to code business logic according to the Domain-Driven Design (DDD) approach.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) - .NET Stream Store library targeting SQL based implementations.
- [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling) - Middleware to handling commands over HTTP; typically used in CQRS applications.
- [NServiceBus](https://github.com/Particular/NServiceBus) - Service bus for .NET.
- [MassTransit](https://github.com/MassTransit/MassTransit) - Distributed Application Framework for .NET.
- [Akka.NET](http://getakka.net/) - Akka.NET is a toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - ASP.NET MVC, Web API and ASP.NET Core based application framework to create NLayered, Domain Driven Designed web Applications implementing best practices.
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) - .NET event sourced domain driven design model via NServicebus and GetEventStore.
- [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - Making it easier to convert strings to/from .NET types.
- [Commanded](https://github.com/slashdotdash/commanded) - Command handling middleware for CQRS/ES applications, Pure Functional Data Structures for Aggregates and Process Managers, Point-to-Point message routing, and much more in Elixir (Erlang VM) - All in Actor concurrency model.
- [akka-ddd](https://github.com/pawelkaczor/akka-ddd) - Reusable artifacts for building applications on top of the Akka platform following CQRS/DDDD-based approach.
- [eventstore](https://github.com/slashdotdash/eventstore) - CQRS event store using PostgreSQL for persistence.
- [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) - NodeJS web API boilerplate for DDD and Clean Architecture applications.
- [wolkenkit](https://www.wolkenkit.io/) - A CQRS, DDD, and event-sourcing framework for JavaScript and Node.js.
- [Broadway](https://github.com/broadway/broadway) - Broadway is a (PHP) project providing infrastructure and testing helpers for creating CQRS and event sourced applications.
- [shriek-fx](https://github.com/ElderJames/shriek-fx) - An simple,elegant and useful Domain-Driven Design and CQRS framework developed using .NET Core 2.0.
- [Rails Event Store](https://railseventstore.org) - Rails Event Store (RES) is a library for publishing, consuming, storing and retrieving events. It's your best companion for going with an event-driven architecture for your Rails application.

## Podcasts and Interviews

- [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) - 11 June 2015.
- [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) - 19 August 2014.
- [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) - 10 May 2007.
- [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) - 29 August 2006.
- [Being the Worst](http://www.beingtheworst.com) - 2012 thru 2016.
- [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) - 13 May 2015.
- [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) - 30 January 2015.

## Conferences

- [Domain-Driven Design Europe - Netherlands](http://www.dddeurope.com)
- [Explore DDD - USA](http://exploreddd.com/)
- [Kandddinsky - Germany](http://kandddinsky.com/)

## User Groups

- [Belgium](http://www.meetup.com/dddbelgium/)
- [Berlin](http://www.meetup.com/Domain-Driven-Design-Berlin/)
- [Cologne/Bonn](https://www.meetup.com/Domain-Driven-Design-Koln-Bonn/)
- [Denver](https://www.meetup.com/ddd-denver/)
- [Greece](https://www.meetup.com/dddgreece/)
- [Hamburg](https://www.meetup.com/DDD-HH-Domain-driven-Design-Hamburg/)
- [Kraków](http://www.meetup.com/ddd-krk/)
- [London](http://www.meetup.com/dddlondon/)
- [Munich](http://www.meetup.com/Domain-Driven-Design-Munich/)
- [Nederland](http://www.meetup.com/Domain-Driven-Design-Nederland/)
- [Norway](https://www.meetup.com/dddnorway/)
- [Phoenix](https://www.meetup.com/DDD-Phoenix)
- [Wroclaw](http://www.meetup.com/DDD-WRO)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nick Chamberlain](https://buildplease.com) has waived all copyright and related or neighboring rights to this work.
