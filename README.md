# tag-center-automation
This tool is developed and maintained by the Trauma and Grief (TAG) Center and Lucine Center. It automates the generation and delivery of Certificate of Completion emails for clinicians who attend trainings facilitated by the TAG Center.

### 🔧 What the tool does
- Generates personalized CEU or COC certificates for participants based on attendance and workshop type.
- Sends emails from the TAG Center administrative Gmail account (`tagthcmmhpi@gmail.com`) using Google’s Gmail API.
- Updates internal Google Sheets databases to track certificate delivery and workshop credits.

This automation ensures that clinicians promptly receive documentation of their participation while reducing the administrative burden on TAG Center staff.

### 🔐 Data and Security
This tool only accesses the minimal amount of data required to send certificate emails:
- Participant name and email address
- Workshop title and date
- Credit type (CEU or COC)

Data is not stored or shared outside of our internal systems. The app is authorized via Google's secure OAuth2.0 flow, and it operates only with explicit, pre-approved access by TAG Center staff.

### 📄 Documentation
- [Privacy Policy](./privacy-policy.md)

### 📫 Contact
For any questions or concerns, please email: [tagthcmmhpi@gmail.com](mailto:tagthcmmhpi@gmail.com)

