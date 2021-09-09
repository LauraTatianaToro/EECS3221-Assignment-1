# Ring of N processess 

TOOLS USED: ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

A simple program called ring that creates a ring of N processes that
send a signal round and round cnt times. 

The program is invoked with
./ring N leader cnt

Processes are created using  fork-exec and SIGUSR1 to send signals.

