Login
=====

This is a login/register/contactus/forgotpassword/newpassword/deleteaccount system with all the php included! In 6 colors :D

When setting this system up for you change home.php(this is the website you come to when you log in!)

Then there is three other files you need to change to let the whole thing work:
- db.php (fill in your database information)
- name.php (this is the title of all pages)
- home.php (this is where the page goes when you logged in!)
  - FOR YOUR HOME.PHP add (
    <?php
    if(!isset($_COOKIE['ID_my_site'])){
         header("location: login.php");
        exit();
    }

    ?>
    <?php include("name.php"); ?>
    )

    above the <html>

/////////////////////////////////////

!!! IMPORTANT !!!
- When creating the table in your database use the SQL code provided in the file database.sql !!!!!

/////////////////////////////////////


Features of this login system :
- login
- register
- forgot password
- newpassword
- MD5 encrypted passwords
- contact us form(working)
- 6 colors schemes to choose from
- modern design

For more info or your own costom colors contact me at momueller@me.com or check me out on twitter @seven11nash

Thanks for downloading and using my php login system!
