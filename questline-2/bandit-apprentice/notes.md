# Bandit Apprentice Notes

## Level 0
Task: Read the password from a file named `readme`.
Command: cat readme
Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

---

## Level 1
Task: Read the content of a file named `-`.
Command: cat ./-
Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

---

## Level 2
Task: Read a file with spaces in the filename.
Command: cat ./--spaces\ in\ this\ filename--
Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

---

## Level 3
Task: Navigate into `inhere/` and find the hidden file.
Command: cd inhere
cat ./...Hiding-From-You
Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

---

## Level 4
Task: Find the only human-readable file in `inhere/`.
Command: cd inhere
file ./*
cat ./-file07
Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

---

## Level 5
Task: Find a 1033-byte, non-executable file.
Command: cd inhere
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

---

## Level 6
Task: Search the entire system for a file owned by user `bandit7` and group `bandit6`, and exactly 33 bytes in size.
Command: find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

---

## Level 7
Task: Find the line containing the word `millionth` in `data.txt`.
Command:used vim and used its inbuilt search tool to find the password near the word millionth
Password: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc 

---

## Level 8
Task: Find the line in `data.txt` that occurs only once.
Command: sort data.txt | uniq -u
Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

---

## Level 9
Task: Find a human-readable string in `data.txt` that follows a line of `=` characters.
Command: used vim and used its inbuilt search tool to find the password near nultiple = chars.
Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

---

## Level 10
Task: Decode a base64-encoded string in `data.txt`.
Command: cat data.txt | base64 -d
Output: The password is dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

