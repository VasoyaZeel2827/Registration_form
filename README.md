
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        #main {
            width: 50%;
            margin: 30px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0,1);
            text-align: center;
        }

        h1 {
            color: red;
            background-color: black;
            text-align: center;
            border-radius: 60px;
            padding: 10px;
        }

        input, select {
            width: 80%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        button {
            width: 120px;
            background-color: #007bff;
            color: white;
            border: none;
            padding: 12px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }

        button:hover {
            background-color: #0056b3;
        }

        label {
            display: block;
            text-align: left;
            margin-left: 10%;
            font-weight: bold;
        }

        .checkbox-container {
            text-align: left;
            margin-left: 10%;
            margin-top: 10px;
        }

        a {
            text-decoration: none;
            color: red;
        }
    </style>
</head>
<body>

    <div id="main">
        <h1>Admission Enquiry for 2025-26</h1>

        <form>
            <label for="name">Full Name</label>
            <input type="text" id="name" placeholder="Enter Name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" placeholder="Enter Email Address" required>

            <label for="mobile">Mobile Number</label>
            <input type="number" id="mobile" placeholder="Enter Mobile Number" required>

            <label for="otp">Enter OTP</label>
            <input type="number" id="otp" placeholder="Enter OTP" required>

            <label for="state">Select State</label>
            <select id="state">
                <option>Select a state</option>
                <option>Gujarat</option>
                <option>Maharashtra</option>
                <option>Rajasthan</option>
                <option>Madhya Pradesh</option>
                <option>Kerala</option>
                <option>Tamil Nadu</option>
                <option>Karnataka</option>
                <option>Uttar Pradesh</option>
                <option>West Bengal</option>
            </select>

            <label for="city">Select City</label>
            <select id="city">
                <option>Select a city</option>
                <option>Ahmedabad</option>
                <option>Surat</option>
                <option>Vadodara</option>
                <option>Rajkot</option>
                <option>Gandhinagar</option>
                <option>Bhavnagar</option>
            </select>

            <label for="level">Select Level</label>
            <select id="level">
                <option>Select Level</option>
                <option>UG</option>
                <option>PG</option>
                <option>Executive Programs</option>
            </select>

            <label for="program">Select Program</label>
            <select id="program">
                <option>Select Program</option>
                <option>BTECH CSE</option>
                <option>BBA</option>
                <option>BCA</option>
                <option>BSC</option>
                <option>BCOM</option>
            </select>

            <div class="checkbox-container">
                <input type="checkbox" id="privacy" required>
                <label for="privacy">I agree to receive information by signing up on the <a href="#">privacy policy</a> of Navrachana University.</label>
            </div>

            <button type="submit">SUBMIT</button>
        </form>
    </div>

</body>
</html>
