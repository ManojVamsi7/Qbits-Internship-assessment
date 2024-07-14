# CRM CLI Application

## Overview

This CRM (Customer Relationship Management) CLI (Command Line Interface) application is designed to help Business Development Associates (BDAs) manage their leads efficiently. The application includes functionalities for creating new users, managing leads, uploading data to a database, viewing payouts, and visualizing lead distribution.

## Features

- **User Management**: Create new BDA users and log in existing users.
- **Lead Management**: Assign, view, and update lead statuses.
- **Database Integration**: Store and manage data in an SQLite database.
- **Payout Calculation**: Calculate payouts based on lead conversions.
- **Data Visualization**: Visualize lead distribution using pie charts.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ManojVamsi7/Qbits-Internship-assessment.git


3. Install Dependencies

Ensure you have Python installed on your system. Then, install the required Python packages:
pip install -r requirements.txt
should include:

1. numpy
2. pandas
3. plotly

Run the Application

  ```bash

Copy code

python main.py

Usage

Start the Application: Run python main.py.

Choose Role:

Select 1 if you are an existing user.

Select 2 if you are a new user.

For New Users:

Enter your name, phone number, and email to create a new BDA account.

For Existing Users:

Enter your name and phone number to log in.

BDA Panel:

Choose from the available options to work on leads, view payouts, upload data to the database, or visualize lead data.

Database Schema
bda: Stores BDA user information.

id: Unique identifier for the BDA.
name: Name of the BDA.
mobile: Mobile number of the BDA.
email: Email address of the BDA.
sales: Stores lead information.

id: Unique identifier for the lead.
bda_id: Identifier of the BDA assigned to the lead.
name: Name of the lead.
mobile: Mobile number of the lead.
lead_result: Result of the lead interaction.
lead_status: Status of the lead (0 for unhandled, 1 for handled).
created_at: Timestamp when the lead was created.
bda_payouts: Stores payout information for BDAs.

id: Unique identifier for the payout.
bda_id: Identifier of the BDA receiving the payout.
payout_date: Date of the payout.
remarks: Remarks about the payout.
amount: Payout amount.
Contribution
Feel free to fork the repository and submit pull requests. For major changes, please open an issue to discuss what you would like to change.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any inquiries or feedback, please contact Manojvamsi07
