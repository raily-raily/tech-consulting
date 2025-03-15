<fieldset>
  <legend>Enrollment Details</legend>
  <label for="course">Course of Study:</label>
  <select id="course" name="course" required>
    <option value="">Select Course</option>
    <option value="cs">Computer Science</option>
    <option value="ee">Electrical Engineering</option>
    <option value="ba">Business Administration</option>
    <option value="math">Mathematics</option>
  </select><br>

  <label for="year">Year of Study:</label>
  <input type="number" id="year" name="year" min="1" max="4" required><br>

  <label for="startDate">Start Date:</label>
  <input type="date" id="startDate" name="startDate" required><br>

  <label for="comments">Additional Comments:</label>
  <textarea id="comments" name="comments" rows="4" cols="50" placeholder="Enter any comments"></textarea><br>

  <label for="file">Upload ID:</label>
  <input type="file" id="file" name="file" accept="image/*,.pdf"><br>
</fieldset>
