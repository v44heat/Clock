# ⌚ XClock

A simple analog clock built using **HTML, CSS, and JavaScript**.
The clock dynamically updates every second using JavaScript's `Date` object and CSS transformations to rotate the clock hands.

---

## 📸 Preview
<img width="1920" height="1078" alt="XClock - Google Chrome 05_03_2026 02_24_32 PM" src="https://github.com/user-attachments/assets/c870694a-3954-4473-9bb6-5c1d44a9ffce" />



## 🚀 Features

* Real-time analog clock
* Hour, minute, and second hands with different lengths
* Smooth hand transitions
* Numbers (1–12) positioned around the clock face
* Responsive centered layout
* Pure **HTML + CSS + JavaScript** (no frameworks)

---

## 🛠️ Technologies Used

* **HTML5** – structure of the clock
* **CSS3** – styling, positioning, and animations
* **JavaScript (Vanilla JS)** – time logic and DOM manipulation

---

## ⚙️ How It Works

1. JavaScript retrieves the current time using:

```javascript
const now = new Date();
```

2. The current **seconds, minutes, and hours** are calculated.

3. Each value is converted into **degrees of rotation**.

Example:

```javascript
const secondsDegrees = ((seconds / 60) * 360) + 90;
```

4. CSS `transform: rotate()` rotates each clock hand accordingly.

---

## 📂 Project Structure

```
xclock/
│
├── index.html
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```
git clone https://github.com/yourusername/xclock.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

That's it — the clock will start running automatically.

---

## 🔮 Possible Improvements

* Add tick marks for each minute
* Add a center pivot design
* Add a digital clock display
* Add dark/light mode
* Add smooth sweeping seconds

---

## 👨‍💻 vincy

Built as a small JavaScript project to practice **DOM manipulation and CSS transforms**.
