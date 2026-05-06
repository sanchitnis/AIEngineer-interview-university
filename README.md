# AI Engineer Interview University

> This study guide is a complete, self-paced curriculum for landing an **AI Engineer** role at a
> top tech company — Google DeepMind, OpenAI, Anthropic, Meta AI, Microsoft AI, Cohere, Mistral, and beyond.
>
> AI Engineers sit at the intersection of software engineering and machine learning. They build
> production ML systems, integrate LLMs into products, design data pipelines, and deploy models
> at scale. This guide covers everything you need: classical CS foundations *and* the modern
> ML/AI stack that interviewers at AI-first companies actually test.
>
> **Please Note:** Focus on the sections marked as required first. The optional sections are
> genuinely optional — depth over breadth. I'll help you get there without wasting your precious time.
>
> The items listed here will prepare you well for a technical interview at any AI-focused company,
> including: OpenAI, Anthropic, Google DeepMind, Meta AI, Microsoft AI, Cohere, Mistral, and the
> traditional giants: Amazon, Google, Meta, and Microsoft.
>
> *Best of luck to you!*

**Note:** This guide is currently available in English only. Translations have been removed to keep the content focused and up-to-date.


## What is it?

<img src="https://github.com/user-attachments/assets/5ee086cc-8412-4cd8-90f7-0386b1bfdaa0">

This is a multi-month study plan for becoming an **AI Engineer** at a top technology company.

**What does an AI Engineer actually do?**
An AI Engineer is not a pure researcher (they don't publish papers) and not a pure software engineer (they don't just build CRUD apps). They:
- Build, fine-tune, and deploy machine learning models in production
- Integrate LLMs, embedding models, and generative AI into products
- Design and maintain data pipelines and feature stores
- Run experiments, evaluate model quality, and monitor models in production
- Work across the ML stack: from data wrangling to inference optimization

AI Engineer roles exist at: Google DeepMind, OpenAI, Anthropic, Meta AI, Microsoft (Copilot team), Cohere, Mistral, Stability AI, and virtually every large tech company with an AI product team.

> *"AI is going to change the nature of work. The engineers who will thrive are those who learn to build with AI, not just use it."*
>
> — **Sam Altman**, CEO of OpenAI

**Required:**
* Python fluency (you will write Python every day)
* Some experience with data (pandas, NumPy, or similar)
* Patience
* Time

Note this is a study plan for **AI engineering**, not frontend engineering, full-stack web development, or pure ML research. It emphasizes the **Python ML ecosystem**, classical CS fundamentals still tested in interviews, and the modern AI/LLM stack.

For a complete CS self-taught program, the resources for this study plan have been included in Kamran Ahmed's Computer Science Roadmap: https://roadmap.sh/computer-science

---

## Choose Your Track

This guide covers **two distinct AI career tracks**. They overlap significantly — both require CS fundamentals and Python — but they diverge in focus. Read both descriptions and choose where to start. You can always cross-train later.

> *"The hottest new programming language is English."*
>
> — **Andrej Karpathy**, former Director of AI at Tesla & co-founder of OpenAI (February 2023)

> *"Every company will be an AI company — the way every company today is a software company. The question is which engineers will lead that transformation."*
>
> — **Jensen Huang**, CEO of NVIDIA

---

### 🏗️ Track A — AI-native Builder

> *"I want to build products and systems using AI tools and LLMs as my primary accelerants."*

**Who this is for:** Product engineers, full-stack developers, and technical founders who want to leverage AI tools (Claude Code, GitHub Copilot, Cursor, Windsurf, etc.) to ship AI-powered products fast. You think in systems: APIs, product flows, architecture diagrams. You don't need to train models from scratch — you orchestrate them.

**Core skills:**
- AI-assisted coding (vibe coding with guardrails, spec-driven development)
- Product engineering: translating user needs → technical specs → shipped features
- Systems architecture: designing robust, scalable AI product backends
- LLM orchestration: prompt engineering, RAG, agents, tool use
- Shipping: CI/CD, cloud deployment, observability

**Sections to prioritize:**
→ [Track A: AI-native Builder](#track-a-ai-native-builder) *(new dedicated section)*
→ [AI-native SDLC & Spec-Driven Development](#ai-native-sdlc--spec-driven-development)
→ [System Thinking & Software Architecture](#system-thinking--software-architecture)
→ [LLM Agents](#llm-agents) + [RAG](#rag-retrieval-augmented-generation) + [Prompting Techniques](#prompting-techniques)
→ [MLOps & AI Infrastructure](#mlops--ai-infrastructure)
→ CS Fundamentals (data structures, algorithms, system design) — still tested in interviews

---

### 🔬 Track B — AI Engineer

> *"I want to build the AI systems themselves — train models, fine-tune LLMs, architect agentic pipelines, and work on the hard technical problems."*

**Who this is for:** Engineers who want to work directly on AI systems: fine-tuning language models, building agentic architectures, curating training data, running distillation pipelines, and owning the full model lifecycle from data collection to production. These are the roles at OpenAI, Anthropic, Google DeepMind, Meta AI Research, and similar organizations.

**Core skills:**
- Deep learning theory and practice (Transformers, training dynamics)
- LLM fine-tuning: instruction tuning, RLHF, DPO, LoRA/QLoRA
- Knowledge distillation: training smaller models to match larger ones
- Data engineering: collection, cleaning, curation, synthetic data generation
- Agentic AI systems: multi-step reasoning, tool use, memory, multi-agent orchestration
- MLOps: experiment tracking, model serving, inference optimization

**Sections to prioritize:**
→ [Track B: AI Engineer (Deep Technical)](#track-b-ai-engineer-deep-technical) *(new dedicated section)*
→ [Deep Learning](#deep-learning) + [Transformers & Attention](#transformers--attention)
→ [Large Language Models & Generative AI](#large-language-models--generative-ai)
→ [MLOps & AI Systems Engineering](#mlops--ai-systems-engineering)
→ [Mathematics for AI](#mathematics-for-ai) — required foundation
→ CS Fundamentals — required at all AI companies

---

## Table of Contents

### The Study Plan

- [What is it?](#what-is-it)
- [Choose Your Track](#choose-your-track)
- [Why use it?](#why-use-it)
- [How to use it](#how-to-use-it)
- [Don't feel you aren't smart enough](#dont-feel-you-arent-smart-enough)
- [A Note About Video Resources](#a-note-about-video-resources)
- [Choose a Programming Language](#choose-a-programming-language)
- [Books for Data Structures and Algorithms](#books-for-data-structures-and-algorithms)
- [Interview Prep Books](#interview-prep-books)
- [Don't Make My Mistakes](#dont-make-my-mistakes)
- [What you Won't See Covered](#what-you-wont-see-covered)
- [The Daily Plan](#the-daily-plan)
- [Coding Question Practice](#coding-question-practice)
- [Coding Problems](#coding-problems)

### 🏗️ Track A — AI-native Builder

- [Track A: AI-native Builder](#track-a-ai-native-builder)
    - [AI Coding Tools & Vibe Coding Workflows](#ai-coding-tools--vibe-coding-workflows)
    - [Product Engineering with AI](#product-engineering-with-ai)
    - [Systems Architecture for AI Products](#systems-architecture-for-ai-products)
    - [Orchestrating AI: Prompting, RAG & Agents for Builders](#orchestrating-ai-prompting-rag--agents-for-builders)
    - [Shipping AI Products: Cloud, APIs & Observability](#shipping-ai-products-cloud-apis--observability)

### 🔬 Track B — AI Engineer (Deep Technical)

- [Track B: AI Engineer (Deep Technical)](#track-b-ai-engineer-deep-technical)
    - [Agentic AI Systems](#agentic-ai-systems)
    - [LLM Fine-tuning in Depth](#llm-fine-tuning-in-depth)
    - [Knowledge Distillation](#knowledge-distillation)
    - [Data Collection & Curation](#data-collection--curation)
    - [Synthetic Data Generation](#synthetic-data-generation)

### AI Engineer Essentials

- [AI-native SDLC & Spec-Driven Development](#ai-native-sdlc--spec-driven-development)
- [Work Environment & Portfolio Building](#work-environment--portfolio-building)
    - [Git & GitHub](#git--github)
    - [Development Environment & Tooling](#development-environment--tooling)
    - [Full-Stack Development Basics](#full-stack-development-basics)
    - [Building & Showcasing Your Portfolio](#building--showcasing-your-portfolio)
- [System Thinking & Software Architecture](#system-thinking--software-architecture)
    - [Architectural Thinking](#architectural-thinking)
    - [Software Architecture Patterns](#software-architecture-patterns)
    - [AI System Design](#ai-system-design)
- [Cloud Concepts for Data Engineering](#cloud-concepts-for-data-engineering)
    - [Cloud Fundamentals](#cloud-fundamentals)
    - [Data Engineering on the Cloud](#data-engineering-on-the-cloud)
    - [MLOps & AI Infrastructure](#mlops--ai-infrastructure)
- [Core Human Life Skills for the AI Era](#core-human-life-skills-for-the-ai-era)
    - [Communication & Storytelling](#communication--storytelling)
    - [Critical Thinking & Problem Framing](#critical-thinking--problem-framing)
    - [Adaptability & Continuous Learning](#adaptability--continuous-learning)
    - [Collaboration & Emotional Intelligence](#collaboration--emotional-intelligence)
- [deeplearning.ai Learning Path](#deeplearningai-learning-path)
    - [Foundational AI & ML](#foundational-ai--ml)
    - [Generative AI & LLMs](#generative-ai--llms)
    - [MLOps & Deployment](#mlops--deployment)
    - [AI for Everyone](#ai-for-everyone)

### AI/ML Core Knowledge

- [Mathematics for AI](#mathematics-for-ai)
    - [Linear Algebra](#linear-algebra)
    - [Calculus & Optimization](#calculus--optimization)
    - [Probability & Statistics](#probability--statistics)
    - [Information Theory](#information-theory-for-ai)
- [Machine Learning Fundamentals](#machine-learning-fundamentals)
    - [Supervised Learning](#supervised-learning)
    - [Unsupervised Learning](#unsupervised-learning)
    - [Model Evaluation & Selection](#model-evaluation--selection)
    - [Feature Engineering](#feature-engineering)
    - [Evaluation Metrics](#evaluation-metrics)
- [Deep Learning](#deep-learning)
    - [Neural Network Fundamentals](#neural-network-fundamentals)
    - [Training Techniques](#training-techniques)
    - [CNNs](#cnns)
    - [RNNs, LSTMs & GRUs](#rnns-lstms--grus)
    - [Transformers & Attention](#transformers--attention)
- [Large Language Models & Generative AI](#large-language-models--generative-ai)
    - [LLM Architecture](#llm-architecture)
    - [Pre-training & Fine-tuning](#pre-training--fine-tuning)
    - [Prompting Techniques](#prompting-techniques)
    - [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation)
    - [LLM Agents](#llm-agents)
    - [LLM Evaluation](#llm-evaluation)
- [MLOps & AI Systems Engineering](#mlops--ai-systems-engineering)
    - [ML Pipelines](#ml-pipelines)
    - [Experiment Tracking](#experiment-tracking)
    - [Model Serving](#model-serving)
    - [Inference Optimization](#inference-optimization)
    - [Model Monitoring](#model-monitoring)
    - [Feature Stores](#feature-stores)
    - [Vector Databases](#vector-databases)
    - [Data Versioning](#data-versioning)

### Topics of Study

- [Algorithmic complexity / Big-O / Asymptotic analysis](#algorithmic-complexity--big-o--asymptotic-analysis)
- [Data Structures](#data-structures)
    - [Arrays](#arrays)
    - [Linked Lists](#linked-lists)
    - [Stack](#stack)
    - [Queue](#queue)
    - [Hash table](#hash-table)
- [More Knowledge](#more-knowledge)
    - [Binary search](#binary-search)
    - [Bitwise operations](#bitwise-operations)
- [Trees](#trees)
    - [Trees - Intro](#trees---intro)
    - [Binary search trees: BSTs](#binary-search-trees-bsts)
    - [Heap / Priority Queue / Binary Heap](#heap--priority-queue--binary-heap)
    - balanced search trees (general concept, not details)
    - traversals: preorder, inorder, postorder, BFS, DFS
- [Sorting](#sorting)
    - selection
    - insertion
    - heapsort
    - quicksort
    - mergesort
- [Graphs](#graphs)
    - directed
    - undirected
    - adjacency matrix
    - adjacency list
    - traversals: BFS, DFS
- [Even More Knowledge](#even-more-knowledge)
    - [Recursion](#recursion)
    - [Dynamic Programming](#dynamic-programming)
    - [Design Patterns](#design-patterns)
    - [Combinatorics (n choose k) & Probability](#combinatorics-n-choose-k--probability)
    - [NP, NP-Complete and Approximation Algorithms](#np-np-complete-and-approximation-algorithms)
    - [How computers process a program](#how-computers-process-a-program)
    - [Caches](#caches)
    - [Processes and Threads](#processes-and-threads)
    - [Testing](#testing)
    - [String searching & manipulations](#string-searching--manipulations)
    - [Tries](#tries)
    - [Floating Point Numbers](#floating-point-numbers)
    - [Unicode](#unicode)
    - [Endianness](#endianness)
    - [Networking](#networking)
- [Final Review](#final-review)

### Getting the Job

- [Update Your Resume](#update-your-resume)
- [Find a Job](#find-a-job)
- [Interview Process & General Interview Prep](#interview-process--general-interview-prep)
- [Be thinking of for when the interview comes](#be-thinking-of-for-when-the-interview-comes)
- [Have questions for the interviewer](#have-questions-for-the-interviewer)
- [Once You've Got The Job](#once-youve-got-the-job)

**---------------- Everything below this point is optional ----------------**

### Optional Extra Topics & Resources

- [Additional Books](#additional-books)
- [System Design, Scalability, Data Handling](#system-design-scalability-data-handling) (if you have 4+ years experience)
- [Additional Learning](#additional-learning)
    - [Compilers](#compilers)
    - [Emacs and vi(m)](#emacs-and-vim)
    - [Unix command line tools](#unix-command-line-tools)
    - [Information theory](#information-theory-videos)
    - [Parity & Hamming Code](#parity--hamming-code-videos)
    - [Entropy](#entropy)
    - [Cryptography](#cryptography)
    - [Compression](#compression)
    - [Computer Security](#computer-security)
    - [Garbage collection](#garbage-collection)
    - [Parallel Programming](#parallel-programming)
    - [Messaging, Serialization, and Queueing Systems](#messaging-serialization-and-queueing-systems)
    - [A*](#a)
    - [Fast Fourier Transform](#fast-fourier-transform)
    - [Bloom Filter](#bloom-filter)
    - [HyperLogLog](#hyperloglog)
    - [Locality-Sensitive Hashing](#locality-sensitive-hashing)
    - [van Emde Boas Trees](#van-emde-boas-trees)
    - [Augmented Data Structures](#augmented-data-structures)
    - [Balanced search trees](#balanced-search-trees)
        - AVL trees
        - Splay trees
        - Red/black trees
        - 2-3 search trees
        - 2-3-4 Trees (aka 2-4 trees)
        - N-ary (K-ary, M-ary) trees
        - B-Trees
    - [k-D Trees](#k-d-trees)
    - [Skip lists](#skip-lists)
    - [Network Flows](#network-flows)
    - [Disjoint Sets & Union Find](#disjoint-sets--union-find)
    - [Math for Fast Processing](#math-for-fast-processing)
    - [Treap](#treap)
    - [Linear Programming](#linear-programming-videos)
    - [Geometry, Convex hull](#geometry-convex-hull-videos)
    - [Discrete math](#discrete-math)
- [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)
- [Video Series](#video-series)
- [Computer Science Courses](#computer-science-courses)
- [Papers](#papers)

---

## Why use it?

> *"AI is not going to replace people. But people who use AI are going to replace people who don't."*
>
> — **Satya Nadella**, CEO of Microsoft

If you want to work as a software engineer for a large company, these are the things you have to know.

If you missed out on getting a degree in computer science, like I did, this will catch you up and save four years of your life.

When I started this project, I didn't know a stack from a heap, didn't know Big-O anything, or anything about trees, or how to
traverse a graph. If I had to code a sorting algorithm, I can tell ya it would have been terrible.
Every data structure I had ever used was built into the language, and I didn't know how they worked
under the hood at all. I never had to manage memory unless a process I was running would give an "out of
memory" error, and then I'd have to find a workaround. I used a few multidimensional arrays in my life and
thousands of associative arrays, but I never created data structures from scratch.

It's a long plan. It may take you months. If you are familiar with a lot of this already it will take you a lot less time.

**[⬆ back to top](#table-of-contents)**

## How to use it

Everything below is an outline, and you should tackle the items in order from top to bottom.

I'm using GitHub's special markdown flavor, including tasks lists to track progress.
  - [More about GitHub-flavored markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

### If you don't want to use git

On this page, click the Code button near the top, then click "Download ZIP". Unzip the file and you can work with the text files.

If you're open in a code editor that understands markdown, you'll see everything formatted nicely.

![How to download the repo as a zip file](https://d3j2pkmjtin6ou.cloudfront.net/how-to-download-as-zip.png)

### If you're comfortable with git

Create a new branch so you can check items like this, just put an x in the brackets: [x]

1. ***Fork the GitHub repo:*** `https://github.com/jwasham/coding-interview-university` by clicking on the Fork button.

    ![Fork the GitHub repo](https://d3j2pkmjtin6ou.cloudfront.net/fork-button.png)

1. Clone to your local repo:

    ```bash
    git clone https://github.com/<YOUR_GITHUB_USERNAME>/coding-interview-university.git
    cd coding-interview-university
    git remote add upstream https://github.com/jwasham/coding-interview-university.git
    git remote set-url --push upstream DISABLE  # so that you don't push your personal progress back to the original repo
    ```

1. Mark all boxes with X after you completed your changes:

    ```bash
    git commit -am "Marked personal progress"
    git pull upstream main  # keep your fork up-to-date with changes from the original repo

    git push # just pushes to your fork
    ```

**[⬆ back to top](#table-of-contents)**

## Don't feel you aren't smart enough

- Successful software engineers are smart, but many have an insecurity that they aren't smart enough.
- The following videos may help you overcome this insecurity:
    - [The myth of the Genius Programmer](https://www.youtube.com/watch?v=0SARbwvhupQ)
    - [It's Dangerous to Go Alone: Battling the Invisible Monsters in Tech](https://www.youtube.com/watch?v=1i8ylq4j_EY)

**[⬆ back to top](#table-of-contents)**

## A Note About Video Resources

Some videos are available only by enrolling in a Coursera or EdX class. These are called MOOCs.
Sometimes the classes are not in session so you have to wait a couple of months, so you have no access.

It would be great to replace the online course resources with free and always-available public sources,
such as YouTube videos (preferably university lectures), so that you people can study these anytime,
not just when a specific online course is in session.

**[⬆ back to top](#table-of-contents)**

## Choose a Programming Language

**Python is the primary language for AI Engineers.** Use it for this study plan, for coding interviews at AI companies, and for all ML/data work.

### For this Study Plan

Use **Python**. It is the lingua franca of machine learning and AI engineering:
- Every major ML framework (PyTorch, TensorFlow, JAX, scikit-learn) has a Python API
- Data manipulation with NumPy and pandas is expected knowledge
- LLM tooling (LangChain, LlamaIndex, HuggingFace Transformers) is Python-native
- Interviewers at AI companies expect fluency in Python idioms

Familiarity with NumPy array operations and basic PyTorch tensor manipulation is a plus — you may be asked to implement ML primitives (e.g., a forward pass, a dot product attention) in Python.

**What about C?**
C/C++ knowledge is *optional background* for AI Engineers. Understanding memory layout helps you reason about model inference performance, but you will not be asked to implement linked lists in C in an AI Engineer interview. Skip it unless you're curious.

Learning resources:
- [Exercism Python track](https://exercism.org/tracks/python)
- [Python for Everybody (Coursera, free to audit)](https://www.coursera.org/specializations/python)
- [Real Python](https://realpython.com/)

### For your Coding Interview

Use **Python** for the coding portion of AI Engineer interviews. It is the most widely accepted language at AI companies and lets you write concise, readable solutions quickly:

- Python ✅ (primary recommendation)
- C++ (accepted everywhere, useful if you're already strong in it)
- Java (accepted, but less idiomatic for ML tasks)

You could also use JavaScript or Ruby, but Python is strongly preferred at AI-first companies.

Read more about choices:
- [Choose the Right Language for Your Coding Interview](http://www.byte-by-byte.com/choose-the-right-language-for-your-coding-interview/)

[See AI building resources here](AI-building-resources.md)

**[⬆ back to top](#table-of-contents)**

## Books for Data Structures and Algorithms

Choose one Python-focused book to build your CS foundation. You'll be doing a lot of reading and coding.

### Python (Recommended)

- [Coding Interview Patterns: Nail Your Next Coding Interview](https://geni.us/q7svoz) (**Main Recommendation**)
    - An insider's perspective on what interviewers are truly looking for and why.
    - 101 real coding interview problems with detailed solutions.
    - Intuitive explanations that guide you through each problem as if you were solving it in a live interview.
    - 1000+ diagrams to illustrate key concepts and patterns.

### Optional (C / Java / C++)

- **C**: [Algorithms in C, Parts 1-5 (Bundle), 3rd Edition](https://www.amazon.com/Algorithms-Parts-1-5-Bundle-Fundamentals/dp/0201756080)
- **Java**: [Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Michael-Goodrich/dp/1118771338/) — Goodrich, Tamassia, Goldwasser
- **C++**: [Data Structures and Algorithms in C++, 2nd Edition](https://www.amazon.com/Data-Structures-Algorithms-Michael-Goodrich/dp/0470383275) — Goodrich, Tamassia, Mount
**[⬆ back to top](#table-of-contents)**

## Interview Prep Books

Here are some recommended books to supplement your learning.

- [Coding Interview Patterns: Nail Your Next Coding Interview](https://geni.us/q7svoz)

- [Programming Interviews Exposed: Coding Your Way Through the Interview, 4th Edition](https://www.amazon.com/Programming-Interviews-Exposed-Through-Interview/dp/111941847X/)
    - Answers in C++ and Java
    - This is a good warm-up for Cracking the Coding Interview
    - Not too difficult. Most problems may be easier than what you'll see in an interview (from what I've read)

- [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - answers in Java

### If you have tons of extra time:

Choose one:

- [Elements of Programming Interviews (C++ version)](https://www.amazon.com/Elements-Programming-Interviews-Insiders-Guide/dp/1479274836)
- [Elements of Programming Interviews in Python](https://www.amazon.com/Elements-Programming-Interviews-Python-Insiders/dp/1537713949/)
- [Elements of Programming Interviews (Java version)](https://www.amazon.com/Elements-Programming-Interviews-Java-Insiders/dp/1517435803/)
        - [Companion Project - Method Stub and Test Cases for Every Problem in the Book](https://github.com/gardncl/elements-of-programming-interviews)

**[⬆ back to top](#table-of-contents)**

## Don't Make My Mistakes

This list grew over many months, and yes, it got out of hand.

Here are some mistakes I made so you'll have a better experience. And you'll save months of time.

### 1. You Won't Remember it All

I watched hours of videos and took copious notes, and months later there was much I didn't remember. I spent 3 days going
through my notes and making flashcards, so I could review. I didn't need all of that knowledge.

Please, read so you won't make my mistakes:

[Retaining Computer Science Knowledge](https://startupnextdoor.com/retaining-computer-science-knowledge/).

### 2. Use Flashcards

To solve the problem, I made a little flashcard site where I could add flashcards of 2 types: general and code.
Each card has a different formatting. I made a mobile-first website, so I could review on my phone or tablet, wherever I am.

Make your own for free:

- [Flashcards site repo](https://github.com/jwasham/computer-science-flash-cards)

**I DON'T RECOMMEND using my flashcards.** There are too many and most of them are trivia that you don't need.

But if you don't want to listen to me, here you go:
- [My flash cards database (1200 cards)](https://github.com/jwasham/computer-science-flash-cards/blob/main/cards-jwasham.db):
- [My flash cards database (extreme - 1800 cards)](https://github.com/jwasham/computer-science-flash-cards/blob/main/cards-jwasham-extreme.db):

Keep in mind I went overboard and have cards covering everything from assembly language and Python trivia to machine learning and statistics.
It's way too much for what's required.

**Note on flashcards:** The first time you recognize you know the answer, don't mark it as known. You have to see the
same card and answer it several times correctly before you really know it. Repetition will put that knowledge deeper in
your brain.

An alternative to using my flashcard site is [Anki](http://ankisrs.net/), which has been recommended to me numerous times.
It uses a repetition system to help you remember. It's user-friendly, available on all platforms, and has a cloud sync system.
It costs $25 on iOS but is free on other platforms.

My flashcard database in Anki format: https://ankiweb.net/shared/info/25173560 (thanks [@xiewenya](https://github.com/xiewenya)).

Some students have mentioned formatting issues with white space that can be fixed by doing the following: open the deck, edit the card, click cards, select the "styling" radio button, and add the member "white-space: pre;" to the card class.

### 3. Do Coding Interview Questions While You're Learning

THIS IS VERY IMPORTANT.

Start doing coding interview questions while you're learning data structures and algorithms.

You need to apply what you're learning to solve problems, or you'll forget. I made this mistake.

Once you've learned a topic, and feel somewhat comfortable with it, for example, **linked lists**:
1. Open one of the [coding interview books](#interview-prep-books) (or coding problem websites, listed below)
1. Do 2 or 3 questions regarding linked lists.
1. Move on to the next learning topic.
1. Later, go back and do another 2 or 3 linked list problems.
1. Do this with each new topic you learn.

**Keep doing problems while you're learning all this stuff, not after.**

You're not being hired for knowledge, but how you apply the knowledge.

There are many resources for this, listed below. Keep going.

### 4. Focus

There are a lot of distractions that can take up valuable time. Focus and concentration are hard. Turn on some music
without lyrics and you'll be able to focus pretty well.

**[⬆ back to top](#table-of-contents)**

## What you won't see covered

These are prevalent technologies but not part of this study plan:

- JavaScript, HTML, CSS, and other front-end technologies
- SQL and relational databases (important, but a separate path)
- Low-level C/assembly programming and pointer arithmetic (useful background, but not what AI Engineer interviews test — see optional CS Background appendix)

What this guide *does* emphasize instead of low-level C:
- Python and the ML ecosystem (NumPy, pandas, scikit-learn, PyTorch)
- ML system design and production AI infrastructure

**[⬆ back to top](#table-of-contents)**

## The Daily Plan

This course goes over a lot of subjects. Each will probably take you a few days, or maybe even a week or more. It depends on your schedule.

Each day, take the next subject in the list, watch some videos about that subject, and then write an implementation
of that data structure or algorithm in the language you chose for this course.

You can see my code here:
 - [C](https://github.com/jwasham/practice-c)
 - [C++](https://github.com/jwasham/practice-cpp)
 - [Python](https://github.com/jwasham/practice-python)

You don't need to memorize every algorithm. You just need to be able to understand it enough to be able to write your own implementation.

**[⬆ back to top](#table-of-contents)**

## Coding Question Practice

    Why is this here? I'm not ready to interview.

[Then go back and read this.](#3-do-coding-interview-questions-while-youre-learning)

Why you need to practice doing programming problems:
- Problem recognition, and where the right data structures and algorithms fit in
- Gathering requirements for the problem
- Talking your way through the problem like you will in the interview
- Coding on a whiteboard or paper, not a computer
- Coming up with time and space complexity for your solutions (see Big-O below)
- Testing your solutions

There is a great intro for methodical, communicative problem-solving in an interview. You'll get this from the programming
interview books, too, but I found this outstanding:
[Algorithm design canvas](http://www.hiredintech.com/algorithm-design/)

Write code on a whiteboard or paper, not a computer. Test with some sample inputs. Then type it and test it out on a computer.

If you don't have a whiteboard at home, pick up a large drawing pad from an art store. You can sit on the couch and practice.
This is my "sofa whiteboard". I added the pen in the photo just for scale. If you use a pen, you'll wish you could erase.
Gets messy quickly. **I use a pencil and eraser.**

![my sofa whiteboard](https://d3j2pkmjtin6ou.cloudfront.net/art_board_sm_2.jpg)

**Coding question practice is not about memorizing answers to programming problems.**

**[⬆ back to top](#table-of-contents)**

## Coding Problems

Don't forget your key coding interview books [here](#interview-prep-books).

Solving Problems:
- [How to Find a Solution](https://www.topcoder.com/thrive/articles/How%20To%20Find%20a%20Solution)
- [How to Dissect a Topcoder Problem Statement](https://www.topcoder.com/thrive/articles/How%20To%20Dissect%20a%20Topcoder%20Problem%20Statement%20Content)

Coding Interview Question Videos:
- [IDeserve (88 videos)](https://www.youtube.com/playlist?list=PLamzFoFxwoNjPfxzaWqs7cZGsPYy0x_gI)
- [Tushar Roy (5 playlists)](https://www.youtube.com/user/tusharroy2525/playlists?shelf_id=2&view=50&sort=dd)
    - Super for walkthroughs of problem solutions
- [Nick White - LeetCode Solutions (187 Videos)](https://www.youtube.com/playlist?list=PLU_sdQYzUj2keVENTP0a5rdykRSgg9Wp-)
    - Good explanations of the solution and the code
    - You can watch several in a short time
- [FisherCoder - LeetCode Solutions](https://youtube.com/FisherCoder)

Challenge/Practice sites:
- [LeetCode](https://leetcode.com/)
    - My favorite coding problem site. It's worth the subscription money for the 1-2 months you'll likely be preparing.
    - See Nick White and FisherCoder Videos above for code walk-throughs.
- [HackerRank](https://www.hackerrank.com/)
- [TopCoder](https://www.topcoder.com/)
- [Codeforces](https://codeforces.com/)
- [Codility](https://codility.com/programmers/)
- [Geeks for Geeks](https://practice.geeksforgeeks.org/explore/?page=1)
- [AlgoExpert](https://www.algoexpert.io/product)
    - Created by Google engineers, this is also an excellent resource to hone your skills.
- [Project Euler](https://projecteuler.net/)
    - very math-focused, and not really suited for coding interviews

**AI/ML-specific practice sites:**
- [Kaggle](https://www.kaggle.com/) — ML competitions and free datasets; a Kaggle rank is a strong portfolio signal
- [HuggingFace Spaces](https://huggingface.co/spaces) — hands-on model experimentation and demos
- [StrataScratch](https://www.stratascratch.com/) — SQL and ML interview problems from real companies
- [LeetCode — Matrix / DP for sequence models](https://leetcode.com/tag/matrix/) — practice matrix operations and DP patterns relevant to ML algorithms

**[⬆ back to top](#table-of-contents)**

---

## Track A: AI-native Builder

> **🏗️ Who this is for:** Product engineers, technical founders, and full-stack developers who use AI tools as their primary development accelerant. You build with AI, not just alongside it.

> *"We may be approaching a moment where a single talented engineer — armed with the right AI tools — can build what used to require an entire team. The one-person startup is becoming the one-person unicorn."*
>
> — **Sam Altman**, CEO of OpenAI, 2024

The AI-native Builder ships products. They wield AI coding assistants fluently, think in system architectures, design for users, and iterate fast. This track is about **leverage** — how a single builder with AI tools can do what used to require a team.

---

### AI Coding Tools & Vibe Coding Workflows

> *"There's a new kind of coding I call 'vibe coding' — where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's a different skill: directing intelligence rather than writing instructions."*
>
> — **Andrej Karpathy**, February 2025

"Vibe coding" — prompting an AI to generate large swaths of code while you steer direction — is a real and powerful technique when done with discipline. The key is maintaining a clear mental model of the system even as AI generates the implementation.

**AI Coding Assistants:**
- [ ] [GitHub Copilot](https://github.com/features/copilot) — integrated into VS Code, JetBrains, Neovim; best for in-editor autocomplete and chat
    - [ ] [GitHub Copilot Docs: Best Practices](https://docs.github.com/en/copilot/using-github-copilot/best-practices-for-using-github-copilot)
- [ ] [Claude Code (Anthropic)](https://claude.ai/code) — agentic coding assistant that operates in your terminal; excellent at large refactors and multi-file tasks
    - [ ] [Claude Code documentation](https://docs.anthropic.com/en/docs/claude-code/overview)
    - Strengths: long context, follows complex instructions, strong at system design reasoning
- [ ] [Cursor](https://www.cursor.com/) — VS Code fork with deep AI integration; `.cursorrules` for project-level context
    - [ ] [Cursor docs: Context management](https://docs.cursor.com/)
- [ ] [Windsurf (Codeium)](https://codeium.com/windsurf) — agentic IDE with Cascade multi-file editing
- [ ] [Aider](https://aider.chat/) — open-source AI pair programmer in your terminal; integrates with any model
- [ ] [Antigravity](https://www.antigravity.dev/) — AI-powered development environment for building full-stack AI apps
- [ ] [Bolt.new](https://bolt.new/) / [v0 (Vercel)](https://v0.dev/) — generate full-stack web apps from a prompt

**Effective vibe coding practices:**
- [ ] Always start with a written spec before prompting — AI output quality is proportional to input clarity
- [ ] Use a CLAUDE.md / .cursorrules / AGENTS.md file to encode project conventions into every session
- [ ] Review every AI-generated change at the diff level — never merge code you haven't read
- [ ] Ask AI to explain its reasoning, not just write code — "explain what you changed and why"
- [ ] Use AI for scaffolding, boilerplate, and repetitive patterns; write critical business logic yourself
- [ ] Version control with small, frequent commits — makes it easy to revert AI mistakes

**Resources:**
- [ ] [How to use Claude Code effectively (Anthropic blog)](https://www.anthropic.com/engineering/claude-code-best-practices)
- [ ] [Prompt Engineering for Developers — deeplearning.ai (free)](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- [ ] [The Pragmatic AI Engineer (book)](https://pragprog.com/) — practical AI-assisted development

**[⬆ back to top](#table-of-contents)**

---

### Product Engineering with AI

Product engineers translate user needs into shipped software. In the AI era, this means knowing how to evaluate whether an AI feature actually solves a user problem — not just whether it technically works.

**Product thinking fundamentals:**
- [ ] [Shape Up (Basecamp — free)](https://basecamp.com/shapeup) — how to scope and pitch product work
- [ ] [Continuous Discovery Habits (Teresa Torres)](https://www.producttalk.org/continuous-discovery-habits/) — building a habit of user research
- [ ] Writing clear product specs: user story → acceptance criteria → technical design
- [ ] [The Product-Led Playbook (Kyle Poyar)](https://www.openviewpartners.com/product-led-growth/) — growth through product

**Designing AI features:**
- [ ] Identifying where AI adds value vs. where deterministic logic is better
- [ ] Handling AI uncertainty: confidence scores, fallbacks, graceful degradation
- [ ] Latency and UX: streaming responses, skeleton loading, optimistic UI
- [ ] Setting user expectations: when to show "AI-generated" labels
- [ ] Evaluation before launch: evaluating LLM output quality with golden test sets
- [ ] A/B testing AI features: metrics that matter (task completion rate, not just engagement)

**Building with LLM APIs:**
- [ ] [OpenAI API quickstart](https://platform.openai.com/docs/quickstart)
- [ ] [Anthropic API docs](https://docs.anthropic.com/)
- [ ] [Google Gemini API](https://ai.google.dev/docs)
- [ ] Structured outputs / JSON mode — reliable LLM output for downstream processing
- [ ] Function calling / tool use — connecting LLMs to real-world actions
- [ ] Rate limiting, retry logic, cost management in production

**[⬆ back to top](#table-of-contents)**

---

### Systems Architecture for AI Products

AI-native products have architectural patterns distinct from traditional web apps. Understanding these patterns is how you make smart technical decisions before writing a single line of code.

**Core AI product architecture patterns:**
- [ ] **LLM + RAG pattern**: retrieval-augmented generation as a first-class architectural component
    - Embedding pipeline, vector store, retrieval, re-ranking, generation
- [ ] **Agentic loop pattern**: LLM + tool calls + memory + planning in a feedback loop
- [ ] **Human-in-the-loop pattern**: where to insert human review checkpoints
- [ ] **Cascade pattern**: cheap/fast model for initial filter → expensive model only when needed
- [ ] **Offline + online split**: batch processing for non-real-time tasks; streaming for UX

**Architecture decision skills:**
- [ ] When to use a hosted API vs. self-hosted model (cost, latency, data privacy)
- [ ] Stateless vs. stateful LLM sessions: session memory, conversation history management
- [ ] Designing for observability: logging LLM inputs/outputs, tracing multi-step pipelines
- [ ] Idempotency and retries in LLM pipelines: handling non-determinism gracefully
- [ ] Schema design for AI-generated content: storing, versioning, and auditing outputs

**Architectural thinking resources:**
- [ ] [System Design Primer](https://github.com/donnemartin/system-design-primer) — foundational system design
- [ ] [Building LLM Applications for Production (Chip Huyen)](https://huyenchip.com/2023/04/11/llm-engineering.html)
- [ ] [LLM App Stack (a16z)](https://a16z.com/emerging-architectures-for-llm-applications/) — map of the LLM application ecosystem
- [ ] [Emerging Architectures for LLM Applications](https://a16z.com/emerging-architectures-for-llm-applications/)

**[⬆ back to top](#table-of-contents)**

---

### Orchestrating AI: Prompting, RAG & Agents for Builders

This is the practical side of working with LLMs in production — beyond the playground.

**Prompt engineering for products:**
- [ ] System prompt design: role, context, constraints, output format
- [ ] Few-shot examples in system prompts for consistent behavior
- [ ] Prompt versioning and change management
- [ ] Guardrails: input/output validation, content moderation, PII detection
- [ ] [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [ ] [Anthropic Prompt Library](https://docs.anthropic.com/en/prompt-library/)

**RAG for builders:**
- [ ] [LangChain quickstart](https://python.langchain.com/docs/get_started/quickstart) — the most popular RAG framework
- [ ] [LlamaIndex quickstart](https://docs.llamaindex.ai/en/stable/getting_started/starter_example/) — document-centric RAG
- [ ] Embedding models: OpenAI `text-embedding-3-small`, Cohere Embed, open-source (all-MiniLM, BGE)
- [ ] Vector stores for builders: Pinecone (managed), Chroma (local dev), pgvector (Postgres extension)
- [ ] Evaluating RAG quality: context recall, answer faithfulness, answer relevance

**Agent frameworks for builders:**
- [ ] [LangGraph](https://langchain-ai.github.io/langgraph/) — graph-based agent orchestration
- [ ] [OpenAI Assistants API](https://platform.openai.com/docs/assistants/overview) — managed agent with threads and tools
- [ ] [Anthropic's tool use guide](https://docs.anthropic.com/en/docs/tool-use)
- [ ] [CrewAI](https://github.com/joaomdmoura/crewAI) — multi-agent collaboration framework

**[⬆ back to top](#table-of-contents)**

---

### Shipping AI Products: Cloud, APIs & Observability

Building is 20% of the work. Shipping and keeping it running is 80%.

**Deployment basics:**
- [ ] [Vercel](https://vercel.com/docs) — easiest deployment for web AI apps (supports Python backends)
- [ ] [Railway](https://railway.app/) — easy cloud deployment for backend services
- [ ] [Fly.io](https://fly.io/docs/) — low-latency global edge deployment
- [ ] Docker + Docker Compose — containerize your AI app for consistent deployments
- [ ] Environment variables and secrets management — never hard-code API keys

**API design for AI products:**
- [ ] [FastAPI](https://fastapi.tiangolo.com/) — Python-native, async-first REST API framework
- [ ] Streaming responses: Server-Sent Events (SSE) for real-time LLM output
- [ ] Webhooks for async AI tasks (long-running inference)
- [ ] Rate limiting, API keys, and basic auth

**Observability for LLM apps:**
- [ ] [LangSmith](https://smith.langchain.com/) — tracing and evaluation for LangChain apps
- [ ] [Langfuse](https://langfuse.com/) — open-source LLM observability (traces, evals, cost tracking)
- [ ] [Arize Phoenix](https://phoenix.arize.com/) — open-source AI observability
- [ ] Logging LLM calls: what to log (prompt, completion, tokens, latency, model version, user id)
- [ ] Cost monitoring: tracking per-user, per-feature LLM API spend

**[⬆ back to top](#table-of-contents)**

---

## Track B: AI Engineer (Deep Technical)

> **🔬 Who this is for:** Engineers who want to build and own AI systems from the ground up — training, fine-tuning, data pipelines, and production model infrastructure. These roles exist at AI research labs and AI-first product companies.

> *"We may be approaching a moment where AI systems can perform the work of a brilliant PhD — advancing science, curing diseases, and driving economic growth at a pace we can barely imagine. The engineers who build these systems will be the most important people in the world."*
>
> — **Dario Amodei**, CEO of Anthropic, *"Machines of Loving Grace"* (2024)

> *"Just as electricity transformed almost everything 100 years ago, today I have a hard time thinking of an industry that AI will not transform in the next several years. The engineers who understand AI from the inside will lead that transformation."*
>
> — **Andrew Ng**, Founder of deeplearning.ai

The AI Engineer goes deeper than the Builder. They don't just call an API — they train the model behind it. They design data pipelines that produce training sets, run fine-tuning experiments, distill large models into smaller deployable ones, and architect the agentic systems that the Builder's products rely on.

---

### Agentic AI Systems

Modern AI products are increasingly *agentic* — models that reason over multiple steps, use tools, maintain memory, and collaborate with other agents to complete long-horizon tasks. Designing these systems requires deep understanding of failure modes, reliability patterns, and evaluation strategies.

**Agentic architecture fundamentals:**
- [ ] The agentic loop: Observe → Think → Act → Observe → ... (the core ReAct cycle)
- [ ] Tool use and function calling: schema design, error handling, tool selection
- [ ] Planning strategies:
    - [ ] ReAct (Reasoning + Acting): interleaved thinking and action
    - [ ] Plan-and-execute: upfront planning, then sequential execution
    - [ ] Tree of Thought: branching exploration for complex reasoning tasks
    - [ ] Reflection / self-critique: having the agent evaluate and revise its own output
- [ ] Memory architectures:
    - [ ] In-context (working memory): what fits in the context window
    - [ ] External memory: vector store for episodic memory, key-value for structured facts
    - [ ] Summarization memory: compress old context to extend effective memory
- [ ] Multi-agent systems:
    - [ ] Orchestrator–subagent patterns: a supervisor assigns tasks to specialist agents
    - [ ] Peer collaboration: agents critique each other's outputs
    - [ ] Parallelism: running independent subtasks concurrently
    - [ ] Communication protocols: how agents pass structured messages

**Reliability and safety for agents:**
- [ ] Error recovery: what to do when a tool call fails or returns unexpected output
- [ ] Infinite loop detection and maximum step limits
- [ ] Human-in-the-loop checkpoints: when to pause and ask for confirmation
- [ ] Sandboxing code execution agents: security implications of letting an LLM run code
- [ ] Evaluation: measuring task completion rate, not just individual step quality

**Resources:**
- [ ] [LangGraph documentation](https://langchain-ai.github.io/langgraph/) — stateful, cyclical agent graphs
- [ ] [AutoGen (Microsoft)](https://microsoft.github.io/autogen/) — multi-agent conversation framework
- [ ] [Agents course — HuggingFace (free)](https://huggingface.co/learn/agents-course/)
- [ ] [OpenAI Assistants and function calling docs](https://platform.openai.com/docs/assistants/overview)
- [ ] ["Building Effective Agents" (Anthropic blog)](https://www.anthropic.com/research/building-effective-agents)

**[⬆ back to top](#table-of-contents)**

---

### LLM Fine-tuning in Depth

Fine-tuning is the process of adapting a pre-trained model to a specific task or style using curated examples. Understanding this deeply — including when NOT to fine-tune — separates AI Engineers from API callers.

**When to fine-tune (and when not to):**
- [ ] Fine-tune when: consistent style/tone, domain-specific vocabulary, reducing prompt length at scale, improved latency vs. few-shot prompting
- [ ] Don't fine-tune when: adding new knowledge (use RAG), one-off tasks, insufficient data

**Full fine-tuning:**
- [ ] Supervised Fine-Tuning (SFT): input–output pairs on instruction-following datasets
- [ ] Dataset format: instruction/response pairs, system prompts, conversation threads
- [ ] Training infrastructure: multi-GPU setup, gradient checkpointing, mixed precision (bf16/fp16)
- [ ] Compute requirements: approximate VRAM needs by model size

**Parameter-Efficient Fine-Tuning (PEFT) — go deep here:**
- [ ] LoRA (Low-Rank Adaptation):
    - Why it works: weight updates lie in a low-rank subspace
    - Hyperparameters: rank (r), alpha (α), target modules
    - Merging LoRA weights back into the base model for inference
- [ ] QLoRA: 4-bit quantization (NF4) of the base model + LoRA adapters on top
    - Enables fine-tuning 70B models on a single A100
    - [QLoRA paper (Dettmers et al. 2023)](https://arxiv.org/abs/2305.14314)
- [ ] Prefix tuning and prompt tuning — learnable soft prompts prepended to input
- [ ] IA³ (Infused Adapter by Inhibiting and Amplifying Inner Activations)

**Alignment fine-tuning:**
- [ ] RLHF (Reinforcement Learning from Human Feedback):
    - Step 1: SFT on demonstration data
    - Step 2: Train a reward model on pairwise preference data
    - Step 3: PPO to optimize the policy toward the reward model
- [ ] DPO (Direct Preference Optimization): bypasses the reward model; train directly on preference pairs
    - [DPO paper (Rafailov et al. 2023)](https://arxiv.org/abs/2305.18290)
- [ ] ORPO, SimPO: newer alignment methods with fewer hyperparameters

**Tooling:**
- [ ] [HuggingFace TRL (Transformers Reinforcement Learning)](https://huggingface.co/docs/trl/) — SFT, DPO, PPO in one library
- [ ] [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) — YAML-configured fine-tuning for LLMs
- [ ] [LlamaFactory](https://github.com/hiyouga/LLaMA-Factory) — unified fine-tuning framework
- [ ] [Unsloth](https://github.com/unslothai/unsloth) — 2x faster fine-tuning with less VRAM

**[⬆ back to top](#table-of-contents)**

---

### Knowledge Distillation

Distillation trains a smaller *student* model to mimic a larger *teacher* model. The goal is to transfer capability into a model cheap enough to deploy at scale. This is a core technique at every AI company with inference cost pressure.

**Types of distillation:**
- [ ] **Response distillation (black-box):** train the student on outputs generated by the teacher
    - Collect teacher completions on a diverse prompt distribution
    - Fine-tune the student with SFT on teacher-generated data
    - Simple to implement; widely used (Alpaca, Vicuna, Orca were built this way)
- [ ] **Feature distillation (white-box):** student learns to match the teacher's internal representations
    - Match intermediate hidden states, attention maps, or logits
    - Requires access to teacher internals (open weights models like LLaMA, Mistral)
    - Approaches: KD loss = cross-entropy(student logits, teacher soft labels) + task loss
- [ ] **Speculative decoding:** use a small draft model to generate candidate tokens, teacher verifies — not distillation per se, but related inference optimization
- [ ] **Self-distillation:** the model distills knowledge from its own larger outputs (chain-of-thought → direct answer)

**Training signal choices:**
- [ ] Hard labels vs. soft labels (temperature-scaled logits)
- [ ] KL divergence as the distillation loss
- [ ] Calibration: ensuring the student's confidence is well-calibrated, not just accurate

**Practical considerations:**
- [ ] Distribution mismatch: teacher and student may have different tokenizers
- [ ] Capacity gap: very small students may fail to absorb large teacher knowledge
- [ ] Data diversity: distillation quality is limited by the prompt distribution you sample

**Resources:**
- [ ] [Distilling Step-by-Step (Hsieh et al., 2023)](https://arxiv.org/abs/2212.10535) — distilling rationales, not just labels
- [ ] [Orca: Progressive Learning from Complex Explanation Traces of GPT-4](https://arxiv.org/abs/2306.02707)
- [ ] [HuggingFace TRL — KTO and DPO trainers](https://huggingface.co/docs/trl/) — includes distillation utilities

**[⬆ back to top](#table-of-contents)**

---

### Data Collection & Curation

The quality of your training data determines the ceiling of your model. "Data-centric AI" — the practice of improving models by improving data rather than changing architecture — is now mainstream at every serious AI lab.

**Data collection strategies:**
- [ ] **Web scraping at scale:** Common Crawl, scrapy, playwright for JS-heavy sites; robots.txt compliance
- [ ] **Crowdsourcing:** Amazon Mechanical Turk, Scale AI, Appen — for human-labeled data
- [ ] **Expert annotation:** domain experts (medical, legal, code) for high-quality niche datasets
- [ ] **Programmatic labeling:** [Snorkel](https://snorkel.ai/) — weak supervision with labeling functions
- [ ] **Self-supervised signals:** using the data structure itself as a label (next token, masked token)
- [ ] **Feedback loops:** collecting implicit signals (clicks, edits, thumbs up/down) from deployed products

**Data curation and quality:**
- [ ] Deduplication: exact dedup (hashing), near-dedup (MinHash/LSH), semantic dedup (embedding similarity)
- [ ] Quality filtering: perplexity filtering, classifier-based filtering, heuristic rules (length, punctuation ratio)
- [ ] Toxicity and PII filtering: off-the-shelf classifiers, regex patterns, named entity redaction
- [ ] Data mixture and weighting: how to balance sources (web data vs. books vs. code vs. conversations)
- [ ] Dataset documentation: data cards, model cards — provenance and licensing

**Data formats for LLM training:**
- [ ] Pre-training: raw text corpora (The Pile, RedPajama, DCLM), packed sequences
- [ ] Instruction tuning: ShareGPT format, Alpaca format, OpenAI chat format
- [ ] Preference data: pairwise comparison format (chosen/rejected), Bradley-Terry model

**Tools and datasets:**
- [ ] [Argilla](https://argilla.io/) — open-source data annotation and curation platform
- [ ] [Label Studio](https://labelstud.io/) — flexible annotation tool for any data type
- [ ] [HuggingFace Datasets](https://huggingface.co/docs/datasets/) — library + hub for ML datasets
- [ ] [DataComp](https://www.datacomp.ai/) — benchmark for data curation pipelines
- [ ] [The Pile](https://pile.eleuther.ai/) — diverse open-source pre-training corpus
- [ ] [OpenHermes](https://huggingface.co/datasets/teknium/OpenHermes-2.5) — large instruction-tuning dataset

**[⬆ back to top](#table-of-contents)**

---

### Synthetic Data Generation

When real data is scarce, expensive to label, or sensitive, synthetic data is the answer. Modern AI labs generate billions of synthetic training examples to complement human-curated data.

**Why synthetic data:**
- [ ] Augmenting rare classes or edge cases in training distributions
- [ ] Generating instruction-following data without human annotators
- [ ] Privacy-preserving: generating statistically similar data without real user data
- [ ] Scaling data for distillation: teacher model generates completions for student training

**Techniques:**

*LLM-based generation:*
- [ ] Prompt an LLM to generate Q&A pairs, instructions, chain-of-thought reasoning traces
- [ ] Self-instruct: use the LLM to generate its own training data from a small seed set
    - [ ] [Self-Instruct paper (Wang et al., 2022)](https://arxiv.org/abs/2212.09561)
- [ ] Persona-driven generation: generate diverse data by varying the persona in the prompt
- [ ] Backtranslation: generate questions from answers, instructions from solutions
- [ ] Constitutional AI (CAI): use a model to critique and revise its own outputs iteratively
    - [ ] [Constitutional AI paper (Anthropic, 2022)](https://arxiv.org/abs/2212.08073)

*Code and structured data:*
- [ ] Generating code with tests: generate function + unit tests, verify with a code executor
- [ ] Math problem generation: template-based generation + symbolic solvers for verification
- [ ] Schema-constrained generation: use JSON schema or grammar constraints for structured output

*Quality control for synthetic data:*
- [ ] Reward model filtering: score synthetic examples with a trained reward model; keep top-k
- [ ] Consistency checks: verify generated answers against ground truth (for math, code)
- [ ] Diversity sampling: embedding-based deduplication to avoid repetitive patterns
- [ ] Human spot-checking: random sample audits before adding to training set

**Resources:**
- [ ] [Phi-1 (Microsoft)](https://arxiv.org/abs/2306.11644) — "textbooks are all you need"; high-quality synthetic code
- [ ] [Magpie: Alignment Data Synthesis from Scratch (2024)](https://arxiv.org/abs/2406.08464) — generating preference data at scale
- [ ] [DataDreamer](https://datadreamer.dev/) — Python library for programmatic dataset generation with LLMs
- [ ] [Evol-Instruct](https://arxiv.org/abs/2304.12244) — evolving instructions to increase complexity (WizardLM)

**[⬆ back to top](#table-of-contents)**

---

In the AI era, the way software is built has fundamentally changed. AI Engineers are expected to work with **Spec-Driven Development** — defining what needs to be built precisely (in natural language or structured specs) before writing a single line of code, then using AI tools to accelerate implementation. This mirrors how senior engineers think: design first, code second.

### What is Spec-Driven Development?

Spec-Driven Development means writing a clear, detailed specification of the system — its inputs, outputs, edge cases, and acceptance criteria — **before** implementation begins. AI coding assistants (GitHub Copilot, Cursor, Claude, etc.) work best when given precise specs.

- [ ] [Specification by Example (Martin Fowler)](https://martinfowler.com/bliki/SpecificationByExample.html)
- [ ] [What is Spec-Driven Development?](https://blog.stoplight.io/spec-driven-development)
- [ ] [Writing Good Technical Specifications (video)](https://www.youtube.com/watch?v=a2n0XQa0OLw)
- [ ] [How to Write a Technical Design Doc](https://medium.com/machine-words/writing-technical-design-docs-71f446e42f2e)
- [ ] [RFC-style documents: How Big Tech teams design before coding](https://www.industrialempathy.com/posts/design-docs-at-google/)

### AI-native SDLC Stages

The modern AI Engineer SDLC differs from traditional waterfall or agile:

1. **Problem Definition** — Frame the problem clearly. What is the desired outcome? Who are the users?
2. **Spec Writing** — Write a structured specification (user stories, data contracts, API schema, acceptance tests).
3. **AI-Assisted Design** — Use LLMs to generate architecture proposals, data models, and pseudocode from specs.
4. **AI-Assisted Implementation** — Use AI coding tools (Copilot, Cursor, Aider) for code generation; review every output critically.
5. **Testing & Validation** — AI-generated tests + human review. Always verify AI output against the original spec.
6. **Iteration** — Short cycles; update the spec when requirements change, not just the code.

- [ ] [How to Use GitHub Copilot Effectively (official guide)](https://docs.github.com/en/copilot/using-github-copilot/best-practices-for-using-github-copilot)
- [ ] [Prompt Engineering for Developers - deeplearning.ai (free course)](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- [ ] [Cursor AI Editor - Getting Started](https://www.cursor.com/docs)
- [ ] [Aider: AI pair programming in your terminal](https://aider.chat/)
- [ ] [Software Engineering with AI: Practical Tips (video)](https://www.youtube.com/watch?v=fjHtjT7GO1c)

### Test-Driven Development (TDD) + AI

TDD is even more powerful in the AI era: write tests first, then let AI write the implementation.

- [ ] [Test-Driven Development: By Example (Kent Beck)](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
- [ ] [TDD with AI coding assistants (video)](https://www.youtube.com/watch?v=Jv2uxzhPFl4)
- [ ] [pytest for Python — official docs](https://docs.pytest.org/en/stable/)

### Version Control Workflows

- [ ] [Git Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
- [ ] [Conventional Commits specification](https://www.conventionalcommits.org/)
- [ ] [Writing good commit messages](https://cbea.ms/git-commit/)

**[⬆ back to top](#table-of-contents)**

---

## Work Environment & Portfolio Building

AI Engineers are judged as much on **what they have built** as on what they know. A strong portfolio demonstrating real projects, clean code, and deployed applications matters enormously. This section covers the essential work environment and portfolio skills.

### Git & GitHub

Mastery of Git and GitHub is non-negotiable. Interviewers look at your GitHub profile.

- [ ] [Git - The Simple Guide](https://rogerdudler.github.io/git-guide/)
- [ ] [Pro Git Book (free, official)](https://git-scm.com/book/en/v2)
- [ ] [Learn Git Branching (interactive)](https://learngitbranching.js.org/)
- [ ] [GitHub Skills — official interactive courses](https://skills.github.com/)
- [ ] [GitHub Actions — CI/CD basics](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
- [ ] [GitHub Copilot — setup and usage](https://docs.github.com/en/copilot/quickstart)
- [ ] [How to contribute to open source](https://opensource.guide/how-to-contribute/)

#### Practical exercises:
- [ ] Create a GitHub profile README showcasing your skills and projects
- [ ] Contribute a pull request to any open-source project (even documentation)
- [ ] Set up a GitHub Actions workflow for a project (lint, test, deploy)

### Development Environment & Tooling

- [ ] [Visual Studio Code — getting started](https://code.visualstudio.com/docs/introvideos/basics)
- [ ] [VS Code for Python](https://code.visualstudio.com/docs/python/python-tutorial)
- [ ] [Docker for Developers (free course)](https://www.youtube.com/watch?v=fqMOX6JJhGo)
- [ ] [Dev Containers in VS Code](https://code.visualstudio.com/docs/devcontainers/containers)
- [ ] [Virtual environments in Python (venv, conda)](https://realpython.com/python-virtual-environments-a-primer/)
- [ ] [Makefile tutorial for project automation](https://makefiletutorial.com/)
- [ ] [Linux command line basics (free LabEx tutorial)](https://labex.io/tutorials/practice-linux-commands-hands-on-labs-398420)

### Full-Stack Development Basics

AI Engineers increasingly need to wrap their models in usable applications. You don't need to be a full-stack expert, but you need enough to ship demos and prototypes.

**Backend / APIs:**
- [ ] [FastAPI tutorial (Python — build REST APIs quickly)](https://fastapi.tiangolo.com/tutorial/)
- [ ] [RESTful API design best practices](https://restfulapi.net/)
- [ ] [Flask for Machine Learning APIs (real-world tutorial)](https://towardsdatascience.com/deploying-a-machine-learning-model-as-a-rest-api-4a03b865c166)

**Frontend / UI for AI apps:**
- [ ] [Streamlit — build data apps in Python (official tutorial)](https://docs.streamlit.io/get-started)
- [ ] [Gradio — ML demo UIs in minutes](https://www.gradio.app/guides/quickstart)
- [ ] [Next.js basics (if you want a proper web frontend)](https://nextjs.org/learn)

**Databases:**
- [ ] [SQL basics — Mode Analytics tutorial](https://mode.com/sql-tutorial/)
- [ ] [SQLite + Python quickstart](https://docs.python.org/3/library/sqlite3.html)
- [ ] [PostgreSQL for beginners](https://www.postgresqltutorial.com/)
- [ ] [Vector databases explained (Pinecone)](https://www.pinecone.io/learn/vector-database/)

### Building & Showcasing Your Portfolio

> *"AI hiring managers aren't just looking at your degree — they're looking at what you've built, what you've deployed, and what problems you've solved. Your GitHub is your proof of work."*
>
> — **Chip Huyen**, ML engineer, author of *Designing Machine Learning Systems*

> *"Don't just study AI. Build with it. Ship something real. A deployed project — however small — demonstrates judgment, persistence, and skill that no résumé line can."*
>
> — **Andrew Ng**, Founder of deeplearning.ai

- [ ] [How to build a compelling data science / AI portfolio](https://towardsdatascience.com/how-to-build-a-data-science-portfolio-5f566517c79c)
- [ ] [Building AI portfolio projects that get noticed (video)](https://www.youtube.com/watch?v=1aXk2RViq3c)
- [ ] [Writing a great project README](https://www.makeareadme.com/)
- [ ] [HuggingFace Spaces — deploy and share your ML models for free](https://huggingface.co/spaces)
- [ ] [Vercel — deploy web apps for free](https://vercel.com/docs)

#### Suggested portfolio project ideas:
- [ ] End-to-end ML pipeline: data → model → REST API → simple UI
- [ ] RAG (Retrieval-Augmented Generation) chatbot over a custom document set
- [ ] Fine-tuned open-source LLM for a specific domain
- [ ] Real-time data dashboard with cloud storage backend
- [ ] CLI or web tool that automates a tedious task using an LLM

**[⬆ back to top](#table-of-contents)**

---

## System Thinking & Software Architecture

In the AI era, even freshers are expected to think architecturally. Companies want engineers who can reason about entire systems — not just write functions. This section trains you to think like a senior architect from day one.

### Architectural Thinking

- [ ] [Fundamentals of Software Architecture (Richards & Ford)](https://www.oreilly.com/library/view/fundamentals-of-software/9781663728357/) — essential read
- [ ] [The System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer) — the most comprehensive free resource
- [ ] [System Design Introduction (video — Gaurav Sen)](https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
- [ ] [Thinking in Systems: A Primer (Donella Meadows)](https://www.amazon.com/Thinking-Systems-Donella-H-Meadows/dp/1603580557) — mental model for complex systems
- [ ] [How to approach system design interviews](https://www.youtube.com/watch?v=bUHFg8CZFws)

### Software Architecture Patterns

- [ ] [Microservices vs Monolith — when to use what](https://martinfowler.com/articles/microservices.html)
- [ ] [Event-driven architecture explained](https://www.youtube.com/watch?v=STKCRSUsyP0)
- [ ] [API Gateway pattern](https://microservices.io/patterns/apigateway.html)
- [ ] [CQRS and Event Sourcing](https://martinfowler.com/bliki/CQRS.html)
- [ ] [The 12-Factor App methodology](https://12factor.net/)
- [ ] [Clean Architecture (Robert Martin)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- [ ] [Domain-Driven Design crash course (video)](https://www.youtube.com/watch?v=4rhzdZIDX_k)

### AI System Design

Designing AI systems is a distinct discipline. These resources specifically address ML/AI architectural decisions.

- [ ] [Designing Machine Learning Systems (Chip Huyen)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — **highly recommended**
- [ ] [ML System Design Template (by Chip Huyen)](https://huyenchip.com/machine-learning-systems-design/toc.html) — free online
- [ ] [Machine Learning System Design Interview (Aminian & Xu)](https://www.amazon.com/Machine-Learning-System-Design-Interview/dp/1736049127)
- [ ] [Full Stack Deep Learning — System Design lectures (free)](https://fullstackdeeplearning.com/course/2022/)
- [ ] [Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/)
- [ ] [MLOps: From Model-centric to Data-centric AI (Andrew Ng)](https://www.youtube.com/watch?v=06-AZXmwHjo)

#### AI system design practice problems:
- [ ] Design a real-time recommendation engine (YouTube, TikTok)
- [ ] Design a document search system with semantic search (RAG)
- [ ] Design an LLM-powered customer support chatbot at scale
- [ ] Design a fraud detection system with ML scoring
- [ ] Design a CI/CD pipeline for ML models (MLOps pipeline)
- [ ] Design a feature store for a large-scale ML platform

**[⬆ back to top](#table-of-contents)**

---

## Cloud Concepts for Data Engineering

AI Engineers must be comfortable with cloud platforms. Data lives in the cloud; models train in the cloud; inference runs in the cloud. This section covers the cloud knowledge required to do serious data engineering and AI work.

### Cloud Fundamentals

Pick one cloud provider to start with (AWS, GCP, or Azure). The concepts transfer across all three.

- [ ] [AWS Cloud Practitioner Essentials (free, official)](https://aws.amazon.com/training/digital/aws-cloud-practitioner-essentials/)
- [ ] [Google Cloud Fundamentals: Core Infrastructure (Coursera)](https://www.coursera.org/learn/gcp-fundamentals)
- [ ] [Microsoft Azure Fundamentals (AZ-900) — free learning path](https://learn.microsoft.com/en-us/training/paths/azure-fundamentals-describe-cloud-concepts/)
- [ ] [Cloud Computing Concepts (Coursera — University of Illinois)](https://www.coursera.org/learn/cloud-computing)

#### Key concepts to understand:
- [ ] Compute: VMs, containers, serverless (Lambda/Cloud Functions/Azure Functions)
- [ ] Storage: object storage (S3/GCS/Blob), block storage, data lakes
- [ ] Networking: VPCs, load balancers, CDNs, security groups
- [ ] IAM: identity, roles, permissions, least-privilege principle
- [ ] Pricing models: on-demand, reserved, spot/preemptible instances

### Data Engineering on the Cloud

- [ ] [Data Engineering Zoomcamp (free, DataTalks.Club)](https://github.com/DataTalksClub/data-engineering-zoomcamp) — **best free end-to-end resource**
- [ ] [Fundamentals of Data Engineering (Reis & Housley)](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/)
- [ ] [Apache Spark basics (PySpark)](https://spark.apache.org/docs/latest/api/python/getting_started/index.html)
- [ ] [dbt (data build tool) — transform data in your warehouse](https://docs.getdbt.com/docs/introduction)
- [ ] [Apache Airflow — workflow orchestration](https://airflow.apache.org/docs/apache-airflow/stable/tutorial/index.html)
- [ ] [Kafka fundamentals for streaming data](https://kafka.apache.org/documentation/#gettingStarted)
- [ ] [Data Lake vs Data Warehouse vs Lakehouse explained](https://www.databricks.com/discover/data-lakes/introduction)

#### Cloud-specific data tools:
- [ ] **AWS**: S3, Glue, Athena, Redshift, SageMaker, Lambda
- [ ] **GCP**: BigQuery, Dataflow, Vertex AI, Cloud Storage, Pub/Sub
- [ ] **Azure**: Azure Data Factory, Synapse Analytics, Azure ML, Blob Storage

### MLOps & AI Infrastructure

- [ ] [MLOps Zoomcamp (free, DataTalks.Club)](https://github.com/DataTalksClub/mlops-zoomcamp)
- [ ] [MLflow: open-source MLOps platform](https://mlflow.org/docs/latest/index.html)
- [ ] [Weights & Biases — experiment tracking](https://docs.wandb.ai/)
- [ ] [Kubernetes basics for ML engineers](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [ ] [Docker + Kubernetes for ML (video)](https://www.youtube.com/watch?v=R-3dfURb2hA)
- [ ] [Deploying ML models with FastAPI + Docker](https://towardsdatascience.com/how-to-deploy-a-machine-learning-model-with-fastapi-docker-and-github-actions-13374cbd638a)
- [ ] [Terraform basics — infrastructure as code](https://developer.hashicorp.com/terraform/tutorials/aws-get-started)
- [ ] [GitHub Actions for ML CI/CD pipelines](https://docs.github.com/en/actions/use-cases-and-examples/publishing-packages/publishing-docker-images)

**[⬆ back to top](#table-of-contents)**

---

## Core Human Life Skills for the AI Era

As AI automates more technical tasks, **human skills become the primary differentiator**. The engineers who thrive in the AI era are those who can think clearly, communicate compellingly, collaborate empathetically, and adapt continuously. These are not soft skills — they are survival skills.

### Communication & Storytelling

In an AI-augmented world, your ability to **explain complex ideas clearly** — to non-technical stakeholders, teammates, and interviewers — is priceless.

- [ ] [The Pyramid Principle: Logic in Writing and Thinking (Barbara Minto)](https://www.amazon.com/Pyramid-Principle-Logic-Writing-Thinking/dp/0273710516) — the gold standard for structured communication
- [ ] [Talk Like TED: The 9 Public-Speaking Secrets (Carmine Gallo)](https://www.amazon.com/Talk-TED-Public-Speaking-Secrets/dp/1250061539)
- [ ] [How to speak (MIT lecture by Patrick Winston)](https://www.youtube.com/watch?v=Unzc731iCUY) — legendary talk on effective communication
- [ ] [Toastmasters — practice public speaking](https://www.toastmasters.org/)
- [ ] [Writing Well: a guide for engineers](https://www.julian.com/guide/write/intro)
- [ ] [Technical writing for engineers (Google course, free)](https://developers.google.com/tech-writing)

### Critical Thinking & Problem Framing

The most dangerous mistake an AI Engineer can make is solving the **wrong problem** brilliantly.

- [ ] [Thinking, Fast and Slow (Daniel Kahneman)](https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555) — cognitive biases and decision-making
- [ ] [The Art of Problem Solving (Russell Ackoff)](https://www.youtube.com/watch?v=f-un9ym6Ru4) — classic talk on problem framing
- [ ] [First Principles Thinking (Elon Musk, Tim Urban)](https://waitbutwhy.com/2015/11/the-cook-and-the-chef-musks-secret-sauce.html)
- [ ] [How to Think (Yale course on the science of well-being)](https://www.coursera.org/learn/the-science-of-well-being)
- [ ] [Mental Models (Farnam Street)](https://fs.blog/mental-models/)
- [ ] [The OODA Loop: observe, orient, decide, act](https://en.wikipedia.org/wiki/OODA_loop)

### Adaptability & Continuous Learning

The half-life of technical knowledge is shrinking. The skill that matters most is **learning how to learn**.

- [ ] [Learning How to Learn (Coursera — Barbara Oakley)](https://www.coursera.org/learn/learning-how-to-learn) — **most enrolled MOOC in history**
- [ ] [A Mind for Numbers: How to Excel at Math and Science (Barbara Oakley)](https://www.amazon.com/Mind-Numbers-Science-Flunked-Algebra/dp/039916524X)
- [ ] [Peak: Secrets from the New Science of Expertise (Anders Ericsson)](https://www.amazon.com/Peak-Secrets-New-Science-Expertise/dp/0544456238) — deliberate practice
- [ ] [Range: Why Generalists Triumph in a Specialized World (David Epstein)](https://www.amazon.com/Range-Generalists-Triumph-Specialized-World/dp/0735214484)
- [ ] [Growth Mindset (Carol Dweck — TED Talk)](https://www.ted.com/talks/carol_dweck_the_power_of_believing_that_you_can_improve)
- [ ] [Building a Second Brain (Tiago Forte)](https://buildingasecondbrain.com/) — knowledge management system

### Collaboration & Emotional Intelligence

AI Engineers rarely work alone. The best outcomes come from teams that communicate well, debate constructively, and trust each other.

- [ ] [Emotional Intelligence 2.0 (Bradberry & Greaves)](https://www.amazon.com/Emotional-Intelligence-2-0-Travis-Bradberry/dp/0974320625)
- [ ] [The Five Dysfunctions of a Team (Patrick Lencioni)](https://www.amazon.com/Five-Dysfunctions-Team-Leadership-Fable/dp/0787960756)
- [ ] [Radical Candor (Kim Scott)](https://www.radicalcandor.com/) — how to give and receive feedback well
- [ ] [Non-Violent Communication (Marshall Rosenberg)](https://www.cnvc.org/learn-nvc/what-is-nvc) — conflict resolution
- [ ] [How to Win Friends and Influence People (Carnegie)](https://www.amazon.com/How-Win-Friends-Influence-People/dp/0671027034) — still relevant after 85 years
- [ ] [Google's Project Aristotle: What makes the perfect team?](https://rework.withgoogle.com/print/guides/5721312655835136/) — psychological safety research

### Ethics & Responsibility in the AI Era

- [ ] [AI Ethics (fast.ai lesson)](https://ethics.fast.ai/)
- [ ] [The Alignment Problem (Brian Christian)](https://www.amazon.com/Alignment-Problem-Machine-Learning-Values/dp/0393635821)
- [ ] [Weapons of Math Destruction (Cathy O'Neil)](https://www.amazon.com/Weapons-Math-Destruction-Increases-Inequality/dp/0553418815) — how models can harm society
- [ ] [AI Ethics course — deeplearning.ai](https://www.deeplearning.ai/short-courses/)
- [ ] [Responsible AI practices — Google](https://ai.google/responsibility/responsible-ai-practices/)

**[⬆ back to top](#table-of-contents)**

---

## deeplearning.ai Learning Path

[deeplearning.ai](https://www.deeplearning.ai/) — founded by Andrew Ng — is the premier online destination for practical AI/ML education. The courses below represent a structured learning path from foundations to cutting-edge techniques. Most short courses are **free to audit**.

### Foundational AI & ML

- [ ] [Machine Learning Specialization (Andrew Ng — Coursera)](https://www.deeplearning.ai/courses/machine-learning-specialization/)
    - Supervised learning, unsupervised learning, reinforcement learning fundamentals
    - Best starting point for anyone new to ML
- [ ] [Deep Learning Specialization (Andrew Ng — Coursera)](https://www.deeplearning.ai/courses/deep-learning-specialization/)
    - Neural networks, CNNs, RNNs, optimization, structuring ML projects
    - 5-course series — the gold standard deep learning curriculum
- [ ] [Mathematics for Machine Learning and Data Science Specialization](https://www.deeplearning.ai/courses/mathematics-for-machine-learning-and-data-science-specialization/)
    - Linear algebra, calculus, probability and statistics for ML

### Generative AI & LLMs

- [ ] [Generative AI with Large Language Models (Coursera)](https://www.deeplearning.ai/courses/generative-ai-with-llms/)
    - How LLMs work, fine-tuning, RLHF, deployment considerations
- [ ] [ChatGPT Prompt Engineering for Developers (free short course)](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
    - Written with OpenAI; covers prompt engineering techniques
- [ ] [Building Systems with the ChatGPT API (free short course)](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/)
- [ ] [LangChain for LLM Application Development (free short course)](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)
    - Chains, agents, memory, retrieval with LangChain
- [ ] [LangChain: Chat with Your Data (free short course)](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/)
    - Document loading, splitting, vector stores, RAG
- [ ] [Building and Evaluating Advanced RAG (free short course)](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/)
- [ ] [Finetuning Large Language Models (free short course)](https://www.deeplearning.ai/short-courses/finetuning-large-language-models/)
- [ ] [Large Language Models with Semantic Search (free short course)](https://www.deeplearning.ai/short-courses/large-language-models-semantic-search/)
- [ ] [Functions, Tools and Agents with LangChain (free short course)](https://www.deeplearning.ai/short-courses/functions-tools-agents-langchain/)
- [ ] [AI Agents in LangGraph (free short course)](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [ ] [Multi AI Agent Systems with crewAI (free short course)](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)

### MLOps & Deployment

- [ ] [Machine Learning Engineering for Production (MLOps) Specialization](https://www.deeplearning.ai/courses/machine-learning-engineering-for-production-mlops/)
    - 4-course series: ML in production, data lifecycle, model deployment, monitoring
- [ ] [Evaluating and Debugging Generative AI (free short course)](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/)
    - Using Weights & Biases for LLM evaluation and debugging

### Vision, NLP & Specialized Topics

- [ ] [Natural Language Processing Specialization](https://www.deeplearning.ai/courses/natural-language-processing-specialization/)
    - 4-course series covering NLP from basics to Transformer models
- [ ] [How Diffusion Models Work (free short course)](https://www.deeplearning.ai/short-courses/how-diffusion-models-work/)
    - Understand the models behind Stable Diffusion, DALL·E
- [ ] [Pair Programming with a Large Language Model (free short course)](https://www.deeplearning.ai/short-courses/pair-programming-llm/)
- [ ] [Understanding and Applying Text Embeddings (free short course)](https://www.deeplearning.ai/short-courses/google-cloud-vertex-ai/)
- [ ] [Vector Databases: from Embeddings to Applications (free short course)](https://www.deeplearning.ai/short-courses/vector-databases-embeddings-applications/)

### AI for Everyone

- [ ] [AI for Everyone (Andrew Ng — non-technical)](https://www.deeplearning.ai/courses/ai-for-everyone/)
    - Understand AI's capabilities and limitations; communicate about AI with non-technical colleagues
- [ ] [AI Python for Beginners (free short course)](https://www.deeplearning.ai/short-courses/ai-python-for-beginners/)
    - Learn Python the AI-native way, using AI assistance from the start

**[⬆ back to top](#table-of-contents)**

---

## Mathematics for AI

Strong mathematical foundations separate great AI Engineers from good ones. Focus on the topics below — interviewers at AI companies may probe these directly.

### Linear Algebra

Essential for understanding how neural networks process data, how embeddings work, and how dimensionality reduction operates.

- [ ] [Essence of Linear Algebra (3Blue1Brown — visual intuition)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2ZAgoSIREkZe0o)
- [ ] [MIT 18.06: Linear Algebra (Gilbert Strang)](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- [ ] **Key concepts:**
    - Vectors, matrices, dot product, matrix multiplication
    - Eigenvalues and eigenvectors
    - Singular Value Decomposition (SVD)
    - Principal Component Analysis (PCA) — understanding it geometrically
    - Orthogonality, projections, least squares

### Calculus & Optimization

Backpropagation *is* the chain rule. You need to understand gradients deeply.

- [ ] [Khan Academy: Multivariable Calculus](https://www.khanacademy.org/math/multivariable-calculus)
- [ ] [CS231n Notes: Optimization](https://cs231n.github.io/optimization-1/)
- [ ] **Key concepts:**
    - Partial derivatives and gradients
    - Chain rule → how backpropagation works
    - Gradient descent and variants (SGD, momentum, Adam)
    - Convex vs. non-convex optimization
    - Learning rate and convergence

### Probability & Statistics

Critical for model evaluation, Bayesian reasoning, and understanding uncertainty.

- [ ] [Statistics and Probability (Khan Academy)](https://www.khanacademy.org/math/statistics-probability)
- [ ] [Think Stats (free book by Allen Downey)](https://greenteapress.com/thinkstats2/)
- [ ] **Key concepts:**
    - Probability distributions: Gaussian, Bernoulli, Categorical, Poisson
    - Bayes' theorem and Bayesian reasoning
    - Maximum Likelihood Estimation (MLE) and MAP estimation
    - Hypothesis testing, p-values, confidence intervals
    - A/B testing and statistical significance
    - Central Limit Theorem

### Information Theory for AI

Directly relevant to loss functions and model evaluation.

- [ ] [Visual Information Theory (Chris Olah)](https://colah.github.io/posts/2015-09-Visual-Information/)
- [ ] **Key concepts:**
    - Entropy and information content
    - Cross-entropy loss — why it's used in classification
    - KL divergence — used in VAEs, RLHF, and model distillation
    - Mutual information

**[⬆ back to top](#table-of-contents)**

---

## Machine Learning Fundamentals

This is table-stakes knowledge for any AI Engineer role. You must understand these concepts and be able to implement them.

**Core resources:**
- [ ] [Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (Géron)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) — the main ML engineering book
- [ ] [Machine Learning Specialization (Andrew Ng — Coursera, free to audit)](https://www.coursera.org/specializations/machine-learning-introduction)
- [ ] [fast.ai Practical Deep Learning for Coders](https://course.fast.ai/)

### Supervised Learning

- [ ] Linear Regression: ordinary least squares, regularization (Ridge, Lasso)
- [ ] Logistic Regression: binary and multiclass, sigmoid, softmax
- [ ] Support Vector Machines: margin, kernel trick (intuition)
- [ ] Decision Trees: splitting criteria (Gini, entropy), pruning
- [ ] Ensemble methods:
    - Random Forests: bagging, feature importance
    - Gradient Boosting: XGBoost, LightGBM — widely used in production ML
- [ ] **Implement from scratch:** logistic regression with gradient descent

### Unsupervised Learning

- [ ] k-Means clustering: initialization, convergence, choosing k (elbow method)
- [ ] Hierarchical clustering: dendrograms, linkage criteria
- [ ] DBSCAN: density-based, handles noise
- [ ] Dimensionality reduction:
    - PCA: when and why to use it
    - t-SNE: visualization of high-dimensional data
    - UMAP: faster and better for embeddings visualization

### Model Evaluation & Selection

- [ ] Train / validation / test splits — and why you need all three
- [ ] k-Fold cross-validation
- [ ] Bias-variance tradeoff — diagnosing overfitting vs. underfitting
- [ ] Regularization techniques: L1 (Lasso), L2 (Ridge), dropout, early stopping
- [ ] Hyperparameter tuning: grid search, random search, Bayesian optimization

### Feature Engineering

- [ ] Encoding categorical variables: one-hot, label encoding, target encoding
- [ ] Normalization and standardization (when to use each)
- [ ] Handling missing data: imputation strategies
- [ ] Feature selection: filter, wrapper, and embedded methods
- [ ] Feature scaling for distance-based models (k-NN, SVM, k-Means)

### Evaluation Metrics

Know when to use which metric and why accuracy alone is often misleading.

- [ ] Classification: accuracy, precision, recall, F1, ROC curve, AUC
- [ ] Regression: MAE, MSE, RMSE, R²
- [ ] Ranking: NDCG, MRR, precision@k
- [ ] NLP: BLEU, ROUGE, perplexity
- [ ] Confusion matrix: TP, FP, FN, TN

**[⬆ back to top](#table-of-contents)**

---

## Deep Learning

- **Core resources:**
    - [ ] [Deep Learning (Goodfellow, Bengio, Courville — free online)](https://www.deeplearningbook.org/) — theoretical foundations
    - [ ] [CS231n: Convolutional Neural Networks for Visual Recognition (Stanford)](http://cs231n.stanford.edu/)
    - [ ] [fast.ai Practical Deep Learning for Coders, Part 1 & 2](https://course.fast.ai/)
    - [ ] ["Attention Is All You Need" — Vaswani et al. 2017 (the Transformer paper)](https://arxiv.org/abs/1706.03762)

### Neural Network Fundamentals

- [ ] Forward pass: how activations flow through layers
- [ ] Backward pass and backpropagation: chain rule in computational graphs
- [ ] Activation functions: ReLU, sigmoid, tanh, GELU, softmax — when to use each
- [ ] Loss functions: cross-entropy, MSE, contrastive loss, triplet loss
- [ ] **Implement from scratch:** a simple 2-layer neural network with backprop (NumPy)

### Training Techniques

- [ ] Stochastic Gradient Descent and variants: momentum, RMSProp, Adam, AdamW
- [ ] Learning rate scheduling: warmup, cosine annealing, reduce-on-plateau
- [ ] Batch normalization: why it helps training stability
- [ ] Dropout: training vs. inference behavior
- [ ] Weight initialization: Xavier/Glorot, He initialization
- [ ] Gradient clipping: when and why

### CNNs

- [ ] Convolution operation: filters, stride, padding, receptive field
- [ ] Pooling: max pooling, global average pooling
- [ ] Classic architectures: LeNet, AlexNet, VGG, ResNet, EfficientNet
- [ ] Skip connections and why ResNets train deeper networks
- [ ] Transfer learning: using pretrained CNNs for new tasks

### RNNs, LSTMs & GRUs

- [ ] Vanilla RNN: sequence modeling, vanishing gradient problem
- [ ] LSTM: cell state, gates (input, forget, output)
- [ ] GRU: simplified LSTM
- [ ] Sequence-to-sequence models: encoder-decoder architecture
- [ ] When to use RNNs vs. Transformers

### Transformers & Attention

This is the most important architecture to understand deeply for modern AI engineering.

- [ ] Self-attention: queries, keys, values; scaled dot-product attention
- [ ] Multi-head attention: why multiple heads help
- [ ] Positional encoding: how position information is injected
- [ ] Encoder-only (BERT-style), decoder-only (GPT-style), encoder-decoder (T5-style) — use cases for each
- [ ] Layer normalization, feed-forward layers, residual connections
- [ ] [ ] [Illustrated Transformer (Jay Alammar)](https://jalammar.github.io/illustrated-transformer/)

**[⬆ back to top](#table-of-contents)**

---

## Large Language Models & Generative AI

This is the highest-signal section for modern AI Engineer roles. Companies like OpenAI, Anthropic, Google DeepMind, and Meta AI test this deeply.

**Core resources:**
- [ ] [Neural Networks: Zero to Hero (Andrej Karpathy)](https://karpathy.ai/zero-to-hero.html) — build GPT from scratch, highly recommended
- [ ] [HuggingFace NLP Course (free)](https://huggingface.co/learn/nlp-course/)
- [ ] [LLM Course by Maxime Labonne (free)](https://github.com/mlabonne/llm-course)

### LLM Architecture

- [ ] GPT-style (decoder-only): autoregressive generation, causal attention mask
- [ ] BERT-style (encoder-only): bidirectional attention, MLM pre-training objective
- [ ] T5-style (encoder-decoder): span corruption, seq2seq tasks
- [ ] Tokenization: BPE, WordPiece, SentencePiece — how text becomes tokens
- [ ] Scaling laws: how model size, data, and compute interact (Kaplan et al.)
- [ ] Context window and its implications for memory and generation quality

### Pre-training & Fine-tuning

- [ ] Pre-training objectives: next token prediction (causal LM), masked LM
- [ ] Instruction tuning: turning a base model into a chat assistant
- [ ] RLHF (Reinforcement Learning from Human Feedback): reward model, PPO — how ChatGPT was aligned
- [ ] Parameter-Efficient Fine-Tuning (PEFT):
    - LoRA: low-rank adapters — modify a small number of parameters
    - QLoRA: quantized LoRA — fine-tune large models on consumer GPUs
    - Prefix tuning, prompt tuning

### Prompting Techniques

- [ ] Zero-shot prompting
- [ ] Few-shot prompting: providing examples in the context
- [ ] Chain-of-thought (CoT): asking the model to reason step by step
- [ ] Self-consistency: sampling multiple CoT paths and taking the majority answer
- [ ] Tool use / function calling
- [ ] System prompts and prompt injection risks

### RAG (Retrieval-Augmented Generation)

Used in production at most AI companies to ground LLMs in external knowledge.

- [ ] Why RAG: solving hallucination and knowledge cutoff problems
- [ ] Document chunking strategies: fixed-size, sentence, semantic chunking
- [ ] Embedding models: generating dense vector representations of text
- [ ] Vector search: cosine similarity, approximate nearest neighbor (ANN)
- [ ] Re-ranking: cross-encoder rerankers after first-stage retrieval
- [ ] HyDE, multi-query retrieval, and other advanced RAG patterns
- [ ] [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction) — leading RAG framework
- [ ] [LlamaIndex Documentation](https://docs.llamaindex.ai/) — document-centric RAG

### LLM Agents

- [ ] ReAct pattern: Reasoning + Acting in interleaved steps
- [ ] Tool use: web search, code interpreter, database queries
- [ ] Planning: task decomposition, tree-of-thought
- [ ] Multi-agent frameworks: AutoGen, CrewAI — agents collaborating to solve tasks
- [ ] Memory in agents: short-term (context window), long-term (vector store, database)

### LLM Evaluation

- [ ] Perplexity: intrinsic measure of language model quality
- [ ] HELM benchmark: holistic LLM evaluation across scenarios
- [ ] MT-Bench: multi-turn conversation quality (GPT-4 as judge)
- [ ] Human evaluation: A/B preference testing
- [ ] Safety evaluation: bias, toxicity, prompt injection, jailbreaks
- [ ] Alignment and RLHF metrics

**[⬆ back to top](#table-of-contents)**

---

## MLOps & AI Systems Engineering

Production AI systems fail in ways that pure ML models don't. This section covers the engineering discipline of keeping ML systems reliable at scale.

**Core resources:**
- [ ] [Designing Machine Learning Systems (Chip Huyen)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107963/) — the definitive MLOps book
- [ ] [Full Stack Deep Learning (free course)](https://fullstackdeeplearning.com/)
- [ ] [Made With ML (free MLOps course)](https://madewithml.com/)

### ML Pipelines

- [ ] Data ingestion → preprocessing → training → evaluation → deployment as a repeatable, versioned pipeline
- [ ] Pipeline orchestration: Apache Airflow, Prefect, Kubeflow Pipelines
- [ ] Data validation: detecting schema drift and distribution shift in inputs
- [ ] Reproducibility: seed management, environment pinning, determinism

### Experiment Tracking

- [ ] [MLflow](https://mlflow.org/): open-source tracking, model registry, project packaging
- [ ] [Weights & Biases](https://wandb.ai/): experiment tracking, artifact management, sweeps
- [ ] [DVC (Data Version Control)](https://dvc.org/): versioning data and models alongside code

### Model Serving

- [ ] REST APIs for inference: FastAPI, Flask — request batching
- [ ] gRPC serving: lower latency for high-throughput inference
- [ ] Serving frameworks: TorchServe, Triton Inference Server, BentoML, Ray Serve
- [ ] Online vs. batch inference: real-time vs. offline scoring
- [ ] Canary deployments and shadow mode

### Inference Optimization

Critical for cost reduction in production.

- [ ] Quantization: INT8, FP16, BF16 — trading precision for speed/memory
- [ ] Pruning: removing low-importance weights
- [ ] Knowledge distillation: training smaller "student" models to mimic larger "teacher"
- [ ] ONNX export: hardware-agnostic model format
- [ ] TensorRT: NVIDIA's inference optimizer for GPU deployment
- [ ] vLLM: PagedAttention for efficient LLM serving

### Model Monitoring

- [ ] Data drift: input distribution shift from training to production
- [ ] Concept drift: the relationship between inputs and outputs changes over time
- [ ] Prediction monitoring: tracking output distributions and anomalies
- [ ] Alerting and automated retraining triggers
- [ ] [Evidently AI](https://www.evidentlyai.com/): open-source model monitoring

### Feature Stores

- [ ] Offline features: computed from historical data, used in training
- [ ] Online features: low-latency retrieval, used at inference time
- [ ] Feature consistency: same feature logic between training and serving ("training-serving skew")
- [ ] [Feast](https://feast.dev/): open-source feature store
- [ ] Tecton: managed feature store

### Vector Databases

Essential for RAG systems, semantic search, and recommendation engines.

- [ ] Why vector DBs: storing and querying embedding vectors at scale
- [ ] FAISS: Facebook's library for efficient similarity search (in-memory)
- [ ] Pinecone: managed vector DB service
- [ ] Weaviate, Milvus, Qdrant: open-source alternatives
- [ ] ANN algorithms: HNSW (Hierarchical Navigable Small World), IVF (Inverted File Index)
- [ ] Filtering: combining vector search with metadata filters

### Data Versioning

- [ ] [DVC](https://dvc.org/): Git-like versioning for data and models
- [ ] Delta Lake: ACID transactions on top of data lake storage
- [ ] Apache Iceberg: open table format for huge analytics datasets
- [ ] Lineage tracking: knowing where each training sample came from

**[⬆ back to top](#table-of-contents)**

---

## Let's Get Started

Alright, enough talk, let's learn!

But don't forget to do coding problems from above while you learn!

## Algorithmic complexity / Big-O / Asymptotic analysis

- Nothing to implement here, you're just watching videos and taking notes! Yay!
- There are a lot of videos here. Just watch enough until you understand it. You can always come back and review.
- Don't worry if you don't understand all the math behind it.
- You just need to understand how to express the complexity of an algorithm in terms of Big-O.
- [ ] [Harvard CS50 - Asymptotic Notation (video)](https://www.youtube.com/watch?v=iOq5kSKqeR4)
- [ ] [Big O Notations (general quick tutorial) (video)](https://www.youtube.com/watch?v=V6mKVRU1evU)
- [ ] [Big O Notation (and Omega and Theta) - best mathematical explanation (video)](https://www.youtube.com/watch?v=ei-A_wy5Yxw&index=2&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
- [ ] [Skiena (video)](https://www.youtube.com/watch?v=z1mkCe3kVUA)
- [ ] [UC Berkeley Big O (video)](https://archive.org/details/ucberkeley_webcast_VIS4YDpuP98)
- [ ] [Amortized Analysis (video)](https://www.youtube.com/watch?v=B3SpQZaAZP4&index=10&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
- [ ] TopCoder (includes recurrence relations and master theorem):
    - [Computational Complexity: Section 1](https://www.topcoder.com/thrive/articles/Computational%20Complexity%20part%20one)
    - [Computational Complexity: Section 2](https://www.topcoder.com/thrive/articles/Computational%20Complexity%20part%20two)
- [ ] [Cheat sheet](http://bigocheatsheet.com/)
- [ ] [[Review] Analyzing Algorithms (playlist) in 18 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZMxejjIyFHWa-4nKg6sdoIv)

Well, that's about enough of that.

When you go through "Cracking the Coding Interview", there is a chapter on this, and at the end there is a quiz to see
if you can identify the runtime complexity of different algorithms. It's a super review and test.

**[⬆ back to top](#table-of-contents)**

## Data Structures

- ### Arrays
    - [ ] About Arrays:
    	- [Arrays CS50 Harvard University](https://www.youtube.com/watch?v=tI_tIZFyKBw&t=3009s)
        - [Arrays (video)](https://www.coursera.org/lecture/data-structures/arrays-OsBSF)
        - [UC Berkeley CS61B - Linear and Multi-Dim Arrays (video)](https://archive.org/details/ucberkeley_webcast_Wp8oiO_CZZE) (Start watching from 15m 32s)
        - [Dynamic Arrays (video)](https://www.coursera.org/lecture/data-structures/dynamic-arrays-EwbnV)
        - [Jagged Arrays (video)](https://www.youtube.com/watch?v=1jtrQqYpt7g)
    - [ ] Implement a vector (mutable array with automatic resizing):
        - [ ] Practice coding using arrays and pointers, and pointer math to jump to an index instead of using indexing.
        - [ ] New raw data array with allocated memory
            - can allocate int array under the hood, just not use its features
            - start with 16, or if the starting number is greater, use power of 2 - 16, 32, 64, 128
        - [ ] size() - number of items
        - [ ] capacity() - number of items it can hold
        - [ ] is_empty()
        - [ ] at(index) - returns the item at a given index, blows up if index out of bounds
        - [ ] push(item)
        - [ ] insert(index, item) - inserts item at index, shifts that index's value and trailing elements to the right
        - [ ] prepend(item) - can use insert above at index 0
        - [ ] pop() - remove from end, return value
        - [ ] delete(index) - delete item at index, shifting all trailing elements left
        - [ ] remove(item) - looks for value and removes index holding it (even if in multiple places)
        - [ ] find(item) - looks for value and returns first index with that value, -1 if not found
        - [ ] resize(new_capacity) // private function
            - when you reach capacity, resize to double the size
            - when popping an item, if the size is 1/4 of capacity, resize to half
    - [ ] Time
        - O(1) to add/remove at end (amortized for allocations for more space), index, or update
        - O(n) to insert/remove elsewhere
    - [ ] Space
        - contiguous in memory, so proximity helps performance
        - space needed = (array capacity, which is >= n) * size of item, but even if 2n, still O(n)

- ### Linked Lists
    - [ ] Description:
    	- [ ] [Linked Lists CS50 Harvard University](https://www.youtube.com/watch?v=2T-A_GFuoTo&t=650s) - this builds the intuition.
        - [ ] [Singly Linked Lists (video)](https://www.coursera.org/lecture/data-structures/singly-linked-lists-kHhgK)
        - [ ] [CS 61B - Linked Lists 1 (video)](https://archive.org/details/ucberkeley_webcast_htzJdKoEmO0)
        - [ ] [CS 61B - Linked Lists 2 (video)](https://archive.org/details/ucberkeley_webcast_-c4I3gFYe3w)
        - [ ] [[Review] Linked lists in 4 minutes (video)](https://youtu.be/F8AbOfQwl1c)
    - [ ] [C Code (video)](https://www.youtube.com/watch?v=QN6FPiD0Gzo)
            - not the whole video, just portions about Node struct and memory allocation
    - [ ] Linked List vs Arrays:
        - [Core Linked Lists Vs Arrays (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-linked-lists-vs-arrays-rjBs9)
        - [In The Real World Linked Lists Vs Arrays (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/in-the-real-world-lists-vs-arrays-QUaUd)
    - [ ] [Why you should avoid linked lists (video)](https://www.youtube.com/watch?v=YQs6IC-vgmo)
    - [ ] Gotcha: you need pointer to pointer knowledge:
        (for when you pass a pointer to a function that may change the address where that pointer points)
        This page is just to get a grasp on ptr to ptr. I don't recommend this list traversal style. Readability and maintainability suffer due to cleverness.
        - [Pointers to Pointers](https://www.eskimo.com/~scs/cclass/int/sx8.html)
    - [ ] Implement (I did with tail pointer & without):
        - [ ] size() - returns the number of data elements in the list
        - [ ] empty() - bool returns true if empty
        - [ ] value_at(index) - returns the value of the nth item (starting at 0 for first)
        - [ ] push_front(value) - adds an item to the front of the list
        - [ ] pop_front() - remove the front item and return its value
        - [ ] push_back(value) - adds an item at the end
        - [ ] pop_back() - removes end item and returns its value
        - [ ] front() - get the value of the front item
        - [ ] back() - get the value of the end item
        - [ ] insert(index, value) - insert value at index, so the current item at that index is pointed to by the new item at the index
        - [ ] erase(index) - removes node at given index
        - [ ] value_n_from_end(n) - returns the value of the node at the nth position from the end of the list
        - [ ] reverse() - reverses the list
        - [ ] remove_value(value) - removes the first item in the list with this value
    - [ ] Doubly-linked List
        - [Description (video)](https://www.coursera.org/lecture/data-structures/doubly-linked-lists-jpGKD)
        - No need to implement

- ### Stack
    - [ ] [Stacks (video)](https://www.coursera.org/lecture/data-structures/stacks-UdKzQ)
    - [ ] [[Review] Stacks in 3 minutes (video)](https://youtu.be/KcT3aVgrrpU)
    - [ ] Will not implement. Implementing with the array is trivial

- ### Queue
    - [ ] [Queue (video)](https://www.coursera.org/lecture/data-structures/queues-EShpq)
    - [ ] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
    - [ ] [[Review] Queues in 3 minutes (video)](https://youtu.be/D6gu-_tmEpQ)
    - [ ] Implement using linked-list, with tail pointer:
        - enqueue(value) - adds value at a position at the tail
        - dequeue() - returns value and removes least recently added element (front)
        - empty()
    - [ ] Implement using a fixed-sized array:
        - enqueue(value) - adds item at end of available storage
        - dequeue() - returns value and removes least recently added element
        - empty()
        - full()
    - [ ] Cost:
        - a bad implementation using a linked list where you enqueue at the head and dequeue at the tail would be O(n)
            because you'd need the next to last element, causing a full traversal of each dequeue
        - enqueue: O(1) (amortized, linked list and array [probing])
        - dequeue: O(1) (linked list and array)
        - empty: O(1) (linked list and array)

- ### Hash table
    - [ ] Videos:
        - [ ] [Hashing with Chaining (video)](https://www.youtube.com/watch?v=0M_kIqhwbFo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=8)
        - [ ] [Table Doubling, Karp-Rabin (video)](https://www.youtube.com/watch?v=BRO7mVIFt08&index=9&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [Open Addressing, Cryptographic Hashing (video)](https://www.youtube.com/watch?v=rvdJDijO2Ro&index=10&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [PyCon 2010: The Mighty Dictionary (video)](https://www.youtube.com/watch?v=C4Kc8xzcA68)
        - [ ] [PyCon 2017: The Dictionary Even Mightier (video)](https://www.youtube.com/watch?v=66P5FMkWoVU)
        - [ ] [(Advanced) Randomization: Universal & Perfect Hashing (video)](https://www.youtube.com/watch?v=z0lJ2k0sl1g&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=11)
        - [ ] [(Advanced) Perfect hashing (video)](https://www.youtube.com/watch?v=N0COwN14gt0&list=PL2B4EEwhKD-NbwZ4ezj7gyc_3yNrojKM9&index=4)
        - [ ] [[Review] Hash tables in 4 minutes (video)](https://youtu.be/knV86FlSXJ8)

    - [ ] Online Courses:
        - [ ] [Core Hash Tables (video)](https://www.coursera.org/lecture/data-structures-optimizing-performance/core-hash-tables-m7UuP)
        - [ ] [Data Structures (video)](https://www.coursera.org/learn/data-structures/home/week/4)
        - [ ] [Phone Book Problem (video)](https://www.coursera.org/lecture/data-structures/phone-book-problem-NYZZP)
        - [ ] distributed hash tables:
            - [Instant Uploads And Storage Optimization In Dropbox (video)](https://www.coursera.org/lecture/data-structures/instant-uploads-and-storage-optimization-in-dropbox-DvaIb)
            - [Distributed Hash Tables (video)](https://www.coursera.org/lecture/data-structures/distributed-hash-tables-tvH8H)

    - [ ] Implement with array using linear probing
        - hash(k, m) - m is the size of the hash table
        - add(key, value) - if the key already exists, update value
        - exists(key)
        - get(key)
        - remove(key)

**[⬆ back to top](#table-of-contents)**

## More Knowledge

- ### Binary search
    - [ ] [Binary Search (video)](https://www.youtube.com/watch?v=D5SrAga1pno)
    - [ ] [Binary Search (video)](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)
    - [ ] [detail](https://www.topcoder.com/thrive/articles/Binary%20Search)
    - [ ] [blueprint](https://leetcode.com/discuss/general-discussion/786126/python-powerful-ultimate-binary-search-template-solved-many-problems)
    - [ ] [[Review] Binary search in 4 minutes (video)](https://youtu.be/fDKIpRe8GW4)
    - [ ] Implement:
        - binary search (on a sorted array of integers)
        - binary search using recursion

- ### Bitwise operations
    - [ ] [Bits cheat sheet](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/bits-cheat-sheet.pdf)
        - you should know many of the powers of 2 from (2^1 to 2^16 and 2^32)
    - [ ] Get a really good understanding of manipulating bits with: &, |, ^, ~, >>, <<
        - [ ] [words](https://en.wikipedia.org/wiki/Word_(computer_architecture))
        - [ ] Good intro:
            [Bit Manipulation (video)](https://www.youtube.com/watch?v=7jkIUgLC29I)
        - [ ] [C Programming Tutorial 2-10: Bitwise Operators (video)](https://www.youtube.com/watch?v=d0AwjSpNXR0)
        - [ ] [Bit Manipulation](https://en.wikipedia.org/wiki/Bit_manipulation)
        - [ ] [Bitwise Operation](https://en.wikipedia.org/wiki/Bitwise_operation)
        - [ ] [Bithacks](https://graphics.stanford.edu/~seander/bithacks.html)
        - [ ] [The Bit Twiddler](https://bits.stephan-brumme.com/)
        - [ ] [The Bit Twiddler Interactive](https://bits.stephan-brumme.com/interactive.html)
        - [ ] [Bit Hacks (video)](https://www.youtube.com/watch?v=ZusiKXcz_ac)
		- [ ] [Practice Operations](https://pconrad.github.io/old_pconrad_cs16/topics/bitOps/)
    - [ ] 2s and 1s complement
        - [Binary: Plusses & Minuses (Why We Use Two's Complement) (video)](https://www.youtube.com/watch?v=lKTsv6iVxV4)
        - [1s Complement](https://en.wikipedia.org/wiki/Ones%27_complement)
        - [2s Complement](https://en.wikipedia.org/wiki/Two%27s_complement)
    - [ ] Count set bits
        - [4 ways to count bits in a byte (video)](https://youtu.be/Hzuzo9NJrlc)
        - [Count Bits](https://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan)
        - [How To Count The Number Of Set Bits In a 32 Bit Integer](http://stackoverflow.com/questions/109023/how-to-count-the-number-of-set-bits-in-a-32-bit-integer)
    - [ ] Swap values:
        - [Swap](https://bits.stephan-brumme.com/swap.html)
    - [ ] Absolute value:
        - [Absolute Integer](https://bits.stephan-brumme.com/absInteger.html)

**[⬆ back to top](#table-of-contents)**

## Trees

- ### Trees - Intro
    - [ ] [Intro to Trees (video)](https://www.coursera.org/lecture/data-structures/trees-95qda)
    - [ ] [Tree Traversal (video)](https://www.coursera.org/lecture/data-structures/tree-traversal-fr51b)
    - [ ] [BFS(breadth-first search) and DFS(depth-first search) (video)](https://www.youtube.com/watch?v=uWL6FJhq5fM)
        - BFS notes:
           - level order (BFS, using queue)
           - time complexity: O(n)
           - space complexity: best: O(1), worst: O(n/2)=O(n)
        - DFS notes:
            - time complexity: O(n)
            - space complexity:
                best: O(log n) - avg. height of tree
                worst: O(n)
            - inorder (DFS: left, self, right)
            - postorder (DFS: left, right, self)
            - preorder (DFS: self, left, right)
    - [ ] [[Review] Breadth-first search in 4 minutes (video)](https://youtu.be/HZ5YTanv5QE)
    - [ ] [[Review] Depth-first search in 4 minutes (video)](https://youtu.be/Urx87-NMm6c)
    - [ ] [[Review] Tree Traversal (playlist) in 11 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZO1JC2RgEi04nLy6D-rKk6b)

- ### Binary search trees: BSTs
    - [ ] [Binary Search Tree Review (video)](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
    - [ ] [Introduction (video)](https://www.coursera.org/learn/data-structures/lecture/E7cXP/introduction)
    - [ ] [MIT (video)](https://www.youtube.com/watch?v=76dhtgZt38A&ab_channel=MITOpenCourseWare)
    - C/C++:
        - [ ] [Binary search tree - Implementation in C/C++ (video)](https://www.youtube.com/watch?v=COZK7NATh4k&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=28)
        - [ ] [BST implementation - memory allocation in stack and heap (video)](https://www.youtube.com/watch?v=hWokyBoo0aI&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=29)
        - [ ] [Find min and max element in a binary search tree (video)](https://www.youtube.com/watch?v=Ut90klNN264&index=30&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Find the height of a binary tree (video)](https://www.youtube.com/watch?v=_pnqMz5nrRs&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=31)
        - [ ] [Binary tree traversal - breadth-first and depth-first strategies (video)](https://www.youtube.com/watch?v=9RHO6jU--GU&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=32)
        - [ ] [Binary tree: Level Order Traversal (video)](https://www.youtube.com/watch?v=86g8jAQug04&index=33&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Binary tree traversal: Preorder, Inorder, Postorder (video)](https://www.youtube.com/watch?v=gm8DUJJhmY4&index=34&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Check if a binary tree is a binary search tree or not (video)](https://www.youtube.com/watch?v=yEwSGhSsT0U&index=35&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Delete a node from Binary Search Tree (video)](https://www.youtube.com/watch?v=gcULXE7ViZw&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=36)
        - [ ] [Inorder Successor in a binary search tree (video)](https://www.youtube.com/watch?v=5cPbNCrdotA&index=37&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
    - [ ] Implement:
        - [ ] [insert    // insert value into tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/submissions/987660183/)
        - [ ] get_node_count // get count of values stored
        - [ ] print_values // prints the values in the tree, from min to max
        - [ ] delete_tree
        - [ ] is_in_tree // returns true if a given value exists in the tree
        - [ ] [get_height // returns the height in nodes (single node's height is 1)](https://www.geeksforgeeks.org/find-the-maximum-depth-or-height-of-a-tree/)
        - [ ] get_min   // returns the minimum value stored in the tree
        - [ ] get_max   // returns the maximum value stored in the tree
        - [ ] [is_binary_search_tree](https://leetcode.com/problems/validate-binary-search-tree/)
        - [ ] delete_value
        - [ ] get_successor // returns the next-highest value in the tree after given value, -1 if none

- ### Heap / Priority Queue / Binary Heap
    - visualized as a tree, but is usually linear in storage (array, linked list)
    - [ ] [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure))
    - [ ] [Introduction (video)](https://www.coursera.org/lecture/data-structures/introduction-2OpTs)
    - [ ] [Binary Trees (video)](https://www.coursera.org/learn/data-structures/lecture/GRV2q/binary-trees)
    - [ ] [Tree Height Remark (video)](https://www.coursera.org/learn/data-structures/supplement/S5xxz/tree-height-remark)
    - [ ] [Basic Operations (video)](https://www.coursera.org/learn/data-structures/lecture/0g1dl/basic-operations)
    - [ ] [Complete Binary Trees (video)](https://www.coursera.org/learn/data-structures/lecture/gl5Ni/complete-binary-trees)
    - [ ] [Pseudocode (video)](https://www.coursera.org/learn/data-structures/lecture/HxQo9/pseudocode)
    - [ ] [Heap Sort - jumps to start (video)](https://youtu.be/odNJmw5TOEE?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3291)
    - [ ] [Heap Sort (video)](https://www.coursera.org/lecture/data-structures/heap-sort-hSzMO)
    - [ ] [Building a heap (video)](https://www.coursera.org/lecture/data-structures/building-a-heap-dwrOS)
    - [ ] [MIT 6.006 Introduction to Algorithms: Binary Heaps](https://www.youtube.com/watch?v=Xnpo1atN-Iw&list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY&index=12)
    - [ ] [CS 61B Lecture 24: Priority Queues (video)](https://archive.org/details/ucberkeley_webcast_yIUFT6AKBGE)
    - [ ] [Linear Time BuildHeap (max-heap)](https://www.youtube.com/watch?v=MiyLo8adrWw)
    - [ ] [[Review] Heap (playlist) in 13 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZNsyqgPW-DNwUeT8F8uhWc6)
    - [ ] Implement a max-heap:
        - [ ] insert
        - [ ] sift_up - needed for insert
        - [ ] get_max - returns the max item, without removing it
        - [ ] get_size() - return number of elements stored
        - [ ] is_empty() - returns true if the heap contains no elements
        - [ ] extract_max - returns the max item, removing it
        - [ ] sift_down - needed for extract_max
        - [ ] remove(x) - removes item at index x
        - [ ] heapify - create a heap from an array of elements, needed for heap_sort
        - [ ] heap_sort() - take an unsorted array and turn it into a sorted array in place using a max heap or min heap

**[⬆ back to top](#table-of-contents)**

## Sorting

- [ ] Notes:
    - Implement sorts & know best case/worst case, average complexity of each:
        - no bubble sort - it's terrible - O(n^2), except when n <= 16
    - [ ] Stability in sorting algorithms ("Is Quicksort stable?")
        - [Sorting Algorithm Stability](https://en.wikipedia.org/wiki/Sorting_algorithm#Stability)
        - [Stability In Sorting Algorithms](http://stackoverflow.com/questions/1517793/stability-in-sorting-algorithms)
        - [Stability In Sorting Algorithms](http://www.geeksforgeeks.org/stability-in-sorting-algorithms/)
        - [Sorting Algorithms - Stability](http://homepages.math.uic.edu/~leon/cs-mcs401-s08/handouts/stability.pdf)
    - [ ] Which algorithms can be used on linked lists? Which on arrays? Which of both?
        - I wouldn't recommend sorting a linked list, but merge sort is doable.
        - [Merge Sort For Linked List](http://www.geeksforgeeks.org/merge-sort-for-linked-list/)

- For heapsort, see the Heap data structure above. Heap sort is great, but not stable

- [ ] [Sedgewick - Mergesort (5 videos)](https://www.coursera.org/learn/algorithms-part1/home/week/3)
    - [ ] [1. Mergesort](https://www.coursera.org/lecture/algorithms-part1/mergesort-ARWDq)
    - [ ] [2. Bottom-up Mergesort](https://www.coursera.org/learn/algorithms-part1/lecture/PWNEl/bottom-up-mergesort)
    - [ ] [3. Sorting Complexity](https://www.coursera.org/lecture/algorithms-part1/sorting-complexity-xAltF)
    - [ ] [4. Comparators](https://www.coursera.org/lecture/algorithms-part1/comparators-9FYhS)
    - [ ] [5. Stability](https://www.coursera.org/learn/algorithms-part1/lecture/pvvLZ/stability)

- [ ] [Sedgewick - Quicksort (4 videos)](https://www.coursera.org/learn/algorithms-part1/home/week/3)
    - [ ] [1. Quicksort](https://www.coursera.org/lecture/algorithms-part1/quicksort-vjvnC)
    - [ ] [2. Selection](https://www.coursera.org/lecture/algorithms-part1/selection-UQxFT)
    - [ ] [3. Duplicate Keys](https://www.coursera.org/lecture/algorithms-part1/duplicate-keys-XvjPd)
    - [ ] [4. System Sorts](https://www.coursera.org/lecture/algorithms-part1/system-sorts-QBNZ7)

- [ ] UC Berkeley:
    - [ ] [CS 61B Lecture 29: Sorting I (video)](https://archive.org/details/ucberkeley_webcast_EiUvYS2DT6I)
    - [ ] [CS 61B Lecture 30: Sorting II (video)](https://archive.org/details/ucberkeley_webcast_2hTY3t80Qsk)
    - [ ] [CS 61B Lecture 32: Sorting III (video)](https://archive.org/details/ucberkeley_webcast_Y6LOLpxg6Dc)
    - [ ] [CS 61B Lecture 33: Sorting V (video)](https://archive.org/details/ucberkeley_webcast_qNMQ4ly43p4)
    - [ ] [CS 61B 2014-04-21: Radix Sort(video)](https://archive.org/details/ucberkeley_webcast_pvbBMd-3NoI)

- [ ] [Bubble Sort (video)](https://www.youtube.com/watch?v=P00xJgWzz2c&index=1&list=PL89B61F78B552C1AB)
- [ ] [Analyzing Bubble Sort (video)](https://www.youtube.com/watch?v=ni_zk257Nqo&index=7&list=PL89B61F78B552C1AB)
- [ ] [Insertion Sort, Merge Sort (video)](https://www.youtube.com/watch?v=Kg4bqzAqRBM&index=3&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
- [ ] [Insertion Sort (video)](https://www.youtube.com/watch?v=c4BRHC7kTaQ&index=2&list=PL89B61F78B552C1AB)
- [ ] [Merge Sort (video)](https://www.youtube.com/watch?v=GCae1WNvnZM&index=3&list=PL89B61F78B552C1AB)
- [ ] [Quicksort (video)](https://www.youtube.com/watch?v=y_G9BkAm6B8&index=4&list=PL89B61F78B552C1AB)
- [ ] [Selection Sort (video)](https://www.youtube.com/watch?v=6nDMgr0-Yyo&index=8&list=PL89B61F78B552C1AB)

- [ ] Merge sort code:
    - [ ] [Using output array (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/sorting/mergesort.c)
    - [ ] [Using output array (Python)](https://github.com/jwasham/practice-python/blob/master/merge_sort/merge_sort.py)
    - [ ] [In-place (C++)](https://github.com/jwasham/practice-cpp/blob/master/merge_sort/merge_sort.cc)
- [ ] Quick sort code:
    - [ ] [Implementation (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/randomization/quick.c)
    - [ ] [Implementation (C)](https://github.com/jwasham/practice-c/blob/master/quick_sort/quick_sort.c)
    - [ ] [Implementation (Python)](https://github.com/jwasham/practice-python/blob/master/quick_sort/quick_sort.py)

- [ ] [[Review] Sorting (playlist) in 18 minutes](https://www.youtube.com/playlist?list=PL9xmBV_5YoZOZSbGAXAPIq1BeUf4j20pl)
    - [ ] [Quick sort in 4 minutes (video)](https://youtu.be/Hoixgm4-P4M)
    - [ ] [Heap sort in 4 minutes (video)](https://youtu.be/2DmK_H7IdTo)
    - [ ] [Merge sort in 3 minutes (video)](https://youtu.be/4VqmGXwpLqc)
    - [ ] [Bubble sort in 2 minutes (video)](https://youtu.be/xli_FI7CuzA)
    - [ ] [Selection sort in 3 minutes (video)](https://youtu.be/g-PGLbMth_g)
    - [ ] [Insertion sort in 2 minutes (video)](https://youtu.be/JU767SDMDvA)

- [ ] Implement:
    - [ ] Mergesort: O(n log n) average and worst case
    - [ ] Quicksort O(n log n) average case
    - Selection sort and insertion sort are both O(n^2) average and worst-case
    - For heapsort, see Heap data structure above

- [ ] Not required, but I recommended them:
    - [ ] [Sedgewick - Radix Sorts (6 videos)](https://www.coursera.org/learn/algorithms-part2/home/week/3)
        - [ ] [1. Strings in Java](https://www.coursera.org/learn/algorithms-part2/lecture/vGHvb/strings-in-java)
        - [ ] [2. Key Indexed Counting](https://www.coursera.org/lecture/algorithms-part2/key-indexed-counting-2pi1Z)
        - [ ] [3. Least Significant Digit First String Radix Sort](https://www.coursera.org/learn/algorithms-part2/lecture/c1U7L/lsd-radix-sort)
        - [ ] [4. Most Significant Digit First String Radix Sort](https://www.coursera.org/learn/algorithms-part2/lecture/gFxwG/msd-radix-sort)
        - [ ] [5. 3 Way Radix Quicksort](https://www.coursera.org/lecture/algorithms-part2/3-way-radix-quicksort-crkd5)
        - [ ] [6. Suffix Arrays](https://www.coursera.org/learn/algorithms-part2/lecture/TH18W/suffix-arrays)
    - [ ] [Radix Sort](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#radixSort)
    - [ ] [Radix Sort (video)](https://www.youtube.com/watch?v=xhr26ia4k38)
    - [ ] [Radix Sort, Counting Sort (linear time given constraints) (video)](https://www.youtube.com/watch?v=Nz1KZXbghj8&index=7&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [Randomization: Matrix Multiply, Quicksort, Freivalds' algorithm (video)](https://www.youtube.com/watch?v=cNB2lADK3_s&index=8&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [Sorting in Linear Time (video)](https://www.youtube.com/watch?v=pOKy3RZbSws&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=14)

As a summary, here is a visual representation of [15 sorting algorithms](https://www.youtube.com/watch?v=kPRA0W1kECg).
If you need more detail on this subject, see the "Sorting" section in [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)

**[⬆ back to top](#table-of-contents)**

## Graphs

Graphs can be used to represent many problems in computer science, so this section is long, like trees and sorting.

- Notes:
    - There are 4 basic ways to represent a graph in memory:
        - objects and pointers
        - adjacency matrix
        - adjacency list
        - adjacency map
    - Familiarize yourself with each representation and its pros & cons
    - BFS and DFS - know their computational complexity, their trade-offs, and how to implement them in real code
    - When asked a question, look for a graph-based solution first, then move on if none

- [ ] MIT(videos):
    - [ ] [Breadth-First Search](https://www.youtube.com/watch?v=oFVYVzlvk9c&t=14s&ab_channel=MITOpenCourseWare)
    - [ ] [Depth-First Search](https://www.youtube.com/watch?v=IBfWDYSffUU&t=32s&ab_channel=MITOpenCourseWare)

- [ ] Skiena Lectures - great intro:
    - [ ] [CSE373 2020 - Lecture 10 - Graph Data Structures (video)](https://www.youtube.com/watch?v=Sjk0xqWWPCc&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=10)
    - [ ] [CSE373 2020 - Lecture 11 - Graph Traversal (video)](https://www.youtube.com/watch?v=ZTwjXj81NVY&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=11)
    - [ ] [CSE373 2020 - Lecture 12 - Depth First Search (video)](https://www.youtube.com/watch?v=KyordYB3BOs&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=12)
    - [ ] [CSE373 2020 - Lecture 13 - Minimum Spanning Trees (video)](https://www.youtube.com/watch?v=oolm2VnJUKw&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=13)
    - [ ] [CSE373 2020 - Lecture 14 - Minimum Spanning Trees (con't) (video)](https://www.youtube.com/watch?v=RktgPx0MarY&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=14)
    - [ ] [CSE373 2020 - Lecture 15 - Graph Algorithms (con't 2) (video)](https://www.youtube.com/watch?v=MUe5DXRhyAo&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=15)

- [ ] Graphs (review and more):

    - [ ] [6.006 Single-Source Shortest Paths Problem (video)](https://www.youtube.com/watch?v=Aa2sqUhIn-E&index=15&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.006 Dijkstra (video)](https://www.youtube.com/watch?v=NSHizBK9JD8&t=1731s&ab_channel=MITOpenCourseWare)
    - [ ] [6.006 Bellman-Ford (video)](https://www.youtube.com/watch?v=f9cVS_URPc0&ab_channel=MITOpenCourseWare)
    - [ ] [6.006 Speeding Up Dijkstra (video)](https://www.youtube.com/watch?v=CHvQ3q_gJ7E&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=18)
    - [ ] [Aduni: Graph Algorithms I - Topological Sorting, Minimum Spanning Trees, Prim's Algorithm -  Lecture 6 (video)]( https://www.youtube.com/watch?v=i_AQT_XfvD8&index=6&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [ ] [Aduni: Graph Algorithms II - DFS, BFS, Kruskal's Algorithm, Union Find Data Structure - Lecture 7 (video)]( https://www.youtube.com/watch?v=ufj5_bppBsA&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=7)
    - [ ] [Aduni: Graph Algorithms III: Shortest Path - Lecture 8 (video)](https://www.youtube.com/watch?v=DiedsPsMKXc&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=8)
    - [ ] [Aduni: Graph Alg. IV: Intro to geometric algorithms - Lecture 9 (video)](https://www.youtube.com/watch?v=XIAQRlNkJAw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=9)
    - [ ] [CS 61B 2014: Weighted graphs (video)](https://archive.org/details/ucberkeley_webcast_zFbq8vOZ_0k)
    - [ ] [Greedy Algorithms: Minimum Spanning Tree (video)](https://www.youtube.com/watch?v=tKwnms5iRBU&index=16&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [Strongly Connected Components Kosaraju's Algorithm Graph Algorithm (video)](https://www.youtube.com/watch?v=RpgcYiky7uw)
    - [ ] [[Review] Shortest Path Algorithms (playlist) in 16 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZO-Y-H3xIC9DGSfVYJng9Yw)
    - [ ] [[Review] Minimum Spanning Trees (playlist) in 4 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZObEi3Hf6lmyW-CBfs7nkOV)

- Full Coursera Course:
    - [ ] [Algorithms on Graphs (video)](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome)

- I'll implement:
    - [ ] DFS with adjacency list (recursive)
    - [ ] DFS with adjacency list (iterative with stack)
    - [ ] DFS with adjacency matrix (recursive)
    - [ ] DFS with adjacency matrix (iterative with stack)
    - [ ] BFS with adjacency list
    - [ ] BFS with adjacency matrix
    - [ ] single-source shortest path (Dijkstra)
    - [ ] minimum spanning tree
    - DFS-based algorithms (see Aduni videos above):
        - [ ] check for a cycle (needed for topological sort, since we'll check for the cycle before starting)
        - [ ] topological sort
        - [ ] count connected components in a graph
        - [ ] list strongly connected components
        - [ ] check for bipartite graph

**[⬆ back to top](#table-of-contents)**

## Even More Knowledge

- ### Recursion
    - [ ] Stanford lectures on recursion & backtracking:
        - [ ] [Lecture 8 | Programming Abstractions (video)](https://www.youtube.com/watch?v=gl3emqCuueQ&list=PLFE6E58F856038C69&index=8)
        - [ ] [Lecture 9 | Programming Abstractions (video)](https://www.youtube.com/watch?v=uFJhEPrbycQ&list=PLFE6E58F856038C69&index=9)
        - [ ] [Lecture 10 | Programming Abstractions (video)](https://www.youtube.com/watch?v=NdF1QDTRkck&index=10&list=PLFE6E58F856038C69)
        - [ ] [Lecture 11 | Programming Abstractions (video)](https://www.youtube.com/watch?v=p-gpaIGRCQI&list=PLFE6E58F856038C69&index=11)
    - When it is appropriate to use it?
    - How is tail recursion better than not?
        - [ ] [What Is Tail Recursion Why Is It So Bad?](https://www.quora.com/What-is-tail-recursion-Why-is-it-so-bad)
        - [ ] [Tail Recursion (video)](https://www.coursera.org/lecture/programming-languages/tail-recursion-YZic1)
    - [ ] [5 Simple Steps for Solving Any Recursive Problem(video)](https://youtu.be/ngCos392W4w)

	Backtracking Blueprint: [Java](https://leetcode.com/problems/combination-sum/discuss/16502/A-general-approach-to-backtracking-questions-in-Java-(Subsets-Permutations-Combination-Sum-Palindrome-Partitioning))
	[Python](https://leetcode.com/problems/combination-sum/discuss/429538/General-Backtracking-questions-solutions-in-Python-for-reference-%3A)
- ### Dynamic Programming
    - You probably won't see any dynamic programming problems in your interview, but it's worth being able to recognize a
    problem as being a candidate for dynamic programming.
    - This subject can be pretty difficult, as each DP soluble problem must be defined as a recursion relation, and coming up with it can be tricky.
    - I suggest looking at many examples of DP problems until you have a solid understanding of the pattern involved.
    - [ ] Videos:
        - [ ] [Skiena: CSE373 2020 - Lecture 19 - Introduction to Dynamic Programming (video)](https://www.youtube.com/watch?v=wAA0AMfcJHQ&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=18)
        - [ ] [Skiena: CSE373 2020 - Lecture 20 - Edit Distance (video)](https://www.youtube.com/watch?v=T3A4jlHlhtA&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=19)
        - [ ] [Skiena: CSE373 2020 - Lecture 20 - Edit Distance (continued) (video)](https://www.youtube.com/watch?v=iPnPVcZmRbE&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=20)
        - [ ] [Skiena: CSE373 2020 - Lecture 21 - Dynamic Programming (video)](https://www.youtube.com/watch?v=2xPE4Wq8coQ&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=21)
        - [ ] [Skiena: CSE373 2020 - Lecture 22 - Dynamic Programming and Review (video)](https://www.youtube.com/watch?v=Yh3RzqQGsyI&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=22)
        - [ ] [Simonson: Dynamic Programming 0 (starts at 59:18) (video)](https://youtu.be/J5aJEcOr6Eo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3558)
        - [ ] [Simonson: Dynamic Programming I - Lecture 11 (video)](https://www.youtube.com/watch?v=0EzHjQ_SOeU&index=11&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [ ] [Simonson: Dynamic programming II - Lecture 12 (video)](https://www.youtube.com/watch?v=v1qiRwuJU7g&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=12)
        - [ ] List of individual DP problems (each is short):
            [Dynamic Programming (video)](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)
    - [ ] Yale Lecture notes:
        - [ ] [Dynamic Programming](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#dynamicProgramming)
    - [ ] Coursera:
        - [ ] [The RNA secondary structure problem (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/80RrW/the-rna-secondary-structure-problem)
        - [ ] [A dynamic programming algorithm (video)](https://www.coursera.org/lecture/algorithmic-thinking-2/a-dynamic-programming-algorithm-PSonq)
        - [ ] [Illustrating the DP algorithm (video)](https://www.coursera.org/lecture/algorithmic-thinking-2/illustrating-the-dp-algorithm-oUEK2)
        - [ ] [Running time of the DP algorithm (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/nfK2r/running-time-of-the-dp-algorithm)
        - [ ] [DP vs. recursive implementation (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/M999a/dp-vs-recursive-implementation)
        - [ ] [Global pairwise sequence alignment (video)](https://www.coursera.org/lecture/algorithmic-thinking-2/global-pairwise-sequence-alignment-UZ7o6)
        - [ ] [Local pairwise sequence alignment (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/WnNau/local-pairwise-sequence-alignment)

- ### Design patterns
    - [ ] [Quick UML review (video)](https://www.youtube.com/watch?v=3cmzqZzwNDM&list=PLGLfVvz_LVvQ5G-LdJ8RLqe-ndo7QITYc&index=3)
    - [ ] Learn these patterns:
        - [ ] strategy
        - [ ] singleton
        - [ ] adapter
        - [ ] prototype
        - [ ] decorator
        - [ ] visitor
        - [ ] factory, abstract factory
        - [ ] facade
        - [ ] observer
        - [ ] proxy
        - [ ] delegate
        - [ ] command
        - [ ] state
        - [ ] memento
        - [ ] iterator
        - [ ] composite
        - [ ] flyweight
    - [ ] [Series of videos (27 videos)](https://www.youtube.com/playlist?list=PLF206E906175C7E07)
    - [ ] [Book: Head First Design Patterns](https://www.amazon.com/Head-First-Design-Patterns-Freeman/dp/0596007124)
        - I know the canonical book is "Design Patterns: Elements of Reusable Object-Oriented Software", but Head First is great for beginners to OO.
    - [Handy reference: 101 Design Patterns & Tips for Developers](https://sourcemaking.com/design-patterns-and-tips)

- ### Combinatorics (n choose k) & Probability
    - [ ] [Math Skills: How to find Factorial, Permutation, and Combination (Choose) (video)](https://www.youtube.com/watch?v=8RRo6Ti9d0U)
    - [ ] [Make School: Probability (video)](https://www.youtube.com/watch?v=sZkAAk9Wwa4)
    - [ ] [Make School: More Probability and Markov Chains (video)](https://www.youtube.com/watch?v=dNaJg-mLobQ)
    - [ ] Khan Academy:
        - Course layout:
            - [ ] [Basic Theoretical Probability](https://www.khanacademy.org/math/probability/probability-and-combinatorics-topic)
        - Just the videos - 41 (each are simple and each are short):
            - [ ] [Probability Explained (video)](https://www.youtube.com/watch?v=uzkc-qNVoOk&list=PLC58778F28211FA19)

- ### NP, NP-Complete and Approximation Algorithms
    - Know about the most famous classes of NP-complete problems, such as the traveling salesman and the knapsack problem,
        and be able to recognize them when an interviewer asks you them in disguise.
    - Know what NP-complete means.
    - [ ] [Computational Complexity (video)](https://www.youtube.com/watch?v=moPtwq_cVH8&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=23)
    - [ ] Simonson:
        - [ ] [Greedy Algs. II & Intro to NP-Completeness (video)](https://youtu.be/qcGnJ47Smlo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=2939)
        - [ ] [NP Completeness II & Reductions (video)](https://www.youtube.com/watch?v=e0tGC6ZQdQE&index=16&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [ ] [NP Completeness III (Video)](https://www.youtube.com/watch?v=fCX1BGT3wjE&index=17&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [ ] [NP Completeness IV (video)](https://www.youtube.com/watch?v=NKLDp3Rch3M&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=18)
    - [ ] Skiena:
        - [ ] [CSE373 2020 - Lecture 23 - NP-Completeness (video)](https://www.youtube.com/watch?v=ItHp5laE1VE&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=23)
        - [ ] [CSE373 2020 - Lecture 24 - Satisfiability (video)](https://www.youtube.com/watch?v=inaFJeCzGxU&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=24)
        - [ ] [CSE373 2020 - Lecture 25 - More NP-Completeness (video)](https://www.youtube.com/watch?v=B-bhKxjZLlc&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=25)
        - [ ] [CSE373 2020 - Lecture 26 - NP-Completeness Challenge (video)](https://www.youtube.com/watch?v=_EzetTkG_Cc&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=26)
    - [ ] [Complexity: P, NP, NP-completeness, Reductions (video)](https://www.youtube.com/watch?v=eHZifpgyH_4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=22)
    - [ ] [Complexity: Approximation Algorithms (video)](https://www.youtube.com/watch?v=MEz1J9wY2iM&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=24)
    - [ ] [Complexity: Fixed-Parameter Algorithms (video)](https://www.youtube.com/watch?v=4q-jmGrmxKs&index=25&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - Peter Norvig discusses near-optimal solutions to the traveling salesman problem:
        - [Jupyter Notebook](http://nbviewer.jupyter.org/url/norvig.com/ipython/TSP.ipynb)
    - Pages 1048 - 1140 in CLRS if you have it.

- ### How computers process a program

    - [ ] [How CPU executes a program (video)](https://www.youtube.com/watch?v=XM4lGflQFvA)
    - [ ] [How computers calculate - ALU (video)](https://youtu.be/1I5ZMmrOfnA)
    - [ ] [Registers and RAM (video)](https://youtu.be/fpnE6UAfbtU)
    - [ ] [The Central Processing Unit (CPU) (video)](https://youtu.be/FZGugFqdr60)
    - [ ] [Instructions and Programs (video)](https://youtu.be/zltgXvg6r3k)
- ### Caches
    - [ ] LRU cache:
        - [ ] [The Magic of LRU Cache (100 Days of Google Dev) (video)](https://www.youtube.com/watch?v=R5ON3iwx78M)
        - [ ] [Implementing LRU (video)](https://www.youtube.com/watch?v=bq6N7Ym81iI)
        - [ ] [LeetCode - 146 LRU Cache (C++) (video)](https://www.youtube.com/watch?v=8-FZRAjR7qU)
    - [ ] CPU cache:
        - [ ] [MIT 6.004 L15: The Memory Hierarchy (video)](https://www.youtube.com/watch?v=vjYF_fAZI5E&list=PLrRW1w6CGAcXbMtDFj205vALOGmiRc82-&index=24)
        - [ ] [MIT 6.004 L16: Cache Issues (video)](https://www.youtube.com/watch?v=ajgC3-pyGlk&index=25&list=PLrRW1w6CGAcXbMtDFj205vALOGmiRc82-)

- ### Processes and Threads
    - [ ] Computer Science 162 - Operating Systems (25 videos):
        - for processes and threads see videos 1-11
        - [Operating Systems and System Programming (video)](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iBDyz-ba4yDskqMDY6A1w_c)
    - [What Is The Difference Between A Process And A Thread?](https://www.quora.com/What-is-the-difference-between-a-process-and-a-thread)
    - Covers:
        - Processes, Threads, Concurrency issues
            - Difference between processes and threads
            - Processes
            - Threads
            - Locks
            - Mutexes
            - Semaphores
            - Monitors
            - How do they work?
            - Deadlock
            - Livelock
        - CPU activity, interrupts, context switching
        - Modern concurrency constructs with multicore processors
        - [Paging, segmentation, and virtual memory (video)](https://youtu.be/O4nwUqQodAg)
        - [Interrupts (video)](https://youtu.be/iKlAWIKEyuw)
        - Process resource needs (memory: code, static storage, stack, heap, and also file descriptors, i/o)
        - Thread resource needs (shares above (minus stack) with other threads in the same process but each has its own PC, stack counter, registers, and stack)
        - Forking is really copy on write (read-only) until the new process writes to memory, then it does a full copy.
        - Context switching
            - [How context switching is initiated by the operating system and underlying hardware?](https://www.javatpoint.com/what-is-the-context-switching-in-the-operating-system)
    - [ ] [threads in C++ (series - 10 videos)](https://www.youtube.com/playlist?list=PL5jc9xFGsL8E12so1wlMS0r0hTQoJL74M)
    - [ ] [CS 377 Spring '14: Operating Systems from University of Massachusetts](https://www.youtube.com/playlist?list=PLacuG5pysFbDQU8kKxbUh4K5c1iL5_k7k)
    - [ ] concurrency in Python (videos):
        - [ ] [Short series on threads](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVMONJWJkmUh6_p8g4F2oy1)
        - [ ] [Python Threads](https://www.youtube.com/watch?v=Bs7vPNbB9JM)
        - [ ] [Understanding the Python GIL (2010)](https://www.youtube.com/watch?v=Obt-vMVdM8s)
            - [reference](http://www.dabeaz.com/GIL)
        - [ ] [David Beazley - Python Concurrency From the Ground Up LIVE! - PyCon 2015](https://www.youtube.com/watch?v=MCs5OvhV9S4)
        - [ ] [Keynote David Beazley - Topics of Interest (Python Asyncio)](https://www.youtube.com/watch?v=ZzfHjytDceU)
        - [ ] [Mutex in Python](https://www.youtube.com/watch?v=0zaPs8OtyKY)

- ### Testing
    - To cover:
        - how unit testing works
        - what are mock objects
        - what is integration testing
        - what is dependency injection
    - [ ] [Agile Software Testing with James Bach (video)](https://www.youtube.com/watch?v=SAhJf36_u5U)
    - [ ] [Open Lecture by James Bach on Software Testing (video)](https://www.youtube.com/watch?v=ILkT_HV9DVU)
    - [ ] [Steve Freeman - Test-Driven Development (that’s not what we meant) (video)](https://vimeo.com/83960706)
        - [slides](http://gotocon.com/dl/goto-berlin-2013/slides/SteveFreeman_TestDrivenDevelopmentThatsNotWhatWeMeant.pdf)
    - [ ] Dependency injection:
        - [ ] [video](https://www.youtube.com/watch?v=IKD2-MAkXyQ)
        - [ ] [Tao Of Testing](http://jasonpolites.github.io/tao-of-testing/ch3-1.1.html)
    - [ ] [How to write tests](http://jasonpolites.github.io/tao-of-testing/ch4-1.1.html)

- ### String searching & manipulations
    - [ ] [Sedgewick - Suffix Arrays (video)](https://www.coursera.org/learn/algorithms-part2/lecture/TH18W/suffix-arrays)
    - [ ] [Sedgewick - Substring Search (videos)](https://www.coursera.org/learn/algorithms-part2/home/week/4)
        - [ ] [1. Introduction to Substring Search](https://www.coursera.org/lecture/algorithms-part2/introduction-to-substring-search-n3ZpG)
        - [ ] [2. Brute-Force Substring Search](https://www.coursera.org/learn/algorithms-part2/lecture/2Kn5i/brute-force-substring-search)
        - [ ] [3. Knuth-Morris Pratt](https://www.coursera.org/learn/algorithms-part2/lecture/TAtDr/knuth-morris-pratt)
        - [ ] [4. Boyer-Moore](https://www.coursera.org/learn/algorithms-part2/lecture/CYxOT/boyer-moore)
        - [ ] [5. Rabin-Karp](https://www.coursera.org/lecture/algorithms-part2/rabin-karp-3KiqT)
    - [ ] [Search pattern in a text (video)](https://www.coursera.org/learn/data-structures/lecture/tAfHI/search-pattern-in-text)

    If you need more detail on this subject, see the "String Matching" section in [Additional Detail on Some Subjects](#additional-detail-on-some-subjects).

- ### Tries
    - Note there are different kinds of tries. Some have prefixes, some don't, and some use strings instead of bits
        to track the path
    - I read through the code, but will not implement
    - [ ] [Sedgewick - Tries (3 videos)](https://www.coursera.org/learn/algorithms-part2/home/week/4)
        - [ ] [1. R Way Tries](https://www.coursera.org/learn/algorithms-part2/lecture/CPVdr/r-way-tries)
        - [ ] [2. Ternary Search Tries](https://www.coursera.org/learn/algorithms-part2/lecture/yQM8K/ternary-search-tries)
        - [ ] [3. Character Based Operations](https://www.coursera.org/learn/algorithms-part2/lecture/jwNmV/character-based-operations)
    - [ ] [Notes on Data Structures and Programming Techniques](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Tries)
    - [ ] Short course videos:
        - [ ] [Introduction To Tries (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/08Xyf/core-introduction-to-tries)
        - [ ] [Performance Of Tries (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/PvlZW/core-performance-of-tries)
        - [ ] [Implementing A Trie (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/DFvd3/core-implementing-a-trie)
    - [ ] [The Trie: A Neglected Data Structure](https://www.toptal.com/java/the-trie-a-neglected-data-structure)
    - [ ] [TopCoder - Using Tries](https://www.topcoder.com/thrive/articles/Using%20Tries)
    - [ ] [Stanford Lecture (real-world use case) (video)](https://www.youtube.com/watch?v=TJ8SkcUSdbU)
    - [ ] [MIT, Advanced Data Structures, Strings (can get pretty obscure about halfway through) (video)](https://www.youtube.com/watch?v=NinWEPPrkDQ&index=16&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf)

- ### Floating Point Numbers
    - [ ] simple 8-bit: [Representation of Floating Point Numbers - 1 (video - there is an error in calculations - see video description)](https://www.youtube.com/watch?v=ji3SfClm8TU)

- ### Unicode
    - [ ] [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets]( http://www.joelonsoftware.com/articles/Unicode.html)
    - [ ] [What Every Programmer Absolutely, Positively Needs To Know About Encodings And Character Sets To Work With Text](http://kunststube.net/encoding/)

- ### Endianness
    - [ ] [Big And Little Endian](https://web.archive.org/web/20180107141940/http://www.cs.umd.edu:80/class/sum2003/cmsc311/Notes/Data/endian.html)
    - [ ] [Big Endian Vs Little Endian (video)](https://www.youtube.com/watch?v=JrNF0KRAlyo)
    - [ ] [Big And Little Endian Inside/Out (video)](https://www.youtube.com/watch?v=oBSuXP-1Tc0)
        - Very technical talk for kernel devs. Don't worry if most is over your head.
        - The first half is enough.

- ### Networking
    - **If you have networking experience or want to be a reliability engineer or operations engineer, expect questions**
    - Otherwise, this is just good to know
    - [ ] [Khan Academy](https://www.khanacademy.org/computing/code-org/computers-and-the-internet)
    - [ ] [UDP and TCP: Comparison of Transport Protocols (video)](https://www.youtube.com/watch?v=Vdc8TCESIg8)
    - [ ] [TCP/IP and the OSI Model Explained! (video)](https://www.youtube.com/watch?v=e5DEVa9eSN0)
    - [ ] [Packet Transmission across the Internet. Networking & TCP/IP tutorial. (video)](https://www.youtube.com/watch?v=nomyRJehhnM)
    - [ ] [HTTP (video)](https://www.youtube.com/watch?v=WGJrLqtX7As)
    - [ ] [SSL and HTTPS (video)](https://www.youtube.com/watch?v=S2iBR2ZlZf0)
    - [ ] [SSL/TLS (video)](https://www.youtube.com/watch?v=Rp3iZUvXWlM)
    - [ ] [HTTP 2.0 (video)](https://www.youtube.com/watch?v=E9FxNzv1Tr8)
    - [ ] [Video Series (21 videos) (video)](https://www.youtube.com/playlist?list=PLEbnTDJUr_IegfoqO4iPnPYQui46QqT0j)
    - [ ] [Subnetting Demystified - Part 5 CIDR Notation (video)](https://www.youtube.com/watch?v=t5xYI0jzOf4)
    - [ ] Sockets:
        - [ ] [Java - Sockets - Introduction (video)](https://www.youtube.com/watch?v=6G_W54zuadg&t=6s)
        - [ ] [Socket Programming (video)](https://www.youtube.com/watch?v=G75vN2mnJeQ)

---

**[⬆ back to top](#table-of-contents)**

## Final Review

    This section will have shorter videos that you can watch pretty quickly to review most of the important concepts.
    It's nice if you want a refresher often.

- [ ] Series of 2-3 minutes short subject videos (23 videos)
    - [Videos](https://www.youtube.com/watch?v=r4r1DZcx1cM&list=PLmVb1OknmNJuC5POdcDv5oCS7_OUkDgpj&index=22)
- [ ] Series of 2-5 minutes short subject videos - Michael Sambol (48 videos):
    - [Videos](https://www.youtube.com/@MichaelSambol)
    - [Code Examples](https://github.com/msambol/dsa)
- [ ] [Sedgewick Videos - Algorithms I](https://www.coursera.org/learn/algorithms-part1)
- [ ] [Sedgewick Videos - Algorithms II](https://www.coursera.org/learn/algorithms-part2)

---

**[⬆ back to top](#table-of-contents)**

## Update Your Resume

- See Resume prep information in the books: "Cracking The Coding Interview" and "Programming Interviews Exposed"
- ["This Is What A GOOD Resume Should Look Like" by Gayle McDowell (author of Cracking the Coding Interview)](https://www.careercup.com/resume),
    - Note by the author: "This is for a US-focused resume. CVs for India and other countries have different expectations, although many of the points will be the same."
- ["Step-by-step resume guide" by Tech Interview Handbook](https://www.techinterviewhandbook.org/resume/guide)
    - Detailed guide on how to set up your resume from scratch, write effective resume content, optimize it, and test your resume

**AI Engineer-specific resume tips:**
- **Lead with projects, not job descriptions.** AI companies want to see what you built, not just where you worked.
- **Quantify ML impact**: "Reduced model latency by 40% via INT8 quantization", "Improved recall@10 from 72% to 89% by adding re-ranker"
- **Highlight open-source contributions** to ML repos (HuggingFace, PyTorch, LangChain, etc.)
- **Include Kaggle rankings** — even a silver medal shows you can compete on real data problems
- **Show your stack**: Python, PyTorch/TensorFlow, MLflow/W&B, LangChain/LlamaIndex, FastAPI, Docker, AWS/GCP/Azure
- **List target companies** you're interviewing at: OpenAI, Anthropic, Google DeepMind, Meta AI, Microsoft AI, Cohere, Mistral, Stability AI, and major tech companies with AI teams

**[⬆ back to top](#table-of-contents)**

## Interview Process & General Interview Prep

- [ ] [How to Pass the Engineering Interview in 2021](https://davidbyttow.medium.com/how-to-pass-the-engineering-interview-in-2021-45f1b389a1)
- [ ] [Demystifying Tech Recruiting](https://www.youtube.com/watch?v=N233T0epWTs)
- [ ] How to Get a Job at the Big 4:
    - [ ] [How to Get a Job at the Big 4 - Amazon, Facebook, Google & Microsoft (video)](https://www.youtube.com/watch?v=YJZCUhxNCv8)
    - [ ] [How to Get a Job at the Big 4.1 (Follow-up video)](https://www.youtube.com/watch?v=6790FVXWBw8&feature=youtu.be)
- [ ] Cracking The Coding Interview Set 1:
    - [ ] [Gayle L McDowell - Cracking The Coding Interview (video)](https://www.youtube.com/watch?v=rEJzOhC5ZtQ)
    - [ ] [Cracking the Coding Interview with Author Gayle Laakmann McDowell (video)](https://www.youtube.com/watch?v=aClxtDcdpsQ)
- [ ] Cracking the Facebook Coding Interview:
    - [ ] [The Approach](https://www.youtube.com/watch?v=wCl9kvQGHPI)
    - [ ] [Problem Walkthrough](https://www.youtube.com/watch?v=4UWDyJq8jZg)
- Prep Courses:
    - [Python for Data Structures, Algorithms, and Interviews (paid course)](https://www.udemy.com/python-for-data-structures-algorithms-and-interviews/):
        - A Python-centric interview prep course that covers data structures, algorithms, mock interviews, and much more.
    - [Intro to Data Structures and Algorithms using Python (Udacity free course)](https://www.udacity.com/course/data-structures-and-algorithms-in-python--ud513):
        - A free Python-centric data structures and algorithms course.
    - [Data Structures and Algorithms Nanodegree! (Udacity paid Nanodegree)](https://www.udacity.com/course/data-structures-and-algorithms-nanodegree--nd256):
        - Get hands-on practice with over 100 data structures and algorithm exercises and guidance from a dedicated mentor to help prepare you for interviews and on-the-job scenarios.
    - [Grokking the Behavioral Interview (Educative free course)](https://www.educative.io/courses/grokking-the-behavioral-interview):
        - Many times, it’s not your technical competency that holds you back from landing your dream job, it’s how you perform on the behavioral interview.
    - [AlgoMonster (paid course with free content)](https://algo.monster/?utm_campaign=jwasham&utm_medium=referral&utm_content=coding-interview-university&utm_source=github):
      - The crash course for LeetCode. Covers all the patterns condensed from thousands of questions.

Mock Interviews:
- [Gainlo.co: Mock interviewers from big companies](http://www.gainlo.co/#!/) - I used this and it helped me relax for the phone screen and on-site interview
- [Pramp: Mock interviews from/with peers](https://www.pramp.com/) - a peer-to-peer model to practice interviews
- [interviewing.io: Practice mock interview with senior engineers](https://interviewing.io) - anonymous algorithmic/systems design interviews with senior engineers from FAANG anonymously
- [Meetapro: Mock interviews with top FAANG interviewers](https://meetapro.com/?utm_source=ciu) - an Airbnb-style mock interview/coaching platform.
- [Hello Interview: Mock Interviews with Expert Coaches and AI](https://www.hellointerview.com/?utm_source=ciu) - interview directly with AI or with FAANG staff engineers and managers.
- [Codemia: Practice system design problems with AI or community solutions and feedback](https://codemia.io/?utm_source=ciu) - Practice system design problems via AI practice tool. Share your solution with the community to get human feedback as well.

**[⬆ back to top](#table-of-contents)**

## Be thinking of for when the interview comes

Think of about 20 interview questions you'll get, along with the lines of the items below. Have at least one answer for each.
Have a story, not just data, about something you accomplished.

**Standard behavioral questions:**
- Why do you want this job?
- What's a tough problem you've solved?
- Biggest challenges faced?
- Best/worst designs seen?
- Ideas for improving an existing product
- How do you work best, as an individual and as part of a team?
- Which of your skills or experiences would be assets in the role and why?
- What did you most enjoy at [job x / project y]?
- What was the biggest challenge you faced at [job x / project y]?
- What was the hardest bug you faced at [job x / project y]?
- What did you learn at [job x / project y]?
- What would you have done better at [job x / project y]?

**AI Engineer-specific behavioral/technical questions to prepare for:**
- Walk me through a model you trained end-to-end: data, architecture, training, evaluation, deployment.
- How did you decide which model architecture to use for [task]?
- Tell me about a time your model performed worse in production than in evaluation. What happened and how did you fix it?
- How would you handle a class imbalance problem in a production fraud detection system?
- Describe your approach to debugging a suddenly degrading ML model in production.
- What's your process for evaluating an LLM-based feature? How do you decide if it's good enough to ship?
- How would you reduce the latency of an LLM inference endpoint by 5x with minimal accuracy loss?
- How do you think about bias and fairness in an ML model you're building?
- Walk me through how you would design a RAG pipeline for [use case].
- Tell me about a trade-off you made between model accuracy and inference cost.

**[⬆ back to top](#table-of-contents)**

## Have questions for the interviewer

Some of mine (I already may know the answers, but want their opinion or team perspective):

- How large is your team?
- What does your dev cycle look like? Do you do waterfall/sprints/agile?
- Are rushes to deadlines common? Or is there flexibility?
- How are decisions made in your team?
- How many meetings do you have per week?
- Do you feel your work environment helps you concentrate?
- What are you working on?
- What do you like about it?
- What is the work life like?
- How is the work/life balance?

**[⬆ back to top](#table-of-contents)**

## Once You've Got The Job

Congratulations!

Keep learning.

You're never really done.

> *"The pace of progress in AI is accelerating. The best engineers — at every level — are those who stay curious, keep building, and treat every project as a chance to understand something deeper. This is a marathon, not a sprint, and the finish line keeps moving."*
>
> — **Demis Hassabis**, CEO of Google DeepMind

---

    *****************************************************************************************************
    *****************************************************************************************************

    Everything below this point is optional. It is NOT needed for an entry-level interview.
    However, by studying these, you'll get greater exposure to more CS concepts and will be better prepared for
    any software engineering job. You'll be a much more well-rounded software engineer.

    *****************************************************************************************************
    *****************************************************************************************************

---

**[⬆ back to top](#table-of-contents)**

## Additional Books

    These are here so you can dive into a topic you find interesting.

### AI/ML Books (Highly Recommended for AI Engineers)

- [Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (Géron)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
    - The main practical ML engineering book — covers the full Python ML stack
- [Deep Learning (Goodfellow, Bengio, Courville — free online)](https://www.deeplearningbook.org/)
    - Theoretical foundations of deep learning
- [Designing Machine Learning Systems (Chip Huyen)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107963/)
    - Production ML/MLOps — essential reading for AI Engineers
- [The Machine Learning Engineering (Burkov)](http://www.mlebook.com/)
    - Practical ML engineering — free to read online
- [Machine Learning System Design Interview (Aminian & Xu)](https://www.amazon.com/Machine-Learning-System-Design-Interview/dp/1736049127)
    - Interview-focused ML system design
- [Speech and Language Processing (Jurafsky & Martin — free online)](https://web.stanford.edu/~jurafsky/slp3/)
    - NLP foundations — covers everything from n-grams to Transformers
- [Pattern Recognition and Machine Learning (Bishop)](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/)
    - Advanced probabilistic ML theory (optional — for those who want depth)

### Classic CS Books

- [The Unix Programming Environment](https://www.amazon.com/dp/013937681X)
    - An oldie but a goodie
- [The Linux Command Line: A Complete Introduction](https://www.amazon.com/dp/1593273894/)
    - A modern option
- [TCP/IP Illustrated Series](https://en.wikipedia.org/wiki/TCP/IP_Illustrated)
- [Head First Design Patterns](https://www.amazon.com/gp/product/0596007124/)
    - A gentle introduction to design patterns
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)
    - AKA the "Gang Of Four" book or GOF
    - The canonical design patterns book
- [Algorithm Design Manual](http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202) (Skiena)
    - As a review and problem-recognition
    - The algorithm catalog portion is well beyond the scope of difficulty you'll get in an interview
    - This book has 2 parts:
        - Class textbook on data structures and algorithms
            - Pros:
                - Is a good review as any algorithms textbook would be
                - Nice stories from his experiences solving problems in industry and academia
                - Code examples in C
            - Cons:
                - Can be as dense or impenetrable as CLRS, and in some cases, CLRS may be a better alternative for some subjects
                - Chapters 7, 8, and 9 can be painful to try to follow, as some items are not explained well or require more brain than I have
                - Don't get me wrong: I like Skiena, his teaching style, and mannerisms, but I may not be Stony Brook material
        - Algorithm catalog:
            - This is the real reason you buy this book.
            - This book is better as an algorithm reference, and not something you read cover to cover.
    - Can rent it on Kindle
    - Answers:
        - [Solutions](https://web.archive.org/web/20150404194210/http://www.algorithm.cs.sunysb.edu/algowiki/index.php/The_Algorithms_Design_Manual_(Second_Edition))
    - [Errata](http://www3.cs.stonybrook.edu/~skiena/algorist/book/errata)
- [Algorithm](http://jeffe.cs.illinois.edu/teaching/algorithms/) (Jeff Erickson)
- [Write Great Code: Volume 1: Understanding the Machine](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
    - The book was published in 2004, and is somewhat outdated, but it's a terrific resource for understanding a computer in brief
    - The author invented [HLA](https://en.wikipedia.org/wiki/High_Level_Assembly), so take mentions and examples in HLA with a grain of salt. Not widely used, but decent examples of what assembly looks like
    - These chapters are worth the read to give you a nice foundation:
        - Chapter 2 - Numeric Representation
        - Chapter 3 - Binary Arithmetic and Bit Operations
        - Chapter 4 - Floating-Point Representation
        - Chapter 5 - Character Representation
        - Chapter 6 - Memory Organization and Access
        - Chapter 7 - Composite Data Types and Memory Objects
        - Chapter 9 - CPU Architecture
        - Chapter 10 - Instruction Set Architecture
        - Chapter 11 - Memory Architecture and Organization
- [Introduction to Algorithms](https://www.amazon.com/Introduction-Algorithms-fourth-Thomas-Cormen/dp/026204630X)
    - **Important:** Reading this book will only have limited value. This book is a great review of algorithms and data structures, but won't teach you how to write good code. You have to be able to code a decent solution efficiently
    - AKA CLR, sometimes CLRS, because Stein was late to the game
- [Computer Architecture, Sixth Edition: A Quantitative Approach](https://www.amazon.com/dp/0128119055)
    - For a richer, more up-to-date (2017), but longer treatment

**[⬆ back to top](#table-of-contents)**

## System Design, Scalability, Data Handling

**You can expect system design questions if you have 4+ years of experience. For AI Engineer roles, expect ML system design questions.**

- Scalability and System Design are very large topics with many topics and resources, since
      there is a lot to consider when designing a software/hardware system that can scale.
      Expect to spend quite a bit of time on this
- Considerations:
    - Scalability
        - Distill large data sets to single values
        - Transform one data set to another
        - Handling obscenely large amounts of data
    - System design
        - features sets
        - interfaces
        - class hierarchies
        - designing a system under certain constraints
        - simplicity and robustness
        - tradeoffs
        - performance analysis and optimization
- [ ] **START HERE**: [The System Design Primer](https://github.com/donnemartin/system-design-primer)
- [ ] [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
- [ ] [How Do I Prepare To Answer Design Questions In A Technical Interview?](https://www.quora.com/How-do-I-prepare-to-answer-design-questions-in-a-technical-interview?redirected_qid=1500023)
- [ ] [8 steps guide to ace your system design interview](https://javascript.plainenglish.io/8-steps-guide-to-ace-a-system-design-interview-7a5a797f4d7d)
- [ ] [Database Normalization - 1NF, 2NF, 3NF and 4NF (video)](https://www.youtube.com/watch?v=UrYLYV7WSHM)
- [ ] [System Design Interview](https://github.com/checkcheckzz/system-design-interview) - There are a lot of resources in this one. Look through the articles and examples. I put some of them below
- [ ] [How to ace a systems design interview](https://web.archive.org/web/20120716060051/http://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
- [ ] [Numbers Everyone Should Know](http://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
- [ ] [How long does it take to make a context switch?](http://blog.tsunanet.net/2010/11/how-long-does-it-take-to-make-context.html)
- [ ] [Transactions Across Datacenters (video)](https://www.youtube.com/watch?v=srOgpXECblk)
- [ ] [A plain English introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
- [ ] [MIT 6.824: Distributed Systems, Spring 2020 (20 videos)](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)
- [ ] Consensus Algorithms:
    - [ ] Paxos - [Paxos Agreement - Computerphile (video)](https://www.youtube.com/watch?v=s8JqcZtvnsM)
    - [ ] Raft - [An Introduction to the Raft Distributed Consensus Algorithm (video)](https://www.youtube.com/watch?v=P9Ydif5_qvE)
        - [ ] [Easy-to-read paper](https://raft.github.io/)
        - [ ] [Infographic](http://thesecretlivesofdata.com/raft/)
- [ ] [Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html)
- [ ] [NoSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
- [ ] Scalability:
    - You don't need all of these. Just pick a few that interest you.
    - [ ] [Great overview (video)](https://www.youtube.com/watch?v=-W9F__D3oY4)
    - [ ] Short series:
        - [Clones](http://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
        - [Database](http://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
        - [Cache](http://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
        - [Asynchronism](http://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)
    - [ ] [Scalable Web Architecture and Distributed Systems](http://www.aosabook.org/en/distsys.html)
    - [ ] [Fallacies of Distributed Computing Explained](https://pages.cs.wisc.edu/~zuyu/files/fallacies.pdf)
    - [ ] [Jeff Dean - Building Software Systems At Google and Lessons Learned (video)](https://www.youtube.com/watch?v=modXC5IWTJI)
    - [ ] [Introduction to Architecting Systems for Scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
    - [ ] [Scaling mobile games to a global audience using App Engine and Cloud Datastore (video)](https://www.youtube.com/watch?v=9nWyWwY2Onc)
    - [ ] [How Google Does Planet-Scale Engineering for Planet-Scale Infra (video)](https://www.youtube.com/watch?v=H4vMcD7zKM0)
    - [ ] [The Importance of Algorithms](https://www.topcoder.com/thrive/articles/The%20Importance%20of%20Algorithms)
    - [ ] [Sharding](http://highscalability.com/blog/2009/8/6/an-unorthodox-approach-to-database-design-the-coming-of-the.html)
    - [ ] [Engineering for the Long Game - Astrid Atkinson Keynote(video)](https://www.youtube.com/watch?v=p0jGmgIrf_M&list=PLRXxvay_m8gqVlExPC5DG3TGWJTaBgqSA&index=4)
    - [ ] [7 Years Of YouTube Scalability Lessons In 30 Minutes](http://highscalability.com/blog/2012/3/26/7-years-of-youtube-scalability-lessons-in-30-minutes.html)
        - [video](https://www.youtube.com/watch?v=G-lGCC4KKok)
    - [ ] [How PayPal Scaled To Billions Of Transactions Daily Using Just 8VMs](http://highscalability.com/blog/2016/8/15/how-paypal-scaled-to-billions-of-transactions-daily-using-ju.html)
    - [ ] [How to Remove Duplicates in Large Datasets](https://blog.clevertap.com/how-to-remove-duplicates-in-large-datasets/)
    - [ ] [A look inside Etsy's scale and engineering culture with Jon Cowie (video)](https://www.youtube.com/watch?v=3vV4YiqKm1o)
    - [ ] [What Led Amazon to its Own Microservices Architecture](http://thenewstack.io/led-amazon-microservices-architecture/)
    - [ ] [To Compress Or Not To Compress, That Was Uber's Question](https://eng.uber.com/trip-data-squeeze/)
    - [ ] [When Should Approximate Query Processing Be Used?](http://highscalability.com/blog/2016/2/25/when-should-approximate-query-processing-be-used.html)
    - [ ] [Google's Transition From Single Datacenter To Failover, To A Native Multihomed Architecture]( http://highscalability.com/blog/2016/2/23/googles-transition-from-single-datacenter-to-failover-to-a-n.html)
    - [ ] [The Image Optimization Technology That Serves Millions Of Requests Per Day](http://highscalability.com/blog/2016/6/15/the-image-optimization-technology-that-serves-millions-of-re.html)
    - [ ] [A Patreon Architecture Short](http://highscalability.com/blog/2016/2/1/a-patreon-architecture-short.html)
    - [ ] [Tinder: How Does One Of The Largest Recommendation Engines Decide Who You'll See Next?](http://highscalability.com/blog/2016/1/27/tinder-how-does-one-of-the-largest-recommendation-engines-de.html)
    - [ ] [Design Of A Modern Cache](http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)
    - [ ] [Live Video Streaming At Facebook Scale](http://highscalability.com/blog/2016/1/13/live-video-streaming-at-facebook-scale.html)
    - [ ] [A Beginner's Guide To Scaling To 11 Million+ Users On Amazon's AWS](http://highscalability.com/blog/2016/1/11/a-beginners-guide-to-scaling-to-11-million-users-on-amazons.html)
    - [ ] [A 360 Degree View Of The Entire Netflix Stack](http://highscalability.com/blog/2015/11/9/a-360-degree-view-of-the-entire-netflix-stack.html)
    - [ ] [Latency Is Everywhere And It Costs You Sales - How To Crush It](http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it)
    - [ ] [What Powers Instagram: Hundreds of Instances, Dozens of Technologies](http://instagram-engineering.tumblr.com/post/13649370142/what-powers-instagram-hundreds-of-instances)
    - [ ] [Salesforce Architecture - How They Handle 1.3 Billion Transactions A Day](http://highscalability.com/blog/2013/9/23/salesforce-architecture-how-they-handle-13-billion-transacti.html)
    - [ ] [ESPN's Architecture At Scale - Operating At 100,000 Duh Nuh Nuhs Per Second](http://highscalability.com/blog/2013/11/4/espns-architecture-at-scale-operating-at-100000-duh-nuh-nuhs.html)
    - [ ] See "Messaging, Serialization, and Queueing Systems" way below for info on some of the technologies that can glue services together
    - [ ] Twitter:
        - [O'Reilly MySQL CE 2011: Jeremy Cole, "Big and Small Data at @Twitter" (video)](https://www.youtube.com/watch?v=5cKTP36HVgI)
        - [Timelines at Scale](https://www.infoq.com/presentations/Twitter-Timeline-Scalability)
    - For even more, see the "Mining Massive Datasets" video series in the [Video Series](#video-series) section
- [ ] Practicing the system design process: Here are some ideas to try working through on paper, each with some documentation on how it was handled in the real world:
    - review: [The System Design Primer](https://github.com/donnemartin/system-design-primer)
    - [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
    - [cheat sheet](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/system-design.pdf)
    - flow:
        1. Understand the problem and scope:
            - Define the use cases, with the interviewer's help
            - Suggest additional features
            - Remove items that the interviewer deems out of scope
            - Assume high availability is required, add as a use case
        2. Think about constraints:
            - Ask how many requests per month
            - Ask how many requests per second (they may volunteer it or make you do the math)
            - Estimate reads vs. writes percentage
            - Keep the 80/20 rule in mind when estimating
            - How much data is written per second
            - Total storage required over 5 years
            - How much data read per second
        3. Abstract design:
            - Layers (service, data, caching)
            - Infrastructure: load balancing, messaging
            - Rough overview of any key algorithm that drives the service
            - Consider bottlenecks and determine solutions
    - Exercises:
        - [Design a random unique ID generation system](https://blog.twitter.com/2010/announcing-snowflake)
        - [Design a key-value database](http://www.slideshare.net/dvirsky/introduction-to-redis)
        - [Design a picture sharing system](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
        - [Design a recommendation system](http://ijcai13.org/files/tutorial_slides/td3.pdf)
        - [Design a URL-shortener system: copied from above](http://www.hiredintech.com/system-design/the-system-design-process/)
        - [Design a cache system](https://web.archive.org/web/20220217064329/https://adayinthelifeof.nl/2011/02/06/memcache-internals/)

### ML System Design

For AI Engineer roles, you will encounter ML system design interviews. The framework:
**Problem scoping → Data → Modeling → Evaluation → Deployment → Monitoring**

**Resources:**
- [ ] [Machine Learning System Design Interview (Aminian & Xu)](https://www.amazon.com/Machine-Learning-System-Design-Interview/dp/1736049127) — interview-focused
- [ ] [Designing Machine Learning Systems (Chip Huyen)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107963/) — production-focused
- [ ] [ML System Design Primer (GitHub)](https://github.com/chiphuyen/machine-learning-systems-design)

**Practice design problems:**
- [ ] Design a **recommendation system** (YouTube, Netflix, Spotify)
    - Candidate generation → scoring → re-ranking
    - Two-tower model, collaborative filtering vs. content-based
- [ ] Design a **search ranking system** (Google, Bing, e-commerce)
    - Query understanding, document retrieval, learning-to-rank
- [ ] Design a **fraud detection system**
    - Real-time scoring, feature computation latency, class imbalance
- [ ] Design a **content moderation system**
    - Multi-modal (text + image), human-in-the-loop, precision vs. recall tradeoffs
- [ ] Design a **semantic search system with RAG**
    - Embedding pipeline, vector DB, chunking, reranking
- [ ] Design an **LLM serving infrastructure**
    - Low latency, high throughput, batching, KV cache, speculative decoding
- [ ] Design a **feature store**
    - Offline vs. online features, consistency, low-latency serving

**[⬆ back to top](#table-of-contents)**

## Additional Learning

    I added them to help you become a well-rounded software engineer and to be aware of certain
    technologies and algorithms, so you'll have a bigger toolbox.

- ### Compilers
    - [How a Compiler Works in ~1 minute (video)](https://www.youtube.com/watch?v=IhC7sdYe-Jg)
    - [Harvard CS50 - Compilers (video)](https://www.youtube.com/watch?v=CSZLNYF4Klo)
    - [C++ (video)](https://www.youtube.com/watch?v=twodd1KFfGk)
    - [Understanding Compiler Optimization (C++) (video)](https://www.youtube.com/watch?v=FnGCDLhaxKU)

- ### Emacs and vi(m)
    - Familiarize yourself with a UNIX-based code editor
    - vi(m):
        - [Editing With Vim 01 - Installation, Setup, and The Modes (video)](https://www.youtube.com/watch?v=5givLEMcINQ&index=1&list=PL13bz4SHGmRxlZVmWQ9DvXo1fEg4UdGkr)
        - [VIM Adventures](http://vim-adventures.com/)
        - set of 4 videos:
            - [The vi/vim editor - Lesson 1](https://www.youtube.com/watch?v=SI8TeVMX8pk)
            - [The vi/vim editor - Lesson 2](https://www.youtube.com/watch?v=F3OO7ZIOaJE)
            - [The vi/vim editor - Lesson 3](https://www.youtube.com/watch?v=ZYEccA_nMaI)
            - [The vi/vim editor - Lesson 4](https://www.youtube.com/watch?v=1lYD5gwgZIA)
        - [Using Vi Instead of Emacs](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Using_Vi_instead_of_Emacs)
    - emacs:
        - [Basics Emacs Tutorial (video)](https://www.youtube.com/watch?v=hbmV1bnQ-i0)
        - set of 3 (videos):
            - [Emacs Tutorial (Beginners) -Part 1- File commands, cut/copy/paste, cursor commands](https://www.youtube.com/watch?v=ujODL7MD04Q)
            - [Emacs Tutorial (Beginners) -Part 2- Buffer management, search, M-x grep and rgrep modes](https://www.youtube.com/watch?v=XWpsRupJ4II)
            - [Emacs Tutorial (Beginners) -Part 3- Expressions, Statements, ~/.emacs file, and packages](https://www.youtube.com/watch?v=paSgzPso-yc)
        - [Evil Mode: Or, How I Learned to Stop Worrying and Love Emacs (video)](https://www.youtube.com/watch?v=JWD1Fpdd4Pc)
        - [Writing C Programs With Emacs](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Writing_C_programs_with_Emacs)
	- [The Absolute Beginner's Guide to Emacs (video by David Wilson)](https://www.youtube.com/watch?v=48JlgiBpw_I&t=0s)
	- [The Absolute Beginner's Guide to Emacs (notes by David Wilson)](https://systemcrafters.net/emacs-essentials/absolute-beginners-guide-to-emacs/)

- ### Unix/Linux command line tools
    - I filled in the list below from good tools.
    - bash
    - cat
    - grep
    - sed
    - awk
    - curl or wget
    - sort
    - tr
    - uniq
    - [strace](https://en.wikipedia.org/wiki/Strace)
    - [tcpdump](https://danielmiessler.com/study/tcpdump/)
    - [Essential Linux Commands Tutorial](https://labex.io/tutorials/practice-linux-commands-hands-on-labs-398420)

- ### DevOps
    - [DevOps Roadmap](https://roadmap.sh/devops)

- ### Information theory (videos)
    - [Khan Academy](https://www.khanacademy.org/computing/computer-science/informationtheory)
    - More about Markov processes:
        - [Core Markov Text Generation](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/waxgx/core-markov-text-generation)
        - [Core Implementing Markov Text Generation](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/gZhiC/core-implementing-markov-text-generation)
        - [Project = Markov Text Generation Walk Through](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/EUjrq/project-markov-text-generation-walk-through)
    - See more in the MIT 6.050J Information and Entropy series below

- ### Parity & Hamming Code (videos)
    - [Intro](https://www.youtube.com/watch?v=q-3BctoUpHE)
    - [Parity](https://www.youtube.com/watch?v=DdMcAUlxh1M)
    - Hamming Code:
        - [Error detection](https://www.youtube.com/watch?v=1A_NcXxdoCc)
        - [Error correction](https://www.youtube.com/watch?v=JAMLuxdHH8o)
    - [Error Checking](https://www.youtube.com/watch?v=wbH2VxzmoZk)

- ### Entropy
    - Also see the videos below
    - Make sure to watch information theory videos first
    - [Information Theory, Claude Shannon, Entropy, Redundancy, Data Compression & Bits (video)](https://youtu.be/JnJq3Py0dyM?t=176)

- ### Cryptography
    - Also see the videos below
    - Make sure to watch information theory videos first
    - [Khan Academy Series](https://www.khanacademy.org/computing/computer-science/cryptography)
    - [Cryptography: Hash Functions](https://www.youtube.com/watch?v=KqqOXndnvic&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=30)
    - [Cryptography: Encryption](https://www.youtube.com/watch?v=9TNI2wHmaeI&index=31&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

- ### Compression
    - Make sure to watch information theory videos first
    - Computerphile (videos):
        - [Compression](https://www.youtube.com/watch?v=Lto-ajuqW3w)
        - [Entropy in Compression](https://www.youtube.com/watch?v=M5c_RFKVkko)
        - [Upside Down Trees (Huffman Trees)](https://www.youtube.com/watch?v=umTbivyJoiI)
        - [EXTRA BITS/TRITS - Huffman Trees](https://www.youtube.com/watch?v=DV8efuB3h2g)
        - [Elegant Compression in Text (The LZ 77 Method)](https://www.youtube.com/watch?v=goOa3DGezUA)
        - [Text Compression Meets Probabilities](https://www.youtube.com/watch?v=cCDCfoHTsaU)
    - [Compressor Head videos](https://www.youtube.com/playlist?list=PLOU2XLYxmsIJGErt5rrCqaSGTMyyqNt2H)
    - [(optional) Google Developers Live: GZIP is not enough!](https://www.youtube.com/watch?v=whGwm0Lky2s)

- ### Computer Security
    - [MIT (23 videos)](https://www.youtube.com/playlist?list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Introduction, Threat Models](https://www.youtube.com/watch?v=GqmQg-cszw4&index=1&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Control Hijacking Attacks](https://www.youtube.com/watch?v=6bwzNg5qQ0o&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=2)
        - [Buffer Overflow Exploits and Defenses](https://www.youtube.com/watch?v=drQyrzRoRiA&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=3)
        - [Privilege Separation](https://www.youtube.com/watch?v=6SIJmoE9L9g&index=4&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Capabilities](https://www.youtube.com/watch?v=8VqTSY-11F4&index=5&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Sandboxing Native Code](https://www.youtube.com/watch?v=VEV74hwASeU&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=6)
        - [Web Security Model](https://www.youtube.com/watch?v=chkFBigodIw&index=7&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Securing Web Applications](https://www.youtube.com/watch?v=EBQIGy1ROLY&index=8&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Symbolic Execution](https://www.youtube.com/watch?v=yRVZPvHYHzw&index=9&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Network Security](https://www.youtube.com/watch?v=SIEVvk3NVuk&index=11&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Network Protocols](https://www.youtube.com/watch?v=QOtA76ga_fY&index=12&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [Side-Channel Attacks](https://www.youtube.com/watch?v=PuVMkSEcPiI&index=15&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)

- ### Garbage collection
    - [GC in Python (video)](https://www.youtube.com/watch?v=iHVs_HkjdmI)
    - [Deep Dive Java: Garbage Collection is Good!](https://www.infoq.com/presentations/garbage-collection-benefits)
    - [Deep Dive Python: Garbage Collection in CPython (video)](https://www.youtube.com/watch?v=P-8Z0-MhdQs&list=PLdzf4Clw0VbOEWOS_sLhT_9zaiQDrS5AR&index=3)

- ### Parallel Programming
    - [Coursera (Scala)](https://www.coursera.org/learn/parprog1/home/week/1)
    - [Efficient Python for High-Performance Parallel Computing (video)](https://www.youtube.com/watch?v=uY85GkaYzBk)

- ### Messaging, Serialization, and Queueing Systems
    - [Thrift](https://thrift.apache.org/)
        - [Tutorial](http://thrift-tutorial.readthedocs.io/en/latest/intro.html)
    - [Protocol Buffers](https://developers.google.com/protocol-buffers/)
        - [Tutorials](https://developers.google.com/protocol-buffers/docs/tutorials)
    - [gRPC](http://www.grpc.io/)
        - [gRPC 101 for Java Developers (video)](https://www.youtube.com/watch?v=5tmPvSe7xXQ&list=PLcTqM9n_dieN0k1nSeN36Z_ppKnvMJoly&index=1)
    - [Redis](http://redis.io/)
        - [Tutorial](http://try.redis.io/)
    - [Amazon SQS (queue)](https://aws.amazon.com/sqs/)
    - [Amazon SNS (pub-sub)](https://aws.amazon.com/sns/)
    - [RabbitMQ](https://www.rabbitmq.com/)
        - [Get Started](https://www.rabbitmq.com/getstarted.html)
    - [Celery](http://www.celeryproject.org/)
        - [First Steps With Celery](http://docs.celeryproject.org/en/latest/getting-started/first-steps-with-celery.html)
    - [ZeroMQ](http://zeromq.org/)
        - [Intro - Read The Manual](http://zeromq.org/intro:read-the-manual)
    - [ActiveMQ](http://activemq.apache.org/)
    - [Kafka](http://kafka.apache.org/documentation.html#introduction)
    - [MessagePack](http://msgpack.org/index.html)
    - [Avro](https://avro.apache.org/)

- ### A*
    - [A Search Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)
    - [A* Pathfinding (E01: algorithm explanation) (video)](https://www.youtube.com/watch?v=-L-WgKMFuhE)

- ### Fast Fourier Transform
    - [An Interactive Guide To The Fourier Transform](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/)
    - [What is a Fourier transform? What is it used for?](http://www.askamathematician.com/2012/09/q-what-is-a-fourier-transform-what-is-it-used-for/)
    - [What is the Fourier Transform? (video)](https://www.youtube.com/watch?v=Xxut2PN-V8Q)
    - [Divide & Conquer: FFT (video)](https://www.youtube.com/watch?v=iTMn0Kt18tg&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=4)
    - [Understanding The FFT](http://jakevdp.github.io/blog/2013/08/28/understanding-the-fft/)

- ### Bloom Filter
    - Given a Bloom filter with m bits and k hashing functions, both insertion and membership testing are O(k)
    - [Bloom Filters (video)](https://www.youtube.com/watch?v=-SuTGoFYjZs)
    - [Bloom Filters | Mining of Massive Datasets | Stanford University (video)](https://www.youtube.com/watch?v=qBTdukbzc78)
    - [Tutorial](http://billmill.org/bloomfilter-tutorial/)
    - [How To Write A Bloom Filter App](http://blog.michaelschmatz.com/2016/04/11/how-to-write-a-bloom-filter-cpp/)

- ### HyperLogLog
    - [How To Count A Billion Distinct Objects Using Only 1.5KB Of Memory](http://highscalability.com/blog/2012/4/5/big-data-counting-how-to-count-a-billion-distinct-objects-us.html)

- ### Locality-Sensitive Hashing
    - Used to determine the similarity of documents
    - The opposite of MD5 or SHA which are used to determine if 2 documents/strings are exactly the same
    - [Simhashing (hopefully) made simple](http://ferd.ca/simhashing-hopefully-made-simple.html)

- ### van Emde Boas Trees
    - [Divide & Conquer: van Emde Boas Trees (video)](https://www.youtube.com/watch?v=hmReJCupbNU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=6)
    - [MIT Lecture Notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2012/lecture-notes/MIT6_046JS12_lec15.pdf)

- ### Augmented Data Structures
    - [CS 61B Lecture 39: Augmenting Data Structures](https://archive.org/details/ucberkeley_webcast_zksIj9O8_jc)

- ### Balanced search trees
    - Know at least one type of balanced binary tree (and know how it's implemented):
    - "Among balanced search trees, AVL and 2/3 trees are now passé and red-black trees seem to be more popular.
        A particularly interesting self-organizing data structure is the splay tree, which uses rotations
        to move any accessed key to the root." - Skiena
    - Of these, I chose to implement a splay tree. From what I've read, you won't implement a
        balanced search tree in your interview. But I wanted exposure to coding one up
        and let's face it, splay trees are the bee's knees. I did read a lot of red-black tree code
        - Splay tree: insert, search, delete functions
        If you end up implementing a red/black tree try just these:
        - Search and insertion functions, skipping delete
    - I want to learn more about B-Tree since it's used so widely with very large data sets
    - [Self-balancing binary search tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)

    - **AVL trees**
        - In practice:
            From what I can tell, these aren't used much in practice, but I could see where they would be:
            The AVL tree is another structure supporting O(log n) search, insertion, and removal. It is more rigidly
            balanced than red–black trees, leading to slower insertion and removal but faster retrieval. This makes it
            attractive for data structures that may be built once and loaded without reconstruction, such as language
            dictionaries (or program dictionaries, such as the opcodes of an assembler or interpreter)
        - [MIT AVL Trees / AVL Sort (video)](https://www.youtube.com/watch?v=FNeL18KsWPc&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=6)
        - [AVL Trees (video)](https://www.coursera.org/learn/data-structures/lecture/Qq5E0/avl-trees)
        - [AVL Tree Implementation (video)](https://www.coursera.org/learn/data-structures/lecture/PKEBC/avl-tree-implementation)
        - [Split And Merge](https://www.coursera.org/learn/data-structures/lecture/22BgE/split-and-merge)
        - [[Review] AVL Trees (playlist) in 19 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZOUFgdIeOPuH6cfSnNRMau-)

    - **Splay trees**
        - In practice:
            Splay trees are typically used in the implementation of caches, memory allocators, routers, garbage collectors,
            data compression, ropes (replacement of string used for long text strings), in Windows NT (in the virtual memory,
            networking and file system code) etc
        - [CS 61B: Splay Trees (video)](https://archive.org/details/ucberkeley_webcast_G5QIXywcJlY)
        - MIT Lecture: Splay Trees:
            - Gets very mathy, but watch the last 10 minutes for sure.
            - [Video](https://www.youtube.com/watch?v=QnPl_Y6EqMo)

    - **Red/black trees**
        - These are a translation of a 2-3 tree (see below).
        - In practice:
            Red–black trees offer worst-case guarantees for insertion time, deletion time, and search time.
            Not only does this make them valuable in time-sensitive applications such as real-time applications,
            but it makes them valuable building blocks in other data structures that provide worst-case guarantees;
            for example, many data structures used in computational geometry can be based on red-black trees, and
            the Completely Fair Scheduler used in current Linux kernels uses red–black trees. In version 8 of Java,
            the Collection HashMap has been modified such that instead of using a LinkedList to store identical elements with poor
            hashcodes, a Red-Black tree is used
        - [Aduni - Algorithms - Lecture 4 (link jumps to the starting point) (video)](https://youtu.be/1W3x0f_RmUo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3871)
        - [Aduni - Algorithms - Lecture 5 (video)](https://www.youtube.com/watch?v=hm2GHwyKF1o&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=5)
        - [Red-Black Tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)
        - [An Introduction To Binary Search And Red Black Tree](https://www.topcoder.com/thrive/articles/An%20Introduction%20to%20Binary%20Search%20and%20Red-Black%20Trees)
        - [[Review] Red-Black Trees (playlist) in 30 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZNqDI8qfOZgzbqahCUmUEin)

    - **2-3 search trees**
        - In practice:
            2-3 trees have faster inserts at the expense of slower searches (since height is more compared to AVL trees).
        - You would use 2-3 trees very rarely because its implementation involves different types of nodes. Instead, people use Red-Black trees.
        - [23-Tree Intuition and Definition (video)](https://www.youtube.com/watch?v=C3SsdUqasD4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=2)
        - [Binary View of 23-Tree](https://www.youtube.com/watch?v=iYvBtGKsqSg&index=3&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [2-3 Trees (student recitation) (video)](https://www.youtube.com/watch?v=TOb1tuEZ2X4&index=5&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

    - **2-3-4 Trees (aka 2-4 trees)**
        - In practice:
            For every 2-4 trees, there are corresponding red–black trees with data elements in the same order. The insertion and deletion
            operations on 2-4 trees are also equivalent to color-flipping and rotations in red–black trees. This makes 2-4 trees an
            important tool for understanding the logic behind red-black trees, and this is why many introductory algorithm texts introduce
            2-4 trees just before red–black trees, even though **2-4 trees are not often used in practice**.
        - [CS 61B Lecture 26: Balanced Search Trees (video)](https://archive.org/details/ucberkeley_webcast_zqrqYXkth6Q)
        - [Bottom Up 234-Trees (video)](https://www.youtube.com/watch?v=DQdMYevEyE4&index=4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [Top Down 234-Trees (video)](https://www.youtube.com/watch?v=2679VQ26Fp4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=5)

    - **N-ary (K-ary, M-ary) trees**
        - note: the N or K is the branching factor (max branches)
        - binary trees are a 2-ary tree, with branching factor = 2
        - 2-3 trees are 3-ary
        - [K-Ary Tree](https://en.wikipedia.org/wiki/K-ary_tree)

    - **B-Trees**
        - Fun fact: it's a mystery, but the B could stand for Boeing, Balanced, or Bayer (co-inventor).
        - In Practice:
            B-trees are widely used in databases. Most modern filesystems use B-trees (or Variants). In addition to
            its use in databases, the B-tree is also used in filesystems to allow quick random access to an arbitrary
            block in a particular file. The basic problem is turning the file block address into a disk block
            (or perhaps to a cylinder head sector) address
        - [B-Tree](https://en.wikipedia.org/wiki/B-tree)
        - [B-Tree Datastructure](http://btechsmartclass.com/data_structures/b-trees.html)
        - [Introduction to B-Trees (video)](https://www.youtube.com/watch?v=I22wEC1tTGo&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=6)
        - [B-Tree Definition and Insertion (video)](https://www.youtube.com/watch?v=s3bCdZGrgpA&index=7&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [B-Tree Deletion (video)](https://www.youtube.com/watch?v=svfnVhJOfMc&index=8&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [MIT 6.851 - Memory Hierarchy Models (video)](https://www.youtube.com/watch?v=V3omVLzI0WE&index=7&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf)
                - covers cache-oblivious B-Trees, very interesting data structures
                - the first 37 minutes are very technical, and may be skipped (B is block size, cache line size)
        - [[Review] B-Trees (playlist) in 26 minutes (video)](https://www.youtube.com/playlist?list=PL9xmBV_5YoZNFPPv98DjTdD9X6UI9KMHz)


- ### k-D Trees
    - Great for finding a number of points in a rectangle or higher-dimensional object
    - A good fit for k-nearest neighbors
    - [kNN K-d tree algorithm (video)](https://www.youtube.com/watch?v=Y4ZgLlDfKDg)

- ### Skip lists
    - "These are somewhat of a cult data structure" - Skiena
    - [Randomization: Skip Lists (video)](https://www.youtube.com/watch?v=2g9OSRKJuzM&index=10&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [For animations and a little more detail](https://en.wikipedia.org/wiki/Skip_list)

- ### Network Flows
    - [Ford-Fulkerson in 5 minutes — Step by step example (video)](https://www.youtube.com/watch?v=Tl90tNtKvxs)
    - [Ford-Fulkerson Algorithm (video)](https://www.youtube.com/watch?v=v1VgJmkEJW0)
    - [Network Flows (video)](https://www.youtube.com/watch?v=2vhN4Ice5jI)

- ### Disjoint Sets & Union Find
    - [UCB 61B - Disjoint Sets; Sorting & selection (video)](https://archive.org/details/ucberkeley_webcast_MAEGXTwmUsI)
    - [Sedgewick Algorithms - Union-Find (6 videos)](https://www.coursera.org/learn/algorithms-part1/home/week/1)

- ### Math for Fast Processing
    - [Integer Arithmetic, Karatsuba Multiplication (video)](https://www.youtube.com/watch?v=eCaXlAaN2uE&index=11&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [The Chinese Remainder Theorem (used in cryptography) (video)](https://www.youtube.com/watch?v=ru7mWZJlRQg)

- ### Treap
    - Combination of a binary search tree and a heap
    - [Treap](https://en.wikipedia.org/wiki/Treap)
    - [Data Structures: Treaps explained (video)](https://www.youtube.com/watch?v=6podLUYinH8)
    - [Applications in set operations](https://www.cs.cmu.edu/~scandal/papers/treaps-spaa98.pdf)

- ### Linear Programming (videos)
    - [Linear Programming](https://www.youtube.com/watch?v=M4K6HYLHREQ)
    - [Finding minimum cost](https://www.youtube.com/watch?v=2ACJ9ewUC6U)
    - [Finding maximum value](https://www.youtube.com/watch?v=8AA_81xI3ik)
    - [Solve Linear Equations with Python - Simplex Algorithm](https://www.youtube.com/watch?v=44pAWI7v5Zk)

- ### Geometry, Convex hull (videos)
    - [Graph Alg. IV: Intro to geometric algorithms - Lecture 9](https://youtu.be/XIAQRlNkJAw?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3164)
    - [Geometric Algorithms: Graham & Jarvis - Lecture 10](https://www.youtube.com/watch?v=J5aJEcOr6Eo&index=10&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [Divide & Conquer: Convex Hull, Median Finding](https://www.youtube.com/watch?v=EzeYI7p9MjU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=2)

- ### Discrete math
    - [Computer Science 70, 001 - Spring 2015 - Discrete Mathematics and Probability Theory](http://www.infocobuild.com/education/audio-video-courses/computer-science/cs70-spring2015-berkeley.html)
    - [Discrete Mathematics by Shai Simonson (19 videos)](https://www.youtube.com/playlist?list=PLWX710qNZo_sNlSWRMVIh6kfTjolNaZ8t)
    - [Discrete Mathematics By IIT Ropar NPTEL](https://nptel.ac.in/courses/106/106/106106183/)

---

**[⬆ back to top](#table-of-contents)**

## Additional Detail on Some Subjects

    I added these to reinforce some ideas already presented above, but didn't want to include them
    above because it's just too much. It's easy to overdo it on a subject.
    You want to get hired in this century, right?

- **SOLID**
    - [ ] [Bob Martin SOLID Principles of Object Oriented and Agile Design (video)](https://www.youtube.com/watch?v=TMuno5RZNeE)
    - [ ] S - [Single Responsibility Principle](http://www.oodesign.com/single-responsibility-principle.html) | [Single responsibility to each Object](http://www.javacodegeeks.com/2011/11/solid-single-responsibility-principle.html)
        - [more flavor](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
    - [ ] O - [Open/Closed Principle](http://www.oodesign.com/open-close-principle.html)  | [On production level Objects are ready for extension but not for modification](https://en.wikipedia.org/wiki/Open/closed_principle)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
    - [ ] L - [Liskov Substitution Principle](http://www.oodesign.com/liskov-s-substitution-principle.html) | [Base Class and Derived class follow ‘IS A’ Principle](http://stackoverflow.com/questions/56860/what-is-the-liskov-substitution-principle)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
    - [ ] I - [Interface segregation principle](http://www.oodesign.com/interface-segregation-principle.html) | Clients should not be forced to implement interfaces they don't use
        - [Interface Segregation Principle in 5 minutes (video)](https://www.youtube.com/watch?v=3CtAfl7aXAQ)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
    - [ ] D -[Dependency Inversion principle](http://www.oodesign.com/dependency-inversion-principle.html) | Reduce the dependency In composition of objects.
        - [Why Is The Dependency Inversion Principle And Why Is It Important](http://stackoverflow.com/questions/62539/what-is-the-dependency-inversion-principle-and-why-is-it-important)
        - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)


- **Union-Find**
    - [Overview](https://www.coursera.org/learn/data-structures/lecture/JssSY/overview)
    - [Naive Implementation](https://www.coursera.org/learn/data-structures/lecture/EM5D0/naive-implementations)
    - [Trees](https://www.coursera.org/learn/data-structures/lecture/Mxu0w/trees)
    - [Union By Rank](https://www.coursera.org/learn/data-structures/lecture/qb4c2/union-by-rank)
    - [Path Compression](https://www.coursera.org/learn/data-structures/lecture/Q9CVI/path-compression)
    - [Analysis Options](https://www.coursera.org/learn/data-structures/lecture/GQQLN/analysis-optional)

- **More Dynamic Programming** (videos)
    - [6.006: Dynamic Programming I: Fibonacci, Shortest Paths](https://www.youtube.com/watch?v=r4-cftqTcdI&ab_channel=MITOpenCourseWare)
    - [6.006: Dynamic Programming II: Text Justification, Blackjack](https://www.youtube.com/watch?v=KLBCUx1is2c&ab_channel=MITOpenCourseWare)
    - [6.006: DP III: Parenthesization, Edit Distance, Knapsack](https://www.youtube.com/watch?v=TDo3r5M1LNo&ab_channel=MITOpenCourseWare)
    - [6.006: DP IV: Guitar Fingering, Tetris, Super Mario Bros.](https://www.youtube.com/watch?v=i9OAOk0CUQE&ab_channel=MITOpenCourseWare)
    - [6.046: Dynamic Programming & Advanced DP](https://www.youtube.com/watch?v=Tw1k46ywN6E&index=14&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [6.046: Dynamic Programming: All-Pairs Shortest Paths](https://www.youtube.com/watch?v=NzgFUwOaoIw&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=15)
    - [6.046: Dynamic Programming (student recitation)](https://www.youtube.com/watch?v=krZI60lKPek&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=12)

- **Advanced Graph Processing** (videos)
    - [Synchronous Distributed Algorithms: Symmetry-Breaking. Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=mUBmcbbJNf4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=27)
    - [Asynchronous Distributed Algorithms: Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=kQ-UQAzcnzA&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=28)

- MIT **Probability** (mathy, and go slowly, which is good for mathy things) (videos):
    - [MIT 6.042J - Probability Introduction](https://www.youtube.com/watch?v=SmFwFdESMHI&index=18&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Conditional Probability](https://www.youtube.com/watch?v=E6FbvM-FGZ8&index=19&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Independence](https://www.youtube.com/watch?v=l1BCv3qqW4A&index=20&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Random Variables](https://www.youtube.com/watch?v=MOfhhFaQdjw&list=PLB7540DEDD482705B&index=21)
    - [MIT 6.042J - Expectation I](https://www.youtube.com/watch?v=gGlMSe7uEkA&index=22&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Expectation II](https://www.youtube.com/watch?v=oI9fMUqgfxY&index=23&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Large Deviations](https://www.youtube.com/watch?v=q4mwO2qS2z4&index=24&list=PLB7540DEDD482705B)
    - [MIT 6.042J - Random Walks](https://www.youtube.com/watch?v=56iFMY8QW2k&list=PLB7540DEDD482705B&index=25)

- [Simonson: Approximation Algorithms (video)](https://www.youtube.com/watch?v=oDniZCmNmNw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=19)

- **String Matching**
    - Rabin-Karp (videos):
        - [Rabin Karps Algorithm](https://www.coursera.org/lecture/data-structures/rabin-karps-algorithm-c0Qkw)
        - [Precomputing](https://www.coursera.org/learn/data-structures/lecture/nYrc8/optimization-precomputation)
        - [Optimization: Implementation and Analysis](https://www.coursera.org/learn/data-structures/lecture/h4ZLc/optimization-implementation-and-analysis)
        - [Table Doubling, Karp-Rabin](https://www.youtube.com/watch?v=BRO7mVIFt08&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=9)
        - [Rolling Hashes, Amortized Analysis](https://www.youtube.com/watch?v=w6nuXg0BISo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=32)
    - Knuth-Morris-Pratt (KMP):
        - [TThe Knuth-Morris-Pratt (KMP) String Matching Algorithm](https://www.youtube.com/watch?v=5i7oKodCRJo)
    - Boyer–Moore string search algorithm
        - [Boyer-Moore String Search Algorithm](https://en.wikipedia.org/wiki/Boyer%E2%80%93Moore_string_search_algorithm)
        - [Advanced String Searching Boyer-Moore-Horspool Algorithms (video)](https://www.youtube.com/watch?v=QDZpzctPf10)
    - [Coursera: Algorithms on Strings](https://www.coursera.org/learn/algorithms-on-strings/home/week/1)
        - starts off great, but by the time it gets past KMP it gets more complicated than it needs to be
        - nice explanation of tries
        - can be skipped

- **Sorting**

    - Stanford lectures on sorting:
        - [Lecture 15 | Programming Abstractions (video)](https://www.youtube.com/watch?v=ENp00xylP7c&index=15&list=PLFE6E58F856038C69)
        - [Lecture 16 | Programming Abstractions (video)](https://www.youtube.com/watch?v=y4M9IVgrVKo&index=16&list=PLFE6E58F856038C69)
    - Shai Simonson:
        - [Algorithms - Sorting - Lecture 2 (video)](https://www.youtube.com/watch?v=odNJmw5TOEE&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=2)
        - [Algorithms - Sorting II - Lecture 3 (video)](https://www.youtube.com/watch?v=hj8YKFTFKEE&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=3)
    - Steven Skiena lectures on sorting:
        - [CSE373 2020 - Mergesort/Quicksort (video)](https://www.youtube.com/watch?v=jUf-UQ3a0kg&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=8)
        - [CSE373 2020 - Linear Sorting (video)](https://www.youtube.com/watch?v=0ksyQKmre84&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=9)

- NAND To Tetris: [Build a Modern Computer from First Principles](https://www.coursera.org/learn/build-a-computer)

**[⬆ back to top](#table-of-contents)**

## Video Series

Sit back and enjoy.

- [List of individual Dynamic Programming problems (each is short)](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)

- [x86 Architecture, Assembly, Applications (11 videos)](https://www.youtube.com/playlist?list=PL038BE01D3BAEFDB0)

- [MIT 18.06 Linear Algebra, Spring 2005 (35 videos)](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8)

- [Excellent - MIT Calculus Revisited: Single Variable Calculus](https://www.youtube.com/playlist?list=PL3B08AE665AB9002A)

- [Skiena lectures from Algorithm Design Manual - CSE373 2020 - Analysis of Algorithms (26 videos)](https://www.youtube.com/watch?v=22hwcnXIGgk&list=PLOtl7M3yp-DX6ic0HGT0PUX_wiNmkWkXx&index=1)

- [UC Berkeley 61B (Spring 2014): Data Structures (25 videos)](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd)

- [UC Berkeley 61B (Fall 2006): Data Structures (39 videos)](https://archive.org/details/ucberkeley-webcast-PL4BBB74C7D2A1049C)

- [UC Berkeley 61C: Machine Structures (26 videos)](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_)

- [OOSE: Software Dev Using UML and Java (21 videos)](https://www.youtube.com/playlist?list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO)

- [MIT 6.004: Computation Structures (49 videos)](https://www.youtube.com/playlist?list=PLDSlqjcPpoL64CJdF0Qee5oWqGS6we_Yu)

- [Carnegie Mellon - Computer Architecture Lectures (39 videos)](https://www.youtube.com/playlist?list=PL5PHm2jkkXmi5CxxI7b3JCL1TWybTDtKq)

- [MIT 6.006: Intro to Algorithms (47 videos)](https://www.youtube.com/watch?v=HtSuA80QTyo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&nohtml5=False)

- [MIT 6.033: Computer System Engineering (22 videos)](https://www.youtube.com/watch?v=zm2VP0kHl1M&list=PL6535748F59DCA484)

- [MIT 6.034 Artificial Intelligence, Fall 2010 (30 videos)](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)

- [MIT 6.042J: Mathematics for Computer Science, Fall 2010 (25 videos)](https://www.youtube.com/watch?v=L3LMbpZIKhQ&list=PLB7540DEDD482705B)

- [MIT 6.046: Design and Analysis of Algorithms (34 videos)](https://www.youtube.com/watch?v=2P-yW7LQr08&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

- [MIT 6.824: Distributed Systems, Spring 2020 (20 videos)](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)

- [MIT 6.851: Advanced Data Structures (22 videos)](https://www.youtube.com/watch?v=T0yzrZL1py0&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=1)

- [MIT 6.854: Advanced Algorithms, Spring 2016 (24 videos)](https://www.youtube.com/playlist?list=PL6ogFv-ieghdoGKGg2Bik3Gl1glBTEu8c)

- [Harvard COMPSCI 224: Advanced Algorithms (25 videos)](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uP4rJgf5ayhHWgw7akUWSf)

- [MIT 6.858 Computer Systems Security, Fall 2014](https://www.youtube.com/watch?v=GqmQg-cszw4&index=1&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)

- [Stanford: Programming Paradigms (27 videos)](https://www.youtube.com/playlist?list=PL9D558D49CA734A02)

- [Introduction to Cryptography by Christof Paar](https://www.youtube.com/playlist?list=PL6N5qY2nvvJE8X75VkXglSrVhLv1tVcfy)
    - [Course Website along with Slides and Problem Sets](http://www.crypto-textbook.com/)

- [Mining Massive Datasets - Stanford University (94 videos)](https://www.youtube.com/playlist?list=PLLssT5z_DsK9JDLcT8T62VtzwyW9LNepV)

- [Graph Theory by Sarada Herke (67 videos)](https://www.youtube.com/user/DrSaradaHerke/playlists?shelf_id=5&view=50&sort=dd)

**[⬆ back to top](#table-of-contents)**

## Computer Science Courses

- [Directory of Online CS Courses](https://github.com/open-source-society/computer-science)
- [Directory of CS Courses (many with online lectures)](https://github.com/prakhar1989/awesome-courses)

**[⬆ back to top](#table-of-contents)**

## Algorithms implementation

- [Multiple Algorithms implementation by Princeton University](https://algs4.cs.princeton.edu/code)

**[⬆ back to top](#table-of-contents)**

## Papers

### Seminal AI/ML Papers (Required Reading for AI Engineers)

These papers define the field. Every AI Engineer should be familiar with their contributions.

- [2012: ImageNet Classification with Deep Convolutional Neural Networks (AlexNet — Krizhevsky et al.)](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
    - The paper that launched the deep learning revolution; showed CNNs could dominate image recognition
- [2014: Generative Adversarial Nets (Goodfellow et al.)](https://papers.nips.cc/paper_files/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html)
    - Introduced GANs — generative models trained via adversarial play
- [2015: Deep Residual Learning for Image Recognition (ResNet — He et al.)](https://arxiv.org/abs/1512.03385)
    - Skip connections enabling training of very deep networks; now a standard building block
- [2017: Attention Is All You Need (Vaswani et al.)](https://arxiv.org/abs/1706.03762)
    - **The most important paper in modern AI** — introduced the Transformer architecture
- [2018: BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (Devlin et al.)](https://arxiv.org/abs/1810.04805)
    - Bidirectional encoder pre-training; fine-tuning paradigm for NLP tasks
- [2020: Language Models are Few-Shot Learners (GPT-3 — Brown et al.)](https://arxiv.org/abs/2005.14165)
    - Scaling to 175B parameters; in-context learning without gradient updates
- [2020: Scaling Laws for Neural Language Models (Kaplan et al.)](https://arxiv.org/abs/2001.08361)
    - Power laws relating model size, data, and compute to loss; foundations of scaling strategy
- [2020: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (Lewis et al.)](https://arxiv.org/abs/2005.11401)
    - The RAG paper — combining retrieval with generation to ground language models
- [2021: LoRA: Low-Rank Adaptation of Large Language Models (Hu et al.)](https://arxiv.org/abs/2106.09685)
    - Efficient fine-tuning by injecting trainable low-rank matrices; now the dominant PEFT method
- [2022: Training language models to follow instructions with human feedback (InstructGPT — Ouyang et al.)](https://arxiv.org/abs/2203.02155)
    - RLHF for aligning LLMs to human intent; the technique behind ChatGPT

### Classic CS Papers

- [Love classic papers?](https://www.cs.cmu.edu/~crary/819-f09/)
- [1978: Communicating Sequential Processes](http://spinroot.com/courses/summer/Papers/hoare_1978.pdf)
    - [implemented in Go](https://godoc.org/github.com/thomas11/csp)
- [2003: The Google File System](http://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
    - replaced by Colossus in 2012
- [2004: MapReduce: Simplified Data Processing on Large Clusters]( http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
    - mostly replaced by Cloud Dataflow?
- [2006: Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [2006: The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby-osdi06.pdf)
- [2007: Dynamo: Amazon's Highly Available Key-value Store](http://s3.amazonaws.com/AllThingsDistributed/sosp/amazon-dynamo-sosp2007.pdf)
    - The Dynamo paper kicked off the NoSQL revolution
- [2007: What Every Programmer Should Know About Memory (very long, and the author encourages skipping of some sections)](https://www.akkadia.org/drepper/cpumemory.pdf)
- 2012: AddressSanitizer: A Fast Address Sanity Checker:
    - [paper](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37752.pdf)
    - [video](https://www.usenix.org/conference/atc12/technical-sessions/presentation/serebryany)
- 2013: Spanner: Google's Globally-Distributed Database:
    - [paper](http://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)
    - [video](https://www.usenix.org/node/170855)
- [2015: Continuous Pipelines at Google](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43790.pdf)
- [2015: High-Availability at Massive Scale: Building Google's Data Infrastructure for Ads](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44686.pdf)
- [2015: How Developers Search for Code: A Case Study](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43835.pdf)
- More papers: [1,000 papers](https://github.com/0voice/computer_expert_paper)
## LICENSE

[CC-BY-SA-4.0](./LICENSE.txt)
