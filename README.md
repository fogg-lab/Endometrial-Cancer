# Endometrial-Cancer

Data retrieval script - download and extract the dataset.

### Prerequisites
- [Python 3.9 or higher](https://www.python.org/downloads/)
- [git](https://git-scm.com/)
- [requests](https://pypi.org/project/requests/)

## Instructions

1. Clone this repo and navigate to its directory.
    ```
    git clone https://github.com/fogg-lab/Endometrial-Cancer.git
    cd Endometrial-Cancer
    ```

2. Run the download script.

    For the command below, the "." at the end expands to the current working directory.
    ```
    python download_dataset.py .
    ```

    To download to a different location, specify a different directory. For example:
    ```
    python download_dataset.py "C:\Users\me\datasets"
    ```
