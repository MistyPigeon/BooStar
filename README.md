# Boo\* (BooStar) 🌟

Boo\* is a not-ready **universal-purpose**, **lightweight**, and **minimalist** programming language inspired by Boo — redesigned for clarity, speed, and clean syntax.

## 🚀 Core Features

- `func` to define functions
- `ret` to return values
- `prnt@"Hello"@` for printing
- `x=5` for assignment, `x = 5` for comparison
- `~` to start indented blocks (no `{}`)
- `nil`, `tru`, `f-` for null, true, and false
- Minimal parentheses and punctuation

## 🧠 Sample Code

```boo
func greet(name: str) -> str ~
    ret@"Hello, " + name + "!"@

x=5
if x = 5 ~
    prnt@"Hi five!"@
else ~
    prnt@"Nope."@

🔧 Goal
Boo* aims to be:

Beginner-friendly

Extremely clean

Fast to type

Fun to write 

📌 Status
Language design ongoing. Parser and interpreter to be built soon.



---

### ✅ Step 2: Create a **`docs/spec.md`** File
Make a folder called `docs/` and add this file to outline Boo\*'s syntax rules.

**📄 `docs/spec.md`**
```markdown
# Boo\* Language Specification (v0.1)

## 📚 Keywords

| Purpose        | Keyword |
|----------------|---------|
| Define function | `func` |
| Return value    | `ret`  |
| Import module   | `imprt` |
| True / False    | `tru` / `f-` |
| Null / None     | `nil`  |
| Print           | `prnt` |
| Code Block Start | `~`   |

## 📦 Syntax Rules

### 🟢 Assign vs Compare
- Assignment: `x=5`
- Comparison: `x = 5`

### 🟢 Strings and Expressions
Use `@...@` to wrap string or expression content.
- `prnt@"Hello"@`
- `ret@x + 1@`

### 🟢 Code Blocks
Use `~` at the start of an indented block.

```boo
if x = 5 ~
    prnt@"Yes!"@
🧪 Example
boo
Copy
Edit
imprt math

func square(n: int) -> int ~
    ret@n * n@

x=5
if x = 5 ~
    prnt@"Five it is!"@
🛠️ Planned:
Parser in C# or Python

Test suite

REPL or CLI runner

yaml
Copy
Edit

---

### ✅ Step 3: Push It to GitHub

If you're working locally:

```bash
git clone https://github.com/MistyPigeon/BooStar.git
cd BooStar

# Create README and spec file
mkdir docs
nano README.md
nano docs/spec.md

# Add, commit, and push
git add .
git commit -m "Added Boo* language spec and README"
git push
