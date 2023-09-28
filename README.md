# Course Schedule Generator and Timetable SMS Notifier

## Overview

This project is designed to help students create a personalized schedule based on their courses and receive their timetable using the Africa's Talking USSD service for input and the SMS API for notification. Additionally, the timetable is generated using the Chat GPT website API.

This README will guide you through setting up and using the application effectively.

## Features

- **Course Schedule Creation**: Students can input their course details through the Africa's Talking USSD service.

- **Timetable Generation**: The timetable is created using the Chat GPT website API based on the user's course information.

- **Timetable Notification**: Students receive their timetable via SMS using the Africa's Talking SMS API.

## Requirements

To run this project, you will need:

- [Node.js](https://nodejs.org/) installed on your machine
- Africa's Talking USSD Service API Key
- Africa's Talking SMS API Key
- Access to the Chat GPT website API

## Setup

1. **Clone the Repository**: Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/your-project.git
   ```
2. Install Dependencies: Navigate to the project directory and install the required Node.js packages.
```bash
npm install
```
3. Configuration: Create a .env file in the project directory and add your API keys for Africa's Talking USSD and SMS services, and the Chat GPT API.
```env
AFRICAS_TALKING_USSD_API_KEY=your_ussd_api_key
AFRICAS_TALKING_SMS_API_KEY=your_sms_api_key
CHAT_GPT_API_KEY=your_chat_gpt_api_key
```
## Usage

- Input Your Courses: To create your course schedule, access the USSD service. Use your phone to dial the USSD code provided by the application.

- Timetable Generation: Once you've input your courses, the application will use the Chat GPT API to generate your timetable based on the provided information.

- Timetable Notification: After the timetable is generated, you will receive an SMS notification with your timetable details via the Africa's Talking SMS service.

## Troubleshooting
If you encounter issues while setting up or using the application, please refer to the documentation of the individual APIs used (Africa's Talking USSD and SMS, Chat GPT API) for troubleshooting guidance.
Contributing
Contributions to this project are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes to suggest.

## License
This project is licensed under the IT License.

## Acknowledgments
The developers would like to thank Africa's Talking and Chat GPT for providing the APIs used in this project.

## Contact
If you have any questions or need further assistance, please contact us at me@email.com.

