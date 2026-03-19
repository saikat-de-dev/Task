# Task 2: HTML

Laundry wallah / Laundry Mart, a premier laundry service, is enhancing its online presence through a HTML webpage. The HTML code serves as a foundation for a user-friendly and visually appealing site. Web Page is about creating a seamless digital experience, showcasing services, pricing, and easy navigation.

## 🏗️ Structure of the Webpage

The webpage is divided into the following main sections:

### 1. Header
 
* Containts the main title:
  * _"Welcome to Laundry Wallah / Laundry Mart"_
* Includes a detailed description of the laundry service highlighting:
  * Convenience
  * Affordability
  * Quality service
  * Doorstep pickup and delivery

### 2. Main Content

🖼️ **Image**

* Displays a laundry-related image.
* Attributes used:
    * src - Image URL
    * alt - Accessibility text
    * title - Tooltip text
    * height and width - Image size

📝 **Services section**(#services)

* Lists all services offered:
    * Washing and Drying
    * Ironing and Folding
    * Dry Cleaning
    * Stain Removal
    * Express Services
    * Special Garment Care
* Implemented using:
    ```html
    * <section>
    * <ul> (unordered list)
    * <li> (list items)

💸 **Pricing Section**(#pricing)

* Displays a price list in a table format.
* Table includes:
    * Service names
    * Corresponding prices
* HTML elements used:
    ```html
    * <table>
    * <tr> (table rows)
    * <th> (table headers)
    * <td> (table data)
    * <thead> (heading of the table)
    * <tbody> (body of the table)

📋 **Booking Section**(#booking)

* Provides a form for users to book services.
* Input fields:
    * Name (text)
    * Email (email)
    * Phone (tel)
* Features:
    * All fields are required
    * Submit button for form submission
* HTML elements used:
    ```html
    * <form>
    * <label>
    * <input>

### 3. Footer

* Contains contact information.
* Includes a clickable email link by using:
```html
<a href="mailto:info@laundrymart.com">
