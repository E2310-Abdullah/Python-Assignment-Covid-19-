# Python-Assignment-Covid-19-
 Python Basics  Control Flow Statements  Assignment - 2 (Covid-19)


age = str(input("Are you a cigarette addict older than 75 years old?: (True/False)")).title().strip()
chronic = str(input("Do you have a severe chronic diswase?: (True/False)")).title().strip()
immune = str(input("Is your immune system too weak?: (True/False)")).title().strip()
risk = age or chronic or immune
if risk == "True" :
    print("You are in the risky group")
else:
    print("You are not in the risky group")
