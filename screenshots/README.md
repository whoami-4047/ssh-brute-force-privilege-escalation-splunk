## Screenshots

### 1. Multiple Failed SSH Login Attempts

This search identifies repeated failed SSH login attempts, indicating a possible brute-force attack.

![Multiple Failed SSH Login Attempts](screenshots/01_failed_ssh_login.png)

---

### 2. Successful SSH Authentication

This event confirms that the attacker successfully authenticated after multiple failed login attempts.

![Successful SSH Authentication](screenshots/02_successful_login.png)

---

### 3. Privilege Escalation

Shows execution of commands with **UID=0**, confirming successful privilege escalation.

![Privilege Escalation](screenshots/03_privilege_escalation.png)

---

### 4. Access to `/etc/shadow`

Demonstrates access to the sensitive `/etc/shadow` file, indicating potential credential compromise.

![Shadow Access](screenshots/04_shadow_access.png)

---

### 5. Attack Timeline

Visualization of the attack progression from initial compromise to privilege escalation.

![Attack Timeline](screenshots/05_attack_timeline.png)

---

### 6. Command Statistics

Statistical summary of executed commands collected from the monitored host.

![Command Statistics](screenshots/06_command_statistics.png)

---

### 7. Brute Force Detection Rule

Splunk detection rule that triggers when multiple failed SSH login attempts are observed.

![Brute Force Detection Rule](screenshots/07_detection_rule.png)
