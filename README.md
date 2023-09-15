# FirstDemoProject
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PassX - personal password manger</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <div class="logo">
            PassX
        </div>
       <ul>
        <li>Home</li>
        <li>About</li>
        <li>Contact</li>
        <li>More</li>
       </ul>
    </nav>
    <div class="container">
        <h1>Password Manager</h1>
        <p>
            Welcome to your Password Manager
Manage your saved passwords in Android or Chrome. They’re securely stored in your passX Account and available across all your devices.
        </p>
        <h2>Your Password</h2>
        <table border="1">
            <tr>
                <th>Website</th>
                <th>Username</th>
                <th>Password</th>
                <th>Delete</th>
            </tr>
            
        </table>
        <h2>Add a Password</h2>
        <form action="/submit" method="post">
            <!-- Text input for username -->
            <label for="Website">Website:</label>
            <input type="text" id="Website" name="Website" required>
            <br><br>
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required> <br><br>
            
        
            <!-- Password input -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <br>
            <button type="submit" class="btn">Submit</button>
  </form>
    </div>
    <script src="script.js"></script>
</body>
</html>
