# Port-Scanner
A Port Scanner is a classic "rite of passage" project for anyone entering the cybersecurity field. It’s essentially a digital door-knocker: a tool designed to probe a server or host for open ports.

What is it?
In networking, "ports" are communication endpoints. A port scanner sends requests to specific ports on a target IP address and analyzes the responses to determine their status:
  Open: The service is listening (e.g., a web server on port 80).
  Closed: No service is active on that port.
  Filtered: A firewall is blocking the request.

The Basic Workflow
  Input: Define a target (IP or URL) and a range of ports (e.g., 1–1024).
  Attempt Connection: Try to establish a connection to each port.
  Handle Results: If the connection succeeds, mark the port as "Open."
  Output: Display a clean list of findings to the user.
