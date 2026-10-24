# EuroFour
## Overview
This software changes the ATC24 radar creation community because why spend time trying to compete against one of the most realistic radar software systems if it already exists and we can just use it instead?

EuroFour is a community project created by Shayzee, which consists of EuroFour Bridge, a desktop application that fetches and updates data from the ATC24 server provided by 24data in real time, converts it into FSD format, and populates it into EuroScope.

EuroFour Plugin, a handmade plug-in that creates a dynamic ATC24 METAR list directly in EuroScope and automatically populates it with all the airports that your connected position is responsible for in EuroScope. For each airport, it displays the active ATIS letter and METAR.

EuroFour Central, a central server whose hosting costs are covered by Shayzee. It collects and stores about 1,000 flight plans a day, provided by 24data directly from the `#flight-plans` channel in the ATC24 Discord server. It runs 24/7 to make sure all controllers have up-to-date flight plans.

EuroFour Admin, a private interface just for me, allowing me to answer any questions that users send or respond to bug reports submitted via the "Report a bug / Get Help" system implemented directly in EuroFour Bridge. I will gladly respond to questions via email.

## Installation
Unzip the compressed (zipped) "EuroFour vX.X.X" folder and follow the installation steps as described in the "README.md" file in the root folder.

**IMPORTANT:** Make sure to read the entire installation section in the "README.md" file in the root folder, or else it might not work as intended.

## Features
- Real-time aircraft updates (position, callsign, altitude, speed, heading)
- Flight plan syncing
- Active controllers list
- Up-to-date ATIS and METAR information in the ATC24 METAR list created by EuroFour Plugin
- Functional "Get ATIS" requests from artificially created `_ATIS` controllers

By using EuroScope as the radar software, it has all the features that EuroScope offers. For example:
- Tag cleared altitude selection
- Tag assigned speed selection
- Tag assigned heading selection
- Tag waypoint direct selection
- Tag sector exit altitude selection
- Active airport/runway selector
- Flight plan setting dialog
- Leader lines
- History trails
- Transition altitude selection
- Distance tool
- Vectoring tool
- Departure list
- Arrival list
- Aircraft list
- Flight plan list
- Controller list
- Conflict alert system
- Tag editor
- And more...

## Requirements
- Operating system: Tested on Windows 11; compatibility with other operating systems is not guaranteed.
- EuroScope: Version 3.2.8 or newer (recommended to use the latest version)
- Internet connection

## Support
If you encounter any problems, please don't hesitate to use my "Report a bug / Get Help" system built into EuroFour Bridge whenever possible.

Alternatively, you can contact me via email at eurofour.support@gmail.com.

## Disclaimer
EuroFour is a community project and is not affiliated with ATC24, 24data, or EuroScope in any way.

This software is provided without any warranties of any kind, to the extent permitted by applicable law. Use of this software is at your own risk.

## Credits
**24SKY by protekti**

Many thanks to protekti for creating the `ATC24-Sector-File.sct` sector file for EuroScope, which EuroFour currently relies on, as it doesn't have its own sector file YET.

24SKY GitHub: https://github.com/BedsAreDragons/24SKY

## License
Copyright © 2026 EuroFour. All rights reserved.

Unless expressly authorized by Shayzee, no part of the EuroFour software may be copied, modified, redistributed, sublicensed, or incorporated into any other software.

EuroFour is provided for personal use only, unless expressly authorized otherwise by Shayzee.
