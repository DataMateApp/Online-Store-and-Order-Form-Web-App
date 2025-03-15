# Online-Store-and-Order-Form-Web-App Code for Google Sheets  
**Transform your spreadsheets into powerful data management tools.**  

## About DataMateApps  
Hi, I'm **Dan Northway**—Founder and Developer of DataMateApps. Before retiring, I spent my career as a **Construction Project Manager and Superintendent**.  

At most companies I worked with, spreadsheets were the backbone of project management. Everything—timecards, pay applications, logs—was stored in countless Excel and PDF files, requiring manual tracking.  

I knew databases could streamline this process, but Excel was the standard. That’s when I had an idea:  
> *What if I could turn Excel itself into a lightweight database?*  

Using **forms and VBA**, I built a system that stored, logged, and organized data efficiently—making sorting and filtering a breeze. It became an essential tool in my workflow.  

### The Birth of DataMate  
After retiring, I revisited the concept, and a lightbulb went off:  
> *Why not make this work with any form?*  

With help from the recently released **ChatGPT**, **DataMate was born!**  

DataMate isn’t a replacement for **full-scale databases like SQL** or enterprise-level solutions. Instead, it’s designed for **small businesses and teams** that rely on spreadsheets but need a **smarter, structured way to manage data**.  

It bridges the gap between **manual spreadsheets** and **complex (often expensive) systems** that may be overkill for smaller operations.  

### Why are DataMateApps Free?  
Because **the idea matters more than the programming.**  

Technology has made development more accessible, and for me, this is both a **passion project** and a way to **keep my mind sharp**. More importantly, I see DataMate as a **legacy—one that grows and evolves with every user.**  

---
This web app is an example to how the DataMate concept can be used for front end development. This web app is a customizable online store and order form linked to Google Sheets™, pulling inventory dynamically. It displays items with images, calculates totals, and processes orders with email notifications. It also generates invoices, receipts, and packing slips. The included App Script is editable.
### Installation and Deployment  

### Step 1: Open Google Apps Script  
1. Open **Google Drive** and create a **new spreadsheet**.  
2. Click **Extensions > Apps Script**.  
3. Delete any default code in `Code.gs`.  
4. Copy & paste the provided `Code.gs`.  
5. Click **Save project to Drive**

### Step 2: Insert email Address
1. In the script editor, locate the section of the script where the email is defined.
Scroll down to line 14:
var recipient = "your-email@example.com";
Replace "your-email@example.com" with your actual email address.
Example:
var recipient = "john.doe@gmail.com"

### Step 3: Install the Inventory Template  
1. Click **Run > onInstall**.  
2. Authorize the script when prompted.
3. Open the DataMate UI and select **Setup**

### Step 4: Deploy as a Web App
Click Deploy > New Deployment.
Under Select type, choose Web app.
In the Description field, enter something like "Order Form Deployment".
Under Execute as, select Me (so the script runs with your permissions).
Under Who has access, select:
Anyone (if you want anyone to access it without signing in).
Click Deploy.
Click Authorize Access and follow the prompts to approve permissions.
Copy the Web App URL and share it with users.

### Step 5: Test the Web App
Open the Web App URL in a browser.
Fill out the form and submit it.
Check:
The Google Sheet to see if the data was recorded.
Your email inbox for a notification.   

---

- **Collaboration is welcome!** – Need collaborators to develop new templates and features. 

Have feature requests? [Email me!](mailto:datamateapp@gmail.com)  
Visit the website? [Website](https://datamateapp.github.io/)

---

## 💙 Support This Project  

DataMate is free, but if you find it useful, consider supporting development:  

[**Support DataMateApps**](https://datamateapp.github.io/Donate%205%20per%20mo.html)  

Every donation helps keep this project alive and evolving!  

---

## License  
This project is licensed under the **MIT License**. See `LICENSE.txt` for details.  

## Credits  
Developed by **Dan Northway**.  
