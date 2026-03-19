# Geolocation AbstractAPI

[![Downloads](https://img.shields.io/github/downloads/aimms/abstract-api/total?style=for-the-badge&logo=github&labelColor=000081&color=1847c9)](https://github.com/aimms/abstract-api/releases)
![AIMMS Version](https://img.shields.io/badge/AIMMS-24.5-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/WebUI-24.10.3.3-white?style=for-the-badge&labelColor=009B00&color=00D400)
![DEX Version](https://img.shields.io/badge/DEX-24.4.1.2-white?style=for-the-badge&labelColor=009B00&color=00D400)


This repository contains a functional AIMMS application that serves as an **IP Locator**. It demonstrates how to integrate external REST services to translate any IP address into precise geographical coordinates (Latitude and Longitude).

## 🎯 Business Problem

Identifying the geographical origin of an IP address is crucial for logistics, cybersecurity, and localized user experiences. This model demonstrates:
- **Real-time Geocoding:** Translating abstract network data into physical locations.
- **REST API Integration:** Handling the full lifecycle of a web request (Prepare, Call, and Handle Response).
- **Data Visualization:** Mapping coordinates instantly using the AIMMS WebUI Map Widget.

## 📖 How to Use This Example

To understand the underlying implementation logic of the API calls used in this project, we recommend reading the detailed guide:

👉 **[Read the Full Article: Geolocation with AbstractAPI](https://how-to.aimms.com/Articles/562/562-geolocation-abstractapi.html)**

### Prerequisites
- **AIMMS:** You will need AIMMS 24.5 or higher. [Download the Free Academic Edition](https://www.aimms.com/english/developers/downloads/free-academic-license/).
- **API Key:** A free API key from [AbstractAPI](https://app.abstractapi.com/api/ip-geolocation/tester) is required to authenticate requests.

### Technical Highlights
- **Asynchronous REST Calls:** Seamlessly communicates with external servers without locking the user interface.
- **Custom UI Styling:** Features advanced CSS modifications for a branded experience, including custom dialog titles and themed workflows.
- **Map Integration:** Uses the Map Widget with custom annotations to visualize the pinpointed IP locations.

## 🚀 Getting Started

1. **Download the Release:** Go to the [Releases](https://github.com/aimms/abstract-api/releases) page and download the `.zip` file.
2. **Obtain API Key:** Sign up at AbstractAPI and copy your unique access token.
3. **Open & Configure:** Launch the `.aimms` project and enter your API key when prompted.
4. **Locate:** Use the "Find IP" page and press the **GeoLocate** button to see the magic happen!

## 🤝 Support & Feedback

This example is maintained by the **AIMMS User Support Team**.
- Found an issue? [Open an issue](https://github.com/aimms/abstract-api/issues).
- Questions? Reach out via the [AIMMS Community](https://community.aimms.com).

---
*Maintained by the AIMMS User Support Team. We optimize the way you build optimization.*
