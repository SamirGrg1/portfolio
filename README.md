<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
    <link rel="stylesheet" href="csst1.css">
</head>
<body>
    <h1> Girlfirend Forms</h1>
    <form action="backend.php">
        <label for="name">Name:</label>
        <div>
            <input type="text" name="myName" id="name">
        </div>
        <br>
        <label for="age">Age:</label>
        <div>
             <input type="text" name="myRole" id="age">
        </div>
        <br>
        <label for="Email">Email:</label>
        <div>
             <input type="text" name="myemail" id="Email">
        </div>
        <br>
        <label for="Date">Date:</label>
        <div>
            <input type="Date" name="myDate" id="Date" >
        </div>
        <br>
        <label for="love">Loving:</label>
        <div>
            <input type="number" name="Loving" id="love">
        </div>
        <br>
        <div>
            Are you eligible?<input type="checkbox" name="eligible?">
        </div>
        <br>
        <div>
            Gender: Male<input type="radio" name="Gender">Female:<input type="radio" name="Gender" >Other:<input type="radio" name="Gender">
        </div>
        <br>
        <label for="Yourself">Write about Yourself.</label>
        <div>
            <textarea name="Mytext" cols="50" rows="20" id="Yourself"></textarea>
        </div>
        <br>
        <div>
            <label for="Scooter">Scooter:</label>
            <select name="Scooter" id="Scooter">
                <option value="Dio">Dio</option>
                <option value="Ntorq">Ntorq</option>
                <option value="Vespa">Vespa</option>
                <option value="Wego">Wego</option>
                <option value="None">None</option>
            </select>
        </div>
        <br>
         <div>
            <input type="submit" value="Submit now">
            <input type="reset" value="Reset now">
        </div>
        <br>
    </form>
</body>
</html>
