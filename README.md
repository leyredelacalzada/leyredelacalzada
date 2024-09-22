# ⭐⭐⭐About Me⭐⭐⭐
```python
# Hi there👋 
# Here you'll be able to find out more about me ;) 
class Bio:
    def __init__(my):
        my.name = "Leyre de la Calzada"
        my.location = {"Hometown": "Barcelona", "Current": "Madrid"}
        my.profession = "Cloud Solution Architect at Microsoft"
        my.education = "MSc in Data Science Student at UNAV"
        my.languages = ["Spanish", "Catalan", "English", "French"]
        my.hobbies = ["Running", "Skiing", "Cycling"]

    def introduce(my):
        return (f"Hi! I'm {my.name}, a {my.profession}, currently based in {my.location['Current']}. "
                f"I'm originally from {my.location['Hometown']}. I'm pursuing my {my.education}. "
                f"I speak {', '.join(my.languages)}. In my free time, I enjoy {', '.join(my.hobbies)}.")
bio = Bio()
print(bio.introduce())


