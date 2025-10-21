# Jellyfin-doubletap
its basic script for forwarding a video on jellyfin web player with doubletaps on left or right of the screen

How to Setup
1. Open your notepad as admin
2. Go for "C:\Program Files\Jellyfin\Server\jellyfin-web" and edit index.html file with notepad
3. at the bottom of the html file you will see something like that </div></div></body></html>```
4. "</div></div> HERE </body></html>" just paste the script between the second div> and </body
5. save and restart jellyfin


you can change how much it forwards by changing the value of const SEEK on the script its 5 as default which means 10 second forwarding you need if you need 30 seconds you need to put 15 as value 
