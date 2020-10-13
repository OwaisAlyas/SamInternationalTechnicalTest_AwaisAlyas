# SamInternationalTechnicalTest_AwaisAlyas
Sam International Technical Test Online Test with integration of OneSignal




# Please follow the below steps to Run this application:

1- Install asp.net core 2.2 if not installed already,
    You can download from here directly, https://dotnet.microsoft.com/download/visual-studio-sdks?utm_source=getdotnetsdk&utm_medium=referral    
2- Create a new folder in your local system, e.g E:\codingAssignment
3- Open git bash and go to this folder's location, e.g. > cd E:\codingAssignment
4- Clone this git repository on this folder using the following command:
   > git clone https://github.com/OwaisAlyas/SamInternationalTechnicalTest_AwaisAlyas.git
5- Go to the newly cloned repo fetched files and open the .csproj file with visual studio
6- Build the Solution
7- Then run the [ PM> Update-Database ] in Nuget Manager (Dont Miss this step, if you will miss the step you will not able see the application and users)
8- Build the Solution
9- Register your first user
10- Now create new user and the first user will be assigned Admin as there must be atleast 1 Admin User. 
11-Every New User will be assigned DataEntryOperater role. An admin can update the roles for each user.

For Help contact with: rajaawais31@gmail.com

#######################################   
Notes:
1- MVC Identity is user for user management - 
2- There are 2 Roles: Admin and DataEntryOperator
3- Admin can perform all crud operations while Data Entry Operator role can only view all apps.
4- Razor Syntax is Used for all data binding
5- Entity framework Code first first approach used.
6- OneSignal Apps API implemented i.e. View all Aps, Create App, Update App .
7- Solid - S,O,L are implemented partially for identity and OneSignal App integration.    


#######################################   

Coding Assignment Question from SAM International

•	Create OneSignal Account (it’s free). You have to use OneSignal Rest API to perform CRUD operation using .NET **Framework** MVC, Entity framework code first approach. All API can be found at given link. https://documentation.onesignal.com/reference/create-notification.
•	You have to implement only Apps API e.g. View all Aps, Create App, Update App.
•	There will be 2 roles Admin and Data Entry Operator.
•	Admin can perform all crud operations while Data Entry Operator role can only view all apps. Use MVC identity for user management. 
•	There’s no need to spend a lot of time on UI, you can use Razor.
•	Architecture of application should be clean and easy to understand. Follow Solid Pattern.
•	Once you done this assignment upload code at GitHub and share the link with Readme file where you can define steps to run the application.
Feel free to ask any question. Try to complete assignment within 48 Hours.

