# SHA File

# 🔗 SHA File Hashing Utility
An efficient, client-side utility built with pure HTML, CSS (Tailwind CSS), and JavaScript for calculating cryptographic hashes of files. It utilizes the vetted CryptoJS library for reliable hashing algorithms.

This tool is essential for verifying data integrity, ensuring that a file has not been altered or corrupted during download or transfer.

# ✨ Core Functionality
Multiple Algorithms: Supports the calculation of SHA-1 (Legacy), SHA-256 (Recommended), and SHA-512 hashes.

Client-Side Hashing: All file processing and hashing occur locally in your browser. Files are never uploaded to a server, ensuring user privacy and speed.

File Size Display: Shows the name and human-readable size of the selected file.

Instant Copy: A dedicated button allows for quickly copying the resulting hash to the clipboard.

# 🚀 Live Demo
https://mitul841.github.io/SHA-FILE/
View Live Demo on GitHub Pages

# 🛠️ How to Use
Select Algorithm: Choose the required hash function (SHA-256 is the modern standard).

Choose File: Click the "Choose File" button and select the file you wish to verify from your local system.

Calculate Hash: Click the Calculate Hash button. A loading message will appear while the browser processes the file.

Verification: Compare the resulting hash value with the original hash provided by the file distributor (e.g., software vendor) to confirm integrity.

# ⚙️ Development Stack
Library: CryptoJS (for robust SHA implementation)

Styling: Tailwind CSS (loaded via CDN)

Language: JavaScript (ES6+) and HTML

Design: Fully responsive dark-mode interface with a focus on simplicity and accessibility.
