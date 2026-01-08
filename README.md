# CyberCrime Investigation (Java)

## Overview
CyberCrime Investigation is a Java project focused on implementing and using a **hash table-based system** to manage cybercrime suspect records (e.g., `Hacker` objects) and related events/incidents. The project emphasizes efficient operations such as insertion, lookup, and removal, along with correct handling of collision-related logic through supporting structures.

---

## Project Structure
src/
  investigation/
    CyberCrimeInvestigation.java
    Driver.java
    Hacker.java
    HNode.java
    Incident.java
    MaxPQ.java
    StdIn.java
    StdOut.java

---

## Core Concepts
- Hash tables and hashing
- Collision-related handling through supporting node/record structures
- Object-based storage and retrieval
- Priority queue usage (`MaxPQ`) as part of investigation workflows (if applicable)

---

## Key Classes (High Level)

### `CyberCrimeInvestigation`
Main implementation file containing the core investigation/hash-table logic and operations.

### Supporting Classes
- `Hacker`, `Incident`: represent investigation entities
- `HNode`: node/structure used by the data storage system
- `MaxPQ`: priority queue utility used for ranking/selection operations
- `StdIn`, `StdOut`: I/O utilities

### `Driver`
Entry point used to run and test the system using provided scaffolding.

---

## How to Run

### Compile
```bash
javac src/investigation/*.java
```

---

## What I learned
How hash-based storage can enable fast average-case lookups
Designing data structure logic around real objects and required interfaces
Integrating core logic with provided scaffolding and utilities

---

## Notes
CyberCrimeInvestigation.java was implemented as part of the course assignment.
Supporting files (Driver, model classes, and utility classes) were provided as scaffolding and were not modified.
