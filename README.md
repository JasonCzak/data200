# DATA 200: Introduction to Data Science

## About the course

An introductory data science course for students with any level of programming experience. I redesigned the projects and modules so that beginners are not overwhelmed and experienced students are still challenged. Students finish the course able to manage real datasets in Python and write up results in LaTeX. In upcoming offerings, they will also track and share their work with Git and GitHub.

The course builds toward two main projects. The first is the Stock Market Project, which every student does with the same finance data. The second is a group project in which student teams find their own datasets and work with them independently. The units described below are the modules that prepare students for those two projects. The major projects are adaptive: each semester they are adjusted to current learning needs and major world events, so some units are reserved for that semester's Canvas page and are not published as open repositories.

The units are organized into topical sections. The foundations build on one another and are taken in order. After the foundations, the units can be taught in any order, and they may be swapped during a semester depending on class strengths and attendance. A unit's number suggests a direction, not a requirement.

## How the course is designed

Five ideas run through the units. Each is stated here in plain language.

- **Specification before creativity.** First you match an exact specification, then you reproduce a published figure, then you design your own.
- **Correct is not the same as trustworthy.** Your result can run and still be wrong, so test it against its assumptions, its sources, and its documentation before you trust it.
- **A professional workflow from the first week.** Reports are written in LaTeX, software versions are fixed, results are tested, and, in upcoming offerings, work is tracked with Git.
- **Skills arrive in the order the projects need them.** Each unit adds something the later projects depend on.
- **Everyone starts from the same place.** Setup is done together, classmates help one another, and there are ways to catch up if you join late or miss work.

## Course objectives

The objectives below come from the DATA 200 faculty workgroup. The units are organized around them.

1. Be able to describe what data are and how they are collected, stored, and managed.
2. Be proficient with methods for data collection and processing.
3. Be able to distinguish different types of data and determine appropriate statistical analysis of these different types.
4. Be proficient with dissemination of data and results, including best practices in data communication and the use of coding to visualize data.
5. Be able to express the core concepts underlying programming for data analysis and demonstrate basic proficiency of these concepts.
6. Understand the ethical considerations of all aspects of the data life cycle.

## Hands-on practice

Alongside those objectives, these are the hands-on skills students practice.

1. **Setting up a reproducible workflow:** Anaconda environments, PyCharm, and, in upcoming offerings, Git and GitHub
2. **Python for data:** core syntax, functions, and working with files
3. **Data management:** cleaning, merging, and reshaping data; working with large datasets and databases
4. **Visualization and statistical analysis:** exploring data and communicating results
5. **Data science and personal finance:** projects applying data methods to financial literacy questions
6. **Final project:** an independent analysis of a real dataset, written up in LaTeX and, in upcoming offerings, published on GitHub

## Tools students learn

- **Python** in reproducible **Anaconda** environments, using **PyCharm Professional** (free through JMU student access)
- **Git and GitHub** for version control (being added in upcoming offerings; a few assignments use GitHub, and students choose what else to publish)
- **LaTeX** (with Overleaf) for reports
- pandas, NumPy, and Matplotlib for data handling and visualization

## The units

The numbers in parentheses refer to the course objectives above.

### Foundations (in order)

The shared starting point: tools, Python, and the habits the later units rely on. Together these build objectives 1, 2, 4, and 5.

- **[Unit 0: Getting Set Up: LaTeX and Professional Computing](https://github.com/JasonCzak/data200-u00-getting-set-up)** (objectives 4, 5). A first-week setup done together in class. Students install LaTeX, compile a document and submit it with its source, and set up the accounts and tools the later work uses. Students who finish early help classmates, and students who add the course late have a catch-up path.
- **[Unit 1: Preparing Output in a Specified Way](https://github.com/JasonCzak/data200-u01-preparing-output)** (objectives 4, 5). A worked program in class, then students write their own version and a short LaTeX report. The goal is to produce output to an exact specification, which prepares students to reproduce a published dot plot on their own.
- **[Unit 2: Getting Started with Git](https://github.com/JasonCzak/data200-u02-getting-started-with-git)** (objectives 1, 5). In upcoming offerings, students install and configure Git, build a short commit history in a practice repository, push it to an empty GitHub repository, and submit a LaTeX report with the repository address.
- **[Unit 3: Python Camp: Pandas and Matplotlib](https://github.com/JasonCzak/data200-u03-python-camp)** (objectives 2, 4, 5). Three worked lessons in class (Matplotlib, pandas, and a combined workflow). Students then build and teach their own three-lesson package, with a slide deck and an overview.
- **[Unit 4: Python Learning Log](https://github.com/JasonCzak/data200-u04-python-learning-log)** (objective 5). A semester-long independent portfolio of at least four entries per week. It builds steady practice and leaves students with evidence they can show employers.

### Models and data practice

Testing every result against its assumptions, provenance, and sources, across modeling, simulation, archiving, and reporting. This section is where objectives 1, 3, 4, and 6 are developed most fully.

- **[Unit 5: Energy, Models, and Data Abstraction](https://github.com/JasonCzak/data200-u05-energy-models-abstraction)** (objectives 3, 5). Students start from a question that sounds simple: how does a car hitting a wall compare with the same car dropped from a height? They fix and extend a starter Python program, work with a Monte Carlo search, and learn that a quantity can be computable without being meaningful.
- **[Unit 6: Data Archaeology](https://github.com/JasonCzak/data200-u06-data-archaeology)** (objectives 1, 3, 6). Students receive three exam-score files with no account of how they were produced. They compute summaries, compare the distributions, and reconstruct the transformations that connect the files. Later they receive information about how the files were produced, and they record the whole chain in a provenance record.
- **Unit 7: Diffusion Simulation.** A one-dimensional diffusion simulation, written up as an Overleaf assignment. <!-- **[Unit 7: Diffusion Simulation](https://github.com/JasonCzak/data200-u07-diffusion-simulation)** -->
- **Unit 8: Archiving the Web with Python.** Students archive a webpage tied to their major as a PDF and document the workflow in LaTeX, including respect for a site's terms and rules for automated access. <!-- **[Unit 8: Archiving the Web with Python](https://github.com/JasonCzak/data200-u08-web-pdf-archiving)** -->
- **Unit 9: Designing a Formal Report Template.** Students research professional reporting practice and design a reusable LaTeX progress-report template. Starter templates are provided at beginner, intermediate, and advanced levels. <!-- **[Unit 9: Designing a Formal Report Template](https://github.com/JasonCzak/data200-u09-formal-reports)** -->

### Professional practice

Responsible use of AI, career readiness, and preparing for the group project. This section develops objectives 4 and 6.

- **Unit 16: Responsible AI and Professional Documentation.** Students are introduced to generative AI after the foundations. Every AI result must be understood, tested, documented, and cross-checked, and the unit sets the AI policy for the rest of the course and for later projects. <!-- **[Unit 16: Responsible AI and Professional Documentation](https://github.com/JasonCzak/data200-u16-responsible-ai)** -->
- **Unit 17: LinkedIn and Resume Development.** A career-readiness assignment: a LinkedIn profile, access to LinkedIn Learning, and a truthful data-analytics resume written in LaTeX. <!-- **[Unit 17: LinkedIn and Resume Development](https://github.com/JasonCzak/data200-u17-linkedin-resume)** -->
- **Unit 18: Group Formation and Project Preparation.** The transition to the group project: teams of four, a proposal, a review of presentations, and a recovery path for students who missed earlier career-readiness work. <!-- **[Unit 18: Group Formation and Project Preparation](https://github.com/JasonCzak/data200-u18-group-project-prep)** -->

## The two projects

Both projects adapt from semester to semester. Their current versions are on that semester's Canvas page.

### Stock Market Project

The common project every student does, applying data methods to financial literacy questions with real market data (objectives 2, 3, 4, 5). Students choose stocks, download their price history, and make the calculations that turn prices into profit, loss, and interest. They then build and justify an investment plan, and teams manage a simulated portfolio for a week, compare projections, and present their results in a recorded team presentation. The project is an educational simulation, not financial advice.

### Group project

Student teams find their own datasets and analyze them (all six objectives).



