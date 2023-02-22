# Step-by-step reading list for the transition to a software engineer from non-developer specialties
This manual is made for you to change. Please edit, add and comment on this document!
If you have problems with editing just [write me on Linkedin](https://www.linkedin.com/in/yurigeronimus/)

![We are all Supermans](/images/superman.png)
## Introduction
My friend in the manager role wants to become a programmer. He asked me to recommend what he can read now before he knows what he will do, even in what language he should develop.

I prepared this "manual" with a list of what to read if you are going to become a software engineer from a non-engineer.

## Instruction
You should read links/books step-by-step from 1 to the next point... **You can stop at any moment.** The "manual" is written in such a way that it from important to more detailed.

P.S. Because the manager asked me about this article, I didn't write you about management practices. But you can add them if you want.

## If you want only one simple source for software engineering…
Ok, If you want only one simples source, so…:
1. Only one simple best practice for programmers - [link](#common-coding-conventions)
2. Only one simple overview of Software Design - [link](#basics-of-sw-design-and-arch)
3. Only one overview of Software architecture - [link](#my-modern-sw-arch) (sorry, only in Russian yet)
4. Only one book to be a good Software Engineer - [link](#code-completed)
5. Only programming principles - [link](#principles)
6. Only one good employee - [link](https://www.linkedin.com/in/yurigeronimus/)
7. Only one step-by-step reading list for the transition to a software engineer - this doc

## Manual - steps to be a software engineer
Let’s understand that all about software creation is named Software Engineering.

Software engineering contains all lifecycle of software - from idea to …, architecture, design, …, construction, …, running, …,  and destruction in the end…

P.S. Be careful, all these steps are in parallel in our modern world.

### Step 00 - Map of your professional journey
Let's understand your future - what should you learn really. Roadmaps:
 1. [Roadmaps for different roles and programming languages](https://roadmap.sh/) (except C++ developer)
 2. Roadmaps for C++ developers:
     * A good[ roadmap](https://github.com/salmer/CppDeveloperRoadmap) ([in rus](https://github.com/salmer/CppDeveloperRoadmap/blob/main/Russian/README.md))
     * [Another good roadmap](https://tproger.ru/articles/razrabotka-na-c-s-nulja-v-2022-godu-dorozhnaja-karta/) (only in rus)

### Step 0 - Computer science and Object-oriented programming basics 
1. Computer science basics - I don't know modern books about computer science because I learned this area at university a long time ago). So let’s understand what is computer science through this [video](https://www.youtube.com/watch?v=SzJ46YA_RaA) and let's see on the internet: 
    1. Basic algorithm knowledge
        1. State machine
        2. Data structs and related: tree, list, deck, stack, queue, hash function, and hash table. [Great algorithm work visualization](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
        3. [Different sort algorithms](https://www.toptal.com/developers/sorting-algorithms)
        4. Computational complexity ([good explanation for data structures and sort algorithms](https://www.bigocheatsheet.com/)) and memory consumption of algorithms
    2. Basic database knowledge
        1. RDBMS, NoSQL, SQL
    3. Basic operating system knowledge
        1. [Process, thread](https://www.youtube.com/watch?v=4rLW7zg21gI)
    4. Basic network knowledge
        1. OSI
        2. TCP/IP (including IP, TCP, and UDP protocols), 
        3. Socket, HTTP
        4. [SSL, HTTPS](https://www.youtube.com/watch?v=j9QmMEWmcfo)
        5. DNS
        6. [How a browser works](https://www.youtube.com/watch?v=AlkDbnbv7dk)
    5. Basic API knowledge
        1.  API
        2.  SOAP, [REST](https://www.youtube.com/watch?v=-mN3VyJuCjM), [GraphQL](https://www.youtube.com/watch?v=yWzKJPw_VzM)
2. Object-oriented programming basics - let's see on the internet what it is in common, and…
    1. [4 Principles of Object-Oriented Programming](https://khalilstemmler.com/articles/object-oriented/programming/4-principles/)
    2. Best practices are below

### Step 1 - Overview of Software Design and Architecture
1. Firstly let’s understand the [difference between Software Design and Architecture](https://medium.com/clean-architecture/difference-between-software-architecture-design-ad09b5ff0a68), just for right mind set when you read these words  
2. Secondly, let’s learn the <a name="basics-of-sw-design-and-arch">[basics of Software Design and Architecture](https://khalilstemmler.com/articles/software-design-architecture/full-stack-software-design/)</a> (20-30 mins)
3. Excellent deep overview of software design and construction - <a name="code-completed">[Code Complete: A Practical Handbook of Software Construction](https://www.oreilly.com/library/view/code-complete-2nd/0735619670/) 2nd Edition</a> by Steve McConnell (in [rus](https://www.labirint.ru/books/272529/))
    1. <a name="code-completed-short">Fast track of this book - only Chapter 35 “Themes in Software Craftsmanship”</a>. Note: it is not a full abstract of this book.

### Step 2 - Coding
#### Step 2.1 People and organization communication
Do understand that software engineering is more about people and organization communication…

The source code is the only description of your software! It is true! Software is electrical impulses on CPUs in server/client, not “text code” on your computer. So you need to have got common knowledge about how to write this description looks like a writing book)
1. How to write “words” and “sentences” 
    1. [Clean Code](https://amzn.to/3e2Am9t) by “Uncle” Bob Martin ([in rus](https://www.labirint.ru/books/642466/))
        * More simple with great examples and other information - <a name="common-coding-conventions">[Common Coding Conventions](https://github.com/tum-esi/common-coding-conventions)</a> by Associate Professorship of Embedded Systems and Internet of Things at TU Munich 
    2. Rewriting (Refactoring) is very important
        1. [Refactoring](https://amzn.to/2G1LIOy) by Martin Fowler ([in rus](https://www.ozon.ru/search/?deny_category_prediction=true&from_global=true&text=%D0%A0%D0%B5%D1%84%D0%B0%D0%BA%D1%82%D0%BE%D1%80%D0%B8%D0%BD%D0%B3.+%D0%A3%D0%BB%D1%83%D1%87%D1%88%D0%B5%D0%BD%D0%B8%D0%B5+%D1%81%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D1%83%D1%8E%D1%89%D0%B5%D0%B3%D0%BE+%D0%BA%D0%BE%D0%B4%D0%B0&product_id=1308678))
            * [More simply with cool pictures](https://refactoring.guru/refactoring) ([in rus](https://refactoring.guru/ru/refactoring))
2. The storytelling of your software through version control (I recommend git)
    1. [Write Better Commits, Build Better Projects](https://github.blog/2022-06-30-write-better-commits-build-better-projects/)
    2. [The naming of your commits](https://dev.to/i5han3/git-commit-message-convention-that-you-can-follow-1709)
3. Do know that [your code can sign contracts](https://en.wikipedia.org/wiki/Design_by_contract) in modern coding like you and it is good

#### Step 2.2 Coding starts with coding tests and testing
Coding starts from coding tests and testing in modern software engineering, so let’s read about Test-Driven Development (TDD):
1. [TDD getting started](https://tddmanifesto.com/getting-started/)
2. Also [this](https://khalilstemmler.com/articles/test-driven-development/introduction-to-tdd/), and [this](https://medium.com/javascript-scene/tdd-changed-my-life-5af0ce099f80) ([in rus](https://habr.com/ru/company/ruvds/blog/450316/))

P.S. Do remember
> Legacy code is simply code without tests. 
> Code without tests is bad code. It doesn’t matter how well written it is; it doesn’t matter how pretty or object-oriented or well-encapsulated it is. With tests, we can change
the behavior of our code quickly and verifiably. Without them, we really don’t know
if our code is getting better or worse.
>
> -- *Michael C. Feathers, Working Effectively with Legacy Code*

#### Step 2.3 Something from engineering…
"Buying" ready modules are cheaper than doing them yourself in most cases in modern engineering, so:
1. Modules - just understand that there are many frameworks, libraries, and software that you should use and know
    1. There are [build automation tools](https://en.wikipedia.org/wiki/Build_automation) and [package managers](https://en.wikipedia.org/wiki/Package_manager) for the correct use of modules
    2. Understand that there are [different licenses](https://en.wikipedia.org/wiki/Software_license) that restrict you from using external modules
2. Just understand that are many patterns of 
    1. software design patterns - [the simplest and most complete registry of software design patterns](https://en.wikipedia.org/wiki/Software_design_pattern#Classification_and_list) (for fans: [principles and principle language](http://principles-wiki.net/about:start) and [pattern-oriented software architecture](https://en.wikipedia.org/wiki/Pattern-Oriented_Software_Architecture)), and…
    2. software architecture styles - [list of software architecture styles and patterns](https://en.wikipedia.org/wiki/List_of_software_architecture_styles_and_patterns) 

P.S. As I have said Engineering is about the whole lifecycle from ideation to destruction so let's read about DevOps [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592) ([in rus](https://www.litres.ru/dzhin-kim/proekt-feniks-roman-o-tom-kak-devops-menyaet-biznes-k-luchshemu/))

### Step 3 - Software design and architecture
1. <a name="my-modern-sw-arch">[My outlook on modern software structure and architecture styles](https://t.me/it_ace/124)</a> (only in Russian) - different styles of modern architectures, storage and messaging technologies, Service Mesh; microservice application design, domain-driven development; cloud-native, reactive, service mesh; deployment technologies - Kubernetes, Helm; data mesh; hundreds of different architectures of modern applications (for different purposes); CI / CD, DevOps, and SRE
2. Software design patterns and principles - area “Patterns and design principles” in [this link](https://roadmap.sh/software-architect) 
3. The modern approach to Software Architecture - [Fundamentals of Software Architecture](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) by Mark Richards, Neal Ford ([Russian language conspectus](https://apolomodov.medium.com/%D0%BE%D0%B1%D0%B7%D0%BE%D1%80-fundamentals-of-software-architecture-1754c0e78d48))
4. Difficult aspects of Software Architecture - [Software Architecture: The Hard Parts](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/) by Neal Ford, Mark Richards, Pramod Sadalage, Zhamak Dehghani ([Russian language conspectus](https://apolomodov.medium.com/review-software-architecture-the-hard-parts-part1-f0cc26ca6c16))

### Step 4 - Check everything else about software design and architecture
1. [Overview of Software Design and Architecture](https://roadmap.sh/software-design-architecture)
2. A classic book about architecture history and design of solid module [Clean Architecture: A Craftsman’s Guide to Software Structure and Design](https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/) by Robert C. Martin ([in rus](https://www.ozon.ru/product/chistaya-arhitektura-iskusstvo-razrabotki-programmnogo-obespecheniya-144499396?sh=P1VIcNdqYQ)) (don’t read carefully at this step, just for an overview)

### Step 5 - Additional - let's read when you will start work
1. More about best practices
   1. [Common Coding Conventions](https://github.com/tum-esi/common-coding-conventions) by Associate Professorship of Embedded Systems and Internet of Things at TU Munich
   2. [This link](#code-completed-short) for short best practices description from the “Code completed” book
   3. <a name="principles">[Programming principles](http://principles-wiki.net/about:start)</a> (and an additional [good link](https://github.com/webpro/programming-principles))
   4. Real software engineering - [Software Engineering at Google](https://www.oreilly.com/library/view/software-engineering-at/9781492082781/) by Titus Winters, Tom Manshreck, Hyrum Wright
2. More about object-oriented design:
   1. [Agile Software Development, Principles, Patterns, and Practices](https://www.amazon.com/Software-Development-Principles-Patterns-Practices/dp/0135974445) by Robert Martin
   2. [Object Design: Roles, Responsibilities, and Collaborations](https://www.amazon.com/Object-Design-Roles-Responsibilities-Collaborations/dp/0201379430), Rebecca Wirfs-Brock et al., Addison-Wesley, 2002.
3. More about coding standards, best practices and tips
   1. [Common Coding Conventions](#bookmark=id.fcka2jdht9zf) by Associate Professorship of Embedded Systems and Internet of Things at TU Munich
   2. [Coding guides from Google](https://google.github.io/styleguide/)
   3. For C++
      1. [C++ core guidelines from C++ language author and other ](https://github.com/isocpp/CppCoreGuidelines)
      2. [Tips from Google](https://abseil.io/tips/)
      3. [Good rules for secure coding](https://wiki.sei.cmu.edu/confluence/pages/viewpage.action?pageId=88046682)
      4. A good[ style guide from Google](https://google.github.io/styleguide/cppguide.html)
4.  More about patterns:
    1. [Design Patterns](https://amzn.to/35Mu7mH) by Gamma, Helm, Johnson, Vlissides
        * [Simply with the story and beautiful pictures](https://refactoring.guru/ru/design-patterns) ([in rus](https://refactoring.guru/ru/refactoring))
    2. [Pattern-oriented Software Architecture](https://amzn.to/3monFIS) by Buschmann et al
5.  In addition to all the previous - how you should work for success as a programmer - [The Pragmatic Programmer: your journey to mastery](https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/) by David Thomas, Andrew Hunt ([in rus](https://www.labirint.ru/books/749461/))
6.  [Another good list of software design and architecture books](https://apolomodov.medium.com/software-design-books-743be52e4c71) (only in Russian)

### Step 6 - About the big picture - let's read at night when you have finished work  :-)
1. Big pictures
   1. “Horizontal” big picture - about the whole software lifecycle:
       1. Modern software lifecycle ![Modern software lifecycle](/images/archmap.png)
       2. Standard [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) ([in rus](https://github.com/ligurio/swebok-2004-in-russian))
   2. “Vertical” big picture
       1. [The Architect’s Path](https://architectelevator.com/architecture/architect-bookshelf/)

### Additional topics
1. Programming:
    1. Good logs
    2. Command line - bash, Powershell
2. Social activities
    1. Software design document
    2. [Architecture decision records](https://github.com/joelparkerhenderson/architecture-decision-record)
3. CI/CD - [link](https://www.youtube.com/watch?v=42UP1fxi2SY)
4. [https://www.shecancode.io/blog/my-software-engineer-roadmap-by-joana-carneiro](https://www.shecancode.io/blog/my-software-engineer-roadmap-by-joana-carneiro) 
5. DDD - [link](https://khalilstemmler.com/articles/domain-driven-design-intro/)
6. BDD

### Additional sources
This section describes the sources of information from which this list was created. But which were not mentioned in it directly.

1. [https://irina-seng.medium.com/top-20-books-a-software-developer-must-read-updated-b24bcc9ee3d](https://irina-seng.medium.com/top-20-books-a-software-developer-must-read-updated-b24bcc9ee3d)
2. [https://youtu.be/rdToUPeO93s?t=1258](https://youtu.be/rdToUPeO93s?t=1258) (only in Russian)
3. [https://roadmap.sh/backend](https://roadmap.sh/backend) 
4. [https://roadmap.sh/software-architect](https://roadmap.sh/software-architect) 

## Authors
1. Yuri Geronimus, [https://www.linkedin.com/in/yurigeronimus/](https://www.linkedin.com/in/yurigeronimus/) (author of the initial version)
2. Let’s put your name and contacts)