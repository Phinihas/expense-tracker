# 💰 Smart Expense

> **Smart Expense** is a modern group expense management app that makes splitting bills, tracking shared expenses, and settling debts simple and transparent.

Whether you're sharing rent with roommates, splitting restaurant bills with friends, or managing expenses during a trip, Smart Expense helps you keep track of **who paid, who owes, and who needs to settle up** — without the usual calculation headaches.

<p align="center">
  <img src="screenshots/app-preview.png" alt="Smart Expense Preview" width="800"/>
</p>

---

## 📱 About the App

Smart Expense is designed for **flatmates, couples, friends, families, and travel groups** who need an easy way to manage shared expenses.

The app provides:

* 🧾 Shared expense tracking
* 👥 Group and room-based expense management
* 💸 Automatic debt calculation
* 🔄 Real-time expense synchronization
* 📸 Receipt and bill attachments
* 🔔 Push notifications
* 🌙 Dark and light themes
* 🔐 Secure authentication
* 📊 Clear expense and settlement tracking

The goal is simple:

> **Add the expense → Split it → Track balances → Settle up.**

---

## ✨ Features

### 👥 Group Expense Management

Create groups/rooms and invite members to manage shared expenses together.

Examples:

* 🏠 Flatmates sharing rent and utilities
* ✈️ Friends sharing travel expenses
* 🍕 Friends splitting restaurant bills
* 💑 Couples managing household expenses
* 👨‍👩‍👧 Families tracking shared costs

---

### 💰 Smart Expense Splitting

Add an expense and specify who participated in it.

Smart Expense automatically calculates how much each member owes.

For example:

```text
Restaurant Bill: ₹2,000

Alice paid: ₹2,000

Participants:
Alice
Bob
Charlie
David

Each person's share: ₹500
```

The application keeps track of the resulting balances automatically.

---

### 🧠 Smart Debt Simplification

Instead of requiring every member to pay every other member, Smart Expense simplifies the settlement process.

For example:

```text
Before Simplification

Bob → Alice     ₹500
Charlie → Alice ₹500
David → Bob     ₹500
Alice → David   ₹200
```

The settlement algorithm calculates a simpler set of transactions so the group can settle their balances with **fewer transfers**.

---

### 🔄 Real-Time Synchronization

Expenses and settlements are synchronized so group members can stay up-to-date.

When a member:

* Adds an expense
* Updates an expense
* Records a settlement
* Confirms a payment

Other members can see the latest information without manually maintaining spreadsheets or chat messages.

---

### 📸 Receipt Attachments

Attach receipts, bills, invoices, or settlement proofs directly to expenses.

This makes it easier to:

* Verify expenses
* Keep payment proof
* Avoid disputes
* Refer back to previous transactions

---

### 🔔 Push Notifications

Receive notifications for important group activity.

Examples:

* New expense added
* Expense updated
* Settlement recorded
* Settlement confirmation
* Group activity

---

### 🌙 Dark & Light Themes

Smart Expense provides both dark and light themes for a comfortable user experience.

<p align="center">
  <img src="screenshots/home-dark.png" width="220"/>
  <img src="screenshots/home-light.png" width="220"/>
  <img src="screenshots/expenses.png" width="220"/>
</p>

---

## 📸 Screenshots

> Add your application screenshots inside the `screenshots/` folder and update the filenames below.

### 🏠 Home / Dashboard

<p align="center">
  <img src="screenshots/home.png" width="250"/>
  <img src="screenshots/dashboard.png" width="250"/>
</p>

### 👥 Groups / Rooms

<p align="center">
  <img src="screenshots/groups.png" width="250"/>
  <img src="screenshots/group-details.png" width="250"/>
</p>

### 💸 Add Expense

<p align="center">
  <img src="screenshots/add-expense.png" width="250"/>
  <img src="screenshots/expense-details.png" width="250"/>
</p>

### 📊 Balances & Settlements

<p align="center">
  <img src="screenshots/balances.png" width="250"/>
  <img src="screenshots/settlements.png" width="250"/>
</p>

### 🧾 Receipt Attachments

<p align="center">
  <img src="screenshots/receipt.png" width="250"/>
</p>

### ⚙️ Profile / Settings

<p align="center">
  <img src="screenshots/profile.png" width="250"/>
  <img src="screenshots/settings.png" width="250"/>
</p>

---

## 🏗️ Application Flow

```text
                 ┌─────────────────┐
                 │   User Login    │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Create / Join   │
                 │     Group       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Add Expense    │
                 │  + Participants │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Calculate Each  │
                 │     Share       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Update Member   │
                 │    Balances     │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Debt Simplifier │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │    Settle Up    │
                 └─────────────────┘
```

---

## 🧮 Expense & Settlement Logic

Smart Expense maintains the balance of each member based on:

```text
Amount Paid
     +
Amount Owed
     -
Amount Already Settled
     =
Current Balance
```

The settlement process then simplifies the group's outstanding balances into fewer transactions.

### Example

```text
Alice:   +₹1,000
Bob:     -₹600
Charlie: -₹400
```

Instead of multiple payments, the simplified settlement can become:

```text
Bob     ───── ₹600 ─────► Alice

Charlie ──── ₹400 ─────► Alice
```

This makes the final settlement easier to understand and complete.

---

## 🔐 Privacy & Security

Smart Expense is designed with privacy in mind.

### Security principles

* 🔒 Secure user authentication
* 🛡️ Protected database access
* 🔐 Authenticated group access
* 📁 Controlled receipt access
* 🚫 No advertisements
* 🚫 No unnecessary tracking

User and expense data should only be accessible to authorized users according to the application's access rules.

---

## 🎨 User Experience

Smart Expense focuses on keeping the experience simple and intuitive.

### Design principles

* Clean and modern interface
* Minimal steps to add an expense
* Clear balance information
* Easy-to-understand settlements
* Dark and light themes
* Responsive layouts
* Consistent navigation

---

## 📲 Download

Smart Expense is available on Google Play.

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.nver.smartexpense">
    <img src="https://img.shields.io/badge/Google%20Play-Download%20App-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Download Smart Expense"/>
  </a>
</p>

**Google Play:**
https://play.google.com/store/apps/details?id=com.nver.smartexpense

---

## 🛠️ Tech Stack

> Update this section with the exact technologies used in your implementation.

| Category       | Technology                  |
| -------------- | --------------------------- |
| Platform       | Android                     |
| Language       | `Your Language`             |
| UI             | `Your UI Framework`         |
| Backend        | `Your Backend`              |
| Database       | `Your Database`             |
| Authentication | `Your Auth Solution`        |
| Storage        | `Your Storage Solution`     |
| Notifications  | `Your Notification Service` |
| Architecture   | `Your Architecture`         |

---

## 📁 Project Structure

```text
SmartExpense/
│
├── app/
│   ├── src/
│   │   └── ...
│   │
│   └── ...
│
├── screenshots/
│   ├── home.png
│   ├── dashboard.png
│   ├── groups.png
│   ├── group-details.png
│   ├── add-expense.png
│   ├── expense-details.png
│   ├── balances.png
│   ├── settlements.png
│   ├── receipt.png
│   ├── profile.png
│   └── settings.png
│
├── README.md
└── ...
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

### 2. Open the project

Open the project using your preferred development environment.

### 3. Configure the required services

Configure the required:

* Database
* Authentication
* Storage
* Push notification service
* Environment variables

according to your project configuration.

### 4. Build and run

Build the project and run it on an Android device or emulator.

---

## 🎯 Use Cases

Smart Expense can be used for:

| Use Case            | Example                                |
| ------------------- | -------------------------------------- |
| 🏠 Shared Household | Rent, electricity, internet, groceries |
| ✈️ Travel           | Hotels, transport, food, activities    |
| 🍕 Dining           | Restaurant and food bills              |
| 🎉 Events           | Parties and group events               |
| 💑 Couples          | Shared household expenses              |
| 👥 Friends          | Weekend trips and activities           |
| 🎓 Students         | Hostel and shared expenses             |

---

## 🌟 Why Smart Expense?

Managing shared expenses through WhatsApp messages, notes, spreadsheets, or manual calculations can quickly become confusing.

Smart Expense brings everything into one place:

```text
                 Shared Expenses
                        │
        ┌───────────────┼───────────────┐
        ▼               ▼               ▼
      Track           Split           Settle
        │               │               │
        └───────────────┼───────────────┘
                        ▼
                 Smart Expense
```

No more:

❌ "Who paid for this?"

❌ "How much do I owe?"

❌ "Did you already pay me?"

❌ "Who should I transfer money to?"

Instead:

✅ Add the expense

✅ Split the cost

✅ Track balances

✅ Simplify settlements

---

## 📈 Future Enhancements

Potential improvements for future versions include:

* 📊 Advanced spending analytics
* 📅 Monthly expense summaries
* 💱 Multi-currency support
* 📤 Export expenses to CSV/PDF
* 🔎 Advanced expense search and filtering
* 💳 Payment integration
* 📈 Spending charts and insights
* 🔁 Recurring expenses
* 🌍 Multi-language support

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you would like to contribute:

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add your feature"
```

4. Push the branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for more information.

---

## 👨‍💻 Author

**Phinihas Gandi**

Software Engineer • AI/ML & Full-Stack Systems

---

<p align="center">
  <strong>💰 Smart Expense — Split. Track. Settle.</strong>
</p>

<p align="center">
  Built to make shared expenses simple, transparent, and stress-free.
</p>
