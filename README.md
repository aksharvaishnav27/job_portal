<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Job Portal README</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px;">

  <h1>💼 Job Portal – Connect Students with Jobs</h1>
  <p>A <strong>full-stack web application</strong> built to help students find jobs and allow recruiters to manage applications — all in one place.</p>

  <hr/>

  <h2>✨ What It Does</h2>

  <h3>👨‍🎓 For Students:</h3>
  <ul>
    <li>🔍 <strong>Search Jobs</strong> – Filter jobs by qualifications and eligibility.</li>
    <li>📄 <strong>Apply for Jobs</strong> – Submit applications directly through the portal.</li>
    <li>📊 <strong>Track Application</strong> – Check if applications are accepted or rejected.</li>
    <li>🧾 <strong>Update Profile</strong> – Manage personal and academic info.</li>
  </ul>

  <h3>🏢 For Recruiters:</h3>
  <ul>
    <li>🏢 <strong>Register Company</strong> – Add details and get listed.</li>
    <li>📝 <strong>Post Job Listings</strong> – Share open positions for students.</li>
    <li>📋 <strong>Manage Applicants</strong> – Accept or reject applications easily.</li>
  </ul>

  <hr/>

  <h2>🛠️ Tech Stack</h2>
  <table border="1" cellpadding="10">
    <tr>
      <th>Layer</th>
      <th>Tech Used</th>
    </tr>
    <tr>
      <td>Frontend</td>
      <td>React, Redux Toolkit, ShadCN UI, Tailwind CSS, Toaster</td>
    </tr>
    <tr>
      <td>Backend</td>
      <td>Node.js, Express.js</td>
    </tr>
    <tr>
      <td>Database</td>
      <td>MongoDB</td>
    </tr>
    <tr>
      <td>Authentication</td>
      <td>JWT (JSON Web Token)</td>
    </tr>
    <tr>
      <td>File Upload</td>
      <td>Resume Upload (PDF supported)</td>
    </tr>
    <tr>
      <td>State Management</td>
      <td>Redux Toolkit</td>
    </tr>
  </table>

  <hr/>

  <h2>🚀 Key Features</h2>
  <ul>
    <li>✅ Secure Login/Signup with JWT</li>
    <li>📎 Resume Upload for students</li>
    <li>⚙️ Clean and responsive UI (Tailwind CSS + ShadCN)</li>
    <li>📬 Real-time notifications using Toaster</li>
  </ul>

  <hr/>

  <h2>🤝 Who Can Use This?</h2>
  <ul>
    <li>🧑‍🎓 Students seeking internships or job opportunities</li>
    <li>🧑‍💼 Recruiters looking to hire fresh talent</li>
    <li>🧑‍💻 Developers or learners exploring full-stack project structure</li>
  </ul>

  <hr/>

  <h2>🧱 Folder Structure (Simplified)</h2>
  <pre>
/client   → React Frontend (Redux Toolkit, UI)
/server   → Node.js + Express Backend
  </pre>

  <hr/>

  <h2>📚 Learnings from the Project</h2>
  <ul>
    <li>How frontend and backend communicate via API</li>
    <li>Global state handling with Redux Toolkit</li>
    <li>User authentication using JWT</li>
    <li>File handling and resume upload</li>
    <li>Role-based access: Student vs Recruiter</li>
  </ul>

</body>
</html>
