# survey
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Survey Form</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styleform.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Survey Form</h1>
      <p class="subtitle">We value your feedback. Please fill out the form below.</p>
    </header>

    <main>
      <form action="#" method="post" class="survey-form">
        <!-- Personal Information Section -->
        <section class="form-section">
          <h3>Personal Information</h3>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" placeholder="Enter your name" required>
          
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" placeholder="Enter your email" required>
          
          <label for="age">Age:</label>
          <input type="number" id="age" name="age" placeholder="Enter your age" min="1" required>
        </section>

        <!-- Feedback Section -->
        <section class="form-section">
          <h3>Your Feedback</h3>
          <label for="experience">How would you rate your experience?</label>
          <select id="experience" name="experience" required>
            <option value="">Select an option</option>
            <option value="excellent">Excellent</option>
            <option value="good">Good</option>
            <option value="average">Average</option>
            <option value="poor">Poor</option>
          </select>

          <label>Would you recommend us?</label>
          <div class="radio-group">
            <label><input type="radio" name="recommend" value="yes" required> Yes</label>
            <label><input type="radio" name="recommend" value="no"> No</label>
          </div>

          <label for="comments">Additional Comments:</label>
          <textarea id="comments" name="comments" rows="4" placeholder="Write your comments here..."></textarea>
        </section>

        <!-- Submission Section -->
        <section class="form-section">
          <button type="submit" class="btn-submit">Submit</button>
        </section>
      </form>
    </main>
  </div>
</body>
</html>
