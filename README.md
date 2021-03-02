# Downloadable content for Kentico Customization for Developers training course
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]() [![Maintenance](https://img.shields.io/maintenance/yes/2021.svg)]() 

This repository contains **v13 sample solution** for **Kentico Xperience Customization for Developers** course that covers back-end development in Kentico. The code in this package was created on Kentico Xperience 13.0 & .NET 4.8.

Find out more about the [Kentico Xperience Customization for Developers](https://xperience.io/services/training/developer-training-courses/xperience-customization-for-developers) course.

## Using the sample solution

To use the sample solution, you need to **Import the packages** [Doctor Specialty custom table](https://github.com/KenticoInternal/DEV02-KX13/blob/master/CMS/CMSSiteUtils/Import/DoctorSpecialtyListCustomTable.zip) and [Doctor Appointments Module](https://github.com/KenticoInternal/DEV02-KX13/blob/master/CMS/CMSSiteUtils/Import/DoctorAppointmentsModule.zip) and also use the [DoctorsAppointments](https://github.com/KenticoInternal/DEV02-KX13/tree/master/DoctorAppointments) project in your solution.

When importing, check **Import files (recommended)** and **Import code files** options. After import, you'll need to include imported files into the solution, add various references, and rebuild your solution in  Visual Studio.
1. Click the **Show All Files** button above the *Solution Explorer*. 
2. Navigate to the following folder and include this folder, all of its subfolders, and files into the solution: *App_Data > CMSModules > DoctorAppointments* folder.
3. Add the downloaded **DoctorAppointments** project to the solution and make sure all files in the project are included in the solution.
4. Add a reference to the *DoctorAppointments* project from the **CMSApp** project (right-click on *CMSApp > References > Add Reference > Projects*)
5. To the *DoctorAppointments* project, add the following references to Kentico Xperience assemblies (*DoctorAppointments > Reference > Add Reference > Assemblies*):
   1. CMS.Base
   2. CMS.Core
   3. CMS.DataEngine
   4. CMS.EmailEngine
   5. CMS.EventLog
   6. CMS.Helpers
   7. CMS.ImportExport
   8. CMS.MacroEngine
   9. CMS.Scheduler
6. Rebuild your solution.
