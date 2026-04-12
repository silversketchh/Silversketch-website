# User Authentication & Orders System TODO

**Information Gathered:**
- Single index.html file with embedded JS/CSS/HTML
- Current order modal collects: name, phone, artwork, size, price, address
- WhatsApp redirect on submit
- No backend/server; pure frontend
- Email: 6srinath2006@gmail.com

**Plan:**
1. **File: index.html**
   - Add login/register modal triggered by "Login"
   - Use localStorage for user data (email/password hash, orders array)
   - On order: save to localStorage orders, send EmailJS (free) to your email
   - "My Orders": show user orders list if logged in
   - Login: check credentials, load orders
   - No real backend; local/persists per browser

2. **New JS Features:**
   - User auth functions (register, login, logout)
   - Orders storage per user
   - EmailJS integration (signup at emailjs.com free)

**Dependent Files:** None (single file)

**Followup steps:**
- User approves → create updated index.html
- Signup EmailJS (free): get service/public keys
- Test login/order/email

Proceed with plan?
