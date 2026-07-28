# Cache_Computer_Organization_HW
## RISC-V Spike Cache Replacement Policy: Random → FIFO

修改開源 RISC-V ISA 模擬器 [Spike (riscv-isa-sim)](https://github.com/riscv-software-src/riscv-isa-sim) 
的 cache 模組，將原本的 LFSR 隨機替換策略改為 FIFO（先進先出），
分別實作於 set-associative（每個 set 一條 FIFO queue）與
fully-associative（單一全域 FIFO queue）兩種 cache 架構。
