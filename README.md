# Faytm

Faytm is a "vibe coding" throw-away project that I'm using to experiment with technologies I find interesting. This is not intended to be a production-ready application, but rather a playground for learning and exploration.

## What is Faytm?
Faytm aims to facilitate UPI payments by scanning people's faces instead of conventional QR codes. The idea is to replace the need for QR codes with facial recognition technology for a more seamless payment experience.

## How it Works
The application will:

1. Use facial recognition to identify registered users

2. Retrieve the associated UPI ID for the recognized face

3. Redirect users to established UPI apps (like Paytm) for the actual payment

4. Auto-fill the UPI ID, making the payment process faster

## Technologies
- [Rust](https://www.rust-lang.org/) - converted to WASM for deployment
- [SpaceTimeDB](https://spacetimedb.com/home) - for storage and compute both
- [LynxJS](https://lynxjs.org/) - for app development

## ToDo
[ ] Will add a link to play store listing

[ ] Will add a link to youtube tutorial

## Disclaimer  
This is a throw-away side project. Faytm does not process payments itself but redirects to official UPI apps for the actual transaction.