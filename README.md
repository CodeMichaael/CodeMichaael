# Unnecessary Introduction 
```py
from typing import Optional

class Brain:

    def __init__(self, dumb: Optional[bool] = False, smart=True):
        self.dum = dumb
        self.smart = smart
    
    def who_am_i(self, i, am, michael):
        return i, am, michael

i_like_coding = Brain(dumb=True)

i_like_coding.who_am_i(i=["Backend Developer & Platform Developer", "Likes soccer"], am="Michaael", michael="me")
```

# Languages & Tools
```py
from typing import List

def languages_and_tools(lang: List[str], tools: [str]):
    return lang, tools

languages_and_tools(lang=["Java", "Python", "Typescript", "Go"], tools=["Flask", "Django", "NoSQL"])
```

# Current Projects
```py
from typing import List

def projects(some_projects: List[str]):
    return some_projects

projects(["OrderPlatform", "MichaelPlatform", "PlatformDatabase", "a few more secret ones :)"])
```
