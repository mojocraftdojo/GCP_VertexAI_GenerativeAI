# GCP_VertexAI_GenerativeAI
 Creating and training LLMs-powered Generative AI models via Google Vertex AI SDK
 
 
 This Jupyter notebook shows several working examples just to demonstrate how to use vertex API to interact with google cloud and run generative AI apps powered by pre-trained large language models (LLMs). The list goes on and not just limited to the examples here. On top of language models, you can also run image models, video models and Speech models via corresponding APIs. 

You will need to have a google cloud GCP account, has at least vertex AI API enabled,  create a project, write down project_id and link it to the billing.

For programmable way to connect and run ML models on GCP, you need to install Google Cloud SDK first, complete the authenticate and some initial setup. You will also need to install vertex AI SDK and several other python libraries.

**Google Cloud SDK Authentication**

--   gcloud auth application-default login


**Set Proper Compute Region/Zones**

 --- gcloud config set compute/region us-central1 
 
 --- gcloud config set compute/zone us-central1-a
 
 Install python libraries
 
	pip install google-cloud-aiplatform --upgrade

 Import Vertex AI SDK
 
 	from google.cloud import aiplatform
 	
 Run the examples 