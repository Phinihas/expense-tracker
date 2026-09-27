# 💰 Smart Expense

> **Smart Expense** is a modern group expense management app designed to make splitting bills, tracking shared expenses, and settling up simple, transparent, and stress-free.

Whether you're sharing rent with roommates, splitting restaurant bills with friends, managing household expenses, or traveling with a group, Smart Expense helps you keep track of **who paid, who owes, and who needs to settle up**.

---

## 📱 About

Smart Expense brings shared expense management into one simple application.

Instead of maintaining spreadsheets, sending messages to remember payments, or manually calculating balances, users can create groups, add expenses, track balances, and settle outstanding amounts in one place.

### Designed for

* 🏠 Flatmates and roommates
* 💑 Couples
* 👥 Friends and groups
* ✈️ Travel groups
* 👨‍👩‍👧 Families
* 🎉 Events and group activities

---

## ✨ Features

### 👥 Group Expense Management

Create or join groups and manage shared expenses with multiple members.

Perfect for:

* Rent and household expenses
* Electricity and utility bills
* Groceries
* Restaurant bills
* Trips and vacations
* Events and activities

---

### 💸 Easy Expense Splitting

Add an expense and select the members involved.

Smart Expense calculates each member's share and keeps track of the resulting balances.

**Example:**

```text
Restaurant Bill: ₹2,000

Paid by: Alice

Members:
Alice
Bob
Charlie
David

Each person's share: ₹500
```

---

### 🧠 Smart Debt Simplification

Smart Expense simplifies outstanding balances to make settlements easier.

Instead of requiring multiple unnecessary transfers between group members, the settlement algorithm calculates a simpler set of transactions.

**Example:**

```text
Before:

Bob     → Alice    ₹500
Charlie → Alice    ₹500
David   → Bob      ₹500
Alice   → David    ₹200
```

The application calculates the outstanding balances and simplifies the settlement process.

---

### 🔄 Real-Time Synchronization

Keep group members up to date with synchronized expense information.

When members add or update expenses, everyone can access the latest group information.

---

### 🧾 Receipt Attachments

Attach receipts, bills, invoices, or settlement proofs directly to transactions.

This helps group members:

* Verify expenses
* Keep payment records
* Avoid confusion
* Refer back to previous transactions

---

### 🔔 Push Notifications

Receive notifications when important activity happens in a group.

Examples include:

* New expense added
* Expense updated
* Settlement recorded
* Settlement confirmed
* Group activity

---

### 🌙 Dark & Light Themes

Choose between modern dark and light themes for a comfortable experience in different environments.

---

### 🔐 Privacy Focused

Smart Expense is designed with privacy in mind.

* Secure authentication
* Protected database access
* Authorized group access
* Secure receipt handling
* No advertisements
* No unnecessary tracking

---

## 🧮 How It Works

```text
             Create / Join Group
                     │
                     ▼
              Add an Expense
                     │
                     ▼
             Select Members
                     │
                     ▼
            Calculate Shares
                     │
                     ▼
             Update Balances
                     │
                     ▼
          Simplify Outstanding
               Debts
                     │
                     ▼
                Settle Up
```

### Simple workflow

**1. Create or join a group**

Add the people you want to share expenses with.

**2. Add an expense**

Enter the expense amount, description, payer, and participating members.

**3. Track balances**

The application calculates how much each member owes or is owed.

**4. Simplify debts**

Outstanding balances are simplified to reduce unnecessary transactions.

**5. Settle up**

Members can record and track settlements until the group balances are cleared.

---

## 📊 Example

Suppose three friends share expenses during a trip.

```text
Alice paid     ₹3,000
Bob paid       ₹1,500
Charlie paid   ₹500

Total          ₹5,000
```

If the expense is shared equally:

```text
Each person's share = ₹1,666.67
```

Smart Expense keeps track of individual balances and calculates the required settlements.

This eliminates the need for manual calculations.

---

## 🎯 Use Cases

| Use Case            | Examples                               |
| ------------------- | -------------------------------------- |
| 🏠 Shared Household | Rent, electricity, internet, groceries |
| ✈️ Travel           | Hotels, transport, food, activities    |
| 🍕 Dining           | Restaurant and food bills              |
| 🎉 Events           | Parties and group events               |
| 💑 Couples          | Shared household expenses              |
| 🎓 Students         | Hostel and shared expenses             |
| 👥 Friends          | Weekend trips and activities           |

---

## 🔒 Privacy & Security

Smart Expense focuses on keeping shared financial information protected.

The application uses Firebase authentication and Firebase's security mechanisms to control access to application data.

The app is also designed without advertisements or unnecessary tracking.

---

## 🎨 User Experience

Smart Expense focuses on providing a simple and modern experience.

### Design principles

* Clean and modern interface
* Simple expense creation
* Clear balance information
* Easy-to-understand settlements
* Dark and light themes
* Straightforward navigation
* Group-focused expense management

---

## 🛠️ Tech Stack

### Frontend

* **Flutter**
* **Dart**

### Backend & Cloud Services

* **Firebase**
* **Firebase Authentication**
* **Cloud Firestore**
* **Firebase Cloud Storage**
* **Firebase Cloud Messaging (FCM)**

### Platform

* Android

---

## 🏗️ Architecture

The application follows a Flutter-based architecture with Firebase providing backend and cloud services.

```text
┌──────────────────────────────┐
│          Flutter App         │
│                              │
│       Dart + Flutter UI      │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│           Firebase           │
│                              │
│  ┌────────────────────────┐  │
│  │ Firebase Authentication│  │
│  └────────────────────────┘  │
│                              │
│  ┌────────────────────────┐  │
│  │     Cloud Firestore    │  │
│  └────────────────────────┘  │
│                              │
│  ┌────────────────────────┐  │
│  │    Cloud Storage       │  │
│  └────────────────────────┘  │
│                              │
│  ┌────────────────────────┐  │
│  │ Firebase Cloud Messaging│ │
│  └────────────────────────┘  │
└──────────────────────────────┘
```

---

## 📲 Download

Smart Expense is available on Google Play.

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.nver.smartexpense">
    <img src="https://img.shields.io/badge/Google%20Play-Download%20Smart%20Expense-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Download Smart Expense"/>
  </a>
</p>

---

## 📸 App Screenshots

<p align="center">
 <img width="591" height="1280" alt="1" src="https://github.com/user-attachments/assets/f3bac976-f3b9-4a3b-bcab-cf4201f24447" />
<img width="591" height="1280" alt="2" src="https://github.com/user-attachments/assets/ca85b114-0c4f-41b9-a6ff-870fe91a74bb" />
<img width="591" height="1280" alt="3" src="https://github.com/user-attachments/assets/e84854bc-dbda-415b-ae9d-ead550d3fd67" />
<img width="591" height="1280" alt="4" src="https://github.com/user-attachments/assets/f8e6226e-56ed-4a36-a8e1-45d2af3c8a97" />
<img width="591" height="1280" alt="5" src="https://github.com/user-attachments/assets/056ff297-08f2-4d74-b31e-c192e4f49820" />
<img width="591" height="1280" alt="6" src="https://github.com/user-attachments/assets/ee2b4221-0d17-4913-8ff2-25cd7ee5b4de" />
<img width="591" height="1280" alt="7" src="https://github.com/user-attachments/assets/1397673c-a3c1-4336-bc89-02d5b2681742" />

</p>


---

## 👨‍💻 Author

**Phinihas Gandi**

Software Engineer • AI/ML & Full-Stack Systems

---

<p align="center">
  <strong>💰 Smart Expense — Split. Track. Settle.</strong>
</p>

<p align="center">
  Built with Flutter & Firebase to make shared expenses simple, transparent, and stress-free.
</p>
