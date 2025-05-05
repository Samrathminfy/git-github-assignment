# Basic Git Workflow Assignment

# Assignment - 1 (Easy)
## 📁 Repository Structure
- `assignment.txt`: The main text file used for demonstrating Git.
- `.git/`: Hidden directory containing Git data.
- `easy_screenshot.png`: Commit history image of the assignment

---

## 🧾 Commit History

### 1. `feat: add assignment file with sample content`
- Created `assignment.txt` with 5 lines of introductory content.

### 2. `docs: add 1 more line`
- Added a line elaborating on Git's capabilities.

### 3. `refactor: clarify description of GitHub`
- Reworded the GitHub description to make it clearer and more accurate.

### 4. `chore: remove redundant demonstration line`
- Removed a line that was no longer needed after editing.

---

## 🖼️ Screenshot of `git log`
![git log screenshot](easy_screenshot.png)

---

## 🔍 Git Diff Example
Run this command to view the most recent change:
```bash
git log --oneline
git diff HEAD~1 HEAD
