定长标记法：
```
print "\n".join(["n01"+ str(num).rjust(4,'0')+".jpg" for num in range(0, 10)])
```
