---
layout: default

---
<!-- modify this form HTML and place wherever you want your form -->
<h2>Registration Form</h2>
<form id="register"
  action="https://formspree.io/mqkyqyry"
  method="POST" id="registration-form"
>
  <label>
    First Name:
    <input type="text" name="Fname">
  </label>
    <label>
    Last name:
    <input type="text" name="Lname">
  </label>
  <label>
    test message:
    <textarea name="message"></textarea>
  </label>
  <label>
    Gender:
    <select name="Gender" id="cars">
      <option value="male">Male</option>
      <option value="female">Female</option>
  </select>
  </label>



</form>
  <button type="submit">Submit Form</button>