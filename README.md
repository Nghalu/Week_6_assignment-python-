#  Ubuntu Image Fetcher

A simple yet powerful Python tool for **mindfully collecting images from the web**.  
The script downloads images from given URLs, validates their content type, and saves them neatly into a local folder — avoiding duplicates and handling errors gracefully.
## Features

-  Fetches one or multiple images from URLs  
-  Automatically creates a `Fetched_Images` directory if missing  
- Validates that files are actual images before saving  
-  Skips duplicates based on filenames  
-  Gracefully handles connection and HTTP errors  
-  Generates unique filenames when missing in the URL  
- User-friendly console output for easy tracking  

## How It Works

1. The script prompts you to enter one or more image URLs (comma-separated).  
2. For each URL, it:
   - Checks if it’s a valid image
   - Creates a safe filename
   - Downloads and saves it to the `Fetched_Images/` folder
3. Skips any duplicates or invalid files.
4. Prints a summary of successful downloads.
