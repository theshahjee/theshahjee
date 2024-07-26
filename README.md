class AboutMe:
    def __init__(self):
        self.name = "Abdullah Mughees"
        self.profession = "AI & ML Developer"
        self.skills = [
            "Natural Language Processing (NLP)",
            "Generative AI",
            "Python",
            "LangChain",
            "Django",
            "AI Model Training"
        ]
        self.interests = [
            "Playing Chess",
            "Watching MMA or Boxing"
        ]
        self.message = (
            "I am a passionate AI & ML Developer with a strong background in "
            "Natural Language Processing, Generative AI, and AI Model Training. "
            "With experience in Python, LangChain, and Django, I strive to create "
            "innovative solutions and advance the field of artificial intelligence. "
            "Outside of work, I enjoy playing chess and following the latest in MMA and boxing. "
            "I am always eager to explore new challenges and contribute to exciting projects."
        )
    
    def display_info(self):
        print(f"Name: {self.name}")
        print(f"Profession: {self.profession}")
        print("Skills:")
        for skill in self.skills:
            print(f"- {skill}")
        print("Interests:")
        for interest in self.interests:
            print(f"- {interest}")
        print(f"\nMessage: {self.message}")

if __name__ == "__main__":
    about_me = AboutMe()
    about_me.display_info()
