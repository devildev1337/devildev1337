from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "DevilPlayZ"
        self.age = "15"
        self.location = "Mars, With Elon Musk"
        self.work = "Developer"
        self.system = "Windows 10, x64"

    def skills(self):
        self.languages = {
            "main": ["Python", "Java", "Php", "Node.js", "C#", "HTML/CSS/JS"],
            "learning": ["golang", "C++"]
        }

        self.works = ['Nuker', 'Coding', 'hacking', 'etc...']
    
    def social_media(self):
        self.discord = "! :tm:DevilPlayZ_#0001"
        self.telegram = "None"
        self.sellix = "None"
        self.onlyfans = None


if __name__ == "__main__":
    readme = GithubReadme.create(DevilPlayZ)
