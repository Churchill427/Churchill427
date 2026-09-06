escription
                    
                    


    The IAG is a famous textile industry. The industry has decided to provide increments based on the employee's experience. As a programmer, help the manager calculate the employees' salaries.
    Functional Requirements:
    
        
            
                Req. #
                Requirements Description
                 Type (Class)Method Name
                Parameters 
                Responsibilities
            
        
        
            
                1.
                Extract the details of the Employee and create an object for the Employee  class.
                 EmployeeUtility extractDetails
                String employeeDetails
                This method accepts employeeDetails separated by a colon as an argument and extracts the properties of the Employee from the argument. Then it sets these values to the Employee object and returnsincremented the Employee object.
            
            
                2.
                Calculate the incremented salary for the employee.
                 EmployeecalculateIncrementSalary  
                 
                This method calculates the increamented salary based on the employee's experience and returns the employee's incremented salary based on the following.
                    
                        
                            
                                Experience 
                                Increment(%)
                            
                        
                        
                            
                                0
                                -
                            
                            
                                1-3
                                10
                            
                            
                                4-6
                                20
                            
                            
                                7-10
                                30
                            
                            
                        
                    Constraints:The calculated incremented salary should be returned as double.The age should be between 21 and 60 (both inclusive), otherwise return -1.
                    
                    
                    When the gender is not 'F' or 'f' for female or 'M' or 'm' for male, otherwise return -1. 
                    The experience should be between 0 and 10 (both inclusive), otherwise return -1.
                    
                    
                    
                
            
        
    
    
    You are provided with the main method in the UserInterface class as code template, and it is excluded from evaluation.

Note:Edit only the Employee and EmployeeUtility classes to implement the business requirements.The methods and the constructor should be public, and the attributes of the class should be private.In the Sample Input / Output provided, the highlighted text in bold corresponds to the input given by the user and the rest of the text represents the output.Ensure that the names for classes, attributes, and methods are provided as specified in the question description.Please do not use System.exit(0); to terminate the program.

    
        
        Input Format:  <employeeId>:<employeeName>: <age>: <gender>: <salary>:<experience>
        
        
            Sample Input / Output 1  
        
        
            Enter the Employee Details
        
        
            EMP123:John:27:m:30000:5
        
        
            Employee Details
            Employee Id: EMP123
            Employee Name: John
            Age: 27
            Gender: m
            Salary: 30000
            Experience: 5
        
        
            Incremented salary is 36000.0 
        
        
               
        
        
            
            
                Sample Input / Output 2
                    
                
            
            
                Enter the Employee Details
            
            
                EMP554:Rose:24:f:8000:-3
                Invalid employee details
