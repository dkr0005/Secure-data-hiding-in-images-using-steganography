# **Secure Data Hiding in Images Using Steganography** 🔐🖼️  

## **📌 Project Overview**  
This project implements **image-based steganography**, which enables users to securely **hide and extract secret messages within images**. It utilizes encryption techniques to ensure the confidentiality of hidden data, making it a powerful tool for secure communication.  

Steganography is the technique of concealing information within digital media, making it imperceptible to the naked eye. This project focuses on hiding text inside images while preserving their original appearance, ensuring that the hidden message remains undetectable unless extracted using the correct decryption process.  

---

## **🛠️ Features**  
- ✅ **Data Hiding** – Embeds secret messages into images without noticeable changes.  
- ✅ **Data Extraction** – Allows retrieval of hidden messages from modified images.  
- ✅ **Encryption & Decryption** – Uses secure encryption to protect hidden data.  
- ✅ **Password Protection** – Ensures only authorized users can extract the hidden data.  
- ✅ **Graphical User Interface (GUI)** – Provides an intuitive and easy-to-use interface.  
- ✅ **Lightweight & Fast** – Works efficiently without significant resource consumption.  

---

## **⚙️ How It Works**  
1. **Image Selection**: The user selects an image in which the secret message will be hidden.  
2. **Data Encryption & Embedding**:  
   - The user enters a secret message.  
   - The message is encrypted for security.  
   - The encrypted message is embedded within the selected image using steganographic techniques.  
3. **Modified Image Generation**: A new image is generated with the hidden message. This image appears unchanged to the human eye.  
4. **Data Extraction & Decryption**:  
   - The recipient loads the modified image into the tool.  
   - By entering the correct password, the hidden message is decrypted and displayed.  

---

## **🔒 Security Considerations**  
- **Encryption Mechanism**: The hidden message is encrypted before embedding, ensuring confidentiality.  
- **Steganographic Techniques**: The message is concealed within pixel values, making it nearly impossible to detect without extraction.  
- **Password Authentication**: Only users with the correct password can decrypt and retrieve the hidden data.  

---

## **📂 Project Structure**  
- **`tool_gui.py`** – GUI-based interface for user-friendly interaction.  
- **`encrypt.py`** – Script for encrypting and embedding data into images.  
- **`decrypt.py`** – Script for extracting and decrypting hidden data from images.  
- **`mypic.jpg`** – Sample input image for testing.  
- **`encryptedpic.png`** – Image containing hidden data.  
- **`Pass.txt`** – Stores encryption key/password for secure retrieval.  
- **`LICENSE`** – Project license file.
  ---
  - Use the GUI to hide or extract messages from images.  

### **2️⃣ Encrypting & Hiding Data**  
- Select an image as the base file.  
- Enter the secret message and provide a password for encryption.  
- The encrypted message is embedded into the image, generating a new **steganographic image**.  

### **3️⃣ Decrypting & Extracting Data**  
- Load the modified image into the tool.  
- Enter the correct password to retrieve the hidden message.  
- The extracted message is decrypted and displayed.  
---
