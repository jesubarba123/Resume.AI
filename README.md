# Resume.AI
Sube un CV, define el puesto objetivo, pega la vacante y genera una versión optimizada, editable y descargable en Word.
# CV ATS Optimizer.

CV ATS Optimizer is a free, browser-based web application designed to help users transform their existing resume into a professional, editable, ATS-friendly CV in Harvard-style format.

The tool allows users to upload their current CV, enter a target position, paste a job description, analyze the resume, identify missing keywords, generate an optimized version, edit the final content, and download it as a `.docx` file.

This project was created as a free resource for the community.

Privacy Notice.

Your CV is processed directly in your browser.

Resume.AI does not store, upload, sell, or share your documents or personal information.

No backend, database, or account registration is used.

---

## Features.

- Upload an existing CV.
- Supports common file formats such as:
  - PDF.
  - DOCX.
  - TXT.
  - RTF.
  - HTML.
  - JPG, JPEG, PNG through OCR when available.
- Manual form option for users whose file does not load correctly.
- Enter a target job position.
- Paste a job description.
- Detect relevant keywords from the job description.
- Estimate an ATS score for the original CV.
- Display missing keywords and improvement suggestions.
- Generate an optimized CV in either English or Spanish.
- Editable preview before downloading.
- Download the optimized CV as an editable Word `.docx` file.
- Harvard-style CV layout.
- ATS-friendly structure.
- No backend required.
- No database required.
- No user registration required.
- Runs directly in the browser.

---

## Main Sections Generated.

The optimized CV includes a clean and professional structure:

- Full Name / Nombre completo.
- Contact Information / Datos de contacto.
- Professional Summary / Perfil profesional.
- Professional Experience / Experiencia profesional.
- Technical Skills / Habilidades técnicas.
- Education / Educación.
- Certifications / Certificaciones.
- Languages / Idiomas.
- Additional Information / Información adicional.

---

## How It Works.

1. The user uploads their CV or completes the manual form.
2. The user enters the target position.
3. The user pastes the job description.
4. The application extracts and analyzes the CV content.
5. The application detects keywords and gaps against the job description.
6. The user receives an estimated ATS score.
7. The application generates an optimized CV.
8. The user can edit the generated version.
9. The user downloads the final CV as a Word `.docx` file.

---

## Technologies Used.

This project is built with:

- HTML.
- CSS.
- JavaScript.

External libraries are loaded through CDN:

- PDF.js for reading PDF files.
- Mammoth.js for reading DOCX files.
- docx.js for generating Word documents.
- Tesseract.js for OCR support on images.

---

## Installation.

No installation is required.

To use the application locally:

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Start using the tool.

```bash
git clone https://github.com/jesubarba123/resume-ai.git
cd resume-ai
