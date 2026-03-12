# RenalCare Premium - Healthcare Booking Platform

A complete healthcare booking platform offering dialysis, chronic disease management, health screenings, and home care services for the Kenyan market.



## 📱 Pages Included

1. **index.html** - Landing page with service overview
2. **login.html** - User authentication (login/signup)
3. **app.html** - Main booking interface with 12 services
4. **payment.html** - Multi-payment gateway (M-PESA, Card, Insurance, Bank)

## 🏥 Services Offered

### Dialysis Care
- Premium Dialysis (KES 17,000)
- Standard Dialysis (KES 14,000)

### Health Screenings
- Diabetes Screening (KES 3,500)
- Hypertension Screening (KES 2,500)
- Comprehensive Health Checkup (KES 15,000)

### Chronic Condition Management
- Diabetes Management (KES 12,000/month)
- Heart Health Monitoring (KES 10,000/month)
- Elderly Care Package (KES 18,000/month)

### Additional Services
- Home Nursing Care (KES 5,000)
- Home Lab Tests (From KES 2,500)
- General Health Monitoring (KES 8,000/month)
- Virtual Doctor Consultation (KES 3,000)

## 💳 Payment Methods

- **M-PESA** - Mobile money payments
- **Credit/Debit Cards** - Visa, Mastercard
- **Insurance** - NHIF, AAR, Britam, Jubilee, Madison, APA
- **Bank Transfer** - Direct bank payments

`

## 🛠️ Technology Stack

- **Frontend**: React 18 (via CDN)
- **Styling**: Tailwind CSS
- **Icons**: Custom SVG icons
- **No Build Process**: Works directly in browser

## 📂 Project Structure

```
renalcare-app/
├── index.html          # Landing page
├── login.html          # Authentication
├── app.html           # Service booking
├── payment.html       # Payment processing
├── README.md          # This file
└── .gitignore         # Git ignore file
```

## 🎨 Customization

### Update Prices
Edit service arrays in each HTML file (search for `price:` or `amount:`).

### Change Colors
Modify Tailwind gradient classes (e.g., `from-blue-600 to-teal-600`).

### Add Services
Add new objects to the `services` array in `app.html`.

### Update Contact Info
Search for phone numbers and emails in HTML files.

## ⚠️ Important Notes

### Demo Mode
- Payment processing is simulated (no real charges)
- M-PESA integration requires Safaricom API setup
- For production, you'll need a backend server

### Real M-PESA Integration
To enable actual M-PESA payments:
1. Register at https://developer.safaricom.co.ke
2. Get API credentials
3. Set up a backend server (Node.js/PHP/Python)
4. Implement Lipa Na M-PESA Online API

### Recommended for Production
- Use payment gateways like Pesapal, Flutterwave, or Paystack
- Add backend for user management and database
- Implement proper authentication (JWT, OAuth)
- Add SSL certificate for security

## 📱 Features

✅ Responsive design (mobile, tablet, desktop)
✅ Modern UI with gradient designs
✅ Form validation
✅ Multiple payment options
✅ Service categorization
✅ User account types (Patient/Provider)
✅ Booking confirmation flow
✅ Order summary
✅ Social login options (UI only)

## 🔒 Security Notes

- Don't store sensitive data in frontend
- Use HTTPS for production
- Implement proper backend authentication
- Validate all inputs server-side
- Use environment variables for API keys

## 📞 Support

For questions or support:
- Email: care@renalcare.co.ke
- Phone: +254 700 123 456

## 📄 License

MIT License - Free to use for your business

## 🎯 Next Steps for Production

1. Set up backend API (Firebase, Node.js, etc.)
2. Integrate real payment gateway
3. Add database (PostgreSQL, MongoDB)
4. Implement email/SMS notifications
5. Add admin dashboard
6. Set up analytics
7. Get SSL certificate
8. Custom domain setup

---

Built with ❤️ for RenalCare Premium
