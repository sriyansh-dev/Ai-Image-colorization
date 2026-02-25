# Ai-Image-colorization
AI Image Colorization is a deep learning–based project that automatically converts black-and-white images into realistic colored versions. It uses computer vision techniques to learn image patterns and context, enabling accurate color generation for photo restoration, enhancement, and AI image processing experiments.


# Image Colorization for old Image
<p align="center"><img src="./example/many_people_nature.gif"></p>

This is a project that utilizes deep learning technology to colorize black-and-white images with historical significance.

The code consists of three main parts: Automatic Colorization, Hint-based Colorization, and Multi-modal Colorization.
- We developed Demo for Automatic Colorization and Hint-based Colorization 
- Through the Multi-modal Colorization code, a Chatbot has been developed to restore black-and-white images on the Kakao Channel. 

# Automatic Colorization
<p align="center"><img src="./example/vis1.gif"></p>

"Automatic Colorization" is a method that predicts colors without user guidance. However, this method had the potential to colorize images in a way that did not align with historical facts, necessitating the development of a new approach.

# Hint-based Colorization
<p align="center"><img src="./example/model.png"></p>
<p align="center"><img src="./example/video1.gif"></p>

"Hint-based Colorization" involves coloring images according to user guidance, allowing users to specify the desired colors for the image. This enables colorization of images with historical significance using the user's prior knowledge.

# Multi-modal Colorization (Text-based Colorization)
<p align="center"><img src="./example/multi.jpg"></p>

The motivation behind developing this method was the technical implementation challenges posed by different platforms. The application of the "Image Colorization" technique, which allows user interaction, varied significantly depending on the platform. While we attempted to apply the technique through the Kakao chatbot, providing user guidance through mouse clicks, it was challenging to do so in KakaoTalk.
Therefore, we developed a method that enables image colorization in KakaoTalk using only "Text" as input. In the image provided, intermediate steps have been omitted, but the method uses CLIP to identify the desired regions and provides user guidance for those regions, allowing for "text-based image colorization."



