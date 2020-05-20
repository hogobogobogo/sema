
## Getting Started with Sema!
---

Welcome to the Sema tutorial! This will teach you everything you need to know to start live coding, using machine learning and designing your own live coding language.

You can also consult the [API docs](docs) and the [examples](examples), or — if you're impatient to start hacking Sema in a free from — the [60-second quickstart](blog/the-easiest-way-to-get-started).


### What is Sema?

Sema is a playground for live coding and designing live coding languages.

It is similar to other live coding environment such as Supercollider, TydalCycles and Gibber, which share a goal of making it easy to build slick interactive user interfaces.

But there's a crucial difference: Sema converts your app into ideal JavaScript at *build time*, rather than interpreting your application code at *run time*. This means you don't pay the performance cost of the framework's abstractions, and you don't incur a penalty when your app first loads.

You can build your entire app with Sema, or you can add it incrementally to an existing codebase. You can also ship components as standalone packages that work anywhere, without the overhead of a dependency on a conventional framework.


### How to use this tutorial

You'll need to have basic familiarity with HTML, CSS and JavaScript to understand Sema.

As you progress through the tutorial, you'll be presented with mini exercises designed to illustrate new features. Later chapters build on the knowledge gained in earlier ones, so it's recommended that you go from start to finish. If necessary, you can navigate via the dropdown above (click 'Introduction / Basics').

Each tutorial chapter will have a 'Show me' button that you can click if you get stuck following the instructions. Try not to rely on it too much; you will learn faster by figuring out where to put each suggested code block and manually typing it in to the editor.


### Understanding components

In Sema, an application is composed from one or more *components*. A component is a reusable self-contained block of code that encapsulates HTML, CSS and JavaScript that belong together, written into a `.sema` file. The 'hello world' example in the code editor is a simple component.