# The Expo EAS Production Blueprint

A complete architecture guide, debugging manual, and configuration templates for migrating a production React Native app to **Expo Application Services (EAS)** and **Over-The-Air (OTA) Updates**.

While scaling out the Synapsis app ecosystem (specifically MyTeal), I hit every snag imaginable: silent crashes, the White Screen of Death (WSOD), poisoned OTA updates, and environment variable disconnects. 

I built this repository to open-source the exact architecture and configurations that finally worked.

## The 5-Part Dev.to Series

If you are transitioning to EAS, read this guide to save yourself days of debugging iOS console logs and Metro bundler headaches.

*   **Part 1:** [Why Use Expo EAS in the First Place? (The Honest Truth)](https://dev.to/debojitdas2003/why-use-expo-eas-in-the-first-place-the-honest-truth-26ga)
*   **Part 2:** [The Bulletproof Guide to Setting Up Expo EAS & OTA Updates (Without the Tears)](https://dev.to/debojitdas2003/the-bulletproof-guide-to-setting-up-expo-eas-ota-updates-without-the-tears-4le3)
*   **Part 3:** [How to Fix React Native EAS Build White Screens and OTA Crashes (A Complete Guide)](https://dev.to/debojitdas2003/how-to-fix-react-native-eas-build-white-screens-and-ota-crashes-a-complete-guide-2e9n)
*   **Part 4:** [Local Builds vs. EAS Cloud: When to Use Which?](https://dev.to/debojitdas2003/local-builds-vs-eas-cloud-when-to-use-which-345l)
*   **Part 5:** [How to Maximize Profit Out of EAS (And When to Buy the Subscription)](https://dev.to/debojitdas2003/how-to-maximize-profit-out-of-eas-and-when-to-buy-the-subscription-347d)

## Configuration Templates

Inside the `/templates` folder of this repository, you will find the sanitized, production-ready configuration files discussed in the series:

*   [`eas.json`](./templates/eas.json) - Properly linked cloud environments and build profiles.
*   [`app.json`](./templates/app.json) - Clean native configurations and fixed runtime versions.
*   [`.env.example`](./templates/.env.example) - The strict prefixing rules required for client-side keys.

## Build in Public
I'm documenting the entire process of building and scaling production mobile apps. 
* Read my technical deep-dives on [Dev.to](https://dev.to/debojitdas2003)
* Follow the daily journey on [LinkedIn](https://www.linkedin.com/in/debojitdas2003/)

---
*If this guide saved you a TestFlight headache, consider starring this repository!*
