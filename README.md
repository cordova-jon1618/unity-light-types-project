# Unity Light Types Project
--------------

## Project Summary:

Light Type Unity Project for my Advanced Computer Graphics Course. 
In this project, I created and explored different lighting scenes using Unity, including Point Lights, Spot Lights, Directional Lights, Area Lights, Emissive Materials, and Ambient Light. Through this work, I gained hands-on experience in selecting the right light type for various scenarios, balancing creative vision with technical considerations like lightmapping and baked lighting. This project also deepened my understanding of the differences between real-time and baked lighting, enhancing my ability to optimize visual quality and resource efficiency in static and dynamic scenes.

--------------

## Built by Jonathan Cordova

Jonathan Cordova [@cordova-jon1618] - https://github.com/cordova-jon1618

--------------

## Assignment Name:

Unity Light Types Assignment

--------------

## Introduction & Objective:

The purpose of this report is to provide an overview of different light types, discuss their characteristics, and explain why and where they are best suited for use. In this assignment I created six scenes to depict the six distinct light types: Point Lights, Spot Lights, Directional Lights, Area Lights, Emissive Materials, and Ambient Light in order to demonstrate the practical application of these light types. This report will also talk about the challenges faced during my implementation, the lessons learned, and a walkthrough of each scene.

--------------

## Background:

Lighting in Unity plays an important role in enhancing the visual quality of any environment or scene. It sets the mood, emphasizes specific elements, and helps create a sense of depth and realism. By completing this assignment, I illustrated the practical application of how different light types can be used to achieve different effects.

--------------

## Challenges faced during the implementation:

The most challenging part of this assignment was trying to understand how baked lighting worked and why each time I changed parameters, the Unity system presented a warning regarding “UV overlapping”. Another challenge I encountered during this implementation was learning to balance the intensity and color of different light types to create my vision of a scene. I let my creativity run wild and am proud of my work. I ensured that the chosen light type complemented my creative vision. The main challenge was dealing with baked lighting and baked global illumination, particularly in the emissive material scene and the area light scene, which required an understanding of lightmapping and baked lighting in Unity.

--------------

## Lessons learned:

This assignment provided me with a good understanding of the importance of choosing the right light type for a given scene. The need to choose the right lighting setups for each scene while maintaining a high creative vision was difficult, but essential to my learning. I enjoyed this assignment as it allowed me to experiment with different light types to achieve my desired vision. I developed a deeper understanding of lightmapping and baked lighting in Unity, which allowed for more efficient use of resources and improved visual quality in the emissive material and area light scenes. One of the great lessons I learned was the difference between real-time lighting and baked lighting, with real-time lighting working for objects and scenes that have movement, whereas baked lighting is excellent for static, unmoving scenes. Managing the trade-off between baking quality and baking time, especially for the area light scene and emissive material scene was a lesson in patience. 

--------------

## Walkthrough of the program:

Please find all scenes for the lighting types in the Scenes folder.

![image](https://github.com/user-attachments/assets/6edadaab-663d-4ccf-8fc7-4766f43c7007)


## Point Lights - Film Awards Show Scene:

![image](https://github.com/user-attachments/assets/91d3781e-51bb-47a5-9e79-2d82c3db1af5)

![image](https://github.com/user-attachments/assets/35ae032f-a227-4239-9d7e-11c28c88f696)

![image](https://github.com/user-attachments/assets/727c7fa0-3812-49d0-86dc-a2faac6f28a9)

![image](https://github.com/user-attachments/assets/95475335-e1e8-446d-b3b2-348b8b35896f)

I used multiple point lights to emit light uniformly in all directions. Point lights are ideal for creating illumination to light up large rooms. In this scene, point lights were used to replicate the appearance of stage lights, highlighting the award (cube), and emphasizing the glamour of the award event.

     
## Spot Lights - Street Road Scene:

Spot lights emit a cone-shaped beam of light, allowing for focused illumination. They are commonly used in streetlights and headlights. In this scene, I used spotlights to mimic the streetlights' focused beams, casting shadows, and creating a dark dramatic atmosphere. I used the free asset from the Unity Store to obtain a streetlight and I added the spot lights to them.  I created a vehicle that is inspired by the “batmobile” from the trilogy films of the “The Dark Knight”. 
        
![image](https://github.com/user-attachments/assets/3e5c41bb-6042-4b15-a25c-eb470da08f8d)

![image](https://github.com/user-attachments/assets/7f6dfe87-c855-4d16-965b-5a82e79bb544)

![image](https://github.com/user-attachments/assets/42c84336-8618-420b-92a2-07460a8c18a7)

![image](https://github.com/user-attachments/assets/3825bf08-f3b9-4214-bb8d-2f705ec904a8)


## Directional Lights - First Moon Landing Scene:

Directional lights emit parallel light rays and are ideal for simulating sunlight or other distant light sources. In this moon landing scene, I used directional lights to simulate the star lights on the surface of the moon. My directional lights cast strong shadows and create a sense of depth on the lunar surface. I made the skylight appear as if it is nighttime to give this scene a sense of taking place on the lunar surface. 
     
![image](https://github.com/user-attachments/assets/5d2854eb-d738-4b22-b83f-2555a6ca49cc)

![image](https://github.com/user-attachments/assets/31508a46-caa1-459a-8901-0f7487e9bca7)

![image](https://github.com/user-attachments/assets/86e8ce96-6164-4fdc-b3a0-adaa7fef075d)

![image](https://github.com/user-attachments/assets/3f5ce70d-211f-42a4-85cb-014eb285c1f3)


## Area Lights - Ancient Temple Scene:

Area lights emit light from a flat, two-dimensional surface, resulting in soft, diffuse lighting. They are suitable for simulating light coming through windows or large openings. In this scene, I used area lights to simulate light coming in from the sun into an ancient temple. These area lights create a soft glow in the ancient temple, illuminating the ancient relics and the ancient robot found in the temple’s altar.

![image](https://github.com/user-attachments/assets/50b593ef-d35c-4e5d-85c6-61320751c6ab)

![image](https://github.com/user-attachments/assets/c604c392-feab-47ff-b5e6-4be504ca6a7c)

![image](https://github.com/user-attachments/assets/119dc42e-eb7c-4295-866d-cb0ed6297b3d)

![image](https://github.com/user-attachments/assets/d087f0c8-79b9-4d45-9ead-116db0a78651)


## Emissive Materials - Light Art Gallery Museum Scene:

This is one of the scenes I am most proud of. I used emissive material and added it to objects to emit light from their surface. In this scene, I used emissive materials to create art pieces, making them the primary light source and creating the perfect art gallery and museum scene.

![image](https://github.com/user-attachments/assets/12ce424f-e4ee-4815-aec1-405c2de301c2)

![image](https://github.com/user-attachments/assets/7d0d3d67-6a5b-4cbd-884d-8cb550b8f30a)

![image](https://github.com/user-attachments/assets/9fa7af35-93df-4c28-a10f-7b85b94d7726)

![image](https://github.com/user-attachments/assets/75430e9f-2ad3-42d1-9bd7-8609fb61199f)


## Ambient Light – “2001 Space Odyssey” Monolith Scene:

Ambient light is a global light source that provides soft, uniform illumination. In this scene, I used ambient light to create a hot sun desert scene. I wanted to create a mysterious atmosphere surrounding the monolith (inspired by the film “2001 Space Odyssey” and I added a UFO that I created using two sphere objects. The ambient lighting ensures that this scene feels straight out of a sci-fi film.

![image](https://github.com/user-attachments/assets/f5418124-7e36-4e40-abdf-9aa606f71b0d)

![image](https://github.com/user-attachments/assets/919c7e75-5341-4312-8906-b0e598c5a796)

![image](https://github.com/user-attachments/assets/17445eda-04a4-40c9-9c7e-ccec7a87628c)

![image](https://github.com/user-attachments/assets/1f6e3955-2004-4d5c-97d2-40b214033481)


--------------

## Conclusion:

Overall, I enjoyed this assignment the most because it gave me the creative freedom and ability to be an artist using Unity. The crossroads between art and technology is rarely experienced by Computer Science students. However, this assignment allowed me to be creative and let out my creative spirit. Moreover, by understanding and selecting the appropriate light type for each, I not only learned a lot, but learned object modeling and other creative skills with Unity. The six scenes demonstrated in my report serve as an example of the potential and effectiveness of different light types. Through experimentation, adaptation, and creativity, I overcame the challenges faced during implementation and successfully utilized these light types to create a story within each scene. I really enjoyed this assignment!

--------------
