# Catering Menu Management Workflow

The Real-Time Menu Change Process enables catering managers to update menu items dynamically via the SharePoint List and PowerApps. This ensures that changes in the menu, such as price modifications, name updates, and new additions are immediately visible to users (employees/customers) after republishing. This process enhances operational efficiency by ensuring instant updates to menu items without manual intervention. It improves accuracy by preventing outdated information from being displayed, leverages automation to streamline updates, and enhances user experience by providing employees and customers with the most current menu options in real time. 

- **System Impact & Benefits**
    - **Efficiency** – Changes are applied instantly, eliminating delays in menu updates.
    - **Accuracy** – Ensures that only the most recent and correct menu items are visible.
    - **Automation** – Minimizes manual intervention by seamlessly syncing updates across platforms.
    - **User Experience** – Provides customers and employees with real-time access to the latest menu, enhancing satisfaction.
    
- **Use Case: *Real-time updates in Menu***
    
    **User:** Catering Manager
    
    **Steps:**
    
    1. Manager Receives Update Request: A supplier, chef, or internal team informs the catering manager about menu changes (e.g., price adjustments, availability updates, or new items).
    2. Manager Edits the SharePoint List: Opens the SharePoint list linked to Power Apps. > Edits existing menu items (price, description, availability) or adds new ones.
    3. The catering manager refreshes the data source inside Power Apps. The updated menu is automatically reflected in the app.
    4. The manager re-publishes the app.
    5. When users access the app, they instantly see the revised menu, this ensures they always have the latest pricing and item availability and can make informed decisions based on the updated selections.
- **Workflow**:
    1. **Process Starts:** User Logs into the Catering SharePoint Team-Site: A manager with access rights enters the platform.
    2. **Navigate to Menu Management Share Point List:** The manager opens the sharepoint list to update menu items.
    3. **Edit Existing Menu or Add New Item:** The user chooses to edit an existing item or add a new dish.
    4. **Modify Item Details (Name, Price, Description, etc.):** The user updates relevant fields such as name, price, category, or dietary info.
    5. **Review Changes:** The user verifies the changes before finalizing.
    6. **Go to Power App >** Refresh the SharePoint list, review the changes, and republish the app.
    7. **Real-Time Update of the Menu:** The system updates the menu immediately after republishing.
    8. **User Gets a Message:** A New Version of the App is Coming (If already using the old version).
    9. **Users See Real-Time Updates:** Employees or customers see the modified menu in real time.
    10. **Process Ends**

![Real-Time Menu Change Workflow.png](Catering%20Menu%20Management%20Workflow/Real-Time_Menu_Change_Workflow.png)

[Real-time menu change.mp4](Catering%20Menu%20Management%20Workflow/Real-time_menu_change.mp4)

### Future Enhancements:

1. **Automate Menu Updates** (Power Automate)
    - Instead of manually refreshing the app, set up Power Automate flow to detect SharePoint changes and automatically refresh the Power Apps data source.
    - Send a notification to staff/customers about major changes (e.g., price increases or new menu additions).