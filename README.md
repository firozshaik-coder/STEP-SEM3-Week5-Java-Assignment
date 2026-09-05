# STEP SEM-3 Week 5 - Java Arrays and Methods

Category C Assignment Problems from CodInClub / BridgeLabz.

## Problems

1. Fantasy Team Score Multiplier
2. Duplicate Player Pick Checker
3. Top Performer Tracker
4. Match Day Grid Analyzer
5. Fantasy League Auto-Draft Ranking Engine

## Java version

Java 8 or later.

## Compile

```bash
javac Problem1.java
java Problem1
```

Repeat for Problems 2-4.

For Problem 5:

```bash
javac Player.java
java Player
```

## Problem 5 thresholds

The assignment says to decide the exact thresholds. This implementation uses:

- Experience-only rule: `matchesPlayed >= 10`
- Combined rule: `matchesPlayed >= 5 && !injured`

Ranking is by batting average in descending order using `Comparable<Player>` and `Arrays.sort()`.

## Expected sample outputs

Problem 1:
`[40.0, 110.0, 30.0, 93.0]`

Problem 2:
`Duplicate Found: Kohli`

Problem 3:
`Min: 33 | Max: 90 | Spread: 57`

Problem 4:
`Match 0: Normal | Match 1: Power Surge | Match 2: Normal`

Problem 5:
`1. Rahul | 2. Virat | 3. Dev`
