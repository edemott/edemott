```python 
class Programmer(object):

    def __init__(self, name, major, interests):
        self.name = name
        self.major = major
        self.interests = interests
        
    def greet(self):
        print("Hello! Welcome to my profile.")

me = Programmer(
    name = "Ethan",
    major = "Data Science",
    interests = ["Faith", "Music", "Travel"]
)

me.greet()
```
