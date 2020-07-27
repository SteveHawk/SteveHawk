# Hi there 👋 It's Steve! <img width="35" src="https://raw.githubusercontent.com/SteveHawk/SteveHawk/master/rick.gif">

🐍 Let me introduce myself a bit here...

<div>
  <img width="333" align="right" src="https://raw.githubusercontent.com/SteveHawk/SteveHawk/master/steve.gif">
</div>

```python
class Steve:
    def __init__(self, UUID: uuid.UUID) -> None:
        self.UUID = UUID
        self.gender = Demiboy()
        self.pronouns = {"He", "Him"}
        self.code = ["Python", "Golang", "C/C++", "Java"]
        self.OS = ("Windows", "Linux", "Android")

    def career(self, year: int) -> str:
        self.career = ["Student", "CV Engineer"]
        now: int = time.localtime()[0]
        if year < now:
            return f"I was a {self.career[0]}."
        elif year == now:
            return f"I am a {self.career[1]} now."
        else:
            return "Maybe I'll become a Musician in the future!"

    def hobby(self, index: int = random.randint(0, 69)) -> str:
        self.interests = [
            "Science Fiction", "Machine Learning", "Chemistry",
            "Computer Vision", "Computer Music", "Astronomy",
            "Music", "Software Defined Radio", "Japanese",
            "Walking (Not Running!)", "Not Tetris 2"
        ]  # And More
        return self.interests[index % len(self.interests)]

world = Universe.World()
ME = Steve(uuid.uuid5(world.UUID, "SteveHawk"))
```

---

💡 & 💖 From [@SteveHawk](https://github.com/SteveHawk)
