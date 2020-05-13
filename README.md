
Построение диаграммы№1

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
