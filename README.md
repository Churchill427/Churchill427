
Description
                    
                    


RSVP, short for "Répondez S'il Vous Plaît" (French for "Please Respond"), is a request for invitees to confirm their attendance, helping with event preparation. An event planner can use the system to manage RSVPs by inputting a guest list, tracking their attendance statuses, and viewing a filtered list of confirmed guests for efficient planning.
Functional Requirement:

    
        
            
                Req. #
            
             Type (Class)
            
                Requirement Description  
            
            
                Method Name
            
            
                Parameters
            
            
                Responsibilities
            
        
        
            
                1
            
            RSVPHandler
            
                Add a guest records to the rsvpList
            
            
                addGuestRSVP
            
            
                String rsvp
            
            
                
                This method should add the guest's details to the RSVP list, which is implemented as an ArrayList.
                Constraints:
                
                
                     rsvp contains guestName and status separated by colon ( : ).
                
                
            
        
        
            
                2
            
            RSVPHandler
            
                Filter the confirmed guests from the rsvpList
            
            
                getConfirmedGuests 
            
            
                
            
            
                This method should iterate over the rsvpList, check for guests with "confirmed" status, and return the names of confirmed guests in a new List.
                 Constraints: 
                
                
                    status is case-insensitive.
                    The method should return a List of Strings.
                
                
            
        
    

You are provided with the main method in the UserInterface class as code template, and it is excluded from evaluation.
Note:

    Edit only the  RSVPHandler class to implement the business requirements.
    The methods should be public, and the attributes of the class should be private. 
    In the Sample Input/Output provided, the highlighted text in bold corresponds to the input given by the user and the rest of the text represents the output.
    Ensure that the names for classes, attributes, and methods are provided as specified in the question description.
    Please do not use System.exit(0); to terminate the program.

 
Sample Input/Output 1:

    
        
        
        Enter the number of guests to add
        3
        Enter the guests details (name:status)
        John Doe:confirmed
        Jane Smith:pending
        Alice Brown:confirmed
        Confirmed Guests
        John Doe
        
        Alice Brown
        
        Sample Input / Output 2:
        
        
            
                
                Enter the number of guests to add
                2
                Enter the guests details (name:status)
                Bob White:pending
                Eve Black:declined
                
            
        
    

No confirmed guests
