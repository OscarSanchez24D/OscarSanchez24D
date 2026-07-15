class Oscar:
    def __init__(self):
        self.full_name = "Oscar Alonso Sánchez Núñez"
        self.age = 23
        self.birth_date = "September 30, 2001"
        self.location = "Chile 🇨🇱"
        self.university = "Universidad Santo Tomás"
        self.degree = "Ingeniero Informático (con distinción)"
        self.favorite_language = "Python 🐍"
        self.phone = "+56 9 5634 8207"
        self.email = "oscarsanchezd24@gmail.com"
        self.linkedin = "linkedin.com/in/oscar-sanchez-b29195369"

    def get_motto(self):
        return "🐭 Nibbling through code, one byte at a time!"

    def current_mission(self):
        return [
            "Building Python applications 🔨",
            "Learning new technologies 📚",
            "Creating digital cheese... I mean, solutions! 🧀"
        ]


oscar = Oscar()
print(f"Hello! I'm {oscar.full_name}")
print(f"Motto: {oscar.get_motto()}")
