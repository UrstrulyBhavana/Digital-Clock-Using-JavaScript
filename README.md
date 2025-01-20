# ⏰ Digital Clock Using JavaScript

A clean and responsive **digital clock** built using JavaScript, HTML, and CSS. This clock updates in real time to display the current hours, minutes, and seconds with a modern aesthetic.

---

## 🚀 Features
- ⏱️ **Real-Time Clock:** Displays hours, minutes, and seconds with continuous updates.
- 🎨 **Modern Design:** Features a gradient background and a frosted glass effect for a sleek appearance.
- 🖥️ **Responsive Layout:** Works perfectly on all devices, from desktops to mobile phones.
- 💡 **Easy Customization:** Change colors, font sizes, and styles effortlessly in the CSS.

---

## 🛠️ Technologies Used
- 🎨 **HTML:** Provides the structure of the digital clock.
- 🎨 **CSS:** Styles the clock with gradients, animations, and responsive design.
- ✨ **JavaScript:** Updates the clock in real time using the `Date` object and intervals.

---

## 🔧 How to Use
1. Open the `index.html` file in your browser.
2. View the live digital clock displaying the current time.
3. Customize the clock by editing the `style.css` file:
   - Change colors in the gradient background.
   - Adjust font sizes or alignment.

---

## 🔑 Key Features (Code)
### **Real-Time Clock Update**
This snippet updates the hours, minutes, and seconds every second:
```javascript
let hrs = document.getElementById("hrs");
let min = document.getElementById("min");
let sec = document.getElementById("sec");

setInterval(() => {
    let currentTime = new Date();

    hrs.innerHTML = (currentTime.getHours() < 10 ? "0" : "") + currentTime.getHours();
    min.innerHTML = (currentTime.getMinutes() < 10 ? "0" : "") + currentTime.getMinutes();
    sec.innerHTML = (currentTime.getSeconds() < 10 ? "0" : "") + currentTime.getSeconds();
}, 1000);
```

## Demo
