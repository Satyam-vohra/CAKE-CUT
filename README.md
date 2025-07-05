# 🎂 Happy Birthday CUTE PAGE🎉

A cute and interactive HTML + CSS + JavaScript animated birthday celebration page designed for a 4-year-old baby named **Nanu**. It features:

- 🎈 Beautiful gradient background
- 👦 Stickman animation that walks in, cuts the cake, and gives a hug
- 🎂 A cake with flickering candle flames
- 🎉 Confetti celebration on cake cut
- 💖 Fully responsive and fun for mobile and desktop

---

## 🌟 Features

- **Interactive Start Button** to launch the animation
- **Candle Flickering Animation**
- **Stickman Walks In** and performs cake cut & hug animation
- **Confetti Fall** after hugging the cake
- **Smooth CSS Animations** using keyframes
- **Responsive Design** for all screen sizes
- **Pure HTML, CSS, and JavaScript** – No frameworks needed

---


Open index.html in any browser:

bash
Copy
Edit
start index.html   # Windows
open index.html    # macOS
xdg-open index.html # Linux


<button onclick="downloadPage()">🎁 Download This Page</button>

<script>
  function downloadPage() {
    const htmlContent = document.documentElement.outerHTML;
    const blob = new Blob([htmlContent], { type: "text/html" });
    const link = document.createElement("a");
    link.href = URL.createObjectURL(blob);
    link.download = "HappyBirthday.html";
    link.click();
  }
</script>

