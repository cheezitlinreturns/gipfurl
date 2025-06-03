Gipfurl is a command line tool for getting the IP(s) of website(s).

# INSTALLATION
- 1:
Run this command:

```
git clone https://github.com/cheezitlinreturns/gipfurl.git
```
```
cd gipfurl
```
- 2:
Run **instgipfurl.sh** as root.
```
sudo ./instgipfurl.sh
```
Let it install.

# Using Gipfurl

- 1:
To get the IP of one website, run this:
```
gipfurl https://example.com
```
Replace https://example.com with the actual website(s) you want to get the IP(s) of.
The output i got was:
```
https://example.com -> 23.192.228.80
```

You can do multiple websites at once.
```
gipfurl https://example.com https://chatgpt.com https://youtube.com
```
The output i got was:
```
https://example.com -> 23.192.228.80
https://chatgpt.com -> 172.64.155.209
https://youtube.com -> 64.233.185.91
```
