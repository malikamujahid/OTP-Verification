# OTP-Verification
# OTP Verification GUI using Twilio API and Tkinter

This is a simple OTP (One-Time Password) verification application built using Python and Tkinter GUI library. The application uses the Twilio API to send an OTP to the specified phone number and allows the user to verify the received OTP.

## Features

- Generates a random OTP and sends it to a specified phone number using Twilio API.
- Provides a GUI interface for users to enter the OTP received on their phone.
- Verifies the entered OTP against the sent OTP and displays a success message if the OTP is correct.
- Provides an option to resend the OTP if needed.


## Getting Started

To run this application on your local machine, follow the steps below:

**1. Clone the repository to your local machine using the following command:**
   git clone https://github.com/your-username/otp-verification.git
2. **Install the required dependencies**
You can use the following command to install the required packages using pip:
   pip install twilio tkinter
3.** Replace the Twilio credentials with your own in the `otp_verifier` class. **
Look for the following lines in the code and update them with your Twilio Account SID and Auth Token:

```python
self.client = Client("YOUR_ACCOUNT_SID", "YOUR_AUTH_TOKEN")
Ensure you have an active internet connection to send SMS messages using Twilio API.

**Run the application using the following command:**

python OTP.py

**Requirements**
Python 3.x
Twilio Account SID and Auth Token (sign up at https://www.twilio.com/try-twilio)
tkinter (Tkinter is usually included with Python, so no separate installation is required.)
**Contributions**
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
      

