# pprof
pprof for sem02 is-105 uia
Wordcount01 Storfil
BRUKERNAVN@b27a9786a460:~/pprof$ time sudo ./wordcount01 2701-0.txt
2023/03/10 07:52:33 profile: memory profiling enabled (rate 1), mem.pprof
"2701-0.txt": 181320 words
2023/03/10 07:52:36 profile: memory profiling disabled, mem.pprof

real    0m3.107s
user    0m0.012s
sys     0m0.011s

Wordcount02 Storfil
BRUKERNAVN@b27a9786a460:~/pprof$ time sudo ./wordcount02 2701-0.txt
2023/03/10 07:58:30 profile: cpu profiling enabled, cpu.pprof
"2701-0.txt": 181320 words
2023/03/10 07:58:30 profile: cpu profiling disabled, cpu.pprof

real    0m0.277s
user    0m0.007s
sys     0m0.021s

Wordcount03 Storfil
BRUKERNAVN@b27a9786a460:~/pprof$ time sudo ./wordcount03 2701-0.txt
2023/03/10 07:58:21 profile: memory profiling enabled (rate 1), mem.pprof
"2701-0.txt": 181320 words
2023/03/10 07:58:21 profile: memory profiling disabled, mem.pprof

real    0m0.118s
user    0m0.007s
sys     0m0.028s
