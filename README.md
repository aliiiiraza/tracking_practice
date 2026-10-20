# Practice Websites (clean - tracking code nahi hai)

Pages: index, shop, order-success, leads, thank-you

Deploy: GitHub repo me sab files root me upload -> Vercel me import -> Framework "Other" -> Deploy.

Tracking ke liye useful hooks:
- Shop: `.add-to-cart-btn`, `#checkout-btn`, `#continue-payment-btn`, `#place-order-btn`, `#buy-now-btn`, search form `#searchForm`
- Purchase: `/order-success` page (URL me order_id aur value; poora order sessionStorage `tm_last_order` me)
- Leads: form `#leadForm`, submit `#form-submit-btn`, call links `a[href^="tel:"]`, WhatsApp `#whatsapp-btn`, FAQ `#faq .q button`
- Lead conversion page: `/thank-you`
