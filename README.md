# Zen_Class_Db

# MongoDb-Task-2-ZenClassDb

In this task I have created  a Zen class programme database with the below mentioned collections

users
codekata
attendance
topics
tasks
company_drives
mentors

Sample:

1.users collection document (Which I have created)

{
  "user_id": 1,
  "user_name": "Vishnu",
  "email": "vishnu@gmail.com",
  "mentor_id": 1,
  "mentor_name": "Priya"
}

2.codekata collection document (Which I have created)

{
  "user-id": 1,
  "user_name": "Vishnu",
  "Total_problems": 25,
  "no_of_problems_solved": 10
}

3.attendance collection document (which I have created)

{
  "user-id": 1,
  "user_name": "Vishnu",
  "month": "october",
  "absent": "16-oct-2020"
}

4.topics collection document (which I have created)

{
  "topic_id": 1,
  "topic": "Database",
  "topic_date": "16-oct-2020"
}

5.tasks collection document (which I have created)

{
  "task_id": 1,
  "user-id": 1,
  "user_name": "Vishnu",
  "task": "HTML task",
  "task_due_date": "28-oct-2020",
  "submitted": false
}

6.company_drives collection document (which I have created)

{
  "user-id": 1,
   "user_name": "Vishnu",
  "drive_date": "16-oct-2020",
  "company_name": "Google",
}

7.mentors collection document (which I have created)

{
  "mentor-id": 1,
  "mentor_name": "mohan",
  "mentor_email": "mohan@gmail.com",
  "mentees_count": 10
}
