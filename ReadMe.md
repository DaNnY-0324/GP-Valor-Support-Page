# VL 100 Support Guide

This is a comprehensive support guide for the VL 100 device. It contains step-by-step instructions for setting up, troubleshooting, and handling transactions with the device. This guide is designed to be responsive and user-friendly, with a light and dark theme toggle, search functionality, and image gallery with modal display for detailed guides.

![VL 100 Guide Screenshot](https://github.com/user-attachments/assets/2a1b2845-57ee-48aa-ac6e-4eb2effadf4e)


## Features

- **Theme Toggle**: Switch between light and dark modes for better readability.
- **Scroll to Top Button**: A back-to-top button that appears after scrolling down.
- **Image Gallery**: Clickable thumbnail images that expand into a modal for better viewing.
- **Responsive Layout**: Adjusts well on different screen sizes.
- **Search Functionality**: Easily search for support articles through the search bar.
- **Contact Form**: A simple form for contacting support.

## Sections Included

1. **VL 100 Quick Start**: Basic steps to set up the device for use.
2. **Capture Preauth (Credit)**: Guide for handling preauth credit transactions.
3. **Pre-Sale Ticket**: Instructions on how to print a pre-sale ticket.
4. **Connect to WiFi**: Step-by-step guide for connecting the device to a WiFi network.
5. **Favorites Menu**: A detailed list of options available in the Favorites menu, including `Reprint Receipt`, `Settlement`, `Tip Adjust`, etc.
6. **Transactions**: A breakdown of different types of transactions such as `Card Sale`, `Credit Sale`, `Debit Sale`, and more.
7. **Terminal Guide**: A visual guide showing the VL 100 terminal’s key components and buttons.

## How to Use

### 1. Theme Toggle
At the top right of the webpage, there is a theme toggle switch. It allows you to switch between light and dark modes. The preference is saved in local storage so that your choice persists across page reloads.

### 2. Scroll to Top
Once you scroll down the page, a "back-to-top" button will appear at the bottom right corner. Clicking this button will take you back to the top of the page.

### 3. Image Modal
Clicking on any of the thumbnail images in the guide opens a larger version in a modal window. To close the modal, simply click on the close (`×`) button.

### 4. Contact Form
At the bottom of the page, a contact form allows users to reach out for support. You can fill in your name, email, and a message, and click the **Submit** button to send your inquiry.

## Project Structure

```bash
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # Stylesheet for the guide
└── js/
    └── script.js           # JavaScript for interactivity (theme toggle, modal, etc.)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vl100-support-guide.git
   ```

2. Open the `index.html` file in any web browser.

## Technologies Used

- **HTML5**: For the structure of the page.
- **CSS3**: For styling the layout, modal, and themes.
- **JavaScript**: For interactivity (theme toggle, image modal, and back-to-top button).
- **FontAwesome**: For icons used in the page (e.g., back-to-top arrow).
