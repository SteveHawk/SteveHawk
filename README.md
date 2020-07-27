# Hi there 👋 It's Steve!

<p>
  <img width="333" align="right" src="https://raw.githubusercontent.com/SteveHawk/SteveHawk/master/steve.gif">
  <img width="333" align="right" src="https://raw.githubusercontent.com/SteveHawk/SteveHawk/master/rick.gif">
</p>

🐍 Let me introduce myself a bit here...

```python
import uuid
import time
import world
import random
from typing import List
from LGBTQ+ import Demiboy

class Steve:
    def __init__(self, UUID: uuid.UUID) -> None:
        self.UUID = UUID
        self.gender = Demiboy()
        self.pronouns = {"He", "Him"}
        self.code = ["Python", "Golang", "C/C++", "Java"]
        self.OS = ("Windows", "Linux", "Android")
        self.website = "https://stevehawk.tk"

    def career(self, year: int) -> str:
        self.career = ["Student", "CV Engineer"]
        now: int = time.localtime()[0]
        if year < now:
            return f"I was a {self.career[0]}."
        elif year == now:
            return f"I am a {self.career[1]} now."
        else:
            return "Maybe I'll become a musician in the future!"

    def hobby(self, index: int = random.randint(0, 69)) -> str:
        self.interests: List[str] = [
            "Science Fiction", "AI/Machine Learning", "Chemistry",
            "Computer Vision", "Computer Music", "Astronomy",
            "Music Production", "Software Defined Radio",
            "Walking (Not Running!)", "Japanese", "Origami",
            "Toki Pona", "Ping Pong", "Not Tetris 2"
        ]
        return self.interests[index % len(self.interests)]

ME = Steve(uuid.uuid5(world.UUID, "SteveHawk"))
```

---

💡 & 💖 From [@SteveHawk](https://github.com/SteveHawk)
