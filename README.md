# -*- coding: utf-8 -*-


class ComputerEngineerStudent:

    def __init__(self):
        self.name = "Mahdi Moghassemi"
        self.role = "Computer Engineering @ K. N. Toosi University of Technology"
        self.language_spoken = ["en_US", "Fa"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = ComputerEngineerStudent()
me.say_hi()
