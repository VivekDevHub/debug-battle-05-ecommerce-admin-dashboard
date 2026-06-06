# Debug Battle 05 - Fixes Applied

## Frontend Fixes

* Fixed login form input name from `pass` to `password`.
* Fixed `showToast` state mutation by using functional state updates.
* Fixed loading state remaining `true` on error; now correctly set to `false`.
* Fixed `.toString()` on variants array returning `[object Object]`; replaced with `JSON.stringify()`.
* Fixed Axios `baseURL` port mismatch (`5000` vs `5001`) by using environment variables.
* Connected Axios configuration to `VITE_API_URL` environment variable.
* Standardized authentication token usage to `accessToken`.
* Removed password hash from UI rendering.
* Prevented crashes from `item.price.toFixed()` using optional chaining.
* Prevented crashes from `totalAmount.toFixed()` using optional chaining.
* Converted `tailwind.config` from CommonJS to ESM format.
* Replaced 20+ invalid Tailwind CSS utility classes with valid color shades.
* Fixed order quantity type by parsing values as numbers.
* Updated API endpoint from `/product` to `/products`.
* Updated API endpoint from `/order` to `/orders`.

## Backend & Configuration Fixes

* Fixed CORS configuration by replacing `origin: '*'` with a specific frontend origin when using `credentials: true`.
* Fixed environment configuration mismatch where `.env` used `https` while the server was running on `http`.
* Improved frontend-backend integration consistency.
* Resolved API route mismatches between frontend and backend services.

## Result

All identified frontend, backend, API integration, configuration, and runtime issues were successfully resolved, resulting in a stable and fully functional e-commerce admin dashboard.
