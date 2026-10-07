# tashfiqonbir About Me 
<h1 align="center">Hi 👋, I'm TASHFIQ ONBIR</h1>
<h3 align="center">Exploring something different from others</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00F7FF&center=true&vCenter=true&width=435&lines=Python+Learner;Beginner+Developer;Exploring+Something+New" alt="Typing SVG" />
</p>

---

### 👨‍💻 About Me
- 🌱 I’m currently **learning Python from the beginning**
- 💡 Exploring something different from others  
- ⚡ Fun fact: I love to build small games and automate things
- 📌 Btw i love to do coding with (AI). [That's The true]

---

### 🛠️ TECH STACK
#### PROGRAMMING LANGUAGES
<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

#### LEARNING
<p>
  <img src="https://skillicons.dev/icons?i=vscode,github,git" />
</p>

---

### 🎮 PLAY A MINI GAME
আমার favorite কাজ: ছোট ছোট game বানানো 😎

#### 1. Snake on my Contributions
<p align="center">
  <img src="https://raw.githubusercontent.com/tashfiqonbir/tashfiqonbir/output/github-contribution-grid-snake-dark.svg" alt="snake game" />
</p>

#### 2. Play in Terminal
```python
import random
print("🎮 Welcome to Number Guessing Game!")
print("I'm thinking of a number between 1-10")
secret = random.randint(1, 10)
tries = 3
for i in range(tries):
    guess = int(input(f"Try {i+1}: "))
    if guess == secret:
        print("🎉 Correct! You won!")
        break
    elif guess < secret:
        print("📈 Too Low!")
    else:
        print("📉 Too High!")
else:
    print(f"💀 Game Over! The number was: {secret}")
