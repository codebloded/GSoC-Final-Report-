
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

My work in project is to add features to allow teachers to give assignments to students.Assignmets are handle by teacher from the sugarizer-server dashboard.

My project is divided into two phases:
1. [Sugarizer-server](https://github.com/llaske/sugarizer-server)
2. [Sugarizer](https://github.com/llaske/sugarizer) (Client Application)

I created some APIs for assignment feature in sugarizer-server. Also created some UIs called views in sugarizer-server dashboard to interact with assignments.
------More to add------

## ✔️ Work Completed
### Phase 1 Sugarizer-server (Dashboard)

Features Implemented :
I made up some APIs 
- Create Asignmets
- Edit Assignments
- Delete Assignmemts
- Launch Assignment: This APIs is used for Launching the assignment which means assignment goes to every student associated to the assignment.
- Return Assignment: This API made `isSubmitted:false` and update the `status:null` 
- Update Comment : This API is responsible for adding comment coressponding to the assignment delivery by a teacher.
- Submit Assignment: This API made `isSubmitted:false` and update `submissinDate: new Date().getTime()`

I have build some Screens in dashboard.
 - Add Assignment

   API Route : `/api/v1/assignments`

   URL :  `/dashboard/assignments/add`

   Add Assignment View ⬇️

   ![add](https://user-images.githubusercontent.com/48005711/192241981-a89e45f9-b710-4a69-88ab-281bf93cb71b.png)

 - Edit Assignment

   API Route : `/api/v1/assignments:assignmentId`

   URL :  `/dashboard/assignments/edit/6331524e1b038f22b6e96bab`

   Edit Asignment View ⬇️
 
   ![edit](https://user-images.githubusercontent.com/48005711/192244633-bef6ef7b-5697-4a80-9330-6c757d0a6efc.png)
  
  - List All Assignment

    API Route : `/api/v1/assignments`

    URL :  `/dashboard/assignments/`

    List All Asignments View ⬇️
 
   ![kist](https://user-images.githubusercontent.com/48005711/192245324-3dda4e0a-4348-4707-8710-5e1425d55def.png)
   
  - List All Assignment Deliveries 
   
    API Route : `/api/v1/assignments/deliveries/:assignmentId`

    URL :  `/dashboard/assignments/deliveries/6331524e1b038f22b6e96bab`

    List All Asignment Deliveries View ⬇️

   ![del](https://user-images.githubusercontent.com/48005711/192245993-a643cfc9-f465-4bd7-8745-7acd9a73a04b.png)
   
   Functionalities in dashboard for assignments :
   - Search Assignment and Filter by Status.
   - Restrict to duplicate the assignment entry by journal view in dashboard.

 




