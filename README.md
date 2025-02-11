## Assignment 1: Getting Organized

### Student Information
**Name:** Sheetal Rana  
**Student ID:** 8994226  

---

## Pet Daycare Client – Problem Statement
As per scenario presented in the Assignment There are three types of Frustration based on the type of user or client.

1. **Owner's Frustrations:**
   - Onboarding new employees takes at least 3 months.

2. **Employee's Frustrations:**
   - The process of onboarding a new client is complicated.
   - They has their own different method of processing incoming clients, leading to inconsistency

3. **Customer's Frustrations:**
   - The onboarding flow is difficult to follow.


## Requirements Gathering  

Prepare the following questions to clarify the true intent of the client to gather necessary information and requirement  

### Questions for the Owner:
- Can you walk me through the current process for new employee onboarding?
- What are the specific pain points or bottlenecks in the existing process?
- How are you currently providing training to new employees?

### Questions for Employees:
- Can you describe the current client onboarding process?
- What are the most common challenges faced by you and clients during onboarding?
- Are there any existing materials (forms, documents, etc.) used for client onboarding?

### Customer Experience Questions (For Both Owner & Employees):
- What do you think? What are the major challenges faced by customers?
- What feedback have you received from customers regarding the onboarding process?
- Are there specific features or improvements customers have requested?


### Follow-Up Clarification Questions:
Based on the initial information, be prepared to ask follow-up questions such as:  
- How do you identify the success of the onboarding processes for both employees and clients?
- How do customers interact with the onboarding process e.g. online forms, phone calls, email or in-person?
- Are there any regulatory or legal compliance required that need to be consider?
- Would you be open to implementing an online system for standardizing onboarding?

**Prepare Question Air for Customer of Pet Daycare to understand their requirements :**
- How would you describe your experience with the current onboarding process?
- What parts of the onboarding process did you find confusing?
- Did you receive clear instructions on what information or documents were required?
- Did you receive timely updates or reminders about your pet’s onboarding status?
- Was the daycare staff helpful in guiding you through the process?
- Would you like a digital onboarding guide to help onboarding questions?
- Would you prefer to upload vaccination records and other required documents online?
- On a scale of 1-10, how satisfied were you with the onboarding process?


## Assumption :
- The current onboarding processes are not standardized and it should be standardized and simplified for both employees and customers.
- They need efficient and consistent onboarding processes to be followed be everyone.
- Employees should have a clear, unified process for onboarding new clients.
- Customers should have an easy-to-follow onboarding process.
- The owners want to reduce the employee onboarding time from three months to a more manageable duration by using the system that onboard new employees detail, providing training, tracking their progress to get in the roll.
- The solution should be user-friendly and not require extensive training for staff.


## Client Requirements :
1.	As the owner, I want a standardized employee onboarding process so that new hires can be trained efficiently and reduce onboarding time.
2.	As the owner, I want a digital onboarding system so that employee training and client onboarding can be managed more efficiently.
3.	As the owner, I want a system that tracks employee onboarding progress so that I can ensure they are meeting training milestones.
4.	As an employee, I want a clear, structured process for onboarding clients so that I do not have to rely on my own method.
5.	As an employee, I want a easy go through to input and track client details so that I can reduce paperwork and onboarding time.
6.	As a customer, I want an easy-to-follow onboarding process so that I do not get confused while registering my pet.
7.	As a customer, I want clear instructions on what documents are required so that I can prepare everything in advance.
8.	As a customer, I want to receive timely updates about my pet’s onboarding status so that I am informed of any pending steps.


## Based on the Client requirement how the system will look like
The Pet Daycare Onboarding System will make the onboarding process easy and fast for both new employees and pet owners. Instead of using paperwork and different methods, everything will be done online in a simple and organized way.

For new employees they will fill out an online form with their personal details, job role, and required documents like ID and certifications. The system will check for missing information and send reminders if anything is incomplete. Once submitted managers can review and approve the application. After approval, employees will get access to training modules and step-by-step guides to help them learn their job quickly. A dashboard will track their progress, ensuring they complete all onboarding steps on time.

For customers, the system will allow them to register their pets online, enter important details, and upload vaccination records before their first visit. Employees will follow a standard process to check and approve the pet’s information. If any details are missing, the system will send automatic reminders to the pet owner. The onboarding status will be updated in real time, so employees and customers always know what steps are left.
This system will save time, reduce errors, and provide a smooth experience for both employees and customers. Everything will be in one place, making onboarding faster, easier, and more consistent.


## Technical Requirements for Developer Team  

**Frontend Development:**  
1.	Create the user interface and dashboards that the users will interact with.
2.	Use React.js or Angular to create online forms for employee and pet owner sign-up.
3.	Create webpage using HTML5, CSS3, and frameworks like Bootstrap to make it look good.  

**Backend Development:**  

4.	Choose either Node.js with Express.js or Python with Django/Flask to set up the server.
5.	Build RESTful APIs to handle form submissions, retrieving data, and updating data in real-time.
6.	Implement a login system using JWT to make sure users can securely sign in.  

**Database Management:**  

7.	Pick a database like MongoDB, MySQL to store and organize the data.  

**File Storage:**  

9.	Set up AWS or Google Cloud Storage to store and manage files like documents or images that users upload.
10.	Employee application on platforms like AWS or Google Cloud Platform.  

**Automated Reminders and Notifications:**  

11.	Use SendGrid to send automatic SMS or email notifications.
12.	Use cron jobs to schedule automatic reminders and tasks.  

**Progress Tracking and Dashboards:**  

13.	Use Chart.js or D3.js to create interactive charts that show progress.
14.	Build dashboards for the admin to track the progress of employee and pet owner onboarding, using React Admin.
15.	to package your application so it runs smoothly in any environment.  

**Version Control:**  

16.	Use Git to manage changes to your code.
17.	Store your code on platforms like GitHub for version management and collaboration.

Dogtopia. (n.d.). Dog boarding. Dogtopia. https://www.dogtopia.com/kitchener/dog-boarding/

FedDev Ontario. (n.d.). How to start a pet care business in Ontario. Southern Ontario Fund for Investment in Innovation. https://sbs-spe.feddevontario.canada.ca/en/how-start-pet-care-business-ontario

PetSmart. (n.d.). Day camp requirements. PetSmart. https://services.petsmart.ca/content/daycamp-requirements

Direct Animal. (n.d.). What to bring to doggy daycare. Direct Animal.  https://www.directanimal.com/pet-daycare-resources/what-to-bring-to-doggy-daycare/

Universal Class. (n.d.). The process of hiring the right employees for your dog daycare business. Universal Class. https://www.universalclass.com/articles/business/the-process-of-hiring-the-right-employees-for-your-dog-daycare-business.htm

Microsoft. (n.d.). Copilot. Microsoft. https://copilot.cloud.microsoft/?fromcode=cmc&redirectid=324BF8029B384E2B91B0B0ECD36A67D4&auth=2

Markdown Guide. (n.d.). Basic syntax. Markdown Guide. Retrieved February 10, 2025, from https://www.markdownguide.org/basic-syntax/

Prompt For new employees, they will fill out an online... | Try in Microsoft 365 Copilot



