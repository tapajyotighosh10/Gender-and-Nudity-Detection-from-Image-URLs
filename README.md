Gender and Nudity Detection from Image URLs

This Python project processes a list of image URLs to detect and classify gender, race, and nudity in the images. The project automates the process of downloading images, analyzing them using third-party APIs, and generating an Excel report with the results.
Features

    Image Downloading: Automatically downloads images from a provided list of URLs.
    Third-Party API Integration: Utilizes two external APIs to detect and classify gender and nudity in the images.
    Excel Report Generation: Creates an Excel file with the following columns:
        URL: The original URL of the image.
        Image: The downloaded image inserted into the Excel sheet.
        Filename: The name of the saved image file.
        Gender: Gender detection results from the API.
        Race: Race classification results (if available).
        Nudity: Nudity detection results from the API.
    Batch Processing: Efficiently processes a batch of 466 URLs to produce the final report.

How It Works

    Download Images: The script fetches images from the given URLs and saves them locally.
    API Requests: Each image is sent to the respective third-party APIs to extract gender and nudity information.
    Excel Report: The data is compiled into an Excel sheet with images and classification results.

Prerequisites

    Python 3.x
    Required Python libraries: requests, openpyxl, PIL
