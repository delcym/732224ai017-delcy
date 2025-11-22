- Create Workflow: Start by creating a new workflow in n8n.

- When Clicking 'Execute Workflow' Trigger: The workflow begins when the "Execute workflow" button is clicked. This triggers the process manually.

- Get Row(s) in Google Sheet: After the workflow is triggered, the next step is to retrieve the rows from a Google Sheet using the "Get row(s) in sheet" node.

- This reads the data from the specified Google Sheet.

- If Condition: Next, an "If" condition is used to check whether a specific condition is met (e.g., whether the row data meets a certain criterion).

- The workflow will branch based on the result of this condition:

- True Path: If the condition is true, data will be appended to one Google Sheet (Append row in sheet).

- False Path: If the condition is false, data will be appended to a different Google Sheet (Append row in sheet1).

- Append Row in Google Sheet: Based on the result of the "If" condition, the data will be appended to either Sheet 1 or Sheet 2.

- Execute Workflow: Finally, the workflow is executed when the "Execute workflow" button is clicked.
  # screen shot
  <img width="1125" height="453" alt="image" src="https://github.com/user-attachments/assets/2a628f1c-23b8-41cf-8bb7-93cd49792bff" />
