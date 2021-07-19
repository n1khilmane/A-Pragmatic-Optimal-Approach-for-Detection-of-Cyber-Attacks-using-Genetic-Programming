## A genetic Programming Model for detection of Cyberattacks

# Statistics

- 94% of malware is delivered via mail.

- Phishing attacks account for more than 80% of reported security
incidents.

- $17,700 is lost every minute due to phishing attacks
- 60% of breaches involved vulnerabilities for which a patch was available
but not applied
- 63% of companies said their data was potentially compromised within
the last 12 months due to hardware-or silicon-level security breach
- Attacks on Iot devices tripled in the first half of 2019
- Data breaches cost enterprises an average of $3.92 million
- 40% of IT leaders say cybersecurity jobs are the most difficult to fill.

# Objectives

✔️ Attackers have been evolving their strategies and methods with time. Using ML/DL methods will certainly improve their exploitations. Hence developing a model which which fights against such threats is very essential.
✔️ Solving a complex attack has become a very difficult task for security engineers. Hence building a self learning model will enhance the ability to identify and rectify such attacks.
✔️ Attacks happen when the systems are most vulnerable, such scenarios will be guarded by the developed model.

# Intrusion Detection System

- An Intrusion detection system (IDS) is a software application or hardware appliance that monitors traffic moving on networks and through systems to search for suspicious activity and known threats, sending up alerts when it finds such items.

# Genetic Programming

- Executional steps for general GP:

1. Generate an initial population of random compositions of the functions and terminals of the problem
(computer programs).
2. Run a tournament, which picks four programs randomly out of the population of programs. It compares them and picks two winners and two losers based on a fitness measure.
3. Apply the search operators crossover and mutation (and possibly others) to the winners to produce offspring in the following way:
a. Copy the two winners
b. With Crossover Frequency, apply crossover to copies of the winners c. With Mutation Frequency, mutate the programs from (a)
4. Replace the tournament losers with the new offspring. The winners of the tournament are unchanged.
5. Repeat until a predefined termination criterion has been satisfied, or a fixed number of generations have been explored.
6. The solution is the genetic program with the best fitness within all the generations.

# Data Acquisition

- Modern DDOS Dataset is used for implementation.
- A novel Dataset which that contains modern kinds of DDoS attacks.
- Generated using NS2 Network simulator.
- The dataset had 2,160,668 number of instances.

# Dataset Classes

- Smurf : The target server receives huge number of ICMP echo requests packet.
- UDP Flood: A massive amount of UDP traffic is sent to inundate the server.
- SQL Injection DDOS: Sql sentences are used to flood the server.
- HTTP Flood: attacker overwhelm the server using HTTP GET/POST methods.
- Normal transaction data.