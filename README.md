
    <h1>🎬 Netflix Data Analysis Project</h1>

    <section>
        <h2>📌 Project Objective</h2>
        <p>
            The objective of this project was to perform an end-to-end exploratory data analysis (EDA)
            on the Netflix dataset to understand content distribution, growth patterns, and structural
            characteristics of Netflix’s catalog.
        </p>
        <p>
            The project emphasizes proper data cleaning, feature engineering, and analytical reasoning,
            following real-world data analysis practices.
        </p>
    </section>

    <section>
        <h2>📂 Dataset Overview</h2>
        <p>The dataset includes information about Netflix Movies and TV Shows such as:</p>
        <ul>
            <li>Content type (Movie / TV Show)</li>
            <li>Title, director, cast</li>
            <li>Country of origin</li>
            <li>Date added to Netflix</li>
            <li>Release year</li>
            <li>Rating</li>
            <li>Duration</li>
            <li>Genres</li>
            <li>Description</li>
        </ul>
        <p>
            The dataset contains missing values, mixed data types, and text-heavy columns,
            making it suitable for realistic data cleaning and analysis.
        </p>
    </section>

    <section>
        <h2>🧹 Data Cleaning & Preparation</h2>
        <ul>
            <li>Verified dataset integrity using unique <strong>SHOW ID</strong> values</li>
            <li>Identified critical vs non-critical missing values</li>
            <li>Converted <strong>DATE ADDED</strong> to datetime format with safe error handling</li>
            <li>Handled invalid or missing dates using <strong>NaT</strong></li>
            <li>Avoided incorrect imputation for categorical columns</li>
            <li>Removed empty and unnecessary columns caused by CSV formatting issues</li>
            <li>Standardized column names for consistency</li>
        </ul>
        <p>
            The project avoided over-cleaning to prevent data loss and analytical bias.
        </p>
    </section>

    <section>
        <h2>🧠 Feature Engineering</h2>
        <ul>
            <li>Extracted <strong>Year Added</strong> and <strong>Month Added</strong> from the date column</li>
            <li>Prepared the dataset for time-based analysis</li>
            <li>Handled movie duration and TV show seasons as separate concepts</li>
            <li>Left missing duration values unfilled to avoid incorrect assumptions</li>
        </ul>
    </section>

    <section>
        <h2>📊 Analysis & Key Insights</h2>
        <ul>
            <li>Distribution of Movies vs TV Shows on Netflix</li>
            <li>Growth trends of Netflix content over time</li>
            <li>Monthly patterns in content additions</li>
            <li>Duration characteristics of Movies and TV Shows</li>
        </ul>
        <p>
            The analysis focused on interpreting results and understanding their real-world implications,
            rather than only computing numerical summaries.
        </p>
    </section>

    <section>
        <h2>📈 Visualization Approach</h2>
        <p>
            Visualizations were designed to support analytical findings and highlight trends clearly.
            Only purposeful and interpretable charts were considered, avoiding unnecessary or misleading plots.
        </p>
    </section>

    <section>
        <h2>🎯 Key Learnings</h2>
        <ul>
            <li>Importance of thoughtful data cleaning decisions</li>
            <li>Correct handling of missing and invalid data</li>
            <li>Datetime feature engineering for trend analysis</li>
            <li>Avoiding silent analytical bugs</li>
            <li>Thinking analytically rather than syntactically</li>
        </ul>
    </section>

    <section>
        <h2>🚀 Project Status</h2>
        <p><strong>Completed</strong></p>
        <p>
            This project demonstrates practical use of Python and Pandas for real-world data analysis,
            from raw data exploration to insight generation.
        </p>
    </section>

    <footer>
        <p>Netflix Data Analysis Project | Python & Pandas</p>
    </footer>


