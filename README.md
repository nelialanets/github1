<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo Forms </title>
</head>

<body>
    <h1>Demo Forms</h1>

    <form action="/tacos">
        <!--file:///tacos?username=neliarod-->
        <!--name is important u should put it on a single data server you use ec. name="q", name"search" "form action sends data to the server"-->

        <div>
            <label for="user name">Enter a User Name</label>
            <input id="user name" type="text" placeholder="Enter a username:" name="username">
        </div>
        <div>
            <label for="color">Select Colo:r</label>
            <input id="color" type="color" name="color">
        </div>
        <div>
            <label for="number">Password:</label>
            <input id="number" type="number" placeholder="enater 8 digits" name="password">
        </div>
        <!--file:///tacos?username=neliarod&color=%23ef9b80&password=2-->
        <form action="https://www.google.com/search?q=web+development" </form>
            <input type="text" name="q">
            <button>Submit Google Search </button>
</body>

</html>
