# Banking-Application [SharePoint-Automate-PowerApps]

The Global Bank App is a comprehensive banking application developed using SharePoint, Power Apps, and Power Automate. This app provides a user-friendly and secure banking experience, offering various functionalities, including login, account management, payments, OTP verification, loan application, and loan approval/declined flow. This readme file provides an in-depth overview of the app's features, how to use them, and additional information.

## Introduction
The Global Bank App is built on the power of SharePoint, Power Apps, and Power Automate, providing seamless integration and robust functionality. Users can securely manage their accounts, perform transactions, and apply for loans using this feature-rich banking application.


## Features
- Login Screen: Users can securely log in using their credentials. The login screen also features a dynamic message marquee and changing images for an engaging experience.

- Home Page: After successful login, users land on the home page, displaying their basic account information. The page is divided into sections, including a header, blue box, grey box, and footer. Functionalities like account statement and money transfer are available.

- Payments Page: Users can initiate transactions by filling out the payment form. The form provides account number and date pre-filling and enables the "Transfer" button only when valid recipient details and transfer amount are entered.

- OTP Verification Page: Enhanced security is provided through OTP verification. A random 4-digit PIN is generated and sent to the user's email. Entering the correct OTP confirms the payment, while three incorrect attempts temporarily block the site.

- Payment Confirmation Page: Users receive transaction details after completing a payment. The confirmation email ensures accurate details, and clicking "Done" finalizes the transaction.

- Account Statement Page: The account statement displays the user's transaction history, with filtering options based on specific dates.

- Login Page Captcha: A captcha feature enhances security during the login process.

- Loan Application Form: Users can apply for loans through a form that automatically calculates repayable amounts, monthly installments, total interest, and eligibility based on user inputs.

- Loan Approval / Declined Flow: Loan approval requests are sent via email to authorities. The process includes information verification and branch manager approval. Users receive email notifications and visual indicators on the UI.

## Getting Started
Prerequisites
- A SharePoint environment to host the Global Bank App.
- Power Apps platform access to develop and deploy the app.
- Power Automate for automation of email notifications and other processes.


## Usage
Launch the app and navigate to the login screen.
Enter your valid credentials to log in. If incorrect, an error message will be displayed.
After logging in, explore the home page with account details and available functionalities.
To transfer money, click on the transfer icon and fill out the payment form with valid details.
Verify transactions using OTP sent to your email during the payment process.
Access payment confirmation details and check your account statement for transaction history.
Apply for a loan by filling out the loan application form with accurate details.
Track the status of your loan application through email notifications and the loan approval/declined flow UI.

## Implementation ScreenShots
![Screenshot 2023-07-22 115729](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/32fb3f2f-ebb0-47a5-ad12-fc84dc7cd3ac)
![Screenshot 2023-07-22 115650](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/1e994c24-52f3-488f-8534-8b4ffa065ddb)
![Screenshot 2023-07-14 193920](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/d656968d-717b-48b7-9c93-f05311c05391)
![Screenshot 2023-07-14 204107](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/eda663bc-5e05-4f80-a527-635c4a8dbf15)
![Screenshot 2023-07-14 204144](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/c193e913-2d53-4161-a1ab-f814525713d2)
![Screenshot 2023-07-14 204159](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/e54d7d42-b2db-463e-8009-5ee0e153b1af)
![Screenshot 2023-07-14 204738](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/3150cde2-1dc2-4649-b3fa-72892f50cbc2)
![Screenshot 2023-07-14 204802](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/171125a1-90cb-43a4-8a0d-f1763319f13f)
![Screenshot 2023-07-14 204938](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/d53e6487-54a2-4862-803d-3ffd482f9ee7)
![Screenshot 2023-07-14 204952](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/62214794-ba6b-4f8c-a865-b7661225d82c)
![Screenshot 2023-07-14 205015](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/9a0bcb97-0ba5-4ab6-88a7-2b3436f91938)
![Screenshot 2023-07-14 205108](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/ad78c490-46cb-4d6c-9181-bb6a6cd524d6)
![Screenshot 2023-07-14 205126](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/59b888c6-9b38-4845-8313-c8dff5848348)
![Screenshot 2023-07-14 205137](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/2912ca82-8aeb-40e2-955e-82b16de25d91)
![Screenshot 2023-07-14 210104](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/fd0eb010-a79b-486f-8a5a-bd9a544c1e8e)
![Screenshot 2023-07-14 210158](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/3783c55d-7ca7-46c2-b76e-88ffd5cbe773)

![Screenshot 2023-07-22 111108](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/99825c87-707f-4b55-8251-26ffb012d7e2)
![Screenshot 2023-07-22 111141](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/80b9e7a2-bf83-4ff5-bfe3-8a5037854000)
![Screenshot 2023-07-22 111621](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/0976fae4-f413-48b1-9e50-4f5c39a242ba)
![Screenshot 2023-07-22 111633](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/2349e30a-77de-49a8-9ba7-5edf1ad557c3)
![Screenshot 2023-07-22 111654](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/5e9eed99-976c-4eac-8384-123f9128b0e5)
![Screenshot 2023-07-22 111716](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/b0749023-8cd1-46ed-9430-53ce5de49762)
![Screenshot 2023-07-22 111731](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/73dbc00a-61bf-4a97-b4c3-95e67cc9fa37)
![Screenshot 2023-07-22 111755](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/38a23703-df94-4227-9d84-d4740841eb6b)
![Screenshot 2023-07-22 111814](https://github.com/Rutuj99/Banking-Application---SharePoint-Automate-PowerApps/assets/55624994/24ab1100-8f01-4ad4-b906-4aa646edc464)




















