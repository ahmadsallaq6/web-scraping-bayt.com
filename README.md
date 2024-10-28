# Job Postings and Resume Datasets

## Job Postings Dataset

### Overview

This dataset contains **2,500 job postings** with detailed information across various roles, providing valuable insights into current hiring trends and demands in the job market.

### Dataset Features

The dataset includes the following columns:

- **Job Title**: The title of the job position.
- **Company**: The name of the company offering the job.
- **Location**: The geographic location of the job, primarily focusing on the Gulf region.
- **Description**: A brief overview of the job responsibilities and expectations.
- **Skills**: Required skills and qualifications for the job.
- **Link**: A URL link to the job posting for more information.

### Key Insights

- **Role Distribution**: The dataset features a diverse range of job titles, with a notable emphasis on sales, development, and management roles. There is a particularly high demand for sales-related positions.
  
- **Geographic Focus**: Job postings are predominantly concentrated in the Gulf region, especially in major cities like **Dubai** and **Riyadh**.
  
- **Industry Highlights**: The dataset covers various industries, including sales, technology development, and administration, providing a snapshot of sectors with active hiring needs.

### Purpose

This dataset is useful for:

- Understanding job market demands.
- Identifying regional hiring hotspots.
- Analyzing skills in demand across different industries.

### Usage

You can use this dataset for data analysis, machine learning projects, or to gain insights into job market trends.

---

## Resume Dataset

### Context

This dataset is a collection of resume examples sourced from [LiveCareer](https://www.livecareer.com). It is intended for categorizing resumes into predefined job categories based on the text content.

### Content

- **Total Resumes**: 2,484 resumes in both string (CSV) and PDF formats.
- **PDF Storage**: PDF files are organized in the `data` folder, with subfolders for each job category. Each resume PDF is named according to the unique ID provided in the CSV file.

### CSV Structure

The CSV file contains the following columns:

- **ID**: Unique identifier for each resume and the filename for the respective PDF.
- **Resume_str**: The text content of the resume in string format.
- **Resume_html**: The resume content in HTML format as extracted during web scraping.
- **Category**: The job category associated with each resume.

### Job Categories

The dataset includes the following job categories:
- `HR`
- `Designer`
- `Information-Technology`
- `Teacher`
- `Advocate`
- `Business-Development`
- `Healthcare`
- `Fitness`
- `Agriculture`
- `BPO`
- `Sales`
- `Consultant`
- `Digital-Media`
- `Automobile`
- `Chef`
- `Finance`
- `Apparel`
- `Engineering`
- `Accountant`
- `Construction`
- `Public-Relations`
- `Banking`
- `Arts`
- `Aviation`

---

This dataset can be used for text classification tasks, especially in training models to categorize resumes based on job descriptions.
