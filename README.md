# 🐾 Dog Breed Check

Dog Breed Check is a web application that connects dog breed information with FDA animal adverse-event reports to help users research medications reported in association with different dog breeds.
<img width="1981" height="470" alt="Screenshot 2026-11-23 at 5 08 34 PM" src="https://github.com/user-attachments/assets/4a65ae20-9296-4cad-ba30-ebbf1cc5d72e" />

## Live Demo 
[Check out the Dog Breed Check Tool!](https://vet-practice-api.onrender.com/)

## Features
Dog Breed Check brings together information from two public APIs to make veterinary medication research more accessible.

- **Breed Search**: Search for a dog breed by name and retrieve breed information
- **Medication Lookup**: Search FDA animal adverse-event data using the selected breed
- **Medication Report Counts**: Display the number of reports associated with each medication ingredient

## How It Works
Dog Breed Check uses two APIs to retrieve and connect information:

1. **Dog API**: The application first queries the Dog API to locate the requested breed. Once a matching breed is found, the application displays its name and description.

2. **FDA Animal and Veterinary API**: The breed information is then used to initiate a second API request to the FDA's Animal and Veterinary Adverse Event database. The application searches reported animal adverse events and retrieves medication active ingredients associated with those reports.


## Tech Stack & APIs 
- HTML 
- CSS
- JavaScript
- Dog API 
- FDA OpenFDA API
- Fetch API
- JSON
- **Dog API**
- **FDA OpenFDA**

## Getting Started
**Installation**
1. Clone the repository:
```bash
git clone https://github.com/CarlyJovon/vet-practice-api.git
```

2. Navigate to the project directory:
```bash
cd vet-practice-api
```
3. Open the project using a local development server, such as VS Code Live Server
4. Search for a dog breed to explore the results

## Disclaimer
Dog Breed Check is an informational research tool and is not a substitute for professional veterinary advice.

FDA adverse-event reports do not establish that a medication caused a reported reaction. Always consult a licensed veterinarian before making medication or treatment decisions for your pet.
