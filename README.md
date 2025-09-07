# CSS.413.1 — Topics in Coding Theory (TIFR, 2025)

This repository hosts the lecture notes and resources for the course **CSS.413.1 — Topics in Coding Theory**, conducted at the Tata Institute of Fundamental Research (TIFR) during the **August–November 2025** semester.

**Instructor:** Prof. Mrinal Kumar  
**Scribe & Notes Author:** Soham Chatterjee  
**Semester:** August – November 2025  
**Institute:** Tata Institute of Fundamental Research (TIFR)  
**Course Page:** *(Add link here if available)*

---

##  Course Overview

An advanced exploration of **coding theory**, focusing on both foundational principles and cutting-edge developments. Topics include:

1. **Introduction to Coding Theory** – basic concepts and linear codes  
2. **Reed–Solomon & Reed–Muller Codes**  
3. **Decoding Algorithms** – Berlekamp–Welch, Sudan, Guruswami–Sudan  
4. **Univariate Multiplicity Codes** & decoding to list-decoding capacity  
5. **Bounds on List Size**  
6. **Locally Decodable & Correctable Codes (LDCs & LCCs)** – local correction of Reed–Muller codes, constant-query decoding, Matching Vector Codes  
7. **Private Information Retrieval (PIR)** – constructions and lower bounds  
8. **Lower Bounds for LDCs** – 2-query, 4-query, and bounds by Katz–Trevisan, Alrabiah–Guruswami  
9. **Local Testing of Codes** – tests by Polischuk–Spielman, Friedl–Sudan, Arora–Sudan, Raz–Safra  
10. **Applications** – explicit constructions, combinatorial & subspace designs, derandomization, hardness vs randomness  

*(See the PDF or source for the full table of contents.)*

---

##  Contents

- `topics-in-coding-theory.tex` — LaTeX source for the lecture notes  
- `topics-in-coding-theory.pdf` — Compiled version of the notes  
- `chapters/` — Individual chapter files (if split)  
- `images/` — Figures and illustrations used in the notes  
- `macros.tex`, `preamble.tex`, etc. — LaTeX utility and formatting files  

---

##  References

- **List Decoding of Error-Correcting Codes** — Venkatesan Guruswami & Madhu Sudan  
- **Decoding Beyond the Error-Correction Bound** — Madhu Sudan  
- **Testing Polynomial Identities** — Sanjeev Arora & Madhu Sudan  
- Additional lectures and research articles as referenced throughout the notes  

---

##  Typesetting & Style

These lecture notes are typeset in **LaTeX**, using a custom theme:

- **Preamble and macros** organized for consistency and ease of editing  
- **Visual styling** (fonts, headings, rules, spacing) aligned with TIFR lecture note aesthetics  
- Modular chapter structure for maintainability  

---

##  How to Compile

```bash
git clone https://github.com/<your-username>/CSS.413.1-Topics-in-Coding-Theory.git
cd CSS.413.1-Topics-in-Coding-Theory
pdflatex topics-in-coding-theory.tex

