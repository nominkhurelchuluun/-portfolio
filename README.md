---
title: "Nomin Khurelchuluun | Data Science Portfolio"
layout: default
---

# Nomin Khurelchuluun

**Undergraduate Student | Aspiring Data Scientist**

Welcome to my portfolio website! Here, I showcase my data science projects, skills, and interests.

---

## 🧑‍💻 About Me

I am a data science undergraduate, graduating in May 2026, passionate about machine learning, data analysis, and
visualization. My interests include predictive modeling, statistical analysis, and building insightful dashboards.

---

<style>
    .tab {
        overflow: hidden;
        border-bottom: 1px solid #ccc;
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
    }

    .tab button.active {
        background-color: #ddd;
    }

    .tabcontent {
        display: none;
        padding: 12px 0;
    }
</style>

<div class="tab">
    <button class="tablinks" onclick="openTab(event, 'Projects')" id="defaultOpen">Projects</button>
    <button class="tablinks" onclick="openTab(event, 'Education')">Education</button>
    <button class="tablinks" onclick="openTab(event, 'Experience')">Experience/Research</button>
</div>

<div id="Projects" class="tabcontent">
    <h2>Projects</h2>
    <ul>
        <li><b>Deep Learning Based Recommendation Engine, /b> – September 2025 - Present
                <br>* Building a personalized deep learning recommender system using neural collaborative filtering on
                the MovieLens dataset, integrating user and item embedding. Currently focusing on model training and
                reporting improvements compared to baseline collaborative filtering approaches.
        </li>
        <li><b>Database for Spotify, /b> – February 2024 - April 2024
                <br>* Built a SQL database system for podcast aggregation, ensuring smooth integration with Spotify and
                enhancing user experience through detailed modeling and design, Developed an intuitive interface for
                exploring podcasts by genre, popularity, and topics, supported by a recommendation engine that adapts
                suggestions based on user preferences, technologies used, and your contributions.
    </ul>
</div>

<div id="Education" class="tabcontent">
    <h2>Education</h2>
    <ul>
        <li>B.A. in Data Science, Columbia University, May 2026</li>
        <li>Relevant Courses: Neural Networks & Deep Learning, AI, Statistical Inference, Probability Theory, Databases.
        </li>
    </ul>
</div>

<div id="Experience/Research" class="tabcontent">
    <h2>Experience</h2>
    <ul>
        <li><b>Quantitative Analysis of Reforestation and Grazing Policies in Mongolia, Researcher/b> – August 2025 -
                Present
                <br>* Collaborating with a Columbia University faculty member to predict vegetation recovery under
                reforestation and livestock reduction policies using quantitative NDVI, livestock census, climate, and
                land-use data.
                * Building Bayesian decision models and machine learning simulations to forecast policy outcomes and
                guide sustainable land management.
        </li>
        <li><b>Student Operations Assistant, Columbia University</b> – November 2024 - Present
            <br>* Analyzing large housing work-order datasets which includes ~30500 WOs using PowerBI and Python;
            completed independent data science project to identify patterns and overlaps, and proposed solutions to
            improve student housing by anticipating future needs, regarding vendors negotiations.
            * Data managing on projects for field operations across 38 Columbia Housing buildings, improving processes
            and reporting to enhance student experiences; managed conference project data full-time in summer and
            part-time for academic semesters.
        </li>
        <li><b>Supply Chain Assistant/Operations Support (Full-time), DSV Air & Sea US</b> – July 2022 - July 2023
            <br>* Served as a key liaison between internal teams and external stakeholders, ensuring objective alignment
            and monitoring KPIs for a luxury electric car client and the branch manager, achieving a 12% quarterly
            increase in invoice processing efficiency.
            * Managed the invoice portal with precision, tracking outstanding over 100 invoices per day on CargoWise
            One, facilitating seamless communication with LLP, and reducing overdue payments through effective follow-up
            strategies.
            * Created visually engaging daily performance reports with Business Excel 1.0 and PowerBI, leveraging
            PivotTables and formulas to provide actionable insights to the internal Accounting Team and trained new
            employees within the team.
        </li>
    </ul>
</div>

<script>
    function openTab(evt, tabName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(tabName).style.display = "block";
        evt.currentTarget.className += " active";
    }
    document.addEventListener("DOMContentLoaded", function () {
        document.getElementById("defaultOpen").click();
    });
</script>

---

## 🛠️ Skills

- **Languages:** Machine Learning, Python, SQL, PowerBI, Business Excel, Key Point Indicator Management, Payroll, Supply
Chain
- **Libraries:** Pandas, NumPy, scikit-learn, matplotlib, seaborn, TensorFlow, PyTorch
- **Tools:** Jupyter Notebook

---

## 📄 Resume

[Download my Resume](resume.pdf)

---

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/nomink_)
- Email: nk3126@columbia.edu

---
