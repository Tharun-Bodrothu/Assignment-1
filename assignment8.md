<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="process.php" method="post">
    <div>
        <label for="name">Name : </label>
        <input type="text" name="name" placeholder="Enter your name" ></div>
    <div><br>
        <label>Gender :</label>
        <input type="radio" name="Gender" value="male">Male
        <input type="radio" name="Gender" value="female">Female
        <input type="radio" name="Gender" value="not">Not to mention
    </div><br><div>
        <label for="country">Nationality :</label>
        <select name="country" id="country">
            <option value="india">India</option>
            <option value="china">China</option>
            <option value="pakistan">Pakistan</option>
            <option value="sri lanka">Sri lanka</option>
            <option value="nepal">Nepal</option>
            <option value="japan">japan</option>
            <option value="usa">USA</option>
            <option value="bangladesh">Bangladesh</option>
            <option value="indonesia">Indonesia</option>
            <option value="canada">Canada</option>
            <option value="france">France</option>
            <option value="britian">Britian</option>
            <option value="spain">Spain</option>
            <option value="switzerland">Switzerland</option>
        </select></div><br>
        <div>
            <input type="submit" name="submit" value="submit">
        </div>
    </form>
</body>
</html>
