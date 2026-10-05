# Orbyte · Smart Tumbler Prototype

An interactive companion web app prototype for the **Orbyte Smart Tumbler**, built with pure HTML, modern CSS, and vanilla JavaScript.

## 🚀 Features & Interactivity

- **💧 Home Screen**:
  - Live animated water drop showing progress towards daily goal.
  - Interactive tap on water droplet to log sips (+150 ml) with pulse animation.
  - Live weather impact banner and reminder alerts.
- **🎯 Goal Customizer**:
  - Interactive `+` / `−` daily target glasses and ml calculator.
  - Activity level selector (Light, Moderate, Active).
  - Health consideration tags (None, Kidney, Heart, Diabetes, Pregnant/nursing).
  - "Save my goal" confirmation feedback.
- **🥤 Tumbler (Live Bottle View)**:
  - Interactive SVG tumbler with liquid wave animation.
  - Tap tumbler to simulate drinking / refilling water.
  - Real-time water temperature selector (`Cold 12°C`, `Just Right 24°C`, `Hot 42°C`).
- **📊 History & Insights**:
  - Interactive weekly drinking bar chart (M–Su) with daily breakdown inspection.
  - Detailed drinking history logs with temperature indicators.
- **⚙️ Settings**:
  - Interactive toggle switches for hydration reminders, battery alerts, sound, and haptics.
  - Clickable menu items with feedback.
- **📱 Responsive Mobile Experience**:
  - Fits beautifully in desktop browser with phone frame mockup and native full-screen fit on mobile devices.

---

## 🛠️ Deploying to Vercel

1. Push this repository to **GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Orbyte Smart Tumbler prototype"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```

2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Click **Deploy** — your prototype will be live instantly!

---

## 💻 Running Locally

Simply open `index.html` in any web browser or use a local static server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node / npx
npx serve .
```
