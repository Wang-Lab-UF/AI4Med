# AI4Med: Artificial Intelligence for Medical and Veterinary Students

**Instructor:** Dr. Yiquan Wang (wang.yiquan@ufl.edu)  
**Semester:** Spring 2026  
**Course Website:** [View Full Syllabus](https://wang-lab-uf.github.io/AI4Med/)

Welcome to AI4Med! This repository contains the course website and will serve as the central hub for all student project submissions.

## Course Overview

This course is designed to help medical and veterinary students with no computer science background:
- Build a big picture understanding of AI/ML techniques
- Learn to use modern AI development tools (Cursor, GitHub Copilot, ChatGPT, Claude, etc.)
- Apply AI to real-world applications (web and game development)
- Reproduce and understand AI research models in life sciences

## For Students

### Viewing the Course Website

**Option 1: View on GitHub Pages**
Visit the live course website at: `https://wang-lab-uf.github.io/AI4Med/`

**Option 2: View Locally**
Clone this repository and open `index.html` in your browser:
```bash
git clone https://github.com/Wang-Lab-UF/AI4Med.git
cd AI4Med
open index.html  # macOS
# or double-click index.html on Windows/Linux
```

### Submitting Your Projects

All course assignments will be submitted as folders in this repository. Follow these steps:

#### 1. Fork and Clone the Repository

First, fork this repository to your own GitHub account, then clone it:
```bash
git clone https://github.com/YOUR-USERNAME/AI4Med.git
cd AI4Med
```

#### 2. Create Your Student Folder

Create a folder with your name (use format: `FirstnameLastname`):
```bash
mkdir projects/FirstnameLastname
cd projects/FirstnameLastname
```

#### 3. Organize Your Assignments

Create subfolders for each assignment:
```
projects/FirstnameLastname/
├── assignment1-ai-tools/
│   ├── README.md
│   ├── tool-exploration-report.pdf
│   └── mini-projects/
├── assignment2-web-app/
│   ├── README.md
│   ├── src/
│   └── documentation.pdf
├── assignment3-model-reproduction/
│   ├── README.md
│   ├── notebook.ipynb
│   └── report.pdf
└── final-project/
    ├── README.md
    └── [your project files]
```

#### 4. Add Your Work

```bash
# After creating your assignment folder and adding files
git add .
git commit -m "Add Assignment 1 - [Your Name]"
git push origin main
```

#### 5. Submit via Pull Request

1. Go to your forked repository on GitHub
2. Click "Pull Request" → "New Pull Request"
3. Title format: `[Assignment X] - [Your Name]`
4. In the description, include:
   - Brief summary of your project
   - Any special instructions for running your code
   - Challenges you faced and how you solved them
5. Submit the pull request

**Note:** Each assignment should be submitted as a separate pull request.

### Assignment Submission Checklist

For each assignment, make sure your folder includes:
- ✅ **README.md** - Overview, how to run your code, dependencies
- ✅ **Source code** - All code files, well-commented
- ✅ **Documentation** - Written reports as PDF
- ✅ **Requirements** - `requirements.txt` for Python projects, `package.json` for Node.js
- ✅ **Demo** - Screenshots, video links, or deployed app URLs

### Getting Help

- **Technical Issues:** Open an issue in this repository
- **Course Questions:** Email instructor or ask during office hours
- **Assignment Clarifications:** Check the course website or create a discussion thread
- **Code Help:** Use course Slack/Discord (link on course website)

## Course Structure

### 14-Week Curriculum
1. **Weeks 1-4:** AI fundamentals and development tools mastery
2. **Weeks 5-6:** Web application development with AI assistance
3. **Weeks 7-8:** AI in medical imaging and natural language processing
4. **Weeks 9-11:** AI in life sciences research and veterinary medicine
5. **Weeks 12-14:** Ethics, advanced topics, and final projects

### Major Assignments
- **Assignment 1:** AI Tools Mastery Portfolio (15%)
- **Assignment 2:** Healthcare Web Application (25%)
- **Assignment 3:** Research Model Reproduction (25%)
- **Final Project:** Student choice project (15%)
- **Participation:** Weekly exercises and engagement (20%)

## Website Features

- **Minimalist Design:** Inspired by Stanford CS229 and UIUC course websites
- **Comprehensive Syllabus:** 14 weeks of detailed topics and readings
- **Practical Focus:** Hands-on labs and real-world projects
- **Extensive Resources:** Curated lists of tools, tutorials, datasets, and papers
- **Responsive Design:** Works on desktop, tablet, and mobile devices

## Repository Structure

```
AI4Med/
├── index.html              # Course website (syllabus, schedule, assignments)
├── style.css               # Website styling
├── README.md               # This file (student guide)
└── projects/               # Student project submissions
    ├── StudentName1/
    │   ├── assignment1-ai-tools/
    │   ├── assignment2-web-app/
    │   ├── assignment3-model-reproduction/
    │   └── final-project/
    ├── StudentName2/
    │   └── ...
    └── ...
```

## For Instructors

### Initial Setup

1. **Create the repository on GitHub**
2. **Push the course website:**
   ```bash
   git init
   git add index.html style.css README.md
   git commit -m "Initial commit: AI4Med course website"
   git branch -M main
   git remote add origin https://github.com/Wang-Lab-UF/AI4Med.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Select main branch as source
   - Site will be live at `https://wang-lab-uf.github.io/AI4Med/`

4. **Create projects folder structure:**
   ```bash
   mkdir projects
   touch projects/.gitkeep
   git add projects/.gitkeep
   git commit -m "Add projects folder for student submissions"
   git push
   ```

5. **Update README links:**
   - All URLs have been updated to Wang-Lab-UF

### Managing Student Submissions

**Review Process:**
1. Students will submit pull requests with their assignments
2. Review code and provide feedback via PR comments
3. Request changes if needed or approve and merge
4. Grade based on merged submissions

**Folder Organization:**
- Each student gets one folder: `projects/FirstnameLastname/`
- Students create subfolders for each assignment
- Keep the main branch clean (website files only initially)
- All student work goes in `projects/` folder

**Grading Tips:**
- Use GitHub's review features for inline code comments
- Create grading rubric as issue templates
- Tag students in comments using @username
- Use labels: "assignment1", "assignment2", "needs-revision", "approved"

## Customization

### Update Course Information
Edit `index.html` to customize:
- Instructor name and contact information
- Meeting times and locations
- Semester/year
- Any course-specific details

### Modify Styling
Edit `style.css` to adjust:
- Colors and fonts
- Layout and spacing
- Responsive breakpoints

### Add Content
- Add new sections by following the existing HTML structure
- Update the navigation menu when adding new sections
- Keep the minimalist aesthetic consistent

## Design Philosophy

This website follows academic course website best practices:

1. **Simplicity:** Clean, distraction-free layout focusing on content
2. **Accessibility:** High contrast, readable fonts, semantic HTML
3. **Clarity:** Clear hierarchy and organization of information
4. **Professionalism:** Academic tone appropriate for university courses
5. **Practicality:** All essential information on one scrollable page

## Course Philosophy

This course recognizes that:
- Medical and veterinary students bring valuable domain expertise
- AI tools can democratize software development for non-programmers
- Understanding AI concepts is more important than low-level implementation details
- Real-world applications motivate learning better than abstract theory
- Reproducibility is crucial in both research and clinical applications

## Target Audience

- Medical students interested in digital health and medical informatics
- Veterinary students exploring AI applications in animal health
- Graduate students in life sciences needing computational skills
- Healthcare professionals wanting to understand AI systems
- Anyone in biomedical fields curious about practical AI applications

## Prerequisites

No programming experience required! Students need:
- Basic understanding of their medical/veterinary domain
- Comfort with using computers and learning new software
- Willingness to experiment and embrace a growth mindset
- Access to a computer and internet connection

## Learning Outcomes

By the end of this course, students will be able to:
1. Explain fundamental AI/ML concepts and their applications in healthcare
2. Use AI-powered development tools to build software efficiently
3. Create functional web applications for healthcare purposes
4. Reproduce published AI research models from literature
5. Critically evaluate AI systems for medical applications
6. Understand ethical considerations and limitations of medical AI
7. Continue learning and applying AI in their future careers

## Technologies Covered

- **AI Tools:** Cursor, GitHub Copilot, ChatGPT, Claude, Hugging Face
- **Programming:** Python basics, JavaScript fundamentals
- **Web Development:** HTML, CSS, JavaScript, React basics
- **ML Frameworks:** Scikit-learn, PyTorch, TensorFlow (introductory)
- **Data Science:** Pandas, NumPy, Matplotlib, Jupyter notebooks
- **Deployment:** GitHub Pages, Netlify, basic cloud platforms

## Resources

The course website includes extensive resources:
- Free online courses and tutorials
- AI development tools and platforms
- Medical AI datasets and challenges
- Research papers and literature
- Community forums and support

## Acknowledgments

This course design is inspired by:
- [CS229: Machine Learning (Stanford)](https://cs229.stanford.edu/)
- [CS 498 DL: Deep Learning (UIUC)](https://slazebni.cs.illinois.edu/spring21/)
- DeepLearning.AI's AI for Medicine Specialization
- Stanford's BIODS 220: AI in Healthcare

## License

This course website template is provided as-is for educational purposes. Feel free to adapt and modify for your own teaching needs.

## Important Links

- 📧 **Instructor Email:** wang.yiquan@ufl.edu
- 🌐 **Course Website:** [View on GitHub Pages](https://wang-lab-uf.github.io/AI4Med/)
- 💬 **Course Discussion:** [Link to Slack/Discord - TBD]
- 📝 **Assignment Submissions:** Submit via Pull Request to this repository
- 📂 **GitHub Repository:** [Wang-Lab-UF/AI4Med](https://github.com/Wang-Lab-UF/AI4Med)

## Academic Integrity

All submitted work must be your own. You are encouraged to:
- ✅ Use AI tools (Cursor, Copilot, ChatGPT, etc.) to assist your coding
- ✅ Collaborate and discuss concepts with classmates
- ✅ Search for solutions and learn from online resources

However, you must:
- ❌ Not copy code directly from classmates
- ❌ Not submit others' work as your own
- ❌ Always document AI assistance and external resources used

**Required:** In your README for each assignment, include a section "AI Tools & Resources Used" listing:
- Which AI tools you used and for what tasks
- External tutorials, Stack Overflow posts, or code you referenced
- Collaborations with classmates (discussion only, not code sharing)

---

**Note:** This course website was created with AI assistance (Cursor + Claude) as a demonstration of the tools and techniques taught in this course.

## Future Enhancements

Potential additions for future iterations:
- Interactive JavaScript elements (collapsible sections, search functionality)
- Student project gallery
- Video lecture embedding
- Discussion forum integration
- Assignment submission portal
- Calendar view of schedule
- Downloadable syllabus PDF

Keep it minimal for now, but these features can be added as needed!

