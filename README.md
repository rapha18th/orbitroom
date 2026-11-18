# ORBIT ROOM

**Your room has gravity.** A seated, hands-only mixed reality game. Your furniture becomes a solar system. Pinch the slingshot on your desk, pull back, let go, and put a rocket into orbit around your couch.

**Every mission is proven before you see it.** A planner flies the game's own 41 by 20 launch grid through the same 240 Hz physics you play, in your room. A room fuzzer proves 100 generated rooms on every build.

**Play on a headset:** https://rapha18th.github.io/orbitroom/ in Quest Browser, seated at a desk.
**Play on a computer:** https://rapha18th.github.io/orbitroom/?emulate (the mouse is your right hand).
**Orbit Rush:** https://rapha18th.github.io/orbitroom/?emulate&rush
**Two players, one headset:** https://rapha18th.github.io/orbitroom/?rush&duel
**Video (1:58):** https://youtu.be/h2WVWmuaCQ8

## How to play

**Pinch. Pull. Let go.** A dotted line shows the flight before you release. One full loop wins. A three-step coach teaches the first shot.

**Missions.** M1 orbits a small moon. M2 teaches speed. M3 wakes the room: every piece of furniture pulls. Then a tour of every world the planner can win, with par and stars.

**Orbit Rush.** A timed round of 2, 3 or 5 minutes. Launch a Probe, Satellite or Station (payload 1, 2, 3). Energy keeps each orbit up. Rescue pods refuel. Most payload in orbit wins.

**Duel.** Two players pass one headset. More payload wins.

## How it works

**Room to gravity field.** Scene data gives each piece of furniture a footprint and label. Mass spreads through its volume and a worker bakes the room to a 4 cm field grid.

**Proof first.** A Web Worker planner offers a mission only when it holds a proven winning shot. The ghost pouch loops that shot.

**Quest budgets.** 72 Hz with fixed foveation, one render pass, M3 under 70 draw calls per eye, eight satellites in four instanced draw calls.

**Hands only.** Immersive Web SDK grab, pinch, poke and ray. The pull is one-euro filtered and read 60 ms before release.

Built with the Immersive Web SDK 1.0.1, Three.js and WebXR. This repository holds the built game. The source repository is private.

## Playtesters

**Device check** https://rapha18th.github.io/orbitroom/canary.html runs a two-minute check of pinch, poke, room labels and frame rate.

**Tester play** https://rapha18th.github.io/orbitroom/?tester=1 sends frame times, hand and head positions, the headset and browser version, the room's object labels and launch results to the ORBIT ROOM team. Each report is labelled with a random session code and is deleted after 30 days. The device check sends the same kind of report.
