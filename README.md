# Vaulted (TapChart demo)

TapChart is a patient-held health ID. You keep your basics, allergies, medicines and conditions in one place and share only what a clinic needs, for a limited time, with a check-in code.

This repo is a **front-end demo with sample data**. There is no backend, no real encryption, no NFC and no real clinics. Everything is saved in your browser (localStorage). The patient and all records are made up.

Live demo: https://quiet-frangollo-c00211.netlify.app/

## What the demo shows
- Health ID, sharing presets, expiry and a biometric step, then a check-in code
- Clinic desk: incoming check-ins, summary, medicine reconciliation with write-back, FHIR R4 download
- Medicine reminders and adherence log, document vault, vitals and trends, emergency card, family profiles
- Access log, export and delete account
- Clinic-side deletion policy: patient requests deletion, the clinic honours it within 72 h and issues a certificate

## Run it
Open `index.html` in a browser. It is a single file.

## Next
FastAPI + PostgreSQL backend per the PRD.
