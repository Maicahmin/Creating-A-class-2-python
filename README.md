# Creating-A-class-using-python

Use the init function to collect the employee information

a. Name, email and mobile number

Instantiate the Employee class two times with different information

Display all the properties of the object.

-----------------------------------------------------------------------

    class employee:

    def __init__(self, name, email, number):
    
        self.name = name
        
        self.email = email
        
        self.number = number
        

    employ1 = employee("maicah", "maicahmin14@gmail.com", "09216432337")

    print(employ1.name)

    print(employ1.email)

    print(employ1.number)


    print()

    employ2 = employee ("jamaica", "bayojamaica@gmail.com", "09074444340")

    print(employ2.name)

    print(employ2.email)

    print(employ2.number)
