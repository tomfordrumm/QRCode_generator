# QR Code Generator

This project provides a simple QR code generator with extensive styling options based on [qr-code-styling](https://github.com/kozakdenys/qr-code-styling).

## Usage

Open `index.html` in any modern browser. All required libraries are loaded via CDN, so no build step is needed.

The settings panel lets you enter data, upload a logo, choose width and height, and optionally expand sections to tweak colors and styles. On mobile screens the QR preview appears above the settings panel, while on desktop the layout switches to a two-column view. The preview area also includes a button to download the QR code as PNG or SVG.

The interface is built with Tailwind CSS and works on both desktop and mobile screens.

The preview size remains constant even when adjusting width and height fields, which only affect the downloaded image. Each setting label includes a tooltip explaining its purpose.
