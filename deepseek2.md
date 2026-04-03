## Node 1: Root

Main text:
## Quick start video tutorial

What if your documentation could think like you do, navigating "if this, then that, except when…" logic to deliver precisely the right information? No LLM hallucinations. No decision-tree duplication. Just deterministic content.

Ancillaries (when selected, insert extra content into the current step):
- Explain LLM hallucinations
    - Link to remote guide: https://netoftrees.github.io/docs-assembler-demo/
- Explain decision trees
    - Link to map: What are decision trees?
- Explain deterministic
    - Link to map: What is deterministic?

Options:
- Continue


## Node 2: What does this extension do?

Main text:
This extension lets you build documentation that branches in different directions.

You write content in Markdown. You organise it into maps. A map is a set of steps followed by options.

The key difference: maps can call other maps and return. This means you never duplicate content. You build reusable pieces, like functions in code.

The result is documentation that adapts to the user's situation without becoming a mess to maintain.

Options:
- Continue to the tutorial
- Watch the video tutorial (link to video)
- Explore the demo guide (link to demo)


## Node 3: Why does this matter?

Main text:
The demo is large. Some pathways through it are hundreds of steps long. This extension (plus Git hosting) is designed for building documentation for complex systems.

If you've ever copied and pasted the same paragraph into ten different documents, then updated it and missed a spot, this tool solves that.

Options:
- Continue


## Node 4: What makes this different?

Main text:
This tutorial demonstrates what is unique about this extension and how it enables you to build complex documentation – or any text that would benefit from branching and deduplication.

The key concepts are:

- Modularisation and routing – multiple exits, deduplication, scalability
- Nesting – how it handles massive maps
- Absolute ownership – your Git repos, your control. No subscription
- Publish to Markdown – edit anywhere if you uninstall. No lock-in
- Remote guides – use third-party guides in your maps. Offload maintenance to those who know the component best

Options:
- Continue


## Node 5: Routing

Main text:
We'll start with routing – the most distinctive feature.

Options:
- Go to Routing sub-map
- Skip to next concept


## Node 6: Nesting

Main text:
Next, how nesting keeps large maps manageable.

Options:
- Go to Nesting sub-map
- Skip to next concept


## Node 7: Ownership and publishing

Main text:
How content ownership and publishing work.

Options:
- Go to Ownership sub-map
- Skip to next concept


## Node 8: Remote guides

Main text:
Using guides published and maintained by others.

Options:
- Go to Remote guides sub-map
- Skip to next concept


## Node 9: Summary

Main text:
You've completed the tutorial. Here's a recap of the benefits.

Options:
- Go to Summary sub-map
- End


______________________________________________________________


## Routing map

## Node 1: What is routing?

Main text:
Routing lets one map call another map and then return to where it started.

Think of it like a function call in code:
- The main map calls a sub-map.
- The sub-map runs its steps.
- When finished, control returns to the main map.

This keeps each map focused on one job. Complex logic lives in its own map, not cluttering the main path.

Options:
- Continue – see an example


## Node 2: An example

Main text:
Imagine an organisation that runs three similar but not identical production lines.

It builds one main diagnostic map for troubleshooting problems across all three lines.

At a certain point, the main map needs to know which line the problem is on. Instead of writing every possibility inside the main map, it routes to a smaller map specific to that line.

That sub-map handles the specialised checks and can exit in different ways depending on what it finds.

The main map does not need to know the details inside the sub-map. It only needs to know which exit was taken to decide what to do next.

Options:
- Continue – remote guides


## Node 3: Routing to remote guides

Main text:
You can link to remote guides the same way you link to maps.

A remote guide might be written by a component vendor and hosted on their GitHub Pages site. If the vendor updates their guide, your guide automatically uses the new version. You change nothing.

Options:
- Continue – benefits


## Node 4: Benefits of routing

Main text:
The map stays short. Each piece stays focused on its own level of detail. Specialised knowledge lives in its own place. The main map remains clean.

The user never sees irrelevant steps. Content appears only when needed. Your map stays simple and easy to maintain, even as procedures within sub-maps or remote guides change over time.

Options:
- Continue – summary


## Node 5: Summary

Main text:
In this sub-map you have seen:

- Deferred questions – the map asks for specific details only when the answer matters
- Routing to specialised sub-maps – unique details live in their own place
- Multiple exit points – a sub-map can return different results
- Remote guides – vendor-maintained content that appears only when required

The result is a diagnostic system that gives the minimal number of steps to a solution. The user is never asked a question or given an instruction that is not yet relevant.

Options:
- Return to main tutorial

______________________________________________________________



______________________________________________________________



______________________________________________________________



______________________________________________________________



______________________________________________________________



______________________________________________________________



______________________________________________________________



______________________________________________________________