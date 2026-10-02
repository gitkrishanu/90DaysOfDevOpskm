# Day04

### Process checks

1. `ps` - Display all running processes

    <img width="991" height="300" alt="image" src="https://github.com/user-attachments/assets/f3f4614a-e355-4e68-8f92-be9f6d30639a" />


2. `htop` - Interactive process viewer

    <img width="630" height="354" alt="image" src="https://github.com/user-attachments/assets/059999a2-2b66-4939-b6c6-6a7aa7e67777" />


3. `pgrep` - find process with and return pid

    <img width="617" height="87" alt="image" src="https://github.com/user-attachments/assets/1c218e66-8912-4296-a3ce-3da733efb3c0" />


---

### Service checks

1. `systemctl` - check status of process `sshd`

    <img width="968" height="372" alt="image" src="https://github.com/user-attachments/assets/7ac8ba40-3538-498e-ab29-b82ff08f575e" />


2. `sytemctl --type=services --state=inactive` - list all inactive services

    <img width="984" height="283" alt="image" src="https://github.com/user-attachments/assets/dfa5aee2-f4f1-4c54-9aba-13e3df2993fe" />


3. `systemstl -is-enabled sshd` - to check service is enabled to start on boot

    <img width="505" height="88" alt="image" src="https://github.com/user-attachments/assets/a155d469-886c-447b-8b4d-bd56052dcfab" />


---

### Log checks

1. `journalctl -u sshd -n 4` - view recent 4 ssh logs

    <img width="992" height="151" alt="image" src="https://github.com/user-attachments/assets/0afedb50-930e-41c7-a0bc-97f68d7f63c4" />


2. `journalctl -n +10` - display oldest 10 logs if `+` removed then recent 10 logs

    <img width="995" height="332" alt="image" src="https://github.com/user-attachments/assets/64aea1a1-e2ee-4edd-aa12-3b02367043e6" />



