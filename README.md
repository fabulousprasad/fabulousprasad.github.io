<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Senior Leader Feedback Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        textarea, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Senior Leader Feedback Survey</h1>
    <form action="submit_feedback.php" method="POST">
        <label for="visibility">1. How aware are you of the new function's goals and activities?</label>
        <textarea id="visibility" name="visibility" rows="3" required></textarea>

        <label for="role_clarity">2. How clearly defined do you find the role and responsibilities of the new function?</label>
        <textarea id="role_clarity" name="role_clarity" rows="3" required></textarea>

        <label for="alignment">3. How well does the new function align with the overall strategic goals of the organization?</label>
        <textarea id="alignment" name="alignment" rows="3" required></textarea>

        <label for="confidence">4. How confident are you in the new function's ability to achieve its objectives?</label>
        <textarea id="confidence" name="confidence" rows="3" required></textarea>

        <label for="collaboration">5. How well does the new function collaborate with other departments and teams?</label>
        <textarea id="collaboration" name="collaboration" rows="3" required></textarea>

        <label for="support">6. Do you think the new function has the necessary support and resources to perform effectively?</label>
        <textarea id="support" name="support" rows="3" required></textarea>

        <label for="overall_assessment">7. What is your overall assessment of the new function’s performance and potential?</label>
        <textarea id="overall_assessment" name="overall_assessment" rows="3" required></textarea>

        <label for="additional_comments">Additional Comments:</label>
        <textarea id="additional_comments" name="additional_comments" rows="4"></textarea>

        <button type="submit">Submit Feedback</button>
    </form>
</div>

</body>
</html>
