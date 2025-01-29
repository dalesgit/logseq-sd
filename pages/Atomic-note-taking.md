### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#what-is-atomic-notetaking)What is Atomic Note-Taking?
tags:: [[SendToLogseq]]

Atomic note-taking is a method of organizing information into independent, atomic units. The aim is to build complex ideas by combining atomic parts and make the resulting ideas reusable by breaking them down into atomic units.

To make an analogy, it’s like building a product by placing a Lego block in the right place, which has part connection information, and then dismantling the product to create new ones.

Principles of Atomic Note-Taking\
The act of taking atomic notes is based on certain principles. These principles can be summarized as follows:

1. One idea, one note.
2. A note that is self-sufficient.
3. Notes that can be linked together.
4. Simple and short notes.
5. Notes focused on a single topic.
6. Information mapping.
7. Findability and traceability (tags, keywords, timestamps).
8. Quick writeability.
9. Manageability (personal information systems).

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#one-idea-one-note)One Idea, One Note

The most important feature of atomic notes is the principle of having only one idea per note. Since we will build the note around a concept like building with Legos, we start by writing the idea at the top of the note using our own notation (a custom writing system).

Let’s continue with an example:

Suppose you want to learn specific information about computer systems, but you don’t know where to start. My recommendation would be to first create keywords that describe what you want to know or learn, using just one or a few words.

To focus on one idea, we start the note by linking it to the topic. In this case, I will examine the topic of Termux.

```
---
Tags:
  - termux
  - linux
  - bash
  - mobile
  - android
  - arm7
datetime: 2024-12-07 11:24
---
> What is Termux?
Termux is a terminal emulator for Android that allows you to experience Linux commands without root permissions or special installation, enabling you to make changes on your phone.
```

As seen, our first note answers the question What is Termux?

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#avoid-writing-excessive-explanations)Avoid writing excessive explanations.

Avoid transitioning to a second topic.\
At the beginning of our note, we specify relevant topic tags (tags) to make it easier to find. After that, we add a timestamp (datetime) to our note, creating a reference for easy access. The other principles will explain what this achieves in detail.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#a-selfsufficient-note)A Self-Sufficient Note

A note should contain all the necessary information on its own. If necessary, we can add keywords to make it easier to find the note. We can also define tags that describe the related topics. After expressing the main message of the note clearly, we can include sources for further reading.

Let’s continue with our example.

```
---
tags:
  - termux
  - linux
  - arm7
  - mobile
  - development
  - setup
datetime: 2024-12-07 11:35
---
> How to install Termux?
There are different ways to install Termux. You can choose one of three methods:
1. Google Play Termux Installation
2. F-Droid Termux Installation
3. Github Termux Installation
We will prefer the second method, which is user-friendly. You can find the necessary information in the following notes and websites.
Installation Files: [F-Droid Termux](https://f-droid.org/en/packages/com.termux/)
Installation Information: [[F-Droid Termux Android Installation]]

```

As seen, all necessary information has been placed on the note. Even if no further details were given, the note still provides an idea of the topic. Also, the related topics are referenced, making the note ready to be expanded.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#linkable-notes)Linkable Notes

![image](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fmiro.medium.com%2Fv2%2Fresize%3Afit%3A720%2Fformat%3Awebp%2F0%2AwKioCIjdOUAA5Zo2){:width 720 :height 552}

As mentioned earlier, notes that can be linked together will facilitate a holistic understanding of the topic. This concept will be revisited when we discuss Personal Information Management Systems.

Diagrams and mind maps play a significant role in linking notes. Therefore, I recommend using mind mapping when creating relationship diagrams. For more information on mind mapping, you can refer to my blog article on Mind Mapping.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#simple-and-short-notes)Simple and Short Notes

Writing long and detailed notes can cause you to lose focus and generate many new questions, so it’s important to limit the length of your notes. The longer the note, the more likely it is to lose its context. Explanations can lead you to other information or new explanations, which may result in deviating from the core concept of atomic notes.

Additionally, when a note gets too long, it loses its atomicity and starts to resemble an article format, which can cause it to drift away from its purpose and practicality.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#focused-notes-on-one-topic)Focused Notes on One Topic

Although multitasking is often praised today, I argue the opposite: Stay focused! Focus entirely on the task at hand, in the moment, and in the place you are. Eliminate distractions and avoid attempting to do multiple tasks at once. Focus on a single topic.

If you need to address multiple ideas, break them into separate notes. Keep each idea as a separate note and revisit them when the time comes. This approach will help you clarify your ideas and address them in an organized manner.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#information-maps-and-diagrams)Information Maps and Diagrams

Frequencies of questions asked deepen our understanding of a topic. The more questions you ask, the broader a concept becomes. By asking a series of 5W1H (Who, What, Where, How, Why) questions about a simple idea, you can explore and expand it further.

Another method is to treat every name, technical term, or concept in a sentence as a new query point. By asking questions about each term or concept, you can analyze the idea in more detail.

Let’s clarify this with another example:

```
---
tags:
  - elixir
  - programming
  - developer
  - oop
  - functionalprogramming
  - highlevelprogramming
datetime: 2024-12-07 14:01
---
> What is Elixir?
Elixir is a dynamic, functional language for building scalable and maintainable applications.
> Which system does Elixir run on?
Elixir runs on the Erlang VM, known for creating low-latency, distributed, and fault-tolerant systems. These capabilities and Elixir tooling allow developers to be productive in several domains such as web development, embedded software, machine learning, data pipelines, and multimedia processing across various industries.
Now let’s ask some questions.
```

What are the terms mentioned in this explanation?

* Erlang VM
* low-latency
* distributed systems
* fault-tolerant systems
* Domain
* web development
* embedded software
* machine learning
* data pipelines
* multimedia processing
* functional language
* scalable applications
* maintainable applications
* dynamic language

Why is Elixir considered a dynamic language? (Let’s deepen the topic)

```
---
tags:
  - elixir
  - runtime
  - compiletime
datetime: 2024-12-07 14:10
---
> Why is Elixir a dynamic language?
_Elixir is considered a dynamic language because its type system and execution model rely on runtime behaviors rather than compile-time checks._
Elixir is considered a dynamic language because its type system and execution model rely on runtime behaviors rather than compile-time checks.
It is a dynamic structure since it is compiled at runtime and performs its checks during compilation.
```

For each of these points, we can create a separate note and formulate questions in pairs, as shown in the following example:

* What is Erlang VM?
* Why does Elixir have low latency?
* How is Elixir used in web development?
* How is Elixir used in embedded software?
* How is Elixir used in machine learning (ML)?
* Why is Elixir a functional programming language?
* How to write scalable software with Elixir?
* What is scalability in software?
* How are data pipelines created with Elixir?
* How is multimedia processing done with Elixir?
* How to write maintainable software with Elixir?
* How is Elixir used in distributed systems?
* How to write fault-tolerant software with Elixir?

As you can see, through a couple of explanation sentences, we can generate multiple questions and break down the topic into smaller, manageable sections. These notes are kept in an atomic system and can be used when needed.

Linking these notes with information maps and diagrams will help create a mental model of the topic and improve flexible and agile thinking. I recommend using Personal Information Management Systems and creating diagrams whenever possible. You can learn more about these systems in my related articles.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#findability-and-traceability)Findability and Traceability

In a personal knowledge management system, tags, timestamps, and keywords are essential for fast access to a note. Using general tags like TODO, FIX and search filters in your system will make it easy to find and retrieve information when needed.

Personally, I use Neovim and Obsidian with various plugins.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#quick-writeability)Quick Writeability

At this stage, creating specific templates for notes ensures that they are recorded in an organized and systematic way. Templates guarantee that each note has a certain structure, making it easy to access the information quickly.

For example, a template could look like this:

```
Title: Name of the note
Date: Creation date of the note
Tags: Key tags related to the topic
Keywords: Important terms related to the topic
Brief Description: A summary of the topic
Detailed Information: In-depth explanations about the topic
Links: Links to other related notes or resources
To-Do/Notes: TODO, progress status, or sections that need to be revised
```

These templates help gather all important information about a topic systematically. In tools like Obsidian and Neovim, you can efficiently work with such templates using plugins or macros.

```
---
tags:
  - tag1
  - tag2
  - tag3
datetime: { { datetime } }
aliases: { { alias } }
related-topics:
  - topic1
  - topic2
  - topic3
---
> {{IDEA}}
Explanations
## Tags
#tag1 #tag2 #tag3
## Backlinks
- [[related-note]]
- [[related-index]]
## Resources
- [weblink1](www.example.com)
- [weblink2](www.example.com)

```

Yes, by creating a note template like the one above, you can quickly and efficiently create new notes using the “Create From Template” feature in Personal Information Management Systems like Obsidian, Neovim, or Notion. This method brings order to your notes, provides faster access, and makes information management easier.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#manageability-personal-information-management-systems)Manageability — Personal Information Management Systems

Personal Information Management Systems (PIMS) are a set of tools and strategies aimed at optimizing the processes of gathering, organizing, storing, accessing, and reusing information. These systems are used to prevent information overload, speed up learning, and increase productivity. PIMS covers many areas, such as note-taking, task management, idea organization, project planning, and even tracking daily life.

While there are various PIMS systems available, you can find information about the tools I use to organize my writings — Neovim and Obsidian — in the related article series on my blog.

### [](https://dev.to/gokayburuc/atomic-note-taking-guide-4fo9#conclusion)Conclusion

I have shared the basic concepts of the atomic note-taking technique. You can explore more information on these topics through my related articles.

Also, you can find information in English about these systems through the following links:

[Obsidian](https://obsidian.md/)\
[Neovim](https://neovim.io/)

Looking forward to meeting you in new articles.

Stay safe!