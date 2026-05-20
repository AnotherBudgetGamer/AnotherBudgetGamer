# Hi, I'm Brent Dillard

I'm a technical support professional and self-directed software developer focused on C programming, systems-oriented learning, and small reusable tools such as libraries with helper functions. I like to work in different environments, so I develop on both Linux and Windows. I am an aspiring video game developer with a few prototype games that I am working on currently. I have always had a love for numbers and rocks that we shocked with electricity and taught to count.

My background combines customer-facing troubleshooting, documentation, escalation management, and hands-on programming. I spent 20 years in the hospitality industry, working deeply with a combination of training and coaching staff daily and monthly budgets, P&L statements other accounting practices. This leads me to building projects that teach me how things work underneath the surface: memory management , file I/O, robust reusable build systems, library integration and linking, exciting game loops, clean UI systems, and project structure.

I currently spend most of my development time working with C, Raylib, Godot, Blender, GIMP, numerous open-source multimedia tools, and various other full-stack web dev tools.

My Philosophy

I believe that if someone cannot understand a concept, the problem is often in how it is being taught, not in the learner themselves.

My experience learning programming and computer hardware has shown me that there is no shortage of information in computer science. What often feels missing is an intermediate layer of developers and problem-solvers who can translate dense technical material into something practical and approachable for non-technical people.

Most people are intimidated by technology they do not understand. Many people use computers and smartphones every day without understanding basic concepts such as file systems, memory, or how software actually behaves underneath the interface. I think that gap matters.

My goal is to understand systems deeply enough that I can explain them clearly to almost anyone. If a person can walk away understanding a concept well enough to explain it to someone else, then the explanation was successful.

That is the standard I try to build toward in both my programming work and my documentation.

## Current Focus

- Building reusable C libraries and learning lower-level programming patterns
- Developing Raylib game prototypes and UI experiments
- Moving game systems from raw C/Raylib prototypes into Godot projects
- Practicing clean project structure with headers, source files, Makefiles, and documentation
- Improving Git/GitHub workflow, README quality, and long-term project organization and consistent documentation
- Building practical web app prototypes with Next.js, React, Prisma, Supabase, Cloudinary, and Clerk

## Technical Skills

### Programming

- C
- JavaScript
- GDScript
- SQL basics
- POSIX file I/O
- Modular header/source organization

### C Tooling

- GCC
- Make
- Static libraries
- Linker flags
- Git/GitHub
- Linux/WSL workflows
- MSYS2/Windows workflows

### Game Development

- Raylib
- Godot and Unity
- Blender
- 2D/3D game systems
- Collision logic
- UI primitives
- Sprite and animation workflows
- Simulation prototypes

### Web Development

- Next.js
- React
- Tailwind CSS
- Prisma
- Supabase/Postgres
- Cloudinary
- Clerk

### Support / Operations

- Zendesk
- Salesforce
- ServiceNow
- Freshdesk
- Jira
- Confluence
- Microsoft 365
- Google Workspace
---
## Featured Projects

### ABG C Library

A reusable personal C utility library built around small, practical helpers for C/Raylib projects.

**Focus areas:**

- Math helpers
- Random helpers
- Clamping
- Interpolation
- Value remapping
- Min/max helpers
- Float comparison
- Safe division
- Public header/source organization
- Static library builds with `Make`, `GCC`, and `ar`

This project has been the most fruitful so far. Learning how to package into a library archive to be easily shared across devices and documenting the process was great experience. I often use the math and clamp functions to speed game prototyping

---

### ABG UI Library

A lightweight Raylib-based ABG C Lib UI helper library for my C/Raylib projects.

**Focus areas:**

- Rectangle helpers
- Panels
- Buttons
- Collision checks
- Rectangle movement/insetting
- Drawing wrappers
- Raylib UI primitives
- Downstream linking with `-labg_ui`

This project grew out of repeated UI code I found myself writing across experiments. This was also a really good learning experience as I was protoyping a Drug Wars clone style game with a Windows 98 theme and this helped me with creating the raised + sunked window style to create depth. The goal is to keep the API small, understandable, and useful for simple game tools and prototypes.

---

### abg-cp

An educational Unix `cp`-style file-copy utility written in C.

**Focus areas:**

- `open`
- `read`
- `write`
- `close`
- Fixed-size buffered copying
- File descriptor validation
- Error handling with `perror`
- Argument validation
- File creation/truncation behavior

This project was built to reinforce low-level systems programming fundamentals and understand what common command-line tools are doing under the hood. This was a great experiment and showed a lot of hidden functionality that is often taken for granted by an average user.

---

### C/Raylib Simulations and Game Prototypes

A collection of small C/Raylib experiments focused on game loops, visual feedback, collision, resource systems, and simple simulations.

**Examples include:**

- Ant-foraging simulation logic
- Resource-node detection
- Boundary steering behavior
- Pheromone/grid planning
- Inventory system experiments
- Procedural generation for maps
- UI overlays
- Shooting and harvesting mechanics
- Floating feedback text
- Market/trading system prototypes

These projects are where I practice turning isolated programming concepts into working gameplay systems.

---

### Debt Runner

A C/Raylib Drug Wars clone game prototype with a Windows 98-inspired interface.

**Focus areas:**

- Game state management
- Degree/class selection
- Player stats
- Inventory slots
- Market screens
- Travel/status screens
- Win98-style UI windows
- Button/list/status bar primitives
- Font and spacing management

This project helped me think more carefully about UI consistency, state management, and data organization in a C game project. This is my most developed project and will probably be finished and release first (for FREE).

---

### Flug That!

A top-down creature capture, processing, and trading game concept originally prototyped in C/Raylib and later explored through Godot.

**Core ideas:**

- Capture tiered creatures called flugs
- Process creatures into materials/resources
- Trade resources locally or through an orbital exchange
- Build progression around better tools, inventory, hotbar upgrades, and planet exploration
- Use pseudo-3D/isometric visual ideas inspired by management/survival games

This is one of my larger ongoing design projects and has helped me think through systems such as inventory, harvesting, trading, material rarity, UI feedback, and world generation. This is my on going passion project that I would like to develop fully, market, and sell. 

---

### Family Photo Website Prototype

A full-stack web app prototype for organizing and sharing family photos.

**Stack:**

- Next.js
- React
- Tailwind CSS
- Prisma
- Supabase/Postgres
- Cloudinary
- Clerk

**Planned features:**

- Authenticated family access
- Multi-photo uploads
- Batch metadata entry
- People tagging
- Collection organization
- Photo browsing
- Recently uploaded views
- Modal image previews

This project focuses on building a practical app for non-technical users, with readable UI, simple workflows, and long-term organization of family photos. This site grew out of need for an older family member to have an easy way to upload photos, CRUD collections of photos adding details, with a clean UI designed for accessibility.  

---

## How I Like to Build

I tend to work documentation-first and implementation-focused.

I like projects that are:

- Small enough to understand
- Structured enough to reuse
- Documented enough to return to later
- Practical enough to teach a real programming concept

In C projects, I care about:

- Clear header/source separation
- Explicit function prototypes
- Consistent naming
- Understandable build steps
- Clean Makefiles
- Correct linker flags
- Minimal hidden behavior
- README files that explain how to actually build and use the project

---

## Learning Philosophy

I learn best by building small projects that expose the underlying mechanics.

Instead of only using high-level abstractions, I like to understand:

- What the compiler is doing
- How linking works
- How static libraries are structured
- How game loops update state
- How collision checks are calculated
- How file descriptors work
- How UI layout is drawn manually
- How data should move through a program

That approach has helped me move between C, Raylib, Godot, JavaScript, and full-stack tools with a better understanding of what each layer is responsible for.

---

## Professional Background

Before focusing heavily on programming projects, I worked in hospitatlity holding almost every role from bus boy/dishwasher to General Manager. I've also worked in technical support, implementation specialist, escalation management, and various customer service roles handling face-to-face interaction with customers.

That experience gave me a strong foundation in:

- Troubleshooting
- Customer communication
- Training/Coaching staff
- Documentation
- Escalation handling
- Process improvement
- Explaining technical issues clearly
- Working with both technical and non-technical users

I try to bring that same clarity into my code, project structure, and documentation. I tend to over docment. 

---

## Tools I Use

- VS Code
- Git/GitHub
- Linux
- WSL
- MSYS2
- GCC
- Make
- Raylib
- Godot
- Blender
- Supabase
- Prisma
- Next.js
- React
- Tailwind CSS

---

## GitHub Goals

I'm using GitHub to document my learning process, build a portfolio of practical programming projects, and keep improving how I structure, explain, and maintain software.

My current goals are:

- Keep improving my C fundamentals
- Build more complete Raylib and Godot prototypes
- Turn repeated code into reusable libraries
- Write better READMEs and setup documentation
- Practice clean Git workflows
- Build projects that show clear progression over time

---

## Contact

- GitHub: [github.com/AnotherBudgetGamer](https://github.com/AnotherBudgetGamer)
- Email: dllrdbrnt@gmail.com

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnotherBudgetGamer/AnotherBudgetGamer/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnotherBudgetGamer/AnotherBudgetGamer/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/AnotherBudgetGamer/AnotherBudgetGamer/output/github-snake.svg" />
</picture>
