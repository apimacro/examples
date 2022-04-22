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
./install.sh
```

Update works such git pull for bash repo: https://github.com/apimacro/bash.git
```bash
./update.sh
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

## Example no 1

Example with url and command: http_status_code
executed in path: '/bash/apimacro/http_status_code.sh' 
through script: ./apimacro 

1/in.csv
```csv
url,                    http_status_code
https://softreck.com
https://softreck.pl
https://sapletta.com
https://sapletta.pl
```


After running macro for project no: 1
will be generated 1/out.csv file with outputs data
```bash
./apimacro 1
```


Generated output data through running script: http_status_code.sh with each data record: url
in second column are result of bash script: http_status_code

1/out.csv
```csv
url,                    http_status_code
https://softreck.com,   200
https://softreck.pl,    200
https://sapletta.com,   200
https://sapletta.pl,    200
```


## Example no 2

Example with url and command: http_status_code
executed in path: '/bash/apimacro/http_status_code.sh'
through script: ./apimacro

1/in.csv
```csv
url,                    http_status_code
https://softreck.com
https://softreck.pl
https://sapletta.com
https://sapletta.pl
```


After running macro for project no: 1
will be generated 1/out.csv file with outputs data
```bash
./apimacro 1
```


Generated output data through running script: http_status_code.sh with each data record: url
in second column are result of bash script: http_status_code

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
