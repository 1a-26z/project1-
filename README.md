# project1-Controller:
 C: /students, createStudent()
 R: /students, getAllStudent(); /students/{id}, getStudentById()
 U: /students, updateStudent()
 D: /students/{id}, deleteStudentById

 Service:
 C: createStudent()
 R: getAllStudent(), getStudentById()
 U: updateStudent()
 D: deleteStudentById()

 Repository:
 C: save();
 R: findByID(), findALL()
 U: save();
 D: deleteStudentById()
