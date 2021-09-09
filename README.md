# Ring of N processess 

TOOLS USED: ![VSCode](https://img.shields.io/badge/-VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat-square&logo=visual-studio-code&logoColor=whit)

A simple program called ring that creates a ring of N processes that
send a signal round and round cnt times. 

The program is invoked with
./ring N leader cnt

Processes are created using  fork-exec and SIGUSR1 to send signals.

