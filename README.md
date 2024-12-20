# Mom's Kitchen Ordering System

A visually appealing, user-friendly application built with Python and Tkinter to simplify placing food orders at "Mom's Kitchen." This tool offers a delightful experience for users by integrating essential functionalities with interactive features, ensuring a smooth and enjoyable process for managing meal orders.

---

## 🚀 Features

- **Elegant User Interface**: Navigate effortlessly with a clean and intuitive design.
- **Smart Order Calculation**: Automatically computes the total cost based on selected items and their quantities.
- **Order Confirmation Workflow**: Asks for additional orders and provides a final confirmation before generating the bill.
- **Reset and Start Over**: Easily reset all fields for a new order session.
- **Interactive Dialog Boxes**: Uses responsive message boxes for user interaction and confirmation.
- **Pre-Defined Menu with Pricing**: Offers a fixed menu with transparent pricing for a hassle-free experience.

---

## 🛠️ Requirements

- Python 3.x
- Tkinter (Pre-installed with Python)

---

## 🧰 Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd MomsKitchen
   ```
3. **Run the Application:**
   ```bash
   python app.py
   ```

---

## 📋 How to Use

1. Open the application.
2. Enter quantities for the desired items in the input fields.
3. Click on the **Place Order** button to calculate and view the total.
4. Follow on-screen prompts to confirm or add more items to your order.
5. Use the **Reset** button to clear inputs and start afresh if needed.

---

## 🍴 Menu Items and Prices

| Item        | Price (₹) |
|-------------|-----------|
| Magiee      | 90        |
| Pasta       | 120       |
| Burger      | 100       |
| Sandwich    | 100       |
| Idli        | 100       |
| Dosa        | 100       |

---

## 📸 Screenshots

![Welcome Screen](https://github.com/user-attachments/assets/33243528-a17f-4431-b1cd-af92d8aebf18)

![Order Input](https://github.com/user-attachments/assets/3603eac4-e181-4484-a8f6-7e7b30d3d52d)

![Order Summary](https://github.com/user-attachments/assets/653efb76-3beb-4911-a8f5-b1913f7df667)

![Enjoy Your Meal](https://github.com/user-attachments/assets/4cfa4547-3f16-46eb-a722-34176a90b634)

---

## ✨ Code Highlights

- **Dynamic and Scalable Order Processing**:
  ```python
  for item, price in prices.items():
      qty = int(entries[item].get()) if entries[item].get() else 0
      if qty > 0:
          total += qty * price
          order_summary += f"{item}: {qty} x ${price} = ${qty * price}\n"
  ```
- **Interactive Workflow Using Dialogs**:
  ```python
  additional_order = messagebox.askyesno("Order More?", "Do you want to order something else before viewing the bill?")
  ```
- **Effortless Reset Mechanism**:
  ```python
  def reset_fields():
      for entry in entries.values():
          entry.delete(0, tk.END)
  ```

---

## 🤝 Contributions

We welcome contributions to enhance the functionality or aesthetics of the app. Feel free to:
- Fork this repository.
- Submit pull requests with improvements or new features.

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## 🌟 Acknowledgments

- A big thanks to the Python and Tkinter communities for their excellent libraries and resources.
- Inspired by a passion for creating simple yet efficient tools for daily tasks.

---

## 📬 Contact

For any inquiries, feedback, or suggestions, feel free to reach out:

[hardikbajiya934@gmail.com](mailto:hardikbajiya934@gmail.com)



