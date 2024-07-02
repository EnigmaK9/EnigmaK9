# 🚀 Welcome to My GitHub Profile 🚀

```python
#!/usr/bin/python

class EnigmaK9:

    def __init__(self):
        self.name = "EnigmaK9"
        self.profession = "Computer Engineer"
        self.location = "Mexico City, Mexico"
        self.skills = ["Web Development", "Data Science", "Deep Learning", "SQL", "Python", "TypeScript"]
        self.languages = ["en_US", "es_MX"]
        self.experience = [
            {"role": "Web Developer", "company": "Arrendify", "website": "https://arrendify.com/", "description": "Revamped and optimized web applications using cutting-edge technologies like Django and Python."},
            {"role": "Sentiment Analysis on X", "company": "Digital Systems Lab, UNAM", "description": "Implemented natural language processing techniques and managed data using Python libraries such as pandas, numpy, scikit-learn, NLTK, and Keras."},
            {"role": "Volunteer", "company": "Virtual Teaching and Cyberpsychology Lab, UNAM", "description": "Secured servers and developed web applications using TypeScript and Python, integrated MariaDB databases for secure data management."},
            {"role": "Data Science Bootcamp", "company": "Dev.F", "description": "Honed skills in SQL, Python, and data manipulation using Pandas and NumPy, integrated statistical techniques and machine learning algorithms into workflows."},
            {"role": "Colmena Project", "company": "LINX Laboratory, UNAM", "website": "https://linx.nucleares.unam.mx/colmena/", "description": "Implemented deep learning techniques in nano-satellites using Deep Q Reinforcement Learning to optimize battery usage."}
        ]

    def say_hi(self):
        print("Hey there! 👋 I'm EnigmaK9, a passionate and results-driven Computer Engineer based in Mexico City. Check out my projects on GitHub and connect with me on LinkedIn!")

    def display_experience(self):
        for job in self.experience:
            print(f"Role: {job['role']}")
            print(f"Company: {job['company']}")
            if 'website' in job:
                print(f"Website: {job['website']}")
            print(f"Description: {job['description']}\n")

me = EnigmaK9()
me.say_hi()
me.display_experience()
