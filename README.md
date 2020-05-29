# Colon-Polyps: Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The sample app described here is up at https://fastai-v3.onrender.com.

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.

### Docker ready to use

You can directly use the already created docker from [https://hub.docker.com/repository/docker/muntisa/colon-polyps-fastai](https://hub.docker.com/repository/docker/muntisa/colon-polyps-fastai).

Run the local docker with the following command:
```
docker run -p 5000:5000 colon-polyps-fastai
```

Have fun!
