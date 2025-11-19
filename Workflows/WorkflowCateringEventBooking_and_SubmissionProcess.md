# Workflow: Catering Event Booking & Submission Process

The catering request process begins when a user accesses the SharePoint team site and opens the Catering App. They fill in the Catering Event Booking Form, explore the menu, select items, review the order, and confirm their selection. The system auto-populates the form with the selected items, and after validation, the user submits it. Once submitted, a confirmation message appears, and the user can review their request on SharePoint.

- **Workflow**:
    
    **Process Start:** The user initiates the process by accessing the SharePoint team site.
    
    1. **Navigation**
        - Launch the Catering App: Clicks the provided link on this site, to open the Catering App.
        - Navigate to Form: Moves to the Catering Event Booking Form to begin a new request.
    2. **Enter Event Details**
        - Fill Request Details: The user enters the required event details such as date, event name, and other required information.
        - Proceed to Menu: Clicks the designated button to move to the menu selection screen.
    3. **Food Selection**
        - On Menu screen: The user selects preferred food items, specifies quantity, and adds them to the cart.
        - Quote Summary screen: Displays the selected food items along with pricing details for final review.
    4. **Decision: Confirm Selection?** (Decision Point)
        - **No >** The user can:
            - Update item quantities.
            - Delete an item from the selection.
            - Return to the menu to add new items.
        - **Yes** > Proceeds to the form with the selected items.
    5. **Auto-Population & Review**
        - Update Form Automatically: The selected menu items are auto-filled into the form under the food selection field.
        - Review Form: The user reviews all entered details to ensure accuracy before submission.
    6. **Decision: Are All Fields Valid?** 
        - **No** > The system identifies missing or incorrect fields and prompts the user with an error message to make corrections.
        - **Yes** > The form proceeds to submission.
    7. **Submission & Confirmation**
        - Form Submitted Successfully: A confirmation message is displayed, indicating successful submission.
    8. **Post-Submission & Review**
        - Return to SharePoint site: The user navigates back to SharePoint site to check the submitted requests.
        - View Submitted Requests: The system displays only the requests submitted by the user.
    9. **Process Ends**
        - The process is completed successfully.

![Catering Event Booking & Submission Process.png](Media/Images/Catering_Event_Booking__Submission_Process.png)

[Form-to-MenuWorkflow.mp4](Media/Videos/Form-to-MenuWorkflow.mp4)
