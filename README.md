# Linux-static-binaries
Linux static binaries to work on 32&amp;64 systems.  
There is mainly Nmap and Gobuster and some other extra tools.
## Impotant Note:
some tools and files aren't mine , it was collected from:
https://github.com/fopina/gobuster  
https://github.com/ernw/static-toolbox  


# **install:**
```
sudo wget https://github.com/AsimCr/Linux-static-binaries/raw/main/Binaries.zip
sudo unzip Binaries.zip
```

# **Usage:**
## Nmap
```
./run-nmap.sh 10.10.10.10
```
## Gobuster
```
./gobuster dir -w big.txt -u http://10.10.10.10/ -t 50 -x php,txt,log,asp -r
```
