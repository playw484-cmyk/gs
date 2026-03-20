# Krisomika Retail Private Limited Careers Page

This repository contains a premium static recruitment webpage for Krisomika Retail Private Limited with:
- a premium-styled employee recruitment process section
- an online job application form
- fields for name, experience, education, and resume upload
- email notification workflow configured for `hr@groceryselect.in` using FormSubmit

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Form email notification

The form posts to `https://formsubmit.co/hr@groceryselect.in`.
If this email address is being used with FormSubmit for the first time, FormSubmit may send an activation email that must be confirmed once before regular submissions start arriving.
