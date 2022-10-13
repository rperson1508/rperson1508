```python
class AboutMe:
    def __init__(self) -> None:
        self.name = "invalid-user"
        self.pronouns = ["he", "him"]
        self.hobbies = ["playing the drums", "science", "chess"]
        self.human_languages = ["english", "mandarin"]
        self.computing_languages = ["python", "html", "css", "sql"]
        self.learning = ["javascript", "typescript"]
        self.tools = ["visual studio code", "git"]
    
    @property
    def discord(self) -> str:
        return "invalid-user#1119"

    def hello(self) -> None:
        print("Hello world!")

me = AboutMe()
me.hello()
```
