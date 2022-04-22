![3/cover.png](http://logo.apimacro.com/3/cover.png)

# [examples.apimacro.com](https://examples.apimacro.com/)

+ [www.apimacro.com](https://www.apimacro.com/)
+ [logo.apimacro.com](https://logo.apimacro.com/)
+ [docs.apimacro.com](https://examples.apimacro.com/)
+ [bash.apimacro.com](https://bash.apimacro.com/)


Examples of usage the apimacro's

## Install

Install from repo: https://github.com/apimacro/bash.git
```bash
./apimacro
```
Update works such git pull for bash repo: https://github.com/apimacro/bash.git
```bash
./apimacro
```

## Start using apiMacro 

List of projects
```bash
./apimacro
```

Run macro for 1/in.csv
```bash
./apimacro 1
```

The same, with separated details, run macro for 1/in.csv
```bash
./apimacro "1/in.csv" "1/out.csv" "1/status.csv"
```

## Projects

files structure
```
1
    in.csv
    out.csv
2
    in.csv
    out.csv
...        
```

## Example

Example with url and command: http_status_code
executed in '/bash/apimacro/http_status_code.sh' trough ./apimacro script

1/in.csv
```csv
url,                    http_status_code
https://softreck.com
https://softreck.pl
https://sapletta.com
https://sapletta.pl
```

generated file through checking each url from 1/in.csv

1/out.csv
```csv
url,                    http_status_code
https://softreck.com,   200
https://softreck.pl,    200
https://sapletta.com,   200
https://sapletta.pl,    200
```


---

+ [edit](https://github.com/apimacro/examples/edit/main/README.md)

+ [apimacro/examples](https://github.com/apimacro/examples)
