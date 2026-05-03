# 🚀 QR Code Generator (Node.js CLI)

A simple **Command Line QR Code Generator** built using **Node.js**.
This project allows users to enter any URL in the terminal and instantly generate a QR code image.

---

## 📌 Features

* 🧾 Takes user input via terminal
* 🔗 Converts URL into QR code
* 🖼 Generates QR image (`qr_image.png`)
* 📁 Saves entered URL in a text file (`URL.txt`)
* ⚡ Fast and beginner-friendly

---

## 🛠 Tech Stack

* **Node.js**
* **Inquirer** – for user input
* **qr-image** – for generating QR codes
* **File System (fs)** – for saving files

---

## 📂 Project Structure

```bash
QR-Code-Generator/
│── index.js
│── package.json
│── package-lock.json
│── qr_image.png   (generated)
│── URL.txt        (generated)
```

---

## ⚙️ How It Works

* The program prompts the user to enter a URL
* It generates a QR code image using `qr-image`
* Saves the QR as `qr_image.png`
* Stores the entered URL in `URL.txt`

Code reference: 

---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Shrijan18/QR-Code-Generator.git
cd QR-Code-Generator
```

### 2️⃣ Install dependencies

```bash
npm install
```

Dependencies used: 

---

### 3️⃣ Run the project

```bash
node index.js
```

---

## 🖥 Example Usage

```bash
Enter the URL: https://youtube.com
```

✔ Output:

* QR code image generated
* URL saved in file

---

## 📸 Output

Generated QR Code:

![QR Code](qr_image.png)

---

## 🎯 Future Improvements

* 🎨 Customize QR color & size
* 🌐 Convert into web app (React + Express)
* 📥 Option to download in different formats
* 📱 Add GUI interface

---

## 🤝 Contributing

Feel free to contribute:

1. Fork the repo
2. Create a new branch
3. Make changes
4. Submit a pull request

---

## 📜 License

This project is licensed under the **ISC License**.

---

## 👨‍💻 Author

**Shrijan**
GitHub: https://github.com/Shrijan18

---

⭐ If you like this project, don’t forget to **star the repo!**
