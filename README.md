# EML File Viewer

A simple, single-page web application to open and view the contents of .eml files (as downloaded from Gmail and other email clients) directly in your browser.

This tool is built with pure HTML, JavaScript, and Tailwind CSS. It parses the .eml file on the client-side, meaning your files never leave your computer.

## How to Use
<ol>

<li>Upload: Click the "Choose .eml file" button and select the .eml file you wish to view.</li>

<li>View: The application will instantly parse and display the email's subject, sender, recipient, and body content in a clean, Gmail-inspired interface.</li>
</ol>

## Features

<ul>
<li>Client-Side Parsing: No server is required. Your data stays private.</li>

<li>Gmail-Style UI: A clean, familiar, and responsive interface.</li>

<li>Content Decoding: Automatically handles common email encodings like Base64 and Quoted-Printable.</li>

<li>Charset Handling: Attempts to correctly decode various character sets to prevent font and text display errors.</li>

<li>Safe HTML Rendering: Renders the HTML body of the email inside a sandboxed iframe to prevent security risks.</li>

</ul>

## Technology

<ul>
<li>HTML: For the basic structure.</li>

<li>Tailwind CSS: For all styling and layout.</li>

<li>JavaScript (Vanilla): For all logic, including file reading (FileReader), EML parsing (regex), and content decoding (TextDecoder).</li>
</ul>