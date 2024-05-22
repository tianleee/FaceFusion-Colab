# FaceFusion AI Deepfake Tool Online Ports

[![Discord](https://img.shields.io/discord/1198701940511617164?color=%23738ADB&label=Discord&style=for-the-badge)](https://discord.gg/osai)

As the official FaceFusion Colabs won't be supported anymore, because FaceFusion uses Paid Clouds like ThinkDiffusion & RunDiffusion, you can use those Online Unofficial Free Ports!


Credits: I didn't make everything alone, every port has his own credits in it, except the hugging face one because it directly launches the UI, that was made by me ([Nick088](https://linktr.ee)) and ofc the program by [Original FaceFusion team](https://github.com/facefusion/facefusion).
# Usage

## Google Colab

**WARNING: YOU COULD RISK YOUR COLAB FREE TIER ACCOUNT**

- Run UI <a target="_blank" href="https://colab.research.google.com/github/tianleee/FaceFusion-Colab/blob/main/FaceFusion_UI.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- Run NO UI<a target="_blank" href="https://colab.research.google.com/github/Nick088Official/FaceFusion-Colab/blob/main/FaceFusion_Headless_No_UI.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Hugging Face Space

**CURRENTLY, ITS HAVING A PROBLEM ON DUPLICATING ON GPU FOR SOME CUDA OR CUDNN ISSUE, PLEASE IF YOU WANNA HELP JOIN THE DISCORD SERVER ABOVE TO CONTACT US!**

[Hugging Face Space🤗](https://huggingface.co/spaces/Nick088/FaceFusion)

## Kaggle



- [Run UI **(WARNING: YOU COULD RISK YOUR KAGGLE ACCOUNT)** ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/nick088/facefusion-ui/notebook)

- [Run NO UI ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/nick088/facefusion-headless-no-ui/notebook)


# Changelog
These are the changelogs for the online ports, to see the updates of the program, please check [their releases here](https://github.com/facefusion/facefusion/releases).
## Update - May 20th, 2024
Updated to facefusion 2.6.0
## Update - May 10th, 2024
Updated to facefusion 2.5.3
## Update - May 7th, 2024
As the tinyurl was giving issues for the Notebooks to git clone Facefusion, I replaced that bypass with rot13 method instead (so that it still doesn't get detected).
## Update - May 1st, 2024
Added LocalTunnel Tunnel Option for FaceFusion UI Colab & Kaggle.
## Update - April 30th, 2024
Added Cloudfare Tunnel Option for FaceFusion UI Colab.
## Update - April 27th, 2024
Added Ngrok Tunnel Option for FaceFusion UI Colab so if there are Gradio API issues, you can use Ngrok instead. Also found out there's an error into using the GPU on the Hugging Face Space, if you wanna help us into resolving it please contact us via the discord server at the top.
## Update - April 22th, 2024
Fixed kaggle ui not showing the public ngrok url and cuda nvidia toolkit not installing because it asks for confirmation. Also shortened up the code to launch ui in kaggle and colab thx to [hina](https://linktr.ee/_hina__) and adjusted the credits to add her ofc.
## Update - April 21th, 2024
Added kaggle options. Also made readme maybe prettier to look at.. Also previously today i deleted cuda toolkit in the installation as i thought it was preinstalled but i was wrong so i added it back and now should all work fine on all ports. 
## Update - April 19th, 2024
Updated facefusion 2.5.1 to 2.5.2 for the colabs & hf space, also added a step for non google chrome users to manually upload inputs in the no ui cokab as it had problems with the cell code for some reason.
## Update - April 16th, 2024
Updated facefusion 2.5.0 to 2.5.1 to both colabs and Hugging Face Space.

Also now fixed the Gradio Public Link not appearing after the update in the Google Colab UI.
## Update - April 13th, 2024
Updated facefusion 2.4.1 to 2.5.0 to both colabs and also the added Hugging Face Space. Also forgot when but thx to Lusbert to fix no ui colab encoding for output video.
