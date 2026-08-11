# QR Code Generator - User Guide

## Overview
A comprehensive QR code generator built with Vue 3 that supports generating QR codes for multiple types of data including URLs, text, contact information, social media, and more.

## Features

### 📱 Supported QR Code Types

1. **🌐 URL** - Generate QR codes for website URLs
   - Example: `https://example.com`

2. **📝 Text** - Encode any plain text
   - Supports long text content

3. **✉️ Email** - Create QR codes that open email compose
   - Email address required
   - Optional: Subject and message body
   - Example: `mailto:user@example.com?subject=Hello&body=Message`

4. **📱 Phone** - Call QR codes
   - Phone number with country code
   - Example: `tel:+1234567890`

5. **💬 SMS** - Text message QR codes
   - Phone number required
   - Optional: Pre-filled message
   - Example: `sms:+1234567890?body=Message`

6. **💬 WhatsApp** - WhatsApp contact QR codes
   - Phone number with country code
   - Optional: Pre-filled message
   - Links directly to WhatsApp

7. **👤 Facebook** - Facebook profile links
   - Enter profile URL or ID
   - Example: `https://facebook.com/username`

8. **📸 Instagram** - Instagram account links
   - Enter username without @
   - Links to Instagram profile

9. **🎥 YouTube** - YouTube video links
   - Full YouTube URL
   - Example: `https://youtube.com/watch?v=...`

10. **☁️ Google Drive** - Shareable Drive links
    - Paste your shareable Google Drive URL
    - Great for file sharing

11. **🆔 vCard** - Contact card (digital business card)
    - Name
    - Phone number
    - Email
    - Organization/Company
    - Website
    - Generates complete vCard format for contact import

## Customization Options

### Size Selection
Choose from predefined sizes:
- 100×100 pixels
- 150×150 pixels
- 200×200 pixels (default)
- 300×300 pixels

### Color Customization
- **Dark Color** - QR code pattern color (default: black)
- **Light Color** - Background color (default: white)
- Use color picker to customize

## Actions

### 📥 Download
- Downloads QR code as PNG image
- Filename includes timestamp for easy identification

### 📋 Copy
- Copies the encoded data to clipboard
- Useful for sharing or storing the data

### 🗑️ Clear
- Resets all form fields
- Removes generated QR code

## How to Use

1. **Select a QR Type** - Choose from the type buttons at the top
2. **Fill in Details** - Enter required information based on type selected
3. **Customize** - Select size and colors if desired
4. **View Preview** - QR code appears automatically in real-time
5. **Download/Copy** - Use action buttons to save or copy the QR code

## Real-Time Generation
- QR code updates automatically as you type
- See results instantly without clicking a button
- High error correction level ensures code works even if partially damaged

## Error Handling
- Clear error messages if QR generation fails
- Validation for required fields
- User-friendly notifications

## Technical Details

- **Library**: qrcode.js (v1.0.0)
- **Framework**: Vue 3 (standalone build)
- **Error Correction Level**: High (supports up to 30% damage)
- **Output Format**: PNG image for download

## Tips

1. **For Social Media**: Use full URLs for best compatibility
2. **For Contact Cards**: Fill all vCard fields for complete business cards
3. **For Text**: Limit very long text as it may create complex QR codes
4. **Color Choice**: Ensure good contrast between dark and light colors
5. **Size**: Larger QR codes are easier to scan at distance

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers

## File Location
`qr-code-generator.html`

Simply open in any browser - no installation required!
