# TuduMVC - a Vanilla.js Implementation of TodoMVC with Urbit Integration

TuduMVC is an implementation of the Vanilla.js version of TodoMVC using an Urbit backbone to support data storage, todo-list modifications (mark as complete, add items, list items, etc.), and serving of the front end page itself.  This guide consists of two parts, each sub-divided into several sub-guides:
1. The **first part** will cover the process from setting up a ship (a unit of the Urbit identity space), hosting the *vanilla* Vanilla.js implementation of TodoMVC, creating a data structure in our application that will house the todo list we're generating from hosting TodoMVC and modifying the Vanilla.js implementation of TodoMVC to communicate with our Urbit as a back-end for that todo list data.  Completing this part of the guide will help you gain confidence in your ability to:
    * Install the Urbit binary and boot a ship
    * Create an efficient and replicable development cycle
    * View, use and modify the files within an operating Urbit ship
    * Set up a repository for your code on git
    * Use and understand Gall agents within Urbit
    * Serve content from your urbit, using both `file-server` and a Gall agent
    * Create a data structure within a Gall agent
    * Update and recompile a Gall agent to accommodate new data structures
    * Create "structures" and "marks" (`/sur` and `/mar` files) to accompany your Gall agents
    * Understand the basics of the type system within Urbit
2. The **second part** will improve our initial implementation by adding in collaborative features to TodoMVC <to be written>.  Completing this second part of the guide will improve your confidence with Gall agents by introducting teh following abilities:

Let's get started!


