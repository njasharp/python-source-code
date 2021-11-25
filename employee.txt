class Employee: 
  def __init__(self, name, job): 
    self.name = name 
    self.job = job 
     
  def tasks(self): 
    print("Tasks are:") 
    
class Manager(Employee): 
  def __init__(self, name, job, staff): 
    super().__init__(name, job) 
    self.staff = staff 
 
  def tasks(self): 
    print("Oversees:") 
    print(staff) 
 
class Associate(Employee): 
  def tasks(self): 
    print("Take orders from manager")