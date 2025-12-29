# Secure Family Task Board

A fully interactive and secure family task management web application that syncs encrypted data via GitHub Gist. Designed for multi-user usage, mobile-friendly, and lightweight.

## Features

- **Secure Access**: Enter a single passphrase to access encrypted tasks stored in a private GitHub Gist.
- **Task Management**:
  - Add/Edit/Delete tasks.
  - Assign tasks to one or multiple users.
  - Set due date (optional) and priority (low/medium/high).
  - Mark tasks as completed or pending.
- **Priority Indicators**: Color-coded priority bars; green indicates completed tasks.
- **Multi-user Support**:
  - Manage users (add/delete/select).
  - User type selection: 👨 Man, 👩 Woman, 🧒 Child.
- **Live Clocks**: Displays current time in IST (India) and CET (Germany).
- **Report Card**:
  - Total tasks, completed, pending.
  - Tasks per user with icons.
  - Tasks per priority.
- **Action Log**:
  - Records all actions (task added/edited/deleted, task completion, user changes).
  - Timestamps in IST and CET.
- **Auto-refresh**: Updates the board every 10 seconds for all users.
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop.

## Usage

1. Open the HTML page in a browser.
2. Enter your **passphrase** in the format:  
   `encryptionKey gistID GitHubPAT`
3. Once logged in:
   - Use the **Manage Users** button to add or delete users.
   - Use the **Add Task** button to create new tasks.
   - Click **Done/Edit/Delete** on tasks as needed.
   - View the **Report Card** at the bottom for task summary.
   - View **Action Log** for a detailed activity history.
4. Click **Save** to synchronize updates securely to GitHub Gist.

## Security

- Tasks and users are encrypted in the browser using AES-GCM.
- Data is stored only in a **private GitHub Gist**.
- No sensitive information is exposed in the HTML page.

## License

Open-source and free to use. Modify as needed for your family or small team projects.
