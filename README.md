# Employee Management

This was a project I made while self studying ASP.NET Core, in order to enhnace my knowledge and better my understanding of back end development. Was definitely alot of fun and I'm very excited to learn more and get further into Back-end Development with .NET.

## Technologies used:

- ASP.NET Core 3.
- Entity Framework Core (Code First Approach).
- Microsoft SQL Server (Local DB).

## Features:

- Full Account Autherntication and Control (Register, Login, Account confirmation, Account recovery with tokens) using ASP.net Identity.
- Login with Google Account.
- Login with Facebook Account.
- Role based Authorization.
- Claim based Authorization.
- Account Lockout and general security.

## Preview of the project:
![HomePage](https://i.imgur.com/HXU9F3a.png)

![Login](https://i.imgur.com/FQJPtXo.png)

![ClaimBasedAuthorization](https://i.imgur.com/Xquxc6R.png)

![ClaimBasedAuthorization](https://i.imgur.com/znGbemA.png)

![AccessDenied](https://i.imgur.com/EtudZmA.png)

![CreateEmployee](https://i.imgur.com/3JTJqGj.png)

![EmployeeCreate](https://i.imgur.com/uPWec8Y.png)

![EmployeeCreatedView](https://i.imgur.com/ejKirB4.png)


## Setup Guide

This guide assumes that all required NuGET packages are already installed. **If you are not sure, run a Clean and Rebuild before starting.**

1. Make sure SQL Server is set up and ready for new databases instances, and set up your connection string in appsettings.
2. Migrations needed to build up the database are already there (check the folder name `Migrations` in the root project directory), launch the Package Manager Console from `Tools > NuGET Package Manager > Package Manager Console`
3. Run the command `Update-Database`
4. Check SQLServer to see if a database was added.
5. Make sure the `Migration History` table was built to, if not, be sure to manually build it to avoid future migration problems.
6. Clean, Rebuild, then Run.
