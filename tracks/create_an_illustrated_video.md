## Track 1 : Create an illustrated video with music and voice

The goal of this track is to create an illustrated story with animated images, music, and voice narrator. The participant discover different technologies including : diffusion models (dall-e, stablediffusion, midjourney,...), text to speech synthesis and text to music synthesis.

1. Step 1 : Generate a pitch for the story 

You can use that prompt in [chatgpt](https://chat.openai.com) to generate a pitch for you story : 

    Please, Generate a script for a 1-minute video about DESCRIBE YOUR STORY. The video should be an illustrated story where a narrator describes the action of each scene. Please output a description of the illustration and the narrator text for each scene. The description of the image should be coherent between the scene and always repeat the personage names and description for each illustration description.


2. Step 2 : Generate a style for you illustrated story.

you can use this prompt in [chatgpt](https://chat.openai.com) :

    Can you create a short style prompt for an image generator. It should only describe the style of the image and not the composition. I would like a DESCRIBE THE STYLE YOU WANT style ?
    example : Render in a vibrant anime style, with smooth gradients, expressive eyes, and soft shading. Emulate the meticulous details typical of high-quality Japanese animation, ensuring clean line art and a balance between realism and stylization.


3. Step 3 : Generate each frame with [bing image creator](https://www.bing.com/create) using the illustration description as prompt. Append the style prompt to each illustration description (you may also need to add some details to the prompt to further describe the scene in odred to keep it consistent with the script).

4. Step 4 : Pass each frame to [gen-2](https://research.runwayml.com/gen2) on runwayml to animate the images.

5. Step 5 : Group the narrator line in chatgpt using that prompt : 

    Can you group all the narrator line into one single paragraph ?

5. Step 5 : Generate the narrator voice with [elevenlabs](https://elevenlabs.io/). Just copy the narrotor paragraph, choose your voice and generate.

6. Step 6 : [optional] Generate a background music with a text to music app. You can also generate ambiant sounds

7. Step 7 : Assemble everything in an [capcut](https://www.capcut.com´) online video editor (example: capcut)