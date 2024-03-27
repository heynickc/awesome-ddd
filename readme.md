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

- [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd/)
	- [Contents](#contents)
	- [Books](#books)
	- [Free eBooks](#free-ebooks)
	- [Training Courses](#training-courses)
	- [Video Collections](#video-collections)
	- [Community Resources](#community-resources)
	- [Blogs](#blogs)
	- [Sample Projects](#sample-projects)
		- [GO](#go)
		- [.NET (C#/F#)](#net-cf)
		- [Haskell](#haskell)
		- [Idris](#idris)
		- [JavaScript / TypeScript](#javascript--typescript)
		- [JVM languages](#jvm-languages)
		- [PHP](#php)
	- [Libraries and Frameworks](#libraries-and-frameworks)
		- [GO](#go-1)
		- [.NET](#net)
		- [Databases](#databases)
		- [Elixir](#elixir)
		- [JavaScript / TypeScript](#javascript--typescript-1)
		- [JVM](#jvm)
		- [PHP](#php-1)
		- [Python](#python)
		- [Ruby](#ruby)
	- [Podcasts and Interviews](#podcasts-and-interviews)
	- [Conferences](#conferences)
	- [User Groups](#user-groups)
	- [Tools](#tools)
	- [License](#license)

## Books

- [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) - A walkthrough of using EventStorming and other modeling techniques to build a CQRS and Event Sourcing-based prototype for a fictional business domain.
- [Architecture Modernization](https://www.manning.com/books/architecture-modernization) - Concrete tools, techniques, and processes to align software architecture with your business domains, organizational design, team topologies, and corporate strategy.
- [Collaborative Software Design](https://www.manning.com/books/collaborative-software-design) - A practical guide for effectively involving all stakeholders in the design of software.A practical guide for effectively involving all stakeholders in the design of software.
- [CQRS](https://leanpub.com/cqrs) - Notes by Mark Nijhof from his experiences learning DDD and CQRS from Greg Young.  There is an extensive sample project that accompanies this book.
- [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215) - The canonical book that coined the term Domain-Driven Design.  Also known as the "Blue Book."
- [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - Very good starter book before you read [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) or [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
- [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles, Tactical Design, and Bounded Context Integration.
- [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) - Domain-Driven Rails describes 11 techniques (from Bounded Contexts to Event Sourcing) that you can use separately and together in new and old Rails apps to achieve better architecture.
- [Domain Modeling Made Functional](https://pragprog.com/book/swdddf/domain-modeling-made-functional) - Tackle Software Complexity with Domain-Driven Design and F#.
- [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - Tangentially connected to DDD, describes the importance of the Ubiquitous Language and working together with domain experts, along with lots of technical details.
- [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) - A walkthrough of using Domain-Driven Design with Event Sourcing and CQRS using ASP.NET Core and SQL Server in production.
- [Hands-On Domain-Driven Design with .NET Core](https://www.amazon.com/Hands-Domain-Driven-Design-NET-dp-1788834097/dp/1788834097) - Tackling complexity in the heart of software by putting DDD principles into practice by Alexey Zimarev.
- [Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577) - Also a canonical book presenting a top-down approach to understanding Domain-Driven Design.  Also known as the "Red Book."
- [Implementing DDD, CQRS and Event Sourcing](https://leanpub.com/implementing-ddd-cqrs-and-event-sourcing) - Learn how to implement DDD, CQRS and Event Sourcing. Understand the theory and put it into practice with JavaScript and Node.js.
- [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - The deepest tutorial and explanation about EventStorming, straight from the inventor.
- [Learning Domain-Driven Design: Aligning Software Architecture and Business Strategy](https://www.amazon.com/Learning-Domain-Driven-Design-Aligning-Architecture/dp/1098100131/) - Learn the essential patterns and practices of domain-driven design and how to apply them in your day-to-day work, both in greenfield and brownfield projects.
- [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - A software architect’s digest of core practices, pragmatically applied.
- [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
- [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson&a_bid=0b3fac80) - Shows how to use Domain-Driven Design to avoid security vulnerabilities.
- [Specification by Example](https://www.manning.com/books/specification-by-example) - This book distills from the experience of leading teams worldwide effective ways to specify, test, and deliver software in short, iterative delivery cycles. Case studies in this book range from small web startups to large financial institutions, working in many processes including XP, Scrum, and Kanban.
- [Versioning in an Event Sourced System](https://leanpub.com/esversioning) - Have you had troubles with versioning an Event Sourced system? Just getting into a new Event Sourced system for the first time? This book is the definitive guide of how to handle versioning over long periods of time.
- [What is Domain-Driven Design?](https://learning.oreilly.com/library/view/what-is-domain-driven/9781492057802/) - A quick read exploring the core patterns and principles of Domain-Driven Design, as well as strategies for applying DDD in brownfield projects.
- [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) - Writing Great Specifications is an example-rich tutorial that teaches you how to write good Gherkin specification documents that take advantage of Specification by Example's benefits.
- 

## Free eBooks

- [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - An infographic on the anatomy of Domain-Driven Design.
- [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://dotnet.microsoft.com/download/thank-you/aspnet-ebook) - Provides end-to-end guidance on building monolithic web applications using DDD, ASP.NET Core, and Azure. [eShopOnWeb sample](https://github.com/dotnet-architecture/eShopOnWeb)
- [Architecture Patterns with Python](https://www.cosmicpython.com/book/preface.html) - A book about Pythonic application architecture patterns for managing complexity.
- [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - Exploring CQRS and Event Sourcing.
- [Domain-Driven Design: The First 15 Years](https://dddeurope.com/15years) - To celebrate the anniversary, we've asked prominent authors in the software design world to contribute old and new essays. With contributions by Martin Fowler, James Coplien, Rebecca Wirfs-Brock, Mel Conway, and many more.
- [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) - A summary of the patterns and definitions of DDD.
- [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - Domain Driven Design Quickly is a short, quick-readable summary and introduction to the fundamentals of DDD.
- [Effective Aggregate Design](http://dddcommunity.org/library/vernon_2011/) -  In this three-part series, Vaughn Vernon walks through some common design pitfalls, discusses the pros and cons of various aggregate modeling choices, and provides rules of thumb to guide modeling of aggregates.
- [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) - Describes three strategies for getting started with DDD when you have a big commitment to legacy systems.
- [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - Discover how a Living Documentation can help you in all aspects of your projects, from the business goals to the business domain knowledge, architecture and design, processes and deployment, even if you hate writing documentation.
- [.NET Microservices: Architecture for Containerized .NET Applications](https://dotnet.microsoft.com/download/thank-you/microservices-architecture-ebook) - An introduction to developing microservices-based applications and managing them using containers. [eShopOnContainers sample](https://github.com/dotnet-architecture/eShopOnContainers)
- [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) - A 68 pages long free ebook on what DDD, CQRS and event-sourcing are, and how they fit each other.
- [DDD Magazine from Xebia #1](https://pages.xebia.com/domain-driven-design-magazine-xebia) - This magazine is packed with visionary and practical insights, based on personal, business, and customer experiences to support you on your DDD journey
- [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) - Visual Collaboration Tools is a book for teams building software. It describes tools that help us in our daily job, and also present field stories from different practitioners.

## Training Courses
- [Advanced Distributed Systems Design](https://learn-particular.thinkific.com/courses/adsd-online) - Online training course from Udi Dahan.  Udi's live training schedule can be found [here](http://udidahan.com/training/).
- [DDD Workshops across Europe and Online](https://training.dddeurope.com/) - Public Workshops by Eric Evans, Alberto Brandolini, Mathias Verraes, Rebecca Wirfs-Brock, Nick Tune, and many more.
- [DDD Workshop by Xebia](https://xebia.com/academy/en/search?query=Domain-driven%20design) - public and in-house Domain-driven design workshops from foundation to professional level.
- [Distilling Domain-Driven Design](https://www.informit.com/store/domain-driven-design-livelessons-video-training-9780134597324) - Vaughn Vernon's online training course.
- [Domain Language eLearning](http://elearn.domainlanguage.com/) - Using our video lessons with Eric Evans, author of the original book on Domain-Driven Design (DDD), teach yourself techniques for evolving practical models that improve your software — not just your documents.
- [Event Sourcery](https://www.youtube.com/@EventSourcery) - Introduction to DDD, CQRS, and Event Sourcing.
- [EventStorming Fundamentals Course](https://elearning.dsolemorera.com/courses/eventstorming-fundamentals) ([also in Spanish](https://elearning.dsolemorera.com/courses/fundamentos-eventstorming)) - learn the fundamentals of EventStorming. Everything about EventStorming with examples.
- [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - These videos include the entirety of Greg Young's DDD, CQRS, and Event Sourcing class.
- [Mixter](https://github.com/DevLyon/mixter) - CQRS and Event Sourcing Koans.
- [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) - Introduction to Event Sourcing and CQRS.
- [Pluralsight](https://pluralsight.com)
	 - [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - Teaches the fundamentals of Domain-Driven Design (DDD) through a demonstration of customer interactions and a complex demo application, along with advice from Eric Evans.
	 - [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - A descriptive, in-depth walk-through for applying Domain-Driven Design principles in practice.
	 - [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing) - This course covers DDD analysis patterns helpful in discovering the top-level architecture of a business domain. Architects and developers will find details of implementation patterns such as Domain Model, CQRS, and Event Sourcing.
- [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) - Introduction to DDD, fundamentals of CQRS & Event Sourcing for Ruby/Rails developers.
- [Reactive Architecture: CQRS and Event Sourcing](https://cognitiveclass.ai/courses/reactive-architecture-cqrs/) - This course will discuss the reasons we use CQRS/ES, what benefits it provides us, but also what it will cost us to use. We will see how CQRS/ES can impact the scalability, consistency, and availability of our application.
- [Reactive Architecture: Domain Driven Design](https://cognitiveclass.ai/courses/reactive-architecture-ddd/) - Use DDD to decompose a problem domain into manageable parts. Learn how those parts can become the foundation of Reactive Microservices and Reactive Architecture. Free, online, self-paced. Certificate offered upon completion.
- [Spatie's Event Sourcing Course](https://spatie.be/products/event-sourcing-in-laravel) - Learn how to build event sourced applications in Laravel using Spatie's event-sourcing package. Has 2 hours of video content and an accompanying ebook.

## Video Collections

- [DDD Europe](https://dddeurope.com/videos) - Recordings of talks given at DDD Europe.
- [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - Searching DDD returns various talks given by Greg Young, Alberto Brandolini, and Dan North, etc.
- [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) - A YouTube collection of talks given by Alberto Brandolini on Event Storming.
- [GlobalAppTesting TechTalks](https://vimeo.com/showcase/gatengineering) - A vimeo channel focused on DDD and CQRS.
- [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) - A YouTube collection of various talks given by Greg Young.
- [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) - Recordings of the talks given at the Explore DDD conference.
- [KanDDDinsky](https://www.youtube.com/channel/UCJCpnslPdb_Dl8DKokXC3HA) - A YouTube collection of talks given at KanDDDinsky.
- [Virtual Domain-driven design](https://www.youtube.com/channel/UCob_jOzzpxBp-di-x0vLlwA) - A youtube collection of recorded meetups session from Virtual Domain-driven design
- [Visuality DDD webinars](https://youtube.com/playlist?list=PLvMNoWK93wtnu9JcSEYnFRgzqbxtLtZZ4) - A YouTube collection of webinars focused on DDD in Ruby on Rails
- [The Art of Discovering Bounded Contexts by Nick Tune](https://www.youtube.com/watch?v=ez9GWESKG4I) - Session from 2017 DevoxxUK on how to define bounded contexts

## Community Resources

- [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email#!forum/dddcqrs) - An active mailing list and an excellent resource to ask questions and learn fine-grained details about DDD/CQRS.
- [DDD-es Google Group](https://groups.google.com/g/ddd-es) - The Google Group to discuss Domain-Driven Design in Spanish.
- [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - The place to discuss Domain-Driven Design, CQRS, Event Sourcing, Model Storming, Hexagonal Architecture, Distributed Systems, Reactive... in the context of PHP.
- [EventStorming Google Group](https://groups.google.com/g/eventstorming) - The Google Group to discuss EventStorming.
- [DDD in Ruby on Rails](https://www.visuality.pl/posts/introduction-to-ddd-in-ruby-on-rails) - A collection of articles on Domain-Driven Design in Ruby on Rails
- [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - A subreddit for Ruby developers interested in Domain-Driven Design.
- [DDD/CQRS/ES Discord](https://github.com/ddd-cqrs-es/community) - A Discord (old Slack) team for those who want to chat about Domain-Driven Design, CQRS, Event Sourcing and sometimes random things. Main channel is language and framework agnostic.
- [Domain StoryTelling Discord](https://discord.gg/KsYaHNNn33) - A Discord team about Domain StoryTelling (#domain-storytelling channel) by [@hofstef](https://twitter.com/hofstef). The homepage is at [domainstorytelling.org](http://domainstorytelling.org/).
- [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) - Software Engineering Stack Exchange questions tagged *domain-driven-design*.
- [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) - Code Review Stack Exchange questions tagged *domain-driven-design*.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) - Stack Overflow questions tagged *domain-driven-design*.
- [Advanced Topics in Event Sourcing / CQRS / DDD](https://github.com/sebastianharko/adv-es-cqrs-ddd) - Advanced Topics in Event Sourcing / CQRS / DDD list compiled and maintaned by @[sebastianharko](https://github.com/sebastianharko).
- [Quora](https://www.quora.com/topic/Domain-Driven-Design-DDD) - Questions tagged *domain-driven-design*.
- [wolkenkit Slack](http://slackin.wolkenkit.io/) - A Slack team on DDD, event-sourcing, CQRS and wolkenkit.
- [Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming) - awesome list that focuses only on Event Storming.
- [Awesome Domain Storytelling](https://github.com/hofstef/awesome-domain-storytelling) - awesome list that focuses only on Domain Storytelling.
- [Virtual Domain-driven design community](https://virtualddd.com) - Online meetups with panel discussions, online collaborations and resource sharing.
- [Domain-driven design heuristics](https://www.dddheuristics.com/) - Domain-Driven Design Heuristics is a community driven site to document and discuss about Design Heuristics.
- [Domain-Driven Design in dynamic languages GitHub](https://github.com/valignatev/ddd-dynamic) - GitHub's profile of Domain-Driven Design in dynamic languages.
- [Domain-Driven Design Crew GitHub](https://github.com/ddd-crew) - GitHub's profile of Domain-Driven Design Crew.
- [Context Mapping by ddd-crew](https://github.com/ddd-crew/context-mapping) - 	Context Mapping Cheatsheet and Starter Kit by ddd-crew.
- [DDD North America](https://dddna.net/) - Upcoming live training, events, and user groups across North America.

## Blogs

- [Nick Chamberlain](https://buildplease.com) - Helpful development and design advice for .NET developers.
- [Ardalis.com](https://ardalis.com/blog) - Steve Smith. Pluralsight author and author of [DDD Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) course and Microsoft [eShopOnWeb sample app](https://github.com/dotnet-architecture/eShopOnWeb).
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
- [Svaťa Šimara](http://svatasimara.cz/) - DDD series - language, domain, modeling, infrastructure, implementation in PHP
- [Martin Havlišta](https://xhafan.com/blog/) - DDD, CQRS, TDD blog posts with code samples in C# .NET
- [Khalil Stemmler](https://khalilstemmler.com/articles/categories/domain-driven-design) - DDD series introduction and talk about how to implement DDD with TypeScript
- [Kenny Baas-Schwegler](https://baasie.com/) - DDD, BDD, Socio-technical, EventStorming and continuous delivery blogs.
- [João Rosa](https://joaorosa.io) - Personal blog about Domain-Driven Design, Visual Collaboration, leadership and organisational design. And other things in between. Curator of [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) and host of the [Software Crafts Podcast](https://www.softwarecraftspodcast.com/)
- [GlobalAppTesting engineering](https://gat.engineering) - GlobalAppTesting's engineering blog with materials on practical DDD and CQRS.

## Sample Projects

### GO
- [BDD in GO](https://github.com/JankariTech/bsDateServer) - Sample app demonstrating the use of Cucumber + GO for a BDD testing approach. Blog post can be found [here](https://dev.to/jankaritech/demonstrating-bdd-behavior-driven-development-in-go-1eci).
- [Citerus DDD Sample App GO Port](https://github.com/marcusolsson/goddd) - This is an attempt to port the [DDD Sample App](https://github.com/citerus/dddsample-core) to idiomatic Go. It can be run in a dockerized mode for previewing the application.
- [DDD by Refactoring](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Complete serverless application to show how to apply DDD, Clean Architecture, and CQRS by practical refactoring of a Go project. A full blog series about it can be found at <https://threedots.tech/>.
- [DDD Food App](https://github.com/victorsteven/food-app-server) - Sample DDD application implementing the 4 layers (Domain, Infrastructure, Application and Interface) and considering two domain patterns. There's a blog article written for it [here](https://dev.to/stevensunflash/using-domain-driven-design-ddd-in-golang-3ee5).
- [DDD Sample in GO](https://github.com/takashabe/go-ddd-sample) - Just another sample application implementing the four layers of DDD.
- [Evolutive CRUD API](https://github.com/friendsofgo/gopherapi) - API implementation with full CRUD using a SOLID, Hexagonal Architecture. There is a series of blog post written for it at <https://blog.friendsofgo.tech/>.
- [Simple Hexagonal Architecture PoC API](https://github.com/tomiok/patients-API) - PoC for a patients API using the hexagonal architecture pattern.
- [Azure DDD boilerplate](https://github.com/joshpme/azure-go-ddd-boilerplate) - A boilerplate project for DDD in Azure using a custom handler and Cosmos DB for event sourcing

### .NET (C#/F#)
- [Better code with DDD building blocks](https://github.com/asc-lab/better-code-with-ddd) - solution presents usage of DDD tactical patterns to achieve better readability and expressiveness of the code. Applying DDD patterns together with ubiquitous language closes the gap between language spoken by experts and the team and language used in the code.
- [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) - Domain Driven Design, CQRS, & Event Sourcing Example using GetEventStore, CommonDomain, NServiceBus, Entity Framework, SQL Server, SignalR.
- [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://github.com/mastreeno/Merp) - An event based Micro ERP.
- [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) - ContosoUniversity on ASP.NET Core with Full .NET Framework.
- [DDD-starter-dotnet](https://github.com/itlibrium/DDD-starter-dotnet) - Sample implementation and comparison of various approaches to building DDD applications. Useful as a baseline to quickly start a DDD .net project.
- [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) - An idiomatic F# implementation of Domain-Driven Design
- [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
- [DotNet CQRS Intro](https://github.com/asc-lab/dotnet-cqrs-intro) - Examples of implementation CQRS with Event Sourcing - evolutionary approach (no CQRS, separate models and commands with the same model, separate models and commands with separate models, separate storage engines, event sourcing).
- [EISK](https://github.com/eisk) - .NET CLI and VS Templates with simple use cases to build scalable applications on top of .net core with architectural best practices (DDD, onion architecture etc).
- [EmailMaker](https://github.com/xhafan/emailmaker) - Email marketing ASP.NET Core MVC and ASP.NET MVC demo app demonstrating [CoreDdd](https://github.com/xhafan/coreddd) usage
- [Equinox Project](https://github.com/EduardoPires/EquinoxProject) - Full ASP.NET Core 3.1 application with Clean Architecture, DDD, CQRS and Event Sourcing concepts
- [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - Full ASP.NET Core 3.1 reference application from Microsoft showing monolithic deployment architecture
- [eShopOnContainersDDD](https://github.com/volak/eShopOnContainersDDD) - eShop fullstack example featuring catalog, basket, checkout, and order bounded contexts
- [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d) - Example of Domain Driven Design for the game of checkers. There are two files: a scratch file with a series of designs, and a final version.
- [Event Sourcing .NET](https://github.com/oskardudycz/EventSourcing.NetCore) - samples and resources about Event Sourcing and CQRS in .NET. Contains also a self-paced kit of how to built own Event Store
- [EventFlow.Example](https://github.com/OKTAYKIR/EventFlow.Example) - DDD, CQRS, and Event-Sourcing example and contains following technology stack: [EventFlow](https://github.com/eventflow/EventFlow), [EventStore](https://eventstore.com), [RabbitMQ](https://www.rabbitmq.com), [MongoDB](https://www.mongodb.com), [PostgreSQL](https://www.postgresql.org), [Docker](https://www.docker.com)
- [Fohjin](https://github.com/MarkNijhof/Fohjin) - Example project that accompanies Mark Nijhof's [CQRS](https://leanpub.com/cqrs) book.
- [FsUno](https://github.com/thinkbeforecoding/FsUno) - Event sourcing implementation sample in F#.
- [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
- [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) - Sample code from CQRS Journey.
- [Modular Monolith](https://github.com/kgrzybek/modular-monolith-with-ddd) - Full Modular Monolith .NET application with Domain-Driven Design approach.
- [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) (.Net Core Preview 2) - a N-Layered Architecture Sample Project.
- [Photostock CQRS-DDD Example](https://github.com/mr0zek/Photostock)
- [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Reactive Trader Cloud by Adaptive Consulting.
- [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.
- [Scritchy](https://github.com/ToJans/Scritchy) - CQRS without the Plumbing, [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
- [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) - Greg Young's SimpleCQRS in F#.
- [SimpleCQRS](https://github.com/gregoryyoung/m-r) - Greg Young's "Simplest Thing" CQRS with Event Sourcing project.
- [TaskoMask](https://github.com/hamed-shirbandi/TaskoMask) - Task management system based on .NET Core with DDD, CQRS and Event Sourcing Concepts.
- [TodoMVC-DDD-CQRS-EventSourcing](https://github.com/volak/TodoMVC-DDD-CQRS-EventSourcing) - Implementation of basic Todo app via tastejs/todomvc in C#/Typescript with eventsourcing, cqrs, and domain driven design

### Haskell
- [Eventuria gsd](https://github.com/Eventuria/gsd) - Haskell todo list reactive application with DDD, CQRS and Event Sourcing, FRP.

### Idris
- [OrderTaking](http://github.com/andorp/order-taking) - Dependently typed implementation of the Domain Modeling Made Functional book. An example project how to formalize Bounded Context and Workflow diagram with dependent types. A NodeJS deployable demo.

### JavaScript / TypeScript
- [wolkenkit Sample Applications](https://docs.wolkenkit.io/latest/media/sample-applications/wolkenkit-boards/) - A collection of DDD sample applications, such as TodoMVC, a geocaching app, collaborative boards etc.
- [Booster framework examples](https://github.com/boostercloud/booster/tree/master/docs/examples) Example applications built with Booster Framework.
- [Over-engineered ToDo app](https://github.com/bitloops/ddd-hexagonal-cqrs-es-eda) - Complete working example of using Domain Driven Design (DDD), Hexagonal Architecture, CQRS, Event Sourcing (ES), Event Driven Architecture (EDA), Behaviour Driven Development (BDD) using TypeScript and NestJS generated using the [Bitloops Language (BL)](https://github.com/bitloops/bitloops-language).

### JVM languages
- [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) - Demo project to implement the CQRS and Event Sourcing patterns in Scala-Akka.
- [DDD By Examples - Library](https://github.com/ddd-by-examples/library) - sample project of a library driven by real business requirements. Modular monolith implemented with the help od DDD, BDD, EventStorming, Example Mapping, CQRS, and more.
- [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) - DDD-CQRS sample v2.0 project that helps you with starting out advanced domain modeling using Spring, JPA and testing.
- [DDD Workshop - Project Manager](https://github.com/mkopylec/project-manager) - "Do It Yourself" DDD workshop and a sample DDD application at the same time. Based on a project managing domain.
- [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) - A simplified (in memory) example of Event Sourcing and CQRS implementation for Java code (modeled for banking domain use cases).
- [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) - A pragmatic application of Event Sourcing and CQRS in Java with good references for common related problems, e.g. event ordering and idempotency.
- [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) - Sample event sourced application with Command Query Responsibility Segregation
- [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - These are the sample Bounded Contexts from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
- [Java CQRS Intro](https://github.com/asc-lab/java-cqrs-intro) - Examples of implementation CQRS with Event Sourcing - evolutionary approach (no CQRS, separate models and commands with the same model, separate models and commands with separate models, separate storage engines, event sourcing).
- [Kotlin DDD Sample](https://github.com/fabriciorissetto/kotlin-ddd-sample) - Sample DDD/CQRS project written in Kotlin.
- [EventStormingWorkshop - Designing Cloud Native Microservices On AWS](https://github.com/humank/EventStormingWorkShop/) - A concrete sample to go through EventStorming workshop and implement DDD tactical design pattern in Java, apply AWS cloud native services to build up business Event based Coffeeshop scenario.
- [DDDSample](https://github.com/citerus/dddsample-core) - Sample DDD project using Spring Boot (originally hosted in http://dddsample.sourceforge.net/)
- [Eclipse CargoTracker](https://eclipse-ee4j.github.io/cargotracker/) - This project demonstrates how you can develop applications with the Jakarta EE platform using widely adopted architectural best practices like Domain-Driven Design (DDD). [The code](https://github.com/eclipse-ee4j/cargotracker/) is intended to mirror a non-trivial application that developers in the real work would work on. It attempts to demonstrate first-hand how you can use Jakarta EE to effectively meet practical enterprise concerns such as productivity, agility, testability, flexibility, maintainability, scalability and security. The project is directly based on the well known original [Java DDD sample application](https://github.com/citerus/dddsample-core) developed by DDD pioneer Eric Evans' company Domain Language and the Swedish software consulting company Citerus. 
- [https://github.com/felipexw/clean-arch-ddd-intro](https://github.com/felipexw/clean-arch-ddd-intro) - Simple DDD + Clean Architecture using Micronaut.

### PHP
- [CodefyPHP Framework](https://github.com/codefyphp/codefy) - A PHP framework for codefying and building complex applications using Domain-Driven Design, CQRS, and Event Sourcing.
- [DDD CQRS Todo Sample](https://github.com/ferrius/ddd-cqrs-example) - DDD CQRS ADR hexagonal architecture implementation built with PHP 7 and Symfony 5.
- [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) - A sample application in PHP built with Symfony 3 and Vue.js.
- [DDD Playground](https://github.com/jorge07/ddd-playground/) - Sample implementation in PHP.
- [Eric Evans DDD Cargo Sample](https://github.com/codeliner/php-ddd-cargo-sample) - PHP 7 Version of the cargo sample used in Eric Evans DDD book
- [Shop Cart in PHP](https://github.com/simara-svatopluk/cart) - Sample project that demonstrates how simple shop cart can look like. Domain objects,Doctrine integration.,TDD,layers,unit testing
- [Symfony 5 DDD ES CQRS backend](https://github.com/jorge07/symfony-5-es-cqrs-boilerplate) - DDD, CQRS and Event Sourcing app using Symfony and PHP 8.

## Libraries and Frameworks

### GO
- [Ginkgo](https://github.com/onsi/ginkgo) - Ginkgo builds on Go's testing package, allowing expressive Behavior-Driven Development ("BDD") style tests.
- [GOBDD](https://github.com/go-bdd/gobdd) - Small BDD framework for GO.
- [GoConvey](https://github.com/smartystreets/goconvey) - Go testing in the browser. Integrates with `go test`. Write behavioral tests in Go.
- [Godog](https://github.com/cucumber/godog) - Package godog is the official Cucumber BDD framework for Golang, it merges specification and test documentation into one cohesive whole, using Gherkin formatted scenarios in the format of Given, When, Then.

### .NET
- [Aggregates.NET](https://github.com/volak/Aggregates.NET) - .NET event sourced domain driven design model via NServicebus and GetEventStore.
- [AggregateSource](https://github.com/yreynhout/aggregateSource) - Lightweight infrastructure for doing eventsourcing using aggregates.
- [Akka.NET](http://getakka.net/) - Akka.NET is a toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
- [ABP](https://abp.io) - Successor of ASP.NET Boilerplate - ASP.NET Core based application framework to create NLayered, Domain Driven Designed web applications with a microservice focused modular architecture
- [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - ASP.NET MVC, Web API and ASP.NET Core based application framework to create NLayered, Domain Driven Designed web Applications implementing best practices.
- [ByValue](https://github.com/sm-g/ByValue) - This library helps to create ValueObjects (even with collection properties) with properly implemented equality behavior.
- [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling) - Middleware to handling commands over HTTP; typically used in CQRS applications.
- [Cirqus](https://github.com/d60/Cirqus) - d60 event sourcing + CQRS framework.
- [CommandQuery](https://github.com/hlaueriksson/CommandQuery) - Command Query Separation for 🌐ASP.NET Core ⚡AWS Lambda ⚡Azure Functions ⚡Google Cloud Functions 🌐ASP.NET Web API 2
- [CoreDdd](https://github.com/xhafan/coreddd) - Set of open-source .NET libraries helping with DDD and CQRS, with NHibernate persistence
- [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) CQRS on Windows Azure.
- [Dolittle](https://dolittle.com) - Build better applications with Dolittle. An Event Sourced, Microservice platform oriented around DDD with developer productivity and simplicity front and center.
- [Edument CQRS and Intentful BDD Testing Starter Kit](https://www.cqrs.nu/) - Library and tutorial for how to build CQRS/ES applications, including a BDD style testing framework.
- [EventFlow](https://github.com/eventflow/EventFlow) - Async/await first CQRS+ES and DDD framework for .NET http://geteventflow.net/.
- [Core.EventStore](https://github.com/younos1986/Core.EventStore) - A library to facilitate communication between CommandService and QueryService. The Idea is when any event occures in commandService, it should be persisted in QueryService in MongoDb.
- [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
- [Marten](https://github.com/JasperFx/marten) - Postgresql as a Document Database and Event Store for .Net Applications.
- [MassTransit](https://github.com/MassTransit/MassTransit) - Distributed Application Framework for .NET.
- [MediatR](https://github.com/jbogard/MediatR) - Supports request/response, commands, queries, notifications and events, synchronous and async with intelligent dispatching via C# generic variance.
- [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - Described in this video: [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
- [NetDevPack](https://github.com/netdevpack) - A smart set of common classes and implementations to improve your development productivity using .NET (DDD, CQRS, Specification Pattern, MediatR, Validations, Notifications).
- [NEventStore](https://github.com/NEventStore/NEventStore) - A persistence library used to abstract different storage implementations when using event sourcing as storage mechanism.
- [NServiceBus](https://github.com/Particular/NServiceBus) - Service bus for .NET.
- [Projac](https://github.com/yreynhout/Projac) - Projac is a set of projection libraries that allow you to write projections targetting various backing stores.
- [shriek-fx](https://github.com/ElderJames/shriek-fx) - An simple,elegant and useful Domain-Driven Design and CQRS framework developed using .NET Core 2.0.
- [SqlStreamStore](https://github.com/damianh/SqlStreamStore) - .NET Stream Store library targeting SQL based implementations.
- [Streamstone](https://github.com/yevhen/Streamstone) - Event Store for Azure Table Storage.
- [Stringly.Typed](https://github.com/mission202/Stringly.Typed) - Making it easier to convert strings to/from .NET types.
- [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.

### Databases
- [Event Store](https://geteventstore.com) - The open-source, functional database with Complex Event Processing in JavaScript.
- [Eventsourcing](https://eventsourcing.com) - Business event capture and querying framework.
- [Message DB](https://github.com/message-db/message-db) - Microservice Native Event Store and Message Store for Postgres. A fully-featured event store and message store implemented in PostgreSQL for Pub/Sub, Event Sourcing, Messaging, and Evented Microservices applications.
- [Serialized](https://serialized.io) - Complete platform for Event Sourcing & CQRS.

### Elixir
- [Commanded](https://github.com/slashdotdash/commanded) - Command handling middleware for CQRS/ES applications, Pure Functional Data Structures for Aggregates and Process Managers, Point-to-Point message routing, and much more in Elixir (Erlang VM) - All in Actor concurrency model.
- [Event Bus](https://github.com/otobus/event_bus) - Traceable, extendable and minimalist event bus implementation for Elixir with built-in event store and event watcher based on ETS.
- [eventstore](https://github.com/slashdotdash/eventstore) - CQRS event store using PostgreSQL for persistence.

### JavaScript / TypeScript

- [cqrs.js](http://cqrs.js.org) - CQRS implementations in node.js.  Includes [node-eventstore](https://github.com/adrai/node-eventstore), [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain), [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer), [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga).
- [wolkenkit](https://www.wolkenkit.io/) - A CQRS, DDD, and event-sourcing framework for JavaScript and Node.js.
- [Bitloops Language (BL)](https://github.com/bitloops/bitloops-language) - Open-source, 4th-generation, transpiled programming language that helps you write clean code, well-designed systems, and build high-quality software that is testable, auditable and maintainable using DDD and Hexagonal Architecture.
- [Booster](https://www.booster.cloud/) - A CQRS, DDD and event-sourcing open-source framework that leverages all the infrastructure and uses high-level abstractions and conventions. It help users build advanved even-driven applications letting them focus on business logic exclusively.  
- [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) - NodeJS web API boilerplate for DDD and Clean Architecture applications.

### JVM
- [akka-ddd](https://github.com/pawelkaczor/akka-ddd) - Reusable artifacts for building applications on top of the Akka platform following CQRS/DDDD-based approach.
- [Apache Isis](https://isis.apache.org/index.html) - Apache Isis is a framework for rapidly developing domain-driven apps in Java.
- [Axon Framework](http://www.axonframework.org/) - The axon framework is focused on making life easier for developers that want to create a java application based on the CQRS principles.
- [DDDplus framework](https://github.com/funkygao/cp-ddd-framework) - A lightweight flexible development framework for complex business architecture based on DDD.
- [JESA](https://github.com/yreynhout/JESA) -  Event sourced aggregates for Java.
- [Lagom](https://www.lagomframework.com) - The Lagom Framework is a microservices framework for the Java Virtual Machine, with APIs for the Java and Scala languages. It includes an Event Sourcing/CQRS based persistence module.
- [SeedStack's Business Framework](http://seedstack.org/docs/business/) - A set of building blocks that enable you to code business logic according to the Domain-Driven Design (DDD) approach.
- [Spine Event Engine](https://spine.io/) - a CQRS/ES framework for building cloud applications. Defines Bounded Contexts with their Commands, Events, and Entity states in Protobuf. The backend logic is written in Java, on top of the Proto-generated code. Client code in Java, JS or Dart communicates with the backend via gRPC.
- [Ahoo-Wang/Wow](https://github.com/Ahoo-Wang/Wow) - A Modern Reactive CQRS Architecture Microservice development framework based on DDD and EventSourcing.

### PHP
- [Broadway](https://github.com/broadway/broadway) - Broadway is a (PHP) project providing infrastructure and testing helpers for creating CQRS and event sourced applications.
- [Ecotone](http://ecotone.tech) - Enables message driven architecture in PHP and provides building blocks to follow DDD and CQRS principles.
- [PHP Glossary](https://github.com/javanile/php-glossary) - Apply a Term Analysis to extract domain terms vs out-of-scope terms in a DDD manner.

### Python
- [Eventsoucing in Python](https://github.com/johnbywater/eventsourcing) - Mature, stable Python library for event sourcing and DDD. Supports wide variety of databases, different kinds of orderings of domain events, application level encryption, snapshotting, optimistic concurrency control, and process events. Applications, and entire systems of applications, can be defined independently of infrastructure, and run in different ways (single threaded, multi-threaded, clocked, stepping, multi-process, actor model) and with different infrastructure.
- [dry-python](https://github.com/dry-python) - A set of libraries for pluggable business logic components.
- [PyAssimilator](https://github.com/knucklesuganda/py_assimilator/) - Quickly create DDD Python patterns, Event-Based Systems, CRUD applications. Set of Python patterns for database access that support SQLAlchemy, MongoDB, Redis, or Pure Python. PyAssimilator allows you to write code without dependencies, meaning you can switch SQL to NoSQL without changing a single file in your system.

### Ruby
- [Eventide](https://eventide-project.org) - Event Sourcing and Microservices Stack for Ruby. A set of libraries for writing event driven, autonomous services.
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

- [Domain-Driven Design Europe](https://dddeurope.com) - The Leading DDD conference (online during COVID19)
- [EventSourcing](https://dddeurope.com/2020/#eventsourcing) - A new event for the CQRS/EventSourcing community
- [DDD Foundations](https://dddeurope.com/2020/#foundations) - A curated conference for DDD newcomers
- [Explore DDD - USA](http://exploreddd.com/)
- [Kandddinsky - Germany](http://kandddinsky.com/)

## User Groups

- [Collective CFP](https://sessionize.com/ddd-meetups) - Submit your talks to all the DDD user groups at once.
- [Map of user groups in Europe](https://datawrapper.dwcdn.net/9FNZI/)
- [Map of user groups in North America](https://datawrapper.dwcdn.net/nbZkd/)
- [Map of user groups in Asia](https://datawrapper.dwcdn.net/oin66/)
- [Map of user groups in Africa](https://datawrapper.dwcdn.net/yaEOa/)
- [Virtual](https://virtualddd.com/)
- [Worldwide](https://www.meetup.com/worldwide-eventstorming-meetup/) - Specific about EventStorming
- [Austria](https://www.meetup.com/ddd-vienna/)
- [Barcelona](https://www.meetup.com/dddbcn/)
- [Belfast](https://dddbelfast.com/)
- [Belgium](http://www.meetup.com/dddbelgium/)
- [Berlin](http://www.meetup.com/Domain-Driven-Design-Berlin/)
- [Cologne/Bonn](https://www.meetup.com/Domain-Driven-Design-Koln-Bonn/)
- [Copenhagen](https://www.meetup.com/copenhagen-domain-driven-design-meetup/)
- [Cracow](http://www.meetup.com/ddd-krk/)
- [DDD Taiwan Community](https://www.facebook.com/groups/dddtaiwan/)
- [Denver](https://www.meetup.com/ddd-denver/)
- [Iran](https://t.me/ddd_iran/)
- [Greece](https://www.meetup.com/dddgreece/)
- [Hamburg](https://www.meetup.com/DDD-HH-Domain-driven-Design-Hamburg/)
- [London](http://www.meetup.com/dddlondon/)
- [Munich](https://www.meetup.com/Microservices-Meetup-Munich/)
- [Nederland](http://www.meetup.com/Domain-Driven-Design-Nederland/)
- [Norway](https://www.meetup.com/dddnorway/)
- [Phoenix](https://www.meetup.com/DDD-Phoenix)
- [Warsaw](https://www.meetup.com/DDD-WAW)
- [Wroclaw](http://www.meetup.com/DDD-WRO)
- [Russia](https://t.me/dddevotion)

## Tools

- [Domain Storytelling](http://www.domainstorytelling.org/) - a knowledge-crunching technique that helps the people involved to familiarize themselves with the domain and work out a model that expresses their shared understanding. Available as a [print-out template](http://www.domainstorytelling.org/images/DST_Whiteboard-Kit.pdf), as well as open-source online tool, [WPS Modeler](https://www.wps.de/modeler) ([source](https://github.com/wps/domain-story-modeler)).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nick Chamberlain](https://buildplease.com) has waived all copyright and related or neighboring rights to this work.
