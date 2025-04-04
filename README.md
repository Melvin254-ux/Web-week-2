
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Ordered List with Roman Numerals -->
        <section>
            <h2>Ordered List with Roman Numerals</h2>
            <ol type="I">
                <li>Item One</li>
                <li>Item Two</li>
                <li>Item Three</li>
                <li>Item Four</li>
                <li>Item Five</li>
            </ol>
        </section>

        <!-- External Image from Pexels -->
        <section>
            <h2>External Image from Pexels</h2>
            <img src="https://images.pexels.com/photos/3573382/pexels-photo-3573382.jpeg" alt="Beautiful Scenery from Pexels" width="600">
        </section>

        <!-- Table of Contacts -->
        <section>
            <h2>Contacts</h2>
            <table border="1">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>John Doe</td>
                        <td>123 Main St, Anytown</td>
                        <td>123-456-7890</td>
                        <td>john.doe@example.com</td>
                    </tr>
                    <tr>
                        <td>Jane Smith</td>
                        <td>456 Elm St, Anycity</td>
                        <td>234-567-8901</td>
                        <td>jane.smith@example.com</td>
                    </tr>
                    <tr>
                        <td>Emily Johnson</td>
                        <td>789 Oak St, Anystate</td>
                        <td>345-678-9012</td>
                        <td>emily.johnson@example.com</td>
                    </tr>
                    <tr>
                        <td>Michael Brown</td>
                        <td>101 Pine St, Anycounty</td>
                        <td>456-789-0123</td>
                        <td>michael.brown@example.com</td>
                    </tr>
                    <tr>
                        <td>Sarah Davis</td>
                        <td>202 Birch St, Anystate</td>
                        <td>567-890-1234</td>
                        <td>sarah.davis@example.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Registration Form -->
        <section>
            <h2>Registration Form</h2>
            <form action="#" method="post">
                <!-- Name Field -->
                <div>
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name" required>
                </div>
                <!-- Email Field -->
                <div>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required>
                </div>
                <!-- Password Field -->
                <div>
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" placeholder="Enter your password" required>
                </div>
                <!-- Date Field -->
                <div>
                    <label for="dob">Date of Birth:</label>
                    <input type="date" id="dob" name="dob" required>
                </div>
                <!-- Dropdown -->
                <div>
                    <label for="country">Country:</label>
                    <select id="country" name="country" required>
                        <option value="">Select your country</option>
                        <option value="usa">USA</option>
                        <option value="canada">Canada</option>
                        <option value="uk">UK</option>
                        <option value="australia">Australia</option>
                    </select>
                </div>
                <!-- Radio Buttons -->
                <div>
                    <label>Gender:</label>
                    <div>
                        <input type="radio" id="male" name="gender" value="male" required>
                        <label for="male">Male</label>
                    </div>
                    <div>
                        <input type="radio" id="female" name="gender" value="female" required>
                        <label for="female">Female</label>
                    </div>
                </div>
                <!-- Checkboxes -->
                <div>
                    <label>Interests:</label>
                    <div>
                        <input type="checkbox" id="sports" name="interests" value="sports">
                        <label for="sports">Sports</label>
                    </div>
                    <div>
                        <input type="checkbox" id="music" name="interests" value="music">
                        <label for="music">Music</label>
                    </div>
                    <div>
                        <input type="checkbox" id="travel" name="interests" value="travel">
                        <label for="travel">Travel</label>
                    </div>
                </div>
                <!-- Submit Button -->
                <div>
                    <button type="submit">Register</button>
                </div>
            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
