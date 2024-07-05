<div align="center">
  <h1 align="center">Hi, Thank You For Visiting My Github Profile!</h1>
  <img src="https://media.giphy.com/media/XKSPsk67cnCw0/giphy.gif" alt="Battle Programmer Shirase Pc GIF" width="300" height="200"/>
  <img src="https://media.giphy.com/media/3Q2hJ4FLN1UvS/giphy.gif" alt="Work Computer GIF" width="300" height="200"/><br>
  <a href="https://www.codewars.com/users/wahyu-priambodo"><img src="https://www.codewars.com/users/wahyu-priambodo/badges/micro" alt="CodeWars"/></a>
  <a href="https://codeforces.com/profile/wahoyuz"><img src="https://img.shields.io/badge/wahoyuz-445f9d?&logo=Codeforces&logoColor=white" alt="CodeForces"/></a>
</div>

<h2>About Me</h2>

```python
# who_am_i.py
import json
import base64

class WhoAmI:
  def __init__(self, name, age, pronouns, country, current_job, interest, hobby, tech_stacks):
    self.name = name
    self.age = age
    self.pronouns = pronouns
    self.country = country
    self.current_job = current_job
    self.interest = interest
    self.hobby = hobby
    self.tech_stacks = tech_stacks

  def __secret_life(self):
    x = "V2F0Y2hpbmcgYW4gYW5pbWUgOnY=".encode('ascii')
    y = base64.b64decode(x).decode('ascii')
    return y

  def Introduction(self):
    print(f"👋 Hi, my name is {self.name} and I'm now {self.age} yo.")
    print(f"👦 My pronouns is {self.pronouns}.")
    print(f"🇮🇩 My nationality is {self.country}.")
    print(f"👨‍🎓 Currently I'm a {self.current_job}.")
    print(f"🧑‍💻 I'm very interesting on a {self.interest}.")
    print(f"🎮 My hobby is doing {self.hobby} at some time to fill my free time.")
    print(f"😎 My favorite tech stacks is:\n{json.dumps(self.tech_stacks, indent=2)}")

Me = WhoAmI("Wahyu Priambodo", 21, "He | Him", "Indonesian", "college student at Politeknik Negeri Jakarta (Jakarta State Polytechnic)", 
            "back-end development", "bug hunting or CTF challenges", {
            "Langs": 
              [
                "C++", 
                "Java", 
                "Python", 
                "PHP",
                "JavaScript"
              ],
            "Db": 
              [
                "MySQL",
                "MongoDB"
              ],
            "Tools":
              [
                "Docker",
                "VSCode",
                "Burp Suite"
              ],
            "OSes": {
              "Hacker mode": "Kali Linux WSL", 
              "Daily-based": "Windows"
            }
        })

Me.Introduction()
```

<h2>Links</h2>
<a href="mailto:wahyupriambodo.sec@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?&logo=gmail&logoColor=white" alt="Gmail"/></a>
<a href="https://www.linkedin.com/in/wahyu-priambodo"><img src="https://img.shields.io/badge/Wahyu_Priambodo-%230077B5.svg?&logo=linkedin&logoColor=white" alt="LinkedIn" alt="LinkedIn"/></a>
<a href="https://github.com/nullfriendz"><img src="https://img.shields.io/badge/nullfriendz-%23121011.svg?&logo=github&logoColor=white" alt="Github"/></a>
<a href="https://www.youtube.com/@wahyupriambodo6985"><img src="https://img.shields.io/badge/Wahyu_Priambodo-%23FF0000.svg?&logo=YouTube&logoColor=white" alt="YouTube"/></a><br>
<a href="https://www.instagram.com/wahyukiddies/"><img src="https://img.shields.io/badge/@wahyukiddies-%23E4405F.svg?&logo=Instagram&logoColor=white" alt="Instagram"/></a>
<a href="https://twitter.com/wahyukiddies"><img src="https://img.shields.io/badge/@wahyukiddies-%231DA1F2.svg?&logo=Twitter&logoColor=white" alt="Twitter"/></a>
<a href="https://discordapp.com/users/689915341429932032"><img src="https://img.shields.io/badge/wahyukiddies-%235865F2.svg?&logo=discord&logoColor=white" alt="Discord"/></a>
<a href="https://www.facebook.com/wahyukiddies/"><img src="https://img.shields.io/badge/Wahyu_Priambodo-%231877F2.svg?&logo=Facebook&logoColor=white" alt="Facebook"/></a>
