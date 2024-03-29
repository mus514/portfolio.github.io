---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
        
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data engineer
          company: Bombardier
          company_url: ''
          company_logo: org-gc
          location: Montreal
          date_start: '2023-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Build ETL pipeline using PySpark and migrate files in parquet format to Microsoft Azure
              * Developed ML algorithms predicting plant part prices, employing data analysis, feature engineering, and model optimization.
              * Develop Python scripts for extracting data from web service APIs and loading them into databases.
              * Implemented pipelines and SQL scripts for tracking and communicating automated migration progress via email.

              Achievements:
              * Optimize ETLs that initially took at least 48 hours to reduce it to just 8 minutes , improving business efficiency and productivity.
              * Developed a robust general-purpose library using Apache Spark to streamline and accelerate the creation of data processing pipelines.
              * Refactor the transformation process from using Pandas to PySpark for process optimization
              * Convert SQL to PySpark code for enhanced flexibility and leverage Spark's distributed computing capabilities, contributing to optimized data workflows.
        
        - title: Actuarial analyst
          company: TELUS Health
          company_url: ''
          company_logo: tls
          location: Quebec
          date_start: '2022-04-01'
          date_end: '2023-02-28'
          description: |2-
              Responsibilities include:
              * Contribute to the examination and verification of annual and periodic data. 
              * Compute pension benefits for 3000 participants, incorporating plan-specific formulas, years of service, average salaries, and interest rates.
              * Manage databases, specifically utilizing Ariel, and oversee participant files for accuracy and completeness.

        - title: Data scientist
          company: Laval University
          company_url: ''
          company_logo: org-x
          location: Quebec
          date_start: '2021-05-01'
          date_end: '2022-09-30'
          description: |2-
              Responsibilities include:
              * Employ Pandas and Scikit-learn for thorough data cleaning, addressing missing values, and handling outliers.
              * Conduct statistical inference, employing Regression Analysis and Hypothesis Testing, to gain insights into the influence of variables on the overall condition of golf courses.
              * Implement machine learning algorithms, including Random Forest, KNN, and Gradient Boosting, utilizing both Python and R environments. These models predict the impact of various chemical components on the condition of golf courses.
              * Conduct data analysis for various optimization algorithms using both R and Python.
              * Address missing data and perform data cleaning utilizing Pandas and Scikit-learn.
              * Run optimization algorithms on Compute Canada using C++.
              * Analyzed optimization algorithms, producing statistical improvements.
              * Developed automated data processing workflows using R and Python, significantly reducing processing time from hours to minutes.
          

        - title: Teaching Assistant, Statistical Analysis of Actuarial Risks
          company: Laval University
          company_url: ''
          company_logo: org-x
          location: Quebec
          date_start: '2021-01-01'
          date_end: '2021-05-30'
          description: |2-
              Responsibilities include:
              * Animate the exercise sessions.
              * Review with the students the insufficiently assimilated material.
              * Supervise students and offer pedagogical assistance.
              * Correction of exams.

    design:
      columns: '2'



  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificate'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: http://www.actuarial-lookup.com/results/mqctfj
          date_end: ''
          date_start: '2019-07-30'
          description: ''
          icon: soa
          organization: SOA
          organization_url: https://www.soa.org/
          title: 'Exam P'
          url: ''

        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/5326f5b4788529fb97f4fd87c1c103820752562b
          date_end: ''
          date_start: '2023-05-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'GARCH Models in R,'

        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/cb5bbb5fc7dd36f8bc8c99c9db36b0a97a57b3b9
          date_end: ''
          date_start: '2023-06-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Intermediate SQL'
          url: ''
    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Data Engineering
          tag: Data Engineering
        - name: Machine Learning
          tag: Machine Learning
          
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      
---
