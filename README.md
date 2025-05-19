# FORMAL-DATA-VALIDATION-CHALLENGE-2025

The RSSRail 2025 conference will organise a data validation challenge to promote the use of formal methods for validating constant data among CBTC and ERTMS industry companies, operators, and research teams. 
We encourage potential participants to register by sending an email to matthias.oustric@clearsy.com and to share their work at this unique event.

## What?
The goal? To identify anomalies in a database for a specified list of self-sufficient specifications. 
This database, especially designed for this event will use the open format of the ERTMS system. 
It will include key elements such as telegrams, transponders, and LEUs. 
The tasks aim to verify the coherence of telegram formats, the rules of transponder positions, and the construction of movement authority packets within a realistic framework. 
Participation is free and open to all teams, from academia and from industry.


## How?
The challenge is designed to be completed in one week by a team of 2 to 3 people. 
The necessary resources (specification, data) will be accessible on this dedicated github repository from June to November 2025, allowing participants to organize their resolution team. 
The data will be produced in .xml and .xlsx formats for wide accessibility. 
A support will be provided during this period to address any questions and resolve issues. 
Questions and answers will be shared with all participants to ensure a common understanding.


## When?
During the conference a dedicated 1h30 session will enable participating teams to present their analyses and discuss the results. 
This will be the opportunity for newcomers to engage with the subject thanks to this hands-on experience. 


## Explanations
### What is Formal Data Validation?
Formal data validation in the railway industry refers to the use of formal methods (mathematically-based techniques) to systematically and rigorously verify the correctness of data used in safety-critical systems. 
It is especially crucial in railways, where incorrect configuration data (e.g., track topology, signal positions, speed limits) can lead to unsafe behavior, even if the software is correct.

###  What is "data" in this context?
In railway systems, large amounts of configuration data are used to adapt generic software to specific track layouts and operational scenarios. Examples include:
- Geometry and topology of the railway network
- Positions and parameters of signals and switches
- Speed profiles
- Balise group positions (for ERTMS)
- Route tables and interlocking rules

### What does "formal validation" do?
Formal data validation checks that all data used by the safety-critical software:
- Are correct (conform to rules and constraints)
- Are complete (nothing missing)
- Are consistent (no internal contradictions)
- Preserve safety properties (e.g., no two conflicting routes active at the same time)


### Typical techniques used
- Modeling of data constraints using formal specification languages (e.g., B, Event-B, Z, or custom domain-specific languages)
- Automated or semi-automated checking using tools
- Proofs or exhaustive checks that the data satisfy safety invariants
