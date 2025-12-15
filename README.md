# E-commerce Product Photo Processor

A Python script for automating product photo editing:
- Automatic background removal (using rembg)
- Resize to standard size (e.g., 1000x1000 with white background)
- Add logo watermark

Perfect for Shopify/Amazon sellers processing bulk images.

## Demo
### Before
![Before](photos/example_before.jpg)

### After
![After](processed/example_after.jpg)

## How to Use
1. Install dependencies: `pip install pillow rembg`
2. Place images in `photos/` folder
3. Add your `logo.png`
4. Run: `python product_processor.py`

## Technologies
- Python
- Pillow
- rembg (AI-based)

Feel free to fork and contribute!
