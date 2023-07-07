# [rsschool-cv](https://Tursynkhan.github.io/rsschool-cv/)
# Tursunov Tursynkhan

_A passionate web developer from Astana_ <br>

+77761388540 | [Email](mailto:tursynkhan001@gmail.com) | [LinkedIn](https://www.linkedin.com/in/tursynkhan-tursunov-a64763211/) | [GitHub](https://github.com/Tursynkhan) 

## 💫 About me

_I hold a degree in Computer Science and I am a student at Alem School, where I have gained valuable knowledge and skills in programming languages like Golang and Javascript. Through various projects including websites, Telegram bots, and TCP chat applications, I have gained hands-on experience working with technologies such as REST API, Microservices, Docker, Docker Compose, Databases, and Golang frameworks like Gin and Echo. I am proficient in using libraries like Postman API and have a strong understanding of key concepts like goroutines, channels, and mutexes for optimizing performance. Currently, I am focused on studying frontend development with the goal of becoming a professional Web developer._

## 👨🏻‍💻 Technical Experience

**Backend Development Intern** @ [ENU](https://enu.kz/kz) _(Jan 2023 - March 2023)_ <br>

- Worked on the server-side of Platonus’ website using both the Go programming language and Node.js.
- Implemented RESTful APIs to connect frontend applications with backend services using Go channels and
goroutines.
- Using GO, developed a microservice for reading large volume of data from PostgreSQL database
- Experience in writing the HTTP RESTful Web services and SOAP API’s in Golang
- Experienced in using Go technologies on UNIX and Linux platforms

**Volunteer,Computer Tutor**  _(Sep 2022 - Oct 2022)_ <br>
_Social Student Loan Project_

- Taught basic concepts/principles of computer science to students and observed and evaluated students’
performance.
- Worked one-on-one to insure the students understanding of Microsoft software
- Help students prepare for exams and quizzes

## 📌 Projects

**[Forum, Website](https://github.com/Tursynkhan/forum)** | _Go,JavaScript,net-http,SQLite,docker_

- Developed a website-forum where people can hold conversations by posting messages.Created a sign-up, sign-in
features for users. Passwords were secured by hashing algorithms.In addition, added a feature for filtering posts
based on keywords or categories
- Used Golang as a main language, and HTML/CSS and JS for frontend, and SQLite as a database, and Docker
Compose where we created local SQLite database. Tested software using Postman
- Utilized the REST API principle and clean architecture in the development of my website-forum.

**[SuperHero Database, Website](https://github.com/Tursynkhan/sortable)** | _Javascript , Fetch API, DOM_
 
- Developed a web application to organize and display data about superheroes using HTML, CSS, and JavaScript.
- Utilized the fetch API to retrieve superhero information from a remote API.
- Implemented pagination functionality to allow users to browse through the data in multiple pages, with
customizable page sizes.
- Designed an interactive search feature to filter superheroes by name in real-time.
## 👨🏻‍🎓 Education

**Bachelor of Science** in Information Technology<br>
[Eurasian National University](https://enu.kz/kz) - Astana, Kazakhstan _(2019 - 2023)_ <br>

**Fullstack Developer** course<br>
[Alem School](https://alem.school/) - Astan, Kazakhstan _(2022 jan - 2023 aug)_
## 💬 Languages

US **English**: B1 <br>
RU **Russian**: Fluent<br>
KZ **Kazakh**: Native
<br>
##  💻 Technical Skills

**Languges** : Golang,JavaScript,C/C++,SQL(Postgres)<br>
**Developer Tools** : Git,Docker,VS Code

<details>
<summary> Example of code:</summary>
An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.<br>

```
function isIsogram(str){
  let newstr=str.toLowerCase();
  for (let i=0;i<newstr.length;i++){
    for(let j=0;j<newstr.length;j++){
      if (newstr[i] ==newstr[j] && i!=j){
        return false
      }
    }
  }
  return true
}
```




