# Maytech ↔ AKQA Context Pack (Curated Summary)

> Use this document as **context** for code generation and workflow scaffolding. Keep it in your repo under `docs/org-context/`.

## 1) Relationship & Responsibilities
- **Maytech** (Sri Lanka partner): Recruitment & onboarding, local HR/admin & payroll, office facilities & hardware, device management/IT support, policy enforcement, incident handling.
- **AKQA**: Project delivery ownership (scope, timelines, quality), tasking & mentorship, KRAs/KPIs and performance reviews, procurement of job‑specific software. Shared IT support as needed.
- **Escalation**: Director of Engineering & Technology (Colombo) → James Freeman (Maytech).

## 2) Work Patterns & Policies
- **Hybrid model**: Tue & Thu mandatory office; Wed encouraged; other days at employee discretion. Acknowledgment via BetterHR.
- **Policies include**: Code of Conduct, Dress Code, Attendance & Punctuality, Hybrid Work, Payroll/Benefits/Leave, Safety & Security, Incident/Issue Management, Social Media, Privacy/Confidentiality, IP.
- **Leave highlights**:
  - *Paternity*: 3 paid days; confirmed employees; to be taken within 30 days of live birth; apply ~12 weeks before due date.
  - *Maternity*: 84 days (1st/2nd child), 42 days (3rd+); confirmed employees; excludes weekly/public/Poya holidays; apply ~12 weeks before due date.

## 3) Forms & Internal Workflows
- **Hardware Requests**: Justification (purpose/impact/benefit) → Line manager approval → Standards/budget checks.
- **IT Support**: Submit request; ticket triage & escalation flow handled by Maytech IT.
- **Incident Reporting**: Online form for building/maintenance issues, loss/theft, safety hazards, injuries. All incidents are investigated.
- **Expense Reimbursement**: Submit via form; supervisor + finance review; attach receipts.
- (Form URLs are managed internally; wire via ENV later).

## 4) Security, Facilities & Building Access
- **Visitor & Access**: Pre‑approve visitors 24h prior; sign‑in with ID & visitor badge; accompany visitors.
- **Asset usage**: Business use only; avoid unapproved third‑party/personal storage devices; report loss/damage promptly; audits occur periodically.
- **Networks**: BYOD uses `MayTech_BOYD` network.
- **Orion City requirement**: Wear Maytech lanyard/ID in all shared areas while commuting within the campus and using common facilities; remove after reaching the private office.

## 5) Finance & Payroll (High-level)
- Payroll run typically around the 6–9th each month.
- RCTI and AUD payments to nominated dollar accounts when applicable.
- Daily check‑in/out via BetterHR.

## 6) Implementation Notes for Apps
- **Roles**: `employee`, `manager`, `hr_admin` (Maytech), `delivery_lead` (AKQA).
- **Modules to scaffold**:
  - *Policy Center* with acknowledgment tracking (Hybrid Work emphasis).
  - *Leave* (maternity/paternity rules embedded; validations on eligibility & notice period).
  - *IT Support* (ticket submit + status).
  - *Incident Reporting* (typed categories, severity, SLA stubs).
  - *Expenses* (line items, receipt upload placeholder, approval flow).
- **Compliance reminders**: client confidentiality banners on pages that deal with data; prompt to use approved channels (email/Slack) for client comms.
- **Orion City lanyard reminder**: show on Tue/Thu (mandatory office) and optional Wed.

---

# Full Text Extracts (from PDFs)
(For reference; keep below the curated summary.)


---

# Source: AKQA-Maytech-Refresher.pdf

RE FRESHER  SESS IO N
Insight into roles and responsibilities and best practices when 
working with clients.

MAYTECH  & AKQ A  PAR TNE RS HIP
Maytech serves as AKQA's local partner in Sri Lanka, supporting its vision to 
establish and expand a Center of Excellence in the country.
Maytech  plays  a crucial  role in talent  acquisition  and onboarding,  sourcing  and screening  qualified  candidates,  
conducting  initial  interviews  and assessments,  and facilitating  onboarding  process  for new hires . Maytech  also 
ensures  a conducive  work  environment  by providing  necessary  infrastructure  and fostering  a supportive  work  
culture,  including  the setting  of various  policies  and frameworks .
AKQA  is responsible  for project  management  and delivery,  defining  project  scope,  timelines,  and deliverables . 
They  provide  technical  guidance  and mentorship  to the Sri Lankan  team,  ensuring  quality  control  and project  
success . AKQA  focuses  on technical  skill development  and training,  developing  and delivering  training  programs  
to upskill  the Sri Lankan  team  and providing  opportunities  for professional  development  and career  growth .  


AN SW ER S  TO COM MO N Q UES TIO NS
Salary & Payments
Payroll is processed between 6th and 9th of each month. 
Funds are credited into your nominated dollar account in AUD. We will 
provide you with a recipient created tax invoice (RCTI) to meet your 
compliance requirements. What is the leave request process?
1. You need to gain approval from your AKQA direct report before 
applying for leave.
2. Once granted, please apply via BetterHR  and state that you have prior 
approval from your line manager.
What if I have a HR related question?
For any HR -related inquiries, including benefits, leave entitlements, and 
policies, please reach out to the Maytech HR Manager, who will be your 
primary point of contact .Whom should I contact regarding general work -related matters ?
Your primary point of contact for work -related queries, concerns, and 
suggestions is the Director of Engineering and Technology . They will serve 
as your main resource for addressing or escalating any issues related to 
your tasks. If the outcome is unsatisfactory , you may escalate the matter 
to James Freeman, the Managing Partner of Maytech Holdings Do I need to check in and out daily of BetterHR ?
Yes, regardless whether you are in the office of remote, you are required 
to check in/out via the BetterHR  application.

PO LICI ES  & PR OCED U RES
POLICIES
• CODE OF CONDUCT
• DRESS CODE
• ATTENDANCE AND PUNCTUALITY
• HYBRID WORK POLICIES
It's important to understand the policies and procedures that guide our 
operations. They ensure a fair and consistent work environment for everyone.
COMPENSATION & BENEFITS
• PAYROLL INFORMATION
• BENEFITS OVERVIEW
• LEAVE POLICIES
• FEEDBACK AND REVIEWS
WORKPLACE INFORMA TION
• IT AND EQUIPMENT
• SAFETY AND SECURITY
• INCIDENT AND ISSUE MANAGEMENTGENERAL POLICIES
• SOCIAL MEDIA POLICY
• PRIVACY AND CONFIDENTIALITY
• INTELLECTUAL PROPERTY


HYB RID WOR K POL ICY
WHAT ARE THE REQUIREMENTS?
• 2 X DAYS A WEEK IN THE OFFICE
• 1 X DAY ENCOURAGED IN THE OFFICE
• REMAINDER EMPLOYEE'S DISCRETION
WHAT ARE THE REQUIRED OFFICE DAYS
• TUESDAY 
• THURSDAY
• WEDNESDAY – ENCOURAGED DAY
NOTES
• MA YTECH  SETS THE POLICY
• REQUIREMENT OF EMPLOYMENT IS 2 X DAYS A WEEK IN 
THE OFFICE
• REVISED POLICY WILL NEED TO BE ACKNOWLEDGED BY 
TEAM MEMBERS IN BETTERHR

W HO  D OES  W HAT
General Responsibilities
Function Responsibility
Physical hardware and peripherals Maytech
Office 365 and HRM Applications Maytech
VPN setup & workbench setup AKQA
IT Support MA YTECH & AKQA
Payroll MA YTECH
Incident Management MA YTECH
HR MA YTECHCore Responsibilities
Function Responsibility
Setting and managing KRA and KPI AKQA
Project & task assignment and guidance AKQA
Job specific software procurement and setup AKQA
Role based policies and mandates MA YTECH & AKQA
Performance reviews AKQA
Learning & Development MAYTECH & AKQA
Culture and Engagement MA YTECH

EM PLOY EE S U PPOR T & W ELL BEIN G
"At Maytech we prioritize the health and wellbeing of our employees because we understand 
that their success is integral to our collective success. By fostering a supportive environment 
that values physical, mental, and emotional wellness, we not only enhance productivity but 
also cultivate a culture where everyone can thrive.
We embrace and promote employee wellbeing through carefully curated programs that cater 
to diverse needs and interests. Whether it's wellness workshops, mindfulness sessions, fitness 
classes, or comprehensive health benefits, we aim to provide resources that empower our 
team to lead balanced and fulfilling lives.
Investing in our employees' health isn't just a commitment; it's a cornerstone of our 
organizational philosophy . Together, we build a stronger, happier, and more resilient workforce, 
driving us toward shared success and a brighter future."
EMPLOYEE SUPPORT
• EMPLOYEE ASSISTANCE PROGRAMS
• GRIEVANCE MANAGEMENT
• HARASSMENT AND BULLYINGEMPLOYEE WELLBEING
• HEALTH INSURANCE
• TEAM BONDING EVENTS
• REWARD PROGRAMS


INTEREACTING & IN THE 
WORKPLACE


CL IEN T CON FI DEN TIAL ITY  - FOU N DATIO N S
Information Sensitivity
•All client information, regardless of format (documents, emails, 
conversations), is considered confidential unless explicitly designated 
otherwise.
•Examples include: client financial data, strategic plans, customer lists, 
internal client communications, personal matters, intellectual 
property, codebase repositories. Data Security
•Handle all client data, both physical and electronic, with the utmost 
care and security.
•Utilise  company -issued devices and adhere to all data security 
protocols.
As you've all signed Non -Disclosure Agreements (NDAs) with 
Maytech, it's crucial to remember that these agreements 
extend to all client interactions. 

CON FID EN TIAL ITY IN  PR ACTICE
Communication Channels
•Use appropriate communication channels for client interactions, such 
as company -approved email and secure messaging platforms (Slack)
•Avoid discussing confidential information in public areas or on 
personal devices
•Be Mindful of the information shared on client internal 
communication platforms (e.g. Slack, T eams)Data Storage
• Store all client data securely on company servers or designation 
secure locations.
• Do not store sensitive information on personal devices or cloud 
storage accounts
• Follow proper file -naming and storage conventions to ensure data 
organisation  and security
Meetings
• Maintain confidentiality during all client meetings, both in -person 
and virtual.
• Avoid discussing sensitive information in hallways or break rooms. 
• Be mindful who is present in meetings rooms, or common office 
areas. Simply: Let's keep client confidences between us

M AIN TAIN IN G NE UTR AL ITY AN D PRO FES S ION AL IS M
LET'S DO A U -TURN FROM THESE:
•Avoid getting drawn into office gossip, rumours , or internal debates 
that don't directly impact your work. 
•Stay out of arguments or disagreements between client and 
colleagues
•Avoid taking sides in internal conflicts or expressing strong public 
opinions on internal matters 
•Do not participate in internal client surveys, petitions or other internal 
processes unless specifically directed by Sri Lankan Human Resources 
or the Director of Technology & Engineering. LET'S FOCUS ON THESE:
• Maintaining a neutral and professional stance, even when faces with 
challenging situations. 
• If you observe any conflicts, focus on de -escalation and maintaining 
a professional environment
• Always communicate with colleagues respectfully and 
professionally, regardless of your personal opinions 
• Remember that your actions and words reflect on both you an 
Maytech. Let's always maintain the highest level of professionalism.
We're here to navigate the workplace with you!
• Maintain confidentiality during all client meetings, both in -person 
and virtual.
• Avoid discussing sensitive information in hallways or break rooms. 
• Be mindful who is present in meetings rooms, or common office 
areas. Deliver excellence, avoid distractions!

M AIN TAIN IN G A CON FID EN T & S U CCES S FU L  CAR EER
We are linked!
We understand that navigating client engagements can sometimes 
present challenges. By adhering to these guidelines, you not only 
protect our clients and our company's reputation, but you also 
safeguard your own career. Maintaining the highest levels of 
professionalism and confidentiality demonstrates your integrity and 
builds trust with both clients and colleagues. This enhances your 
reputation within our company and opens doors to future 
opportunities for growth and advancement.What's the upside?
• Stronger Client Relationships:  Demonstrating professionalism and 
confidentiality strengthens our relationships with clients, leading to 
increased business opportunities and long -term success.
• Enhanced Professional Reputation:  Adhering to these guidelines 
enhances your professional reputation within the company and 
within the industry.
• Increased Career Opportunities:  A strong track record of 
professionalism and ethical conduct opens doors to career 
advancement and new opportunities.
• Reduced Risk:  By following these guidelines, you minimise  the risk 
of disciplinary action, legal issues, and damage to your professional 
reputation
What's the otherside  of the coin?
• While we prioritise  a positive and supportive work environment, it's important to remember that your actions have 
consequences. These can include disciplinary action, up to and including termination of employment. 

QUESTIONS?


---

# Source: AKQA-Maytech-Refresher#2.pdf

RE FRESHER  SESS IO N # 2
Digging deeper into how we operate

IN S IG HT – AKQ A  & MAY TECH PAR TN ERS HIP
Staff Salary Seat Fee10% 
Margin of 
Staff SalaryChargeable 
Cost AKQAPricing Formula:What is the Seat Fee?
The Seat Fee is an approved cost by AKQA which covers the 
following operations costs:
•Staff Laptop
•Peripherals: Monitors, Headsets, Wireless Mouse etc.
•Office:  Floor Space, Electricity, Water, Rent , Cleaning
•Perishables: T ea & Coffee, Water, Office Snacks, Office Lunch 
Vouchers 
•IT Software: HR Software, Office365 Subscription, Device 
Management, IT Support
•Human Resourcing & Administration, Including Payroll Fees
•Contribution to Employee Incentives: Christmas Party, Events, 
Awards etc.
 Mutual Alignment
•Cost Optimisation : Partnership with Maytech leverages our lower operating 
cost base. As previously mentioned, this is not AKQA’s first attempt in the Sri 
Lankan market
•Long -Term Sustainability:  Maintaining a low corporate cost structure is crucial 
for both AKQA’s & Maytech success.
•Employee Investment:  Reduced corporate costs enable better alignment for 
enhanced employee remuneration.
Why are we breaking this down?

PO LICI ES  & PR OCED U RES
POLICIES
We’re simplifying the number of polices! We’ll notify via Group Chat once finalied .
• LEAVE & ATTENDANCE 
• CODE OF CONDUCT
• GENERAL SECURITY
• HYBRID WORK 
• DISCIPLINE & TERMINATION
• GRIEVANCE HANDLING
• OVERTIME
• RESIGNATION
• CLOTHING & ACCESSORIES
Step 1: Access Learning 
Library from Home Screen
Step 2: Open, View and 
Acknowledge each policy 

WO R K FLOWS
Hardware Request
New hardware requests are submitted via this 
form FORM . Requests must include a clear 
justification outlining the purpose of the 
hardware, its impact on work or team 
performance, and the resulting benefits.  Line 
Manager approval is required before the request 
is forwarded to Management or AKQA for review 
and processing. Hardware requests are fulfilled 
subject to company standards and budget.
IT Support
For Maytech IT -related issues, please submit a 
request via FORM . From here a member of our 
team will process and escalate the matter if 
required. 
Refer to next slide of IT support inclusionsIncident Response
Prompt reporting of all workplace incidents is 
required . Use the designated online FORM .  
Common reportable incidents include 
building/maintenance issues, theft/loss, physical 
incidents (injuries, falls, etc.), and safety hazards.  
The incident report form provides instructions 
and required information. All incidents will be 
investigated.Expense Reimbursement
Expense Claims are submitted via FORM . All 
Expense Claims will be revered and processed by 
finance in addition to your immediate supervision 
where applicable.
Note: We will send Form links Via 
Email and share presentation

POLICIES 


L EAV E & ATTE ND AN CE – EV EN T BAS ED
Paid Paternity:
•3 x days of Paid Leave
•Eligibility: Only available for Confirmed Employees
•Paternity Leave must be taken within 30 days of the child's birth. 
•Paternity leave is granted solely for the purpose of supporting the 
mother and newborn child immediately following a birth and is 
available only in the event of a live birth. It cannot be used for any 
other purpose, nor can any unused portion be carried forward, 
accumulated, or exchanged for other benefits or compensation. 
•Application to be made 12 weeks prior to the excepted date.Paid Maternity Leave:
•First and Second Child:  84 days of paid leave (14 days before 
confinement and 70 days after, or mutually agreed with employer).
•Third and Subsequent Child:  42 days of paid leave (14 days before 
confinement and 28 days after, or mutually agreed with employer).
•Eligibility: Only available for Confirmed Employees
•Maternity leave is exclusive of weekly holidays, public holidays, and 
Poya holidays.
•Maternity leave is granted solely for the purpose of childbirth and is 
available only in the event of a live birth. It cannot be used for any 
other purpose, nor can any unused portion be carried forward, 
accumulated, or exchanged for other benefits or compensation. 
•Application to be made 12 weeks prior to the excepted date

G EN ER AL S ECU R ITY
Visitors & Guests, Conduct:
•Visitors must sign in upon arrival; by providing a valid ID with the name 
of the employee they are visiting and wear a visitor badge visibly whilst 
on company premises.  All visitors will be escorted by their host or a 
designated employee.  
•Pre-approval: Notify HR or Administration at least 24 hours in advance, 
providing visitor details and purpose. 
•Short Notice Visits: Require immediate approval from the department 
head and notification to security. 
•Common Sense when working with client information;
•Not leaving sensitive information on whiteboards
•Be cautions even with approved contractors are in the office 
spaces, both with company assets & information 
Note: Fingerprint door access control system on order due April / May. Asset Common Sense
•Do not download any 3rd party applications that are not relevant to 
your core job. e.g. torrents, video streaming applications etc. 
•To refrain from the use of Personal Memory storage devices (USB 
Drives, External Hard Drives) without prior approval of the 
management/IT Department. 
•Promptly report any loss, damage, or suspected unauthorized use of 
Company assets or data breaches to the IT department or designated 
asset manager. 
•Maytech will conduct periodic audits to verify the accuracy of the asset 
register and ensure compliance with this policy.
•Purpose: Company assets, including but not limited to computers, 
laptops, servers, mobile devices, software licenses, peripherals, and 
external drives. must be used solely for business purposes and in 
accordance with company policies and procedures. 
•To refrain from using Personal devices within the work premises 
without the prior approval of the Management/IT Department.
•Personal Phones must use MayTech_BOYD  network connection

O RI ON  CI TY SECU R ITY R EQ U IR EME NTS
When to Wear Your Lanyard:
Your Maytech ID, and Maytech lanyard must be visibly 
worn in the following situations:
• Commuting To Work: From the moment you 
enter the building complex or grounds until you 
reach your designated office space. This includes 
common areas like lobbies, elevators, and 
hallways.
• Commuting From Work: From the time you leave 
your office space until you exit the building 
complex or grounds. Again, this includes all 
common areas.
• On-Site Facilities: Whenever you are utilising  any 
facilities within the building complex, including 
but not limited to: restrooms, cafeterias, break 
rooms, and other shared spaces.Lanyard Removal:
•Once you have arrived at the office you may 
remove your lanyard.
Why?
•This is a security requirement mandated by Orion 
City. It is implemented to help identify authorised  
personnel on the grounds, ensuring the safety and 
security of all staff, visitors, and the building itself.
•This is crucial for compliance with building 
regulations and maintaining a controlled access 
environment.
•Orion City have been pressuring us for a why to 
adhere to their policies. 


QUESTIONS?