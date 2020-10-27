# 1. installation

## 1.1 Windows

### 1.1.1 download

- [R package && R tools](https://mirrors.tuna.tsinghua.edu.cn/CRAN/)

- [R studio](https://www.rstudio.com/ide/download/desktop)

### 1.1.2 configuration

add `C:\Program Files\R\R-4.0.3` to **system environment path**

### 1.1.3

 ```
 writeLines('PATH="${RTOOLS40_HOME}\\usr\\bin;${PATH}"', con = "~/.Renviron")
 Sys.which("make")
 ## "C:\\rtools40\\usr\\bin\\make.exe"
 install.packages("rms", type = "source")
 ```
## 1.2 Conda

```
conda activate env
conda install -c r r-base
R
 install.packages("rms")
```

