# 📝 Mad Libs Generator (Python)

This is a simple and fun Mad Libs-style game written in Python. It reads a story from a text file and replaces placeholders like `<noun>` or `<verb>` with words provided by the user.

---

## 📜 How It Works

1. A text file named `story.txt` contains a story with placeholders inside `< >`.
2. The Python script:
   - Reads the story from the file
   - Finds all unique placeholders like `<noun>`, `<verb>`, etc.
   - Prompts the user to enter a word for each placeholder
   - Replaces all placeholders in the story
3. The final story is printed with all user input filled in!

---

## ▶️ How to Use

1. Clone or download this repository.
2. Create a file called `story.txt` in the same directory and write your story using `<word>` placeholders.

Example `story.txt`:
```
Once upon a time, there was a <adjective> <noun> who loved to <verb> every single day.
```

3. Run the script:

```bash
python mad_libs.py
```

4. You’ll be prompted to enter words for each placeholder.
5. The completed story will be printed!

---
