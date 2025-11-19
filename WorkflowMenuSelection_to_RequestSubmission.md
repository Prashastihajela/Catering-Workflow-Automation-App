# Workflow: Menu Selection to Request Submission

This workflow illustrates the step-by-step process of how a user selects items from the catering menu, calculates the total, and submits a request for catering services.

**Use Case: *Creating a New Catering Request***

**User:** Event Planner or Client
**Objective:** Allow users to browse, select, and submit a catering request efficiently.

**Steps:**

1. User browses available menu items and selects preferred items.
2. Uses the Price Calculator to compare different items based on budget.
3. Fills out the Catering Event Booking Form in Power Apps. 
4. The submission is automatically stored in SharePoint for tracking.

- **Workflow:**
    
    **Start Event:** The user opens the app and navigates to the Menu screen.
    
    **Task 1: Menu Selection:** The user selects one or more menu items.
    
    **Task 2: Price Calculation:** The app calculates the subtotal and adds service charges based on the selected service type.
    
    **Task 3: Order Confirmation:** The user reviews the order on Quote Summary Screen. 
    
    - If **Not Satisfied** → User **Edits Order** → Returns to Task 1.
    - If **Satisfied**, the user **confirms selection** and proceeds.
    
    **Task 4:** The app redirects the user to the form submission screen.
    
    **Task 5:** The user enters event details (e.g., event date, location, guests, etc.).
    
    **Task 6:** The user clicks Submit.
    
    - If all fields are valid, the form is submitted successfully → Moves to Task 7.
    - If errors are detected, the user is prompted to fix the errors before resubmitting.
    
    Task 7: On successful submission, the request is stored in SharePoint.
    
    **End Event:** A confirmation message is displayed, informing the user that the form has been successfully submitted.
    

![Menu to Form Submission Workflow.png](Media/Images/Menu_to_Form_Submission_Workflow.png)

[Menu-to-FormWorkflow.mp4][Watch Video](Media/Videos/Menu-to-FormWorkflow.mp4)

<aside>


### Home Page Upgrade – Smarter Navigation & Personalization

</aside>

![***Original Home Page (Before)***](Media/Images/Original_Homepage.png)

***Original Home Page (Before)***

[***New Home Page (After)***](Media/Videos/New_Homepage_(After).mp4)

***New Home Page (After)***

<aside>

*A refreshed interface with a structured layout, left-side navigation, and dynamic personalization—making catering reservations smoother than ever.*

</aside>
