# Flask Stable Diffusion Application to generate Image 

Example app that demonstrates how to run a Flask app with a free GPU using Google Colab and ngrok.



## Instructions

- Open the Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AssemblyAI-Examples/flask-gpu-app/blob/main/notebook.ipynb)

- Go to [ngrok.com](ngrok.com), get a free API token, and in the Colab replace **YOUR-AUTHTOKEN-HERE** with the token.

  ![Screenshot 2024-01-02 195541](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/c0e1cccf-9e69-445f-b648-fc68e589bbc7)


- Set the runtime to GPU

  ![image](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/4bff0cb3-060a-4860-980e-6f05259889f1)


- Click on `Runtime -> Run all`

- In the output cell you should see a url similar to this: Running on something like **http://ca29-35-185-229-95.ngrok-free.app**. Open this url and use your application.

![Screenshot 2024-01-02 195908](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/48e72051-ce34-42f6-b5c1-85e6ec87554f)


User prompt: Ashoka the great the Indian king

The output is a as below:

![Screenshot 2024-01-02 200013](https://github.com/ParthaPRay/Flask-Stable-Diffusion-Model-ngrok/assets/1689639/5a8525df-e16f-49db-b670-32b942439dc6)


References

1. free stable diffusion app with a gpu backend](https://www.assemblyai.com/blog/build-a-free-stable-diffusion-app-with-a-gpu-backend/
2. https://youtu.be/wBCEDCiQh3Q
