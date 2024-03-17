# index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PLP HACKATHON CHALLENGE(WEB DEVELOPMENT)</title>
    <link href="webhack_1.css" rel="stylesheet" />
  </head>
  <body>
    <h2 class="heading">MY HACKATHON CHALLENGE(WEB DEV)</h2>
    <p>
     Hackathons are events where computer programmers gather to develop new approaches to solving problems or completing large projects that require collaboration. During hackathons, participants look to introduce new techniques, standards or personal programming styles to progress on projects and develop solutions. 
    </p>
    <a
      href="https://www.techtarget.com/searchcio/definition/hackathon#:~:text=A%20hackathon%2C%20also%20known%20as,an%20event%20marked%20by%20endurance."
      alt="About hackathon"
      target="_blank"
      title="External link"
    >
      <button class="btn" type="button">
        Know more about hackathon &rightarrow;
      </button></a
    >
    <br />
    <br />
    <section>
      <img
        class="img"
        src="https://tfwlab.wales/wp-content/uploads/2022/08/HACKATHON-1-980x551.png"
        alt="image"
      />
    </section>
    <section>
      <form>
        <label for="Name">Name</label>
        <input
          type="text"
          name="Name"
          id="Name"
          placeholder="Type your name"
        />
        <br />
        <label for="email" name="email">email address</label>
        <input
          type="email"
          name="email"
          id="email"
          placeholder="Type your email address"
        />
        <br />
        <label for="phone" name="phone"> Phone number</label>
        <input
          type="number"
          name="phone"
          id="phone"
          placeholder="Type your phone number"
        />
        <br />
        <label for="age" name="age">Age</label>
        <input
          type="number"
          id="age"
          name="age"
          placeholder="Type in your age"
        />
        <br />
        <br />
        <fieldset>
          <legend>Gender</legend>
          <input type="radio" id="male" name="female" />
          <label for="male" name="male">Male</label> <br />
          <input type="radio" id="female" name="female" />
          <label for="female" name="female">Female</label>
        </fieldset>
        <br />
        <label for="course" name="course">Multi-selection of subject</label>
        <select>
          <option>English</option>
          <option>Math</option>
          <option>Science</option>
          <option>Art</option>
          <option>Craft</option>
          <option>Agriculture</option>
          <option>Geography</option>
          <option>History</option>
        </select>
        <br />
        <label for="pwd" name="pwd">Password</label>
        <input
          type="password"
          name="pwd"
          id="pwd"
          placeholder="Type your password"
        />
        <br />
        <label for="id" name="id">SessionID</label>
        <input type="password" id="id" name="id" placeholder="SessionID" />
        <br />
        <input class="button btn1" type="button" value="Cancel" />
        <input class="btn2" type="button" value="Register" />
      </form>
    </section>
  </body>
</html>
