# Application for Pizza's image classification using [fast.ai](https://www.fast.ai) models and deployed on [Render](https://render.com)

You can upload your Calzone/Pineapple/Pepperoni pizza's picture on the [website](https://choose-the-right-pizza.onrender.com) to check the result !

You can also use this repo to make your own image classifier using fast.ai models.

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
