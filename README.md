# SE-Assignment2: Version Control Using GitHub

## Overview
This project was created as part of **CINS 5318 – Software Engineering (Fall 2025)** under the guidance of **Dr. Mary Kim**.  
The objective of this assignment is to gain practical experience using **Git** and **GitHub** for version control, collaboration, and documentation.

The project demonstrates:
- Repository creation and initial commit.
- Working with branches and pull requests.
- Merging and resolving conflicts.
- Tracking tasks using GitHub Issues.
- Maintaining a comprehensive project README.

---

## Project Description
This project features a simple “Hello, World!” program that was later enhanced to greet users personally.  
The initial version prints “Hello, World!”, and I modified it in another feature branch to give a personalized greeting to the user and to trigger a merge conflict:

feature-1 => Hello, World!

feature-2 => Hi! Benign John


---

## ⚙️ Installation Instructions

Follow these steps to clone and run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/johnbenign/SE-assignment2.git

# 2. Navigate into the project directory
cd SE-assignment2

# 3. (Optional) Create a new branch for modifications
git checkout -b feature-1

# 4. Run the HelloWorld.java in your favorite IDE
```

## Usage Example

### Output Example:

=> Hello, World!

=> Hi! Benign John

### Program Description:

- The program starts by displaying a simple "Hello World!" greeting.
- I then modified the to give a personalized greeting the user and to also force a merge conflict.

---

## 🌱 Branching and Merging Workflow

| Branch | Purpose | Status |
| --- | --- | --- |
| `main` | Contains the final merged project | ✅ Merged |
| `feature-1` | Added personalized greeting | ✅ Merged |
| `feature-2` | Simulated and resolved merge conflict | ✅ Merged |

## 🧠 GitHub Issues

Two GitHub Issues were created and managed to simulate real-world collaboration:

| Issue | Assigned To | Description | Status |
|:------|:-------------|:-------------|:--------|
| #1 Add installation instructions to README | Benign John | Documented setup steps and usage guide | ✅ Closed |
| #2 Improve Hello World feature with user input | Chukwuemeka Kingsley | Enhanced the program to personalize greetings | ✅ Closed |

---

## 📄 Reflection Summary

Using GitHub for this assignment improved understanding of collaborative version control.  
Key takeaways include:

- Effective use of branches for isolated development.  
- Understanding pull requests and code reviews.  
- Learning how to resolve merge conflicts.  
- Using Issues to track and manage tasks efficiently.




