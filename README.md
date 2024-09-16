<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Hrishikesh Nirgude Portfolio">
    <link rel="stylesheet" href="styles.css">
    <title>Hrishikesh Nirgude - Portfolio</title>
</head>
<body>
    <header>
        <div class="container">
            <h1>Hrishikesh Nirgude</h1>
            <p>Master of Science in Mechatronics and Robotics Engineering</p>
            <p>Email: <a href="mailto:hnirgude@wpi.edu">hnirgude@wpi.edu</a> | <a href="https://www.linkedin.com/in/hrishikesh-nirgude-380746173" target="_blank">LinkedIn</a> | +1 (774) 5256539</p>
        </div>
    </header>
    
    <main>
        <section id="education">
            <h2>Education</h2>
            <div class="section-content">
                <h3>Worcester Polytechnic Institute</h3>
                <p>Master of Science in Mechatronics and Robotics Engineering</p>
                <p>August 2024 – Present</p>
                <h3>College of Engineering Pune (COEP)</h3>
                <p>Bachelor of Technology in Mechanical Engineering</p>
                <p>August 2016 – May 2020</p>
            </div>
        </section>
        
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Programming Languages: C++, Python, MATLAB, C, Arduino</li>
                <li>Technical Skills: Docker, ROS2, OMPL, PyTorch, Sensor Integration, Embedded Programming, etc.</li>
                <li>CAD/FEA Software: SolidWorks, AutoCAD, ANSYS</li>
                <li>Manufacturing and Fabrication: CNC Router, Casting, 3D Printing</li>
            </ul>
        </section>
        
        <section id="experience">
            <h2>Industrial Work Experience (3 - 4 years)</h2>
            <div class="section-content">
                <h3>TATA – Senior Engineer</h3>
                <p>Product: Automatic Transmission System | March 2024 – August 2024</p>
                <ul>
                    <li>Managed cross-functional teams, launched initiatives saving $3.5M annually.</li>
                    <li>Automated cost-up idea generation workflow, achieving $1.2M in savings.</li>
                </ul>
                
                <h3>Eaton – Design Engineer</h3>
                <p>Product: Mobility division | April 2021 – March 2024</p>
                <ul>
                    <li>Led launch of 5 products, saving $500K.</li>
                    <li>Reduced development cycle by 50% using advanced simulations.</li>
                </ul>
            </div>
        </section>
        
        <section id="projects">
            <h2>Research Projects and Academic Work</h2>
            <ul>
                <li><strong>Modular Snake Robot</strong>: Humanoid arm inspired design using Denavit-Hartenberg approach for forward kinematics.</li>
                <li><strong>Stewart Platform Mechanism</strong>: Execution and simulation for aerospace engineering applications.</li>
            </ul>
        </section>
        
        <section id="awards">
            <h2>Leadership / Awards / Honors</h2>
            <ul>
                <li>Worcester Polytechnic Institute - Teaching Assistant</li>
                <li>Asia-Pacific Broadcasting Union - Best Aesthetic Robot</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>© 2024 Hrishikesh Nirgude. All Rights Reserved.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
}

main {
    padding: 20px;
    background-color: #fff;
    margin-top: 20px;
    border-radius: 5px;
}

h2 {
    color: #333;
    margin-bottom: 10px;
}

.section-content {
    margin-bottom: 30px;
}

ul {
    list-style-type: square;
    margin: 10px 0;
    padding-left: 20px;
}

ul li {
    margin-bottom: 5px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 30px;
}
