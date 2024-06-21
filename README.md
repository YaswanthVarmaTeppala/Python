
#Class and Obuject and __init__ Method
class Computer:
    """def __init__(self,cpu,ram):
        self.cpu = cpu
        self.ram = ram
    def config(self):
        print("config is",self.cpu,self.ram)


com1 = Computer('i5',16)
com2 = Computer('rizan 3',8)

com1.config()
com2.config()"""

#Constructor and Self

    def __init__(self):
        self.name = "Yash"
        self.age = 24

    def Update(self):
        self.age = 25
        print(self.age)

    def compare(self,other):
        if self.age == other.age:
            return True
        else:
            return False

c1 = Computer()
c1.age = 30
c2 = Computer()
if c1.compare(c2):
    print("They are same")
else:
    print("They are different")

print(c1.name)
print(c2.name)
print(c1.age)
print(c2.age)
print(c1.name,c1.age)
