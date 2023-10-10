# ADR 1:  Native, Web, or Hybrid App:
The app's design is influenced by the need for location tracking, real-time order status updates, seamless and secure payment gateway integration, a user-friendly interface which is easy to navigate.

## Decision
We will develop a native app for both Android and iOS Devices.

## Rationale
Choosing a native app approach comes after considering the important features the application demands. Native apps provide the best performance as they can directly access the device hardware. Their capability to use device-specific features like GPS is unmatched compared to web or hybrid apps. Moreover, native development ensures adherence to platform-specific guidelines that will lead to a more intuitive user experience. While development might be longer, as separate codebases are needed for iOS and Android, the overall user satisfaction and app responsiveness justify the choice.

## Status
Accepted

## Consequences
- Superior user experience
- Faster performance
- Access to device-specific features (GPS)
- Separate development for iOS and Android will be required, leading to higher costs and longer development time.