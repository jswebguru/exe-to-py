## Exe-To-Py

Decompile exe made by pyInstaller to its original py file.

### Install dependencies

```command
    git clone git@github.com:jswebguru/exe-to-py.git
    cd exe-to-py
    pip install -r requirements.txt
```

### Run
1. At first please copy exe file into this repository
2. Run 'Python pyinstxtractor.py [exe file]'
3. Go to extracted folder and check [FileName].pyc or struct file.
4. Copy and paste the header of struct file into [FileName].pyc and save it.
5. Just run 'uncompyle6/decompyle3 [FileName].pyc > [Output].py'.

### Notes.
If the scripts was written by py39, it's impossible to decompile because uncompyle/decompyle doesn't support py39.
