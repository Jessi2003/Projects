# Projects
<!DOCTYPE html>
<html>
    <head>
       
    <style>
        #bg{
            background-color:rgb(231, 107, 231);
            text-align:center;
            border-color: black;
            border-width:4px;
            border-style:solid;
            border-radius: 14px;
        }
        #para{
            color:rgb(19, 17, 17);
            font-style:italic;
            font-size: 21px;
            margin:4px;
            padding:5px;
        }
        #button{
        font-style:oblique;
        border-radius: 10px;
        background-color: rgb(81, 184, 231);
        height:40px;
        width:80px;
        font-size:17px;
        }
        .msg{
            font-size:27px;
            font-style:italic;
            font-weight:bold;
        }
        .p{
            font-style:oblique;
            font-size:18px;
        }
    </style>   
    </head>
    <body>
        <div id="bg">
            <br>
            <h1>Welcome to Jessi's Secret Chamber</h1>
            <p id="para">"Hello Dear, I hope this message finds you well! I wanted to reach out and say hello. How have you been? It's been a while since we last caught up, and I'm eager to hear all about what's new in your life. Let's find a time to connect soon and share some stories. Take care and see you soon!"</p>
            <p class="p">Click on below button to see hidden message</p>
           
            <button id="button" type="button" onclick="document.getElementById('demo').innerHTML='Love you so much maa .....'">Click</button>
            <p id="demo" class="msg"></p>
            <br>
            <br>
        </div>
       
    </body>
</html>
