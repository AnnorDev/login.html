# login.html
user login using Html & Css

<!DOCTYPE html>
<html>
    <head>
        <title>annor dev</title>
        <style>
            .style1{
                border: 1px black solid;
                width: 100% 100%;
                height: 1000px;
                background-color: aquamarine;
                background-repeat: no-repeat;
                background-size: contain;
            }

            .style2{
                background-image: url(https://images.ctfassets.net/hrltx12pl8hq/5596z2BCR9KmT1KeRBrOQa/4070fd4e2f1a13f71c2c46afeb18e41c/shutterstock_451077043-hero1.jpg);
                border-radius: 20px;
                width: 400px;
                height: 500px;
                border: 4px black solid;
                margin-top: 40px;
                margin-left: 35%;
            }
            input{
                width: 300px;
                height: 30px;
                margin-left: 60px;
            }
            h1{
                text-align: center;
                font-family: Arial, Helvetica, sans-serif
            }
            p{
                margin-left: 20px;
                font-size: 19px;
            }
            button{
                font-size: 20px;
                margin-left: 42%;
                margin-top: 10px;
                background-color: rgb(43, 214, 226);
            }
        </style>
    </head>
    <body>
        <div class="style1">
            <div class="style2">
                <form>
                    <h1><i>USER LOGIN</i></h1>
                    <p>User Id:</p>
                    <input type="email" placeholder="Example@gmail.com">
                    <p>Password:</p>
                    <input type="password" placeholder="**************">
                    <button type="submit">Login</button>
                </form>
            </div>
        </div>
    </body>
</html>
