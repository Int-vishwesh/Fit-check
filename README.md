# Fit-check
- a resume and job description compatibility checker, with estimated ats score for specific job description

- uses natural language processing to match keywords and phrases from resume and job description i.e openAI 


## technology
- html/css
- JavaScript
- make.com

## approach
- getting jd and resume of user from the form
- transferring these data to make.com modules using axios through http
- after that connected module of make.com to openai api using api key
- processing those data with keywords and all formality
- returning the result to the user in their mail