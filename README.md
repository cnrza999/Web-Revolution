# Web-Revolution
This article is about Web Application Revolution.

Web Revolution

Web Application แบ่งออกเป็น 3 ยุคคือ

ยุคแรก 
ในช่วง ค.ศ 1989-1990 การจะสร้างเว็บๆหนึ่งนั้น เราได้แบ่งเป็น 2 ส่วน -> 1.ไฟล์ HTML(hypertext mark up language)
ที่ทำหน้าที่โชว์หน้าเว็บไซต์แต่ไม่สามารถอ่านฐานข้อมูลได้ และ -> 2.Common Gateway Interface(CGI) มีหน้าที่อ่านฐานข้อมูลจากเซิฟเวอร์ 
แล้วนำมาแสดงผลเป็น HTML อีกทีโดยทั่วไป CGI นั้นสามารถเขียนโดยภาษาอะไรก็ได้ เช่น C#, Perl, Python แต่ยุคนั้นนิยมใช้ภาษา Perl ในการเขียน CGI.

ยุคที่สอง
ในช่วง ค.ศ 1994-1995 ในยุคนี้เราสร้างเว็บโดยการเขียนรวมไฟล์ HTML กับ code ที่ใช้อ่านฐานข้อมูลลงไปใน HTML ภาษาที่นิยมในการเขียนคือ PHP.

ยุคที่สาม 
ในช่วง ค.ศ 2003 ในยุคนี้เราสร้างเว็บโดนการเขียน code ตัวกลางขึ้นมาเรียกว่า Dispatcher(Router) ใช้ในการควบคุมการทำงานทั้งหมดเอาไว้ เมื่อมี request ไปที่เส้นทางไหน
Dispatcher จะทำหน้าที่หา function ที่ต้องการใช้ หากหา function นั้นไม่เจอ Dispatcher จะไปหาใน folder อีกที ยุคนี้เรียกว่า modern stack
ระบบทีนิยมใช้คือ Java Spring MVC, Ruby on Rails, PHP Laravel.

Web Revolution

Web application consist of 3 eras

First era,
In 1989-1990 in order to build a website we seperate into 2 part -> The first part is HTML(hypertext mark up language) file 
this part is use to display the webpage but unable to read the database somehow. The second part is Common Gateway Interface(CGI) the 
role of CGI is to read database and display in form of HTML. In generally, CGI can be written in any computer language including C#, Perl, Python.
However, the most popular language is Perl.

Second era,
In 1994-1995, we build a website in one single files which consist of HTML and code that read database, the most popular is PHP.

Third era,
In 2003, we no longer use file but apply the central code known as Dispatcher which control the operating system. when the request is come the 
Dispatcher will find the function that suit the request best. However, if there is no valid function, it will continue searching in the folder.
This era is called modern stack. the popular system that mostly used consist of Java Spring MVC, Ruby on Rails, PHP Laravel. 

