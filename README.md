# 📶 BLE Distance Estimator

A minimal and modern mobile-friendly web application that calculates the estimated distance between a BLE device and a receiver using RSSI (Received Signal Strength Indicator).

---

## 📐 RSSI-to-Distance Formula

The distance `d` in meters can be estimated using the following formula:

```
d = 10^((P - S) / (10 * N))
```

Where:
- **d** = Estimated distance in meters  
- **P** = Transmitted power at 1 meter (Tx Power or Measured Power, in dBm)  
- **S** = Measured RSSI value (in dBm)  
- **N** = Environmental factor (typically between 2 and 4)

---

## 🧮 Features

- Simple and clean user interface
- Optimized for mobile devices
- Smooth hover effects
- Instant calculation based on user input

---

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript

---

## 🚀 Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/ble-distance-estimator.git
```

### 2. Navigate to the project folder:
```bash
cd ble-distance-estimator
```

### 3. Open `index.html` in your browser:
You can simply open the file directly or use a live server extension for real-time updates.

---

## 📸 UI Preview

![screenshot or gif preview here]

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Contributions

Feel free to fork the repository and submit a pull request to improve this tool or enhance its features!

---

## 👨‍💻 Author

Built with ❤️ by [Your Name](https://github.com/your-username)
```

Let me know if you'd like a custom banner or screenshot preview section added!
