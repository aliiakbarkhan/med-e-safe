# Med-E-Safe

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/12cbe8a4-f55c-4b40-85bb-d8e1405e7b84/dgf7bs9-91a4de96-bb76-4a9c-8893-f8bb759fc027.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzEyY2JlOGE0LWY1NWMtNGI0MC04NWJiLWQ4ZTE0MDVlN2I4NFwvZGdmN2JzOS05MWE0ZGU5Ni1iYjc2LTRhOWMtODg5My1mOGJiNzU5ZmMwMjcuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.6eP1xsyPRLor7OWLZwpelEwK2qLxCYAX0bjozXJL9OM" />

## Overview
Med-E-Safe is a secure and efficient web-based medical record management system designed to protect patient data while providing seamless access to medical reports. Built with **HTML, CSS, JavaScript**, and **Supabase** for backend storage and authentication, this platform enables patients to manage their reports and doctors to access necessary medical records securely.

## Features
- **Secure Authentication**: User verification via email authentication powered by Supabase.
- **Patient Dashboard**: View and manage uploaded medical reports.
- **Report Upload**: Securely upload medical reports to cloud storage.
- **Doctor Dashboard**: Access and manage patient records securely.
- **Supabase Integration**: Backend storage and authentication handled through Supabase for enhanced security.

## Project Structure
```bash
Med-E-Safe/
│── index.html        # Main landing page
│── file-viewer.html  # Patient's dashboard to view reports
│── supa.html         # Report upload page
│── doctor.html       # Doctor's dashboard
│── assets/           # CSS, images, scripts
```

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Supabase (Storage & Authentication)
- **Authentication:** Supabase email verification

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/med-e-safe.git
   ```
2. Navigate to the project folder:
   ```sh
   cd med-e-safe
   ```
3. Set up Supabase:
   - Create a [Supabase](https://supabase.com/) account.
   - Configure authentication and storage settings.
   - Obtain your Supabase **Project URL** and **API Key**.
4. Link Supabase to your project:
   - Update JavaScript files with your Supabase credentials.
5. Run the project:
   - Open `index.html` in a browser.

## Screenshots
### 1. Landing Page (`index.html`)

![Screenshot 2025-03-14 203935](https://github.com/user-attachments/assets/5a324388-74da-4b19-9c59-aa4f671daecb)


### 2. Patient Dashboard (`file-viewer.html`)

![Screenshot 2025-03-14 204025](https://github.com/user-attachments/assets/3731aac0-ea02-4e7a-a635-31a1f7725256)

### 3. Report Upload Page (`supa.html`)

![Screenshot 2025-03-14 204002](https://github.com/user-attachments/assets/4466173a-87cd-4740-a4e7-ec304d878d03)

### 4. Doctor Dashboard (`doctor.html`)

![Screenshot 2025-03-14 204052](https://github.com/user-attachments/assets/c1710f11-c2fb-4d01-a70f-cc794e27ae35)


### 5. Supabase Backend

![Screenshot 2025-03-14 204335](https://github.com/user-attachments/assets/939c66e7-d14e-483e-ae9f-d1e7cbb09acb)

## Database Information

- Supabase/Database URL: https://dasbfurobvglciwqetyx.supabase.co
- Bucket/Folder Name: files
- Database/ANON Key: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImRhc2JmdXJvYnZnbGNpd3FldHl4Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDE4NjI0NDUsImV4cCI6MjA1NzQzODQ0NX0.ESMHA5GCIRhF1Y8SSnmuXQ2bD1-A9g_i1K-Jo6p82Kw


## Security & Data Protection
- **End-to-end encryption** to ensure the confidentiality of medical records.
- **Email verification** to prevent unauthorized access.
- **Secure cloud storage** via Supabase for protected data handling.

## Future Enhancements
- Implement role-based access control for different user types.
- Introduce AI-based report analysis for better insights.
- Improve UI/UX for enhanced usability.

## Contributing
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request.

## License

https://github.com/user-attachments/assets/1b6f530c-0eb8-4c25-90c6-f26a9c64263a


## Contact
For any queries or collaboration opportunities, reach out at **aliakbarkhana79@gmail.com**.

