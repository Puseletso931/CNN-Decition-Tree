# Project Setup

## Step 1: Install Requirements
To install all required libraries, run:
```bash
pip install -r requirements.txt
```
## Step 2: Graphviz Setup (Windows Users)

For Windows users, Graphviz may require additional setup:

### 1. Install Graphviz
Download the Graphviz installer from the [Graphviz download page](https://graphviz.gitlab.io/download/).

### 2. Set the Graphviz Path
After installation, add Graphviz's `bin` directory to your system's PATH environment variable. This allows `pydotplus` to locate Graphviz.

- Open **Environment Variables** settings.
- Edit the `PATH` variable to include the path to your Graphviz `bin` directory, usually:
  ```plaintext
  C:\Program Files\Graphviz\bin
   ```