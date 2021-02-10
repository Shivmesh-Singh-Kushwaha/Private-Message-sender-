//<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trello App</title>
    <style>
        #form{
            border: 2px solid slategrey;
            margin: auto;
            height: 32vw;
            width: 25vw;
            background-color : silver;
            
            
        }
        #head{
            width: 37%;
            height: 8%;
            margin: auto;
            
        }
        #email{
            margin: auto;
            height: 46%;
            width: 97%;
        }
        #comment{
            margin: auto;
            height: 87%;
            width: 97.5%;
        }
        #emailid{
            margin: auto;
            height: 13%;
            width: 96%;
        }
        #text{
            margin: auto;
            height: 28%;
            width: 96%;
        }
        .button1,.button2{
            margin: auto;
            height: 12%;
            width: 95%;
        }
        #send{
            background-color:rgb(35, 187, 47);
            height: 70%;
            width: 100%;
        }
        #reset{
            background-color:rgb(35, 187, 47);
            height: 74%;
            width: 100%;
        }
        #span{
            margin: auto;
            font-weight: bold;
            width: 56%;
        }
        #anchor{
            height: 8%;
            width: 26%;
            float: right;
        }
        #para
        {
            margin: auto;
            width: 93%;
        }
        .line{
            margin: auto;
            background-color: darkslategrey;
            width: 97%;
        }
    </style>
</head>
<body>
    <form action="Createlink.html" id="form" method="post">
        <h3 id="head">Invite to Board</h3>
        <hr class="line"/>
        <div id="emailid">
          <label for="email">Email Id</label>:
          <input type="email" id="email" name="Email-id" >
        </div>
        <div id="text">
          <label for="comment">Comment</label>:
          <textarea name="Comment" id="comment"  ></textarea>
        </div><br>
        <div class="button1">
          <input type="reset" value="Reset" id="reset">
        </div>
        <div class="button2">  
          <button id="send">Send Invitation</button>
        </div>
        <hr class="line"/>
        <p><span id="span">   [-] Invite with link </span><a href="https://www.google.com/forms/about/" id="anchor">Create Link</a></p>

        <p id="para">Anyone with this link can join as board member</p>


    </form>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Response</title>
</head>
<body>
    Your details have been recorded. Thank you for sumbit.
</body>
</html>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
