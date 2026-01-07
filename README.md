# Nitish Kumar ASCII Art Project 

##  Project Title
**ASCII Art Representation of Nitish Kumar Using Python**

---

##  Project Description
This project converts an image of Nitish Kumar into a colored ASCII art representation using core Python logic. The program reads a 24-bit BMP image directly at the binary level, manually extracting image dimensions and RGB pixel data without relying on external image-processing libraries.

The image is resized using a nearest-neighbor algorithm to match terminal display constraints while maintaining the original aspect ratio. Each pixel’s color values are optionally enhanced to improve visual clarity. The processed pixels are then mapped to ASCII characters (*) and rendered in the terminal using ANSI escape sequences for true-color output.

The result is a terminal-based ASCII portrait that demonstrates low-level file handling, logical image processing, and character-based rendering using pure Python.

---

##  Objectives
- Apply Python fundamentals such as loops, conditionals, and functions  
- Understand binary file handling  
- Convert image pixel data into ASCII characters  
- Improve logic-building and creativity
- Generate terminal-based visual output using ANSI colors  

---

##  How the Program Works

### 1️⃣ Image Input
- The program reads a 24-bit BMP image(`output.bmp`) using manual binary file operations.
- Image width, height, and RGB pixel values are extracted without using external libraries.

### 2️⃣ Image Processing
- The image is resized using nearest-neighbor logic to fit terminal dimensions.
- Aspect ratio is maintained for correct visual appearance.

### 3️⃣ Color Enhancement
- RGB values are manually enhanced to improve color clarity.
- This step increases visual quality without using image libraries.

### 4️⃣ ASCII Conversion
- Each pixel is mapped to the `*` character.
- ANSI escape codes are used to display colored ASCII characters in the terminal.

### 5️⃣ Output Display
- The final ASCII art image of Nitish Kumar is printed directly to the terminal.

---

## ▶ How to Run the Program

### Step 1: Image Preparation
- Convert the image of Nitish Kumar to 24-bit BMP format
- Rename the file to:
- Place it in the same directory as the Python file.

### Step 2: Run the Program
Open the terminal and execute:

### Step 3: View Output
- The ASCII art will appear in the terminal.
- Ensure the terminal supports ANSI color output.

---

##  Technologies Used
- Python 3
- Loops and Conditional Statements
- Functions
- File Handling
- Binary Data Processing
- ANSI Escape Codes

---

##  Project Structure
```text
Nitish-Kumar-ASCII-Art/
│
├── ascii_art.py
├── output.bmp
└── README.md
```
---

##  Learning Outcomes
- Improved understanding of Python core concepts  
- Experience with low-level file handling  
- Logical thinking and problem-solving  
- Creative application of programming fundamentals  

---

##  Student Declaration
This project is submitted as part of the Minor II academic requirement and is created using my own understanding of Python programming fundamentals.

---

 *End of README*


