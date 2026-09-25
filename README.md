# NIST Editor – ANSI/NIST-ITL Biometric File Viewer, Editor & Validator
![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D4?style=for-the-badge)
![.NET](https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge)
![WebView2](https://img.shields.io/badge/WebView2-Required-00A300?style=for-the-badge)

🌐 **Website:** https://nadrianstoica.github.io/NIST-Editor/  
⬇️ **Latest Windows build:** https://github.com/nadrianstoica/NIST-Editor/releases/latest

---

## Comprehensive ANSI/NIST Biometric File Viewer, Editor, Validator and Analysis Tool


**NIST Editor** by Adrian Stoica (nadrianstoica) is a Windows desktop application for viewing, editing, validating, converting and analyzing ANSI/NIST-ITL biometric files, including fingerprint, facial, iris and other biometric records.

> **Independent project:** NIST Editor is not affiliated with or endorsed by the U.S. National Institute of Standards and Technology (NIST).

It has been designed for:

- Biometric software engineers
- AFIS developers
- Law enforcement agencies
- Border control systems
- Forensic laboratories
- Government agencies
- Biometric SDK vendors
- Researchers
- System integrators

The application focuses on **correctness**, **interoperability**, **standards compliance**, **lossless editing**, and **offline operation**.

---

## Live Demonstration

<p align="center">

<img src="docs/images/demo.gif" width="1000">

</p>

*A short demonstration showing opening a NIST file, image preview, field editing, validation, and integrated NFIQ2 fingerprint quality analysis.*

---

## Main Features

### ANSI/NIST Traditional Support

✔ Open Traditional ANSI/NIST files

✔ Edit any supported record

✔ Byte-preserving binary payload handling

✔ Lossless Traditional → Traditional round-trip

✔ Automatic LEN/CNT regeneration

✔ Legacy separator preservation

✔ Variable-length and fixed-length record support

---

### XML Support

✔ Import ANSI/NIST XML

✔ Export ANSI/NIST XML

✔ Lossless XML round-trip

✔ Traditional ↔ XML conversion

✔ Preservation of binary payloads

---

### Standards-Aware Editing

Built-in knowledge of multiple biometric standards and implementation profiles.

Examples include:

- ANSI/NIST-ITL 1-2025
- ANSI/NIST-ITL 1-2011
- FBI EBTS
- INTERPOL
- Optional imported implementation profiles

Features include:

- automatic profile detection
- profile-specific validation
- schema-aware editing
- contextual hints
- code tables
- repair suggestions
- validation explanations

Optional implementation profiles can be imported without modifying the built-in standards.

---

## Supported Record Types

Supports editing and validation of numerous ANSI/NIST record types including:

- Type-1 Transaction Information
- Type-2 User Defined Text
- Type-3 Low Resolution Grayscale Fingerprint
- Type-4 High Resolution Grayscale Fingerprint
- Type-5 Low Resolution Binary Fingerprint
- Type-6 High Resolution Binary Fingerprint
- Type-7 User Defined Image
- Type-8 Signature Image
- Type-9 Minutiae
- Type-10 Facial / SMT Image
- Type-11 Voice
- Type-12 Dental
- Type-13 Latent Fingerprint
- Type-14 Tenprint Fingerprint
- Type-15 Palmprint
- Type-16 User Defined Testing Image
- Type-17 Iris
- Type-18 DNA
- Type-19 Plantar / Friction Ridge
- Type-20 Source Representation
- Type-21 Associated Context
- Type-22 Non-photographic Imagery
- Type-98 XML
- Type-99 CBEFF Biometric Data Block

---

## Image Support

Supports many biometric image encodings including:

- WSQ
- JPEG
- JPEG 2000
- PNG
- BMP
- TIFF
- JPEG-LS
- DICOM
- RAW raster formats

Capabilities:

✔ Automatic decoder detection

✔ Image metadata extraction

✔ Resolution verification

✔ Compression verification

✔ Preview generation

✔ Payload preservation

---

## Fingerprint Quality Analysis

Integrated **NFIQ2** quality analysis.

Features include:

- Quality score
- Quality assessment
- Fingerprint overlay
- Ridge endings
- Bifurcations
- Minutiae statistics
- Processing time
- Exported minutiae
- Overlay rendering

The overlay is rendered directly over the decoded image used for NFIQ2 processing.

---

## Validation Engine

The editor performs comprehensive validation including:

✔ Mandatory fields

✔ Field formats

✔ Numeric ranges

✔ Enumerations

✔ Compression algorithms

✔ Image metadata

✔ Resolution consistency

✔ DPI consistency

✔ CGA consistency

✔ Record relationships

✔ Cross-field validation

✔ Profile-specific validation

Validation messages include contextual explanations and repair suggestions where applicable.

---

## Image Preview

The integrated preview supports:

- automatic image detection
- metadata inspection
- safe payload preview
- DPI diagnostics
- compression diagnostics
- embedded decoder selection

Large binary payloads remain fully preserved.

---

## Type-12 Dental Support

Structured Traditional dental parsing including:

- dental history
- oral findings
- structured list handling
- image references
- payload preservation

JSON/XML dental payloads are safely preserved while providing secure preview capabilities.

---

## NFIQ2 Integration

Integrated NFIQ2 analysis provides:

- fingerprint quality score
- quality assessment
- extracted minutiae
- overlay visualization
- feature statistics
- CSV export
- overlay PNG export

---

## Privacy

**NIST Editor operates completely offline.**

No biometric records are transmitted to external services.

No cloud processing is required.

All decoding, validation and quality analysis are performed locally.

---

## Standards

The integrated Help contains references to major biometric standards including:

- ANSI/NIST-ITL
- FBI EBTS
- INTERPOL
- NIST Special Publications
- ISO biometric standards
- WSQ
- JPEG 2000
- JPEG-LS
- NIEM
- Additional reference documentation

---

## Windows Desktop

Public Windows releases are built using

- .NET 10
- Microsoft Edge WebView2

The HTML application is embedded inside the executable.

---

## License

NIST Editor is **licensed, not sold**.

### Free Personal and Evaluation Use

NIST Editor may be used **free of charge** for:

* personal, non-commercial use; and
* evaluation, testing, demonstration, or assessment purposes.

Evaluation use may include testing the software within an organization before deciding whether to adopt or deploy it for operational or production use.

### Commercial and Organizational Use

Use of NIST Editor for **commercial, professional, governmental, forensic, law-enforcement, organizational, operational, or production purposes** is subject to the NIST Editor **End-User License Agreement (EULA)**.

A commercial-use license is granted, subject to the terms of the EULA, upon receipt of a support contribution made in connection with NIST Editor.

> **There is no minimum contribution amount. Any support contribution, regardless of amount, constitutes sufficient consideration for the commercial-use license granted under the EULA.**

Organizations and professionals intending to use NIST Editor for purposes other than personal use or evaluation should review the EULA before deployment or operational use.

### Restrictions and Legal Terms

The EULA contains the complete terms governing the software, including:

* permitted and prohibited uses;
* personal and evaluation use;
* commercial and organizational licensing;
* redistribution and sublicensing restrictions;
* intellectual-property rights;
* warranty disclaimers;
* limitations of liability; and
* termination conditions.

Unless expressly permitted by the EULA, the license does not grant the right to redistribute, sublicense, sell, relicense, or commercially distribute NIST Editor or modified versions of it.

> **In the event of any conflict between this README and the EULA, the EULA governs.**

### Full License Agreement

The complete Software License Agreement is included with NIST Editor and is available from:

**Help → About → Software License Agreement (EULA)**

By installing, accessing, or using NIST Editor, you acknowledge that your use of the software is subject to the applicable terms of the EULA.

---

## Download

Download the latest public **Windows executable build** from the **Releases** section:

https://github.com/nadrianstoica/NIST-Editor/releases/latest

Public release archives contain the Windows application builds intended for end users. Project/source archives are not distributed as NIST Editor release downloads.

No installation is required.

---

## Documentation

The integrated Help includes documentation for:

- Supported record types
- Standards
- Profiles
- Validation rules
- Compression algorithms
- Image formats
- Fingerprint quality analysis
- Licensing

---

## Reporting Issues

Bug reports and feature requests are welcome.

When reporting issues please include:

- Application version
- Windows version
- Steps to reproduce
- Screenshots
- Sample file (if legally permissible)
- optional: JSON with the internal metadata. Go to Help / Developer diagnostics / Export Canonical Debug JSON metadata only

---

## Screenshots

### Main Window

<p align="center">
<img src="docs/images/main-window.png" width="1000">
</p>

---

### Image Preview

<p align="center">
<img src="docs/images/main-window-light.png" width="1000">
</p>

---

### Validation

<p align="center">
<img src="docs/images/validation.png" width="1000">
</p>

---

### Fingerprint Quality Analysis

<p align="center">
<img src="docs/images/nfiq2-overlay.png" width="1000">
</p>

---

### Schema Browser

<p align="center">
<img src="docs/images/schema-browser.png" width="1000">
</p>

---

### Help

<p align="center">
<img src="docs/images/help.png" width="1000">
</p>

---

### About

<p align="center">
<img src="docs/images/about.png" width="1000">
</p>

---

## Copyright

Copyright © Adrian Stoica, 2026.

All rights reserved.

<sub>Proudly engineered in Romania.</sub>
