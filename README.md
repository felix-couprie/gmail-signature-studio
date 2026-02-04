# SigMail Studio 🚀

The ultimate signature generator for disruptive email thought leadership.

## What is this?

A single-file HTML tool that generates Gmail-friendly email signatures using HTML tables (because divs are so 2010). Perfect for when you need to look professional while maintaining your startup founder aesthetic.

## Features

- 📧 **Gmail-optimized** - Uses table layouts that actually work in email clients
- 🖼️ **Image upload** - Convert images to base64 (max 500KB) for embedded signatures
- 🎨 **Live preview** - See your signature in real-time with white background
- 🌐 **Bilingual** - FR/EN support with startup-themed placeholders
- ✨ **Customizable** - Control every field: name, title, location, email, phone, motto, links
- 📋 **One-click copy** - Copy HTML and paste directly into Gmail
- 🦄 **SaaS vibes** - Pre-filled with hilarious startup culture examples

## How to use

1. **Open the file** - Just open `signature-generator.html` in Chrome or any modern browser
2. **Fill in your details** - Or click "Fill with SaaS vibes 🦄" for inspiration
3. **Upload an image** (optional) - Converts to base64 automatically (JPG, PNG, GIF, SVG supported)
4. **Copy from preview** - The white preview box shows exactly what your signature will look like
5. **Paste into Gmail** - Settings → General → Signature → Paste

## Configuration options

- **Image URL or Upload** - Use a public HTTPS URL or upload a file (auto-converts to base64)
- **Image size & radius** - Control dimensions and corner rounding
- **Personal info** - First name, last name, title, location, email, phone, motto
- **Toggle visibility** - Show/hide any field with checkboxes
- **Links** - Up to 3 clickable links (with "open in new tab" option)
- **Custom HTML** - Advanced mode: paste your own HTML for the right side

## Technical details

- **Single file** - No dependencies, no build step, no npm hell
- **Works offline** - Just HTML, CSS, and vanilla JavaScript
- **Base64 encoding** - Images embedded directly in the signature
- **500KB image limit** - Keeps email size reasonable
- **Table-based layout** - Image left, content right (the way email clients like it)

## Pro tips

- Use base64 images instead of URLs for Gmail (more reliable)
- Keep your image under 200KB for faster email loading
- Phone numbers are plain text (not clickable) as intended
- Test your signature by sending yourself an email
- The preview has a white background to match email clients

## Placeholders examples

Because life's too short for boring email signatures:

- **Chad Synergetic** - Chief Vibes Officer · Growth Hacking Ninja 🦄
- **Location** - SF Bay Area (Remote-first, WFH Tuesdays)
- **Motto** - "Disrupting the disruption. Let's synergize! 🚀"
- **Links** - LinkedIn (Thought Leadership™), My SaaS (pre-seed, hockey stick growth)

## Browser compatibility

Works in all modern browsers. Tested in:
- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅

## License

Do whatever you want with it. Ship it. Fork it. Disrupt it. Synergize it. 

---

Built with HTML tables and startup vibes. No VCs were harmed in the making of this tool.
