<img src="https://i.pinimg.com/originals/fd/30/84/fd30846b19ff684f079d23b217a481e8.gif"  min-width="300px" max-width="300px "width="300px" allign="right" alt="logo readme">

# About Me

```python
class Kristian:
    def __init__(self):
        self.name = "Kristian"
        self.age = 22
        self.location = "Brazil, Rio Grande do Sul"
        self.language_proficiency = {
            'Portuguese': 'native',
            'English': {
                'reading': 'intermediate',
                'understanding': 'intermediate',
                'speaking': 'basic'
            }
        }
        self.current_role = "IT Assistant at Continental SP"
        self.education = {
            'current': "B.S. in Information Systems at Universidade Franciscana (UFN)",
            'past': "Technical degree in Computer Science from SEG Albert Einstein"
        }
        self.interests = [
            "system administration", "web development", 
            "algorithms", "artificial intelligence", 
            "Cyber Security"
        ]
        self.hobbies = ["customizing peripherals", "developing hardware", "competitive gaming"]

    def skills(self) -> Dict[str, List[str]]:
        return {
            'programming_languages': ['PHP', 'Python', 'C#', 'SQL'],
            'tools': ['Docker', 'VSCode', 'Github'],
            'web_development': ['Backend-focused'],
            'data_manipulation': ['SQL', 'Excel', 'VBA']
        }

    def learning(self() -> Dict[str, List[str]]:
        return {
            'current_focus': [
                "low-level programming with C++",
                "JavaScript",
                "computer architecture",
                "operating systems",
                "modeling and simulations"
            ],
            'methods': ["agile development", "project management"],
            'simulation_tools': ["VPython", "queue theory"]
        }

    def career(self) -> Dict[str, str]:
        return {
            'experience': "1 year as IT Assistant",
            'responsibilities': (
                "Maintaining infrastructure, administering ERP systems, "
                "managing servers, providing remote support"
            )
        }

    def contact(self) -> Tuple[str, str, str, str]:
        github = "github.com/KristianFrasson"
        linkedin = "linkedin.com/in/kristian-frasson-49a286288/"
        steam = "steamcommunity.com/id/krsfl/"
        gear = "gearz.gg/ferox"
        return github, linkedin, steam, gear

    def fun_facts(self() -> List[str]]:
        return [
            "I've been passionate about technology since childhood, starting with Minecraft plugin development.",
            "I customize high-performance peripherals and hardware as a hobby.",
            "I'm always seeking ways to improve business efficiency through technological solutions.",
            "I play competitive electronic games as a hobby."
        ]

# Connect with me and let's talk tech!

kristian = Kristian()
print(kristian.contact())
