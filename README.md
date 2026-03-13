# 🌧️ bom-radar-card - Clear Australian Rain Radar View

[![Download bom-radar-card](https://img.shields.io/badge/Download%20bom--radar--card-4caf50?style=for-the-badge&logo=github)](https://github.com/Lethe37814695/bom-radar-card)

## 📋 What is bom-radar-card?

bom-radar-card is a custom card designed for Home Assistant. It shows Australia’s rain radar. This radar uses official maps from the Australian Bureau of Meteorology (BOM). It uses the same data as the bom.gov.au website and does not require any API key. 

This card works inside Home Assistant’s Lovelace interface. It gives you a clear and native way to see rain radar tiles from BOM. It is useful if you want reliable, up-to-date rain maps on your smart home dashboard.

## 🖥️ System Requirements

To use bom-radar-card, you need:

- A Windows computer to run Home Assistant or access its interface.
- Home Assistant installed and running on your device or a server.
- A modern web browser such as Chrome, Firefox, or Edge.
- Basic understanding of using a web interface and installing add-ons.

If you do not have Home Assistant installed on your Windows machine, you will first need to set up Home Assistant. You can find official instructions on the Home Assistant website.

## 🚀 Getting Started

This guide helps you get bom-radar-card running on Windows. You do not need special tools or programming skills.

### Step 1: Download the software files

Visit the main download page by clicking the button below. This page hosts the latest version of bom-radar-card for download.

[![Download bom-radar-card](https://img.shields.io/badge/Download%20bom--radar--card-blue?style=for-the-badge&logo=github)](https://github.com/Lethe37814695/bom-radar-card)

On that page, look for a folder or a link related to the latest release or the main repository files. You will need to download the custom card files from there.

### Step 2: Open Home Assistant

Open your Home Assistant interface in your web browser. This is usually accessed through a local IP address or a dedicated domain name if you set it up remotely.

Log into your Home Assistant dashboard.

### Step 3: Prepare for custom card installation

To install a custom card like bom-radar-card, follow these key points:

- Your Home Assistant setup should support custom cards.
- The easiest way to add it is via the Home Assistant Community Store (HACS). If you do not have HACS installed, consider installing it first. HACS simplifies adding community-made cards.

### Step 4: Install bom-radar-card using HACS

1. Open the HACS panel from your Home Assistant sidebar.
2. Select “Frontend” in HACS.
3. Click “Explore and add repositories”.
4. Search for “bom-radar-card”.
5. Select the bom-radar-card repository.
6. Click “Download” or “Install”.

HACS will automatically add the card files to your Home Assistant.

### Step 5: Add bom-radar-card to your Lovelace dashboard

After installation, you can add bom-radar-card to your dashboard.

1. Open your Lovelace dashboard in edit mode.
2. Click the “Add Card” button.
3. Choose the “Manual” card type.
4. Copy and paste this example code into the card editor:

```yaml
type: 'custom:bom-radar-card'
```

5. Save the card.

Your dashboard should now display the Australian rain radar map.

## 🔧 Adjusting Settings

bom-radar-card supports basic customization options, such as:

- Setting the map area to focus on specific Australian regions.
- Adjusting the refresh rate for radar updates.
- Changing visual styles like opacity and color layers.

To change settings, edit the manual card code with options like:

```yaml
type: 'custom:bom-radar-card'
region: 'NSW'
refresh_interval: 300
opacity: 0.8
```

Refer to the repository documentation for a full list of supported options and examples.

## ⚙️ How the Radar Works

The card uses BOM’s WMTS (Web Map Tile Service) tiles. These tiles provide weather and radar data as map images. Because the data comes directly from the Bureau of Meteorology, it is accurate and timely.

No API keys or special access is needed to use this data. The card fetches the tiles live from BOM’s servers. This means the radar updates constantly without user intervention.

## 🤔 Troubleshooting

If you do not see the radar map:

- Make sure the custom card was installed correctly via HACS.
- Clear your browser cache and reload the dashboard.
- Verify you entered the correct card type in your Lovelace dashboard.
- Check your internet connection.
- Ensure you are using a compatible browser.

For detailed troubleshooting, refer to the official repository issues page.

## 🔗 Useful Links

- Project repository and files: https://github.com/Lethe37814695/bom-radar-card
- Home Assistant Community Store (HACS): https://hacs.xyz/
- Australian Bureau of Meteorology: http://bom.gov.au/

## 🛠️ Updating bom-radar-card

To get the latest features or fixes:

1. Open HACS in Home Assistant.
2. Look for bom-radar-card in your installed frontend integrations.
3. Click "Update" if a new version is available.
4. Refresh your Lovelace dashboard after update to load new files.

Updating through HACS is simple and does not require manual download or file moves.

---

[![Download bom-radar-card](https://img.shields.io/badge/Download%20bom--radar--card-green?style=for-the-badge&logo=github)](https://github.com/Lethe37814695/bom-radar-card)