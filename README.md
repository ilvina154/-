Практическая работа №1
Построение диаграммы


@startuml
Institution o— Student
Institution o— Course
Institution o— Lecturer
Course -left- Student
Course -right-Lecturer
Class Institution{
* name:String
* listStudents:List
* listLecturers:List
* listCourses:List
* getName():String
* setListStudents():List
* setListLecturers():List
* setListCourses():List
* }
* Class Student{
* name:String
* listCourses:List
* listLecturers:List
* getName():String
* getListCourses():List
* getListLecturers():List
* }
* Class Lecturer{
* name:String
* listCourses:List
* listStudents:List
* getName():String
* getListCourses():List
* getListStudents():List
* }
* Class Course{
* name:String
* listStudents:List
* listLecturers:List
* array getName():String
* getListStudents():List
* getListLecturers():List
* }
* @enduml
Image link: http://www.plantuml.com/plantuml/img/hLFB2i8m4BpdAt9KIdwWI2bu4egNVa6mQmsqAIIRWuZ_RgJPjDA7YjwoEvEPsJnoYzAWQnkMnzL1MrJeK7MQTqBm4bq56YVzVUUCXKcxW1Cw0uRrE1SDd75GeQvHzGN5G6wajNoaTME2Qzb2Mg9HklPLeom65PiMljY5AWiWYGMKIe9xvm3sHSPOmcl0epVQRCaguHQm6BbvwDKlCg8bKGRJo0c-n23dUvWvYCxFEvlvpRJp8zMhOIA-CX05fixNYHSkxwUyYrT4QViT_tnDtbmQ8wyhgLSUpYVdd8EkdZ-HqUe1



Написание кода по диаграмме🔝
public class institution{
private string name;
private listStudents:List<Student>
private listLecturers:List<Lecturer>
private listCourses:List<Course>
 
public String getName()
public setListStudents():List<Student>
public setListLecturers():List<Lecturer>
public setListCourses():List<Course>
}

public Class Student{
private String name;
private listCourses:List<Course>
private listLecturers:List<Lecturer>

public String getName()
public getListCourses():List<Course>
public getListLecturers():List<Lecturer>
}

public Class Lecturer{
private String name;
private listCourses:List<Course>
private listStudents:List<Student>
 
public String getName()
public getListCourses():List<Course>
public getListStudents():List<Student>
 
}
public Class Courses{
private String name;
private listStudents:List<Student>
private listLecturers:List<Lecturer>
 
public String array getName()
public getListStudents():List<Student>
public getListLecturers():List<Lecturer>
}



