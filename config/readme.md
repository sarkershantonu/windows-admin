# configuration and administration 

### Expoert all variable to a file 
- run in CMD  ``` SET >> env.txt```

### Import environment veriables from a file 
- run in CMD ```for /F %A in (env.txt) do SET %A```
