# 🌐 Personal Portfolio Website

This is my personal portfolio website built using **HTML** and **CSS**. It includes sections like **About Me**, **Projects**, and **Skills** — everything you need to know about me in one place!

---

## 🧑‍💻 About Me

Hi! I’m **N. Sharan**, a first-year undergraduate student at **IIT Kharagpur**, pursuing a B.Tech in Electrical Engineering. I enjoy web development and am currently learning **C** and **JavaScript** to enhance my skills further.

---

## 🔧 Tech Stack Used

- ✅ HTML5  
- ✅ CSS3  
- 🚧 (Learning): JavaScript & C

---

## 📁 Folder Structure
<!DOCTYPE html>
<html lang="en">
<h<img width="676" alt="img1" src="https://github.com/user-attachments/assets/c4d6c21c-68d8-4b97-9fc5-ef5cef6d4b97" />
ead>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Verdana, Arial, Helvetica, sans-serif;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        nav {
            background-color: rgb(193, 213, 63);
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        main {
            flex-grow: 1;
            padding: 20px;
        }

        #boys {
            text-align: center;
            margin-bottom: 20px;
            
            padding: 10px;
            border-radius: 8px;
        }

        .good {
    margin: 20px auto;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Soft Shadow */
    width: 380px;
    height: auto;
    display: flex;
    align-items: center;
    background-color: #FAF3E0;  /* Background */
    color: #3D405B;
    border-radius: 10px;
    cursor: pointer;
    transition: transform 0.3s, background-color 0.3s, box-shadow 0.3s;
}

.good:hover {
    transform: scale(1.02); /* Slightly grows */
    background-color: #81B29A; /* Secondary Accent */
    color: white;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3); /* Enhanced Shadow */
    border: 2px solid #3D405B;
}

.good img {
    width: 150px;
    height: 150px;
    margin-top: 15px;
    border: 2px solid #3D405B
    
}


        .buttons {
            padding: 10px 20px;
            border-radius: 5px;
            border: none;
            background-color: rgb(195, 133, 53);
            color: black;
            cursor: pointer;
            font-weight: bolder;
            margin: 10px 0;
            display: flex;
            justify-content: center;
            
        }

        .buttons:hover {
            transform: scale(1.02); /* Slightly grows */
    background-color: #2b9358; /* Secondary Accent */
    color: white;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3); /* Enhanced Shadow */
    border: 2px solid #3D405B;
}
.buttons:active {
    transform: scale(0.98); /* Slightly shrinks */
    background-color: #1a5d3d; /* Darker shade for click effect */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

        footer {
            background-color: #493c3c;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer div {
            margin-bottom: 10px;
        }
        .head{
            font-family: Arial, Helvetica, sans-serif;
            background-color: #674747;
            color: white;
            border-radius: 10px;
            padding-bottom: 10px;
            padding-top: 10px;
            border: 2px solid #d8d9e7;
        }
        .projects {
    transform: scale(1.03);
    margin: 40px auto;
    padding: 30px;
    background-color: #f0deab;
    border-radius: 10px;
    width: 80%;
    border: 2px solid #3D405B;
    transition: transform 0.3s, background-color 0.3s, box-shadow 0.3s;
}

.projects:hover {
    box-shadow: 0  20px 20px rgba(0, 0, 0, 0.2);
    background-color: #e6c982;
}
.project-card {
    padding: 15px;
    margin-bottom: 15px;
    border: 2px solid #3D405B;
    border-radius: 8px;
    background-color: white;
    transition: transform 0.3s, background-color 0.3 , box-shadow 0.3s;
}

.project-card:hover {
    transform: scale(1.02);
    background-color: #E07A5F;
    color: white;
}
.my{
    padding-bottom: 10px;
}
    </style>
</head>
<body>
    <!-- Navbar placed outside main to always stay on top -->
    <nav>
        <ul>
            <li><button class="buttons">HOME</button></li>
            <li><button class="buttons">ABOUT ME</button></li>
            <li><button class="buttons">MY PROJECTS</button></li>
            <li><button class="buttons">CONTACTS</button></li>
        </ul>
    </nav>

    <main>
        <div id="boys">
            <h1 class="head">my portfolio</h1>
        </div>

        <div class="good">
            <p>
                “Hello everyone, I am N. Sharan, a first-year undergraduate pursuing a B.Tech degree in Electrical Engineering at IIT Kharagpur. I am currently residing in LBS Hall, where I have been staying for the past six months.”

            </p>
            <img src="img1.png" alt="my face">
        </div>


        <div class="projects">
            <h2 class="my">My Projects</h2>
            
            <div class="project-card">
                <h3>HTML & CSS Portfolio Page</h3>
                <p>This is the very page you are viewing! Built with HTML and CSS, showcasing all my projects in a clean, responsive layout.</p>
            </div>
            </div>
           
        </div>
        <div class="projects">
            <h2 class="my">My skills</h2>
            
            <div class="project-card">
                <h3>PROFICIENT IN HTML AND CSS</h3>
                <p>I am proficient in HTML and CSS, with experience in creating responsive and visually appealing web pages.
                    Currently, I am expanding my skill set by learning C for programming fundamentals and JavaScript to enhance web development capabilities.”.</p>
            </div>
            
        </div>
    </main>

    <footer>
        <div>
            <h3>Contact Us</h3>
            <p>Phone: 7093842006</p>
            <p>Email: sharan.12.new@email.com</p>
        </div>
        <div>
            &copy; 2025 All Rights Reserved
        </div>
    </footer>
</body>
</html>
