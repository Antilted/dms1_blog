---
title: This is a week 8 session 2 !
published_at: 2025-05-09
snippet: Homework task 
disable_html_sanitization: true
allow_math: true
---

# Introduction

Today, another familiar and ovegone agenda reappeared that is SOUNDS. I have got the chance to learn sounds in the first and second assingment but for this time we are focusing on a more 3D sound base and its physics. In class we get to see some esamples of how vital sound is to a good scene, it sets the mood and it even excites the player as well. An activity was also handed out to us on Unity that we add sounds to our scene to make it more impactful.

# Sound as space and emotions

As ive mentioned before sounds is extemely important because it gives the player a indepth understanding of aura in the scene as well as the distance and position they are at. Sounds can lead the player into feeling a particular way take music for instance, i the creator/editor sets up a lofi vibe music to a sunset scene it can already manipulate the emotions of the player and lead it to direct calmess. Sound effects are also neccessary in certain scenerios such as weather or tiny particles elements, by doing this you can make a sudden change to the player mindset or emotions, in addition, you can gradually change the way a scene meaning is to the player. 

# Ambience sounds

These sounds as ive metioned similary above are usually static sound meaning they only can be heard by a player when they are in a certain are of the scene. These sounds basically gives the player a sense of place and position, also this can give off a description of what the place is like if is urban, rural or even fantasy type. Ambient sounds are also hints because if the echo or range of a sound is heard before the player enter a certain part of the scene then they could probably predict whats going to happen next and not get easliy confused. The reason behind this is that sounds can atcually give off a better visualization in our mind rather than relying on sight purely because we can sometimes hear what we cant see like hidden GameOjects for example.

# Audio Landmarks

As mentioned before in the previous section auio can be used to lead the player in a certain direction. With sight objects like footpaths or alligned walls are used because its visual and it makes us go directly into it. For sounds, the audio can get louder or more potentially agressive as the player get closer in range or in contrast, it could get dimmer and let the player have a sense that they are getting further away from the object.

# Unity Sounds

I then hopped into unity for a practice activity with sounds. First we must download the 3 samples sounds that RMIT provided that is piano, guitar and flute ambient sounds. We were asked to create a mountain type terrain and we add the sounds in. By clicking add component in the inspector panel we can add an audio source. There we applied our selected audio to the source, there are also a bunnch of settings that we could mess with.

![Added_audio](w8s2/audio.jpg)

Also we can do things in the graph editor, there's the Logarithimc, Linear and coustum graph. All of these can be adjusted from the settings above. Theres the Dopper level meaning how ambient you want it a how distorted from what i've heard when trying. Also the most important thing with this is the you must set the spacial Blend from 2D to 3D or the graph wont matter. Theres the minimum distance meaning the closest distance to hear a 100 full volume of the audio, and the maximun distance meaning that is the range and when you leave that range the audio can't be heard anymore. Spread is advised to set to max because its better quality.

![Settings](w8s2/morespunds.jpg)

# Assingment 3 status

Like ive mentioned before ive decided not to really make a graybox prototype because my project is a little too ambitious and i really need to change them from time to time. 3 of them are terrain based and only the last one is interior designed based (sort of). Ive figured out how to swap between different scenes, experment with aspects of sounds and most of all scripting, this is by far the most annyoing things that ive ever come across, the reason is when i was writing the script for a 3D model all of the directions are inverted and its because of the models inverted direction at first. I tried to change the direction and script multiple times for it still doesn't work an something crashed my Unity and i've lost process many times so i decided to just do a static moving model. it doesnt look good but at least the mechanic is working fine maybe there are some bugs but they are not severe. Heres what i did 

![Enchance](w8s2/addedtrees.jpg)

This time ive added more environmental detail, also made the cube float like a magic ball. Sounds and lighting will be added later on right now just focusing on design and mechanic to get them working properly.

![Dinos](w8s2/dinos.jpg)

Finished compositing and scripting dinos, it may look a little stiff and not natural but im not a game desinger so this is the best i could do i added sfx to the dinos and i'll do more ambient sfx and lighting next time

I've also started working on the Thalassophobia part but i've run into a huge list of errors with the water mechanics and i got scammed after purchising a already existing assest inside of Unity so i decided to just go with Unity standard assets basic water this may look bad and not artistic enough but this is the only thing not giving me a huge list of error. I'll add rain, shark and sfx later on. The boat mechanics ran into a lot bugs espcially the detecting part of the boat when the player gets on and ride around it, it keeps flipping over and please MR THOMAS DO NOT DRIVE THE BOAT ON LAND because the boat will float away and not able to get down because i didnt add the bouyancy mechanic but instead turned off gravity in Rigibody and DO NOT EXIT THE BOAT WHILE IN WATER, i mean nobody does that anyways but dont do it because you will fall out of the map. But you exit the boat near the gulf when portal is visible.

Thats all for today
Alan