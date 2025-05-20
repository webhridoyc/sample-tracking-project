# Server-Side CAPI Integration Note

This project currently uses client-side Facebook Pixel and GA4 via GTM. 
To upgrade to server-side Facebook CAPI:

## Tools You Can Use:
- Facebook Conversion API Gateway
- Google Tag Manager Server container
- Custom Node.js/PHP server endpoints

## General Steps:
1. Create a server (e.g., Vercel, Firebase, or your own).
2. Use Facebook CAPI token (Events Manager > Settings).
3. Capture events from the front-end and send them via HTTPS POST to Facebook's CAPI endpoint.

> Reference: https://developers.facebook.com/docs/marketing-api/conversions-api/

This project includes a `config-example.json` to guide integration structure.
