# 🧬 Protein Workflows

### *The digital drafting board for protein engineering pipelines.*

This repository is currently a **centralized dumping space** for architectural ideas, automation requests, and existing workflows. We are focusing on gathering requirements and identifying pain points before moving into active development.

---

## 🚦 Current Status: Gathering Ideas & Existing Work
**This is not a production code repository (yet).** 

We are cataloging what the protein engineering community needs on Isambard, while also collecting existing scripts or containers that could serve as building blocks.

---

## 💡 How to Contribute
If you have a workflow idea or a "wishlist" item, please contribute by opening an issue. 

### 🔍 Search First
Please browse existing issues before creating a new one. If someone has already raised your idea, **interact with it!** Comment with your support or add further technical details. This helps us gauge which tools are the most high-priority.

### 📝 Creating a Request
1. Navigate to the **[Issues](../../issues)** tab.
2. Check if your software/workflow is already listed.
   - If **yes**: Add your thoughts to the discussion at the bottom of that issue.
   - If **no**: Click **New Issue** and use template for workflow requests.
3. **Include Credits:** In your request, please mention anyone currently working on this or individuals/groups who have previously developed similar pipelines. This ensures we don't reinvent the wheel and give credit where it's due.

---

## 📂 The "Dump Space"
We are also accepting existing assets that might help the project. If you have useful snippets, please contribute them to the following areas:

### 🐳 Containers & Environments
If you have working **Dockerfiles**, **Apptainer/Singularity** definitions, or **Conda** `.yaml` files that successfully run protein tools (especially on HPC clusters like Isambard), please add them to the `/containers` directory.
For now feel free to push to main

### 📜 Useful Scripts
Any pipelines that or otherwise relevant Bash/ Python scripts that might be useful 
- Add it to the `/scripts` directory.
- Include a brief comment at the top of the file explaining what it does and who wrote it.
(https://github.com/digiengbi). 
For now feel free to push to main

> **Goal:** To turn fragmented structural biology tools into seamless, reproducible workflows.
