# hashcrack

- **Name:** hashcrack
- **Difficulty:** easy

## Method

1. Open a terminal and connect to the challenge instance using `netcat` (`nc`).
2. You will see some hashes appear.
3. Copy each hash and upload it to a hash cracking site such as:
   - https://crackstation.net/
4. Crack the hash, then paste the recovered plaintext back into the terminal.
5. Repeat the process for each hash until the challenge finishes (usually it will reveal the flag).

## Notes

- Make sure you copy the hash exactly (no extra spaces or newlines).
- If a hash site doesn’t find it, try a different cracker or a local tool (e.g., Hashcat/John) with a larger wordlist.

