riya@iiitbhopal — terminal
██████╗ ██╗██╗ ██╗ █████╗
██╔══██╗██║╚██╗ ██╔╝██╔══██╗
██████╔╝██║ ╚████╔╝ ███████║
██╔══██╗██║ ╚██╔╝ ██╔══██║
██║ ██║██║ ██║ ██║ ██║
╚═╝ ╚═╝╚═╝ ╚═╝ ╚═╝ ╚═╝
██████╗ ██╗ ██╗██╗██╗ ██╗███████╗██████╗ ██╗
██╔══██╗██║ ██║██║██║ ██║██╔════╝██╔══██╗██║
██║ ██║██║ █╗ ██║██║██║ ██║█████╗ ██║ ██║██║
██║ ██║██║███╗██║██║╚██╗ ██╔╝██╔══╝ ██║ ██║██║
██████╔╝╚███╔███╔╝██║ ╚████╔╝ ███████╗██████╔╝██║
╚═════╝ ╚══╝╚══╝ ╚═╝ ╚═══╝ ╚══════╝╚═════╝ ╚═╝
riya@iiitbhopal:~$ uname -a
Linux iiitbhopal 6.6.0-arch1 #1 SMP PREEMPT_DYNAMIC x86_64 GNU/Linux
riya@iiitbhopal:~$ cat /etc/motd
┌─────────────────────────────────────────────────────────────────────┐
│ Welcome. You've landed on Riya Dwivedi's corner of the web. │
│ CSE @ IIIT Bhopal · Semester III · Breaks things to understand them. │
└─────────────────────────────────────────────────────────────────────┘
riya@iiitbhopal:~$ cat /proc/self/status
Name: Riya Dwivedi
State: R (running)
Institute: Indian Institute of Information Technology, Bhopal
Branch: Computer Science & Engineering
Semester: III
VmPeak: ∞ kB
Threads: 1 (focused, not scattered)
Quirk: Breaks things to understand them
SigBlk: tutorial-before-docs
SigIgn: imposter syndrome
SigCgt: segfaults, TLEs, wrong answers
riya@iiitbhopal:~$ tree ~/skills --charset=ascii
~/skills
|-- languages/
| |-- C++ [primary]
strong
| |-- Python [primary]
comfortable
| `-- C [base]
solid foundation
|
|-- focus/
| |-- DSA/
| | |-- arrays, strings, recursion
| | |-- linked lists, stacks, queues
| | |-- binary search (and its dark arts)
| | |-- trees — BST, traversals, height tricks
| | `-- sorting — bubble to merge to "why does quicksort work"
| `-- competitive-programming/
| |-- problem decomposition
| `-- greedy intuition + time complexity reasoning
riya@iiitbhopal:~$ git log --oneline --graph --all
* 7f3a1c2 (HEAD → now) actively grinding DSA, building problem-solving muscle
* 4e9b0d8 (semester-III) got comfortable with trees and recursion
* 2c81f3a (semester-II) linked lists clicked — finally
* 9d04e71 (semester-I) wrote first C++ program, broke it immediately, fixed it
* 1b72ca0 (pre-college) curious kid who took apart things to see what's inside
* 0000000 (origin) "why does this work?" — the question that started it all
riya@iiitbhopal:~$ grep -rn "deep_interest" ~/brain/ --include="*.log"
./brain/rabbit_holes.log:42:
TOPIC: How computers actually sort things
├── Why O(n log n) is the wall you can't break for comparisons
├── Radix sort — when you escape the comparison model entirely
└── The moment merge sort's divide-and-conquer "clicked" visually
./brain/rabbit_holes.log:61:
TOPIC: Recursion — not the syntax, the thinking
├── Trust the function you haven't written yet
├── Base case as the only truth you're allowed to assume
└── Call stack visualization — drawing boxes until it made sense
riya@iiitbhopal:~$ diff ~/me_before_college ~/me_now
--- a/me_before_college
+++ b/me_now
@@ -1,7 +1,7 @@
- knows: basic maths, curiosity
+ knows: C++, Python, DSA fundamentals, OOP, recursion
- reaction to errors: panic
+ reaction to errors: read the message, trace the stack
- relationship with loops: "why won't it stop"
+ relationship with loops: "off-by-one again, classic"
+ new trait: breaks things on purpose now
riya@iiitbhopal:~$ cat .hidden/easter_egg.txt
cat: .hidden/easter_egg.txt: Permission denied
riya@iiitbhopal:~$ sudo cat .hidden/easter_egg.txt
[sudo] password for riya:
The real trick with DSA isn't memorizing algorithms.
It's learning to see the shape of a problem before you know its name.
A graph problem doesn't announce itself.
A greedy solution doesn't come with a label.
You get there by breaking enough things to know what they look like from the inside.
-- riya, 2am, after a tree problem finally made sense
riya@iiitbhopal:~$ echo "find me here"
GitHub → github.com/riyadwivediarp-hash
riya@iiitbhopal:~$ shutdown -h now
Connection to riya@iiitbhopal closed.
└─❯ ▌
