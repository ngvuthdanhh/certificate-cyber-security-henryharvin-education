# Demo Lab 03 – Password Cracking with Hydra

## Objective
Use Hydra to brute force weak SSH credentials.

## Steps
1. Prepare wordlist (e.g., `rockyou.txt`)  
2. Run Hydra:  
   ```bash
   hydra -l admin -P /usr/share/wordlists/rockyou.txt ssh://192.168.1.20

3. Monitor attempts and capture successful login

## Expected Outcome

- Discovery of weak password

- Emphasis on enforcing strong password policies
