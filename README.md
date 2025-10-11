---
title: "Nomin Khurelchuluun | Data Science Portfolio"
layout: default
---

# Nomin Khurelchuluun

**Undergraduate Student | Aspiring Data Scientist**

Welcome to my portfolio website! Here, I showcase my data science projects, research, and professional experience.

---

## 🧑‍💻 About Me

I am a Data Science undergraduate at Columbia University, graduating in May 2026.  
My work focuses on **machine learning, data visualization, and predictive analytics**.  
I’m passionate about uncovering insights through data and applying them to solve real-world challenges — especially in areas of sustainable development, operations, and strategy.

Outside academics, I’m interested in consulting, impact investing, and using data for global problem-solving.

---

<style>
    body {
        font-family: 'Helvetica Neue', Arial, sans-serif;
        background: #f8f9fa;
        color: #333;
        line-height: 1.6;
    }

    h1, h2 {
        color: #0a2540;
    }

    .tab {
        overflow: hidden;
        border-bottom: 2px solid #ccc;
        margin-top: 2em;
    }

    .tab button {
        background-color: inherit;
        float: left;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 10px 20px;
        transition: 0.3s;
        font-size: 17px;
        color: #0a2540;
        font-weight: bold;
    }

    .tab button:hover {
        background-color: #ddd;
    }

    .tab button.active {
        background-color: #0a2540;
        color: white;
    }

    .tabcontent {
        display: none;
        padding: 15px 0;
        border-top: none;
    }

    ul {
        margin-left: 1.5em;
    }

    a {
        color: #1d4ed8;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }

    iframe {
        border: 1px solid #ccc;
        border-radius: 8px;
    }
</style>

<div class="tab">
    <button class="tablinks" onclick="openTab(event, 'Projects')" id="defaultOpen">Projects</button>
    <button class="tablinks" onclick="openTab(event, 'Education')">Education</button>
    <button class="tablinks" onclick="openTab(event, 'Experience')">Experience / Research</button>
    <button class="tablinks" onclick="openTab(event, 'CV')">CV</button>
</div>

<div id="Projects" class="tabcontent">
    <h2>Projects</h2>
    <ul>
        <li>
            <b>Deep Learning-Based Recommendation Engine</b> – <i>Sept 2025 - Present</i><br>
            Building a personalized deep learning recommender system using neural collaborative filtering on
            the MovieLens dataset. Integrating user-item embeddings and comparing model performance against baseline
            collaborative filtering approaches.
        </li>
        <br>
        <li>
            <b>Podcast Aggregation Database</b> – <i>Feb 2024 - Apr 2024</i><br>
            Built a SQL database for podcast aggregation with an interface for discovering podcasts by genre,
            popularity, and topic. Designed an ER model and implemented a recommendation engine for personalized discovery.
        </li>
        <br>
        <li>
            <b>Market Feasibility Analysis (STATA)</b> – <i>Mar 2023 - Jun 2023</i><br>
            Collected 100+ surveys and analyzed suburban mall data using STATA. Used KPI dashboards to reduce project launch costs by 15%.
        </li>
        <br>
        <li>
            <b>Java Anagram Finder</b> – <i>Dec 2023</i><br>
            Developed a Java program that finds all anagrams of a given word using BSTMap, AVLTreeMap, and MyHashMap. Benchmarked runtime across data structures.
        </li>
    </ul>
</div>

<div id="Education" class="tabcontent">
    <h2>Education</h2>
    <ul>
        <li><b>B.A. in Data Science</b> – Columbia University, Expected May 2026</li>
        <li><b>A.A. in Liberal Arts – Business Transfer</b> – College of San Mateo</li>
        <li>Relevant Coursework: Machine Learning, Databases, Statistical Modeling, Algorithms, Probability Theory</li>
    </ul>
</div>

<div id="Experience" class="tabcontent">
    <h2>Experience & Research</h2>

    <ul>
        <li>
            <b>Researcher – Quantitative Analysis of Reforestation and Grazing Policies in Mongolia</b> – <i>Aug 2025 - Present</i><br>
            Collaborating with Columbia University faculty to predict vegetation recovery under reforestation and livestock reduction policies
            using NDVI, livestock census, and climate data. Applying Bayesian decision models to simulate sustainable outcomes.
        </li>
        <br>
        <li>
            <b>Student Operations Assistant</b> – Columbia University, <i>Nov 2024 - Present</i><br>
            Analyzing 30,500+ housing work-order datasets using Power BI and Python. Built an independent data project identifying overlap patterns
            to optimize vendor negotiations. Managed housing project data for 38 campus buildings.
        </li>
        <br>
        <li>
            <b>Operations Assistant – DSV Air & Sea US</b> – <i>Jul 2022 - Jul 2023</i><br>
            Created data-driven Excel dashboards improving billing accuracy and operational KPIs. Reduced invoice processing time by 40% and overdue
            invoices by 12%. Managed invoice portal with CargoWise One for luxury retail and EV clients.
        </li>
    </ul>
</div>

<div id="CV" class="tabcontent">
    <h2>Curriculum Vitae</h2>
    <p>You can view or download my full CV below:</p>
    <iframe src="assets/resume.pdf" width="100%" height="600px"></iframe>
</div>

<script>
function openTab(evt, tabName) {
    let tabcontent = document.getElementsByClassName("tabcontent");
    for (let i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    let tablinks = document.getElementsByClassName("tablinks");
    for (let i = 0; i < tablinks.length; i++) {
        tablinks[i].classList.remove("active");
    }
    document.getElementById(tabName).style.display = "block";
    evt.currentTarget.classList.add("active");
}
document.addEventListener("DOMContentLoaded", function() {
    document.getElementById("defaultOpen").click();
});
</script>

---

## 🛠️ Skills

- **Languages:** Python, SQL, R, Java  
- **Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow, PyTorch, Matplotlib, Seaborn  
- **Tools:** Power BI, Excel, Jupyter Notebook, CargoWise One  
- **Specialties:** Data Cleaning, Machine Learning, Data Visualization, Statistical Analysis

---

## 📄 Resume
[Download Resume (PDF)](assets/resume.pdf)

---

## 📫 Contact
- 📧 Email: [nk3126@columbia.edu](mailto:nk3126@columbia.edu)  
- 💼 [LinkedIn](https://linkedin.com/in/nomink)

---

© 2025 Nomin Khurelchuluun | Built with 💻 & Data
