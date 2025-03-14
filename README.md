# Med-E-Safe

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
![Landing Page](path/to/landing-page-screenshot.png)

### 2. Patient Dashboard (`file-viewer.html`)
![Patient Dashboard](path/to/patient-dashboard-screenshot.png)

### 3. Report Upload Page (`supa.html`)
![Report Upload](path/to/report-upload-screenshot.png)

### 4. Doctor Dashboard (`doctor.html`)
![Doctor Dashboard](path/to/doctor-dashboard-screenshot.png)

### 5. Supabase Backend
![Supabase Backend](path/to/supabase-backend-screenshot.png)

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
This project is licensed under the MIT License.

## Contact
For any queries or collaboration opportunities, reach out at **aliakbarkhana79@gmail.com**.

