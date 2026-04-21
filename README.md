<h1>Firewall traffic simulation</h1>
<h2>Description</h2>
This homelab project simulates a basic firewall system using Python. It generates random internal IP traffic and evaluates each request against a predefined set of firewall rules.

The program classifies traffic as either allowed or blocked, demonstrating how rule-based filtering works in real-world network security environments.
<br />

<h2>Lab breakdown:</h2>
1. Traffic Generation
- <b>Created a function to generate random IP addresses within the internal network range</b>
- <b>Each execution simulated 12 connection attempts</b>

2. Rule Evaluation
- <b>Implemented a function to compare each generated IP address against predefined firewall rules</b>
- <b>If a match was found → connection was blocked</b>
- <b>If no match was found → connection was allowed</b>

3. Simulation Execution
- <b>Ran the simulation loop to process multiple traffic events</b>
- <b>Generated a random identifier for each event to mimic unique network activity</b>
- <b>Output displayed:</b>
  - IP Address
  - Action taken (Allow/Block)
  - Random event ID
 
<h2>Pictures:</h2>
<img src="[https://github.com/AndreeSalvo/Firewall-traffic-simulation/blob/5e41c709934f8bc71646b9a695c56c7f7c4c33c5/Firewall%20code.jpg]"/>
