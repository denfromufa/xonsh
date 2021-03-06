================
Xonsh Change Log
================

Current Developments
====================
**Added:**

* timeit alias will now complete its arguments.
* $COMPLETIONS_MENU_ROWS environment variable controls the size of the 
  tab-completion menu in prompt-toolkit.

**Changed:**

* Prompt-toolkit shell will now dynamically allocate space for the 
  tab-completion menu.

**Deprecated:**

None

**Removed:**

None

**Fixed:**

* First prompt in the prompt-toolkit shell now allows for up and down
  arrows to search through history.

**Security:**

None


v0.2.1 - v0.2.4
===============
You are reading the docs...but you still feel hungry.

v0.2.0
=============
**Added:**

* Rich history recording and replaying

v0.1.0
=============
**Added:**

* Naturally typed environment variables
* Inherits the environment from BASH
* Uses BASH completion for subprocess commands
* Regular expression filename globbing
* Its own PLY-based lexer and parser
* xonsh code parses into a Python AST
* You can do all the normal Python things, like arithmetic and importing
* Captured and uncaptured subprocesses
* Pipes, redirection, and non-blocking subprocess syntax support
* Help and superhelp with ? and ??
* Command aliasing
* Multiline input, unlike ed
* History matching like in IPython
* Color prompts
* Low system overhead




<v0.1.0
=============
The before times, like 65,000,000 BCE.
