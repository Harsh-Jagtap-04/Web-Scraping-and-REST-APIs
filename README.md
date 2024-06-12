# Web-Scraping-and-REST-APIs

Welcome to my GitHub repository! This project is designed to demonstrate how to fetch and display repository information from GitHub using Python and web scraping.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This repository contains two main Python scripts:

1. **GitHub API Script**: This script fetches information about a specific GitHub repository using the GitHub API.
2. **Web Scraping Script**: This script scrapes the GitHub topics page to extract information about popular repositories in a given topic.

## Features

- **Fetch GitHub Repository Details**: Retrieve details such as description, star count, and open issues for a specified repository using the GitHub API.
- **Scrape GitHub Topic Pages**: Extract details of popular repositories from the GitHub topics page.
- **Combining Data**: Merge data from the API and scraping to provide a comprehensive overview of repositories.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name


## Usage

### GitHub API Script

To fetch details about a specific GitHub repository, run the `github_api_script.py` script:

```python
# Replace 'username' and 'repository_name' with the actual values
python github_api_script.py username repository_name
