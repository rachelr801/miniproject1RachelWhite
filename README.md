### INF601 - Advanced Programming in Python
### Rachel White
### Mini Project 1
 
 
# Project Title
 
API Client Practice to Get, Update, and Delete Post
 
## Description

This program contains the REST API code to post, get, update, and delete posts from the class practice API website. It also return various error messages, depending on the issue encountered. The program uses an API token that the user must set before running the program using the instructions listed below under Dependencies.

## AI Usage
I used Claude to do the initial push to GitHub because I wasn't sure how to accomplish that within Claude Code. I also used Claude to test whether the error messages printed correctly with the given scenarios.
 
## Getting Started
 
### Dependencies

To create your unique token follow these steps:
  Replace all three values below with your own. These are written so that they fail if you don't — if you send one unchanged you will  get a 422, not an account. Use the one that matches your terminal.

  macOS / Linux (also correct in Git Bash or WSL on Windows):
  curl -X POST https://practice.fhsucyber.com/api/v1/auth/register -H "Content-Type: application/json" -d '{"name":"YOUR       NAME","email":"YOUR_EMAIL_HERE","password":"YOUR_PASSWORD"}'
  
  Windows PowerShell:
  Invoke-RestMethod -Uri "https://practice.fhsucyber.com/api/v1/auth/register" -Method Post -ContentType "application/json" -Body   '{"name":"YOUR NAME","email":"YOUR_EMAIL_HERE","password":"YOUR_PASSWORD"}'
  Do not paste the curl version into PowerShell. There, curl is a built-in alias for a different command and quoting works   differently, so you will get a confusing error that has nothing to do with your account.

You must also install:
  pip install requests

 
### Installing

The program is located at: https://github.com/rachelr801/miniproject1RachelWhite.git
 
### Executing program

 Make sure to set your token in the same terminal you run the program from:
   export PRACTICE_API_TOKEN="your-token-here"      # macOS / Linux
   $env:PRACTICE_API_TOKEN = "your-token-here"      # Windows PowerShell

Run the program with python client.py.
 
## Help

If the program prints "PRACTICE_API_TOKEN is not set", then you will need to set it again in that window and re-run.
 
## Authors
 
Contributors names and contact info
 
Jason Zeller
jlzeller@fhsu.edu
 
## Version History
* 0.1
    * Initial Release
 
## License
 
This project is licensed under the Rachel White License.
 
## Acknowledgments
