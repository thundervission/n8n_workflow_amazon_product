# n8n_workflow_amazon_product
Amazon MacBook M4 Price Tracker Automation
# Amazon MacBook M4 Price Tracker Automation

## Overview

This repository contains an n8n workflow that automates the tracking of the Apple MacBook Air M4 13-inch (256GB) price on Amazon. The workflow monitors price changes and alerts users when significant fluctuations occur, helping shoppers grasp the best buying time.

## Features

- Periodic price monitoring via ScrapeOps API
- Detailed price change alerts via email or notification
- Calculates percentage and absolute price differences
- Handles price increase and decrease scenarios
- Easy import/export via n8n JSON workflow file

## Getting Started

### Prerequisites

- An active n8n instance (self-hosted or cloud)
- ScrapeOps API key (sign up at https://scrapeops.io)
- Gmail or SMTP credentials for email notifications (optional)

### Installation

1. Clone or download this repository.
2. Open your n8n editor.
3. Import the workflow JSON file `Amazon_product_macbook_m4_tracking.json`.
4. Configure your credentials:
   - ScrapeOps API key
   - Email service credentials for notifications
5. Adjust monitored product URLs or ASINs as needed.
6. Activate the workflow schedule to your desired frequency.

### Usage

- The workflow fetches product information and pricing from Amazon.
- When a price change threshold is crossed, it sends an alert with product details.
- Review the alert email for actionable insights.

### Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

### License

This project is licensed under the MIT License.

### Contact

Author: [Your Name or GitHub Username]  
Email: your.email@example.com  

---

