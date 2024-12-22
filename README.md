import os

# Define README content
readme_content = """# Hi there, I'm Rahul Mamoria! 👋

Welcome to my GitHub profile! I'm a **Software Engineer** from India, passionate about building efficient, scalable, and user-friendly applications.

---

## 🚀 About Me

- 🌟 **Interests**: Gym, badminton, swimming, cafe racers, and bike rides.
- 💻 **Current Focus**: Angular, React, Node.js, and Next.js.
- 🎓 **Learning**: Performance optimization, state management, Docker, and Kubernetes.
- 🛠️ **Specialization**: Frontend development, technical architecture, and UI/UX design.

---

## 💼 My Tech Stack

### **Languages**:
![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)&nbsp;
![TypeScript](https://img.shields.io/badge/-TypeScript-05122A?style=flat&logo=typescript)&nbsp;
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![C++](https://img.shields.io/badge/-C++-05122A?style=flat&logo=c%2B%2B)&nbsp;

### **Frameworks and Libraries**:
![Angular](https://img.shields.io/badge/-Angular-05122A?style=flat&logo=angular)&nbsp;
![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react)&nbsp;
![Next.js](https://img.shields.io/badge/-Next.js-05122A?style=flat&logo=next.js)&nbsp;
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-05122A?style=flat&logo=tailwindcss)&nbsp;

### **Tools and Platforms**:
![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=node.js)&nbsp;
![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker)&nbsp;
![Kubernetes](https://img.shields.io/badge/-Kubernetes-05122A?style=flat&logo=kubernetes)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;

### **Other Tools**:
![Visual Studio Code](https://img.shields.io/badge/-VS%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;
![Postman](https://img.shields.io/badge/-Postman-05122A?style=flat&logo=postman)&nbsp;
![Figma](https://img.shields.io/badge/-Figma-05122A?style=flat&logo=figma)&nbsp;

---

## 📝 Top Projects

### [🌐 Portfolio Website](https://github.com/rahulmamoria/portfolio)
A personal portfolio showcasing my skills, projects, and achievements. Built with Angular and Tailwind CSS.

### [📊 Dashboard Application](https://github.com/rahulmamoria/dashboard-app)
An interactive and dynamic React application for visualizing business data. Features include real-time updates and chart components.

### [🔒 Authentication Service](https://github.com/rahulmamoria/auth-service)
A Node.js-based backend service for managing user authentication with JWT and role-based access control.

---

## 📫 How to Reach Me

- **Email**: [rahul.mamoria@example.com](mailto:rahul.mamoria@example.com)
- **LinkedIn**: [linkedin.com/in/rahulmamoria](https://linkedin.com/in/rahulmamoria)
- **Twitter**: [@rahul_mamoria](https://twitter.com/rahul_mamoria)

---

## 📊 GitHub Stats

![Rahul's GitHub stats](https://github-readme-stats.vercel.app/api?username=rahulmamoria&show_icons=true&hide=stars&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rahulmamoria&layout=compact&theme=radical)

---

## 🌟 Fun Fact
I love solving complex problems in both code and life! 💡
"""

# Write README file
with open("README.md", "w") as file:
    file.write(readme_content)

print("README.md has been created successfully!")
