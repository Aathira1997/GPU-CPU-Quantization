# GPU and CPU Quantization on Airavata
AI4Bharat/Airavata Quantization + FastAPI Backend

AIM: 
This project aims to quantize the AI4Bharat/Airavata large language model for efficient, optimized performance on both CPU and GPU. The project also involves developing a FastAPI backend service to serve the quantized model for inference, with a focus on reducing latency and increasing throughput while maintainingthe  quality of generation. All inference metrics, such as latency and throughput, are to be captured and evaluated using a single-machine setup. 

Step-by-Step Procedure (GPU Quantization +FastAPI Backend): 

1. Install required libraries 
2. BitsAndBytes for 4-Bit Quantization 
3. Load the Model in 4-Bit on GPU
4. Define a Prompt Formatting Function
5. Create FastAPI Backend
6. FastAPI on Colab using Ngrok
7. Inference via Swagger UI
8. Performance Metrics 
