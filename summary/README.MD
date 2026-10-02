# Resume Summary Generator

## Overview

The **Resume Summary Generator** creates concise, professional resume summaries from structured candidate information such as experience, skills, education, and career goals.

It is designed to help produce consistent, job-focused summaries suitable for resumes and job applications.

## Key Features

* Generate professional resume summaries
* Highlight relevant experience and skills
* Create concise, recruiter-friendly content
* Adapt summaries to different roles
* Produce consistent output formats

## Input

The generator can process information such as:

```text
- Professional experience
- Technical skills
- Education
- Previous roles
- Career goals
- Target position
```

## Output

The system produces a structured professional summary:

```text
Professional Role + Years of Experience
        ↓
Key Technical Skills
        ↓
Relevant Experience
        ↓
Career Strengths / Focus
```

### Example

**Input:**

```text
Role: Full Stack Developer
Experience: 4 years
Skills: Python, Java, React, SQL
Focus: Web application development
```

**Output:**

```text
Full Stack Developer with 4 years of experience
building web applications using Python, Java, React,
and SQL, with a strong focus on scalable and reliable
software development.
```

Add a detailed input schema:
Name
Experience
Skills
Education
Target role
Add a realistic generated-summary example.

## Installation

```bash
git clone <repository-url>
cd resume-summary-generator
pip install -r requirements.txt
```

## Testing

Run the test suite with:

```bash
pytest
```
