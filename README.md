# Practice Drill 1


# Step 1: First create the parent directory and sub childs using below commands
mkdir -p hello/five/six/seven
mkdir -p hello/one/two/three/four

# Step 2: To create the text file use cmd line 'touch'
touch hello/five/six/c.txt hello/five/six/seven/error.log
touch hello/one/a.txt hello/one/b.txt
touch hello/one/two/d.txt hello/one/two/three/e.txt hello/one/two/three/four/access.log

# Step 3: To Delete '.log' files present in all file first find them by their file type and extension names and to delete use -delete cmd line
find hello -type f -name "*.log" -delete

# Step 4: To write or edit any text file use nano cmd line
nano hello/one/a.txt   # (Used to edit the file)
cat hello/one/a.txt    # (To see the content inside the file)

# Step 5: To remove a directory and its contents use rm cmd line
rm -r hello/five

# Step 7: To rename a directory use mv cmd line
mv hello/one hello/uno

# Step 8: To move a file to a subdirectory use mv cmd line
mv hello/uno/a.txt hello/uno/two

# To see the file structure install tree and use tree cmd line
tree hello/
```

## Final Structure

```
hello/
└── uno
    ├── b.txt
    └── two
        ├── a.txt
        ├── d.txt
        └── three
            ├── e.txt
            └── four
```
