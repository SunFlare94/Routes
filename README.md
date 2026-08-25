# Routes — Desktop Offline Map Viewer

A lightweight Windows desktop application for viewing offline maps with route planning, navigation controls, and a simple dark interface.

Routes is designed for users who want to view offline map data on a Windows PC without requiring an internet connection while using the map files supported by the application.

## Download

Download the latest release of **Routes** from this repository.

> **Note:** Routes is currently provided as a Windows `.exe` application.

## Features

- Offline map viewing
- Route planning
- Map navigation and zooming
- Pan and rotate the map
- Distance measurement
- Waypoint support
- Map reset controls
- Dark-map viewing
- Multiple offline map files can be loaded
- No additional software installation required
- Simple standalone Windows application

## System Requirements

- **Windows 10 or later (64-bit)**
- **OpenGL 4.0+ compatible GPU** with updated drivers
- Internet connection is **not required for offline map viewing**
- No additional software is required — everything needed by the application is bundled

## Map Files

Routes uses offline `.obf` map files.

You can obtain `.obf` map files from:

- [OsmAnd](https://osmand.net/)
- OsmAnd-compatible map exports

### How to add map files

1. Download the required `.obf` map files.
2. Open the folder containing `Routes.exe`.
3. Place the `.obf` files inside the `obf files` folder.
4. You can place multiple `.obf` files in the folder.
5. Start `Routes.exe`.
6. Routes will automatically detect the available map files.

> **Important:** Routes does not provide the map data itself. You are responsible for obtaining and using map files in accordance with their applicable terms and licenses.

## How to Use

1. Double-click `Routes.exe`.
2. The application automatically loads the available maps from the `obf files` folder.
3. Use the mouse and keyboard controls below to navigate the map.

## Controls

| Action | Control |
|---|---|
| Zoom | Mouse wheel |
| Pan | Left-click and drag |
| Rotate map | Right-click and drag |
| Measure distance | `M` key |
| Add waypoint | `N` key |
| Toggle dark map | `K` key |
| Reset rotation | `R` key |
| Reset map | `X` key |
| Clear distance tool | `Esc` key |
| Clear points | `Delete` key |

## Trial & License

Routes includes a **10-day free trial**.

After the trial period expires, you must purchase a license to continue using Routes.

### License Price

**$5 USD — one-time payment**

The license is intended for use on **one computer** and the generated license key is tied to your machine.

## How to Purchase a License

### 1. Start the Application

Download and run `Routes.exe`.

During the trial period, you can use the application normally.

### 2. Get Your Machine ID

After the trial expires, open the license section in Routes:

**Help → Enter License**

Your application will display your **Machine ID**.

Copy this Machine ID.

### 3. Pay $5 USD

Use the Razorpay payment link below:

**Purchase Routes License — $5 USD**

https://rzp.io/rzp/iDO2p0X

### 4. Send Your Machine ID

After completing the payment, provide your **Machine ID** to the developer so that a unique license key can be generated for your computer.

### 5. Receive Your License Key

A license key will be generated for your Machine ID.

### 6. Enter Your License Key

Open:

**Help → Enter License**

Paste the license key into the license field and activate Routes.

> **Important:** Your license key is tied to your machine. If you change computers, a new license may be required.

## Purchase / Support

If you enjoy Routes and would like to support its continued development, you can use the payment options below.

### GitHub Sponsors

You can support the project through GitHub Sponsors:

https://github.com/sponsors/SunFlare94

### Razorpay — $5 License Payment Link

Purchase a Routes license for the exact **$5 USD** license price using the Razorpay Payment Link:

**[Pay $5 USD for a Routes License](https://rzp.io/rzp/iDO2p0X)**

After completing the payment, please provide your **Machine ID** so that a unique license key can be generated for your computer.

### Pay for a Routes License via UPI — ₹476.66

Indian users can also purchase a Routes license using the fixed-amount Razorpay UPI QR code below.

The license QR code is configured for **₹476.66 INR**.

Scan the QR code using **Google Pay, PhonePe, Paytm, or another supported UPI application**.

![Routes License - Razorpay UPI QR Code](QrCode1.jpeg)

> **License payment:** This QR code is for the Routes license and charges the fixed INR amount shown above. The $5 USD option is available through the Razorpay Payment Link.

### Casual Support / Donation

If you would like to support the development of Routes **without purchasing a license**, you can make a casual contribution using the original Razorpay UPI QR code below.

This QR code is for **optional donations/support** and is separate from the fixed-price Routes license payment.

![Casual Support - Razorpay UPI QR Code](QrCode.jpeg)

Thank you for supporting the continued development of Routes!

## Screenshots

### Main Map View

![Routes Main Map View](Screenshot%201.png)

### Map Navigation

![Routes Map Navigation](Screenshot%202.png)

### Application Interface

![Routes Application Interface](Screenshot%203.png)

## Technical Details

- **Platform:** Windows 10+ (64-bit)
- **Graphics:** OpenGL 4.0+
- **Map engine:** OsmAnd Core
- **UI:** PySide6 (Qt)
- **Map format:** `.obf`
- **Application type:** Standalone Windows desktop application
- **Distribution:** Windows executable (`Routes.exe`)

## Privacy

Routes is designed for offline map viewing.

- No account is required to use the application during the trial.
- Offline map viewing does not require an internet connection.
- Map data is loaded locally from the `obf files` folder.
- Routes does not provide or redistribute third-party map data.

## License

This project is distributed as a paid Windows application with a **10-day free trial**.

The application, its executable files, source code (if any), branding, and associated assets remain the property of the developer unless otherwise stated.

You may not redistribute, resell, modify, reverse engineer, or commercially exploit the application without permission from the developer.

Third-party components and map data may have their own licenses and terms.

## Developer

**Mukul Pramanik (SunFlare94)**

Platform: Windows 10+ (64-bit)

## Support Development

If Routes is useful to you, consider supporting its continued development.

### Purchase a License

- [Razorpay — Purchase $5 Routes License](https://rzp.io/rzp/iDO2p0X)
- **UPI License QR:** `QrCode1.jpeg` — fixed **₹476.66 INR**

### Casual Donation

If you simply want to support the project without purchasing a license, you can use the original casual-support QR code:

![Casual Support QR Code](QrCode.jpeg)

You can also support the project through [GitHub Sponsors](https://github.com/sponsors/SunFlare94).

Thank you for supporting independent software development!
