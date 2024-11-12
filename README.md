# GoatSwitch AI Chat VS Code Extension 🐐💬

Welcome to GoatSwitch AI, your ultimate AI-powered companion for modernizing and upgrading your codebases! 🚀

Imagine having an intelligent assistant right within your VS Code, guiding you through complex upgrades, refactoring legacy code, and ensuring your projects are always up-to-date with the latest standards. With GoatSwitch AI, you get an interactive, chat-based experience that not only simplifies your workflow but also provides real-time Git diffs to keep you in control of every change. 🧠💡

Say goodbye to tedious manual updates and hello to a smarter, faster, and more efficient way to code! 💻✨

A nicer version of the documentation is available at [GoatSwitch AI Chat Docs](https://docs.goatswitch.ai). 📚

---

## Key Features 🌟

- **AI-Powered Analysis**: Scans codebases to suggest modernization opportunities. 🔍
- **Interactive Modernization**: Chat interface to specify and refine tasks. 💬
- **Live Updates**: Real-time Git diff view for tracking changes. 📈
- **Safe Execution**: Git-tracked modifications for easy review and rollback. 🔄

---

## Requirements 📋

### For modernizing .NET Projects

- Base directory should be a Git repository 🗂️
- At least one .csproj file should be present 📄
- The .csproj file should not be in the root directory (open the parent directory instead) 📁
- Up to 10,000 LoC (free version) 📏

### For modernizing Java Projects

- Base directory should be a Git repository 🗂️
- A pom.xml or build.gradle file should be present 📄
- Up to 10,000 LoC (free version) 📏

### For modernizing any language (python, javascript/typescript, c++, go, rust, php, etc.)

- Base directory should be a Git repository 🗂️
- Up to 10,000 LoC (free version) 📏

---

## Installation 🛠️

1. Search "GoatSwitch AI Chat" in the VSCode Extensions Marketplace and click "Install." 🔍
2. Verify the GoatSwitch icon appears in the activity bar. ✅

![GoatSwitch Installed](media/gs_installed.png)

---

## Usage 🚀

1. **Open Folder**: Ensure there are no pending changes in the Git repository. 📂
2. **Select Project**: Click the GoatSwitch icon in VSCode to begin. 🐐
3. **Describe Task**: Specify tasks such as "Upgrade to .NET 8" or "Refactor legacy code patterns" and press "Enter". 📝
4. **Review AI Plan**: After generating a task plan, you can:
   - **Approve**: Confirm the AI plan, and watch real-time changes in the Git diff view. ✔️
   - **Decline and Revise**: Adjust the task description if the AI's plan doesn’t meet your needs and press "Enter". ✏️
5. **Review Changes**: After all steps are done, review the changes in the Git extension, commit or discard them and start a new task. 🔄

---

## Example Tasks 🛠️

### .NET

- Upgrade to .NET 8 🔄
- Migrate from BinaryFormatter to System.Text.Json 🔄
- Migrate logging to Serilog / NLog / Log4Net / Microsoft.Extensions.Logging 🔄
- Migrate to Newtonsoft.Json / System.Text.Json 🔄
- Migrate to Entity Framework Core 🔄
- Refactor legacy patterns 🛠️
- Refactor to record classes 🛠️
- Refactor to use advanced pattern matching 🛠️

### Java

- Update to Java 21 🔄
- Refactor legacy patterns 🛠️
- Remove deprecated APIs 🗑️
- Migrate to Hibernate 🔄

### Any Language

- Add xml-style docstrings 📖
- Migrate inline / html comments to XML docstrings 📖
- Refactor legacy patterns 🛠️
- Remove deprecated APIs 🗑️
- Improve code readability 📖
- Migrate to library/framework X 🔄

**Theses are just examples, GoatSwitch AI can handle a wide range of tasks. Just try it out!** 🚀

---

## Troubleshooting 🛠️

### Project Detection Issues

- Ensure project size < 10,000 LoC. 📏
- Check for .csproj/pom.xml/build.gradle file. 📄
- Verify repository is initialized with git and clean (no git pending changes). 🗂️

### Runtime Issues

- Reload VSCode window or restart VSCode if chat becomes unresponsive. 🔄
- If AI generates unexpected changes, use the VSCode Git extension to review and revert modifications. 🔄

### Platform Limitations

- Works on Windows, macOS, and Linux. 🖥️
- Unsupported on VSCode Web. 🌐

---

## Support 🆘

For bugs or feature requests, visit [GitHub Issues](https://github.com/GoatSwitch/web-docs). 🐛  
Email support available at hello@goatswitch.ai. 📧

## Acknowledgments 🙏

This extension includes code from [Claude Dev](https://github.com/cline/cline/tree/v1.9.0), licensed under the MIT License. 📜
