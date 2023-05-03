
# Plagiarism Detector

A web application to check if a document's contents are plagiarised or not.


## Steps:

- User enters a query/text.
-  gets processed (Uppercase to lowercase, Removal of punctuationmarks, etc.)
- Resulting URL, matched contents are checked for similarity with given text query.
- The Plagiarism Percentage is returned on the web page along with links of sites matched.


## Web Screenshots:

![UI] ![Screenshot 2023-05-01 165933](https://user-images.githubusercontent.com/125241405/235997302-2a66bdef-0735-48a6-bc56-91aeb46a1c4d.png)

![Plagiarised data] ![Screenshot 2023-05-01 165908](https://user-images.githubusercontent.com/125241405/235997508-7bf44cca-22d6-47c1-9865-87672257243b.png)


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

