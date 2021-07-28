# Data Warehouse of Online Course Selling Website

Data Warehouse to keep track of database data of an online course selling website.

![datawarehouse-min](https://user-images.githubusercontent.com/36237368/127320048-060457e2-b52a-497e-a273-94608573fcdc.png)

## Data Marts:
1. Course Education
    - Facts:
        1. Course_Education
        2. C_Fact_CourseBuying
        3. C_Fact_CourseBuying_Periodic
        4. C_Fact_CourseDownloading
        5. C_Fact_Course_Downloading_Periodic
    
2. User Behavior
    - Facts:
        1. U_Fact_UserRating
        2. U_Fact_PassedCourses
        3. U_Fact_UserRate_Acc
        4. U_Fact_Comments
        5. U_Fact_CommentRating
        6. U_Fact_InfluentialUsers_Acc

3. Human Resources
    - Facts:
        1. Human Resources ترامHR_Fact_InstructorCourse_T
        2. HR_Fact_InstructorCourse_ACC
        3. HR_Fact_InstructorRate_Daily
        4. HR_Fact_StaffPayment_T
        5. HR_Fact_StaffPayment_Yearly
        6. HR_Fact_Tickets_Daily


## Dimensions:
1. S_Dim_User
2. S_Dim_Course
3. S_Dim_Date
4. C_Dim_CourseTopic
5. HR_Dim_Instructor
6. HR_Dim_Staff
7. HR_Dim_TicketCategory

## Dimensions Details:

1. S_Dim_User
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320073-cc13a462-630c-4f4a-9437-02cc5bb9f4a9.png" style="width:500px">

2. S_Dim_Course
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320068-02a47129-5c05-4de9-a011-dc44b06e155e.png" style="width:500px">

3. S_Dim_Date
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320073-cc13a462-630c-4f4a-9437-02cc5bb9f4a9.png" style="width:500px">

4. C_Dim_CourseTopic
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320070-2c36e65f-c00c-4bbb-89b1-8c0b4300554f.png" style="width:500px">

5. HR_Dim_Instructor
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320057-ea704a49-8710-4cfe-89bc-965fc7bdf789.png" style="width:500px">

6. HR_Dim_Staff
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320060-a8784070-f2d7-44c5-a07a-b8c615003b52.png" style="width:500px">

7. HR_Dim_TicketCategory
<br/>
<img src="https://user-images.githubusercontent.com/36237368/127320063-380f5388-31ec-4a82-80c4-4c2d5cace83b.png" style="width:500px">
