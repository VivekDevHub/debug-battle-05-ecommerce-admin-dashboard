Frontend
Login input name="pass" instead of "password" → fixed
showToast mutates state array, sets same ref → functional state updates
setLoading(true) on error → changed to false
.toString() on variants array sends [object Object] → JSON.stringify()
Axios baseURL port 5000 mismatches Vite proxy 5001 → use env variable
VITE_API_URL env var defined but never used → axios reads it now
Token field name inconsistent (token vs accessToken) → both use accessToken
Password hash displayed in UI → removed
item.price.toFixed crashes if undefined → optional chaining
totalAmount.toFixed crashes if undefined → optional chaining
tailwind.config uses CJS in ESM project → converted to ESM
20+ invalid Tailwind classes → replaced with valid shades
Order quantity stored as string → parsed as number
Frontend calls /product but server has /products → fixed
Frontend calls /order but server has /orders → fixed
CORS origin: '*' with credentials: true rejected by browser → specific origin
.env has https but server runs http → changed to http