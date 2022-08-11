class Student():

    def setName(self,Name):
        self.Name=Name

    def getName(self,Name):
        return self.Name

    def setMarks(self,Marks):
        self.Marks=Marks

    def getMarks(self,Marks):
        return self.Marks

l=[]
n=int(input('enter the number of students;'))
for i in range(n):
    s=Student()
    Name=input("enter the names:")
    Marks=input("enter the marks;")
    s.setName(Name)
    s.setMarks(Marks)
    l.append(s)

for s in l:
    print("the student name:",s.getName(Name))
    print("the marks :",s.getMarks(Marks))
    print()
