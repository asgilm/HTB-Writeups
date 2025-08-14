# 🧪 Writeup: [Module or Assessment]

---

### 🧠 Objective

[Describe brevemente el propósito principal del laboratorio. Ejemplo:]

Get familiar with the Pwnbox lab environment and practice basic network commands on a Linux system.

---

### 🛠️ Tools and Commands Used

- **Pwnbox (Parrot OS)** – Cloud-based working environment.
- **ip / ifconfig** – View network interfaces.
- **ping** – Check connectivity.
- **traceroute** – Trace routes to external domains.

```bash
# Example commands run
ip a
ping 10.10.10.1
traceroute hackthebox.com
```
> Output showed active interface `tun0`, which connects to HTB’s VPN network

Use the `ping` comand.

---

### 🔍 Steps

1. Launching the Pwnbox environment
    - Accessed the Parrot OS terminal through the browser.
    - Set full screen for better visibility.

2. Enumerating network interfaces
    - Command used: ip a
    - Noticed the tun0 interface was active, indicating connection to HTB’s VPN environment

---

### 📌 Key Learning Points

- Understood the role of the tun0 interface in the HTB VPN environment
- Practiced using basic Linux networking tools.

---

### Troubleshooting

- The `ifconfig` command was not installed. Used `ip a` as alternative.

---

### Further Research

- Difference between ip a and ifconfig.
