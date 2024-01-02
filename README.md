# Flask Stable Diffusion Application to generate Image 

Example app that demonstrates how to run a Flask app with a free GPU using Google Colab and ngrok.

![image](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/dc6189b1-ee3d-4119-a183-6f68a9905fe4)



# Stable Diffusion Model Used

**runwayml/stable-diffusion-v1-5** with fp16


# Instructions

1. Open the Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/blob/main/notebook.ipynb)



2. Go to [ngrok.com](ngrok.com), get a free API token, and in the Colab replace **YOUR-AUTHTOKEN-HERE** with the token.

  ![Screenshot 2024-01-02 195541](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/c0e1cccf-9e69-445f-b648-fc68e589bbc7)


3. Set the runtime to GPU

  ![image](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/4bff0cb3-060a-4860-980e-6f05259889f1)


4. Don't forget to put your !ngrok authtoken .............................. in the ipynb on Google Colab.

5. Click on `Runtime -> Run all`

6. In the output cell you should see a url similar to this: Running on something like **http://ca29-35-185-229-95.ngrok-free.app**. Open this url and use your application.

![Screenshot 2024-01-02 195908](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/48e72051-ce34-42f6-b5c1-85e6ec87554f)

Click on **visit site**

Then:

**User prompt:** Ashoka the great the Indian king

The output is a as below:

![Screenshot 2024-01-02 210520](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/1b202d9e-c2e5-4672-adb0-a8e91aa9c418)

and click on Download button to download the image.


Also the output from the code is shown below

![Screenshot 2024-01-02 210620](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/068eb72f-bbc0-48e8-bfbf-45c48469827d)


Try with different prompts..........

**Happy image generation**



# Packages

* torch>=1.4
* diffusers==0.10.2
* transformers
* scipy
* ftfy
* accelerate
* pyngrok==4.1.1
* flask_ngrok





References

1. free stable diffusion app with a gpu backend](https://www.assemblyai.com/blog/build-a-free-stable-diffusion-app-with-a-gpu-backend/
2. https://youtu.be/wBCEDCiQh3Q
