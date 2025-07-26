# Hackwart-Founders

# ✨ Hogwarts Flow Master 🧙‍♂️🚦

> "Mischief Managed... and so is the Traffic!"  
> A Harry Potter–themed AI-based Traffic Signal Optimizer built for **Triwizardathon 2025** 🪄  
> By the legendary team: **Hackwarts Founders**

---

## 🧠 What It Does

🧙 Magical Traffic Optimizer uses **AI (YOLOv8)** to analyze real-time traffic from 4 different lanes (North, East, South, West) and **automatically chooses the lane that deserves the green signal** — all through the lens of magic and machine learning!

---

## 🧪 Tech Stack Used

| Magic Tool      | Muggle Equivalent 🔍        |
|-----------------|-----------------------------|
| 🧙 YOLOv8        | Vehicle detection via Ultralytics |
| 🧠 Streamlit     | For a real-time magical UI  |
| 🖥️ OpenCV       | Frame extraction & analysis |
| 🧪 Python        | Our magic wand 🪄           |

---

## 🎥 How It Works

1. Upload short traffic videos for all 4 lanes 📸
2. Click the **"Cast Signal Optimizing Spell"** button 🪄
3. Our AI counts the vehicles using YOLOv8 🚗
4. Lane with the most traffic is blessed with the **green signal** 🟢
5. Rest lanes receive the **"Expelliarmus" STOP Signal** 🔴

---

## 🌟 UI Highlights

- 🪄 **Harry Potter Theme** with magical fonts, sparkles & glowing effects
- 🚦 Real-time lane analysis
- ✨ Hover effects and golden signal boxes
- 🧙‍♂️ Interactive and responsive layout built using Streamlit

---

## 📂 File Structure

```bash
├── app.py                  # Streamlit UI (Main file)
├── yolov8m.pt              # YOLOv8 model (required)
├── BG1.jpg                 # Optional local background image (or use online)
├── requirements.txt        # All Python dependencies
├── README.md               # You're reading it now 😉



⚙️ How to Run Locally
bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/your-username/magical-traffic-optimizer.git

# 2. Move into the directory
cd magical-traffic-optimizer

# 3. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the app
streamlit run app.py
👨‍🎓 Team Hackwarts Founders
🧙‍♀️ Himani Uppal (Frontend Magic + Streamlit UI)
