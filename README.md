# Ola Range Booster (Android starter project)

Target vehicle: Ola S1 Pro+ Gen 3, 5.2 kWh.

## Included in v1
- Manual remaining-range estimate from distance travelled and battery percentage used.
- BLE scanner to discover nearby Bluetooth Low Energy devices.
- Basic safe range-driving guidance.

## Important limitations
- This version does **not** connect to Ola's proprietary telemetry service, read live BMS/MCU values, or write tuning values.
- BLE discovery is not the same as pairing or a supported scooter data connection.
- No BMS protections, speed limits, motor limits, or firmware are modified.

## Build APK
1. Open this folder in Android Studio (Giraffe or newer; preferably current stable).
2. Allow Gradle to download Android Gradle Plugin 8.7.3 and Android SDK platform 35.
3. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Install the generated `app/build/outputs/apk/debug/app-debug.apk` on your Android phone.

Minimum Android: 8.0 (API 26). Bluetooth scan requires runtime permissions.
