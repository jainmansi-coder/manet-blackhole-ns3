# MANETShield: Blackhole Attack Detection & Prevention in NS-3

## Overview
This project implements a Mobile Ad hoc Network (MANET) simulation using NS-3 (v3.43)
to demonstrate a Blackhole attack on the AODV routing protocol and evaluates
detection and prevention mechanisms.

## Scenarios Implemented
1. Baseline MANET (No attack)
2. MANET under Blackhole Attack
3. MANET with Blackhole Detection & Prevention

## Performance Metric
- Packet Delivery Ratio (PDR)

## Results Summary
| Scenario | PDR |
|--------|-----|
| Baseline | 0.79 |
| Attack | 0.73 |
| Prevention | 0.63 |

## Files
- scratch/manet-baseline.cc : Baseline simulation
- scratch/manet-attack.cc : Blackhole attack simulation
- scratch/manet-prevention.cc : Detection & prevention logic
- baseline.txt : Output results
- attack.txt : Output results
- prevention.txt : Output results

## Tools & Environment
- NS-3.43
- C++
- Ubuntu (WSL)

## Author
**Jain Mansi**
