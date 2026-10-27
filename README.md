# sesona297.github.io

## CONTACT 
-7100, Mfuleni,Cape Town 
-Western Cape  
-0656307046 
-240773365@mycput.ac.za 

## PROFILE 
I am a passionate and dedicated third year Application Development 
student with a solid foundation in Java, File handling, GUI development, 
and database. Experienced in developing academic projects that 
involve OOP, database models, and user interface design.

## EDUCATION 
National Senior Certificate 
Mfuleni High School 
Completed:2023 
Cape Town, South Africa 
 
Diploma in Application Development 
Cape Peninsula University of 
Technology. 
Cape Town, South Africa

## KEY SKILLS 
- UX/UI wireframe (Figma) 
- Basic SQL/Databases 
- Gui Development 
- Report Writing 
- Teamwork 
- Problem Solving

## Academic Projects

### StudyGroup Finder
- Worked in a team to build an application that helps students find study groups  
- Designed and implemented a Goal Tracker to set, track, and manage goals  

### UX/UI Wireframes
- Designed low-fidelity wireframes for a mobile application (Multimedia project)  

### GUI Development
- Designed and updated graphical user interfaces using Java Swing components  

### Database Handling
- Implemented a relational database using MySQL  

## REFERENCES 
Cape Peninsula University of Technology: 
- burgerr@cput.ac.za 
- cicerot@cput.ac.za 
- Zietsmane@cput.ac.za

## Mock Interview Video
<video src="./mock interview.mp4" controls width="600"></video>

# SPS Fruit & Vegetable Coolers: Agile Team Charter
 
## 1. Team Purpose
 
SPS Fruit & Vegetable Coolers provides secure, refrigerated overnight storage and transport assistance for street vendors in the Cape Town CBD. Our purpose is to reduce produce spoilage, physical strain and stress for vendors who have no safe storage option.
 
**Team mission:** To validate and deliver a simple, affordable cold storage service that protects vendor income.
 
**Current goal:** Validate demand through the MVP flyer campaign. Success is defined as 15 to 20 of 50 vendors approached signing up with their contact details.
 
## 2. Team Members and Roles
 
- **Sesona Ntshatsha (Team Leader and Designer):** Facilitates meetings, keeps the backlog prioritized, removes blockers and leads design of flyers and branding.
- **Alakhe Sbusiso Mxakato (Researcher and Presenter):** Gathers vendor feedback, validates assumptions with data and leads presentations.
- **Noxolo Portia Ngubo (Writer, Editor and Presenter):** Produces and quality-checks written work and supports presentations.
## 3. Core Values
 
- **Respect:** We listen to every opinion and value each member's contribution.
- **Accountability:** We do what we commit to and communicate early if we cannot.
- **Transparency:** We share progress, problems and mistakes openly.
- **Customer focus:** Every decision is tested against the needs of the street vendor.
- **Continuous improvement:** We reflect regularly and adapt how we work.
## 4. Working Agreements
 
**Ways of working**
 
- We work in one-week sprints with a shared product backlog and a visible task board (To Do, In Progress, Done).
- A short stand-up is held three times a week, either in person or on WhatsApp. Each member states what was done, what is planned and any blockers.
- Sprint planning takes place at the start of each sprint and a sprint review and retrospective at the end.
**Communication**
 
- The team WhatsApp group is the main channel for daily communication, and messages are answered within 24 hours.
- Shared documents are stored in one common folder with clear version names.
**Decision making**
 
- Decisions are made by consensus. If consensus cannot be reached, the team votes and the majority decision stands.
- Customer feedback from vendors takes priority over personal preference.
**Definition of Done**
 
- A task is complete only when it has been reviewed by at least one other member, meets the assignment or business requirement, and is uploaded to the shared folder.
**Conflict resolution**
 
- Issues are raised directly and respectfully with the person concerned first.
- If unresolved, the issue is discussed with the whole team at the next meeting.
- If it remains unresolved, the matter is referred to the lecturer for guidance.
## 5. Boundaries and Constraints
 
- Work stays within the agreed target market: Cape Town CBD fruit and vegetable vendors without their own vehicle.
- Spending must stay within the estimated startup budget of R70,500, and no commitments are made without team approval.
- All work must be original, properly referenced and in line with university academic integrity rules.
- Vendor information collected during research is kept confidential and used only for the project.
- Members may not take on work that exceeds their capacity without informing the team.
## 6. Risks and Team Response
 
- **Market risk:** Vendors may not switch. We respond by testing demand early with the MVP.
- **Operational risk:** Delays or equipment failure may reduce trust. We respond by planning ahead and keeping backup options.
- **Team risk:** Missed deadlines or unequal workload. We respond by raising concerns early and reviewing workload at each retrospective.
## 7. Review of the Charter
 
The charter will be reviewed at every sprint retrospective. Changes are made only with the agreement of all members.
 
## 8. Team Agreement
 
By signing below, each member agrees to uphold this charter.
 
- Sesona Ntshatsha: ____S.Ntshatsha______ Date: _26 October 2026_________
- Alakhe Sbusiso Mxakato: __________ Date: __________
- Noxolo Portia Ngubo: __________ Date: __________

 # User Stories and Tasks: SPS Coolers
 
**Format:** As a [user], I want [feature], so that [benefit].
 
## Product Backlog
 
| # | User story | Acceptance criteria | Tasks | Priority |
|---|------------|---------------------|-------|----------|
| 1 | As a new vendor, I want to create an account with my name, trading spot, username, phone and 4-digit PIN, so that I can start using cold storage. | All fields are required.<br>The PIN is exactly 4 digits.<br>Duplicate usernames are rejected. | Build the sign-up form.<br>Add validation.<br>Save to the `profiles` table. | Must |
| 2 | As a vendor, I want to log in with my username and PIN, so that I can see my storage. | Correct details open my dashboard.<br>Wrong details show an error. | Build the login form.<br>Check credentials.<br>Handle errors. | Must |
| 3 | As a vendor, I want to see how many crates I have stored and in which unit, so that I always know what is in the cooler. | The home card shows the crate count, unit number and start date. | Design the storage card.<br>Query the active booking. | Must |
| 4 | As a vendor, I want to see the hub closing time, so that I drop off my crates before 18:00. | A highlighted notice shows the closing time on the dashboard. | Add a closing time to the hub data.<br>Build the banner. | Should |
| 5 | As a vendor, I want to access a QR code linked to my storage booking, so that the facility manager can identify my booking and direct me to my assigned storage unit. | A unique QR code is generated for a confirmed storage booking.<br>When the facility manager scans it, the system displays the booking details and assigned storage unit. | Generate a unique QR code linked to the booking.<br>Display the QR code on the vendor's dashboard.<br>Enable the facility manager to scan the QR code and retrieve the booking details. | Must |
| 6 | As a vendor, I want to modify my storage booking, so that I only pay for the space I need. | I can change my crate count and confirm the change. | Build the modify form.<br>Update the booking. | Should |
| 7 | As a vendor, I want to book transport assistance (a facility Bakkie), so that I can collect my stock from the supplier. | I can pick a date, time and location and get a confirmation. | Build the request form.<br>Save the request.<br>Show its status. | Should |
| 8 | As a vendor, I want to choose to pay for my storage fortnightly or monthly, so that I can match my payments to when I earn money. | I can select fortnightly or monthly when booking and change it later.<br>The amount due and the next due date are shown before I confirm. | Add a payment frequency option to the booking form.<br>Calculate the amount and next due date.<br>Save the choice to the booking. | Should |
 
## Screenshots
 

<img width="424" height="641" alt="Screenshot 2026-10-27 024942" src="https://github.com/user-attachments/assets/c117d5eb-173b-43eb-be84-86b29148f8ea" />
<img width="432" height="641" alt="Screenshot 2026-10-27 025025" src="https://github.com/user-attachments/assets/954e08f5-bf46-4eb3-a834-253d1d3ae910" />
<img width="426" height="645" alt="Screenshot 2026-10-27 025046" src="https://github.com/user-attachments/assets/7f23058a-9e17-4aa8-b92f-787052ecea15" />
<img width="432" height="638" alt="Screenshot 2026-10-27 025107" src="https://github.com/user-attachments/assets/5996e3fe-8df8-4410-951d-a97040752dcf" />
<img width="435" height="594" alt="Screenshot 2026-10-27 034427" src="https://github.com/user-attachments/assets/8cfc723c-a922-4e57-b642-26e02c236f1a" />
<img width="426" height="641" alt="Screenshot 2026-10-27 034901" src="https://github.com/user-attachments/assets/c8da0203-7145-414d-aef0-50b7f66c7f63" />






## Reflection
 
**Situation:** SPS Coolers is a smart cold storage application designed to help street vendors manage their storage bookings and access the facility.
 
**Task:** My responsibility was to develop user stories and break them down into manageable tasks that the team could use for planning and development.
 
**Action:** I wrote user stories from the vendor's perspective using the "As a user, I want, so that" format. I added acceptance criteria to define how each feature should work and applied MoSCoW prioritisation to distinguish essential features from additional ones. I then broke the user stories into smaller, manageable tasks.
 
**Result:** This process helped organise the required features, clarify what each story needed to achieve, and support the creation of the Product Backlog and Sprint 1 backlog. I learned the importance of prioritising requirements and defining clear acceptance criteria before development begins.
 
