# Resume Roast Skill

A reusable AI skill that reviews a resume against a job description and provides honest, specific, and actionable feedback.

## Project Objective

The goal of this project is to turn repeated resume-review instructions into a reusable skill that can be used in a fresh AI chat.

## Features

- Reviews resumes against specific job descriptions.
- Provides an estimated match score out of 100.
- Identifies strengths and missing qualifications.
- Highlights weak or vague resume statements.
- Suggests honest improvements and rewrites.
- Recommends relevant job-description keywords.
- Provides five prioritized improvement suggestions.
- Avoids inventing skills, qualifications, or experience.

## Project Structure

```text
Resume-Roast-Skill/
│
├── resume-roast/
│   └── SKILL.md
│
├── tests/
│   ├── test-1-data-analyst.md
│   ├── test-2-frontend-developer.md
│   ├── test-3-customer-support.md
│   ├── result-1-data-analyst.md
│   ├── result-2-frontend-developer.md
│   └── result-3-customer-support.md
│
├── comparison/
│   └── test-1-comparison.md
│
└── README.md
```

## How to Use

1. Open a new ChatGPT conversation.
2. Upload the `SKILL.md` file.
3. Upload the resume and corresponding job description.
4. Ask ChatGPT to follow the Resume Roast Skill instructions.
5. Review the feedback and suggested improvements.

Note: Saving `SKILL.md` locally does not automatically install a slash command in ChatGPT. The instructions can be supplied in a fresh conversation as described above.

## Testing

The skill was tested using three different job roles:

1. Data Analyst Intern
2. Frontend Developer Intern
3. Customer Support Associate

Each test used a different sample resume and job description.

## Comparison

The Data Analyst Intern review was also performed without uploading the skill.

Both reviews produced an estimated match score of 55/100. The comparison showed that the skill provides a reusable structure and consistent review instructions.

See `comparison/test-1-comparison.md` for the detailed comparison.

## Technologies Used

- Markdown
- Generative AI
- Prompt Engineering
- Agent Skill Instructions

## Project Status

Completed – Three test cases and one with-skill versus without-skill comparison.