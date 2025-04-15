# Connect-the-network-devices-
Connect the network devices together according to the labels. Use the appropriate type of cable.
![image](https://github.com/user-attachments/assets/f3913930-1d39-4793-b57b-4c3f9e20067d)

🖥️ Topology Summary :
🔌 Connection Examples and Their Meaning:
R1 to R2 (50 meters) — FastEthernet — likely copper (straight-through or crossover depending on device type).

R1 to R3 (3 kilometers) — GigabitEthernet — use fiber optic cable due to the distance.

R3 to R4 (250 meters) — also Gigabit — again, fiber optic is appropriate.

Switches to Routers (within 100m) — copper Ethernet cables are fine.

📌 Device Roles:
Routers: R1, R2, R3, R4

Switches: SW1–SW8

PCs: PC1, PC2, PC3

Server: SRV1

🔧 Cable Type Tips (When Auto MDI-X is OFF):

Connection Type	Cable to Use
Router ↔ Switch	Straight-through
PC ↔ Switch	Straight-through
Switch ↔ Switch	Crossover
Router ↔ Router	Crossover
Gigabit over long distance (e.g., R1 ↔ R3)	Fiber
