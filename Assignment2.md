<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submit Form</title>
</head>
<body>
   <form action="process.php" method="post">
        <div>
            <label>Name:</label>
            <input type="text" name="name" placeholder="Enter your name">
        </div>
        <br>
        <div>
            <label>Email:</label>
            <input type="email" name="mail" placeholder="Enter your e-mail">
        </div>
        <br>
        <div>
            <label>password:</label>
            <input type="password" name="password" placeholder="Enter your password">
        </div>
        <br>
        <div>
        <input type="checkbox" name="checkbox">
        <label>Click here to agree to terms and conditions</label>
        </div>
        <br>
        <input type="submit" name="submit" value="submit">
   </form> 
</body>
</html>
