# Defusing-Binary-Bomb
The purpose of this project is to become more familiar with machine level programming.


  Your job for this lab is to defuse your bomb.
  You can use many tools to help you defuse your bomb. Please look at the hints section for some tips and ideas. The
best way is to use your favorite debugger to step through the disassembled binary.
  Although phases get progressively harder to defuse, the expertise you gain as you move from phase to phase should
offset this difficulty. However, the last phase will challenge even the best students, so please don’t wait until the last
minute to start.
  The bomb ignores blank input lines. If you run your bomb with a command line argument, for example,
linux> ./bomb psol.txt
then it will read the input lines from psol.txt until it reaches EOF (end of file), and then switch over to stdin.
  To avoid accidentally exploding the bomb, you will need to learn how to single-step through the assembly code and
how to set breakpoints. You will also need to learn how to inspect both the registers and the memory states. One of
the nice side-effects of doing this project is that you will get very good at using a debugger. This is a crucial skill
that will pay big bonuses the rest of your career.
  The first four phases are worth 15 points each. Phases 5 and 6 are a little more difficult, so they are worth 20 points
each.
