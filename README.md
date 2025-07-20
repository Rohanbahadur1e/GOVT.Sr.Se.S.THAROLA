<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Govt. Sr. Sec. School Tharola - Admission 2025</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #003366;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 0 10px #ccc;
    }
    h2 {
      color: #004080;
    }
    form input, form select, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #004080;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #003366;
    }
    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Govt. Senior Secondary School, Tharola</h1>
    <p>Admission Portal 2025 - Arts Stream</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#admission">Admission Info</a>
    <a href="#form">Apply Online</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="admission">
    <h2>Admission Information</h2>
    <p><strong>Available Classes:</strong> 6th to 12th (Arts Stream Only)</p>
    <p><strong>Admission Starts:</strong> 15 March 2025</p>
    <p><strong>Last Date:</strong> 10 May 2025</p>
    <p><strong>Required Documents:</strong></p>
    <ul>
      <li>Birth Certificate</li>
      <li>Previous Class Marksheet</li>
      <li>Aadhar Card</li>
      <li>2 Passport-size Photos</li>
    </ul>
    <p><strong>Note:</strong> Admission based on merit & seat availability.</p>
  </div>

  <div class="container" id="form">
    <h2>Online Admission Form</h2>
    <form action="https://formspree.io/f/mnnzjvbn" method="post">
      <label for="name">Full Name:</label>
      <input type="text" name="Name" id="name" placeholder="Enter your full name" required>

      <label for="dob">Date of Birth:</label>
      <input type="date" name="Date of Birth" id="dob" required>

      <label for="class">Class for Admission:</label>
      <select name="Class" id="class" required>
        <option value="">-- Select Class --</option>
        <option value="6th">6th</option>
        <option value="7th">7th</option>
        <option value="8th">8th</option>
        <option value="9th">9th</option>
        <option value="10th">10th</option>
        <option value="11th (Arts)">11th (Arts)</option>
        <option value="12th (Arts)">12th (Arts)</option>
      </select>

      <label for="father">Father's Name:</label>
      <input type="text" name="Father's Name" id="father" placeholder="Enter father's full name" required>

      <label for="aadhar">Aadhar Number:</label>
      <input type="text" name="Aadhar Number" id="aadhar" pattern="\d{12}" maxlength="12" placeholder="12-digit Aadhar Number" title="Enter 12-digit Aadhar Number" required>

      <label for="mobile">Mobile Number:</label>
      <input type="tel" name="Mobile Number" id="mobile" pattern="[6-9]{1}[0-9]{9}" maxlength="10" placeholder="10-digit Mobile Number" title="Enter valid 10-digit mobile number" required>

      <label for="email">Your Email:</label>
      <input type="email" name="Email" id="email" placeholder="Enter your email" required>

      <button type="submit">Submit Admission Form</button>
    </form>
  </div>

  <footer id="contact">
    <p>Contact Number: <strong>8679191976</strong></p>
    <p>Email: <strong>r40532162@gmail.com</strong></p>
    <p>© 2025 Govt. Senior Secondary School, Tharola</p>
  </footer>

</body>
</html>
