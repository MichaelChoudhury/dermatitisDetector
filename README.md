# Midterm Assignment (Build an AI Startup)

## Team members: 
## 1. ainanami2018@gmail.com (Iman Idris)
## 2. pursh2002@gmail.com (Dr Purushottam)
## 3. choudhury.michael@gmail.com (Michael Choudhury)

## Classification service for trainee dermatologists to help diagnose skin diseases using a simple web app programmed in Python-3.
## ML/DL frameworks used: Fastai computer vision; PyTorch

## How to use the web app?
- ### Choose an image of a case of eczema, measles, or melanoma using google or take a photo using a smart phone.
- ### Save the image to your PC.
- ### Upload the image to the app.
- ### Click the 'Analyze' button.
- ### Read the result.

# Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The sample app described here is up at https://fastai-v3.onrender.com. Test it out with bear images!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
