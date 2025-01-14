# Merry Christmas Paul!
Here is a Christmas present to you by way of your very own space app. It can do everything from pulling images from the Curiosity rover on Mars to tracking satellites through space and a bunch more! I really hope you enjoy! Merry Christmas!!
# Read All 6 Steps of This First!

Getting this over to you has been the biggest headache of all!
I can't use email as its too big as well as being tagged as a virus, I cant put the .exe on GitHub because it’s too big, I also tried WeTransfer etc but none of that works as it all thinks it’s a virus! (It’s not....I promise).

In short, I had to break it up into smaller parts as compressed archives to get round size limits and antivirus checks! So, apologies for the ballache but it’s the only way I could get this to you on Christmas short of rush DHL-ing you a USB!

So, let’s get this up and running on your laptop!! 

# Step 1 - 7-Zip
First, you're going to need 7-Zip, if you don’t have it, you can download it and install it here
https://7-zip.org/a/7z2409-x64.exe

After downloading, run the install and you should be good to go, no restarts or anything needed.

# Step 2 - Downloading
Download all 7 of the .7z files in this repo.

If you know how to use GitHub then you know what you’re doing so skip to step 3.

If not, then click on the green code button here

![image](https://github.com/user-attachments/assets/c66a2541-f813-41a9-a820-48e8179718b4)

#  
After clicking on this button there will be an option to download the ZIP file, click that and download it.

![image](https://github.com/user-attachments/assets/a96ed840-0d12-448e-8b92-82dcd9943749)


Now you have the ZIP file, extract it normally (you don't have to use 7-Zip for this, just normally is fine) into a folder anywhere you'd like. Make sure there is nothing else in this file, if you extract it into a folder that already has files in the world will literally end... or it'll fail to compile. Either way, let’s not risk it. Clean folder please!

You should end up with a file that looks like this.

![image](https://github.com/user-attachments/assets/cbf851c7-ede5-45ab-9fe3-48fb125cc416)

You can delete the readme.md file, its fine if you don’t but probably better if you do.

# Step 3 - Recombining into an Executable

Ok, this is the part where we need 7-Zip.

Go to the first of the archived sections (Paul's Space App.7z.001), right click it and look for 7-Zip.
if it doesn’t immediately come up in the list of options click on the "show more options" part.

Now you should see the 7-Zip option. Move your mouse over it to see its internal options and click on "Extract Here".

It should only take a few seconds to stich it all together and then the completed exe will appear.

![image](https://github.com/user-attachments/assets/c8c653af-b285-4de2-a11c-24948785055f)

You can now delete all the other files and move this to somewhere nice. I spent ages making that .ico file look nice so it would look great on your desktop, hint hint!

![image](https://github.com/user-attachments/assets/8f302ed1-84ca-4072-bc32-1569330b0996)

See!! so so pretty!

# Step 4 - Turn Off the Internet!!

It sounds stupid but when opening it for the very first time it will still get deleted by Windows. One way to get round this is to just toggle off your Wi-Fi when you open it. You'll only need to do this the very first time you open it. After that it will open just like any other program.
# Step 5 - Running the Program

Double click it like any normal program!! Duhhh!!
Legit though on its first start up it'll be compiling a bunch of stuff in the background so give it a good 20-30 seconds before trying it again if you need to!

# Step 6 - Internet Back On

Once the program is running you can now turn the internet back on. The program will need this to talk to all the APIs.

Enjoy!!!



# User Guide - For When You Have It Installed and Running

Ok, welcome to the program, the first thing you should see is a pretty blank screen with 6 tabs.

![image](https://github.com/user-attachments/assets/9fb9ce69-125c-4ab7-a0b5-b51045d8ac4f)

These tabs let you change between the different sections of the program.

# Curiosity Rover

Annoyingly I had actually built the program to support switching between Curiosity, Opportunity and Spirit as well as all the cameras, but NASA have stopped the API for Opportunity and Spirit! There are ways of web scraping the pics but that’s a whole project in itself. Maybe an idea for version 2.0!

Anyway, for now you have the Mars Curiosity Rover and all of its cameras! Start by selecting the camera you want from the dropdown menu.

![image](https://github.com/user-attachments/assets/fefffa34-0e13-4061-9a92-18d550e7b894)

And now select if you want to look for pictures on a specific Earth day or a particular Sol. After playing with it a while I prefer to use Sol, but you do you.

![image](https://github.com/user-attachments/assets/d4dc7858-9d02-440a-8f89-91cbe3e33858)

After you have selected which you'd prefer, pop in your preferred date/Sol. Obviously if you’re wanting to look at the landing cams etc go with sol 0.

When you have everything ready click on the "Get Photos" button.

NOW THIS TAKES AGES!!! Don’t worry, it hasn’t crashed. The NASA API for other services like EPIC is fine, but for the mars rover the requests take sooooooooo long to get back so sit tight and wait with bated breath!

![image](https://github.com/user-attachments/assets/dde884ad-719a-40ce-843e-846c758ab597)

Once your picture is up you can cycle through earlier and later picture on that camera with the previous and next buttons.

If you happen to select a camera on a day/sol where no pictures were taken you will see a pop up telling you so.

![image](https://github.com/user-attachments/assets/0a632374-bc4e-48d8-8089-fc083efb97b3)

# NASA Astronomy Picture of the Day
Every day NASA publish a new picture of something interesting in the world of space.

If you leave the input blank it will pull up the most recent one.

![image](https://github.com/user-attachments/assets/a14d0aec-e754-4408-b9d8-0561da250ecc)

You can also put in any specific date you want to see from.

Again, once the picture is loaded you can cycle through them with the navigation buttons.

For each picture there is a title as well as a description of the picture. Hours of fun!!

![image](https://github.com/user-attachments/assets/7f552d7c-a529-45ce-b328-54b6830ed764)

# EPIC Images
So EPIC is the Earth Polychromatic Imaging Camera. It’s positioned at the L1 point between the Earth and the Sun which basically means it’s always taking pictures of a fully lit earth.

Same deal with the inputs, put in a date or leave it blank for the most recent.

You can see in this picture as it is winter now, Australia is near central in the picture as it is summer there. try loading some pictures and cycling through during our summer times and look at the difference!

![image](https://github.com/user-attachments/assets/ea1edf63-954a-4d9e-acb3-e7f476c83c85)


# Astronauts

Here you can look up exactly who’s currently in space! 

Just press the "Get Current Astronauts" button and it will show you what manned craft are currently in space and who is onboard them.

![image](https://github.com/user-attachments/assets/5a234a31-e523-4d5c-89ce-10637e094ae6)


# Satellite Tracker
Does what it says on the tin! It finds the exact position of various satellites and shows you where they are and where they're going.

![image](https://github.com/user-attachments/assets/204128d7-409a-4217-8140-747e734e6cbf)

I've made it start with just the ISS and Hubble selected so it’s not a giant mess, but as you add more they will be added to the map and their courses for the next orbits mapped.

The positions should refresh every 30 seconds but if you're getting impatient you can use the "refresh positions" button.

The courses are actually computed in the program using the data from the satellites themselves so if you select loads of satellites at once it will bog the program down so try not to select too many at once.

![image](https://github.com/user-attachments/assets/fd69d8d0-1f43-4149-a5f0-cde186b63d6c)

Interesting note, because GOES-16 (black) is in a geostationary orbit it doesn't have an orbital track over the ground, how cool is that!!


# Settings

Just a simple settings menu. During testing of sending this to other computers the size of the text turned out to be an issue so I've put a text size slider in there so you can suit it to wherever you’re running in on whatever screen.

I've also made it run a dark mode by default but I've also make another lighter colour scheme for everything if you prefer to be blinded so horses for courses. Just select the mode in the dropdown menu that you prefer.

![image](https://github.com/user-attachments/assets/7732c794-4688-4e90-8635-05a401d22376)



#
# Limits and Know Issues
#
As this is just for you, I've embedded the API keys into the binaries themselves. As its just your keys, there is a limit to how much you can use this..... turns out it's 1,000 requests per hour! If for some reason you hit that limit you will be blocked for 1 hour and then the key will begin to work again.
#
~~As a result of how I'm doing the memory stuff on the back end, please avoid changing tabs while a picture is loading. In most cases this is barely an issue but with the long load times for the Mars rover pictures it becomes one. So try to avoid changing tabs whenever you can see a loading bar.~~

EDIT – Actually, this was pissing me off! I've fixed it now so it can load all the tabs in the background so feel free to tab away during loading!!
#
As Mentioned, I'd avoid selecting too many satellites in the satellite tracker at once, all the back-end computation of the flight paths really slow everything down. I didn't have the will to multi-thread this!
#
The satellite tracker and the astronaut list use a different API to the NASA one with different limits. The satellite tracker is similar in limit to the NASA one, but the crew and craft look up one is smaller. I don’t know exactly what it is but I have hit the limit during testing. If you do hit the limit, just give it an hour to reset but you shouldn’t be needing to spam that list anyway!
#
I'm sure there are bugs yet to find so do let me know if you find any!
#













