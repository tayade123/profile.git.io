# profile.git.io
![react](https://github.com/user-attachments/assets/76df8b91-089f-4595-ac8a-bde00bec42fb)
![python](https://github.com/user-attachments/assets/b59a3dc3-8ea6-4938-97a6-235cc0791e68)
![project2](https://github.com/user-attachments/assets/7e70110b-bcea-4ec5-8e9d-4454e69eeb53)
![project1](https://github.com/user-attachments/assets/ec33c078-e5f9-4d06-9de9-1bd7f5a9ed3d)
![profile](https://github.com/user-attachments/assets/539afa38-b924-4438-aea2-09d7a01ebc34)
![java](https://github.com/user-attachments/assets/b58f0626-c18c-4c9a-a4ed-62ee557c01ed)
![html](https://github.com/user-attachments/assets/ab18f9a5-980b-472e-abb4-0d656f6cad0f)
![css](https://github.com/user-attachments/assets/8bb1a403-8eae-49b9-adea-2fc39235543d)
![cpp](https://github.com/user-attachments/assets/5579a9f1-de0a-43fa-b6ae-89ff62f223c4)
![java](https://github.com/user-attachments/assets/0bcd6680-e35f-45c6-a011-123dd73a92f9)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Developer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.min.js"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
            transition: all 0.3s ease-in-out;
        }
        header {
            background-color: #4a90e2;
            color: white;
            padding: 20px;
            font-size: 24px;
            font-weight: 600;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            flex-wrap: wrap;
            animation: slideDown 1s ease-out;
        }
        @keyframes slideDown {
            from {
                transform: translateY(-100px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid white;
            margin-top: 30px;
            margin-right: 15px;
            border: 5px solid transparent;
    background: linear-gradient(white, white) padding-box,
                linear-gradient(45deg, #1b1b1b, #fad0c4) border-box;
    border-radius: 50%;
        }
        .header-left {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        nav {
            display: flex;
            gap: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: 500;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffd700;
        }
        #about, #skills, #projects, #contact {
            padding: 40px;
            animation: fadeIn 1s ease-in;
        }
        #about {
            background: white;
            padding: 40px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            width: 60%;
            margin: 20px auto;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
            padding: 20px;
            justify-items: center;
        }
        .skill {
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 120px;
            transition: transform 0.3s;
        }
        .skill:hover {
            transform: translateY(-5px);
        }
        #projects {
            padding: 40px;
            background: #fff;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            width: 80%;
            margin: 20px auto;
        }
        .project img {
            width: 100%;
            max-width: 400px;
            border-radius: 8px;
        }
        #contact {
            background: #ffffff;
            padding: 50px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            width: 40%;
            margin: 40px auto;
            text-align: left;
        }
        #contact input, #contact textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        #contact button {
            background-color: #4a90e2;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            transition: background 0.3s;
        }
        #contact button:hover {
            background-color: #357ABD;
        }
        footer {
            background: #4a90e2;
            color: white;
            padding: 20px;
            margin-top: 40px;
            text-align: center;
            font-size: 16px;
            font-weight: 500;
        }
        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                text-align: center;
            }
            nav {
                flex-direction: column;
                gap: 10px;
                margin-top: 10px;
            }
            #about, #projects, #contact {
                width: 90%;
            }
            .skills-grid {
                grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            }
        }
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        .skill:hover {
            transform: scale(1.1);
            transition: transform 0.3s ease-in-out;
        }
        #contact button:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        <div class="header-left">
            
            Jagdish Tayade | Software Developer
        </div>
        <nav>
            <a href="#about">About Me</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact Me</a>
        </nav>
    </header>

    <img  src="profile.jpg" alt="Profile Photo" class="profile-img">
    <section id="about" class="fade-in">
        <h2>About Me</h2>
        <p>"As a passionate and detail-oriented software developer, I specialize in designing, developing, 
            and optimizing applications that solve real-world problems. With expertise in multiple programming languages,
            frameworks, and technologies, I thrive on writing clean, efficient, and scalable code. Whether working on 
            front-end interfaces, back-end systems, or full-stack development, I am committed to delivering high-quality 
            solutions that enhance user experience and drive innovation. Always eager to learn and stay updated with the 
            latest industry trends, I enjoy collaborating with teams to build robust and cutting-edge software applications."</p>
    </section>
    <section id="skills" class="fade-in">
        <h2>Skills</h2>
        <div class="skills-grid">
            <div class="skill"><img src="html.png" alt="HTML"><br>HTML</div>
            <div class="skill"><img src="css.png" alt="CSS"><br>CSS</div>
            <div class="skill"><img src="react.png" alt="React.js"><br>React.js</div>
        </div>
        <div class="skills-grid">
            <div class="skill"><img src="java.png" alt="Java"><br>Java</div>
            <div class="skill"><img src="python.png" alt="Python"><br>Python</div>
            <div class="skill"><img src="cpp.png" alt="C/C++"><br>C/C++</div>
        </div>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <p>Project 1 - A web application built using html and css.</p>
            <p>Project 1 - A web application live demo Link <a href="https://tayade123.github.io/lovegame.git.io/">Click Me</a></p>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <p>Project 2 - A dynamic website powered by Python and Django.</p>
            <p>Project 1 - A web application live demo Link <a href="https://tayade123.github.io/Gym-Website/">Click Me</a></p>
        </div>
    </section>
    <section id="contact" class="fade-in">
        <h2>Contact Me</h2>
        <form action="mailto:tayadejagdish673@gmail.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        © 2025 Jagdish Tayade | All Rights Reserved
    </footer>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const sections = document.querySelectorAll(".fade-in");
            function reveal() {
                sections.forEach(section => {
                    const top = section.getBoundingClientRect().top;
                    if (top < window.innerHeight * 0.85) {
                        section.classList.add("visible");
                    }
                });
            }
            window.addEventListener("scroll", reveal);
            reveal();
        });
    </script>
</body>
</html>
