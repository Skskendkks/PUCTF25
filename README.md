# PUCTF-25 Catch the Arcadeholic (Mics)
Difficulty: ★★★☆☆☆☆☆☆☆        Author: Yeung Wang Sang        Team: T001_ctf-beginner

# PUCTF25 Catch the Arcadeholic writeup

Here is the link for your reference. 

https://ctf.polyuctf.com/challenges#Catch%20that%20Arcadeholic-109

## The question

Jeffrey is one of the member in Nuttyshell, but he is addicted to video arcade games now and don't want to play CTF for a lifetime.

We hacked his phone and found some photos from his gallery that might help us to find him, can you help us to find him?

Flag format: PUCTF25{<street_name_with_underscore>_<xxx.xxx_xxx.xxx(geolocation_of_the_location_in_the_image)>}

PS: The first letter of the street name should be capitalized, e.g. foo bar street should be written as Foo_Bar_Street, the decimal places of the geolocation should be three digits without rounding.

## Finding

Jeffrey is one of the members in Nuttyshell, but he is addicted to ***video arcade games*** now and doesn't want to play CTF for a lifetime.

## Image

![/image/chall_(1).jpg](/image/chall_(1).jpg)

# View the image and find the clue

## McDonald’s logo

I can see the McDonald's logo, and I see the license plate. 

## license plate

The license plate is “MW 79-83,” black background with white text.  

2 English words and 4 numbers are the same as a Hong Kong license plate. That means car number of this area is similar to that of Hong Kong. 

## Promotional poster

You can see a few Chinese words. That means the area in Asia. 

## Summarize the photo

In Asia, the number of vehicles with black backgrounds and white letters is roughly the same as that in Hong Kong. 

### Therefore, I guess the location is Macau.

Go to Google Macau license plate is the same as this picture. 

[Vehicle registration plates of Macau](https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FVehicle_registration_plates_of_Macau&psig=AOvVaw19TEPqLa5Msm23azEaiNXX&ust=1745685405558000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCPDa4I3P84wDFQAAAAAdAAAAABAE)

# Finding the location

Go to Google Maps to search the “街機”; 

[](https://www.notion.so)

![/img/image.png](/image/image.png)

Did not have too many results. 

## Use google map street view

Just zoom in and use the Google Maps street view service. You can see the photo. 

[街機](https://maps.app.goo.gl/f74doNKTsHtfLew36)

Can find the same photo 

[](https://www.notion.so)

![/img/image%201.png](/image/image%201.png)

## Final result

Here is the Google map final result 

![/img/image%202.png](/image/image%202.png)

The English version of Google Maps can show the street name. 

![/img/image%203.png](/image/image%203.png)

The full form is Rua Alegre Stree 

The geolocation can be found in the Google Maps URL. 

![/img/image%204.png](/image/image%204.png)

PUCTF25{<street_name_with_underscore>_<xxx.xxx_xxx.xxx(geolocation_of_the_location_in_the_image)>}
