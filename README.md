# OCR Tesseract Docker for AWS Elastic Beanstalk
Allows upload of an image for OCR using Tesseract and deployed using Docker.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need Docker installed on your system and a command line editor.

```
Docker
Git Bash (on Windows)
Terminal (Linux or Mac)
```

### Installing and Running

You can clone this repository or download a zip file, build and run the Docker image.http://ocr-tesseract-docker-aws-dev.us-east-1.elasticbeanstalk.com/
```
$ docker build -t ocr-tesseract-docker-aws .
$ docker run -d -p 5000:5000 ocr-tesseract-docker-aws
```

OR you can pull and/or run the Docker image from my repository on Docker Hub

```
docker pull ricktorzynski/ocr-tesseract-docker-aws
docker run -d -p 5000:5000 ricktorzynski/ocr-tesseract-docker-aws
```
Then open up browser to http://localhost:5000

You can use these images to test it - these are photos of a job posting with NLP Logix:

* [Job Posting 1](https://www.torzyn.com/ocr/senior_python_developer_nlplogix1_sm.jpg)
* [Job Posting 2](https://www.torzyn.com/ocr/senior_python_developer_nlplogix2_sm.jpg)
* [Job Posting 3](https://www.torzyn.com/ocr/senior_python_developer_nlplogix3_sm.jpg)

## Deployed to AWS Elastic Beanstalk

http://ocr-tesseract-docker-aws-dev.us-east-1.elasticbeanstalk.com/

## Built With
```
Python
Flask
Pytesseract
OpenCV
Bootstrap
Docker
```

## Acknowledgments

I would like to thank Matt Berseth and Robert Marsh of NLP Logix for inspiring me to build this application - I have learned a great deal in a short amount of time.  I can finally begin integrating development and data science in a meaningful way.

