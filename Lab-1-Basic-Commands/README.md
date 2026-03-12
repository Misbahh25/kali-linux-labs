# Kali Linux Basic Command Line Practice Lab

## Commands Used
```bash
# Step 1: Verify location
pwd
ls

# Step 2: Create workspace
mkdir linux_lab
cd linux_lab
pwd

# Step 3: Organize folders
mkdir docs notes temp
ls

# Step 4: Create files
touch docs/file1.txt
touch docs/file2.txt
touch notes/today.txt
ls docs
ls notes

# Step 5: Edit file
nano notes/today.txt
# (Type content, save with CTRL+O, exit with CTRL+X)

# Step 6: Analyze file
wc notes/today.txt

# Step 7: Remove file
rm docs/file2.txt
ls docs

# Step 8: Remove empty folder
rmdir temp
ls

# Step 9: Remove folder with content
rm -r docs
ls
