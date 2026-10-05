# Task 1 — Identify Constraints

## Automated Railway Level-Crossing Control System

The following constraints define rules that the Automated Railway Level-Crossing Control System must always satisfy.

---

### C1 — Barrier Must Not Open While Train Is Present

**Constraint:**  
The barrier must not open while a train is present at the crossing.

**Reason:**  
Opening the barrier could allow road traffic to enter the crossing while the train is passing.

---

### C2 — Barrier Must Close When Train Approaches

**Constraint:**  
The barrier must close when an approaching train is detected.

**Reason:**  
It prevents road traffic from entering the crossing before the train arrives.

---

### C3 — Warning Signals Must Activate

**Constraint:**  
Warning lights and audible alarms must be activated when a train approaches.

**Reason:**  
Warnings alert drivers and pedestrians that a train is approaching.

---

### C4 — Barrier Must Remain Closed While Train Is Passing

**Constraint:**  
The barrier must remain closed while the train is passing through the crossing.

**Reason:**  
Opening the barrier during train passage can cause a collision.

---

### C5 — Barrier Can Open Only After Train Clears

**Constraint:**  
The barrier must open only after the system confirms that the train has completely cleared the crossing.

**Reason:**  
It ensures that road traffic does not enter while any part of the train is still in the crossing.

---

### C6 — Sensor Failure Must Not Cause Unsafe Opening

**Constraint:**  
A sensor failure must not cause the barrier to open when the train status is unknown.

**Reason:**  
Unknown train status must be handled safely to prevent accidents.

---

### C7 — Barrier Failure Must Be Detected

**Constraint:**  
The system must detect when the barrier fails to close or open correctly.

**Reason:**  
A failed barrier can create a dangerous situation for road traffic and trains.

---

### C8 — Communication Loss Must Be Handled Safely

**Constraint:**  
The system must enter a safe state when communication with the control center is lost.

**Reason:**  
Loss of communication should not cause unsafe crossing operation.

---

### C9 — Incorrect Sensor Readings Must Not Open Barrier

**Constraint:**  
Incorrect or inconsistent sensor readings must not cause the barrier to open.

**Reason:**  
False sensor information could incorrectly indicate that the train has cleared the crossing.

---

### C10 — Emergency Condition Must Activate Safety Response

**Constraint:**  
When an emergency condition occurs, the system must activate the appropriate safety response.

**Reason:**  
Emergency conditions require immediate action to protect trains, drivers, and pedestrians.
