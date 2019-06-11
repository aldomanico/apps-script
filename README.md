# apps-script

Step A: Create new stand-alone script
1. Login to Google Account
2. Go to script.google.com
3. Click New Script
4. Copy-paste existing script contents or create from scratch
5. Name the script and click Save

Step B: Create new forms-based script
1. Login to Google Account
2. Create a new form or click on an existing form
3. From the form edit screen, click on the 3 dots in the top right corner, and click Script Editor
4. Copy-paste existing script contents or create from scratch
5. Name the script and click Save

To run calendar-report:
1. If not already created, follow Step A for calendar-report
2. Confirm correct calendar id on line 16 of the script
3. Click the Play button or Run Function
4. Output is saved to Google Drive

To run legal-risk-memo:
1. If not already created, follow Step B for legal-risk-memo
2. Adjust desired variables:
  2a. document name and header on lines 101 and 105 of the script
  2b. destinationGoogle Drive folder on line 155
  2c. email settings on lines 175-178
5. Click the Play button or Run Function
6. Output is saved as a pdf in designated Google Drive folder and emailed to listed recipients
