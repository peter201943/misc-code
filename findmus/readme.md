



# Searching for Files




## About
- Testing ag, batch ability to search files for tags
- Created 2021-05-09T13:59:00-05:00
- Creator mangelsdorf-peter-james.1999-02-11.201943




## Plan
```bash
# Step 1: Find all files named "music"
ag -g music > search.txt
# Step 2: Find all files with sections tagged "music"
ag -l "\n- music" > search.txt
# Step 3: In each file, find all lines following each `## [title](url)` and before the next section
for /F 
# Step 4: Open results in text editor
code results.md
```



## Expected Results
- Want all 23 sections combined together in a single file
- Want none of the 20 other sections






