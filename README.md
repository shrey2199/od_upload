# OD Upload

A Jupyter notebook for uploading files to OneDrive using Rclone. Supports uploading movies from URLs and series from zip files.

## Prerequisites

- Google Colab environment (recommended)
- Rclone configuration file

## Installation

Run the first cell in the notebook to install required dependencies:
- aria2
- rclone

## Usage

### Movie Upload from URL
1. Enter the download URL when prompted
2. Optionally change the filename
3. The file will be downloaded and uploaded to the "Movies" folder on OneDrive

### Series Upload from Zip File
1. Enter the zip download URL
2. Download and extract the zip file
3. Upload the extracted folder to the "Series" folder on OneDrive using Rclone

## Configuration

Edit the `remote_name` variable in the relevant cells to match your Rclone remote configuration.