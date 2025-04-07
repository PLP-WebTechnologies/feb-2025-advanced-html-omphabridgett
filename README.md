<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Heritage Registration Page</title>
</head>
<body>
  <!-- Ordered List with Roman Numerals -->
  <h2>Steps to Preserve Heritage</h2>
  <ol type="I">
    <li>Identify cultural elements</li>
    <li>Promote education and awareness</li>
    <li>Involve local communities</li>
    <li>Document traditions and stories</li>
    <li>Support conservation initiatives</li>
  </ol>

  <!-- External Image from Pexels -->
  <h2>Heritage Image</h2>
  <img src="https://images.pexels.com/photos/158607/cairn-fog-mystical-background-158607.jpeg" alt="Heritage Scene" width="500">

  <!-- Table of Contacts -->
  <h2>Contact Directory</h2>
  <table border="1" cellpadding="10">
    <tr>
      <th>Name</th>
      <th>Address</th>
      <th>Mobile</th>
      <th>Email</th>
    </tr>
    <tr>
      <td>John Doe</td>
      <td>123 Heritage Rd</td>
      <td>0123456789</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Mary Smith</td>
      <td>456 Culture St</td>
      <td>0987654321</td>
      <td>mary@example.com</td>
    </tr>
    <tr>
      <td>Sipho Nkosi</td>
      <td>789 Legacy Ave</td>
      <td>0671234567</td>
      <td>sipho@example.com</td>
    </tr>
    <tr>
      <td>Nomsa Dlamini</td>
      <td>321 Memory Ln</td>
      <td>0812345678</td>
      <td>nomsa@example.com</td>
    </tr>
    <tr>
      <td>Thabo Mokoena</td>
      <td>555 Tradition Blvd</td>
      <td>0723456789</td>
      <td>thabo@example.com</td>
    </tr>
  </table>

  <!-- Registration Form -->
  <h2>Registration Form</h2>
  <form>
    <!-- Name -->
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

    <!-- Email -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="example@email.com" required><br><br>

    <!-- Password -->
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter password" minlength="6" required><br><br>

    <!-- Date -->
    <label for="date">Date of Birth:</label>
    <input type="date" id="date" name="dob" required><br><br>

    <!-- Dropdown -->
    <label for="country">Country:</label>
    <select id="country" name="country" required>
      <option value="">--Select--</option>
      <option value="za">South Africa</option>
      <option value="ng">Nigeria</option>
      <option value="ke">Kenya</option>
      <option value="gh">Ghana</option>
    </select><br><br>

    <!-- Radio Buttons -->
    <p>Gender:</p>
    <input type="radio" id="male" name="gender" value="male" required>
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br><br>

    <!-- Checkboxes -->
    <p>Select your interests:</p>
    <input type="checkbox" id="history" name="interest" value="History">
    <label for="history">History</label>
    <input type="checkbox" id="culture" name="interest" value="Culture">
    <label for="culture">Culture</label>
    <input type="checkbox" id="art" name="interest" value="Art">
    <label for="art">Art</label><br><br>

    <!-- Submit -->
    <button type="submit">Register</button>
  </form>
</body>
</html>

