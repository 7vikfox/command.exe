## 📄 Commands Used During Development

### 📁 Navigation

```bash
dir
cd <folder_name>
cd ..
```



### 📄 File Creation & Editing (Windows CMD)

```bash
echo . > filename.py
notepad filename.py
```



### 🐍 Python & Package Management

```bash
python --version
python -m pip install --upgrade pip
python -m pip install pytest
python -m pip list
python -m ensurepip
```



### 🧪 Running Tests

```bash
pytest test_file.py
python -m pytest test_file.py
python test_file.py
```



### 🔧 Git Workflow

```bash
git status
git add .
git commit -m "message"
git push
git pull
```



### 🌿 Branch Management

```bash
git checkout -b <branch_name>
git push origin <branch_name>
```



### 🧹 Squashing Commits (optional)

```bash
git reset --soft HEAD~<n>
git commit -m "clean commit message"
git push --force
```



### 🔍 Inspecting History

```bash
git log --oneline
```



### 📂 Rename Directory (Windows)

```bash
ren <old_name> <new_name>
```



## ✅ Notes

* Commands were executed in the project root directory.
* `python -m` was used to avoid PATH issues.
* Squashing was optional depending on PR requirements.



