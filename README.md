<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeJob Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #007bff; /* Background color for the whole page */
            color: #333; /* Default text color */
        }

        header {
            background: #007bff;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background: #53f469;
            color: #fff;
            padding: 0.5rem;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .text-section {
            max-width: 50%;
            color: #fff; /* Change paragraph text color to white */
        }

        .text-section h2 {
            margin-bottom: 1rem;
            color: #fff; /* Heading color in the text section */
        }

        .image-section {
            max-width: 45%;
        }

        .image-section img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(174, 4, 4, 0.1);
        }

        .resume-upload {
            margin-top: 2rem;
            text-align: center;
        }

        .resume-upload h3 {
            margin-bottom: 1rem;
            color: #fff; /* Heading color in the resume upload section */
        }

        .resume-upload input[type="file"] {
            padding: 0.5rem;
            margin-bottom: 1rem;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .resume-upload button {
            padding: 0.5rem 1rem;
            background: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .resume-upload button:hover {
            background: #c50d26;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: #2450a1;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .top-address {
            text-align: center;
            margin: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>CodeJob Company</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#jobs">Jobs</a>
        <a href="#employer">Employer Dashboard</a>
        <a href="#candidate">Candidate Dashboard</a>
    </nav>

    <div class="container">
        <div class="text-section">
            <h2>Welcome to CodeJob Company</h2>
            <p>CodeJob Company, we're thrilled to announce that we're hiring freshers who are eager to start their
                journey in the tech world. If you're a recent graduate looking to apply your skills and grow in a
                 supportive environment, we want to hear from you! Submit your resume today and join a team where 
                 your potential can thrive.</p>
        </div>
        <div class="image-section">
            <img src="devi.jpg" alt="Company Image">
        </div>
    </div>

    <div class="resume-upload">
        <h3>Upload Your Resume</h3>
        <button>Upload</button>
    </div>

    <footer>
        <p>&copy; 2024 CodeJob Company</p>
        <p><a href="#top" style="color: white;">Back to top</a></p>
    </footer>
</body>
</html>
