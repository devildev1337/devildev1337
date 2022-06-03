from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "Devil"
        self.age = "15"
        self.location = "Mars, With Elon Musk"
        self.work = "Developer"
        self.system = "Windows 10, x64"

    def skills(self):
        self.languages = {
            "main": ["Python", "Java", "Php", "Node.js", "C#", "HTML/CSS/JS"],
            "learning": ["golang", "C++"]
        }

        self.works = ['Token Generator', 'hCaptcha Bypass', 'Chat Botter', 'Shill Tool', 'Token Manager', 'etc...']
    
    def social_media(self):
        self.discord = "𝑫 𝒆 𝒗 𝒊 𝒍 ᴱᶻ#0001"


if __name__ == "__main__":
    readme = GithubReadme.create(Void)
