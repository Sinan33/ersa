# Ersa | The National Digital Agent

<div align="center">
  <img src="lo.png" alt="Ersa Logo" width="180" height="auto" />
  <br><br>
  <p>
    <b>Automating Government Services with Advanced AI</b>
  </p>
  <p>
    <a href="https://rayansu.com/ersa/home">View Live Demo</a>
    ·
    <a href="https://github.com/sinan33/ersa/issues">Report Bug</a>
    ·
    <a href="https://github.com/sinan33/ersa/issues">Request Feature</a>
  </p>
</div>

---

<div align="center">
  <h3>⚠️ IMPORTANT NOTICE | تنويه هام</h3>
</div>

```diff
- نظرا لضيق الوقت وكذلك وصول القبول النهائي لي ولفريقي على البريد الإلكتروني بشكل متأخر جدا، تم برمجة الواجهات الأمامية فقط بشكل قريب جدا من الشكل النهائي

+ ( علما أننا لم نأخذ ورش العمل أيضا ولكن حاولنا قدر المستطاع إنجاز كل شيء بشكل احترافي كامل وكأنها منصة تليق فعلا بسيادة أبشر ووزارة الداخلية )

- علما أننا فريق كامل محترف بإمكاننا إنجاز كامل المشروع حتى الشكل النهائي


## 📖 About The Project

**Ersa Platform** introduces an intelligent agent that executes all government transactions on your behalf with seamless security. From issuing IDs and tracking requests to intelligently navigating complex procedures, the agent understands regulations and operates entirely in your place. 

Ersa is designed to be the trusted official assistant for digital government management across all sectors—from Interior to Commerce and Education—transforming every procedure into an instant, streamlined, and highly accurate experience.

### Key Features

* **🤖 AI-Driven Agent:** Automates complex government transactions with high precision.
* **🔒 Enterprise-Grade Security:** Advanced encryption for personal data and biometric protection.
* **⚡ Instant Performance:** Optimized for speed with immediate request processing.
* **🎨 Modern UI/UX:** A glassmorphism-based interface with smooth animations and responsive design.
* **📹 Optimized Media:** Custom video player integration (Plyr.js) with smart preloading and thumbnails.
* **🔗 Clean URLs:** Advanced `.htaccess` configuration for professional routing (removing `.html` extensions).

---

## 🛠️ Built With

This project is built using modern web technologies to ensure performance and scalability:

* ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
* ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
* ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
* **Plyr.js** (Video Player)
* **Font Awesome 6** (Iconography)
* **Apache** (Server Configuration)

---

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* A web server (Apache recommended) with `mod_rewrite` enabled to handle the `.htaccess` rules.

### Installation

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/sinan33/ersa.git](https://github.com/sinan33/ersa.git)
    ```
2.  **Setup the Server**
    * Ensure your server points to the root directory.
    * The project includes a `.htaccess` file to handle URL rewriting (e.g., converting `/home.html` to `/home`).
3.  **Media Assets**
    * Ensure the video file `ersa.mp4` and thumbnail `video-thumb.jpg` are placed in the root directory (or update paths in `index.html` accordingly).

---

## 📂 Project Structure

```text
ersa/
├── lo.png              # Logo
├── ersa.mp4            # Promo Video
├── video-thumb.jpg     # Video Thumbnail
├── home.html           # Main Landing Page
├── login.html          # Authentication Page
├── .htaccess           # URL Rewriting Rules
└── README.md           # Documentation
