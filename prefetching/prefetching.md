
Prefetching stuff goes here!

Example of usage: /u/csc368h/winter/pub/bin/gem5.opt prefetchTagged.py daxpy --binary_args 1000

Look at the following section in stats.txt:

Instruction Cache:
![image](https://github.com/user-attachments/assets/58c312ce-aa61-493a-9f29-c1046e954bc3)

Data Cache:
![image](https://github.com/user-attachments/assets/8fbeeda6-97af-492d-9666-f763036f7827)

# System config:

Freq: 75Mhz

CPU voltage: 1V

Memory: DDR3_1600_8x8 (8GB)

CPU type: X86TimingSimpleCPU (unless otherwise specified)

L1 Instruction Cahce:

assoc = 2
tag_latency = 1
data_latency = 1
response_latency = 1
mshrs = 8
tgts_per_mshr = 20
size='4kB'

L1 Data Cache:
assoc = 2
tag_latency = 1
data_latency = 1
response_latency = 1
mshrs = 8
tgts_per_mshr = 20
size='4kB'






