<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankitha Chakali - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        /* CSS STYLES */
        :root {
            --primary-color: #007bff; /* Blue */
            --secondary-color: #6c757d; /* Gray */
            --background-color: #f8f9fa; /* Light Gray */
            --card-background: #ffffff; /* White */
            --text-color: #343a40; /* Dark Gray */
            --header-font: 'Poppins', sans-serif;
        }

        body {
            font-family: var(--header-font);
            margin: 0;
            padding: 0;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header & Hero Section */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 40px 0;
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            font-weight: 700;
            margin-bottom: 5px;
            font-size: 2.5em;
        }

        header p {
            font-style: italic;
            font-size: 1.1em;
            margin-top: 0;
        }
        
        /* Navigation */
        nav {
            background-color: #343a40;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
            transition: background-color 0.3s;
        }
        nav ul li a:hover {
            background-color: #0056b3;
        }


        /* Section Styling */
        section {
            padding: 40px 0;
        }

        h2 {
            color: var(--primary-color);
            text-align: center;
            margin-bottom: 30px;
            font-size: 2em;
            border-bottom: 3px solid var(--primary-color);
            display: inline-block;
            padding-bottom: 5px;
            width: fit-content;
            margin-left: auto;
            margin-right: auto;
            display: block;
        }

        /* Card and Grid Layouts */
        .card {
            background-color: rgb(255 255 128 / 0.5);;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .skills-grid, .education-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            text-align: center;
        }
        
        .skill-item {
            padding: 15px;
            background-color: #e9ecef;
            border-radius: 5px;
            font-weight: 600;
        }

        /* Project & Experience List */
        .experience-item {
            border-left: 4px solid var(--primary-color);
            padding-left: 20px;
            margin-top: 15px;
        }
        .experience-item h4 {
            margin: 0;
            font-size: 1.2em;
            color: var(--primary-color);
        }
        .experience-item small {
            color: var(--secondary-color);
            display: block;
            margin-bottom: 10px;
        }

        /* Education */
        .education-card h3 {
            color: var(--primary-color);
            margin-top: 0;
        }
        .education-card p {
            margin: 5px 0;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #343a40;
            color: white;
            margin-top: 40px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        /* Media Queries for Responsiveness */
        @media (max-width: 768px) {
            header {
                padding: 30px 10px;
            }
            header h1 {
                font-size: 2em;
            }
            .skills-grid, .education-grid {
                grid-template-columns: 1fr;
            }
            nav ul {
                flex-direction: column;
            }
            nav ul li a {
                text-align: center;
                padding: 10px;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Ankitha Chakali</h1>
            <p>Software Developer | Aspiring Innovator</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#vision">Vision</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        
        <section id="vision">
            <h2>🎯 Professional Vision</h2>
            <div class="card">
                <p>I am seeking a **growth-oriented, challenging position in software development** where I can apply my technical expertise and innovative thinking to create meaningful solutions. I am currently pursuing entry-level roles where I can contribute my skills and grow as a professional developer.</p>
            </div>
        </section>

        <hr>

        <section id="skills">
            <h2>💻 Core Competencies</h2>
            <div class="card">
                <p>I possess a strong foundation in both core programming concepts and web development technologies.</p>
                <div class="skills-grid">
                    <div class="skill-item">C, C++, Java, Python</div>
                    <div class="skill-item">HTML, CSS, JavaScript, Bootstrap</div>
                    <div class="skill-item">GitHub, Version Control, Debugging Tools</div>
                    <div class="skill-item">SQL, Database Management</div>
                    <div class="skill-item">Windows, Linux</div>
                    <div class="skill-item">AWS Cloud Computing</div>
                    <div class="skill-item">Salesforce Administration</div>
                </div>
            </div>
        </section>

        <hr>

        <section id="experience">
            <h2>🚀 Projects & Experience</h2>
            <div class="card">
                <h3>Intern Web Development (Interncall)</h3>
                <div class="experience-item">
                    <h4>Role: Intern Web Development</h4>
                    <small>Duration: 6 Months</small>
                    <ul>
                        <li>Gained hands-on experience building responsive, scalable applications.</li>
                    </ul>
                </div>
                
                <h3 style="margin-top: 30px;">Certifications & Specialized Knowledge</h3>
                <div class="experience-item">
                    <small>Full Stack Web Development (Interncall Company, 2023)</small>
                </div>
                <div class="experience-item">
                    <small>AWS Cloud Computing (Amazon Web Services, 2022)</small>
                </div>
                <div class="experience-item">
                    <small>Salesforce Administration (Salesforce Platform, 2022)</small>
                </div>
                <div class="experience-item">
                    <small>Cybersecurity (Tech Mehindra Foundation)</small>
                </div>
            </div>
        </section>

        <hr>
        
        <section id="education">
            <h2>🎓 Education & Foundation</h2>
            <div class="education-grid">
                <div class="card education-card">
                    <h3>Master of Computer Applications (MCA)</h3>
                    <p><strong>Ashoka Women's Engineering College, Kurnool</strong></p>
                    <p>Expected Graduation: 2025</p>
                    <p>CGPA: 8.20</p>
                </div>
                
                <div class="card education-card">
                    <h3>B.Sc (Mathematics, Statistics, Computer Science)</h3>
                    <p><strong>St. Joseph's Degree College, Kurnool</strong></p>
                    <p>Year: 2020-2023</p>
                    <p>CGPA: 8.0</p>
                </div>
            </div>
        </section>
        
        <hr>

        <section id="softskills">
            <h2>🌟 Soft Skills & Interests</h2>
            <div class="card">
                <p><strong>Key Soft Skills:</strong> Interpersonal Communication, Problem Solving, Collaboration, Active Listening, Adaptability, Leadership.</p>
                <p><strong>Interests:</strong> Playing Sports, Archery, Capturing Moments, Feeling the Music, Pursuing a career that aligns with my values and talents.</p>
            </div>
        </section>

    </div>

    <footer id="contact">
        <div class="container">
            <p>&copy; 2025 Ankitha Chakali. All rights reserved.</p>
            <p class="contact-info">
                Contact: 
                <a href="mailto:ankithachakalii@gmail.com">ankithachakalii@gmail.com</a> | 
                <a href="tel:+917013340991">+91-7013340991</a> | 
                Nandikotkur, Andhra Pradesh
            </p>
        </div>
    </footer>
    
    <script>
        // JAVASCRIPT for smooth scrolling (optional but nice)
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
