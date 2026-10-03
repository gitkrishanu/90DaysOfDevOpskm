## Commands I have tried / practiced today

### Environment basics

1. `uname -a`
2. `lsb_release -a`
3. `cat /etc/os-release`

root@ubuntu-host ~ ➜  uname -a
Linux ubuntu-host 6.8.0-124-generic #124~22.04.1-Ubuntu SMP PREEMPT_DYNAMIC Tue May 26 21:05:19 UTC  x86_64 x86_64 x86_64 GNU/Linux
<img width="1694" height="836" alt="image" src="https://github.com/user-attachments/assets/ee33140b-4ec7-498c-b91d-c117a7dd1209" />



### Filesystem sanity

1. `mkdir /tmp/runbook-demo`
2. `cp /etc/hosts /tmp/runbook-demo && ls -l /tmp/runbook-demo/`

<img width="834" height="139" alt="image" src="https://github.com/user-attachments/assets/017bb3db-c584-4204-9718-38e5f74a4c7f" />


### CPU & memory

1. `pgrep ssh`
2. `ps -o pid,pcpu,pmem,comm -p 2289 2291`
3. `free -h`

<img width="831" height="234" alt="image" src="https://github.com/user-attachments/assets/acbd699b-c28c-4d2d-9cbf-b06ce5214f4d" />


### Disk & IO

1. `df -h`
2. `sudo du -sh /var/log`

<img width="805" height="359" alt="image" src="https://github.com/user-attachments/assets/fa4caa63-58f2-432c-8d3c-a0d6a7c16870" />

<img width="984" height="220" alt="image" src="https://github.com/user-attachments/assets/26d002f0-adbb-4541-a441-96d42cf69f20" />

### Network

1. `ss -tulpn`
2. `ping -c 3 google.com`

<img width="1430" height="304" alt="image" src="https://github.com/user-attachments/assets/25b7b0b2-4727-44c8-9121-66ba4ddfbb89" />



### LOGS

1. `journalctl -u NetworkManager -n 10`
2. `tail -n 10 /var/log/auth.log`

<img width="1440" height="353" alt="image" src="https://github.com/user-attachments/assets/79a24919-2f04-40c5-85c7-855fee24fb9e" />
