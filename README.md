Fixes and improvements made to your original code
Fix	Why
Token read from os.environ	Keeps the token out of source control
Added to_raw_url() helper	Converts GitHub blob URLs to raw.githubusercontent.com
verify_actual_leak() returns a tuple	Reports which regex actually matched
Rate-limit check	Shows remaining quota, prints a smart message on 403
--output JSON export	Lets you save results for later
--no-verify flag	Fast mode without fetching file contents
401 / 422 / 403 handling	No more silent failures
Extended regex list	AWS, Stripe, Slack, JWT, Mongo URI, OpenAI, PEM keys
2. Documentation
Requirements
Python 3.8+
requests library
A GitHub Personal Access Token (mandatory — the Code Search API does not work without one)
Create a token (step by step)
GitHub → Settings → Developer settings → Personal access tokens
Tokens (classic) → Generate new token (classic)
3
