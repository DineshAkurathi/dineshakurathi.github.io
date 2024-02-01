<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Insert title here</title>
<link rel="stylesheet" type="text/css" href="styles.css">
<style>
    /*This code is from neumorphicCss file which is a simple layout file in css*/
*{margin:0;padding:0;}
body{
  background-color:#ececec;
  width:100%;height:100vh;
  position:relative;
}
[type="checkbox"]{
/*   background-color:orange; */
  height:100px;width:100px;
  -webkit-appearance:none;
  box-shadow:
    -10px -10px 15px rgba(255,255,255,.5),
    10px 10px 15px rgba(70,70,70,.2);
  position:absolute; top:50%; left:50%;
  transform:translate(-50%,-50%);
  border:8px solid #ececec;
  border-radius:5%;
  outline:none;
  display:flex; justify-content:center; align-items:center;
  cursor:pointer;
}
/*Write a main container code to store all the elements inside the main container code will be in myCss file*/
.main-container{
    font-family: 'Ubuntu', sans-serif;
    /*Also make this width dynamic to phone, tab etc...*/
    width: 950px;
    height: 1725px;
    margin: 6em auto;
}



/*continue here and also change all the classes in html code where ever necessary ALL THE BEST FOR YOUR NEW WEBSITE*/





</style>
</head>
<body>
	<h1>Hello </h1>
	<button class="hover-button">Hover me</button>
	<div class="main-container">
        <!--Header container-->
        <header class="block">
            <ul class="header-menu horizontal-list">
                <li><a class="header-menu-tab" href="#1"><span class="icon entypo-cog scnd-font-color"></span>Settings</a></li>
                <li><a class="header-menu-tab" href="#2"><span class="icon fontawesome-user scnd-font-color"></span>Account</a></li>
                <li><a class="header-menu-tab" href="#3"><span class="icon font-awesome-envelope scnd-font-color"></span>Messages</a></li>
                <li><a class="header-menu-tab" href="#4"><span class="icon font-awesome-star-empty scnd-font-color"></span>Favorites</a></li>
                <li><a></a></li>
            </ul>
            <div class="profile-menu">
                <p>Me<a href="#26"><span class="entypo-down-open scnd-font-color"></span></a></p>
                <div class="profile-picture small-profile-picture">
                    <!--Add the image src below-->
                    <img width="40px" alt="Dinesh Akurathi picture" src="">
                </div>
            </div>
        </header>
        <!--Header container ends here-->
    </div>
</body>
</html>
