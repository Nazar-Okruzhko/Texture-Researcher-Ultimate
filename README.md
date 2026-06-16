<img width="1398" height="151" alt="image" src="https://github.com/user-attachments/assets/a927397d-21df-4d8f-9f28-074161e34392" />
    
    Hello, it's Nazar Okruzhko, some of you might know me from Reddit or Sketchfab, I am an "ID Tech 5 Expert" in terms of Reverse Engineering, 
    I used to be a real Begginer at reverse engineering, just started a some time ago hovewer Reversing ID Tech 5 / ID Tech 6 / ID 
    Tech 7 / ID Tech 8 games made me grew unrealisticly fast, and over time write some Extraction Scripts. 
    I noticed that I won't be able to countinue writing custom Extraction Scripts, so I decided to release the "Ultimate" Extraction Tools!...
    I've made a tool called "Texture Researcher Ultimate" for Extracting 2D Textures from any games.

<img width="1920" height="1080" alt="Screenshot (2922)" src="https://github.com/user-attachments/assets/03c023ce-9800-48da-bad4-4748f1dfbebc" />

![Static Badge](https://img.shields.io/badge/Minimal%20Requirements%3A%20-%20Windows%20XP%20-%20Orange)

What is Texture Researcher Ultimate?

Basically it's an encoder for Compressed Textures (BC1-BC7) or Uncompressed Textures (RGBA 8888/4444/5551) who's image data always starts at a certain Offset followed by Width and Height parameters which can be found in headers as well as the BC Flag Byte...

(Hovewer I do really recommend you trying out the ImageHeat this is far more advenced program with other features)

## Getting Started

Texture Researcher Ultimate is a program for Reverse Engineering/Studying Binary Texture 3D files.

This tool allows for exposing Binary file for:\
• Image Offset (Payload)\
• Image Width\
• Image Height\
• Image Pixel Format\
• Image Swizzle Type

Tool has support for Reading Width and Height values from Binary files in Short data type.

## INTRODUCTION
All the images are consist of raw/compressed pixel data stored at specific offset with different Sizes (Width and Height),
but not only that Binary Textures from games use texture Block Compression known as BC (Mainly DXT's and RGBA's) and sometimes they are swizzled (if they came from console).

Finding all that is possible with good HEX Viewer and this program, brute-forcing using only Texture Researcher Ultimate is also possible but keep in mind that some formats may have dynamic Offsets and Block Compressions and obviously Width and Height but mostly all this info is stored in the headers).
