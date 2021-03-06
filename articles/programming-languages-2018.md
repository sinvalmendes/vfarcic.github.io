## What do you believe will be the most in-demand programming language of 2018?

The most in-demand programming languages are, and will continue being, C, C++, Java, JavaScript, Python, C#, and other well-established ones. They've been around for so long that most software is written in one of those. Even if everyone decides to write new projects in some other language, those will continue dominating. The market for those languages is driven by legacy systems and people's desire to stick with what they know.

So, the concrete answer to the question is that the most in-demand languages in 2018 will continue being the same that were dominating 2017, and 2016, and the last ten years, or more.

We cannot escape legacy, nor we can hope that companies' workforce, often counted in thousands, will receive a blessing to spend considerable time away from projects to learn new languages. Technology moves fast, but adoption of new and better languages does not.

You might not agree with my statements. Maybe you went to StackOverflow and, judging from the number of question for each language, concluded that Python is the king now? I'd beg to differ. StackOverflow, and other similar sites, measure language popularity based on the number of questions each receives. Or the information might be coming from questionnaires and search terms. All those methods are flawed because they ignore the way how enterprise companies work. They are big and often closed into their own worlds. For example, an employee working in a huge bank is more likely to consult internal Wiki pages, or ask colleagues, or do some other type of internal inquiry than someone working in a smaller company. When looking at online sources in search for the most in-demand language, we often overlook that employees of some types of companies are more likely to search for solutions online, while others tend to rely more on internal resources.

When we combine the need to maintain legacy code, the traditionalism, laziness, or lack of time to learn, we can conclude that existing experts often stick with what they know. With the tendency of big corporations to turn to internal sources of knowledge, online sources of data become less valid than it might seem. The only thing left is to make such prediction based on personal experience from working with big enterprises, smaller startups, and different open source communities.

In the enterprise world, things do not change fast. Java, C, C#, and similar well-established languages, will continue to rule. Not much changed this year, nor can we expect a significant shift in 2018.

Instead, I'll limit my prediction to projects that start from scratch and are not limited with legacy systems nor internal company rules. I'll make my judgment based on open source projects that flourished in 2017 and are likely to continue growing (both in codebase size and numbers). In other words, I'm making my prediction based on choices that are restricted only by peoples opinion what would be the best language to code something that starts from nothing. No legacy, and no management decisions. I'll use only peoples desire to do their best and learn in the process without being restrained with the past.

With such a limited scope, the language that will rule in 2018 is Go.

## What's driving the demand for this skill?

Containers, microservices, clusters, and schedulers are all the hype (for a good reason).

Docker is becoming the de-facto standard for packaging and delivering applications. It's written in Go. Many of the tools in its ecosystem were written in other languages (e.g., Python), but Docker (the company) and the community around it decided that that is not good enough. They rewrote everything in Go and chose to start all new projects with it. The result is readable code base, resource efficient binaries, fast build time, and so on.

Microservices are focused on size and speed. People are slowly realizing that JVM is too big by itself. Even a "hello world" type of application requires hundreds of megabytes of libraries, has long compilation time, takes a long time to start, and so on. The same applies to other languages based on virtual machines (e.g., C#). None of them plays well with the ideas behind microservices. C is too complicated for rapid development, especially when memory management comes into play. Multi-threading is still a challenge in many languages. To cut the long story short, most programming languages were designed a long time ago when the problems they were trying to solve were different than those we're facing today. New languages emerged and will continue appearing. However, they are encumbered by the ghosts of the past (e.g., Kotlin requires JVM) or have a scope limited to only a small segment of professionals (R is mostly used for machine learning). Go is designed from scratch with the experience of older languages and is effective as a solution for a wide range of problems. It has a small footprint (ideal for microservices), has efficient memory management (garbage collector) that does not require a big VM, it's flexible, fast, and designed by a company that has the needs that exceed most others (Google).

In the meantime, Kubernetes became the fastest growing open source project with a huge ecosystem delivered through third-party solutions. The project itself is entirely written in Go. While that is not the requirement for third-party solutions, they are also mostly written in Go. All in all, the most talked about, and the fastest growing ecosystem is rotating around a single programming language.

2017 was floating around containers (Docker), microservices, and schedulers (Kubernetes and Swarm). While some might think that it was a hype that will be replaced with something else, I am convinced that they (together with DevOps and a few other things), just started. 2018 will be all about Kubernetes and its ecosystem. Some will adopt it, others will contribute to it, and many software vendors will base their strategies on the support of its ecosystem. 2018 will be the year when (almost) everyone will adopt Kubernetes or offer solutions based on it. Most of the work in that sphere will be done in Go, and that will, inevitably, lead to a huge increase in demand.

Kubernetes is not the only thing that leads me to that conclusion. We can observe the trend by watching companies who decided to rewrite their software or start a new line of products in a different language. That is often Go. HashiCorp, for example, switched to Go for its newer products (e.g., Terraform). Elastic wrote their new products in Go (e.g., PacketBeat and FileBeat). Google increased their usage of Go quite a lot.

All that is not to say that the "old" languages will not be used anymore nor that the demand will drop significantly. They will continue dominating. Go will not become the most used language anytime soon (if ever), but it will experience a bigger increase (percentage wise) than any other.

## What other languages do you feel will be popular in 2018? What's increasing the demand for these languages?

Machine learning will become more widespread, and that will increase the demand for R.

With the continuing increase in DevOps popularity, Python usage will increase as well. It is often the language of choice among sysadmins and operators (besides Bash). As they move away from their departments into self-sufficient teams in charge of a service (or two), they will bring Python with them. It is also becoming the language of choice for data-science projects, and that will fortify its demand.

## Which languages are likely to become less sought after in 2018?

JavaScript will see a decline. Browsers will continue being the dominating clients (there's not much need for desktop applications anymore). However, that is already a well-established market that will not see a significant increase. On the other hand, companies will start realizing that there is no strong reason to choose only one language for everything and the number of back-end projects written in JavaScript (NodeJS) will decline. People will start noticing its limitations and switch to something else. Since there is a strong aversion among JavaScript developers towards languages like Java and C#, they had no intention to change to something else. The rise in popularity of Go will provide a valid alternative to NodeJS and will result in a decline of JavaScript for back-end applications.
