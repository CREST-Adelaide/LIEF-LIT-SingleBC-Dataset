Hardware infrastructure:
- CREST-NUC-1: 129.127.231.53
- CREST-Edge-1b: 129.127.230.61
- CREST-Edge-2b: 129.127.231.125
- CREST-Edge-3b: 129.127.231.162
- CREST-Edge-4b: 129.127.231.168

Request:
- Ch1: PoW-X64-ARMv7
- Ch2: PoW-X64-ARMv7
- Evaluation: Ch1-Performance-ResourceConsumption
- Evaluation: Ch2-Performance-ResourceConsumption

Experiment Plan:
1. Verifier(request)
2. DeplPoW_X64_ARM(Ch1)
3. DeplPoW_X64_ARM(Ch2)
4. EvalPerformanceEthereum(Ch1)
5. EvalPerformanceEthereum(Ch2)