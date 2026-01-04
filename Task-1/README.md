# Bandit

## Levels 0-5

### Level 0

**Commands Used**

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
bandit0
```

**Commands Used**

```bash
ls
```

**Output**

```bash
readme
```

**Commands Used**

```bash
cat readme
```

**Output**

```bash
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

### Level 1

**Commands Used**

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

**Commands Used**

```bash
ls
```

**Output**

```bash
-
```

**Commands Used**

```bash
cat ./-
```

**Output**

```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

### Level 2

**Commands Used**

```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

**Commands Used**

```bash
ls
```

**Output**

```bash
--spaces in this filename--
```

**Commands Used**

```bash
cat ./--spaces\ in\ this\ filename--
```

**Output**

```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

### Level 3

**Commands Used**

```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

**Commands Used**

```bash
ls
```

**Output**

```bash
inhere
```

**Commands Used**

```bash
cd inhere
ls -a
```

**Output**

```bash
.  ..  ...Hiding-From-You
```

**Commands Used**

```bash
cat ./...Hiding-From-You
```

**Output**

```bash
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

### Level 4

**Commands Used**

```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

**Commands Used**

```bash
ls
```

**Output**

```bash
inhere
```

**Commands Used**

```bash
cd inhere
ls -a
```

**Output**

```bash
.  ..  -file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09
```

**Commands Used**

```bash
file ./*
```

**Output**

```bash
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
```

**Commands Used**

```bash
cat ./-file07
```

**Output**

```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```

### Level 5

**Commands Used**

```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```

**Commands Used**

```bash
ls
```

**Output**

```bash
inhere
```

**Commands Used**

```bash
cd inhere
ls -a
```

**Output**

```bash
.            maybehere01  maybehere04  maybehere07  maybehere10  maybehere13  maybehere16  maybehere19
..           maybehere02  maybehere05  maybehere08  maybehere11  maybehere14  maybehere17
maybehere00  maybehere03  maybehere06  maybehere09  maybehere12  maybehere15  maybehere18
```

**Commands Used**

```bash
find . -type f -size 1033c -readable ! -executable
```

**Output**

```bash
./maybehere07/.file2
```

**Commands Used**

```bash
cd maybehere07
cat ./.file2
```

**Output**

```bash
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```

# CIA

<p>
CIA is the abbreviation for Confidentiality, Integrity and Availability; three pillars of effective IT security system which helps in protecting data and securing information in organisations.
<br>
<br>
1)	Confidentiality:
It ensures that data is private and is accessible to authorised personnel only.
•	Sensitive info(passwords, personal data) is kept secret.
<br>
•	Encryption, authentication, VPNs can be used to enhance confidentiality.
<br>
2)	Integrity:
<br>
It ensures that data is authentic, accurate and unaltered.
<br>
•	Prevents unauthorised modifications and builds trust.
<br>
•	Methods like hashing, digital signatures and version controls.
<br>
3)	Availability:
<br>
Availability ensures that systems, networks, and data are accessible to authorized users whenever needed.
<br>
•	Business continuity.
<br>
•	Regular maintenance, updates and backups.
<br>
<br>
Relationship between CIA components:-
<br>
All the components are important, improving one affects the other. So, one must make sure that all the three are balanced properly.
