#### 
```
# File $fist: data extratc
sed 's/\([^:]*\).*/\1/' <File name>
# File :$secund data
sed 's/\([^:]*\)\(.*\)/\2/' /etc/passwd
```

```
# Json
jq '.asns[index]' | tr -d 'remove point' 


```