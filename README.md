# Variable Neighborhood Search for the Static Aircraft Landing Problem

- **Course:** EMU427 – Heuristic Methods for Optimization (Fall 2026)
- **Institution:** Hacettepe University, Department of Industrial Engineering
- **Group:** Tayyare (Kerem Tayar, Yiğit Akın, Yusuf Başlar, Arda Altın)

## Overview
Google Colab / Python 3.11 implementation of a Variable Neighborhood Search (VNS) metaheuristic coupled with First-Improvement VND (`Swap` and `Insertion`) and an $O(N^2)$ Two-Pass Heuristic Timing Decoder for the static single-runway Aircraft Landing Problem ($R = 1$).

## Files
- `EMU_427.ipynb`: Main Colab notebook containing the data fetcher, VNS/VND/Decoder implementation, and preliminary experiment outputs (`airland1`–`airland8`, `seed = 42`).

## How to Run
Open `EMU_427.ipynb` in Google Colab and run all cells (`Runtime > Run all`). The script automatically downloads the required OR-Library benchmark instances (`airland1`–`airland8`).
