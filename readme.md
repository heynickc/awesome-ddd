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
- [User Groups](#user-groups)

## Books

- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215) - The canonical book that coined the term Domain-Driven Design.  Also known as the "Blue Book."
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) - A summary of the patterns and definitions of DDD.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - Tangentially connected to DDD, describes the importance of the Ubiquitous Language and working together with domain experts, along with lots of technical details.
- [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) - Also a canonical book presenting a top-down approach to understanding Domain-Driven Design.  Also known as the "Red Book."
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - Very good starter book before you read *Implementing Domain-Driven Design* or *Domain Driven Design: Tackling the Complexity at the Heart of Software.*
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - A software architect’s digest of core practices, pragmatically applied.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - Discover how a Living Documentation can help you in all aspects of your projects, from the business goals to the business domain knowledge, architecture and design, processes and deployment, even if you hate writing documentation.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - The deepest tutorial and explanation about EventStorming, straight from the inventor.
- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - An infographic on the anatomy of Domain-Driven Design.
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - Exploring CQRS and Event Sourcing.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - Domain Driven Design Quickly is a short, quick-readable summary and introduction to the fundamentals of DDD.
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles, Tactical Design, and Bounded Context Integration.
- [CQRS](https://leanpub.com/cqrs) - In 2009 I have had the pleasure of spending a 2 day course and many geek beers with Greg Young talking about Domain-Driven Design specifically focused on Command Query Responsibility Segregation (CQRS).

## Training Courses

- [Domain Language eLearning](http://elearn.domainlanguage.com/) - Using our video lessons with Eric Evans, author of the original book on Domain-Driven Design (DDD), teach yourself techniques for evolving practical models that improve your software — not just your documents.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - These videos include the entirety of Greg Young's DDD, CQRS, and Event Sourcing class.
- [Distilling Domain-Driven Design](https://forcomprehension.com/) - Vaughn Vernon's online training course.
- [Advanced Distributed Systems Design](https://5757066.flickrocket.com/us/) - Udi's live training schedule can be found [here](http://udidahan.com/training/).
- [Nomad PHP: Introduction to Event Sourcing and CQRS](https://nomadphp.com/product/introduction-event-sourcing-cqrs/)
- [Event Sourcery](https://eventsourcery.com/) - Introduction to DDD, CQRS, and Event Sourcing.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - Teaches the fundamentals of Domain-Driven Design (DDD) through a demonstration of customer interactions and a complex demo application, along with advice from Eric Evans.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - A descriptive, in-depth walk-through for applying Domain-Driven Design principles in practice.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing) - This course covers DDD analysis patterns helpful in discovering the top-level architecture of a business domain. Architects and developers will find details of implementation patterns such as Domain Model, CQRS, and Event Sourcing.

## Video Collections

- [DDD Europe](https://dddeurope.com) - Recordings of talks given at DDD Europe.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - Searching DDD returns various talks given by Greg Young, Alberto Brandolini, and Dan North, etc.
- [Alberto Brandolini: Event Storming (YouTube)](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) - A YouTube collection of talks given by Alberto Brandolini on Event Storming.
- [Greg Young (YouTube)](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) - A YouTube collection of various talks given by Greg Young.

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) - An active mailing list and an excellent resource to ask questions and learn fine-grained details about DDD/CQRS.
- [Domain Driven Design Yahoo Group](https://groups.yahoo.com/neo/groups/domaindrivendesign/conversations/messages) - This group is for discussion of the domain-driven style of designing software, and the book by Eric Evans, Domain-Driven Design: Tackling Complexity in the Heart of Business Software. Questions and discussion of the book content is welcome here, as well as sharing of experiences applying DDD, and discussions of the topic in general.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - The place to discuss Domain-Driven Design, CQRS, Event Sourcing, Model Storming, Hexagonal Architecture, Distributed Systems, Reactive... in the context of PHP.
- [EventStormers Google+ Community](https://plus.google.com/u/0/communities/113258571348605620818) - A public discussion group for everybody interested in EventStorming, and related themes.
- [DDD/CQRS/ES Slack](https://ddd-cqrs-es.herokuapp.com/) - A slack team for those who want to chat about Domain-Driven Design, CQRS, Event Sourcing and sometimes random things. Main channel is language and framework agnostic.
- [Stack Exchange](https://programmers.stackexchange.com/questions/tagged/domain-driven-design) - Stack Exchange questions tagged *domain-driven-design*.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) - Stack Overflow questions tagged *domain-driven-design*.

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

## Sample Projects

- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Reactive Trader Cloud by Adaptive Consulting.
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d) - Example of Domain Driven Design for the game of checkers. There are two files: a scratch file with a series of designs, and a final version.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) - Greg Young's "Simplest Thing" CQRS with Event Sourcing project.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://naa4e.codeplex.com/SourceControl/latest) by Dino Esposito.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) - Sample code from CQRS Journey.
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) - Domain Driven Design, CQRS, & Event Sourcing Example using GetEventStore, CommonDomain, NServiceBus, Entity Framework, SQL Server, SignalR.
- [Scritchy](https://github.com/ToJans/Scritchy) - CQRS without the Plumbing, [video](http://www.youtube.com/watch?v=5DKTFZD3hu8)
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - These are the sample Bounded Contexts from the book "Implementing Domain-Driven Design" by Vaughn Vernon: [http://vaughnvernon.co/?page_id=168](http://vaughnvernon.co/?page_id=168).
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon: [http://vaughnvernon.co/?page_id=168](http://vaughnvernon.co/?page_id=168).
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) - Demo project to implement the CQRS and Event Sourcing patterns in Scala-Akka.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) - DDD-CQRS sample v2.0 project that helps you with starting out advanced domain modeling using Spring, JPA and testing.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) - Sample implementation in PHP.
- [Fohjin](https://github.com/MarkNijhof/Fohjin) - The example project I created based on these discussions was very well received by the community and regarded a good reference project to explain and learn the patterns that make up CQRS.

## Libraries and Frameworks

- [Event Store](https://geteventstore.com) - The open-source, functional database with Complex Event Processing in JavaScript.
- [Axon Framework](http://www.axonframework.org/) - The axon framework is focused on making life easier for developers that want to create a java application based on the CQRS principles.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - Described in this video: [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NEventStore](https://github.com/NEventStore/NEventStore) - A persistence library used to abstract different storage implementations when using event sourcing as storage mechanism.
- [Projac](https://github.com/yreynhout/Projac) - Projac is a set of projection libraries that allow you to write projections targetting various backing stores.
- [Streamstone](https://github.com/yevhen/Streamstone) - Event Store for Azure Table Storage.
- [Value](https://github.com/tpierrain/Value) - Help you to easily implement Value Types in your C# projects without making errors nor polluting your domain logic with boiler-plate code.
- [Cirquis](https://github.com/d60/Cirqus) - d60 event sourcing + CQRS framework.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) - Lightweight infrastructure for doing eventsourcing using aggregates.
- [JESA](https://github.com/yreynhout/JESA) -  Event sourced aggregates for Java.
- [EventFlow](https://github.com/eventflow/EventFlow) - Async/await first CQRS+ES and DDD framework for .NET http://geteventflow.net/.
- [cqrs.js](http://cqrs.js.org) - CQRS implementations in node.js.  Includes [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [Eventsourcing](https://eventsourcing.com) - Business event capture and querying framework.
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) CQRS on Windows Azure.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) - A set of building blocks that enable you to code business logic according to the Domain-Driven Design (DDD) approach.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) - .NET Stream Store library targeting SQL based implementations.
- [NServiceBus](https://github.com/Particular/NServiceBus) - Service bus for .NET.
- [MassTransit](https://github.com/MassTransit/MassTransit) - Distributed Application Framework for .NET.
- [Akka.NET](http://getakka.net/) - Akka.NET is a toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - ASP.NET MVC, Web API and ASP.NET Core based application framework to create NLayered, Domain Driven Designed web Applications implementing best practices.
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) - .NET event sourced domain driven design model via NServicebus and GetEventStore.

## Podcasts and Interviews

- [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) - 11 June 2015.
- [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) - 19 August 2014.
- [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) - 10 May 2007.
- [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) - 29 August 2006.
- [Being the Worst](http://www.beingtheworst.com) - 2012 thru 2016.
- [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) - 13 May 2015.
- [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) - 30 January 2015.

## User Groups

- [Belgium](http://www.meetup.com/dddbelgium/)
- [Munich](http://www.meetup.com/Domain-Driven-Design-Munich/)
- [Berlin](http://www.meetup.com/Domain-Driven-Design-Berlin/)
- [Nederland](http://www.meetup.com/Domain-Driven-Design-Nederland/)
- [London](http://www.meetup.com/dddlondon/)
- [Kraków](http://www.meetup.com/ddd-krk/)
- [Wroclaw](http://www.meetup.com/DDD-WRO)
- [Phoenix](https://www.meetup.com/DDD-Phoenix)
- [Denver](https://www.meetup.com/ddd-denver/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nick Chamberlain](https://buildplease.com) has waived all copyright and related or neighboring rights to this work.
