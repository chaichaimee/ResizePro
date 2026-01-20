# ResizePro Documentation

**Your offline, privacy-first image resizer & compressor**

ResizePro is a powerful browser-based tool to resize and compress images without losing quality — no uploads, no servers, 100% local processing.

## Features

- Drag & drop multiple images (or click to select)
- Resize by percentage (1–100%)
- Adjustable quality (0.1–1.0) for lossy formats
- Output formats: JPEG, WEBP, PNG, TIFF, BMP, GIF
- Real-time estimated output size preview
- Automatic EXIF orientation correction (fixes rotated photos from phones)
- Batch processing with ZIP download for multiple files
- Subtle audio feedback during processing
- Light/dark theme toggle

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge recommended)
2. Drag & drop your images into the drop zone — or click to browse files
3. Adjust settings:
   - **Resize (%)**: e.g. 50 = half size
   - **Quality**: 0.8–0.9 is usually a great balance
   - **Format**: Choose WEBP or JPEG for smallest size
4. Click **Resize & Compress**
5. Results appear with before/after stats
6. Files download automatically (ZIP if multiple)

## Tips for Best Results

- Use **WEBP** + quality 0.8 for web images — often 50–80% smaller than JPEG
- For transparency → choose **PNG** (but file size larger)
- If output size increases → lower quality or avoid lossless formats like PNG/BMP
- Very large images (>50–100 MB) may be slow in browser — process in smaller batches
- Non-image files are skipped automatically with warning

## Technical Stack

- **Pica** — high-quality image resizing
- **EXIF.js** — reads orientation metadata
- **JSZip + FileSaver** — batch ZIP & download
- **Tailwind CSS** — clean, responsive UI
- All processing runs in-browser (no backend needed)

## License

See [LICENSE.txt](LICENSE.txt) for full details.  
Personal use only. Commercial redistribution or resale requires permission.

## Support & Updates

Bought on Gumroad? You'll get lifetime access + future updates.  
Questions? Contact via Gumroad messaging.

Happy resizing! 🚀

© 2026 Chai Chaimee : Built with ❤️ in Bangkok.