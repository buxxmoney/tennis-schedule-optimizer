---
title: Demo
description: "See how the optimizer recommends matchups using mock data."
weight: 4
---

## 🧾 Coach Input Example: Santa Clara University

To generate the optimized non-conference schedule below, the coach at Santa Clara would provide the following inputs:

### 🎾 Team Information

| Input Category         | Example Input                                     |
|------------------------|---------------------------------------------------|
| **Team Name**          | Santa Clara University                           |
| **Team Rank**          | 40                                                |
| **Location**           | Santa Clara, California                          |
| **Max # of Matches**   | 7 non-conference matches                          |
| **Travel Budget**      | $6,000                                            |
| **Climate Preference** | Warm weather preferred for January–February      |
| **Surface Preference** | Outdoor only                                      |
| **Preferred Opponent Tier** | Opponents ranked #20–75                    |
| **Available Weeks**    | Jan 15 – March 10                                 |
| **Home/Away Ratio**    | At least 3 home matches, max 4 away               |
| **Conference Rules**   | No shared travel partners, max 2 time zones per trip |
| **Player Experience (Optional)** | Prefer matchups against experienced lineups |

---

These inputs are processed by the optimization engine to:
- Filter out invalid matchups
- Score remaining matchups using the match value formula
- Output a ranked list of high-impact, winnable matches that align with coach preferences

---

### 🎾 Santa Clara - Optimized Schedule

| Opponent     | Rank | Location | Match Value | Reason                        |
|--------------|------|----------|-------------|-------------------------------|
| UC Irvine    | 52   | Away     | 44.0        | Ranked opponent, good odds   |
| BYU          | 70   | Home     | 22.0        | Winnable match with points   |
| Denver       | 47   | Away     | 40.3        | Road match w/ ranking boost  |
| UConn        | 36   | Home     | 50.2        | Strong opponent, home edge   |
| Rice         | 58   | Away     | 39.1        | Value in away match bonus    |
| Air Force    | 72   | Home     | 18.7        | Fills 7-match requirement    |

> **Total projected points**: 214.3
