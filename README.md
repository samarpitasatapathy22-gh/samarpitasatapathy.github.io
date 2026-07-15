<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samarpita Satapathy - Technical Documentation Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', 'Roboto', 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: #ecf0f1;
            padding: 50px 40px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: 700;
            letter-spacing: 1px;
        }
        
        .header p {
            font-size: 1.1em;
            opacity: 0.95;
            font-weight: 300;
            margin-bottom: 10px;
        }
        
        .badge {
            display: inline-block;
            background: #3498db;
            color: white;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.85em;
            margin-top: 10px;
            font-weight: 600;
        }
        
        .content {
            padding: 40px;
        }
        
        .toc {
            background: #ecf0f1;
            padding: 25px;
            border-left: 4px solid #3498db;
            border-radius: 4px;
            margin-bottom: 40px;
        }
        
        .toc h2 {
            color: #2c3e50;
            font-size: 1.3em;
            margin-bottom: 15px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        
        .toc ul {
            list-style: none;
            columns: 2;
            column-gap: 30px;
        }
        
        .toc li {
            margin-bottom: 8px;
        }
        
        .toc a {
            color: #2980b9;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .toc a:hover {
            color: #3498db;
        }
        
        section {
            margin-bottom: 45px;
        }
        
        h2 {
            color: #2c3e50;
            font-size: 1.8em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #3498db;
            font-weight: 700;
        }
        
        h3 {
            color: #34495e;
            font-size: 1.3em;
            margin-top: 20px;
            margin-bottom: 15px;
            font-weight: 600;
        }
        
        p {
            margin-bottom: 15px;
            color: #555;
            font-size: 1em;
        }
        
        ul, ol {
            margin-left: 25px;
            margin-bottom: 20px;
        }
        
        li {
            margin-bottom: 8px;
            color: #555;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
            background: #ffffff;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
            border-radius: 4px;
            overflow: hidden;
        }
        
        th {
            background: #34495e;
            color: #ecf0f1;
            padding: 15px;
            text-align: left;
            font-weight: 600;
            border-bottom: 2px solid #2c3e50;
        }
        
        td {
            padding: 12px 15px;
            border-bottom: 1px solid #ecf0f1;
        }
        
        tr:hover {
            background: #f8f9fa;
        }
        
        .contact-box {
            background: #ecf0f1;
            padding: 25px;
            border-radius: 4px;
            border-left: 4px solid #27ae60;
            margin-top: 20px;
        }
        
        .contact-box a {
            color: #2980b9;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }
        
        .contact-box a:hover {
            color: #3498db;
            text-decoration: underline;
        }
        
        .quote {
            background: #f0f8ff;
            border-left: 5px solid #3498db;
            padding: 25px;
            margin: 30px 0;
            font-style: italic;
            color: #2c3e50;
            font-size: 1.1em;
            border-radius: 4px;
        }
        
        .footer {
            background: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
        
        .competency-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .skill-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 6px;
            border-top: 4px solid #3498db;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
        }
        
        .skill-card h4 {
            color: #2c3e50;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        .skill-card ul {
            margin-left: 20px;
            font-size: 0.95em;
        }
        
        code {
            background: #f4f4f4;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
            color: #d63384;
            font-size: 0.9em;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 1.8em;
            }
            
            .content {
                padding: 20px;
            }
            
            .toc ul {
                columns: 1;
            }
            
            h2 {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <h1>Samarpita Satapathy</h1>
            <p>Associate Technical Writer & Documentation Specialist</p>
            <span class="badge">2+ Years Experience</span>
            <span class="badge">Enterprise SaaS & On-Premise</span>
        </div>
        
        <!-- Main Content -->
        <div class="content">
            <!-- Overview -->
            <p style="font-size: 1.1em; color: #2c3e50; margin-bottom: 30px; line-height: 1.8;">
                Technical documentation specialist with 2+ years of experience creating <strong>user-centric documentation</strong> 
                for enterprise SaaS and on-premise applications. I specialize in transforming <strong>complex technical information</strong> 
                into clear, structured, and easy-to-understand documentation that improves user experience and engagement.
            </p>
            
            <!-- Table of Contents -->
            <div class="toc">
                <h2 style="border: none; margin: 0; padding: 0; font-size: 1.2em;">Quick Navigation</h2>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#competencies">Core Competencies</a></li>
                    <li><a href="#technical-stack">Technical Stack</a></li>
                    <li><a href="#portfolio">Documentation Portfolio</a></li>
                    <li><a href="#expertise">Expertise Areas</a></li>
                    <li><a href="#contact">Contact Information</a></li>
                </ul>
            </div>
            
            <!-- About Me -->
            <section id="about">
                <h2>About Me</h2>
                <ul>
                    <li><strong>Current Role:</strong> Associate Technical Writer at OpenText</li>
                    <li><strong>Specialization:</strong> End-to-end documentation ownership and information architecture</li>
                    <li><strong>Expertise:</strong> Enterprise SaaS and on-premise product documentation</li>
                    <li><strong>Focus Areas:</strong> Structured authoring, information architecture, and content strategy</li>
                    <li><strong>Currently Expanding:</strong> GitHub, Markdown, and Docs-as-Code methodologies</li>
                </ul>
            </section>
            
            <!-- Core Competencies -->
            <section id="competencies">
                <h2>Core Competencies</h2>
                
                <h3>Documentation Types</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Documentation Type</th>
                            <th>Proficiency Level</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>User Guides & Manuals</td>
                            <td>Expert</td>
                        </tr>
                        <tr>
                            <td>Installation & Configuration Guides</td>
                            <td>Expert</td>
                        </tr>
                        <tr>
                            <td>Administrator Guides</td>
                            <td>Advanced</td>
                        </tr>
                        <tr>
                            <td>API Documentation</td>
                            <td>Advanced</td>
                        </tr>
                        <tr>
                            <td>Integration Documentation</td>
                            <td>Advanced</td>
                        </tr>
                        <tr>
                            <td>Release Notes</td>
                            <td>Advanced</td>
                        </tr>
                        <tr>
                            <td>Troubleshooting Guides</td>
                            <td>Advanced</td>
                        </tr>
                        <tr>
                            <td>Knowledge Base Articles</td>
                            <td>Advanced</td>
                        </tr>
                        <tr>
                            <td>Context-Sensitive Help (CSH)</td>
                            <td>Advanced</td>
                        </tr>
                    </tbody>
                </table>
                
                <h3>Specialized Skills</h3>
                <div class="competency-grid">
                    <div class="skill-card">
                        <h4>Information Architecture</h4>
                        <ul>
                            <li>Structured content organization</li>
                            <li>Taxonomy development</li>
                            <li>Navigation design</li>
                            <li>Content governance</li>
                        </ul>
                    </div>
                    <div class="skill-card">
                        <h4>Content Strategy</h4>
                        <ul>
                            <li>Documentation planning</li>
                            <li>User analysis & personas</li>
                            <li>Consistency management</li>
                            <li>Style guide development</li>
                        </ul>
                    </div>
                    <div class="skill-card">
                        <h4>Technical Writing</h4>
                        <ul>
                            <li>User-centered design</li>
                            <li>Complex concept simplification</li>
                            <li>Technical accuracy</li>
                            <li>UX/UI microcopy</li>
                        </ul>
                    </div>
                </div>
            </section>
            
            <!-- Technical Stack -->
            <section id="technical-stack">
                <h2>Technical Stack</h2>
                
                <h3>Authoring & Markup Tools</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Category</th>
                            <th>Tools & Technologies</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>XML/DITA Editors</strong></td>
                            <td>Arbortext Editor, Oxygen XML Editor</td>
                        </tr>
                        <tr>
                            <td><strong>DITA Publishing</strong></td>
                            <td>MadCap Flare</td>
                        </tr>
                        <tr>
                            <td><strong>Document Authoring</strong></td>
                            <td>Microsoft Word</td>
                        </tr>
                        <tr>
                            <td><strong>Markup Languages</strong></td>
                            <td>DITA XML, Markdown, HTML (Basics)</td>
                        </tr>
                    </tbody>
                </table>
                
                <h3>Version Control & Collaboration</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Category</th>
                            <th>Tools & Platforms</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>Version Control</strong></td>
                            <td>Git, GitLab, GitHub, Perforce</td>
                        </tr>
                        <tr>
                            <td><strong>Project Management</strong></td>
                            <td>Jira, ValueEdge</td>
                        </tr>
                    </tbody>
                </table>
                
                <h3>Multimedia & Content Creation</h3>
                <table>
                    <thead>
                        <tr>
                            <th>Category</th>
                            <th>Tools & Software</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>Video Creation</strong></td>
                            <td>Camtasia, Adobe Premiere Pro</td>
                        </tr>
                        <tr>
                            <td><strong>Document Processing</strong></td>
                            <td>Adobe Acrobat</td>
                        </tr>
                    </tbody>
                </table>
            </section>
            
            <!-- Documentation Portfolio -->
            <section id="portfolio">
                <h2>Documentation Portfolio</h2>
                <p>Collection of technical writing samples and reusable templates:</p>
                <ul>
                    <li><strong>User Guide</strong> - Comprehensive end-user documentation</li>
                    <li><strong>Installation Guide</strong> - System requirements and setup procedures</li>
                    <li><strong>Quick Start Guide</strong> - Expedited onboarding documentation</li>
                    <li><strong>API Documentation</strong> - Technical reference for developers</li>
                    <li><strong>Troubleshooting Guide</strong> - Issues and resolution procedures</li>
                    <li><strong>Release Notes</strong> - Version updates and features</li>
                    <li><strong>FAQ</strong> - Frequently asked questions</li>
                    <li><strong>Knowledge Base Articles</strong> - In-depth topic documentation</li>
                    <li><strong>Documentation Templates</strong> - Reusable templates</li>
                </ul>
            </section>
            
            <!-- Expertise Areas -->
            <section id="expertise">
                <h2>Expertise Areas</h2>
                <h3>Documentation Best Practices</h3>
                <ul>
                    <li><strong>Structured Authoring:</strong> DITA XML implementation and methodology</li>
                    <li><strong>Content Reusability:</strong> Single-sourcing and modular documentation strategies</li>
                    <li><strong>Information Architecture:</strong> Logical organization and content findability</li>
                    <li><strong>Content Strategy:</strong> Planning, governance, and consistency</li>
                </ul>
                
                <h3>Technical Communication</h3>
                <ul>
                    <li>Complex technical concept simplification</li>
                    <li>Technical accuracy with user accessibility</li>
                    <li>Cross-functional SME collaboration</li>
                    <li>Quality assurance and peer review</li>
                </ul>
                
                <h3>Emerging Technologies</h3>
                <ul>
                    <li><strong>Docs-as-Code:</strong> Markdown-based documentation workflows</li>
                    <li><strong>Version Control:</strong> Git-based documentation versioning</li>
                    <li><strong>CI/CD Integration:</strong> Continuous documentation integration</li>
                </ul>
            </section>
            
            <!-- Quote -->
            <div class="quote">
                "Great technical documentation doesn't just explain a product—it empowers people to achieve their objectives with confidence and efficiency."
            </div>
            
            <!-- Contact Information -->
            <section id="contact">
                <h2>Contact Information</h2>
                <div class="contact-box">
                    <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/samarpita-satapathy/" target="_blank">linkedin.com/in/samarpita-satapathy/</a></p>
                    <p><strong>Email:</strong> <a href="mailto:samarpitasatapathy22@gmail.com">samarpitasatapathy22@gmail.com</a></p>
                </div>
            </section>
        </div>
        
        <!-- Footer -->
        <div class="footer">
            <p>Last Updated: July 2026 | Technical Documentation Portfolio</p>
        </div>
    </div>
</body>
</html>
