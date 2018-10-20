# Docker Compose Testing

# Requirements:
  - Python 2.7: https://www.python.org/downloads/
  - Pip: https://pip.pypa.io/en/stable/installing/
  - Docker CE: https://docs.docker.com/install/
  - Docker Compose: https://docs.docker.com/compose/install/


# Using This Repo
1. Install the required packages listed above
2. Download this Repo
3. Navigate to the root of the repo
4. Run 'docker compose up'
5. Navigate to 'localhost:9001' in a web browser
6. Refresh the page as many times as you'd like
7. Verify the number of page hits increases with each page refresh
8. Alternatively, run `curl localhost:9001` from a terminal (requires 'curl')
9. Verify the number of page hits increases each time you rerun the curl command

# Expected Results

Web Browser:
[![N|Solid](https://s3.amazonaws.com/gbruno-images/docker-compose-results-browser.png)](https://nodesource.com/products/nsolid)
---
Terminal:
[![N|Solid](https://s3.amazonaws.com/gbruno-images/docker-compose-results-terminal.png)]

