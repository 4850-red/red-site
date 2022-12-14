---
layout: default
parent: Development
nav_order: 1
---

# Research

A lot of research had to be done so that the technical specifications of the UXA-90 robot could be documented that were needed for development. The initial documentation that came with the robots was sparse on exact operating details of the robot. As such, initial research was done in operating proceedures of the robot and documented on the [training](training) page.

## Motor Ranges

To document the motor ranges, A webapp was created to select motors and control them with a slider, similar to what is in the app. The following data about the motors was then determined:
- Minimum
- Maximum
- Default position

| Motor ID | Motion | Minimum | Default | Maximum | Notes |
0 | Left foot tilt | 127 | 115 | 140 | Inwards to outwards
1 | Right foot tilt | 127 | 110 | 140 | Outwards to inwards
2 | Left foot | 127 | 77 | 175 | Down to up
3 | Right foot | 127 | 78 | 175 | Up to down
4 | Left knee | 204 | 77 | 204 | Backwards to forwards
5 | Right knee | 50 | 50 | 180 | Forwards to backwards
6 | Left leg kick | 127 |  |  | Forwards to backwards
7 | Right leg kick | 127 |  |  | Backwards to forwards
8 | Left leg outward | 127 |  |  | Inwards to outwards
9 | Right leg outward | 127 |  |  | Outwards to inwards
10 | Left leg rotate | 127 |  |  | Outwards to inwards
11 | Right leg rotate | 127 |  |  | Inwards to outwards
12 | Left arm rotate hole | 180 | 10 | 254 | 10 is straight up
13 | Right arm rotate whole | 180 | 1 | 254 | 254 is straight up
14 | Left arm rotate out | 115 | 1 | 120 | 115 is up
15 | Right arm rotate out | 138 | 130 | 254 | 254 is up
16 | Left arm rotate in | 120 | 1 | 254 |
17 | Right arm rotate in | 128 | 1 | 254 |
18 | Left elbow | 48 | 48 | 190 | 190 is up
19 | Right elbow | 210 | 65 | 210 | 210 is up
22 | Hip rotate | 127 | 90 | 170 | 127 is right
23 | Head yaw |  |  |  |
24 | Head pitch |  | 70 | 160 |
