# Smart Document Formatter

**A Python-powered desktop application that automatically formats Microsoft Word documents using predefined professional and academic formatting standards.**

Smart Document Formatter simplifies document formatting by allowing users to select an existing Word document, choose a document category and formatting standard, and automatically apply consistent typography, spacing, margins, headings and other layout settings.

Instead of manually formatting every document, users can apply professional formatting presets in just a few steps.

---

## Overview

Smart Document Formatter is designed for students, researchers, professionals, businesses and anyone who regularly works with Microsoft Word documents.

The application provides predefined formatting templates for different document types, making it easier to produce clean, consistent and professionally structured documents.

The primary objective is to automate document formatting while preserving the author's original written content.

## Features

### Document Categories

The application includes formatting presets for:

- **Academic Work** – University assignments, dissertations, research projects and academic reports.
- **Resume / CV** – Professional CVs, graduate resumes and ATS-friendly resumes.
- **Business Documents** – Corporate reports, business proposals and project reports.
- **Formal Letters** – Official letters, application letters and cover letters.
- **Research Publications** – Journal manuscripts, conference papers and scientific articles.
- **Books and E-books** – Textbooks, educational notes and book manuscripts.
- **Meeting Documents** – Meeting minutes, agendas and action plans.
- **General Documents** – Study notes, personal documents and general-purpose documentation.

### Academic Formatting Standards

Available academic formatting presets include:

- APA 7th Edition
- MLA 9th Edition
- Harvard Referencing
- Chicago Style
- IEEE Style
- General University Standard

### Formatting Capabilities

- Automatic font and font-size standardisation.
- Paragraph spacing and line-spacing adjustments.
- Page margin configuration.
- Heading and subheading formatting.
- Paragraph indentation and alignment.
- Table formatting and styling.
- Optional page numbering.
- Preservation of existing document text.
- Custom output filenames and destination folders.

### File Management

- Browse and select existing Word documents.
- Choose where formatted documents are saved.
- Specify custom output filenames.
- Preserve the original document.
- Save formatted documents as separate `.docx` files.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Tkinter | Desktop application interface |
| python-docx | Microsoft Word document processing |
| lxml | Advanced Word document XML manipulation |
| Pillow | Image-processing support |

---

## Installation

### Requirements

- Python 3.9 or later.
- Windows recommended for the current desktop interface.
- Microsoft Word or another compatible `.docx` viewer for reviewing formatted documents.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/smart-document-formatter.git
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Enter the Project Directory

```bash
cd smart-document-formatter
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

Alternatively:

```bash
pip install python-docx
```

### 4. Run the Application

```bash
python smart_document_formatter.py
```

The desktop application should open.

---

## How to Use

1. Launch Smart Document Formatter.
2. Select an existing `.docx` document using the Browse button.
3. Choose the appropriate document category.
4. Select your preferred formatting preset.
5. Configure additional options, such as table styling and page numbering.
6. Specify the output filename.
7. Select the destination folder.
8. Click **Format Document**.
9. Open the generated document and review the formatting.

### Sample Document

A sample academic document is included in the `samples` directory.

Use it to test different academic formatting presets before processing your own documents.

---

## Project Structure

```text
smart-document-formatter/
│
├── smart_document_formatter.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── samples/
    └── sample_academic_document.docx
```

---

## Content Preservation

Smart Document Formatter is designed to modify document formatting without rewriting the author's content.

The original document is not intentionally overwritten. A separate formatted copy is generated.

Existing text, images, tables and other document elements are generally retained. However, complex Word layouts, floating objects, text boxes and specialised headers or footers may require manual review.

Always review the resulting document before submitting or distributing it.

---

## Current Limitations

This is an early version of the application.

The following capabilities are planned but are not yet implemented:

- Automatic table of contents generation.
- Before-and-after document preview.
- Batch formatting of multiple documents.
- User-created and saved formatting templates.
- PDF export.
- Advanced document structure detection.
- More comprehensive preservation of complex Word layouts.
- Windows executable installer.

The formatting presets provide practical starting points and do not guarantee complete compliance with every university's formatting handbook or citation-style requirements.

---

## Development Roadmap

| Feature | Status |
|---|---|
| Desktop application interface | Implemented |
| Predefined document categories | Implemented |
| Academic formatting presets | Implemented |
| Automatic paragraph formatting | Implemented |
| Heading formatting | Implemented |
| Table formatting | Implemented |
| Custom file selection | Implemented |
| Custom output destination | Implemented |
| Optional page numbering | Implemented |
| Automatic table of contents | Planned |
| Formatting preview | Planned |
| Batch document processing | Planned |
| Custom formatting templates | Planned |
| PDF export | Planned |
| Windows `.exe` installer | Planned |

---

## Contributing

Suggestions, bug reports and contributions are welcome.

If you encounter a formatting issue or have an idea for improving the application, feel free to open a GitHub Issue.

---

## License

No open-source licence has been assigned yet. All rights are reserved unless and until a licence is added.

---

**Smart Document Formatter**

*Making professional document formatting easier, faster and more accessible.*
