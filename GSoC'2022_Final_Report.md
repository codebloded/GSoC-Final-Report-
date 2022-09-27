
<h1 align="center"><img height="50px" width="50px"src="https://user-images.githubusercontent.com/48005711/192225098-47f04ed7-1a27-4ad2-a031-469a15509d8a.png"/>Sugarizer Assignments</h1>

<div align="center">
  <span>Google Summer of Code, 2022 Final Report</span>
  <br>
  <br>
</div>

<div align="center">
  <img height="200px" width="200px" src="https://user-images.githubusercontent.com/48005711/192224558-8479ee0f-2f4d-4b8b-a4e7-ef9a726be6b8.png"/>
  <img height="200px" width="200px" src="https://user-images.githubusercontent.com/48005711/192224568-601ba03a-033f-47f3-ab2b-5eda0fc60688.png"/>
  
</div>

Student Name : Rohan Kumar

Email: rohanrajput16.phy@gmail.com

Github Username: [codebloded](https://github.com/codebloded/)

Mentor: [Nikhil Mehra](https://github.com/NikhilM98) , [Lionel Laské](https://github.com/llaske)

## My Work in Project

My work in the project is to add features to allow teachers to give assignments to students. Assignments are handled by a teacher from the sugarizer-server dashboard. 

My project is divided into two phases:
1. [Sugarizer-server](https://github.com/llaske/sugarizer-server)
2. [Sugarizer](https://github.com/llaske/sugarizer) (Client Application)

I created some APIs for assignment feature in sugarizer-server. Also created some UIs called views in sugarizer-server dashboard to interact with assignments.
------More to add------

## ✔️ Work Completed
### 🟢 Phase 1 Sugarizer-server (Dashboard)

Features Implemented :
- Create : Teachers can create assignment in the dashboard.
- Edit : Teachers can edit the assignments which are created on their own.
- Delete : Teachers can delete the assignments which are created on their own.
- Launch Assignment : When the teacher launches an assignment, that assignment will go to all the students who are associated with that assignment.
- Submit Assignment : This feature is used through the Sugarizer client app, which allows a student to submit their assignments.
- Return Assignment : When the teacher returns an assignment for one student, that student can resubmit that assignment.
- Update Comment : A teacher can add a comment to give some remarks or grades on a particular delivery.


I have build some Screens in dashboard.
 - Add Assignment
 
   ![add](https://user-images.githubusercontent.com/48005711/192241981-a89e45f9-b710-4a69-88ab-281bf93cb71b.png)

 - Edit Assignment.
  
    ![edit](https://user-images.githubusercontent.com/48005711/192244633-bef6ef7b-5697-4a80-9330-6c757d0a6efc.png)
  
 - List All Assignment.
 
   ![kist](https://user-images.githubusercontent.com/48005711/192245324-3dda4e0a-4348-4707-8710-5e1425d55def.png)
   
  - Actions in List all assignment view.
    
    ![lS](https://user-images.githubusercontent.com/48005711/192514855-4459ab09-4ee1-44af-9aea-94e7f703663b.png)

 - List All Assignment Deliveries.

   ![del](https://user-images.githubusercontent.com/48005711/192245993-a643cfc9-f465-4bd7-8745-7acd9a73a04b.png)
   
   ![Screenshot from 2022-09-27 17-13-32](https://user-images.githubusercontent.com/48005711/192516528-b89d0ddc-270a-4f80-b0f7-a31fe3d65bb8.png)
     - Teachers can check the assignment of any student by clicking on launch assignment delivery button.
     - Teachers can add comments to the students to remark on any particular assignment.
     - This is how a teacher check and add comment on assignment delivery.⬇️
  
     ![mango](https://user-images.githubusercontent.com/48005711/192519428-05566cda-afa0-45cb-9615-5f17389dd5b9.gif)
     
     -Such an assignment can be returned by a teacher to a particular student.
     
     ![ret](https://user-images.githubusercontent.com/48005711/192520120-5e061f1d-4fcd-492a-9165-2469daadf062.gif)
     After returning the delivery of an assignment, the status of that delivery is changed from "Delivered" to "Expected", which means that the                assignment can be submitted by the student to whom it has been returned.



   Functionalities in dashboard for assignments :
   - Search Assignment and Filter by Status.
      ![Screenshot from 2022-09-27 16-06-28](https://user-images.githubusercontent.com/48005711/192504171-0bbabd17-75b5-489d-834d-25d6ed7ff35e.png)
        - Search Assignmet by its name.
        - Search Assignment by its status.
        - Also we can filter the assignment by the combination of its name and its status. ⬇️
        ![Screenshot from 2022-09-27 16-12-49](https://user-images.githubusercontent.com/48005711/192505350-922c50f6-c2e6-41bd-9ba0-1aacf484e03c.png)
        - There are three types of status with an assignment. ⬇️
        
          ![Screenshot from 2022-09-27 16-15-37](https://user-images.githubusercontent.com/48005711/192505902-4166b612-4aa3-4744-8e9b-0f35cb95b80c.png)
        
   - Restrict to duplicate the assignment entry by journal view in dashboard.
   ![restrict](https://user-images.githubusercontent.com/48005711/192507029-e441d958-ba27-4c99-a88a-49985d0cd631.gif)

 
### 🟢 Phase 2 Sugarizer (Client App).

Features Implemented:









