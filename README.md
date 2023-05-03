
# Plagiarism Detector

A web application to check if a document's contents are plagiarised or not.


## Steps:

- User enters a query/text.
-  gets processed (Uppercase to lowercase, Removal of punctuationmarks, etc.)
- Resulting URL, matched contents are checked for similarity with given text query.
- The Plagiarism Percentage is returned on the web page along with links of sites matched.


## Web Screenshots:

![UI] [url=https://ibb.co/188M4kT][img]https://i.ibb.co/188M4kT/Screenshot-2023-05-01-165933.png[/img][/url]

![Plagiarised data] [url=https://ibb.co/4SW4B9h][img]https://i.ibb.co/4SW4B9h/Screenshot-2023-05-01-165908.png[/img][/url]


## Run Locally

Clone the project

```bash
  git clone git@github.com:Aayush-Gangwar/Plagiarism-Detector.git
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  run main.py
```

