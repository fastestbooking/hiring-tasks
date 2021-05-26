## Backend Deve
Assume your assign a task to build a university admission backend.

Assuming the following interface
```ts
Student {
  firstName: string;
  lastName: string;
  email: string
  userName: string
  cgpa: number
}
```
```ts
Application {
  student: Student;
  program: string;
  semeter: string;
  created_at: Date;
  updated_at: Date;
}

```

Create a RESTAPI  to manage the Student and Application resource. Upload your code to github and send the github repo link to hr@fastestbooking.com

###### Note: 

  * Use any framwork of your choice
  * Repo has to be public
  * Repo name has to begin with fastestbooking-`*****` (Replace `****` with anything eg `'task'`)
  * Writing Unit/Integration test is a plus but not requiredts
