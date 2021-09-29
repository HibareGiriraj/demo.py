class Employee:
    def __init__(self,ename,enum):                  # Constructor
        self.ename=ename
        self.enum=enum
    def display(self):                               # To get display
        print('Name : ',self.ename)
        print('E_number : ',self.enum)
class Fitness(Employee):                              # Its a  derived class
    def __init__(self,height,ename,enum,weight):
        self.height=height
        Employee.__init__(self, ename, enum)
        self.weight=weight
    def display(self):
        print('Height : ',self.height)
        Employee.display(self)
        print('weight : ',self.weight)
f1=Fitness(5.8,'Giriraj',23,65)
print('Employee Details : ')
f1.display()
