<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kunjan Shrimali | DevOps Engineer</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            padding: 60px 0;
        }

        header {
            background: #0f172a;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
            color: #cbd5e1;
        }

        h2 {
            margin-bottom: 20px;
            color: #0f172a;
            border-left: 5px solid #2563eb;
            padding-left: 10px;
            font-size: 26px;
        }

        .about p {
            max-width: 800px;
        }

        .skill-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.05);
            transition: 0.3s ease;
        }

        .card:hover {
            transform: translateY(-6px);
        }

        .card h3 {
            margin-bottom: 12px;
            color: #2563eb;
        }

        ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        .achievements ul li {
            margin-bottom: 10px;
        }

        .contact p {
            margin-bottom: 8px;
        }

        footer {
            background: #0f172a;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 30px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Kunjan Shrimali</h1>
    <p>DevOps Engineer | Cloud Architect | Web Developer</p>
</header>

<section class="about container">
    <h2>About Me</h2>
    <p>
        I am a results-driven DevOps and Cloud Engineer specializing in AWS, Azure,
        CI/CD pipelines, containerization, and scalable infrastructure design.
        I focus on automation, system reliability, and production-grade deployments.
    </p>
</section>

<section class="skills container">
    <h2>Technical Skills</h2>
    <div class="skill-grid">
        <div class="card">
            <h3>Cloud Platforms</h3>
            <ul>
                <li>AWS</li>
                <li>Microsoft Azure</li>
                <li>Google Cloud</li>
            </ul>
        </div>

        <div class="card">
            <h3>DevOps & Tools</h3>
            <ul>
                <li>Docker</li>
                <li>Kubernetes</li>
                <li>Jenkins</li>
                <li>GitHub Actions</li>
                <li>Terraform</li>
                <li>Linux</li>
            </ul>
        </div>

        <div class="card">
            <h3>Programming</h3>
            <ul>
                <li>Python</li>
                <li>PHP</li>
                <li>JavaScript</li>
                <li>Bash</li>
                <li>SQL</li>
            </ul>
        </div>
    </div>
</section>

<section class="achievements container">
    <h2>Key Achievements</h2>
    <ul>
        <li>Designed and implemented complete CI/CD pipelines</li>
        <li>Deployed scalable cloud infrastructure on AWS & Azure</li>
        <li>Containerized and managed Kubernetes applications</li>
        <li>Automated deployment workflows for web projects</li>
        <li>Configured secure Linux-based production servers</li>
    </ul>
</section>

<section class="contact container">
    <h2>Contact</h2>
    <p>Email: yourmail@gmail.com</p>
    <p>GitHub: github.com/KunjanShrimali</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
</section>

<footer>
    <p>© 2026 Kunjan Shrimali. All Rights Reserved.</p>
</footer>

</body>
</html>
