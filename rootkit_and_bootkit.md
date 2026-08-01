# Bootkit vs Rootkit

## Bootkit

A **bootkit** is a type of malware that infects a computer's **boot loader** or **Master Boot Record (MBR)**, which is responsible for starting the operating system.

After infecting the computer, the bootkit executes malicious code **before the operating system loads**, allowing it to:

- Bypass security measures.
- Gain control of the system at the earliest stage of the boot process.
- Maintain persistence even before the OS and many security tools start.

---

## Rootkit

A **rootkit** is malware designed to **hide its presence and activities** from both the user and the operating system's security mechanisms.

Once installed, a rootkit can:

- Modify the operating system's core components.
- Conceal malicious files, processes, registry entries, or network connections.
- Help attackers maintain privileged, stealthy access to the system.

---

## Key Difference

- **Bootkit:** Attacks the **boot process**, executing **before** the operating system starts.
- **Rootkit:** Attacks the **operating system itself**, hiding malicious activity **after** the system has booted.
