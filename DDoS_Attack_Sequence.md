```mermaid
sequenceDiagram
actor Hacker
Hacker->>Botnet Zombie: Destroy Website
Botnet Zombie->>Hacker: DONE!
Botnet Zombie->Webpage: Flooding system with high traffic
participant Webpage
Webpage<<->>Firewall: System has been overloaded
box Red 
    participant Firewall
    end
participant Firewall
Firewall-->Webpage: Applying Anti DDOS software like Cloudfare or Data Dome
```
