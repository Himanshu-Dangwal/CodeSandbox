# 💻 CodeSandbox

This project aims to build a **CodeSandbox-like platform** where users can directly write and run code — similar to how they work in **VS Code**, but entirely in the browser.

## ✨ Vision

The goal is to eliminate the need for any installations or local setup. Users will be able to:

- Create full-fledged web applications right from the browser
- Install and manage dependencies (like `npm install`)
- Write, run, and preview their code in real-time
- Save and share projects instantly

> A truly **plug-and-code** experience — accessible anytime, anywhere.

---

## 🛠️ Content / Development Plan

### **Phase 1: Core Setup**
- [ ] Project structure with frontend and backend separation
- [ ] Set up Monaco Editor for in-browser coding
- [ ] Build the basic layout: Editor, Terminal, Preview

### Phase 2: Backend Integration
- [ ] Create a Node.js backend to:
  - Handle virtual file systems
  - Install dependencies (`npm`, `yarn`, etc.)
  - Run user code securely (inside Docker or sandboxes)
  - Serve preview builds
- [ ] Connect frontend to backend using REST or WebSocket

### **Phase 3: Live Preview & File Management**
- [ ] Render frontend code in a live preview (iframe-based)
- [ ] Allow users to create/save multiple files and folders
- [ ] Enable persistent project storage (database or local)

### **Phase 4: Dependency Management**
- [ ] Parse and install packages from `package.json`
- [ ] Serve installed modules from backend (e.g., via `/node_modules`)
- [ ] Show terminal output or errors from install/build

### **Phase 5: Project Features**
- [ ] User authentication
- [ ] Save and load projects from the cloud
- [ ] Shareable project URLs


---

## Tech Stack (Planned)

- **Frontend**: React, TypeScript, TailwindCSS
- **Editor**: Monaco Editor
- **Backend**: Node.js, Express
- **Execution**: Docker for isolated code execution (not completely sure about execution yet)
- **Storage**: MongoDB / PostgreSQL for saved projects
- **Live Preview**: iframe + WebSocket streaming
- **Package Management**: npm/yarn

---

## 🚀 Goal

To empower developers with a **zero-setup, full-featured coding environment** directly in the browser — ideal for prototyping, testing, and sharing live apps.

