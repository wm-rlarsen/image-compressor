# Image Compressor

A single-file browser tool for converting batches of images to smaller JPEGs. Open `Image Batch Converter.html` in Microsoft Edge or Google Chrome. No installation is required, and images are processed locally in your browser.

## Use

Download image-compressor.html and run it in your browser.  This tool is a single file that requires no setup or installation.

1. Choose a folder or select multiple image files. Images inside subfolders are ignored.
2. Choose a quality preset, or select **Advanced** to set JPEG quality and optionally try to meet a target file size.
3. Keep the original dimensions, set maximum dimensions, or scale images to a percentage of their original size. Choose a background color for transparent images.
4. Optionally rename files with a prefix and date format. The tool uses the photo’s EXIF capture date when available, and the file’s modified date otherwise. Duplicate names receive a numbered suffix.
5. Download the JPEGs in a ZIP, or choose an output folder to save individual files.

## Supported formats

JPG/JPEG, PNG, WebP, and BMP. HEIC/HEIF is not yet supported.

Unreadable and unsupported files are skipped and listed in the completion summary. Original files are left unchanged.
