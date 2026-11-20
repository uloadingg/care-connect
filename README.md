# Care Connect Website

**Live site:** [careconnectwa.com](https://careconnectwa.com)

Care Connect is a Washington State elder care referral agency. This repository holds the agency's public website, which serves three groups of users:

| User | What they need | How the site meets it |
| --- | --- | --- |
| Families of seniors | Help finding an adult family home or assisted living facility | Senior Home Placement service details and direct call/email contact |
| Caregivers | A way to find care jobs quickly | One-tap "apply by text" link that pre-fills an application message |
| Care home providers | A simple way to share open beds and partner with the agency | Provider availability form (Google Form) |

## Features

- Single-page layout with sections for About, Services, Caregivers, Providers and Contact
- Three service offerings: Senior Home Placement, Caregiver Job Placement and Provider Partnerships
- Mobile-friendly contact actions: tap-to-call, tap-to-email and tap-to-text links
- Provider intake handled through an external Google Form, so availability updates come in without a custom backend

## Built with

- HTML and CSS
- Google Fonts
- GitHub Pages for hosting, with a custom domain

## Why it's built this way

The goal was the fastest route from "someone needs help" to "they're talking to us." Every section ends in a direct contact action rather than a long form, because families and caregivers often reach out from their phones. Using GitHub Pages and a Google Form keeps the site free to host and easy to update.

## Roadmap

- Add a short intake form for families
- Track which contact method each lead uses, to see which channels bring in the most referrals
- Add an FAQ section for families new to adult family homes

## Run it locally

Clone the repo and open `index.html` in any browser. No build step is needed.
