# 🛠️ Take Ownership Context Menu Tweak for Windows 10/11

Easily add or remove a **"Take Ownership"** option to the right-click context menu for files and folders in Windows. Useful for regaining control of locked files and deleting protected content.

---

## 📁 Files Included

- `TakeOwnership.reg` – Adds the "Take Ownership" option
- `RemoveTakeOwnership.reg` – Removes the option
- `README.txt` – Usage instructions (optional if you're reading this)

---

## ⚙️ How to Use

### ➕ Add "Take Ownership"
1. Right-click `TakeOwnership.reg`
2. Click **Merge**
3. Confirm the prompts

This adds a right-click option for files and folders that runs `takeown` and `icacls` under the hood.

### ➖ Remove It
1. Right-click `RemoveTakeOwnership.reg`
2. Click **Merge** to remove the context menu item

---

## 🛡️ Safe and Admin-Friendly

- Uses built-in Windows commands (`takeown` & `icacls`)
- Requires administrator privileges
- No third-party software needed

---

## ✅ Tested On

- Windows 10 Pro (21H2)
- Windows 11 (22H2)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
