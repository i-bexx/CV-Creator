# Java PDF Resume Generator

A lightweight, programmatic approach to generating professional resumes (CVs) in PDF format using Java and the **OpenPDF** library.

This project creates a clean, structured PDF resume including a profile photo, personal details, and work experience history.

## Features

* **PDF Generation:** Generates a standard A4 PDF file (`resume.pdf`).
* **Image Support:** Automatically embeds a profile photo from the resources folder.
* **Text Formatting:** Uses different fonts and sizes for titles, headers, and body text.
* **Clean Layout:** Simple, linear layout for easy readability.

## Tech Stack

* **Java:** JDK 8 or higher.
* **OpenPDF:** A free and open-source PDF library (fork of iText).

## Dependencies

To run this project, you need to add the **OpenPDF** dependency to your build file.

### Maven (`pom.xml`)
```xml
<dependency>
    <groupId>com.github.librepdf</groupId>
    <artifactId>openpdf</artifactId>
    <version>1.3.30</version>
</dependency>
