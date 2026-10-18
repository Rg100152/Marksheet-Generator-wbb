# Marksheet-Generator-wbb
# Marksheet Generator Web App
A client-side web application designed to generate and preview academic marksheets in a classic board examination format[span_0](start_span)[span_0](end_span). Built using standard HTML, CSS, and vanilla JavaScript.
## Features
- **Live Preview**: Real-time updates to candidate details, roll numbers, school information, and subject scores.
- **Automated Calculations**: Automatically calculates subject totals, averages (such as First Language Paper 1 & 2 combined scores), and corresponding letter grades (`AA`, `A+`, `A`, `B+`, `B`, `C`, `D`)[span_1](start_span)[span_1](end_span).
- **Photo Upload**: Allows uploading a candidate photograph with an optional grayscale/vintage filter[span_2](start_span)[span_2](end_span).
- **Print-Ready Layout**: Includes `@media print` CSS rules to hide the editor sidebar and export a clean A4 document or PDF.
## Project Structure
- `index.html` - Contains the layout structure, styling (CSS), and calculation logic (JavaScript) in a single self-contained file.
## How to Use
1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Use the left-hand control panel to edit the student details and subject marks.
4. Upload a passport-style photo using the file input.
5. Click **Print / Save PDF** to print the document or save it as a PDF via your browser's print dialog.
## Grading Scale Reference

| Marks Range | Grade | Performance Indicator |
| :--- | :--- | :--- |
| 90 - 100 | AA | Outstanding[span_3](start_span)[span_3](end_span) |
| 80 - 89 | A+ | Excellent[span_4](start_span)[span_4](end_span) |
| 60 - 79 | A | Very Good[span_5](start_span)[span_5](end_span) |
| 45 - 59 | B+ | Good[span_6](start_span)[span_6](end_span) |
| 35 - 44 | B | Satisfactory[span_7](start_span)[span_7](end_span) |
| 25 - 34 | C | Marginal[span_8](start_span)[span_8](end_span) |
| Below 25 | D | Disqualified[span_9](start_span)[span_9](end_span) |

## Disclaimer
This project is a UI/UX template created strictly for educational, demonstration, and layout prototyping purposes. It is not affiliated with any official educational board and must not be used to generate or misrepresent official academic records.