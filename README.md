# Texture-Researcher-Ultimate
Hello, Nazar Okruzhko here maybe some of you know me from Reddit or Sketchfab, I am an ID Tech 5 expert, I am very newbie/noob at reverse engineering just started a few months ago but made some progress over the past few weeks, expecially for ID Tech 5 and 6 games...

<img width="1920" height="1080" alt="Screenshot (1976)" src="https://github.com/user-attachments/assets/8147deee-f732-42e0-941a-b561a6b9f681" />

I've made a tool called "Texture Researcher Ultimate" for Extracting textures from any games, it's based on the original "Raw Texture Cooker".

[Hovewer I do really recommend you trying out the ImageHeat this is far more advence program with other features]

## Getting Started

Texture Researcher Ultimate is a program for Reverse Engineering/Studying Binary Texture 3D files.

This tool allows for exposing Binary file for:

• Image Offset (Payload)

• Image Width

• Image Height

• Image Pixel Format

• Image Swizzle Type

Tool has support for Reading Width and Height values from Binary files in Short data type.

## INTRODUCTION
All the images are consist of raw/compressed pixel data stored at specific offset with different Sizes (Width and Height),
but not only that Binary Textures from games use texture Block Compression known as BC (Mainly DXT's and RGBA's) and sometimes they are swizzled (if they came from console).

Finding all that is possible with good HEX Viewer and this program, brute-forcing using only Texture Researcher Ultimate is also possible but keep in mind that some formats may have dynamic Offsets and Block Compressions and obviously Width and Height but mostly all this info is stored in the headers).
