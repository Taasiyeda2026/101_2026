# Form 101 - Tax Year 2026

## Overview
A Hebrew tax form (טופס 101) for tax year 2026. This is a static HTML application that allows users to fill in employee details and generate a signed PDF document.

## Project Structure
- `index.html` - Main form page (copy of 101_2026.html for web serving)
- `101_2026.html` - Original form file
- `server.py` - Simple Python HTTP server for development

## Features
- Employee details form (name, ID, birth date, phone)
- Canvas-based signature pad
- PDF generation using jsPDF library

## Running the Project
The project runs as a static website served on port 5000.

Development: `python server.py`

## Deployment
Configured for static deployment - serves the HTML files directly.
