# FindTrace

GPS track recorder & city explorer for iOS.

FindTrace automatically records your GPS tracks in the background and lights up every city you visit.

## Features

- **Background GPS tracking** — records your daily routes without opening the app
- **Speed-colored tracks** — different colors for walking, running, cycling, and driving
- **City light-up** — automatically lights up cities where you stay for 30+ minutes
- **Footprint map** — see all the places you've been on a single map
- **Daily history** — browse past tracks by date
- **Battery optimized** — switches to low-power mode when stationary
- **Privacy first** — all data stored locally on your device, never uploaded

## Screenshots

<!-- Add screenshots here -->

## Requirements

- iOS 17.0+
- Xcode 15+

## Build

1. Clone the repository
2. Open `FindTrace.xcodeproj`
3. Select your Team in Signing & Capabilities
4. Build and run (Cmd+R)

## Tech Stack

- SwiftUI + SwiftData + MapKit
- MVVM architecture
- Background location tracking (no blue status bar)
- WGS-84 → GCJ-02 coordinate conversion for China maps
- Geofence-based app relaunch after termination

## Privacy

All location data is stored locally on your device. No data is ever transmitted to any server. See [Privacy Policy](PRIVACY.md).

## License

MIT License. See [LICENSE](LICENSE) for details.
