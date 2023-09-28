# Phone Email Multithreaded Scraper

Project for extract emails and phones from a list of web pages, with multithreading, using requests, bs4, regex and selenium for get more data.

</div><br><details>
            <summary>Table of Contents</summary>
            <ol>
<li><a href='#details'>Details</a></li>
<li><a href='#install'>Install</a></li>
<li><a href='#settings'>Settings</a></li>
<li><a href='#run'>Run</a></li>
<li><a href='#roadmap'>Roadmap</a></li></ol>
        </details><br>

# Details

This project is for extract emails and phones from a list of web pages, with multithreading, using requests, bs4, regex and selenium for get more data.

The script extract emails and phones from the web pages in the `input .txt` file, and save the output in the `output.csv` file.

The script use multithreading for extract data from the web pages faster.

The script use selenium (google chrome) for get more data from the web pages, because some web pages use javascript to show the data. You can use or not it (see the `USE_SELENIUM` variable in the `.env` file).

You can setup the number of threads in the `.env` file (see the `THREADS` variable).

# Install

## Prerequisites

* [Google chrome](https://www.google.com/intl/es-419/chrome/)
* [Python >=3.10](https://www.python.org/)
* [Git](https://git-scm.com/)

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Abhi6722/phone-email-multithreaded-scraper
   ```
2. Install python packages (opening a terminal in the project folder)
   ```sh
   python -m pip install -r requirements.txt 
   ```

# Settings

1. Set your option in the file `.env`
2. Put the web pages in the `input.csv` file

# Run

1. Run the project folder with python: 
    ```sh
    python .
    ```
2. Wait until the script finish, and check the `output.csv` file in the project folder

# Roadmap

- [x] Extract email and phone using requests and bs4
- [x] Extract email and phone using regex
- [x] Extract email and phone using selenium
- [x] Multithreading
- [x] `.env` file for options

