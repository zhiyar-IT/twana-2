# پەراوگەو چامەمەنی توانا ٢ - Website

## Description
This is the official website for پەراوگەو چامەمەنی توانا ٢, a professional stationery and print shop. The website is designed to attract customers with a modern, colorful, and responsive layout. It showcases the shop’s services, contact information, social media links, and includes a secure way for the owner to update the shop’s QR code.

---

## Features

- **Modern, Responsive Design:** Works on all devices and screen sizes.
- **Services Section:** Lists all the jobs and services the shop can handle.
- **Contact Information:** Address and phone numbers are clearly displayed.
- **Social Media Links:** Quick access to Facebook, Instagram, Snapchat, Telegram, and WhatsApp.
- **Owner QR Code Management:**  
  - Only the owner (with password) can update the QR code image.
  - QR code is stored in the browser’s local storage and persists after refresh.
- **RTL (Right-to-Left) Layout:** Fully supports Kurdish language and script.

---

## How to Use

1. **Open the Website:**  
   Open `index.htmltwana2.html` in your browser.

2. **Update QR Code (Owner Only):**
   - Click on the QR code image in the footer.
   - Enter the owner password (default: `twana2owner`).
   - The "بارکۆدی نوێ زیاد بکە" button will appear.
   - Click the button and select your new QR code image.
   - The image will be saved locally and shown automatically on future visits.

3. **Change Owner Password:**  
   Edit the `OWNER_PASS` variable in the `<script>` section at the bottom of the HTML file.

4. **Update Social Links:**  
   Edit the `<a href="...">` tags in the footer and hero sections to use your real social media URLs.

---

## Customization

- **Colors & Styles:**  
  Edit the CSS variables in the `<style>` section at the top of the HTML file.
- **Services:**  
  Update the `.jobs-grid` section to add, remove, or rename services.
- **QR Code:**  
  You can generate a QR code for your website using [https://www.qr-code-generator.com/](https://www.qr-code-generator.com/) and upload it as needed.

---

## Notes

- The QR code image is stored in the browser’s local storage. If you clear your browser data, you will need to re-upload the QR code.
- For higher security, consider a server-side solution for QR code management.
- The website is static and does not require a backend.

---

## License

This project is for the exclusive use of پەراوگەو چامەمەنی توانا ٢.