- Create Workflow: Start a new workflow in n8n.

- On Form Submission Trigger: The workflow begins when a form is submitted. This triggers the "On form submission" event.

- Append Row in Google Sheet: After the form is submitted, the data is added to a Google Sheet by using the "Append row in sheet" node.
  
-   This stores the form data in your specified Google Sheet.

- Google Sheets Trigger: After the row is added to the sheet, a "Google Sheets Trigger" node is used to listen for any new rows added to the sheet.

-   This acts as a trigger whenever a new form submission (row) is added.

- Send Message (via Gmail): Once a new row is detected by the Google Sheets trigger, the "Send message" node sends a message (likely an email) using Gmail or another communication method.

- Execute Workflow: Finally, the workflow can be executed automatically when a form is submitted, triggering all the steps in sequence.
  # screen shot
  <img width="729" height="485" alt="image" src="https://github.com/user-attachments/assets/b5c0af91-7222-4573-ad26-5f20c1ff8bef" />
