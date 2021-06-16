import mysql.connector
con=mysql.connector.connect(host="localhost",user="root",password="",database=" task_1")

def AddStudent(NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,
MobileComputing,Networking,TOTAL,AVERAGE,GRADE):
    res=con.cursor()
    sql="insert into student (NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,TOTAL,AVERAGE,GRADE) values (%s,%s,%s,%s,%s,%s,%s,%s,%s,%s,%s)"
    user = (NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,TOTAL,AVERAGE,GRADE)
    res.execute(sql, user)
    con.commit()
    print("Student data Add Successfully")

def GetStudent(id):
    res=con.cursor()
    sql = "SELECT ID,NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,TOTAL,AVERAGE,GRADE from student where id=%s"
    user = (id,)
    res.execute(sql, user)
    result=res.fetchall()
    print(result)


def GetAllStudent():
    res=con.cursor()
    sql="SELECT ID,NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,TOTAL,AVERAGE,GRADE from student "
    res.execute(sql)
    result=res.fetchall()
    print(result)
     

def UpdateStudent(NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,id):
    res=con.cursor()
    sql = "update student set NAME=%s,DEPARTMENT=%s,COLLEGE=%s,DatabaseManagementSystem=%s,DataStructure=%s,ObjectOrientedProgramming=%s,MobileComputing=%s,Networking=%s where id=%s"
    user = (NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,id)
    res.execute(sql, user)
    con.commit()
    print("Student data Updated Successfully")



def DeleteStudent(id):
    res=con.cursor()
    sql = "delete from student where id=%s"
    user = (id,)
    res.execute(sql, user)
    con.commit()
    print("Student data Deleted Successfully")


def EXit():
    pass

while True:
    print("1.AddStudent Data")
    print("2.GetStudent Data")
    print("3.GetAllStudent Data")
    print("4.UpdateStudent Data")
    print("5.DeleteStudent Data")
    print("6.Exit")
    choice=int(input("Enter your choice "))
    
    if choice == 1:
        NAME = input("Enter Name: ")
        DEPARTMENT = input("Enter Department: ")
        COLLEGE = input("Enter College: ")
        DatabaseManagementSystem =int(input("Enter mark of DBMS: "))
        DataStructure =int(input("Enter mark of DS: "))
        ObjectOrientedProgramming =int(input("Enter mark of OOPS: "))
        MobileComputing =int(input("Enter mark of MC: "))
        Networking =int(input("Enter mark of Networking: "))
        TOTAL = DatabaseManagementSystem + DataStructure + ObjectOrientedProgramming + MobileComputing + Networking
        print("Total ="  +str(TOTAL))
        AVERAGE = TOTAL/5
        print("Average ="  +str(AVERAGE))
        
        GRADE = ''
        if (AVERAGE >= 85):
            GRADE='A'
            print("Grade A")
        elif (AVERAGE >=60):
            GRADE='B'
            print("Grade B")
        elif (AVERAGE >=35):
            GRADE='C'
            print("Grade C")
        else:
            GRADE='F'
            print("Grade F(Fail)")
        
        AddStudent(NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,
                    DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,TOTAL,AVERAGE,GRADE)
    elif choice == 2:
        id=input("Enter the ID to Select: ")
        GetStudent(id)
        
        
    elif choice == 3:
        GetAllStudent()
        
    
    elif choice == 4:
        id=input("Enter the Id: ")
        NAME = input("Enter Name: ")
        DEPARTMENT = input("Enter Department: ")
        COLLEGE = input("Enter College: ")
        DatabaseManagementSystem =input("Enter mark of DBMS: ")
        DataStructure =input("Enter mark of DS: ")
        ObjectOrientedProgramming =input("Enter mark of OOPS: ")
        MobileComputing =input("Enter mark of MC: ")
        Networking =input("Enter mark of Networking: ")
        UpdateStudent(NAME,DEPARTMENT,COLLEGE,DatabaseManagementSystem,DataStructure,ObjectOrientedProgramming,MobileComputing,Networking,id)

    elif choice == 5:
        id=input("Enter the ID to delete: ")
        DeleteStudent(id)
        

    elif choice == 6:
        quit()

    else:
        print("Invalid selection.please select correct Menu !")
        





