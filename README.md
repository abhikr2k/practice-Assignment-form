# practice-Assignment-form

  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>My Bio Data</h1>
    <fieldset>
        <legend>Personal Informtion</legend>
    First Name:
    <input type="text" placeholder="First Name">
    Last Name:
    <input type="text" placeholder="Last Name">
    <br>
    <br>
    Male:
    <input type="radio" value="male">
    Female:
    <input type="radio" value="Female">
    Other:
    <input type="radio" value="other">
    <br>
    <br>
    Date of Birth:
    <input type="date">
    <br>
    <br>
    Enter Your Mail:
    <input type="email" placeholder="Enter Your Email">
    <br>
    <br>
    Phone:
    <input type="number" placeholder="+91">
    <br>
    <br>
    Height:
    <input type="number" placeholder="Height In Feet">
    </fieldset>
    <br>
    <fieldset>
        <legend>Education</legend>
        School Name:
        <input type="text" placeholder="School Name">
        <br>
        <br>
        Class:
        <input type="number" placeholder="Enter Class">
        <br>
        <br>
        Stream:
        <select name="" id="">
            <option value="stream">Stream</option>
            <option value="med">Medical</option>
            <option value="comm">Commerce</option>
            <option value="non med">Non Medical</option>
        </select>
        <br>
        <br>
        Marksheet:
        <input type="file" name="" id="">
    </fieldset>
    <br>
    <button>Submit</button>


    <h1>This is Time Table</h1>
    <table border="3" cellspacing="5" cellpadding="8">
      <tr>
        <th>Days / Periods</th>
        <th>1</th>
        <th>2</th>
        <th>3</th>
        <th></th>
        <th>4</th>
        <th>5</th>
        <th>6</th>
      </tr>
      <tr>
        <td>Mon</td>
        <td>Science</td>
        <td>English</td>
        <td>Hindi</td>
        <th rowspan="6" STYLE="writing-mode: vertical-lr;
        -ms-writing-mode: tb-rl;
        transform: rotate(180deg);">BREAK</th>
        <td>Maths</td>
        <td>Games</td>
        <td>Moral Science</td>
      </tr>
      <tr>
        <td>Tue</td>
        <td>Science</td>
        <td>English</td>
        <td>Hindi</td>

        <td>Maths</td>
        <td>Games</td>
        <td>Moral Science</td>
      </tr>
      <tr>
        <td>Wed</td>
        <td>Science</td>
        <td>English</td>
        <td rowspan="3">Hindi</td>

        <td>Maths</td>
        <td>Games</td>
        <td>Moral Science</td>
      </tr>
      <tr>
        <td>Thu</td>
        <td>Science</td>
        <td>English</td>

        <td>Math</td>
        <td>Games</td>
        <td>Moral Science</td>
      </tr>
      <tr>
        <td>Fri</td>
        <td>Science</td>
        <td>English</td>

        <td>Maths</td>
        <td>Games</td>
        <td>Moral Science</td>
      </tr>
      <tr>
        <td>Sat</td>
        <td>Science</td>
        <td>English</td>
        <td>Hindi</td>
        <td colspan="3">Maths</td>
      </tr>
      <tr>
        <th colspan="8">This is Class VIII</th>
      </tr>
    </table>
</body>
</html>
