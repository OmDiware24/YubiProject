# YubiProject
Text To Image LypSync Model


Lip Sync Video Generator 🎭🎙️
This project creates a realistic talking video by syncing lip movements with speech. We use:
✅ Amazon Polly to convert text into speech.
✅ Wav2Lip to sync the speech with a given image.

📌 How It Works?
1️⃣ Text-to-Speech: Convert text into audio using Amazon Polly.
2️⃣ Lip Syncing: Use Wav2Lip to sync the audio with an image.
3️⃣ Generate Video: The final output is a talking video!

🛠️ Steps to Run the Project
1️⃣ Clone the Project
bash
Copy
Edit
git clone https://github.com/your-username/your-repository.git
cd your-repository
2️⃣ Install Required Libraries
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Model
bash
Copy
Edit
python inference.py --checkpoint_path checkpoints/wav2lip_gan.pth --face image.jpg --audio generated_audio.wav
🎬 The final lip-sync video will be saved in the output folder.

📜 Project Links
📂 GitHub Repo: [Your Repo Link]
🎬 Lip-Sync Video: [Google Drive Link]
📄 Colab Notebook: [Colab Link]

🛠️ Tools & Technologies Used
Python 🐍
Amazon Polly 🔊
Wav2Lip 🎭
Google Colab ☁️
