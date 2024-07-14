
# Homework 7

For this assignment, I have created the repository form scratch. I have installed the docket and setup the account.
I have installed the requirement.txt file.

## Installation

1.Clone the repo
2.Install and activate virtual environment
3.Install the requirements.txt file

## Building the image 

I have used below docker commands to build the image.
1. docker build -t my-qr-app .
2. docker run -d --name qr-generator \
  -e QR_DATA_URL='https://example.com' \
  -e QR_CODE_DIR='qr_codes' \
  -e QR_CODE_FILENAME='exampleQR.png' \
  -e FILL_COLOR='blue' \
  -e BACK_COLOR='white' \
  my-qr-app

## Below is the QR code which directs to my github homepage:

![Github QR Code](image.png)

### log for creating th QR code:
![Log for successfully creating the QR code](log.png)