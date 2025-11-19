# Technical Architecture

### Data Sources

- **SharePoint List**:
    - Catering Event Enquiry: Stores form submissions capturing event details (title, date, time, location, menu, dietary restrictions, etc.).
    - Resources: Holds all menu-related details (e.g., dish names, ingredients, special notes, unit-price).

### Connectors Used

- **SharePoint** Used to retrieve and update items in the SharePoint lists.
    
    [**Demonstration of SharePoint integration** with Power Apps](Technical%20Architecture/Demonstration%20of%20SharePoint%20integration%20with%20Power%201a43ea63525980148433ff9b6b2d419e.md)
    
    [Demonstrating how Power Apps captures menu data and stores it in SharePoint](Technical%20Architecture/Demonstrating%20how%20Power%20Apps%20captures%20menu%20data%20an%201a43ea63525980439b82c1a8a12ea056.md)
    
- **Office 365 Users** used for retrieving user information (e.g., name, email) within the Power Apps environment.

### Environment Setup

- **Power Apps Environment**: Created in the default environment provided by the university’s Microsoft 365 tenant.
- **User Permissions**:
    - Members: Submit new forms and view existing submissions. Contribute level on SharePoint lists.
    - Owners: Full control over the SharePoint lists and the Power App. Full editing rights for the Power App and administrative tasks.