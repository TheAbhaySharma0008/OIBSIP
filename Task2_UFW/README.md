# Task 2: Basic Firewall Configuration with UFW

## Objective
Configure a basic firewall using UFW (Uncomplicated Firewall) on Kali Linux.

## Tools Used
- Kali Linux
- UFW (Uncomplicated Firewall)

## Commands Executed

```bash
sudo apt install ufw
sudo ufw status
sudo ufw allow ssh
sudo ufw deny http
sudo ufw enable
sudo ufw status verbose
```

## Firewall Rules

- Allowed SSH (Port 22)
- Denied HTTP (Port 80)
- Firewall enabled successfully

## Verification

The firewall configuration was verified using:

```bash
sudo ufw status verbose
```

The output confirmed that:
- Firewall is active.
- SSH traffic is allowed.
- HTTP traffic is denied.

## Conclusion

Successfully configured a basic firewall using UFW and verified the active rules.
