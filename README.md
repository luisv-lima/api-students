# api-students
API to manage 'Golang do Zero' course students

Routes:
- GET /students - List all students
- POST /students - Create student
- GET /students/:id - Get infos from a specific student
- PUT /students/:id - Update student
- DELETE /students/:id - Delete student
- GET /students?active=<true/fales> - List all actitve/non-active students


Struct Student:
- Name   (string)
- CPF    (int)
- Email  (string)
- Age    (int)
- Active (bool)