# CST-Training
CST Training 

**CST Training**  - User Stories

User Stories

### **Lead Capture & Nurturing**

As a prospective student, 
I want to receive relevant course information 
so that I can choose the best training program for my needs.

As a marketing manager, 
I want to automatically capture leads from website forms 
so that I can follow up with potential students promptly.

### **Email Marketing Campaigns**

As a marketing manager, 
I want to create segmented email lists based on user interests 
so that I can send targeted course promotions.

As a prospective student, 
I want to receive email reminders about upcoming courses 
so that I don’t miss enrollment deadlines.

### **Customer Journey Mapping**

As a marketing manager, 
I want to visualize the customer journey 
so that I can optimize touchpoints and improve conversion rates.

As a prospective student, 
I want a seamless experience from initial inquiry to course enrollment 
so that I feel confident in my choice.

### **Course Enrollment Follow-up**

As a course coordinator, 
I want automated follow-up emails post-enrollment 
so that students receive necessary information before the course starts.

As a new student, 
I want to get timely updates and preparatory materials 
so that I am ready for my training.

### **Feedback Collection**

As a course coordinator, 
I want to send automated feedback surveys after course completion 
so that I can gather student opinions and improve course offerings.

As a student, 
I want to easily provide feedback on the training I received 
so that my input can help improve future courses.

### **Sales Pipeline Management**

As a sales manager, 
I want to track leads and manage the sales pipeline in HubSpot 
so that I can forecast sales and manage resources efficiently.

As a sales representative, 
I want to receive notifications for follow-up tasks
so that I can ensure timely communication with prospects.

### **Automated Reporting**

As a marketing manager, 
I want automated reports on campaign performance 
so that I can quickly assess the effectiveness of marketing efforts.

As a course coordinator, 
I want regular updates on enrollment numbers 
so that I can manage class sizes and resources.



* Contact-based workflows:

These workflows automate actions based on your contacts' behavior, allowing you to personalize communications. 
For example, you can send automated follow-ups to contacts who haven't opened an email in 30 days, 
enroll new subscribers in onboarding email sequences, and add contacts to segments based on their preferences. 

* Deal-based workflows:

Trigger actions like Slack notifications or follow-up tasks when deal properties are updated. 
This provides real-time visibility into deal milestones and changes, ensuring timely follow-up. 

* Company-based workflows:

Automate actions based on company records, such as sending annual review requests or triggering 
specific communications based on company size or industry. 

* Ticket-based workflows:

Help customer service teams manage issues seamlessly by updating priority, assignment, 
and status as issues move from open to closed. 

* Quote-based workflows: 

Trigger notifications at specific milestones, 
like 5 days before the expiration date, and automate sending discount approvals to ensure 
proper oversight of pricing. 

* Third-party app workflows: 

Tools like Luru can extend beyond the native capabilities of 
HubSpot to create multi-step workflows that integrate with other applications. 


### User Story 1

As a marketing manager at CST Training,<br>
I want to automatically send personalized emails to potential<br>
students based on their course interests and previous website interactions,<br>
So that I can increase course enrollment and engagement.<br>

### User Story 2

As a course advisor at CST Training,<br>
I want to receive automated notifications when a potential student submits an inquiry form,<br>
So that I can quickly follow up and provide personalized guidance.<br>

### User Story 3

**As** a student at CST Training,<br>
**I** want to receive automated reminders for upcoming courses and deadlines,<br>
**So** that I can stay organized and on track with my training.<br>

### User Story 4

**As** a training manager at CST Training,<br>
**I** want to automatically track course completion and performance data,<br>
**So** that I can assess student progress and identify areas for improvement.<br>

### User Story 5

**As** a marketing manager at CST Training,<br>
**I** want to automate the creation of lead nurturing campaigns,<br>
**So** that I can build relationships with potential students and<br>
guide them through the enrollment process.<br>



**Workflow Name**: Welcome Email Sequence<br>
<br>
**Purpose**: To welcome new leads to CST Training and provide them with valuable information about the services offered.
<br>
**Trigger**: New Contact is Created
<br>
**Workflow Steps**:
<br>
**Delay**: Wait for 1 hour after the contact is created. This allows time for the contact information to be captured.
<br>
**Email**: Send the first email in the sequence.
<br>
**Subject**: Welcome to CST Training!
<br>
**Body**: A warm welcome message, introducing CST Training's services and value proposition.
<br>
**Personalization**: Use contact information (e.g., first name) to personalize the message.
<br>
**Call to action**: Encourage the contact to visit the website for more information or schedule a consultation.
<br>
**Delay**: Wait for 3 days after the first email is sent.
<br>
**Email**: Send the second email in the sequence.
<br>
**Subject**: Learn More About Our [Course Category] Programs
<br>
**Body**: Highlight relevant courses or training programs based on the contact's interests (if available).
<br>
**Personalization**: Mention specific courses or programs based on the contact's previous website interactions.
<br>
Call to action: Encourage the contact to download a brochure or request a personalized course recommendation.
<br>
**Delay**: Wait for 5 days after the second email is sent.
<br>
**Email:** Send the final email in the sequence.
<br>
Subject: Don't Miss Our Upcoming [Event/Webinar/Workshop]
<br>
**Body**: Promote an upcoming event or educational resource that aligns with the contact's interests.
<br>
**Call to action**: Encourage the contact to register for the event or access the resource.