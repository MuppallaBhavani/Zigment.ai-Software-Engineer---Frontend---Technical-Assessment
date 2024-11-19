# Zigment.ai-Software-Engineer---Frontend---Technical-Assessment


    <h1>Dynamic Form Generator</h1>
    <p>
        A web application to dynamically generate forms based on a JSON schema. 
        Edit the JSON, preview the form, and submit data in real-time.
    </p>

    <h2>🚀 Live Demo</h2>
    <p>Access the live app: <a href="#">Dynamic Form Generator</a></p>

    <h2>📦 Features</h2>
    <ul>
        <li>Split-screen layout: JSON editor and real-time form preview.</li>
        <li>Supports text, email, select, radio, and textarea fields.</li>
        <li>Validation for required fields and custom patterns.</li>
        <li>Responsive design with mobile support.</li>
        <li>Dark mode toggle (bonus).</li>
        <li>Download form submissions as JSON (bonus).</li>
    </ul>

   

    <h2>📋 Example JSON Schemas</h2>
    <h3>Simple Form</h3>
    <pre><code>
{
  "formTitle": "Contact Form",
  "formDescription": "Fill out your details.",
  "fields": [
    {
      "id": "name",
      "type": "text",
      "label": "Name",
      "required": true,
      "placeholder": "Enter your name"
    },
    {
      "id": "email",
      "type": "email",
      "label": "Email",
      "required": true,
      "placeholder": "you@example.com",
      "validation": {
        "pattern": "^[^\\s@]+@[^\\s@]+\\.[^\\s@]+$",
        "message": "Please enter a valid email address"
      }
    }
  ]
}
    </code></pre>

    <h2>🛠️ Tech Stack</h2>
    <ul>
        <li>Frontend: React, TypeScript, Tailwind CSS</li>
        <li>Form Management: React Hook Form</li>
        <li>JSON Validation: Ajv</li>
        <li>Testing: Jest, Playwright</li>
        <li>Deployment: Vercel</li>
    </ul>

    <h2>🖥️ Development Guide</h2>
    <ul>
        <li>JSON Editor: Validates JSON in real-time and displays errors.</li>
        <li>Form Generator: Dynamically generates fields and handles validation.</li>
        <li>Styling: Clean and responsive UI with Tailwind CSS.</li>
    </ul>

    <h2>🌟 Bonus Features</h2>
    <ul>
        <li>Copy JSON schema to clipboard.</li>
        <li>Download form submissions as JSON.</li>
        <li>Dark mode toggle for better accessibility.</li>
    </ul>

    <h2>🌐 Deployment</h2>
    <ol>
        <li>Install Vercel CLI:
            <pre><code>npm install -g vercel</code></pre>
        </li>
        <li>Deploy:
            <pre><code>vercel</code></pre>
        </li>
    </ol>

    <h2>🤝 Contributing</h2>
    <p>Contributions are welcome! Feel free to open issues or submit pull requests.</p>

    <h2>📧 Contact</h2>
    <p>For questions or feedback, email <a href="mailto:your-email@example.com">your-email@example.com</a>.</p>

