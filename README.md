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

i_like_coding.who_am_i(i=["Backend Developer", "Likes soccer"], am="Michaael", michael="me")
```
