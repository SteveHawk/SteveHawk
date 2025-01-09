# Hi there 👋 It's Steve! <img width="35" src="https://raw.githubusercontent.com/SteveHawk/SteveHawk/master/rick.gif">

🐍 Let me introduce myself a bit here...

<div>
  <img width="333" align="right" src="https://raw.githubusercontent.com/SteveHawk/SteveHawk/master/steve.gif">
</div>

```python
class Steve:
    def __init__(self, UUID: uuid.UUID) -> None:
        self.UUID = UUID
        self.gender = Gender.UNDEFINED
        self.pronouns = {"They", "Them"}
        self.code = ["Python", "Rust", "Java", "Golang", "C"]
        self.OS = ("Linux", "Android")

    def career(self, year: int) -> str:
        self.career = ["Computer Vision Engineer", "Solo Dev"]
        if year < (now := time.localtime()[0]):
            return f"I was a {self.career[0]}."
        elif year == now:
            return f"I am a {self.career[1]} now."
        return "Maybe I'll become a Musician in the future!"

    async def hobby(self, index: int = random.randint(0, 69)) -> str:
        self.interests = [
            "Vision Computing", "Music", "Ham Radio", "Astronomy",
            "Science Fiction", "Toki Pona", "Not Tetris 2"
        ]  # And More
        return self.interests[index % len(self.interests)]

world = Universe.World()
ME = Steve(uuid.uuid5(world.UUID, "SteveHawk"))
```

---

💡 & 💖 From [@SteveHawk](https://github.com/SteveHawk)
