```
██████╗ ██╗██╗   ██╗ █████╗     ██████╗ ██╗    ██╗██╗██╗   ██╗███████╗██████╗ ██╗
██╔══██╗██║╚██╗ ██╔╝██╔══██╗    ██╔══██╗██║    ██║██║██║   ██║██╔════╝██╔══██╗██║
██████╔╝██║ ╚████╔╝ ███████║    ██║  ██║██║ █╗ ██║██║██║   ██║█████╗  ██║  ██║██║
██╔══██╗██║  ╚██╔╝  ██╔══██║    ██║  ██║██║███╗██║██║╚██╗ ██╔╝██╔══╝  ██║  ██║██║
██║  ██║██║   ██║   ██║  ██║    ██████╔╝╚███╔███╔╝██║ ╚████╔╝ ███████╗██████╔╝██║
╚═╝  ╚═╝╚═╝   ╚═╝   ╚═╝  ╚═╝    ╚═════╝  ╚══╝╚══╝ ╚═╝  ╚═══╝  ╚══════╝╚═════╝ ╚═╝
```

```bash
riya@iiitbhopal:~$ uname -a
Linux iiitbhopal 6.6.0-arch1 #1 SMP PREEMPT_DYNAMIC x86_64 GNU/Linux

riya@iiitbhopal:~$ whoami
riya

riya@iiitbhopal:~$ cat /etc/motd
┌─────────────────────────────────────────────────────────────────┐
│  Welcome. You've landed on Riya Dwivedi's corner of the web.   │
│  CSE @ IIIT Bhopal  ·  Semester III  ·  Breaks things to       │
│  understand them.                                               │
└─────────────────────────────────────────────────────────────────┘
```

---

```bash
riya@iiitbhopal:~$ cat /proc/self/status
Name:           Riya Dwivedi
State:          R (running)
Institute:      Indian Institute of Information Technology, Bhopal
Branch:         Computer Science & Engineering
Semester:       III
VmPeak:         ∞ kB
Threads:        1  (focused, not scattered)
Quirk:          Breaks things to understand them
SigBlk:         tutorial-before-docs
SigIgn:         imposter syndrome
SigCgt:         segfaults, TLEs, wrong answers
```

---

```bash
riya@iiitbhopal:~$ tree ~/skills --charset=ascii
~/skills
|-- languages/
|   |-- C++             [primary]  ████████████░░  strong
|   |-- Python          [primary]  █████████░░░░░  comfortable
|   `-- C               [base]     ███████░░░░░░░  solid foundation
|
|-- focus/
|   |-- DSA/
|   |   |-- arrays, strings, recursion
|   |   |-- linked lists, stacks, queues
|   |   |-- binary search (and its dark arts)
|   |   |-- trees — BST, traversals, height tricks
|   |   `-- sorting — bubble to merge to "why does quicksort work"
|   |
|   `-- competitive-programming/
|       |-- problem decomposition
|       |-- greedy intuition building
|       `-- time complexity reasoning
|
`-- cs-fundamentals/
    |-- OOP concepts (C++)
    |-- memory layout — stack vs heap
    `-- pointers (the fun kind)
```

---

```bash
riya@iiitbhopal:~$ git log --oneline --graph --all
* 7f3a1c2  (HEAD -> now)    actively grinding DSA, building problem-solving muscle
* 4e9b0d8  (semester-III)   got comfortable with trees and recursion
* 2c81f3a  (semester-II)    linked lists clicked — finally
* 9d04e71  (semester-I)     wrote first C++ program, broke it immediately, fixed it
* 1b72ca0  (pre-college)    curious kid who took apart things to see what's inside
* 0000000  (origin)         "why does this work?" — the question that started it all
```

---

```bash
riya@iiitbhopal:~$ grep -rn "deep_interest" ~/brain/ --include="*.log"

./brain/rabbit_holes.log:42:  TOPIC: How computers actually sort things
./brain/rabbit_holes.log:43:  ├── Why O(n log n) is the wall you can't break for comparisons
./brain/rabbit_holes.log:44:  ├── Radix sort — when you escape the comparison model entirely
./brain/rabbit_holes.log:45:  └── The moment merge sort's divide-and-conquer "clicked" visually

./brain/rabbit_holes.log:61:  TOPIC: Recursion — not the syntax, the thinking
./brain/rabbit_holes.log:62:  ├── Trust the function you haven't written yet
./brain/rabbit_holes.log:63:  ├── Base case as the only truth you're allowed to assume
./brain/rabbit_holes.log:64:  └── Call stack visualization — drawing boxes until it made sense

./brain/rabbit_holes.log:89:  TOPIC: Binary search beyond "find the index"
./brain/rabbit_holes.log:90:  ├── Searching on the answer space, not the array
./brain/rabbit_holes.log:91:  ├── Why lo + (hi - lo) / 2 instead of (lo + hi) / 2
./brain/rabbit_holes.log:92:  └── Predicate-based thinking — true/false boundaries
```

---

```bash
riya@iiitbhopal:~$ diff ~/me_before_college ~/me_now
--- a/me_before_college
+++ b/me_now
@@ -1,7 +1,7 @@
-  knows: basic maths, curiosity
+  knows: C++, Python, DSA fundamentals, OOP, recursion
-  reaction to errors: panic
+  reaction to errors: read the message, trace the stack
-  problem-solving: "I'll just try things randomly"
+  problem-solving: "what's the smallest subproblem here?"
-  relationship with loops: "why won't it stop"
+  relationship with loops: "off-by-one again, classic"
+  new trait: breaks things on purpose now
+  new trait: enjoys the segfault more than the success
```

---

```bash
riya@iiitbhopal:~$ man riya

RIYA(1)                    User Commands                    RIYA(1)

NAME
       riya - a work-in-progress system optimized for problem solving

SYNOPSIS
       riya [--think] [--break] [--fix] [--repeat] <problem>

DESCRIPTION
       riya is an IT undergraduate at IIIT Bhopal, currently in
       Semester III. Primary function: decompose hard problems into
       smaller ones until they feel embarrassingly simple.

       Operates best between 10pm and 2am. May emit warning-level
       output when a solution is inelegant.

OPTIONS
       --think         Stares at the problem before touching keyboard.
                       Recommended. Often skipped by peers.

       --break         Intentional failure mode. Inputs edge cases,
                       breaks assumptions, stress-tests the logic.
                       Not a bug — this is the workflow.

       --fix           Traces root cause. Does not patch symptoms.

       --repeat        Loops until understood, not just until working.

       --help          You're reading it.

KNOWN BUGS
       - Occasionally over-engineers solutions
       - Explains time complexity to people who did not ask
       - Will rewrite code from scratch if it "feels wrong"

EXIT STATUS
       0   Problem solved and understood
       1   Problem solved but not understood (treated as failure)

SEE ALSO
       cppreference(1), codeforces(1), gdb(1)

AUTHOR
       Riya Dwivedi <riyadwivediarp-hash@github>
```

---

```bash
riya@iiitbhopal:~$ ls -la ~/currently/
total 3
drwxr-xr-x  riya  riya   building problem-solving intuition through CP
drwxr-xr-x  riya  riya   implementing classic DSA from scratch (no copy-paste)
drwxr-xr-x  riya  riya   learning to think before typing
```

---

```bash
riya@iiitbhopal:~$ cat .hidden/easter_egg.txt
cat: .hidden/easter_egg.txt: Permission denied

riya@iiitbhopal:~$ sudo cat .hidden/easter_egg.txt
[sudo] password for riya: 

The real trick with DSA isn't memorizing algorithms.
It's learning to see the shape of a problem before you
know its name. A graph problem doesn't announce itself.
A greedy solution doesn't come with a label.

You get there by breaking enough things to know
what they look like from the inside.

-- riya, 2am, after a tree problem finally made sense
```

---

```bash
riya@iiitbhopal:~$ echo "find me here"
  GitHub   →  github.com/riyadwivediarp-hash

riya@iiitbhopal:~$ shutdown -h now
Connection to riya@iiitbhopal closed.

└─❯ ▌
```
