# 🛡️ Operation: Firewall Beta - Escape Room

**Operation: Firewall Beta** is a browser-based, interactive cybersecurity escape room designed for team building and skills training. Players must work together as "SysAdmins" to bypass security protocols, decrypt data, and restore a central mainframe before a timer expires.

## 📁 Project Structure
- `escapeRoom.html`: The single-file source code containing all HTML, CSS, and JavaScript for the game.
- `README.md`: This documentation file.

## 🚀 How to Play
1.  **Launch**: Open `escapeRoom.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
2.  **Start Mission**: Click the "START MISSION" button on the landing page to begin the timer and reveal the game interface.
3.  **Objectives**: Complete 4 stages to save the system:
    -   **Stage 1 - Biometric Login**: Answer tech trivia questions and combine the first letter of each answer to form a password.
    -   **Stage 2 - The Firewall**: Solve a Wordle-style puzzle with 5-letter tech terms (e.g., LINUX, DEBUG, CACHE).
    -   **Stage 3 - Auth Matrix**: Solve computational challenges involving binary bitwise operations and algorithm logic (Max Subarray Sum).
    -   **Stage 4 - Voice Verification**: Solve riddles related to computer hardware and time.
4.  **Win Condition**: Complete all stages before the timer (default: 40 minutes) runs out.
5.  **Fail Condition**: If the timer expires, the mission fails. Users can view a "Mission Report" to see key learnings.

## 🛠️ Features
-   **Countdown Timer**: A visual timer adds urgency. Expiry triggers a failure screen.
-   **Interactive Inputs**: Custom single-character input boxes with auto-advance and keyboard support (Backspace, Paste).
-   **Immediate Feedback**: Inputs light up Green (correct) or Red (incorrect) for immediate validation in specific stages.
-   **Education Focused**: A "Mission Debrief" screen summarizes the concepts learned (Latency, Algorithms, Binary, etc.) either after winning or failing.
-   **Secret Developer Nav**: A hidden button (top-left corner, invisible) allows testers to cycle through game stages for quick verification.

## 💻 Technical Details
-   Built with Vanilla HTML, CSS, and JavaScript.
-   No external dependencies or libraries required.
-   Responsive grid layout for Wordle stage.
-   Dynamic DOM manipulation for stage navigation and state management.

---
*Created for the Escape Room Team Activity.*