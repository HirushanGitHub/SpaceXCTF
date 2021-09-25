<h1> SpaceXCTF </h1>

<h2>How to setup SpaceXCTF</h2>

First of all download apache wed server and then install it (WAMP/XAMPP for windows, Lamp for Linux).
If you install "WAMP" for windows OS, there is a file in C:drive named "WAMP". There is a folder named "www" in this file. Then place your web app ("SpaceXCTF" folder of the downloaded zip) to the "www" folder. After that start the "WAMP" server after clicking. At this time you can see a WAMP server green colour icon in the right side of the start bar.

If you install "XAMPP" for windows OS there is a file in C:drive named "XAMPP". There is a folder named "htdocs" in this file. Then place your web app into this folder. Next go to "XAMPP" Control Panal and start Apache web server and MySQL.

After doing one of them, open any web browser in your desktop. After that type as "localhost" in the address box. If you use XAMPP then, access to the "SpaceXCTF" folder in the "htdocs" file and if you use WAMP then, access to the "SpaceXCTF" folder in the "www" folder through the browser.

eg :- (localhost/SpaceXCTF)

Then,import the DataBase into the apache wed server by following this video (https://www.youtube.com/watch?v=kxdzfv-KU9Y).This database is in a file known as Spacex_Data_Base in the downloaded zip.

<h4> Note :- You must use Linux environment to play levels from 15th to 20th. </h4>

<h3>If this is not working ....</h3>
I have implemented this,using WAMP server. Access to the 'loginpage.php' from browser.Then copy the current URL of the browser in the address box. After that go to "newregister.php" code and found the Ajax call(line no: 100). Paste(line no: 115) the coppied URL to the URL ("http://localhost:8080/spacex/loginpage.php") which is used to access "loginpage.php".Save the content and run.

<h3>You can download SpaceXCTF using this link :- https://mega.nz/folder/4NpWXZAD#Q88gLa2vZgxHwtR0chfZFw </h3>

Contact :- hirushansajindra96@gmail.com
