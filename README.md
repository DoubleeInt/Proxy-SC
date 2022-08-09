# 💣Proxy-SC!💣

------

![image](https://user-images.githubusercontent.com/110692792/183766708-bb80a539-0578-45e8-845b-f8c7e560e5a7.png)

## 👁️‍🗨️Proxy scraper & checker👁️‍🗨️

------

This is a fairly simple script that collects proxies from different sources and checks them for validity.

This script can work with HTTP, SOCKS4, SOCKS5 proxies.

```
- Asynchronous.
- Uses regex to search for proxies (ip:port format) on a web page, which allows you to pull out proxies even from json without making any changes to the code.
- Supports determining the geolocation of the proxy exit node.
- Can determine if a proxy is anonymous.
```


### 🧐Usage🧐

------

- Install [Python](https://python.org/downloads). During installation, be sure to check the box `Add Python to PATH`.
- Download and unpack [the archive with the `program`](https://github.com/DoubleeInt/Proxy-SC/archive/refs/heads/main.zip).
- Install dependencies from `requirements.txt`
  `python -m pip install -U -r requirements.txt` 
- Run `main.py` (`python main.py` on the command line).
- Wait untill script finish.

### 📁Folders📁

------

Script creates 4 folders:

- `proxies`
- `proxies_anonymous`
- `proxies_geolocation`
- `proxies_geolocation_anonymos`

### ⭐Have a good day⭐
