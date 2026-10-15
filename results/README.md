# Simulation logs referenced in Summary.pdf

File names are <configuration>_<trace>.txt.

task1/   Task 1B. no_prefetch_lru = baseline; ip_stride_lru = reference IP-stride; spp_lru = SPP.
task2a/  Task 2A, no prefetcher. lru, rrip, irrip_4ways (submitted I-RRIP); irrip_2/6/8ways = protected-ways sweep.
task2b/  Task 2B, no prefetcher. dyn_irrip = final Dynamic I-RRIP; dyn_irrip_threshold* = threshold sweep
         (0.15 is the same configuration as dyn_irrip); dyn_irrip_16leaders / 64leaders = leader-set sweep.
task3/   Task 3, SPP at L1D. spp_lru, spp_dyn_irrip (unmodified 2B policy), spp_pa_dyn_irrip (prefetch-aware, submitted).
plots/   The figures used in Summary.pdf.
         speedup/mpki/accuracy/coverage.png  = Task 1B (Figure 1)
         t2s_*.png                           = Tasks 2A and 2B (Figures 2 and 3)
         t3s_*.png                           = Task 3 (Figures 4 and 5)
