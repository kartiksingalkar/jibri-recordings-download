# jibri-recordings-download
Search and Download Jitsi Meet Jibri recording files from server to local system using flask app.

Description:
This Flask application provides a RESTful API to search and download Jitsi Jibri recordings stored on a Linux virtual machine. It allows users to search for recordings based on a provided filename and generates downloadable links for the matching files.

Prerequisites:
Linux virtual machine with Jitsi Jibri recordings stored in a specified directory.
Python 3.x installed on the virtual machine.
Basic knowledge of Flask, Gunicorn, and Nginx for deployment.

Note:
Modify the recording_directory variable in the app.py file to point to the directory where your Jitsi Jibri recordings are stored.
