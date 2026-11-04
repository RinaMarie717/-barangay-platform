# Barangay Information Management Platform

A modern, citizen-centric web application designed to streamline administrative workflows, document issuances, and resident record management for local government units (Barangays).

---

## 🚀 Key Modules & Capabilities

* **Resident Registry & Demographics:** Secure management of resident profiles, household mapping, and automated statistical reporting.
* **Digital Document Issuance:** Streamlined generation of Barangay Clearances, Certificates of Indigency, Residency, and Business Permits.
* **Katarungang Pambarangay Module:** Digital blotter and amicable settlement tracking for local dispute resolution.
* **Specialized Beneficiary Tracking:** Integrated workflows complying with national welfare acts for senior citizens, solo parents, and first-time jobseekers.

---

## 📋 Prerequisites

Ensure you have the following installed on your local machine:

* **Node.js** (v18.0.0 or higher recommended)
* **npm** (comes with Node.js) or `pnpm` / `yarn`

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone [https://github.com/RinaMarie717/barangay-information-management-platform.git](https://github.com/RinaMarie717/barangay-information-management-platform.git)
cd barangay-information-management-platform
```
2. Install dependencies

```bash
    npm install
```
3. Configure Environment Variables
Create a .env file in the root directory and add your Firebase credentials:

```bash
VITE_FIREBASE_API_KEY=your_api_key_here
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

4. Start the local development server

```bash
npm run dev
```
Open http://localhost:3000 in your browser to view the application.

5. Build for production

```Bash
npm run build
```

⚖️ Legal & Governance Compliance
This platform is engineered to align with key Philippine legislative frameworks governing local government units:

Republic Act No. 7160 (Local Government Code of 1991): Supports Katarungang Pambarangay conciliation records, blotter logs, and official document issuances.

Republic Act No. 11261 (First Time Jobseekers Assistance Act): Facilitates fee-exempt document processing and registry tracking for qualified first-time jobseekers.

Republic Act No. 8972 (Solo Parents' Welfare Act): Manages identification, profiling, and priority welfare tracking for solo parents.

Republic Act No. 10173 (Data Privacy Act of 2012): Implements strict security safeguards for resident personal demographic data and system access logs.

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.


```---

<ElicitationsGroup message="Next steps or additional sections you can include:">
  <Elicitation label="Add project structure tree" query="How can I add a file directory structure tree to show how the React and Firebase code is organized?"/>
  <Elicitation label="Add contributors section" query="How do I add a credits or contributors section to this README?"/>
</ElicitationsGroup>

```
