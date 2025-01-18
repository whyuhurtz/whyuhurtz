<div align="center">
  <h1 align="center">Hi! Welcome to My World.</h1>
  <img src="https://media.giphy.com/media/XKSPsk67cnCw0/giphy.gif" alt="Battle Programmer Shirase Pc GIF" width="300" height="200"/>
  <img src="https://media.giphy.com/media/3Q2hJ4FLN1UvS/giphy.gif" alt="Work Computer GIF" width="300" height="200"/><br>
  <a href="https://www.codewars.com/users/wahyu-priambodo"><img src="https://www.codewars.com/users/wahyu-priambodo/badges/micro" alt="CodeWars"/></a>
  <a href="https://codeforces.com/profile/wahoyuz"><img src="https://img.shields.io/badge/wahoyuz-445f9d?&logo=Codeforces&logoColor=white" alt="CodeForces"/></a>
</div>

<h2>About Me</h2>

```python
# whoami.py
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

Me = WhoAmI("Wahyu Priambodo", 21, "He | Him", "Indonesian",
            "college student at Politeknik Negeri Jakarta (Jakarta State Polytechnic)", 
            [ "sysadmin", "bug bounty hunting", "ctf" ],
            "Mobile Legends",
            {
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
                ]
            }
        )

Me.Introduction()
```

<h2>Connect with me :D</h2>
<a href="mailto:wahyupriambodo.net@gmail.com"><img src="https://img.shields.io/badge/Wahyu_Priambodo-D14836?&logo=gmail&logoColor=white" alt="Gmail"/></a>
<a href="https://www.linkedin.com/in/wahyu-priambodo"><img src="https://img.shields.io/badge/Wahyu_Priambodo-%230077B5.svg?&logo=LinkedIn&logoColor=white" alt="LinkedIn"/></a>
<a href="https://www.instagram.com/whyuhurtz/"><img src="https://img.shields.io/badge/@whyuhurtz-%23E4405F.svg?&logo=Instagram&logoColor=white" alt="Instagram"/></a>
<a href="https://x.com/whyuhurtz"><img src="https://img.shields.io/badge/@whyuhurtz-%231DA1F2.svg?&logo=X&logoColor=white" alt="Twitter"/></a>
<a href="https://www.facebook.com/whyuhurtz/"><img src="https://img.shields.io/badge/whyuhurtz-%231877F2.svg?&logo=Facebook&logoColor=white" alt="Facebook"/></a>

