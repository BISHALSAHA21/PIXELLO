# PIXELLO

## AI-Based Image Generation using Stable Diffusion and Facial Recognition

### **📌 Overview**
PIXELLO is an AI-powered system that generates high-quality **facial images** based on **user-uploaded photos and provided names**. By leveraging **Stable Diffusion**, it generates **renowned and synthetic faces** rather than real-life common faces. The system integrates **face detection** to identify subjects in images and uses AI-driven enhancement techniques to create detailed outputs.

### **🛠️ Features**
✅ **Face Detection** – Identifies faces in uploaded images using recognition algorithms.  
✅ **Stable Diffusion-Based Image Generation** – Creates **renowned and synthetic** faces rather than real-life common ones.  
✅ **User Input Integration** – Accepts user-provided names and images for processing.  
✅ **Bounding Box Visualization** – Highlights detected faces in the uploaded image.  
✅ **Configurable AI Parameters** – Users can adjust model settings for image generation.  
✅ **High-Quality Image Output** – Ensures enhanced resolution using AI models.  
✅ **Side-by-Side Comparison** – Displays original and generated images for analysis.  
✅ **Generation Progress Tracking** – Monitors image quality improvement across inference steps.  

### **🔧 Technologies Used**
- **Stable Diffusion 2** (for AI-based image generation)  
- **Face Recognition Library** (`face_recognition`, `dlib`)  
- **Hugging Face Transformers** (for model inference)  
- **Diffusers Library** (for stable diffusion model execution)  
- **Python Libraries:** `torch`, `matplotlib`, `PIL`, `numpy`  

### **🚀 Getting Started**
#### **1️⃣ Clone the repository**
```bash
git clone https://github.com/BISHALSAHA21/PIXELLO.git
cd PIXELLO
```

#### **2️⃣ Install dependencies**
```bash
pip install -r requirements.txt
```

#### **3️⃣ Run the project**
```bash
python main.py
```

### **📊 Dataset & Model References**
- **Face Recognition Library (dlib):** [dlib.net](http://dlib.net/)  
- **Stable Diffusion Model:** [Hugging Face](https://huggingface.co/models)  
- **Colab Stable Diffusion Notebook:** [Hugging Face Diffusers](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb)  

### **🎨 Example Output**
#### **Input Image & Name:**
🖼️ *User uploads an image and provides a name.*  
![image](https://github.com/user-attachments/assets/2ad55f3d-c277-4856-9882-38ede3f82469)
![image](https://github.com/user-attachments/assets/2c784ec1-148e-40f5-93ef-55a67eca032d)




#### **Detected Face:**
📌 *System detects faces and marks them with bounding boxes.*  
![image](https://github.com/user-attachments/assets/ed64f158-c73b-488f-8c25-34aeff846b5b)
![image](https://github.com/user-attachments/assets/c5e7c368-000e-404a-b9c2-7a5be51b6148)


#### **Generated Facial Image:**
🎭 *AI generates a high-quality renowned facial image resembling the uploaded photo.*  
![image](https://github.com/user-attachments/assets/1b27f53a-2d9c-40a5-b513-3d73c59069e4)


#### **Image Comparison:**
🔍 *Original vs. AI-generated face displayed side by side.*  
![image](https://github.com/user-attachments/assets/af7eaec8-c15c-4102-bfb0-9ed8d6d38cef)


#### **Generation Progress:**
📈 *Monitors improvement across multiple inference steps.*  

### **🔮 Future Enhancements**
🚀 Improve realism using **GAN-based facial synthesis**  
🚀 Add **age progression/regression** for enhanced features  
🚀 Enable **real-time face swapping** using AI  
🚀 Deploy as an **interactive web app (Flask/Gradio)**  

### **📞 Contact**
📧 **[Your Email]**  
🔗 **[Your LinkedIn]**  

---
Let us know if you have any feedback or contributions! 🚀

