Html Code:


<html>
    <head>
    <title> My name </title>
    <link rel= "mystyle.css" href="style.css">
    </head>
<body>
        <p><center> My name is mukunth </center></p>
    
    <button onclick="changebackground()">Click me</button>
    
    <script src="myjavascript.js"></script>

</body>
</html>

Css Code:

body {
    background-color: aqua;
    text-align: center;
    padding: 50px;
    justify-content: center;
    align-items: center;
    }
    button {
        
        padding: 10px 20px;
        font-size :16px;
        cursor: pointer;
        display: none;
        position:fixed;
        top: 50%;
        left: 50%;

}


Java Script Code:

function changebackground() {
            const colors =["blue", "green", "pink", "yellow", "red", "purple"];
            document.body.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
            alert("Hello my name is mukunth. My age is 21");
}


