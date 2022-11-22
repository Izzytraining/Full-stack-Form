<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Forms</title>
  </head>
  <body>
    <h1>Exercise Form</h1>
    <form action="">
      <label for="First Name">First name</label>
      <br />
      <input type="text" placeholder="First name" />
      <br />
      <label for="Last name">Last name</label>
      <br />
      <input type="text" placeholder="Last name" />
      <br />
      <label for="Age">Age</label>
      <br />
      <input type="number" placeholder="Age" />
      <br />
      <label for="enter email">Email</label>
      <br />
      <input type="email" name="email" id="enter email" />
      <br />
      <br />
      <label>Select your favourite colour</label>
      <br />
      <label>Pick a colour</label>
      <select name="colour" id="colour">
        <option value="colour">Blue</option>
        <option value="colour">Red</option>
        <option value="colour">Green</option>
        <option value="colour">Purple</option>
        <option value="colour">Yellow</option>
      </select>
      <br />
      <br />
      <img src="../images/Unknown.png" alt="" height="50px" width="100px" />
      <br />
      <label for="poembox">Write a poem about your favourite colour</label>
      <br />
      <textarea name="poem" id="poembox" cols="30" rows="10"></textarea>
      <br />
      <input type="submit" value="Submit" />
    </form>
  </body>
</html>
