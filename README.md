git-practice
============

This is experimental repository containing lectures/tasks to practice using
of Git. I found that many users learn just elementary of Git and any more
complex task take a lot of tim

The goal of this project is to help to learn new and slightly advanced users of
Git how to use this tool. Basic idea is to provide tasks that will show how
to use Git, firstly just in blind basic (simple) way, that is not usually
optimal and later jump to tasks that point users to optimize their processes
to save time.

Tasks will be added & modified continuosly over time as I do that just in my
free time. Similarly the repository and readme will be modified over time to
find the best concept how to achieve goals of this project.

Description of tasks (DRAFT)
============================

branch based
------------

Each task is in separate branches. Usually a task needs one branch with task
itself and second branch with results, to see expected solution. Default names
of branches contain suffixes:
  -task0001
  -task0001-result

Each branch should contain a **task** file with complete description of the task.
Optionally can contain a **task-result** file that contains instructions, how
to meet goals of the task.

or branch + folders
-------------------

Branches are created only in case they are needed by specific task. Otherwise
there are used branches described just in tasks. Usually some branches can be
same for specific tasks.

Tasks itself are described in files under specific directory structure
corresponding to expected sections. E.g.:

    .
    ├── 01-Elemenary
    |   └── 01-commit
    |       ├── task.md
    |       └── task-result.md
    ├── 02-Rebase-and-Merge
    |   └── 01-simple-merge
    |       ├── task.md
    :       └── task-result.md


Sections (DRAFT)
================

**Note**: *This is really just draft. Probably it will be split into different
sections in future.*

1. Elementary
2. Rebase and merge
3. Configuration
4. Search and debug

Contribution
============

As I said, I do that just in my free time, so any help is appreciated. Whole
project is still under heavy draft, how everything will be provided. I guess
that better design will be produced when more tasks will be added.

