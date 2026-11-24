# Pulau Tidak Ada — Treasure Map

[![make.fun · u-ravendell-charm-the-cartographers-a-one-day-00854547](https://make.fun/badge/u-ravendell-charm-the-cartographers-a-one-day-00854547.svg)](https://make.fun/bounty/u-ravendell-charm-the-cartographers-a-one-day-00854547?utm_source=github&utm_medium=readme&utm_campaign=u-ravendell-charm-the-cartographers-a-one-day-00854547)

A treasure map of an island that does not exist, drawn 100% procedurally by
`main.ts` — no image assets, no system fonts, no network. Every pixel,
including the 5×7 bitmap font used for the place labels, is generated in code.

The island holds Gunung Tugas Menumpuk, Bukit Meeting Tanpa Akhir, Hutan
Wi-Fi Hilang, Teluk Lupa Password, Danau Kopi Dingin, Pantai Cuti Tertunda,
and Tanjung Deadline — plus a polite sea monster, a compass rose, a little
ship, and a dashed footpath from the landing beach to the red X where the
treasure supposedly is ("di sini, katanya").

## Run locally

```sh
mkdir -p out
MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.png — 1024x1024 PNG, under 1 MiB
```

Requires Node 22 or later. No dependencies to install.
