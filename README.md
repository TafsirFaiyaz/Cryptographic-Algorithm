# 🔒 Cryptographic Algorithms Repository

Welcome to the **Cryptographic Algorithms** repository. This project is a collection of Python implementations and theoretical documentation for various cryptographic techniques, ranging from classical ciphers to modern encryption standards and digital signatures.

The code is primarily written in Python using **Jupyter Notebooks**, making it easy to visualize and experiment with the algorithms step-by-step.

## 📂 Repository Contents

This repository covers the following core areas of cryptography:

### 1. Classical Cryptography
Implementation of historical encryption techniques used to understand the basics of substitution and shifting.
* **Caesar Cipher:** Simple substitution method shifting alphabets.
* **Substitution Cipher:** Replacing plaintext with ciphertext based on a fixed system.

### 2. Symmetric Key Cryptography
Algorithms where the same key is used for both encryption and decryption.
* **AES (Advanced Encryption Standard):** A robust block cipher used globally.
* **DES (Data Encryption Standard):** An older symmetric-key block cipher.
* **A5/1 Algorithm:** A stream cipher used to provide over-the-air privacy in GSM cellular standards.

### 3. Asymmetric Key Cryptography
Algorithms that use a pair of keys (public and private) for secure communication.
* **RSA (Rivest–Shamir–Adleman):** One of the first public-key cryptosystems widely used for secure data transmission.
* **ECC (Elliptic Curve Cryptography):** An approach to public-key cryptography based on the algebraic structure of elliptic curves.

### 4. Hashing & Data Integrity
Techniques to ensure data has not been altered.
* **Hashing Algorithms:** Implementations of various hash functions.
* **MAC (Message Authentication Code):** verifying the integrity and authenticity of a message.
* **MAC Signature:** Digital signatures using MAC mechanics.

### 5. Steganography
* **Steganography:** The practice of concealing a message within another file (e.g., an image or text).

---

## 📄 File Structure

| File Name | Description |
| :--- | :--- |
| `A51 Algorithm.ipynb` | Implementation of the A5/1 stream cipher. |
| `AES Algorithm.ipynb` | Code walkthrough for the AES encryption standard. |
| `Caesar_Cipher .ipynb` | Python implementation of the Caesar Cipher. |
| `Des_Algorithm.ipynb` | Code for Data Encryption Standard (DES). |
| `ECC.ipynb` | Implementation of Elliptic Curve Cryptography. |
| `MAC_Signature.ipynb` | Demonstrates Message Authentication Codes and Signatures. |
| `RSA.ipynb` | Step-by-step RSA encryption and decryption code. |
| `Steganography.ipynb` | Scripts for hiding data within files. |
| `Substitution_Cipher.ipynb` | Implementation of general substitution ciphers. |
| `Types_of_Hashing.ipynb` | Examples of different hashing functions (MD5, SHA, etc.). |
| `*.pdf` files | Supporting documentation and theoretical explanations for the algorithms. |

---

## 🚀 Getting Started

To run the codes in this repository, you will need **Python** installed along with **Jupyter Notebook**.

### Prerequisites
Ensure you have the following installed:
* Python 3.x
* Jupyter Notebook or JupyterLab

### Installation
1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/repository-name.git](https://github.com/your-username/repository-name.git)
    ```
2.  Navigate to the directory:
    ```bash
    cd repository-name
    ```
3.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

---

## 🤝 Contributing

Contributions are welcome! If you have a new algorithm to add or an optimization for existing codes:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/NewAlgorithm`).
3.  Commit your changes.
4.  Push to the branch and open a Pull Request.

## 📝 License

This project is open-source and available for educational purposes.

👨‍💻 Author

TafsirFaiyaz
