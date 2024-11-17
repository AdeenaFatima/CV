<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>

         {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            background-color: white;
            padding: 20px;
        }

        .container {
            display: flex;
            max-width: 900px;
            width: 100%;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.8);
            border-radius: 8px;
        }


        .sidebar {
            width: 30%;
            background-color: rgb(31, 29, 29);
            color: white;
            padding: 20px;
            border-radius: 8px 0 0 8px;
            text-align: center;
        }

        .sidebar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 15px;
            border: 3px solid green;
        }

        .sidebar h1 {
            font-size: 24px;
            margin: 10px 0;
        }

        .sidebar p {
            font-size: 16px;
            margin-bottom: 15px;
            color: rgb(131, 131, 131);
        }

        .contact-info {
            text-align: left;
            margin-top: 20px;
        }

        .contact-info div {
            margin-bottom: 10px;
            font-size: 14px;
            color: rgb(131, 131, 131);
        }

        .main-content {
            width: 70%;
            padding: 20px;
        }

        .main-content h2 {
            font-size: 20px;
            color: rgb(5, 5, 4);
            border-bottom: 2px solid rgb(4, 7, 4);
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        .section {
            margin-bottom: 20px;
        }

        .section p,
        .section ul {
            font-size: 16px;
            line-height: 1.6;
            color: rgb(26, 23, 23);
        }

        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            padding: 12px;
            text-align: left;
            border: 1px solid rgb(0, 0, 0);
        }
        th {
            background-color: rgb(0, 0, 0);
            color: white;
        }
        caption {
            font-size: 1.4em;
            font-weight: bold;
            margin-bottom: 10px;
        }

    </style>
</head>
<body>

<div class="container">

    <div class="sidebar">
        <img src="ProfilePicture.jpg" alt="Profile Picture" style="margin: 30px 0px 0px 0px; width: 160px; height: 160px;">
        <div class="contact-info"style="margin: 1400px 0px 0px 0px;">
          
            <div><strong>📧 Email:</strong> adeena346@gmail.com</div>
            <div><strong>📞 Phone:</strong> +311 4317390</div>
            <div><strong>🔗 LinkedIn:</strong>linkedin.com/AdeenaFatima</div>
            <div><strong>🐙 GitHub:</strong> github.com/youruse</div>
        </div>
    </div>

    <div class="main-content">
        <h1><strong>ADEENA FATIMA</strong></h1>
        <section class="section">
            <h2>Educational Background</h2>
            <p><li>Bachelor in Computer Science</li>
                University of Management and Technology, Lahore, Pakistan
                2023 – 2027
                
                <li>FSc Pre-Medical</li>
                Unique Group of Institutions, Lahore, Pakistan
                2020 – 2022
                
                <li>Matric (Science)</li>
                Unique Group of Institutions, Lahore, Pakistan</p>
        </section>

        <section class="section">
            <h2>Work Experience</h2>
            <ul>
                <strong></strong> 
                <p> Currently employed as a <strong>Web Developer</strong> in the industry, focusing on front-end and back-end integration, enhancing user experience, and implementing new features.
                    Gained practical experience through multiple internships during my degree, where I worked with <strong>HTML, CSS, JavaScript, and frameworks like React and Node.js</strong> to develop responsive and user-friendly websites.
                </p>
            </ul>
        </section>

        <section class="section">
            <h2>Technical Skills</h2>
            <ul>
                <li>Programming Languages: Python, JavaScript</li>
                <li>Digital Marketing</li>
                <li>Innovative Probkem solving</li>
                <li>Leadership skills</li>
                <li>Excellent Communication Skills</li>
            </ul>
        </section>

        <section class="section">
            <h2>Professional competencies</h2>
            <table>
                                <tr>
                    <th>Category</th>
                    <th>Details</th>
                </tr>
                <tr>
                    <td>Time Management</td>
                    <td>Efficient in meeting project deadlines and managing priorities.</td>
                </tr>
                <tr>
                    <td>Development</td>
                    <td>Skilled in designing and developing responsive, user-friendly web interfaces.</td>
                </tr>
                <tr>
                    <td>Version Control</td>
                    <td>Experienced for maintaining code quality and project collaboration.</td>
                </tr>
                <tr>
                    <td>Database Management</td>
                    <td>Familiar with MySQL and MongoDB for efficient data storage and retrieval.</td>
                </tr>
            </table>
        </section>
        <section class="section">
            <h2>Life Goals</h2>
            <ul>
                <li>Become a successful software engineer</li>
                <li>Achieve financial stability through smart investments</li>
                <li>Mentor and volunteer in tech educutaion</li>
                <li>Travel and explore new cultures</li>
                <li>Learn new languages or skills for personal and professional growth</li>

          </ul>
        </section>
        <section class="section">
            <h2>Personal Interests</h2>
            <ul>
                <li>Reading exploring imaginative stories</li>
                <li>Exploring photography and capturing unique moments</li>
                <li>Engaging in outdoor activities like bedminton</li>
                <li>Participating in community events or volunteering</li>


            </ul>
        </section>

        <section class="section">
            <h2>AUDIO</h2>
            <audio controls>
          <source src="https://www.youtube.com/watch?v=i8kgJv8ykho" type="audio/ogg">
         
        </audio>
        </section>
    
        <section class="section">
            <h2>VIDEO</h2>
            <video width="320" height="200" controls>
          <source src="https://www.youtube.com/watch?v=u28MASoZGtM" type="video/mp4">
          
        </video>
        </section>
    </div>
</div>

</body>
</html>
