<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FSWD Course</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', 'Segoe UI', system-ui, sans-serif;
}

body {
    background: #fefefe;
    color: #2d3748;
    line-height: 1.7;
}

/* Header */
.header {
    background: linear-gradient(135deg, #f093fb 0%, #f5576c 50%, #f9844a 100%);
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.header h1 {
    font-size: clamp(2.2rem, 5vw, 3.2rem);
    font-weight: 700;
    margin-bottom: 12px;
    text-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.header p {
    font-size: 1.2rem;
    opacity: 0.95;
    max-width: 600px;
    margin: 0 auto;
}

/* Container */
.container {
    width: 90%;
    max-width: 1000px;
    margin: 0 auto 60px;
    padding: 0 20px;
}

/* Card */
.card {
    background: white;
    padding: 40px;
    margin-bottom: 30px;
    border-radius: 16px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.06);
    border: 1px solid #f7fafc;
    transition: all 0.3s ease;
}

.card:hover {
    box-shadow: 0 8px 30px rgba(0,0,0,0.1);
    transform: translateY(-4px);
}

.card h2 {
    color: #2d3748;
    font-size: 1.8rem;
    font-weight: 600;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 12px;
}

/* List */
.card ul {
    list-style: none;
    padding-left: 0;
}

.card ul li {
    margin: 14px 0;
    padding: 14px 18px;
    background: #fff5f5;
    border-left: 4px solid #f5576c;
    border-radius: 8px;
    transition: all 0.2s ease;
    font-size: 1rem;
}

.card ul li:hover {
    background: #ffe6e6;
    padding-left: 22px;
}

/* Form */
form input, 
form select, 
form textarea {
    width: 100%;
    padding: 16px 20px;
    margin: 12px 0;
    border: 2px solid #e2e8f0;
    border-radius: 12px;
    font-size: 16px;
    background: white;
    transition: all 0.2s ease;
    color: #2d3748;
}

form input::placeholder,
form textarea::placeholder {
    color: #a0aec0;
}

form input:focus, 
form select:focus, 
form textarea:focus {
    outline: none;
    border-color: #f5576c;
    box-shadow: 0 0 0 3px rgba(245, 87, 108, 0.1);
}

form select {
    cursor: pointer;
}

/* Button */
button {
    width: 100%;
    padding: 18px 24px;
    background: linear-gradient(135deg, #f5576c 0%, #f093fb 100%);
    border: none;
    color: white;
    font-size: 16px;
    font-weight: 600;
    border-radius: 12px;
    cursor: pointer;
    transition: all 0.3s ease;
    text-transform: uppercase;
    letter-spacing: 0.5px;
}

button:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 25px rgba(245, 87, 108, 0.3);
}

button:active {
    transform: translateY(0);
}

/* Footer */
.footer {
    text-align: center;
    padding: 30px;
    background: #2d3748;
    color: white;
    margin-top: 50px;
}

/* Responsive */
@media (max-width: 768px) {
    .header {
        padding: 60px 20px;
    }
    
    .card {
        padding: 30px 24px;
        margin-bottom: 25px;
    }
    
    .container {
        width: 95%;
    }
}

@media (max-width: 480px) {
    .header h1 {
        font-size: 2rem;
    }
    
    .header p {
        font-size: 1.1rem;
    }
    
    .card {
        padding: 24px 20px;
    }
    
    form input, form select, form textarea {
        padding: 14px 16px;
    }
}
</style>
</head>

<body>

<!-- Header -->
<div class="header">
    <h1>Full Stack Web Development</h1>
    <p>Master Frontend & Backend | Job Ready in 3 Months</p>
</div>

<!-- Main Container -->
<div class="container">

    <!-- About -->
    <div class="card">
        <h2>📚 Course Curriculum</h2>
        <p style="margin-bottom: 25px; color: #718096; font-size: 1.1rem;">
            Complete Full Stack Developer training with industry projects.
        </p>

        <ul>
            <li>HTML5, CSS3, JavaScript (ES6+)</li>
            <li>React.js, Tailwind CSS</li>
            <li>Node.js, Express.js APIs</li>
            <li>MongoDB & PostgreSQL</li>
            <li>Git, Docker, Deployment</li>
            <li>Interview Prep + Certificate</li>
        </ul>
    </div>

    <!-- Form -->
    <div class="card">
        <h2>🎯 Enroll Today</h2>

        <form>
            <input type="text" placeholder="Full Name" required>
            <input type="email" placeholder="Email Address" required>
            <input type="tel" placeholder="Phone Number" required>

            <select required>
                <option value="">Select Qualification</option>
                <option>B.Tech / B.E</option>
                <option>BCA / B.Sc (CS/IT)</option>
                <option>MCA / M.Tech</option>
                <option>Working Professional</option>
            </select>

            <textarea rows="4" placeholder="Why Full Stack Development?"></textarea>

            <button type="submit">Join Now - Limited Seats</button>
        </form>
    </div>

</div>

<!-- Footer -->
<div class="footer">
    © 2024 FSWD Academy | Building Future Full Stack Developers
</div>

</body>
</html>
