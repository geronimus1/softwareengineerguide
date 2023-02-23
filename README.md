# From Zero to Hero: A Step-by-Step reading list to transform into a Super Professional Software Engineer
This guide is made for you to change. Please comment and edit this document!
If you have problems with editing just [write me on Linkedin](https://www.linkedin.com/in/yurigeronimus/)

## Introduction
> My fellow Supermen and Superwomen, I stand before you today to remind you that we are all capable of greatness. We may not have superhuman strength or the ability to fly, but we have something even better - the power of our minds and the strength of our wills. So let's put on our capes, channel our inner superheroes, and take on the world with all the courage and determination of the Man of Steel himself. Up, up, and away!

![We all are Supermans](/images/superman.png)

A friend of mine who currently holds a managerial position expressed interest in transitioning to a software engineer role. They approached me for recommendations on what to read and which language to start with, despite being uncertain about their future path.

To assist them, I have compiled a comprehensive list of recommended reading materials for individuals transitioning from a non-engineering background to a career in software engineering.

Furthermore, even if you are already a software engineer, you can still utilize this manual to enhance your skills and progress towards becoming a super software engineer.

## Instruction
>Attention citizens of Metropolis! Just like how Superman goes step-by-step to save the day, you too can become a software engineer by following a step-by-step reading list. And the best part? You can stop at any moment, just like how Superman takes a break to eat a sandwich. 

It is advisable to follow the sequence of links/books from point one to the next, but you have the freedom to stop at any point. The "manual" has been organized in a manner that progresses from crucial to more intricate concepts.

Please note that I have excluded management practices from this article since my friend is a manager, and he didn't ask it. However, you are welcome to include them if you wish.

## If you want only one simple source for software engineering…
> If you want only one simple source for Superman...  You could always try calling the Daily Planet and asking for Clark Kent. Just make sure you don't mention anything about Superman, or you might blow his cover!

Alright, if you're looking for just one simple source, then here they are:
1. Only one simple best practice for programmers - [link](#common-coding-conventions)
2. Only one simple overview of Software Design - [link](#basics-of-sw-design-and-arch)
3. Only one overview of Software architecture - [link](#my-modern-sw-arch) (sorry, only in Russian yet)
4. Only one book to be a good Software Engineer - [link](#code-completed)
5. Only one simple source for programming principles - [link](#principles)
6. Only one book about working with legacy code - [link](#legacy-code)
7. Only one good employee - [link](https://www.linkedin.com/in/yurigeronimus/)
8. Only one simple step-by-step reading list for the transition to a software engineer - this doc

## Educational pathway: Steps to be a software engineer
> Once upon a time, in a small town called Smallville, Superman was just a regular kid going to school. Well, maybe not so regular with his X-ray vision and super strength coming in handy during science class. After graduating high school, he didn't just fly away to save the world. Instead, he got his Bachelor's and Master's degrees because even a superhero knows the value of education. But let's be honest, those superpowers are what really make him a hero in the job market.

It's important to acknowledge that everything related to software development falls under the umbrella of Software Engineering. This encompasses the entire life cycle of software creation, including ideation, architecture, design, construction, implementation, operation, and ultimately, decommissioning.

However, it's crucial to note that in today's modern world, these steps often occur concurrently rather than in a sequential order.

## Conversation with a father about career: Your professional journey
> When Superman asked his father about his career, his father replied, "Son, you have to find your passion and fly with it!" Superman was confused, but his father continued, "No, literally, fly with it. That's how you became a superhero." And so, Superman explored various fields of interest, including saving the world, and never stopped learning how to become a better hero.

To ensure that you're on the right path for your future, it's important to determine what skills you should learn. Here are some useful roadmaps to guide you:

1. [Roadmaps for different roles and programming languages](https://roadmap.sh/) (excluding C++ developer).
2. Roadmaps specific to C++ developers:
    * A comprehensive [roadmap](https://github.com/salmer/CppDeveloperRoadmap) (available in Russian [here](https://github.com/salmer/CppDeveloperRoadmap/blob/main/Russian/README.md)).
    * Another useful [roadmap](https://tproger.ru/articles/razrabotka-na-c-s-nulja-v-2022-godu-dorozhnaja-karta/) (only available in Russian).

## Childhood: Computer science and Object-oriented programming basics
> As a little tyke, even Superman had to learn the basics of walking, talking, and making friends, just like the rest of us mere mortals. But let's be real, his true superpower was his boundless curiosity, which led him to explore the world around him and uncover its hidden secrets (and maybe accidentally break a few things along the way).

You should have a basic understanding of two major sections:
1. Computer science basics - here are a few options to understand the first major section. Since I learned this area a long time ago in university, I'm not familiar with the latest books. So, let's start with this [video](https://www.youtube.com/watch?v=SzJ46YA_RaA) to get a general idea of what computer science is all about. Then, you can explore two different options on the internet:
    1. For a simpler approach, check out [CS50's Introduction to Computer Science Harvard Course](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x)
    2. For a deeper dive, here's a more comprehensive list:
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

## Conversation with a father about the universe:  Overview of Software Design and Architecture
> When Superman asked his father about the universe, his mind was blown away like a bird in a tornado. His dad explained how the planets, stars, and galaxies were like pieces in a giant puzzle, and Superman's brain was like a sponge that absorbed all the knowledge like a thirsty plant on a rainy day. From that day forward, Superman's passion for space exploration was sky high!


Before we dive in, let's take a quick glance at Software Design and Architecture so that you have a general idea of what you'll be learning in the future. Who knows, maybe it'll be enough for you:smiley:, especially last book:
1. Firstly let’s understand the [difference between Software Design and Architecture](https://medium.com/clean-architecture/difference-between-software-architecture-design-ad09b5ff0a68), just for right mind set when you read these words  
2. Secondly, let’s learn the <a name="basics-of-sw-design-and-arch">[basics of Software Design and Architecture](https://khalilstemmler.com/articles/software-design-architecture/full-stack-software-design/)</a> (20-30 mins)
3. Excellent deep overview of software design and construction - <a name="code-completed">[Code Complete: A Practical Handbook of Software Construction](https://www.oreilly.com/library/view/code-complete-2nd/0735619670/) 2nd Edition</a> by Steve McConnell (in [rus](https://www.labirint.ru/books/272529/))
    1. <a name="code-completed-short">Fast track of this book - only Chapter 35 “Themes in Software Craftsmanship”</a>. Note: it is not a full abstract of this book.

## School
### Elementary school: People and organization communication
> Back in elementary school, Superman was just like any other kid, learning the ABCs and 123s. But little did he know that these fundamental skills would become his secret weapons against his toughest enemies. Who knew that the power of reading, writing, and math could save the world?

Understand that software engineering involves a great deal of communication and coordination among people and organizations. The source code is an only description of the software. Software is essentially electrical impulses on CPUs in server/client systems, and not merely text code on your computer. 

Therefore, it is important to have a good understanding of how to write a clear and descriptive code that resembles a written book:
1. How to write “words” and “sentences” 
    1. [Clean Code](https://amzn.to/3e2Am9t) by “Uncle” Bob Martin ([in rus](https://www.labirint.ru/books/642466/))
        * More simple with great examples and other information - <a name="common-coding-conventions">[Common Coding Conventions](https://github.com/tum-esi/common-coding-conventions)</a> by Associate Professorship of Embedded Systems and Internet of Things at TU Munich 
    2. Rewriting (Refactoring) is very important
        1. [Refactoring](https://amzn.to/2G1LIOy) by Martin Fowler ([in rus](https://www.labirint.ru/books/601754/))
            * [More simply with cool pictures](https://refactoring.guru/refactoring) ([in rus](https://refactoring.guru/ru/refactoring))
2. The storytelling of your software through version control (I recommend git)
    1. [Write Better Commits, Build Better Projects](https://github.blog/2022-06-30-write-better-commits-build-better-projects/)
    2. [The naming of your commits](https://dev.to/i5han3/git-commit-message-convention-that-you-can-follow-1709)
3. Do know that [your code can sign contracts](https://en.wikipedia.org/wiki/Design_by_contract) in modern coding like you and it is good

### Junior high school: Coding starts with coding tests and testing
> Superman wasn't just a bookworm in junior high/middle school. He was always pushing his limits, whether it was testing out his superhuman strength or seeing how far he could go with his wild imagination. These early years taught him to never back down from a challenge and to always believe in himself, no matter how impossible the task may seem.

In modern software engineering, coding begins with coding tests and testing. So, let's learn about Test-Driven Development (TDD).:
1. [TDD getting started](https://tddmanifesto.com/getting-started/)
2. Also [this](https://khalilstemmler.com/articles/test-driven-development/introduction-to-tdd/), and [this](https://medium.com/javascript-scene/tdd-changed-my-life-5af0ce099f80) ([in rus](https://habr.com/ru/company/ruvds/blog/450316/))

P.S. Do remember
> Legacy code is simply code without tests. 
> Code without tests is bad code. It doesn’t matter how well written it is; it doesn’t matter how pretty or object-oriented or well-encapsulated it is. With tests, we can change
the behavior of our code quickly and verifiably. Without them, we really don’t know
if our code is getting better or worse.
>
> -- *Michael C. Feathers, [Working Effectively with Legacy Code](#legacy-code)*

### High school: Something from engineering…
> During his high school years, Superman not only focused on academic subjects but also began to experience the realities of life beyond the classroom. Through extracurricular activities and volunteer work, he gained a sense of purpose and empathy for others, preparing him to use his powers for the greater good. This combination of academic and personal growth set the foundation for his future as a hero and helped him understand the challenges and struggles of real life.

In most cases in modern engineering, it's cheaper to purchase ready-made modules than to develop them yourself. Therefore:
1. Modules -  it's important to understand that there are various frameworks, libraries, and software that you should be familiar with and use
2. Additionally, you should be aware of:
    1. [Build automation tools](https://en.wikipedia.org/wiki/Build_automation) and [Package managers](https://en.wikipedia.org/wiki/Package_manager) for the correct use of modules
    2. [Different licenses](https://en.wikipedia.org/wiki/Software_license) that restrict you from using external modules
2. Just understand that there are many patterns of:
    1. Software design patterns - checkout [the simplest and most complete registry of software design patterns](https://en.wikipedia.org/wiki/Software_design_pattern#Classification_and_list)
        * For fans of patterns: [principles and principle language](#principles) and [pattern-oriented software architecture](https://en.wikipedia.org/wiki/Pattern-Oriented_Software_Architecture)
    2. Software architecture styles - check out this [list of software architecture styles and patterns](https://en.wikipedia.org/wiki/List_of_software_architecture_styles_and_patterns) 

P.S. As I have said Engineering is about the whole lifecycle from ideation to destruction so let's read about DevOps [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592) ([in rus](https://www.litres.ru/dzhin-kim/proekt-feniks-roman-o-tom-kak-devops-menyaet-biznes-k-luchshemu/))

## Bachelor of Science
> During his Bachelor of Science studies, Superman delved deep into the mysteries of science and technology, learning all sorts of nerdy things that would make Sheldon from The Big Bang Theory jealous. Armed with this newfound knowledge and a sharp intellect, he was ready to take on the world as a pro software engineer. Plus, he finally figured out how to calculate the trajectory of his punches to make them extra powerful!

### Primary curriculum: Software design and architecture

In this are we will understand about modern Software design and architecture:

1. <a name="my-modern-sw-arch">[My outlook on modern software structure and architecture styles](https://t.me/it_ace/124)</a> (only in Russian) - different styles of modern architectures, storage and messaging technologies, Service Mesh; microservice application design, domain-driven development; cloud-native, reactive, service mesh; deployment technologies - Kubernetes, Helm; data mesh; hundreds of different architectures of modern applications (for different purposes); CI / CD, DevOps, and SRE
2. Software design patterns and principles - area “Patterns and design principles” in [this link](https://roadmap.sh/software-architect) 
3. The modern approach to Software Architecture - [Fundamentals of Software Architecture](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) by Mark Richards, Neal Ford ([Russian language conspectus](https://apolomodov.medium.com/%D0%BE%D0%B1%D0%B7%D0%BE%D1%80-fundamentals-of-software-architecture-1754c0e78d48))
4. How Software architecture is practiced in reality - [Building Evolutionary Architectures](https://www.amazon.com/_/dp/1492097543?tag=oreilly20-20) by Neal Ford, Rebecca Parsons, Patrick Kua, Pramod Sadalage ([in rus, 1st edition](https://www.labirint.ru/books/667923/))
5. Difficult aspects of Software Architecture - [Software Architecture: The Hard Parts](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/) by Neal Ford, Mark Richards, Pramod Sadalage, Zhamak Dehghani ([Russian language conspectus](https://apolomodov.medium.com/review-software-architecture-the-hard-parts-part1-f0cc26ca6c16))

P.S. While there are many more in-depth aspects of software design and architecture to explore, we believe this list provides a solid foundation before diving into more advanced sources when you begin working. We will cover these advanced topics later in this article.

### Additional courses: Check everything else about software design and architecture
If you want a more in-depth overview of software design and architecture, you may find the following resources helpful:
1. [Overview of Software Design and Architecture](https://roadmap.sh/software-design-architecture)
2. A classic book about architecture history and design of solid module [Clean Architecture: A Craftsman’s Guide to Software Structure and Design](https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/) by Robert C. Martin ([in rus](https://www.ozon.ru/product/chistaya-arhitektura-iskusstvo-razrabotki-programmnogo-obespecheniya-144499396?sh=P1VIcNdqYQ)) (don’t read carefully at this step, just for an overview)

## On-the-Job Learning: Let's read when you will start work
> Well, after completing his formal education, Superman finally joined the workforce and boy was it a rollercoaster ride! From tackling office politics to dealing with cranky clients, Superman learned that the real-world had a lot more surprises in store for him than just fighting off Lex Luthor. But with his superpowers and quick wit, he was able to soar through any challenge that came his way!

As you're now working, it's important to read the best sources to be successful in real life, not just to appear intelligent:
1. More about best practices
   1. [Common Coding Conventions](https://github.com/tum-esi/common-coding-conventions) by Associate Professorship of Embedded Systems and Internet of Things at TU Munich
   2. [This link](#code-completed-short) for short best practices description from the “Code completed” book
   3. <a name="principles">[Programming principles](http://principles-wiki.net/about:start)</a> (and an additional [good link](https://github.com/webpro/programming-principles))
   4. Real software engineering - [Software Engineering at Google](https://www.oreilly.com/library/view/software-engineering-at/9781492082781/) by Titus Winters, Tom Manshreck, Hyrum Wright
2. More about object-oriented design:
   1. [Agile Software Development, Principles, Patterns, and Practices](https://www.amazon.com/Software-Development-Principles-Patterns-Practices/dp/0135974445) by Robert Martin
   2. [Object Design: Roles, Responsibilities, and Collaborations](https://www.amazon.com/Object-Design-Roles-Responsibilities-Collaborations/dp/0201379430), Rebecca Wirfs-Brock et al., Addison-Wesley, 2002.
3. How to work with legacy code
    1. <a name="legacy-code">[Working Effectively with Legacy Code](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052) by Michael Feathers</a> ([in rus](https://www.labirint.ru/books/231685/))
4. More about coding standards, best practices and tips
    1. [Common Coding Conventions](#bookmark=id.fcka2jdht9zf) by Associate Professorship of Embedded Systems and Internet of Things at TU Munich
    2. [Coding guides from Google](https://google.github.io/styleguide/)
    3. For C++
        1. [C++ core guidelines from C++ language author and other ](https://github.com/isocpp/CppCoreGuidelines)
        2. [Tips from Google](https://abseil.io/tips/)
        3. [Good rules for secure coding](https://wiki.sei.cmu.edu/confluence/pages/viewpage.action?pageId=88046682)
4. A good[ style guide from Google](https://google.github.io/styleguide/cppguide.html)
5.  More about patterns:
    1. [Design Patterns](https://amzn.to/35Mu7mH) by Gamma, Helm, Johnson, Vlissides
        * [Simply with the story and beautiful pictures](https://refactoring.guru/ru/design-patterns) ([in rus](https://refactoring.guru/ru/refactoring))
        * [Simplest quick reference for basic design patterns](http://www.mcdonaldland.info/2007/11/28/40/)
    2. [Pattern-oriented Software Architecture](https://amzn.to/3monFIS) by Buschmann et al
6.  In addition to all the previous - how you should work for success as a programmer - [The Pragmatic Programmer: your journey to mastery](https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/) by David Thomas, Andrew Hunt ([in rus](https://www.labirint.ru/books/749461/))
7.  [Another good list of software design and architecture books](https://apolomodov.medium.com/software-design-books-743be52e4c71) (only in Russian)

## Master of Science: About the big picture
> Ah, the illustrious MSc degree, where Superman can further hone his skills and become a real expert in his chosen field. It's like a superhero upgrade - a cape for the brain, if you will! And who knows, with all that advanced knowledge and research abilities, maybe Superman can finally figure out why people insist on wearing their underwear on the outside.

Once you achieve success in your work, you can expand your knowledge to understand broader contexts and the bigger picture, which can help you grow in your career:
1. “Horizontal” big picture - about the whole software lifecycle:
    1. Modern software lifecycle ![Modern software lifecycle](/images/archmap.png)
    2. Standard [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) ([in rus](https://github.com/ligurio/swebok-2004-in-russian))
2. “Vertical” big picture
    1. [The Architect’s Path](https://architectelevator.com/architecture/architect-bookshelf/)

## Additional courses: additional topics for learn
> Perhaps Superman even took a course on "How to Handle Kryptonite in the Workplace" or "Superhero Ethics 101." And let's not forget about "Superhero Fashion Design," because let's be honest, that cape doesn't just design itself!
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

## Additional sources
This section describes the sources of information from which this list was created. But which were not mentioned in it directly.

1. [https://irina-seng.medium.com/top-20-books-a-software-developer-must-read-updated-b24bcc9ee3d](https://irina-seng.medium.com/top-20-books-a-software-developer-must-read-updated-b24bcc9ee3d)
2. [https://youtu.be/rdToUPeO93s?t=1258](https://youtu.be/rdToUPeO93s?t=1258) (only in Russian)
3. [https://roadmap.sh/backend](https://roadmap.sh/backend) 
4. [https://roadmap.sh/software-architect](https://roadmap.sh/software-architect) 

## Authors
1. Yuri Geronimus, [https://www.linkedin.com/in/yurigeronimus/](https://www.linkedin.com/in/yurigeronimus/) (author of the initial version)
2. Let’s put your name and contacts)