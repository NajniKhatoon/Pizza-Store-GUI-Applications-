# 🍕 Flying Pizza Store

A Python desktop application built with **Tkinter** that allows users to browse pizzas, view prices, add items to a cart, and place orders — all through a graphical interface.

---

## 👤 Author

- Student Name: Najni Khatoon  
- Student ID:** w2152992

---

## 📋 Features

- 🖼️ Browse pizzas displayed as image buttons
- 💷 View pizza name and price loaded from a CSV file
- 🛒 Add items to cart with quantity selection
- 📦 View order summary with grand total
- ✅ Confirm or cancel orders
- ➕ Placeholders for Add New and Delete pizza functionality
- ❌ Quit confirmation dialog

---

## 🗂️ Project Structure

```
flying-pizza-store/
│
├── pizza_template.py       # Main application file
├── pizza_prices.csv        # Pizza names and prices
├── allPizza/               # Folder containing pizza images (.png, .jpg, etc.)
└── README.md
```

---

## 🍕 Pizza Menu & Prices

| Pizza | Price |
|---|---|
| Beef Sizzler | £8.99 |
| Small Beef Sizzler | £8.99 |
| Chicken Sizzler | £10.99 |
| Small Chicken Sizzler | £10.99 |
| Hawaiian | £9.99 |
| Small Hawaiian | £9.99 |
| Meat Feast | £9.99 |
| Small Meat Feast | £9.99 |
| Veg Sizzler | £9.99 |
| Small Veg Sizzler | £4.99 |
| Veg Supreme | £9.99 |
| Small Veg Supreme | £4.99 |
| New Pizza | £11.99 |

---

## ⚙️ Requirements

- Python 3.x
- Pillow (PIL)
- Tkinter (usually included with Python)

Install dependencies:

```bash
pip install Pillow
```

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/flying-pizza-store.git
cd flying-pizza-store
```

2. Make sure `pizza_prices.csv` and the `allPizza/` image folder are in the same directory as `pizza_template.py`.

3. Run the app:
```bash
python pizza_template.py
```

---

## 🖥️ App Layout

| Section | Description |
|---|---|
| **Top Menu Bar** | Buttons: Show All Pizzas, Clear, Add New, Delete, Quit |
| **Left Panel (Red)** | Pizza image buttons grid |
| **Right Panel (Black)** | Selected pizza details, quantity picker, Add to Cart |
| **Bottom Panel (Green)** | Cart summary with grand total, Confirm and Cancel buttons |

---

## 📌 Notes

- Pizza images must be placed inside the `allPizza/` folder
- Image filenames must match pizza names in `pizza_prices.csv`
- Supported image formats: `.png`, `.jpg`, `.jpeg`, `.bmp`, `.gif`, `.tiff`
