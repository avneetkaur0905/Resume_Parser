## Resume Matching and Gap Analysis Tool

# Overview
In this project I have created a resume matching and skill gap analysis tool that works with SBERT (Sentence-BERT) to evaluate how well candidate resumes match with job descriptions. Additionally, it identifies missing skills and provides relevant study resources to bridge these skill gaps. This tool is particularly useful especially for job seekers, or anyone looking to analyze their profiles in comparison to job requirements efficiently.

# Features
Semantic Matching: Utilizes SBERT to assess the similarity between job descriptions and resumes by encoding them into embeddings and calculating cosine similarity scores. This produces a "match score" indicating how closely a resume aligns with the job description.

Skill Gap Identification: The tool compares job description keywords with those found in the resume to identify skills that are missing from the candidate's profile.

Study Material Links: For each identified gap, a relevant study link is provided to help candidates acquire the missing skills.

Output: The final results include a match score, a list of gap topics, and study material links for each resume-job description pair, saved to a CSV file.



