# FinCubes 🧊🧊🧊 
🧊🧊🧊 Multidimensional financial visualization framework with a Three.js instancing technique

![fincubes](media/fincubes.PNG)

Quick Deploy: To deploy simply view with an http server served. 

# 💸 FinCubes: 3D Financial Visualization Playground 🚀

Welcome to **FinCubes**! This is a next-generation, interactive 3D visualization tool for exploring financial flows, budgets, and statements—using cubes, physics, and a dash of fun! 🟩🟦🟥

## 🎮 Modes (Currently only PersonalFinanceCubes are open source, the rest are in development)

- **PersonalFinanceCubes** (current, `PersonalFinanceCubes.html`)
  - Visualize your income, expenses, assets, and liabilities as dynamic, physics-enabled cubes!
  - First-person mode, interactive picking, and real-time updates.
- **GovBudgetCube** (coming soon)
  - Explore government budgets as a living, breathing 3D world of cubes.
- **FinStatementCubes** (coming soon)
  - Dive into company financial statements in a tactile, visual way.

---

## ✨ Features

- **3D Physics**: Powered by [Three.js](https://threejs.org/) and [Ammo.js](https://github.com/kripken/ammo.js/), cubes bounce, stack, and interact in real time.
- **Interactive Controls**: Switch between orbit and first-person (FPS) modes, pick up cubes, and see labels on hover.
- **Customizable**: Adjust your financial data and see the cubes update instantly.
- **Resizable GUI**: Move and resize the control panel to your liking.
- **Visual Debugging**: See picking regions and debug overlays for advanced users.

---

## 🚀 Quick Start & Deployment

### 1. **Clone or Download the Repo**

```sh
git clone https://github.com/Photon1c/FinCubes.git
cd FinCubes
```

### 2. **Run a Local Web Server**

You need to serve the files over HTTP (not just open the HTML file directly) because of module imports and WASM. Here are some easy options:

#### **Using Python 3**

```sh
cd public
python -m http.server 8080
```
Then open [http://localhost:8080/PersonalFinanceCubes.html](http://localhost:8080/PersonalFinanceCubes.html) in your browser.

#### **Using Node.js (http-server)**

```sh
npm install -g http-server
cd public
http-server -p 8080
```
Then open [http://localhost:8080/PersonalFinanceCubes.html](http://localhost:8080/PersonalFinanceCubes.html) in your browser.

#### **Other Static Servers**
Any static file server will work! Just make sure to serve from the `public` directory.

### 3. **Enjoy!**

- Use the GUI panel to enter your financial data.
- Click **Visualize** to see your cubes come to life.
- Press **P** to enter FPS mode, **H** to show hover labels, **R** to pick up/drop cubes, and **Esc** to exit FPS mode.
- Resize or collapse the GUI as you wish.

---

## 🛠️ Requirements

- Modern browser (Chrome, Firefox, Edge, Safari)
- No build step required! All dependencies are loaded via ES modules or CDN.
- [Three.js](https://threejs.org/) and [Ammo.js](https://github.com/kripken/ammo.js/) are included in the project.

---

## 🧩 Contributing

Pull requests, issues, and ideas are welcome! Want to add a new mode, improve the physics, or make the cubes even more fun? Jump in! 🏗️

---

## 📅 Roadmap

- [x] PersonalFinanceCubes (interactive, physics-based personal finance viz)
- [ ] GovBudgetCube (government budget explorer)
- [ ] FinStatementCubes (company financial statement explorer)
- [ ] Multiplayer mode? (collaborative finance!)
- [ ] VR/AR support? (dream big!)

---

## 📸 Screenshots

*Coming soon!*

---

## 📝 License

MIT License. Use, remix, and share!

---

Made with Cursor IDE, JavaScript, and a love of data. 
