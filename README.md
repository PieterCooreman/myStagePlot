# myStage - Stage Plot Builder

myStage is a lightweight, single-page web application designed for musicians, bands, and sound engineers to quickly create, manage, and export professional stage plots and input lists. 

Built entirely with pure HTML, CSS, and vanilla JavaScript, it runs completely in the browser without the need for a backend or database.

## 🚀 Features

* **Drag-and-Drop Interface:** Easily place instruments, amps, monitors, and stage setups onto a customizable stage canvas.
* **Comprehensive Icon Library:** Uses Iconify to pull in highly specific musical icons from Material Design, FontAwesome 6, and Phosphor Icons for an accurate representation of stage equipment.
* **Dynamic Input List:** Automatically generates a numbered input list based on the items dropped onto the stage, complete with customizable notes (e.g., "Needs 48v Phantom Power", "Bring own SM58").
* **Canvas Controls:** Select, rotate (360 degrees), duplicate, and delete stage items. Add custom text labels to any icon.
* **State Persistence:** Automatically saves your progress to your browser's `localStorage` so you never lose your work if the page reloads or is accidentally closed.
* **Import & Export (JSON):** Save your stage layout as a `.json` file to your computer and upload it later to resume editing.
* **Image Export:** Generate and download a high-resolution image (PNG) of your complete stage plot and input list to email directly to venues and audio engineers.

## 🛠️ Technologies Used

* **HTML5 / CSS3 / Vanilla JavaScript:** No heavy frameworks (React, Angular, Vue) required.
* **[Iconify](https://iconify.design/):** For dynamic, lightweight, and scalable SVG icon rendering.
* **[html2canvas](https://html2canvas.hertzen.com/):** To handle capturing the DOM and exporting the stage plot and input list as a clean image file.

## 💻 Installation & Usage

Because myStage is a vanilla frontend application, there is no complex build process or installation required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/mystage.git](https://github.com/yourusername/mystage.git)
