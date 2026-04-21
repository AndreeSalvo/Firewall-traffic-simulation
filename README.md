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
https://github.com/AndreeSalvo/Firewall-traffic-simulation/blob/0cc036522b3b28bd6642297fc1dda41e02cd9760/Firewall%20code.png
