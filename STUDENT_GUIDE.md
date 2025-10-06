# Quick Start Guide for Students

Welcome to AI4Med! This guide will help you get started with the course and submit your assignments.

## 📚 Step 1: View the Course Website

Visit the course website to see the full syllabus, schedule, and assignment details:
- **Online:** [https://wang-lab-uf.github.io/AI4Med/](https://wang-lab-uf.github.io/AI4Med/)
- **Locally:** Open `index.html` in your browser

## 🔧 Step 2: Set Up Your Development Environment

### Install Git
- **macOS:** Git is pre-installed
- **Windows:** Download from [git-scm.com](https://git-scm.com/)
- **Linux:** `sudo apt-get install git`

Verify installation:
```bash
git --version
```

### Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Sign up for a free account
3. Verify your email address

### Install Code Editor
Choose one:
- **Cursor** (recommended for this course): [cursor.sh](https://cursor.sh)
- **VS Code**: [code.visualstudio.com](https://code.visualstudio.com/)

### Install Python
Download Python 3.8+ from [python.org](https://python.org)

Verify installation:
```bash
python3 --version
```

### Install Node.js (for web development assignments)
Download from [nodejs.org](https://nodejs.org)

Verify installation:
```bash
node --version
npm --version
```

## 📝 Step 3: Submit Your First Assignment

### Fork the Repository
1. Go to the main course repository on GitHub
2. Click the **Fork** button (top right)
3. This creates your own copy of the repository

### Clone Your Fork
```bash
# Replace YOUR-USERNAME with your GitHub username
# The main repository is at: https://github.com/Wang-Lab-UF/AI4Med
git clone https://github.com/YOUR-USERNAME/AI4Med.git
cd AI4Med
```

### Create Your Student Folder
```bash
# Replace FirstnameLastname with your actual name (no spaces)
mkdir -p projects/FirstnameLastname
cd projects/FirstnameLastname
```

### Create Assignment Folder
```bash
# For Assignment 1
mkdir assignment1-ai-tools
cd assignment1-ai-tools
```

### Copy the Template
```bash
# Copy the template to get started
cp ../../ASSIGNMENT_TEMPLATE.md README.md
```

### Add Your Work
1. Write your code
2. Create documentation
3. Add screenshots/demos
4. Fill out the README.md

### Commit Your Changes
```bash
# From your assignment folder
git add .
git commit -m "Add Assignment 1 - [Your Name]"
git push origin main
```

### Create a Pull Request
1. Go to your forked repository on GitHub
2. Click **Pull Request** → **New Pull Request**
3. Fill out the PR template (it will appear automatically)
4. Click **Create Pull Request**

**Done!** Your assignment is submitted. The instructor will review and provide feedback.

## 🎯 Assignment Submission Checklist

Before submitting each assignment, make sure you have:

- [ ] Created folder: `projects/YourName/assignment-X/`
- [ ] Included comprehensive `README.md`
- [ ] Added all source code with comments
- [ ] Included `requirements.txt` or `package.json`
- [ ] Wrote documentation/report (PDF)
- [ ] Added demo materials (screenshots, video, or deployed URL)
- [ ] Documented all AI tools and resources used
- [ ] Tested that code runs on a fresh environment
- [ ] Committed and pushed to your fork
- [ ] Created pull request with filled template

## 💡 Tips for Success

### Using AI Tools Effectively
1. **Start with a clear goal** - Know what you want to build
2. **Iterate** - Use AI suggestions as starting points, then refine
3. **Understand the code** - Don't just copy-paste, learn what it does
4. **Debug actively** - AI tools make mistakes, you need to catch them
5. **Document usage** - Note what tools helped with what tasks

### Writing Good Documentation
- Explain **what** your project does and **why**
- Include **how** to run it step-by-step
- Describe **challenges** and how you overcame them
- Reflect on **what you learned**

### Getting Help
1. **Check the course website first** - Answers may already be there
2. **Search online** - Stack Overflow, documentation, tutorials
3. **Use AI assistants** - ChatGPT, Claude, Cursor can help debug
4. **Ask classmates** - Discuss concepts (but don't share code)
5. **Office hours** - Email instructor to schedule time
6. **Open an issue** - Use GitHub issues for technical questions

## 🚨 Common Mistakes to Avoid

1. ❌ **Waiting until the last minute** - Start early!
2. ❌ **Not testing your code** - Always test before submitting
3. ❌ **Poor documentation** - A great project needs great docs
4. ❌ **Forgetting dependencies** - Include requirements.txt or package.json
5. ❌ **Not using version control properly** - Commit often with clear messages
6. ❌ **Ignoring the template** - Use the provided structure
7. ❌ **Not documenting AI usage** - This is required!

## 📖 Learning Resources

### Git & GitHub
- [GitHub Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [Learn Git Branching](https://learngitbranching.js.org/) (interactive)

### Python
- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [Real Python Tutorials](https://realpython.com/)

### Web Development
- [MDN Web Docs](https://developer.mozilla.org/)
- [freeCodeCamp](https://www.freecodecamp.org/)

### AI/ML
- Course website has comprehensive resources!
- Start with the recommended readings for each week

## 🎓 Academic Integrity Reminder

You **CAN**:
- ✅ Use AI tools extensively (document usage)
- ✅ Search online for help and tutorials
- ✅ Discuss concepts with classmates
- ✅ Get inspiration from open-source projects

You **CANNOT**:
- ❌ Copy code from classmates
- ❌ Submit someone else's work
- ❌ Use code without attribution
- ❌ Fail to document AI assistance

**Golden Rule:** If you used it, document it. Transparency is key!

## ❓ FAQ

### Q: What if I'm not comfortable with programming?
**A:** That's okay! This course is designed for beginners. Use the AI tools to help you learn, and don't hesitate to ask for help.

### Q: Can I work with a partner?
**A:** Assignments are individual unless explicitly stated as group work. You can discuss concepts but must write your own code.

### Q: What if my code doesn't work?
**A:** Document what you tried and what errors you got. Partial credit is given for effort and learning.

### Q: How much should I use AI tools?
**A:** As much as you want! Just document it. The goal is to learn, and AI tools are part of that learning.

### Q: What if I can't deploy my web app?
**A:** Include clear instructions for running locally and screenshots/video of it working. Deployment is encouraged but not always required.

### Q: Can I use ChatGPT to write my README?
**A:** You can use it to help structure or refine your writing, but the content should be your own thoughts and experiences. Document this usage.

### Q: What if I finish early?
**A:** Great! Add extra features, improve documentation, or help classmates (by explaining concepts, not sharing code).

## 📧 Contact

- **Instructor:** Dr. Yiquan Wang
- **Email:** wang.yiquan@ufl.edu
- **Course Website:** [View Syllabus](https://wang-lab-uf.github.io/AI4Med/)
- **GitHub Repo:** [Wang-Lab-UF/AI4Med](https://github.com/Wang-Lab-UF/AI4Med)

## 🚀 Ready to Start?

1. Fork the repository
2. Clone to your computer
3. Create your folder
4. Start Assignment 1
5. Have fun learning AI!

Good luck! 🎉

---

*This guide was created to help you succeed in AI4Med. If you have suggestions for improvements, let the instructor know!*

