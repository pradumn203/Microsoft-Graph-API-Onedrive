# Microsoft Graph Onedrive API - Angular JS!
### For Ziroh Labs EWL Project

### Created By :-
- Pradumn Mishra ([pradumn203](https://linkedin.com/in/pradumn203/))
- Jyoti Prakash Dikshit ([Jyoti Prakash Dikshit](https://www.linkedin.com/in/jyoti-prakash-dikshit/))
- Abhisek Omkar Prasad ([AbhisekOmkar](https://www.linkedin.com/in/abhisek-omkar-prasad-70937a173/))
- Urja Jain ([Urja Jain](https://www.linkedin.com/in/urja-jain-020301/))
- Mithilesh Kumar Mahatha ([Mithilesh Mahatha](https://www.linkedin.com/in/mithilesh-kumar-mahatha-2b3a99195/))

This project is showing how you can use [Microsoft Graph](https://developer.microsoft.com/en-us/graph/) in your Angular 4 project.

Microsoft Graph gives you power to interact with Excel, Outlook, OneDrive, OneNote, Planner, Azure AD, SharePoint, etc.

## What this project does
It shows how you can Mircosoft Graph to login with a Microsoft account and access one drive files.


Once you login, it shows all your onedrive files and folders.



You can download any file you want by just clicking on it.





## How to run

This project was generated with [Angular CLI](https://github.com/angular/angular-cli).
Use `npm start` or `ng serve` to run. Navigate to [http://localhost:4200/](http://localhost:4200/).

## How to create a project by yourself

To create your app, you need get an App ID at [https://apps.dev.microsoft.com/](https://apps.dev.microsoft.com/).

Configure the app with the permissions you need. Check **Allow Implicit Flow**. Update **Redirect URLs**.

This demo needs  `Files.ReadWrite.All` permissions. The Redirect URLs are `http://localhost:4200`, `http://localhost:4200/home`.

Some of these info also need to be set up in the app [config file](./src/app/shared/configs.ts).

## Learn More

To learn more about Microsoft Graph, please check [this document](https://developer.microsoft.com/en-us/graph/).
