# Spam Email Detection

## Introduction

This project focuses on detecting spam emails using a dataset containing information from 5,172 randomly selected email files. The goal is to build a classification model that can accurately distinguish between spam and not-spam emails based on the content of the emails.

## About the Dataset

The dataset is provided in a CSV file with the following characteristics:

- **Rows**: 5,172 rows, each representing an individual email.
- **Columns**: 3,002 columns in total.
  - **First Column**: Indicates the email name. The names have been anonymized with numbers to protect privacy.
  - **Last Column**: Contains the labels for classification:
    - `1` for spam emails.
    - `0` for not-spam emails.
  - **Remaining 3,000 Columns**: These columns represent the 3,000 most common words across all emails, excluding non-alphabetical characters. Each cell in these columns contains the count of the respective word in the corresponding email.

This compact representation allows for efficient processing and analysis of email data without needing to work with separate text files.

## Project Structure

The project is organized as follows:

- `data/`: Contains the CSV file with email data for spam detection.
- `notebooks/`: Jupyter notebooks for data exploration, feature selection, model training, and evaluation.
- `models/`: Saved models and related artifacts.
- `README.md`: Project overview and documentation.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/spam-email-detection.git

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact `Argha Dey Sarkar` at [email2argha@gmail.com].
