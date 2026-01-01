CLI Input
reposcope https://github.com/openmrs/openmrs-core


CLI Output (Plain, clean) ::
Repo name
Primary language
Stars
Forks
Open issues
“Good first issue” count
Last commit date


TECH STACK (FINAL) 💻
Python 3.10+
requests
argparse (no Typer luxury)
GitHub REST API v3

reposcope/
├── reposcope/
│   ├── __init__.py
│   ├── github_api.py
│   ├── analyzer.py
│   └── cli.py
├── tests/
│   └── test_analyzer.py
├── README.md
├── requirements.txt
└── setup.py
