# ayushsharma2013.github.io
My personal website, built at GDG Jammu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayush Sharma - Resume</title>
    <style>
        /* CSS RESET & VARIABLES */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
            --primary-color: #2563eb;
            --primary-hover: #1d4ed8;
            --text-dark: #0f172a;
            --text-muted: #475569;
            --border-color: #e2e8f0;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.05);
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-dark);
            line-height: 1.6;
            padding: 16px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        section {
            background-color: var(--card-bg);
            padding: 24px;
            border-radius: 12px;
            margin-bottom: 20px;
            border: 1px solid var(--border-color);
            box-shadow: var(--shadow);
        }

        h2 {
            font-size: 1.25rem;
            color: var(--text-dark);
            margin-bottom: 12px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 6px;
        }

        p {
            color: var(--text-muted);
        }

        /* HEADER SECTION STYLES */
        header {
            background-color: var(--card-bg);
            padding: 32px 24px;
            border-radius: 12px;
            text-align: center;
            margin-bottom: 20px;
            border: 1px solid var(--border-color);
            box-shadow: var(--shadow);
        }

        header h1 {
            font-size: 2rem;
            color: var(--text-dark);
            margin-bottom: 4px;
        }

        header p {
            font-size: 1rem;
            color: var(--primary-color);
            font-weight: 500;
        }

        /* SKILLS SECTION STYLES */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            list-style: none;
        }

        .skill-tag {
            background-color: #eff6ff;
            color: var(--primary-color);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
            border: 1px solid #bfdbfe;
        }

        /* PROJECTS SECTION STYLES */
        .project-card {
            background-color: var(--bg-color);
            padding: 16px;
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }

        .project-card h3 {
            font-size: 1.1rem;
            color: var(--text-dark);
            margin-bottom: 6px;
        }

        /* CONTACT SECTION STYLES */
        .contact-links {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .contact-item {
            color: var(--text-muted);
            text-decoration: none;
            word-break: break-all;
        }

        .contact-item strong {
            color: var(--text-dark);
        }

        .contact-item a {
            color: var(--primary-color);
            text-decoration: none;
        }

        .contact-item a:hover {
            text-decoration: underline;
        }

        /* RESPONSIVE DESIGN (FOR LAPTOPS & DESKTOPS) */
        @media (min-width: 640px) {
            body {
                padding: 40px 20px;
            }

            header h1 {
                font-size: 2.5rem;
            }

            .contact-links {
                flex-direction: row;
                justify-content: space-between;
            }
        }
    </style>
</head>
<body>

    <div class="container">

        <!-- HEADER SECTION -->
        <header>
            <h1>Ayush Sharma</h1>
            <p>Student & Developer</p>
        </header>

        <!-- ABOUT SECTION -->
        <section id="about">
            <h2>About Me</h2>
            <p>My name is Ayush from class 7th. I attend Model Academy High School Kalideh and I enjoy learning new computer technologies.</p>
        </section>

        <!-- SKILLS SECTION -->
        <section id="skills">
            <h2>Skills</h2>
            <ul class="skills-list">
                <li class="skill-tag">Python</li>
            </ul>
        </section>

        <!-- PROJECTS SECTION -->
        <section id="projects">
            <h2>Projects</h2>
            <div class="project-card">
                <h3>Web Creation</h3>
                <p>Designing and building modern, responsive single-page websites using clean HTML and CSS.</p>
            </div>
        </section>

        <!-- CONTACT SECTION -->
        <section id="contact">
            <h2>Contact</h2>
            <div class="contact-links">
                <div class="contact-item">
                    <strong>Email:</strong> 
                    <a href="mailto:ayushsharma4957@gmail.com">ayushsharma4957@gmail.com</a>
                </div>
                <div class="contact-item">
                    <strong>GitHub:</strong> 
                    <a href="https://github.com/ayushsharma" target="_blank" rel="noopener">github.com/ayushsharma</a>
                </div>
            </div>
        </section>

    </div>

</body>
</html>
