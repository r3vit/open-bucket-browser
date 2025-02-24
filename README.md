# Open Bucket Browser

Open Bucket Browser is a lightweight web interface designed to navigate and explore open S3 buckets.

It fetches all bucket content beyond the default 1000-item limit, organizes files into a user-friendly folder structure, and lets you copy the complete URL of any file with a single click.

## Features

- **Navigation:** browse bucket contents organized in a nested folder structure.
- **File Type Icons:** icons for images, videos, JSON/text, and database files.
- **Copy URL on Click:** clicking a file copies its full URL to the clipboard for easy sharing.
- **Complete Data Retrieval:** Handles multiple pages of S3 listings to display all available files (not just your first 1000s).

## How to Use

1. **Open the `index.html` file in your browser.**
2. **Enter the Bucket URL:** paste the URL of your open S3 bucket (without a trailing slash and with https) into the input field at the top.
3. **Load the Bucket:** click the **Load Bucket** button to fetch and display the bucket contents.
4. **Copy File URL:** click on any file to copy its complete URL to your clipboard.

## Requirements

- A publicly accessible S3 bucket.
- A modern web browser that supports the Fetch API and Clipboard API.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the WTFPL v2
