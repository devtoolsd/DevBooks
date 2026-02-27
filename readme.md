# Awesome DevBooks 

> A curated, opinionated list of **best-in-class** books for modern software development, popular programming languages, and AI/ML. 

**Awesome DevBooks** is a project by [**DevTools Directory**](https://devtools.directory) — a community hub for developer tools, resources, and curated lists.
Find us on [GitHub](https://github.com/devtoolsd).

**Want the complete lists?** Full, expanded book lists live in [data/](data/). Each section below includes a **Full list** link to its dedicated page.

---

## Table of Contents

- [Software Engineering Essentials](#software-engineering-essentials)
- [Architecture, Data & Distributed Systems](#architecture-data--distributed-systems)
  - [Databases](#databases)
- [System Design](#system-design)
- [Computer Science Foundations](#computer-science-foundations)
- [Testing & Quality](#testing--quality)
- [DevOps, CI/CD & Infrastructure](#devops-cicd--infrastructure)
- [Security](#security)
- [Version Control](#version-control)
- [Platforms](#platforms)
- [Major Frameworks](#major-frameworks)
- [Automation](#automation)
- [Monitoring & Observability](#monitoring--observability)
- [APIs](#apis)
- [Cloud](#cloud)
- [Programming Languages](#programming-languages)
  - [Python](#python)
  - [JavaScript / TypeScript](#javascript--typescript)
  - [Java](#java)
  - [Go](#go)
  - [Rust](#rust)
  - [C / C++](#c--c)
  - [C#](#c)
  - [Kotlin](#kotlin)
  - [Swift](#swift)
  - [Ruby](#ruby)
  - [Elixir](#elixir)
  - [Scala](#scala)
  - [PHP](#php)
  - [Functional Programming](#functional-programming)
  - [Shell & Command Line](#shell--command-line)
- [Frontend & Web Development](#frontend--web-development)
- [Mobile Development](#mobile-development)
- [Data Engineering](#data-engineering)
- [AI / Machine Learning](#ai--machine-learning)
  - [Big-Picture AI & Fundamentals](#big-picture-ai--fundamentals)
  - [Deep Learning & Modern Practice](#deep-learning--modern-practice)
  - [AI Engineering, LLMs & Agents](#ai-engineering-llms--agents)
  - [ML Systems & MLOps](#ml-systems--mlops)
- [Career, Communication & Engineering Culture](#career-communication--engineering-culture)
- [Further Reading](#further-reading)
- [Related Projects](#related-projects)
- [Contributing](#contributing)

---

## Software Engineering Essentials

- **[The Pragmatic Programmer *(20th Anniversary Ed.)*](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/)** - *by: Andrew Hunt & David Thomas* - Practical habits, thinking tools, and engineering instincts that age incredibly well.
- **[Code Complete *(2nd Ed.)*](https://www.microsoftpressstore.com/store/code-complete-9780735619678)** - *by: Steve McConnell* - The "how to write good code" encyclopedia: construction, readability, and craft.
- **[Clean Code](https://www.goodreads.com/book/show/3735293-clean-code)** - *by: Robert C. Martin* - Principles and examples for writing code that stays readable under pressure.
- **[Clean Architecture](https://www.goodreads.com/book/show/18043011-clean-architecture)** - *by: Robert C. Martin* - Core architectural ideas for keeping systems maintainable as they grow.
- **[A Philosophy of Software Design *(2nd Ed.)*](https://www.amazon.com/Philosophy-Software-Design-John-Ousterhout/dp/1732102201)** - *by: John Ousterhout* - A sharp counterpoint to Clean Code — argues for deep modules and against over-decomposition.
- **[Refactoring *(2nd Ed.)*](https://martinfowler.com/books/refactoring.html)** - *by: Martin Fowler* - The classic playbook for improving design without changing behavior.
- **[Working Effectively with Legacy Code](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)** - *by: Michael Feathers* - How to add tests and make changes safely in scary, untested codebases.
- **[Design Patterns](https://en.wikipedia.org/wiki/Design_Patterns)** - *by: Gamma, Helm, Johnson, Vlissides* - The OG patterns catalog — treat it as vocabulary, not dogma.
- **[Fundamentals of Software Architecture](https://fundamentalsofsoftwarearchitecture.com/)** - *by: Richards & Ford* - Practical, modern guide to architecture styles, trade-offs, and the architect's role.
- **[The Mythical Man-Month](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)** - *by: Frederick P. Brooks Jr.* - Timeless lessons on why software schedules explode and what to do about it.

> Full list: [data/software-engineering.md](data/software-engineering.md)

---

## Architecture, Data & Distributed Systems

- **[Designing Data-Intensive Applications](https://dataintensive.net/)** - *by: Martin Kleppmann* - The go-to guide for storage, streams, consistency, and real-world system trade-offs.
- **[Domain-Driven Design](https://domainlanguage.com/ddd/)** - *by: Eric Evans* - Modeling complex domains and aligning code with business reality.
- **[Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)** - *by: Vaughn Vernon* - The practical companion to the "big blue book" — DDD with actual code.
- **[Release It! *(2nd Ed.)*](https://pragprog.com/titles/mnee2/release-it-second-edition/)** - *by: Michael T. Nygard* - Stability patterns and failure-mode thinking for production systems.
- **[Site Reliability Engineering](https://sre.google/books/)** - *by: Beyer, Jones, Petoff, Murphy* - Reliability principles, SLOs, toil reduction, and operating at scale — free online.
- **[The SRE Workbook](https://sre.google/workbook/table-of-contents/)** - *by: Beyer, Murphy, Rensin, Kawahara* - Hands-on companion to the SRE book with real implementation examples — free online.
- **[Kubernetes: Up & Running *(3rd Ed.)*](https://www.amazon.com/Kubernetes-Running-Dive-Future-Infrastructure/dp/109811020X)** - *by: Hightower, Burns, Beda* - A practical mental model for Kubernetes and container orchestration.
- **[Building Event-Driven Microservices](https://www.oreilly.com/library/view/building-event-driven-microservices/9781492057888/)** - *by: Adam Bellemare* - How to design and build event-driven systems at scale using streaming platforms.

> Full lists: [data/architecture.md](data/architecture.md) · [data/distributed-systems.md](data/distributed-systems.md) · [data/databases.md](data/databases.md)

### Databases

- **[The Art of PostgreSQL *(2nd Ed.)*](https://theartofpostgresql.com/)** - *by: Dimitri Fontaine* - Advanced SQL and PostgreSQL features through real application examples.
- **[PostgreSQL: Up and Running *(3rd Ed.)*](https://www.amazon.com/PostgreSQL-Running-Practical-Advanced-Database/dp/1491963417)** - *by: Regina Obe & Leo Hsu* - A friendly, practical introduction to PostgreSQL for application developers.
- **[MongoDB: The Definitive Guide *(3rd Ed.)*](https://www.amazon.com/MongoDB-Definitive-Powerful-Scalable-Storage/dp/1491954469)** - *by: Shannon Bradshaw et al.* - Comprehensive coverage of MongoDB for developers and operations.
- **[Redis in Action](https://www.manning.com/books/redis-in-action)** - *by: Josiah Carlson* - Data structures, patterns, and real use cases for Redis beyond simple caching.

> Full list: [data/databases.md](data/databases.md)

---

## System Design

> Essential reading for building production-grade systems — and for navigating technical interviews.

- **[System Design Interview – Vol. 1 *(2nd Ed.)*](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF)** - *by: Alex Xu* - The most practical intro to system design with clear frameworks and real examples.
- **[System Design Interview – Vol. 2](https://www.amazon.com/System-Design-Interview-Insiders-Guide/dp/1736049119)** - *by: Alex Xu & Sahn Lam* - Deeper dives: Google Maps, ad click aggregation, stock exchange, and distributed message queues.
- **[The System Design Primer](https://github.com/donnemartin/system-design-primer)** - *by: Donne Martin* - Free, comprehensive GitHub guide covering scalability, reliability, and trade-off thinking.

> Full list: [data/system-design.md](data/system-design.md)

---

## Computer Science Foundations

> These books don't expire. Invest in them once and they pay dividends forever.

- **[SICP](https://mitpress.mit.edu/9780262510875/structure-and-interpretation-of-computer-programs/)** - *by: Abelson, Sussman & Sussman* - Abstraction, interpreters, and "how to think like a programmer" at a deep level — free online.
- **[Introduction to Algorithms *(CLRS, 4th Ed.)*](https://mitpress.mit.edu/9780262046305/introduction-to-algorithms-fourth-edition/)** - *by: Cormen, Leiserson, Rivest, Stein* - The standard reference for algorithms and data structures.
- **[The Art of Computer Programming](https://www-cs-faculty.stanford.edu/~knuth/taocp.html)** - *by: Donald E. Knuth* - The deep end of algorithms, analysis, and programming elegance.
- **[Computer Systems: A Programmer's Perspective *(3rd Ed.)*](https://csapp.cs.cmu.edu/)** - *by: Bryant & O'Hallaron* - What's actually happening under your code: memory, caching, linking, concurrency.
- **[Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)** - *by: Arpaci-Dusseau & Arpaci-Dusseau* - OS fundamentals explained with unusual clarity — free online.
- **[Computer Networking: A Top-Down Approach *(8th Ed.)*](https://www.amazon.com/Computer-Networking-Top-Down-Approach-8th/dp/0136681557)** - *by: Kurose & Ross* - The standard networking text — TCP/IP, HTTP, DNS, and how the internet actually works.

> Full list: [data/computer-science.md](data/computer-science.md)

---

## Testing & Quality

- **[Test-Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)** - *by: Kent Beck* - TDD from the inventor of TDD — walks through the process step by step with real code.
- **[Growing Object-Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)** - *by: Freeman & Pryce* - The best book on TDD in practice, showing how tests shape real architecture.
- **[The Art of Unit Testing *(3rd Ed.)*](https://www.manning.com/books/the-art-of-unit-testing-third-edition)** - *by: Roy Osherove* - Practical patterns for writing tests that are maintainable and trustworthy.
- **[Software Engineering at Google](https://abseil.io/resources/swe-book)** - *by: Winters, Manshreck, Wright* - How Google thinks about testing, code review, maintainability, and scale — free online.

> Full list: [data/testing.md](data/testing.md)

---

## DevOps, CI/CD & Infrastructure

- **[The DevOps Handbook *(2nd Ed.)*](https://itrevolution.com/product/the-devops-handbook-second-edition/)** - *by: Kim, Humble, Debois, Willis, Forsgren* - The definitive guide to DevOps transformation: flow, feedback, and continuous learning.
- **[Accelerate](https://itrevolution.com/product/accelerate/)** - *by: Forsgren, Humble, Kim* - Data-driven proof of what actually makes software delivery faster and more reliable.
- **[Continuous Delivery](https://www.continuousdelivery.com/)** - *by: Humble & Farley* - The foundational book on CI/CD pipelines, deployment automation, and release confidence.
- **[Infrastructure as Code *(3rd Ed.)*](https://www.amazon.com/Infrastructure-Code-Dynamic-Systems-Cloud/dp/1098114671)** - *by: Kief Morris* - Principles and patterns for managing cloud and server infrastructure with code.
- **[Terraform: Up & Running *(3rd Ed.)*](https://www.terraformupandrunning.com/)** - *by: Yevgeniy Brikman* - Hands-on Terraform for real-world infrastructure automation.
- **[The Phoenix Project](https://itrevolution.com/product/the-phoenix-project/)** - *by: Kim, Behr, Spafford* - A novel that makes DevOps principles viscerally real — essential culture reading.

> Full list: [data/devops.md](data/devops.md)

---

## Security

- **[Serious Cryptography *(2nd Ed.)*](https://nostarch.com/seriouscrypto)** - *by: Jean-Philippe Aumasson* - Cryptography concepts explained for engineers who need to use it correctly.
- **[The Web Application Hacker's Handbook *(2nd Ed.)*](https://www.wiley.com/en-us/The+Web+Application+Hacker%27s+Handbook%3A+Finding+and+Exploiting+Security+Flaws%2C+2nd+Edition-p-9781118026472)** - *by: Stuttard & Pinto* - Practical web security testing and attack/defense thinking.
- **[Hacking: The Art of Exploitation *(2nd Ed.)*](https://nostarch.com/hacking2.htm)** - *by: Jon Erickson* - Low-level security from first principles: buffer overflows, shellcode, and network exploits.
- **[The Tangled Web](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886)** - *by: Michal Zalewski* - A deep and honest look at how browsers and the web work — and why security is hard.

> Full list: [data/security.md](data/security.md)

---

## Version Control

- **[Pro Git *(2nd Ed.)*](https://git-scm.com/book/en/v2)** - *by: Scott Chacon & Ben Straub* - The most readable Git book, from basics to power-user workflows — free online.
- **[Version Control with Git](https://www.oreilly.com/library/view/version-control-with/9781492091191/)** - *by: Jon Loeliger & Matthew McCullough* - Comprehensive Git reference and best practices, from commits to collaboration workflows.
- **[Learn Git in a Month of Lunches](https://www.manning.com/books/learn-git-in-a-month-of-lunches)** - *by: Rick Umali* - Bite-sized Git lessons for daily use, with practice-friendly examples.

> Full list: [data/version-control.md](data/version-control.md)

---

## Platforms

- **[Amazon Web Services in Action *(3rd Ed.)*](https://www.manning.com/books/amazon-web-services-in-action-third-edition)** - *by: Andreas Wittig & Michael Wittig* - A practical, end-to-end AWS guide with enough depth to build real systems confidently.
- **[Kubernetes: Up & Running *(3rd Ed.)*](https://www.amazon.com/Kubernetes-Running-Dive-Future-Infrastructure/dp/109811020X)** - *by: Hightower, Burns, Beda* - The clearest mental model for modern cloud-native infrastructure and orchestration.
- **[UNIX and Linux System Administration Handbook *(5th Ed.)*](https://www.oreilly.com/library/view/unix-and-linux/9780134278308/)** - *by: Evi Nemeth et al.* - The classic reference for operating real Linux/Unix systems in production.

> Full lists: [data/aws.md](data/aws.md) · [data/azure.md](data/azure.md) · [data/google-cloud.md](data/google-cloud.md) · [data/kubernetes.md](data/kubernetes.md) · [data/docker.md](data/docker.md) · [data/linux.md](data/linux.md) · [data/ios.md](data/ios.md) · [data/android.md](data/android.md)

---

## Major Frameworks

- **[Learning React *(2nd Ed.)*](https://www.oreilly.com/library/view/learning-react-2nd/9781492051718/)** - *by: Alex Banks & Eve Porcello* - A clean introduction to modern React (hooks + functional components) with practical patterns.
- **[Django for Professionals](https://www.amazon.com/Django-Professionals-Production-websites-Python/dp/1955390038)** - *by: William S. Vincent* - Teaches the “production mindset” for Django: security, deployment, and maintainability.
- **[Spring in Action *(6th Ed.)*](https://www.manning.com/books/spring-in-action-sixth-edition)** - *by: Craig Walls* - The most practical guide to the Spring ecosystem used in real Java backends.

> Full lists: [data/laravel.md](data/laravel.md) · [data/rails.md](data/rails.md) · [data/django.md](data/django.md) · [data/spring.md](data/spring.md) · [data/aspnet-core.md](data/aspnet-core.md) · [data/react.md](data/react.md) · [data/vue.md](data/vue.md) · [data/angular.md](data/angular.md) · [data/nodejs.md](data/nodejs.md) · [data/flutter.md](data/flutter.md)

---

## Automation

- **[Ansible for DevOps](https://www.ansiblefordevops.com/)** - *by: Jeff Geerling* - A hands-on path to infrastructure automation that works in real environments.
- **[Grokking Continuous Delivery](https://www.manning.com/books/grokking-continuous-delivery)** - *by: Christie Wilson* - A modern, practical guide to designing CD systems that keep software releasable.
- **[Automating the Boring Stuff with Python](https://automatetheboringstuff.com/)** - *by: Al Sweigart* - The fastest way to start automating repetitive tasks with scripts — free online.

> Full list: [data/automation.md](data/automation.md)

---

## Monitoring & Observability

- **[Site Reliability Engineering](https://sre.google/books/)** - *by: Beyer, Jones, Petoff, Murphy* - The core SRE playbook: SLOs, toil reduction, and operating services at scale — free online.
- **[Cloud Observability in Action](https://www.manning.com/books/cloud-observability-in-action)** - *by: Michael Hausenblas* - Modern observability end-to-end (logs/metrics/traces) with practical tooling examples.
- **[Prometheus: Up & Running](https://www.oreilly.com/library/view/prometheus-up/9781492034131/)** - *by: Brian Brazil* - The essential reference for metrics-first monitoring with Prometheus.

> Full list: [data/monitoring.md](data/monitoring.md)

---

## APIs

- **[API Design Patterns](https://www.manning.com/books/api-design-patterns)** - *by: JJ Geewax* - Practical patterns for building reliable APIs across REST, gRPC, and GraphQL.
- **[Designing Web APIs](https://www.oreilly.com/library/view/designing-web-apis/9781492026914/)** - *by: Brenda Jin et al.* - A pragmatic guide to building APIs developers love, with real-world design trade-offs.
- **[Automating API Delivery](https://www.oreilly.com/library/view/automating-api-delivery/9781633438781/)** - *by: Ikenna Nwaiwu* - APIOps: reviews, automation, OpenAPI, and governance that scales with teams.

> Full list: [data/apis.md](data/apis.md)

---

## Cloud

- **[Designing Data-Intensive Applications](https://dataintensive.net/)** - *by: Martin Kleppmann* - The best single book for thinking clearly about distributed and cloud-scale trade-offs.
- **[Infrastructure as Code *(3rd Ed.)*](https://www.amazon.com/Infrastructure-Code-Dynamic-Systems-Cloud/dp/1098114671)** - *by: Kief Morris* - Patterns for building and maintaining cloud infrastructure safely with code.
- **[Which Cloud?](https://www.wiley.com/en-us/Which+Cloud%3A+A+Developer%27s+and+Architect%27s+Guide+to+Comparing+AWS%2C+Microsoft+Azure%2C+and+Google+Cloud-p-9781119760115)** - *by: Vishal Agrawal* - A practical comparison of AWS/Azure/GCP to help you choose and map services.

> Full list: [data/cloud.md](data/cloud.md)

---

## Programming Languages

### Python

Python has one of the richest programming book ecosystems of any language, and for good reason — it spans beginners writing their first script all the way to engineers building distributed ML systems. The books below are the best of that spectrum: *Python by Example* and *Python Crash Course* get you coding confidently from day one, *Fluent Python* and *Effective Python* make you truly fluent in the language's idioms and internals, and *Architecture Patterns with Python* and *High Performance Python* take you into production-grade territory. Together they form a complete path from first line to senior engineer.

- **[Python by Example](https://github.com/pycollege/python-by-example)** - *by: Dariush Abbasi* - A practical, example-driven guide to learning Python — clear explanations and real coding tasks, great for building intuition fast.
- **[Python Crash Course *(3rd Ed.)*](https://nostarch.com/python-crash-course-3rd-edition)** - *by: Eric Matthes* - Best beginner book — projects-first, clear, and up to date with Python 3.11+.
- **[Fluent Python *(2nd Ed.)*](https://www.fluentpython.com/about/)** - *by: Luciano Ramalho* - Idiomatic Python: data model, iterators, concurrency, typing, and best practices.
- **[Effective Python *(3rd Ed.)*](https://effectivepython.com/)** - *by: Brett Slatkin* - Sharp, practical items for writing clean, correct, modern Python.
- **[Architecture Patterns with Python](https://www.cosmicpython.com/)** - *by: Percival & Gregory* - DDD, ports & adapters, and event-driven architecture in Python — free online.
- **[High Performance Python *(2nd Ed.)*](https://www.amazon.com/High-Performance-Python-Performant-Programming/dp/1492055026)** - *by: Gorelick & Ozsvald* - Profiling, optimization, concurrency, and making Python fast when it needs to be.

> Full list: [data/python.md](data/python.md)

---

### JavaScript / TypeScript

JavaScript is the only language that runs natively in every browser on the planet, and that ubiquity has spawned a remarkably deep body of literature. The challenge isn't finding a JS book — it's finding ones that teach the language honestly rather than glossing over its genuinely strange parts. The books here do exactly that: *Eloquent JavaScript* builds real understanding from the ground up, *You Don't Know JS Yet* goes deep on the mechanics most developers never fully grasp, and *Programming TypeScript* gives you the type-level tools to scale JavaScript into large, reliable codebases. Pair any two of these and you'll understand JavaScript better than most working professionals.

- **[Eloquent JavaScript *(4th Ed.)*](https://eloquentjavascript.net/)** - *by: Marijn Haverbeke* - Best "learn JS by understanding it" book — updated for modern JS, free online.
- **[You Don't Know JS Yet *(2nd Ed.)*](https://github.com/getify/You-Dont-Know-JS)** - *by: Kyle Simpson* - Deep dive into JS mechanics: scope, closures, prototypes, types, and async — free online.
- **[JavaScript: The Good Parts](https://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742)** - *by: Douglas Crockford* - Slim, sharp, still essential for understanding the language's quirks and pitfalls.
- **[Programming TypeScript](https://www.amazon.com/Programming-TypeScript-Making-JavaScript-Applications/dp/1492037656)** - *by: Boris Cherny* - How to scale JS codebases with TypeScript's type system and patterns.
- **[Node.js Design Patterns *(3rd Ed.)*](https://www.nodejsdesignpatterns.com/)** - *by: Casciaro & Mammino* - Patterns, best practices, and idioms for serious server-side Node.js development.

> Full lists: [data/javascript.md](data/javascript.md) · [data/typescript.md](data/typescript.md)

---

### Java

Java's longevity — over 30 years and still powering much of the world's enterprise infrastructure — has produced a small canon of genuinely great books that have stood the test of time. *Effective Java* is the consensus best book on any object-oriented language, not just Java. *Java Concurrency in Practice* remains unmatched for writing safe concurrent code, even as the language has evolved. *Modern Java in Action* bridges the gap to Java 17+ idioms, and *Spring in Action* covers the framework that most production Java systems actually run on. Read them in order and you'll write Java that senior engineers respect.

- **[Effective Java *(3rd Ed.)*](https://www.informit.com/store/effective-java-9780134685991)** - *by: Joshua Bloch* - The definitive guide to writing robust, idiomatic Java.
- **[Java Concurrency in Practice](https://jcip.net/)** - *by: Brian Goetz et al.* - The classic on writing safe and scalable concurrent Java code — still unsurpassed.
- **[Modern Java in Action *(2nd Ed.)*](https://www.manning.com/books/modern-java-in-action-second-edition)** - *by: Urma, Fusco, Mycroft* - Lambdas, streams, modules, reactive, and records — the Java 17+ way to write code.
- **[Spring in Action *(6th Ed.)*](https://www.manning.com/books/spring-in-action-sixth-edition)** - *by: Craig Walls* - The definitive practical guide to the Spring ecosystem.

> Full list: [data/java.md](data/java.md)

---

### Go

Go's philosophy is deliberate simplicity — small language, fast compiler, opinionated tooling — and its best books reflect that ethos. The Donovan & Kernighan classic covers the language thoroughly and remains the clearest introduction to Go's concurrency model. *Learning Go* brings it up to modern idioms for developers arriving from Python or JavaScript. *100 Go Mistakes* is the most efficient way to level up after the basics: a clear catalog of the patterns that trip up even experienced Go developers. These three books together are all you need to write professional, idiomatic Go.

- **[Boring Go!](https://golang.college/books/boring-go)** - *by: Hassan Aminfar* - If you’ve ever felt that Go’s simplicity is a feature—not a limitation—Boring Go! puts words, examples, and confidence behind that instinct.
- **[The Go Programming Language](https://www.gopl.io/)** - *by: Donovan & Kernighan* - Clear, thorough coverage of Go from core language to concurrency.
- **[Learning Go *(2nd Ed.)*](https://www.oreilly.com/library/view/learning-go-2nd/9781098139285/)** - *by: Jon Bodner* - Modern, idiomatic Go for developers coming from other languages — updated for Go 1.21+.
- **[100 Go Mistakes and How to Avoid Them](https://100go.co/)** - *by: Teiva Harsanyi* - A catalog of real Go pitfalls with clear explanations and fixes.
- **[Powerful Command-Line Applications in Go](https://pragprog.com/titles/rggo/powerful-command-line-applications-in-go/)** - *by: Ricardo Gerardi* - Build real CLI tools in Go — great for systems and DevOps developers.

> Full list: [data/go.md](data/go.md)

---

### Rust

Rust's ownership model is genuinely unlike anything in other mainstream languages, which means most developers need to unlearn before they can learn. The books below are carefully sequenced for that journey. *The Rust Programming Language* (universally called "the book") is one of the best official language guides ever written — free, clear, and comprehensive. *Programming Rust* goes deeper for real systems work, and *Rust for Rustaceans* takes you into advanced territory once the fundamentals click. *Zero to Production* is the practical capstone: building a real production API end-to-end, where all the theory becomes concrete.

- **[The Rust Programming Language *(2nd Ed.)*](https://doc.rust-lang.org/book/)** - *by: Klabnik, Nichols & contributors* - The best first-principles introduction to Rust — free online.
- **[Programming Rust *(2nd Ed.)*](https://www.amazon.com/Programming-Rust-Fast-Systems-Development/dp/1492052590)** - *by: Blandy, Orendorff, Tindall* - Practical, detailed Rust for real systems work.
- **[Rust for Rustaceans](https://nostarch.com/rust-rustaceans)** - *by: Jon Gjengset* - Idiomatic Rust for developers ready to go beyond the basics.
- **[Zero to Production in Rust](https://www.zero2prod.com/)** - *by: Luca Palmieri* - Build a production-ready backend API from scratch — the best "real project" Rust book.

> Full list: [data/rust.md](data/rust.md)

---

### C / C++

C and C++ sit at the foundation of almost everything in computing — operating systems, compilers, databases, game engines, embedded systems — and their best books reflect that depth and weight. K&R's *The C Programming Language* is one of the finest technical books ever written: 272 pages that explain more than most 800-page volumes. For C++, Scott Meyers' *Effective Modern C++* remains the clearest guide to writing safe, performant code with the modern language features, and Stroustrup's *Tour of C++* gives you an authoritative overview of the whole language in compact form. These aren't weekend reads — they're references you'll return to for years.

- **[The C Programming Language *(2nd Ed.)*](https://en.wikipedia.org/wiki/The_C_Programming_Language)** - *by: Kernighan & Ritchie* - The classic C text — short, sharp, and foundational.
- **[Effective Modern C++](https://www.amazon.com/Effective-Modern-Specific-Ways-Improve/dp/1491903996)** - *by: Scott Meyers* - Best practices for C++11/14 and "how to stop hurting yourself."
- **[C++ Primer *(5th Ed.)*](https://www.amazon.com/C-Primer-5th-Stanley-Lippman/dp/0321714113)** - *by: Lippman, Lajoie, Moo* - A thorough, structured path through modern C++.
- **[A Tour of C++ *(3rd Ed.)*](https://www.amazon.com/Tour-C-Bjarne-Stroustrup/dp/0136816487)** - *by: Bjarne Stroustrup* - A concise, expert overview of modern C++ from the creator of the language.

> Full lists: [data/c.md](data/c.md) · [data/cpp.md](data/cpp.md)

---

### C#

C# has evolved faster than almost any other mainstream language over the past decade — nullable reference types, records, pattern matching, async/await, source generators — and its literature has kept pace. Jon Skeet's *C# in Depth* is the gold standard for understanding *why* the language works the way it does, not just *how* to use it. Stephen Cleary's concurrency cookbook is the most practical guide to async programming patterns that C# developers face daily. Together with a current reference like Mark Price's comprehensive guide to .NET 8+, these three books cover C# from its design principles through modern production patterns.

- **[C# in Depth *(4th Ed.)*](https://csharpindepth.com/)** - *by: Jon Skeet* - The book for understanding the *why* behind C# features — not just syntax.
- **[Concurrency in C# Cookbook *(2nd Ed.)*](https://www.amazon.com/Concurrency-Cookbook-Asynchronous-Multithreaded-Programming/dp/149205450X)** - *by: Stephen Cleary* - Practical patterns for async, parallel, and reactive C# code.
- **[C# 12 and .NET 8](https://www.amazon.com/12-NET-Modern-Cross-Platform-Development/dp/1837635870)** - *by: Mark J. Price* - Comprehensive, up-to-date coverage of modern C# and the .NET ecosystem.

> Full list: [data/csharp.md](data/csharp.md)

---

### Kotlin

Kotlin has become the dominant language for Android development and a serious contender on the JVM server side, offering a modern, expressive alternative to Java with full interoperability. Its book ecosystem is compact but high quality. *Kotlin in Action* — written by two JetBrains engineers who designed the language — is the authoritative starting point, covering the language idioms and patterns you'll actually use. *Effective Kotlin* is the natural follow-up: a distillation of what writing production Kotlin well actually looks like, item by item. Two books; more than enough to be confident in the language.

- **[Kotlin in Action *(2nd Ed.)*](https://www.manning.com/books/kotlin-in-action-second-edition)** - *by: Jemerov & Isakova* - Practical Kotlin with the patterns you'll actually use on real projects.
- **[Effective Kotlin *(2nd Ed.)*](https://kt.academy/book/effectivekotlin)** - *by: Marcin Moskala* - Best practices and idioms for writing clean, safe, maintainable Kotlin.
- **[Kotlin Programming: The Big Nerd Ranch Guide *(2nd Ed.)*](https://www.oreilly.com/library/view/kotlin-programming-the/9780136870494/)** - *by: David Greenhalgh & Josh Skeen* - A hands-on, example-driven path that helps Kotlin “click” quickly.

> Full list: [data/kotlin.md](data/kotlin.md)

---

### Swift

Swift is Apple's language for the entire Apple platform — iOS, macOS, watchOS, tvOS — and since its introduction in 2014 it has matured into a genuinely elegant, safe, and performant language. The official Swift book from Apple is unusually good for official documentation: clear, current, and always kept up to date with new language releases. *Swift in Depth* goes further, covering generics, protocol-oriented design, and the advanced patterns that distinguish fluent Swift from translated Objective-C. The Big Nerd Ranch iOS guide rounds it out with the best hands-on project-based learning for building real apps.

- **[The Swift Programming Language](https://docs.swift.org/swift-book/)** - *by: Apple* - The official, free, and continuously updated guide to Swift — always current.
- **[Swift in Depth](https://www.manning.com/books/swift-in-depth)** - *by: Tjeerd in 't Veen* - Goes beyond syntax to cover generics, protocols, and idiomatic Swift patterns.
- **[iOS Programming: The Big Nerd Ranch Guide *(7th Ed.)*](https://www.bignerdranch.com/books/ios-programming-the-big-nerd-ranch-guide-seventh-edition/)** - *by: Keur & Hillegass* - The most practical hands-on guide to building real iOS apps.

> Full list: [data/swift.md](data/swift.md)

---

### Ruby

Ruby is a language designed above all for developer happiness — expressive, flexible, and famously elegant — and its best books capture that spirit while building serious engineering depth. Sandi Metz's *Practical Object-Oriented Design* is required reading regardless of which language you work in: it uses Ruby to teach OOP more clearly than any other book in any language. *The Well-Grounded Rubyist* is where you go to truly understand how Ruby works under the hood — objects, blocks, closures, and the metaprogramming that makes Rails possible. The Pickaxe (*Programming Ruby 3.2*) is the definitive reference once you need to go deeper.

- **[The Well-Grounded Rubyist *(3rd Ed.)*](https://www.manning.com/books/the-well-grounded-rubyist-third-edition)** - *by: Black & Leo III* - The best "understand Ruby deeply" book — objects, blocks, modules, and metaprogramming.
- **[Practical Object-Oriented Design *(2nd Ed.)*](https://www.poodr.com/)** - *by: Sandi Metz* - Uses Ruby to teach OOP clearly — one of the best object-oriented design books for any language.
- **[Programming Ruby 3.2 *(5th Ed.)*](https://pragprog.com/titles/ruby5/programming-ruby-3-2-5th-edition/)** - *by: Thomas, Fowler, Hunt* - The definitive Ruby reference — "the Pickaxe."

> Full list: [data/ruby.md](data/ruby.md)

---

### Elixir

Elixir sits on top of the Erlang VM — one of the most battle-tested runtimes for fault-tolerant, distributed systems ever built — and brings a modern, Ruby-influenced syntax to that proven foundation. It's the best language available for building systems that must stay up, handle concurrency gracefully, and recover from failure automatically. Dave Thomas' *Programming Elixir* is the joyful introduction the language deserves. Saša Jurić's *Elixir in Action* takes you into OTP, processes, and real production architecture. And *Programming Phoenix* shows how it all comes together in web applications with real-time features that would be painful to build anywhere else.

- **[Programming Elixir 1.6](https://pragprog.com/titles/elixir16/programming-elixir-1-6/)** - *by: Dave Thomas* - The best starting point for Elixir's functional and concurrent programming model.
- **[Elixir in Action *(3rd Ed.)*](https://www.manning.com/books/elixir-in-action-third-edition)** - *by: Saša Jurić* - Production-grade Elixir: OTP, concurrency, and building real fault-tolerant systems.
- **[Programming Phoenix 1.4](https://pragprog.com/titles/phoenix14/programming-phoenix-1-4/)** - *by: McCord, Tate, Valim* - Building real-time web apps with Phoenix and LiveView — collaborative app development at its best.

> Full list: [data/elixir.md](data/elixir.md)

---

### Scala

Scala is the most ambitious language on the JVM: it fuses object-oriented and functional programming into a single, expressive type system, and it runs on the Java runtime with full interoperability. That ambition makes it powerful and also genuinely demanding to learn well. *Programming in Scala* — co-authored by the language's creator, Martin Odersky — is the authoritative guide and the right place to start. *Functional Programming in Scala* is one of the finest FP books ever written in any language: rigorous, demanding, and transformative for how you think about code. The *Scala Cookbook* fills in the practical day-to-day gaps that the theory books leave open.

- **[Programming in Scala *(5th Ed.)*](https://www.artima.com/shop/programming_in_scala_5ed)** - *by: Odersky, Spoon, Venners* - The authoritative Scala guide, co-authored by the language creator.
- **[Functional Programming in Scala *(2nd Ed.)*](https://www.manning.com/books/functional-programming-in-scala-second-edition)** - *by: Chiusano & Bjarnason* - Learn FP rigorously from the ground up using Scala — demanding but transformative.
- **[Scala Cookbook *(2nd Ed.)*](https://www.amazon.com/Scala-Cookbook-Object-Oriented-Functional-Programming/dp/1492051543)** - *by: Alvin Alexander* - Practical, recipe-driven solutions for everyday Scala development.

> Full list: [data/scala.md](data/scala.md)

---

### PHP

PHP powers a remarkable share of the web — WordPress, Wikipedia, Facebook's original stack — and despite its reputation, modern PHP is a genuinely capable, well-designed language. The challenge is that there is a vast amount of outdated PHP code and outdated PHP advice floating around the internet, making good books especially valuable here. Josh Lockhart's *Modern PHP* is the essential reset: it shows what PHP actually looks like written well in 2026 with modern tooling. Matt Zandstra's *PHP Objects, Patterns and Practice* builds the object-oriented and design-pattern foundation that serious PHP work requires. *Laravel: Up & Running* covers the framework that defines professional PHP web development today.

- **[Modern PHP](https://www.amazon.com/Modern-PHP-Features-Good-Practices/dp/1491905018)** - *by: Josh Lockhart* - Brings PHP into the modern era: namespaces, traits, generators, Composer, and best practices.
- **[PHP Objects, Patterns and Practice *(6th Ed.)*](https://www.amazon.com/PHP-Objects-Patterns-Practice-Enhancements/dp/1484267907)** - *by: Matt Zandstra* - OOP, design patterns, and professional PHP workflows.
- **[Laravel: Up & Running *(3rd Ed.)*](https://www.amazon.com/Laravel-Running-Framework-Building-Modern/dp/1098141806)** - *by: Matt Stauffer* - The definitive practical guide to building modern applications with Laravel.

> Full list: [data/php.md](data/php.md)

---

### Functional Programming

Functional programming is less a language and more a way of thinking — one that makes programs easier to reason about, test, and compose. These books are language-agnostic in spirit even when they use a specific language as their vehicle. Haskell is the natural home for pure FP learning because it enforces the discipline that other languages only encourage, and *Learn You a Haskell* is the most enjoyable entry point the language has. *Category Theory for Programmers* goes deeper into the mathematical structures that underlie all of functional programming. Scott Wlaschin's *Domain Modeling Made Functional* is the sleeper hit of the list: it applies FP and DDD to real business problems in F# with unusual clarity, and its lessons transfer to any language.

- **[Learn You a Haskell for Great Good!](http://learnyouahaskell.com/)** - *by: Miran Lipovača* - The most fun intro to Haskell and pure functional thinking — free online.
- **[Haskell Programming from First Principles](https://haskellbook.com/)** - *by: Allen & Moronuki* - A rigorous, beginner-friendly path through Haskell and type theory.
- **[Haskell for Imperative Programmers](https://leanpub.com/haskell-for-imperative-programmers)** - *by: Philipp Hagenlocher (2024)* - Written specifically for developers arriving from OOP/imperative backgrounds — practical and grounded.
- **[Category Theory for Programmers](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/)** - *by: Bartosz Milewski* - The mathematical foundations underlying functional programming — free online.
- **[Domain Modeling Made Functional](https://pragprog.com/titles/swdddf/domain-modeling-made-functional/)** - *by: Scott Wlaschin* - DDD and functional design in F# — invaluable even if you never write F#.

> Full list: [data/functional-programming.md](data/functional-programming.md)

---

### Shell & Command Line

The command line is the universal interface of software development — every language, every platform, every server. Developers who are fluent at the shell move faster, debug more effectively, and automate repetitive work that slows everyone else down. *The Linux Command Line* is the best starting point: methodical, clear, and free online. Once you're comfortable there, *sed & awk* opens up serious text processing power, and *Classic Shell Scripting* covers the portability and reliability patterns that distinguish production scripts from quick hacks. These aren't glamorous books — but they pay dividends every single day.

- **[The Linux Command Line *(2nd Ed.)*](https://linuxcommand.org/tlcl.php)** - *by: William Shotts* - The best introduction to Bash and the Unix philosophy — free online.
- **[sed & awk *(2nd Ed.)*](https://www.amazon.com/sed-awk-Dale-Dougherty/dp/1565922255)** - *by: Dougherty & Robbins* - Deep mastery of the two most essential Unix text-processing tools.
- **[Classic Shell Scripting](https://www.amazon.com/Classic-Shell-Scripting-Arnold-Robbins/dp/0596005954)** - *by: Robbins & Beebe* - Real-world shell scripting patterns for portability and reliability.

> Full list: [data/shell-command-line.md](data/shell-command-line.md)

---

### More Languages (Full Lists Only)

In addition to the languages highlighted above, the `data/` directory includes focused book lists for many more languages and ecosystems:

- **Ada** – full list: [data/ada.md](data/ada.md)
- **Assembly** – full list: [data/assembly.md](data/assembly.md)
- **Clojure** – full list: [data/clojure.md](data/clojure.md)
- **COBOL** – full list: [data/cobol.md](data/cobol.md)
- **Dart** – full list: [data/dart.md](data/dart.md)
- **Erlang** – full list: [data/erlang.md](data/erlang.md)
- **Fortran** – full list: [data/fortran.md](data/fortran.md)
- **F#** – full list: [data/fsharp.md](data/fsharp.md)
- **Groovy** – full list: [data/groovy.md](data/groovy.md)
- **Haskell** – full list: [data/haskell.md](data/haskell.md)
- **Julia** – full list: [data/julia.md](data/julia.md)
- **Lisp** – full list: [data/lisp.md](data/lisp.md)
- **Lua** – full list: [data/lua.md](data/lua.md)
- **Nim** – full list: [data/nim.md](data/nim.md)
- **Objective-C** – full list: [data/objective-c.md](data/objective-c.md)
- **OCaml** – full list: [data/ocaml.md](data/ocaml.md)
- **Pascal** – full list: [data/pascal.md](data/pascal.md)
- **Perl** – full list: [data/perl.md](data/perl.md)
- **PowerShell** – full list: [data/powershell.md](data/powershell.md)
- **Prolog** – full list: [data/prolog.md](data/prolog.md)
- **R** – full list: [data/r.md](data/r.md)
- **Scheme** – full list: [data/scheme.md](data/scheme.md)
- **Shell (scripting)** – full list: [data/shell.md](data/shell.md)
- **Solidity** – full list: [data/solidity.md](data/solidity.md)
- **SQL** – full list: [data/sql.md](data/sql.md)
- **Zig** – full list: [data/zig.md](data/zig.md)

## Frontend & Web Development

- **[CSS: The Definitive Guide *(5th Ed.)*](https://www.oreilly.com/library/view/css-the-definitive/9781098117603/)** - *by: Meyer & Weyl* - The most comprehensive and current CSS reference — covers Grid, Flexbox, and custom properties.
- **[Every Layout](https://every-layout.dev/)** - *by: Pickering & Bell* - Reframes CSS layout as composable, algorithmic design primitives — changes how you think about CSS.
- **[HTTP: The Definitive Guide](https://www.amazon.com/HTTP-Definitive-Guide-Guides/dp/1565925092)** - *by: Gourley et al.* - Deep understanding of HTTP — essential for every web developer.
- **[Web Performance in Action](https://www.manning.com/books/web-performance-in-action)** - *by: Jeremy Wagner* - Practical techniques for making real-world websites significantly faster.
- **[Web Scalability for Startup Engineers](https://www.amazon.com/Scalability-Startup-Engineers-Artur-Ejsmont/dp/0071843655)** - *by: Artur Ejsmont* - Pragmatic guide to scaling web architecture from day one through millions of users.

> Full list: [data/frontend.md](data/frontend.md)

---

## Mobile Development

- **[iOS Programming: The Big Nerd Ranch Guide *(7th Ed.)*](https://www.bignerdranch.com/books/ios-programming-the-big-nerd-ranch-guide-seventh-edition/)** - *by: Keur & Hillegass* - The most practical hands-on guide to building real iOS apps with Swift and UIKit.
- **[SwiftUI by Tutorials *(5th Ed.)*](https://www.kodeco.com/books/swiftui-by-tutorials)** - *by: Kodeco Team* - Project-driven SwiftUI development covering the full modern iOS stack.
- **[Android Programming: The Big Nerd Ranch Guide *(5th Ed.)*](https://www.bignerdranch.com/books/android-programming-the-big-nerd-ranch-guide-5th-edition/)** - *by: Phillips, Stewart, Hardy* - The definitive hands-on guide to Android development in Kotlin.
- **[Jetpack Compose by Tutorials *(2nd Ed.)*](https://www.kodeco.com/books/jetpack-compose-by-tutorials)** - *by: Kodeco Team* - Project-based guide to building modern Android UIs with Jetpack Compose.
- **[Flutter in Action](https://www.manning.com/books/flutter-in-action)** - *by: Eric Windmill* - Cross-platform mobile development with Flutter and Dart — one codebase for iOS and Android.

> Full list: [data/mobile.md](data/mobile.md)

---

## Data Engineering

- **[Fundamentals of Data Engineering](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/)** - *by: Reis & Housley* - The first comprehensive book on the data engineering lifecycle — pipelines, storage, and serving.
- **[Streaming Systems](https://www.oreilly.com/library/view/streaming-systems/9781491983867/)** - *by: Akidau, Chernyak, Lax* - How streaming works at a deep level — windows, watermarks, and exactly-once semantics.
- **[Data Pipelines with Apache Airflow](https://www.manning.com/books/data-pipelines-with-apache-airflow)** - *by: Harenslak & de Ruiter* - Practical Airflow for orchestrating real-world data workflows.
- **[The Data Warehouse Toolkit *(3rd Ed.)*](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802)** - *by: Kimball & Ross* - The foundational guide to dimensional modeling — bedrock of analytical data design.
- **[Spark: The Definitive Guide](https://www.oreilly.com/library/view/spark-the-definitive/9781491912201/)** - *by: Chambers & Zaharia* - Comprehensive guide to Apache Spark for large-scale data processing.

> Full list: [data/data-engineering.md](data/data-engineering.md)

---

## AI / Machine Learning

### Big-Picture AI & Fundamentals

- **[Artificial Intelligence: A Modern Approach *(4th Ed.)*](https://aima.cs.berkeley.edu/)** - *by: Russell & Norvig* - The classic survey of AI: agents, search, logic, probability, and learning.
- **[Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)** - *by: Christopher M. Bishop* - Core probabilistic ML foundations with a Bayesian viewpoint — free online.
- **[The Elements of Statistical Learning *(ESL, 2nd Ed.)*](https://hastie.su.domains/ElemStatLearn/)** - *by: Hastie, Tibshirani, Friedman* - Deep statistical learning theory — a reference you'll keep returning to — free online.
- **[An Introduction to Statistical Learning *(ISLR, 2nd Ed.)*](https://www.statlearning.com/)** - *by: James, Witten, Hastie, Tibshirani, Taylor* - Friendlier, applied companion to ESL — the best first stats-ML book — free online.
- **[Mathematics for Machine Learning](https://mml-book.github.io/)** - *by: Deisenroth, Faisal, Ong* - Linear algebra, calculus, and probability as actually used in ML — free online.

> Full list: [data/ai-fundamentals.md](data/ai-fundamentals.md)

---

### Deep Learning & Modern Practice

- **[Deep Learning](https://www.deeplearningbook.org/)** - *by: Goodfellow, Bengio, Courville* - The deep learning reference text — free online.
- **[Hands-On Machine Learning *(3rd Ed.)*](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1098125975)** - *by: Aurélien Géron* - Practical ML with end-to-end projects using modern Python tooling — updated for TF2/Keras 3.
- **[Deep Learning with Python *(2nd Ed.)*](https://deeplearningwithpython.io/)** - *by: François Chollet* - Intuitive deep learning from the Keras creator — partially free online.
- **[Natural Language Processing with Transformers *(Revised Ed.)*](https://transformersbook.com/)** - *by: Tunstall, von Werra, Wolf* - Modern NLP and transformer workflows with Hugging Face and hands-on examples.
- **[Reinforcement Learning: An Introduction *(2nd Ed.)*](http://incompleteideas.net/book/the-book-2nd.html)** - *by: Sutton & Barto* - The RL classic, from bandits to policy gradients — free online.
- **[Generative Deep Learning *(2nd Ed.)*](https://www.oreilly.com/library/view/generative-deep-learning/9781098134174/)** - *by: David Foster* - Practical generative modeling: VAEs, GANs, diffusion, and transformers.

> Full list: [data/deep-learning.md](data/deep-learning.md)

---

### AI Engineering, LLMs & Agents

> ⚡ The fastest-moving section of the list. These books reflect how AI is actually being built in production in 2025–2026.

- **[AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/)** - *by: Chip Huyen (2025)* - The definitive guide to building production AI systems with LLMs — foundation models, RAG, fine-tuning, agents, and evals. Start here.
- **[Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch)** - *by: Sebastian Raschka (2024)* - Builds a GPT-style LLM step by step in PyTorch — the best way to truly understand what's inside any model.
- **[The LLM Engineering Handbook](https://www.amazon.com/LLM-Engineering-Handbook-production-ready-applications/dp/1836200072)** - *by: Iusztin & Labonne (2024)* - End-to-end guide for shipping LLM applications: RAG, vector search, prompt chaining, fine-tuning, evals, and LLMOps.
- **[Prompt Engineering for LLMs](https://www.oreilly.com/library/view/prompt-engineering-for/9781098156145/)** - *by: Berryman & Ziegler (2024)* - Systematic prompt engineering from two core GitHub Copilot engineers — treats prompts as first-class engineering artifacts.
- **[Designing Multi-Agent Systems](https://www.oreilly.com/library/view/designing-multi-agent-systems/9781098164744/)** - *by: Victor Dibia (2025)* - Framework-agnostic guide to building reliable AI agent systems: orchestration patterns, memory, evaluation, and failure modes.
- **[Generative AI Design Patterns](https://www.oreilly.com/library/view/generative-ai-design/9781098165567/)** - *by: Cihan Biyikoglu (2025)* - 32 reusable patterns for RAG, reasoning chains, multi-modal systems, and agentic architectures.

> Full list: [data/ai-engineering.md](data/ai-engineering.md)

---

### ML Systems & MLOps

- **[Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107963/)** - *by: Chip Huyen* - End-to-end ML system design: data, training, deployment, monitoring, and iteration.
- **[Introducing MLOps](https://www.oreilly.com/library/view/introducing-mlops/9781492083283/)** - *by: Treveil, Sharif & Meissner* - Practical MLOps: model versioning, drift detection, and CI/CD for ML pipelines.
- **[Feature Engineering for Machine Learning](https://www.oreilly.com/library/view/feature-engineering-for/9781491953235/)** - *by: Alice Zheng & Amanda Casari* - How to transform raw data into features that actually improve model performance.

> Full list: [data/mlops.md](data/mlops.md)

---

## Career, Communication & Engineering Culture

- **[The Staff Engineer's Path](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/)** - *by: Tanya Reilly* - How to grow as a technical leader without becoming a manager — highly practical.
- **[Staff Engineer](https://staffeng.com/book)** - *by: Will Larson* - Real stories and frameworks from engineers who made it to Staff and beyond.
- **[The Manager's Path](https://www.oreilly.com/library/view/the-managers-path/9781491973882/)** - *by: Camille Fournier* - A technical leader's guide from tech lead to CTO — worth reading even if you never want to manage.
- **[An Elegant Puzzle](https://lethain.com/elegant-puzzle/)** - *by: Will Larson* - Engineering management systems: team design, hiring, incident management, strategy.
- **[Peopleware *(3rd Ed.)*](https://www.amazon.com/Peopleware-Productive-Projects-Teams-3rd/dp/0321934113)** - *by: DeMarco & Lister* - The argument that most software failures are social, not technical — still disturbingly accurate.
- **[The Clean Coder](https://www.amazon.com/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)** - *by: Robert C. Martin* - Professionalism, estimates, pressure, and how to behave when things go wrong.
- **[Software Engineering at Google](https://abseil.io/resources/swe-book)** - *by: Winters, Manshreck, Wright* - How Google thinks about maintainability, testing, and operating at scale — free online.
- **[Thinking in Systems](https://www.chelseagreen.com/product/thinking-in-systems/)** - *by: Donella Meadows* - Systems thinking fundamentals — applies to codebases, teams, and organizations alike.

> Full list: [data/career.md](data/career.md)

---

## Further Reading

Curated book lists that go deeper on specific topics:

- **[AI Books](https://github.com/mahseema/aibooks)** - Broad coverage of AI, ML, and deep learning books and resources.
- **[GoBooks](https://github.com/dariubs/gobooks)** - Large, curated collection of Go books, tutorials, and learning resources.
- **[JavaScript Books](https://github.com/minouou/jsbooks)** - Books and learning resources for JavaScript.
- **[PostgreSQL Books](https://github.com/sara8086/PostgresBooks)** - Books and guides for PostgreSQL.
- **[Python Books](https://github.com/lara-west/PythonBooks)** - Python books, tutorials, and learning materials.
- **[Free Programming Books](https://github.com/EbookFoundation/free-programming-books)** - The largest curated list of free programming books across every language and topic.

---

## Related Projects

Other curated lists from [DevTools Directory](https://devtools.directory) and the [AI for Developers](https://github.com/ai-for-developers) community:

- **[Awesome DevTools](https://github.com/devtoolsd/awesome-devtools)** - A curated list of the best developer tools across every category — editors, debuggers, productivity, and more.
- **[Awesome Cloud](https://github.com/devtoolsd/awesome-cloud)** - The best cloud platforms, services, and infrastructure tools for developers and DevOps.
- **[Awesome AI Coding Tools](https://github.com/ai-for-developers/awesome-ai-coding-tools)** - Curated list of AI-powered coding assistants, code generators, and developer copilots.
- **[Awesome VibeCoding](https://github.com/ai-for-developers/awesome-vibe-coding)** - Resources, tools, and guides for the emerging vibe coding movement — building with AI as a co-pilot.

---

## Contributing

PRs are welcome! When adding a book, please:

- Keep the list format consistent with existing sections.
- Prefer official or free links when available.
- Write a one-line description that explains **why it's worth reading**, not just what it covers.
- Note the edition and year if it matters — especially for fast-moving topics like AI.
- For the AI Engineering section, always include the publication year since the field moves quickly.

---

<div align="center">
  <sub> A <a href="https://devtools.directory">DevTools Directory</a> project · <a href="https://github.com/devtoolsd">github.com/devtoolsd</a> · <a href="#-awesome-devbooks--2026-edition">Back to top ↑</a></sub>
</div>
