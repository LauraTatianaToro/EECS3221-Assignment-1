# Ring of N processess 

A simple program called ring that creates a ring of N processes that
send a signal round and round cnt times. 

The program is invoked with
./ring N leader cnt

Processes are created using  fork-exec and SIGUSR1 to send signals.

