<html>
    <head>
        <title>Forms</title>
        <style>
            body{
                background-image: url(images/sport2.jpg);
                background-position: center;
                background-size: cover;
                color: chartreuse;
            }
            form{
                position: absolute;
                top: 20%;
                left: 40%;
            }
        </style>
    </head>
    <body>
        <form>
         <label>Name:</label>
            <input type="text" name="name" placeholder="Enter name" size="10" required /><br>
        Gender:
        <input type="radio" name="gender" value="Male">
        <lable>Male</lable>
        <input type="radio" name="gender" value="Female">
        <label>Female</label>
        <input type="radio" name="gender" value="Others">
        <label>Others</label>
        <br><br>
        <label>Date of Birth</label>
        <input type="text" name="date of birth" size="10" pattern="[0-31]{2}-[1-12]{2}-[2001-2003]{4}" placeholder="dd-mm-year" required />
        <br><br>
        Favourt Sport:
        <select>
            <option>Cricket</option>
            <option>Football</option>
            <option>Volley Ball</option>
            <option>Throw Ball</option>
            <option>Hockey</option>
        </select>
        <br><br>
        <label>Phone</label>
        <input type="text" name="country code" value="+91" size="2">
        <input type="tel" name="phone" size="25" pattern="[0-9]{4}-[0-9]{6}" required />
        <br><br>
        E-mail:
        <input type="email" name="email" placeholder="                     @gmail.com">
        <br><br>
        <input type="submit">
        </form>
    </body>
</html>
