# Data Warehouse of Online Course Selling Website

Data Warehouse to keep track of database data of an online course selling website.

![datawarehouse](https://user-images.githubusercontent.com/36237368/127318949-2f23f9c1-956e-4c2b-baf7-fcada2d69485.png)

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
![S_Dim_User](https://user-images.githubusercontent.com/36237368/127319284-ed2293b8-c093-4b2b-8376-856b4c31f8c0.png)

2. S_Dim_Course
![S_Dim_Course](https://user-images.githubusercontent.com/36237368/127319106-ea434a48-d53b-4ce6-92b2-36cb6d5d5257.png)
3. S_Dim_Date
4. C_Dim_CourseTopic
![S_Dim_CourseTopic](https://user-images.githubusercontent.com/36237368/127319143-65f3543f-0b47-461e-bd56-4b32cd0c76de.png)
5. HR_Dim_Instructor
![HR_Dim_Instructor](https://user-images.githubusercontent.com/36237368/127318980-6b81e7b6-8397-481f-97a5-c961acee644c.png)
6. HR_Dim_Staff
![HR_Dim_Staff](https://user-images.githubusercontent.com/36237368/127319036-d7755952-c965-4e4c-b954-74901bc276bd.png)
7. HR_Dim_TicketCategory
![HR_Dim_TicketCategory](https://user-images.githubusercontent.com/36237368/127319089-0cd6c89b-4916-45b3-8b8a-93d4e47231d7.png)