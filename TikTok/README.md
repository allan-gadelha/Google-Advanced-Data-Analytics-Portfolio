# TikTok Claim Classification Project

Welcome to your new role at TikTok! This project focuses on the development of a predictive model to classify claims and opinions within TikTok videos and comments. As a data analyst on the TikTok data team, your insights and contributions will play a crucial role in enhancing the efficiency of handling user reports.

## Project Goal

TikTok aims to develop a predictive model that can accurately determine whether a video contains a claim or offers an opinion. The successful implementation of this model will help reduce the backlog of user reports, allowing for more efficient moderation.

## Project Background

TikTok’s data team is in the early stages of the claims classification project. Before diving into data analysis, the following tasks need to be accomplished:

- Create a project proposal with organized milestones.
- Classify tasks using the PACE workflow.
- Identify relevant stakeholders.

## Team Members at TikTok

### Data Team Roles
- Willow Jaffey - Data Science Lead
- Rosie Mae Bradshaw - Data Science Manager
- Orion Rainier - Data Scientist

### Cross-functional Team Members
- Mary Joanna Rodgers - Project Management Officer
- Margery Adebowale - Finance Lead, Americas
- Maika Abadi - Operations Lead

## Meeting Notes

### Mary Joanna Rodgers (Project Management Officer)
- The project requires a global document identifying deliverables and milestones.
- Visuals need to be generated for sharing with TikTok executives.

### Orion Rainier (Data Scientist)
- Understanding the data is crucial, including inspecting the dataset for missing data.
- Exploratory Data Analysis (EDA) is needed to determine useful information in TikTok’s data.
- Statistical testing will be essential, along with running hypothesis tests.

### Willow Jaffey (Data Science Lead)
- The goal is to build and deliver a reliable machine learning model.
- Determining the type of regression model for the project is essential.
- Main talking points for the presentation to the leadership team need to be identified.

### Rosie Mae Bradshaw’s Thoughts and Concerns
- Suggests using Python for the project.
- Checking assumptions made by any regression modeling.
- Identifying and setting up the project’s workflow.

### Data dictionary

This project uses a dataset called tiktok_dataset.csv. It contains synthetic data created for this project in partnership with TikTok. 

The dataset contains: 

19,383 rows – Each row represents a different published TikTok video in which a claim/opinion has been made.

12 columns 

| Column name               | Description                                                                                                      |
|---------------------------|------------------------------------------------------------------------------------------------------------------|
| #                         | TikTok assigned number for video with claim/opinion.                                                              |
| claim_status              | Whether the published video has been identified as an “opinion” or a “claim.”                                   |
| video_id                  | Random identifying number assigned to video upon publication on TikTok.                                        |
| video_duration_sec        | How long the published video is measured in seconds.                                                             |
| video_transcription_text  | Transcribed text of the words spoken in the published video.                                                     |
| verified_status           | Indicates the status of the TikTok user who published the video in terms of their verification, either “verified” or “not verified.” |
| author_ban_status         | Indicates the status of the TikTok user who published the video in terms of their permissions: “active,” “under scrutiny,” or “banned.” |
| video_view_count          | The total number of times the published video has been viewed.                                                    |
| video_like_count          | The total number of times the published video has been liked by other users.                                     |
| video_share_count         | The total number of times the published video has been shared by other users.                                    |
| video_download_count      | The total number of times the published video has been downloaded by other users.                                |
| video_comment_count       | The total number of comments on the published video.                                                              |