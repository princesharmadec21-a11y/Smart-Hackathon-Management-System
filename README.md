# HackMate – Smart Hackathon Management MVP

A Python + Google Colab prototype to help organizers manage hackathon registrations, project submissions, judging, and leaderboards.

## Features
- Register teams with unique team IDs
- Submit GitHub and presentation links
- Score projects using consistent criteria
- Calculate average scores across judges
- Display an automatically ranked leaderboard
- Export CSV backups

## Judging criteria (100 points)
| Criterion | Maximum |
|---|---:|
| Innovation | 20 |
| Working demo | 25 |
| Technical skills | 25 |
| Usefulness | 15 |
| Presentation | 15 |

## Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `HackMate_Hackathon_MVP.ipynb`.
3. Run the notebook cells from top to bottom.
4. Register teams, submit projects, add judge scores, and refresh the leaderboard.

## Dependencies
`pandas`, `ipywidgets`, `IPython` (typically available in Colab).

## Limitations
This is an in-memory demo, not a deployed multi-user portal. Data is lost when the runtime resets unless exported to CSV. No authentication or persistent database is included. Do not use it to store real participant data without adding security and persistence.
