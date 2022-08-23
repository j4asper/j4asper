```python
import pytz, requests
from datetime import datetime

class Jasper:
    def __init__(self):
        self.age = 19
        self.birthday = datetime(year=2003, month=1, day=19) # 19th of January
        self.location = "Odense 5000, Denmark" # 🇩🇰
        self.timezone = pytz.timezone('Europe/Copenhagen')
        self.company = 'JC-Integrations'
        self.personal_site = 'https://jazper.dk'
        self.email = 'jasper@jazper.dk'
        self.hours_spent_on_this_readme_file = 2 # Worth it

github_user = Jasper()

print(f'Hi! I am {github_user.name}, i am {github_user.age} years old and based in {github_user.location}')
```

**E-Mail:**  
<a href="mailto:jasper@jazper.dk"><img src="https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white"></a>

**HomeLab:**  
<a href=""><img src="https://img.shields.io/badge/HomeLab-FFA500?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNTIgNTIiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDUyIDUyOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8cmVjdCB4PSIzIiB5PSI0NiIgc3R5bGU9ImZpbGw6IzgzOTU5NDsiIHdpZHRoPSI2IiBoZWlnaHQ9IjIiLz4NCjxyZWN0IHg9IjQzIiB5PSI0NiIgc3R5bGU9ImZpbGw6IzgzOTU5NDsiIHdpZHRoPSI2IiBoZWlnaHQ9IjIiLz4NCjxyZWN0IHk9IjMyIiBzdHlsZT0iZmlsbDojMjgzMjM4OyIgd2lkdGg9IjUyIiBoZWlnaHQ9IjE0Ii8+DQo8Y2lyY2xlIHN0eWxlPSJmaWxsOiNFN0VDRUQ7IiBjeD0iOCIgY3k9IjM5IiByPSIzIi8+DQo8Zz4NCgk8cGF0aCBzdHlsZT0iZmlsbDojMzg0NTRGOyIgZD0iTTQ3LDM1Yy0wLjU1MywwLTEsMC40NDctMSwxdjZjMCwwLjU1MywwLjQ0NywxLDEsMXMxLTAuNDQ3LDEtMXYtNkM0OCwzNS40NDcsNDcuNTUzLDM1LDQ3LDM1eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNNDMsMzVjLTAuNTUzLDAtMSwwLjQ0Ny0xLDF2NmMwLDAuNTUzLDAuNDQ3LDEsMSwxczEtMC40NDcsMS0xdi02QzQ0LDM1LjQ0Nyw0My41NTMsMzUsNDMsMzV6Ii8+DQoJPHBhdGggc3R5bGU9ImZpbGw6IzM4NDU0RjsiIGQ9Ik0zOSwzNWMtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTF2LTZDNDAsMzUuNDQ3LDM5LjU1MywzNSwzOSwzNXoiLz4NCgk8cGF0aCBzdHlsZT0iZmlsbDojMzg0NTRGOyIgZD0iTTM1LDM1Yy0wLjU1MywwLTEsMC40NDctMSwxdjZjMCwwLjU1MywwLjQ0NywxLDEsMXMxLTAuNDQ3LDEtMXYtNkMzNiwzNS40NDcsMzUuNTUzLDM1LDM1LDM1eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNMzEsMzVjLTAuNTUzLDAtMSwwLjQ0Ny0xLDF2NmMwLDAuNTUzLDAuNDQ3LDEsMSwxczEtMC40NDcsMS0xdi02QzMyLDM1LjQ0NywzMS41NTMsMzUsMzEsMzV6Ii8+DQoJPHBhdGggc3R5bGU9ImZpbGw6IzM4NDU0RjsiIGQ9Ik0yNywzNWMtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTF2LTZDMjgsMzUuNDQ3LDI3LjU1MywzNSwyNywzNXoiLz4NCjwvZz4NCjxyZWN0IHk9IjE4IiBzdHlsZT0iZmlsbDojMzg0NTRGOyIgd2lkdGg9IjUyIiBoZWlnaHQ9IjE0Ii8+DQo8Y2lyY2xlIHN0eWxlPSJmaWxsOiNFN0VDRUQ7IiBjeD0iOCIgY3k9IjI1IiByPSIzIi8+DQo8Zz4NCgk8cGF0aCBzdHlsZT0iZmlsbDojMjgzMjM4OyIgZD0iTTQ3LDIxYy0wLjU1MywwLTEsMC40NDctMSwxdjZjMCwwLjU1MywwLjQ0NywxLDEsMXMxLTAuNDQ3LDEtMXYtNkM0OCwyMS40NDcsNDcuNTUzLDIxLDQ3LDIxeiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMyODMyMzg7IiBkPSJNNDMsMjFjLTAuNTUzLDAtMSwwLjQ0Ny0xLDF2NmMwLDAuNTUzLDAuNDQ3LDEsMSwxczEtMC40NDcsMS0xdi02QzQ0LDIxLjQ0Nyw0My41NTMsMjEsNDMsMjF6Ii8+DQoJPHBhdGggc3R5bGU9ImZpbGw6IzI4MzIzODsiIGQ9Ik0zOSwyMWMtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTF2LTZDNDAsMjEuNDQ3LDM5LjU1MywyMSwzOSwyMXoiLz4NCgk8cGF0aCBzdHlsZT0iZmlsbDojMjgzMjM4OyIgZD0iTTM1LDIxYy0wLjU1MywwLTEsMC40NDctMSwxdjZjMCwwLjU1MywwLjQ0NywxLDEsMXMxLTAuNDQ3LDEtMXYtNkMzNiwyMS40NDcsMzUuNTUzLDIxLDM1LDIxeiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMyODMyMzg7IiBkPSJNMzEsMjFjLTAuNTUzLDAtMSwwLjQ0Ny0xLDF2NmMwLDAuNTUzLDAuNDQ3LDEsMSwxczEtMC40NDcsMS0xdi02QzMyLDIxLjQ0NywzMS41NTMsMjEsMzEsMjF6Ii8+DQoJPHBhdGggc3R5bGU9ImZpbGw6IzI4MzIzODsiIGQ9Ik0yNywyMWMtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTF2LTZDMjgsMjEuNDQ3LDI3LjU1MywyMSwyNywyMXoiLz4NCjwvZz4NCjxyZWN0IHk9IjQiIHN0eWxlPSJmaWxsOiMyODMyMzg7IiB3aWR0aD0iNTIiIGhlaWdodD0iMTQiLz4NCjxjaXJjbGUgc3R5bGU9ImZpbGw6I0U3RUNFRDsiIGN4PSI4IiBjeT0iMTEiIHI9IjMiLz4NCjxnPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNNDcsN2MtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTFWOEM0OCw3LjQ0Nyw0Ny41NTMsNyw0Nyw3eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNNDMsN2MtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTFWOEM0NCw3LjQ0Nyw0My41NTMsNyw0Myw3eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNMzksN2MtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTFWOEM0MCw3LjQ0NywzOS41NTMsNywzOSw3eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNMzUsN2MtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTFWOEMzNiw3LjQ0NywzNS41NTMsNywzNSw3eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNMzEsN2MtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTFWOEMzMiw3LjQ0NywzMS41NTMsNywzMSw3eiIvPg0KCTxwYXRoIHN0eWxlPSJmaWxsOiMzODQ1NEY7IiBkPSJNMjcsN2MtMC41NTMsMC0xLDAuNDQ3LTEsMXY2YzAsMC41NTMsMC40NDcsMSwxLDFzMS0wLjQ0NywxLTFWOEMyOCw3LjQ0NywyNy41NTMsNywyNyw3eiIvPg0KPC9nPg0KPGNpcmNsZSBzdHlsZT0iZmlsbDojMjFDNkY3OyIgY3g9IjE1IiBjeT0iMzkiIHI9IjIiLz4NCjxjaXJjbGUgc3R5bGU9ImZpbGw6IzIxQzZGNzsiIGN4PSIxNSIgY3k9IjI1IiByPSIyIi8+DQo8Y2lyY2xlIHN0eWxlPSJmaWxsOiM4MUVBMUM7IiBjeD0iMTUiIGN5PSIxMSIgcj0iMiIvPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPC9zdmc+DQo="></a>

<details close>
<summary>Show more stuff</summary>

## Socials
<details close>
<summary>Show</summary>

<a href="https://www.reddit.com/user/j4asper"><img src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white"></a>
<a href="https://www.snapchat.com/add/j4azper"><img src="https://img.shields.io/badge/Snapchat-FFFC00?style=for-the-badge&logo=snapchat&logoColor=white"></a>
<a href="https://twitter.com/Jazper1901"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"></a>
<a href="https://www.linkedin.com/in/jasper-christiansen-5611a9224/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://www.kaggle.com/jazper"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"></a>
<a href="https://steamcommunity.com/id/Jasper1901/"><img src="https://img.shields.io/badge/Steam-000000?style=for-the-badge&logo=steam&logoColor=white"></a>
<a href="https://discord.com/users/282660538356596736"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>

</details>

## Computer
<details close>
<summary>Show</summary>

```console
jasper@Jasper-PC:~$ neofetch
        `osssssssssssssssssssso`           jasper@Jasper-PC 
       .osssssssssssssssssssssso.          ---------------- 
      .+oooooooooooooooooooooooo+.         OS: Zorin OS 16.1 x86_64 
                                           Kernel: 5.15.0-41-generic 
                                           Uptime: 6 hours, 9 mins 
  `::::::::::::::::::::::.         .:`     Packages: 2595 (dpkg), 37 (flatpak), 
 `+ssssssssssssssssss+:.`     `.:+ssso`    Shell: bash 5.0.17 
.ossssssssssssssso/.       `-+ossssssso.   Resolution: 1920x1080, 1920x1080 
ssssssssssssso/-`      `-/osssssssssssss   DE: GNOME 
.ossssssso/-`      .-/ossssssssssssssso.   WM: Mutter 
 `+sss+:.      `.:+ssssssssssssssssss+`    WM Theme: ZorinGrey-Dark 
  `:.         .::::::::::::::::::::::`     Theme: ZorinGrey-Dark [GTK2/3] 
                                           Icons: ZorinGrey-Dark [GTK2/3] 
                                           Terminal: gnome-terminal 
      .+oooooooooooooooooooooooo+.         CPU: AMD Ryzen 5 1400 (8) @ 3.800GHz 
       -osssssssssssssssssssssso-          GPU: AMD RX 6600 
        `osssssssssssssssssssso`           Memory: 5403MiB / 32017MiB 
```

<a href="https://zorin.com/os/"><img src="https://img.shields.io/badge/Zorin%20OS-0CC1F3?style=for-the-badge&logo=zorin&logoColor=white"></a>
<a href="https://www.amd.com/en/products/cpu/amd-ryzen-5-1400"><img src="https://img.shields.io/badge/AMD-Ryzen_5_1400-ED1C24?style=for-the-badge&logo=amd&logoColor=white"></a>
<a href="https://www.sapphiretech.com/en/consumer/pulse-radeon-rx-6600-8g-gddr6"><img src="https://img.shields.io/badge/AMD-Radeon_RX_6600-ED1C24?style=for-the-badge&logo=amd&logoColor=white"></a>
<a href="https://www.mozilla.org/da/firefox/new/"><img src="https://img.shields.io/badge/Firefox_Browser-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white"></a>
<a href="https://code.visualstudio.com/"><img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"></a>

</details>


## Tools I've used
<details close>
<summary>Show</summary>

### Programming Languages:  

<a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
<a href="https://docs.microsoft.com/en-us/dotnet/"><img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"></a>
<a href="https://dart.dev/"><img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"></a>
<a href="https://www.javascript.com/"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"></a>

### Databases:

<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi9o5DsrJf5AhV1VvEDHdUkApgQFnoECBIQAQ&url=https%3A%2F%2Fmariadb.org%2F&usg=AOvVaw10264uJfiT1f86dmQ3wPSz"><img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"></a>
<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjN_u_xrJf5AhX9XvEDHbDSC1QQFnoECBQQAQ&url=https%3A%2F%2Fwww.mysql.com%2F&usg=AOvVaw20c6IrMAtNC1A9NZPsDpWW"><img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"></a>
<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjB8eD4rJf5AhVDQvEDHQ16BrEQFnoECBIQAQ&url=https%3A%2F%2Fwww.sqlite.org%2F&usg=AOvVaw2FGx1kWp6WBAJWy5IhYh3r"><img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white"></a>
<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiKlvr8rJf5AhUtYPEDHZ0XA-MQFnoECA8QAQ&url=https%3A%2F%2Fredis.io%2F&usg=AOvVaw0SPzotNaWJKDkbJZ8FW9ft"><img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white"></a>

## Web:

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white">
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/fastapi-109989?style=for-the-badge&logo=FASTAPI&logoColor=white">

### Other Technologies:

<a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-119EFF?style=for-the-badge&logo=Docker&logoColor=white"></a>
<a href="https://www.twilio.com/"><img src="https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white"></a>
<a href="https://nextcloud.com/"><img src="https://img.shields.io/badge/Nextcloud-0082C9?style=for-the-badge&logo=Nextcloud&logoColor=white"></a>
<a href="https://github.com"><img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"></a>
<a href="https://www.cloudflare.com/"><img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white"></a>
<a href="https://analytics.google.com"><img src="https://img.shields.io/badge/Google%20Analytics-E37400?style=for-the-badge&logo=google%20analytics&logoColor=white"></a>
<a href="https://metrics.torproject.org/rs.html#details/0E0ED80D042D31C98EE24ECFAD89DA333FA4C3EB"><img src="https://img.shields.io/badge/TorProject-7D4698?style=for-the-badge&logo=torproject&logoColor=white"></a>
<img src="https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white">
<img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white">
<img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white">
<img src="https://img.shields.io/badge/VirtualBox-21416b?style=for-the-badge&logo=VirtualBox&logoColor=white">


<img src="https://github-readme-stats.vercel.app/api?username=j4asper&theme=blue-green">

</details>

<a href="https://www.buymeacoffee.com/jazper" target="_blank"><img src="https://img.buymeacoffee.com/api/?url=aHR0cHM6Ly9jZG4uYnV5bWVhY29mZmVlLmNvbS91cGxvYWRzL3Byb2ZpbGVfcGljdHVyZXMvMjAyMi8wOC9JNUc0QnN4OTJLWVE5NkVLLnBuZ0AzMDB3XzBlLndlYnA=&creator=Jasper+O.+C.&design_code=1&design_color=%2326B0A1&slug=jazper" width="400" height="auto"></a>

</details>

