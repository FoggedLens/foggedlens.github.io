---
layout: single
title: DeFlock Mobile App User Guide
permalink: /deflock-mobile-guide/
excerpt: Learn how to use our mobile app to find and report cameras
date:   2025-10-24 19:07:36 -0600
related: false

author:
  name: Bob
  bio: Creator of the DeFlock mobile app
---

## Table of Contents

- [Introduction: Why Map Surveillance?](#introduction-why-map-surveillance)
  - [What is OpenStreetMap?](#what-is-openstreetmap)
  - [What Makes DeFlock Different](#what-makes-deflock-different)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Initial Setup](#initial-setup)
  - [Connecting to OpenStreetMap](#connecting-to-openstreetmap)
  - [Understanding the Interface](#understanding-the-interface)
- [Your First Device: A Complete Walkthrough](#your-first-device-a-complete-walkthrough)
  - [Step 1: Find a Device](#step-1-find-a-device)
  - [Step 2: Add the Device](#step-2-add-the-device)
  - [Step 3: Choose a Device Profile](#step-3-choose-a-device-profile)
  - [Step 4: Add Details](#step-4-add-details)
  - [Step 5: Submit](#step-5-submit)
- [Core Features](#core-features)
  - [Understanding Pin Colors](#understanding-pin-colors)
  - [Device Types You Can Map](#device-types-you-can-map)
  - [Editing Existing Devices](#editing-existing-devices)
  - [Working Offline](#working-offline)
  - [Upload Queue Management](#upload-queue-management)
  - [Suspected Locations](#suspected-locations)
  - [Proximity Alerts](#proximity-alerts)
  - [Location Search](#location-search)
- [Advanced Features](#advanced-features)
  - [Custom Device Profiles](#custom-device-profiles)
  - [Multiple Map Layers](#multiple-map-layers)
  - [Operator Profiles](#operator-profiles)
  - [Advanced Settings](#advanced-settings)
- [Tips & Best Practices](#tips--best-practices)
  - [Accurate Positioning](#accurate-positioning)
  - [Safety First](#safety-first)
  - [Quality Contributions](#quality-contributions)
- [Troubleshooting](#troubleshooting)
  - [Common Issues](#common-issues)
  - [Getting Help](#getting-help)
- [Join the Movement](#join-the-movement)

---

## Introduction: Why Map Surveillance?

Mass surveillance infrastructure is expanding rapidly in our communities, often without public awareness or consent. Automated License Plate Readers (ALPRs), AI-powered cameras, gunshot detection systems, and other surveillance devices are being installed by the thousands—but where are they, who operates them, and what are their capabilities?

**DeFlock makes surveillance infrastructure visible.** By documenting these devices and uploading the data to OpenStreetMap, we create a transparent, searchable record of the surveillance apparatus in our communities. Knowledge is power, and transparency is the first step toward accountability.

### What is OpenStreetMap?

OpenStreetMap (OSM) is the "Wikipedia of maps"; a collaborative, open-source mapping platform where anyone can contribute geographic data. Unlike corporate mapping services, OSM is community-owned and freely accessible. When you map surveillance devices with DeFlock, you're contributing to this global commons.

**You must have a [free OpenStreetMap account](https://www.openstreetmap.org/user/new)** before submitting new data through DeFlock.

### What Makes DeFlock Different

- **Privacy-respecting**: We collect no user data. Everything stays on your device except what you choose to upload to OpenStreetMap.
- **Intuitive UI**: DeFlock makes it easy to view and contribute map data.
- **Offline-capable**: Download map areas and work completely offline, then sync when you have internet.
- **Manufacturer-aware**: Built-in profiles for Flock Safety, Motorola, Genetec, and other major surveillance vendors.
- **Community-driven**: Part of the broader movement for surveillance transparency.

---

## Getting Started

### Installation

Download DeFlock from the App Store (iOS) or Google Play (Android)

>>LINKS<<

### Initial Setup

1. **Grant location permission** to let the map follow you as you move. While optional, this is helpful for quickly mapping objects as you see them.
2. **Enable notification permissions** to receive alerts as you approach nearby surveillance infrastructure on the map.

*[Screenshot: Permission dialogs]*

### Connecting to OpenStreetMap

Before you can submit surveillance data, you need to connect your OpenStreetMap account:

1. Open the **Settings** menu (gear icon)
2. Tap **Log in to OpenStreetMap**
3. Authenticate with your OpenStreetMap credentials
4. Authorize DeFlock to modify the map for you
5. Test your connection to OSM to verify everything is ready

*[Screenshot: Settings > Authentication screen]*

The app will securely store your authentication tokens. You only need to log in once.

### Understanding the Interface

The main screen shows:
- **Map view** with your current location if available
- **"New Node" button** to submit new nodes to OSM
- **Settings gear** for configuration
- **Search button** to find specific locations on the map
- **Follow-me toggle** for GPS tracking (off/follow/follow+rotate)
- **"Download" button** to store the visible area locally for offline use

*[Screenshot: Main interface with annotations]*

**Map Controls:**
- **Pinch to zoom** in/out
- **Drag to pan** around the map
- **Two-finger rotate** to change orientation
- **Tap markers** to see device details

---

## Your First Device: A Complete Walkthrough

Let's map your first surveillance camera step-by-step.

### Step 1: Find a Device

Start with an obvious surveillance camera—perhaps at a traffic intersection, parking lot, or building entrance. Position yourself where you can safely observe the device while using your phone.

*[Screenshot: User in field with visible camera]*

### Step 2: Add the Device

1. **Tap the "New Node" button** at the bottom of the screen
2. **Position the pin** precisely on the camera location by dragging the map
3. **Set the direction** using the slider; the shaded field-of-view cone reacts live

*[Screenshot: Add node interface with positioning controls]*

### Step 3: Choose a Device Profile

DeFlock includes profiles for major surveillance manufacturers:

- **Flock Safety**: AI powered mass surveillance cameras
- **Motorola/Vigilant**: Professional ALPR systems
- **Genetec**: Security cameras and systems
- **Leonardo/ELSAG**: Law enforcement ALPR

Select the profile that best matches your device, or create a custom profile if none apply.

*[Screenshot: Profile selection screen]*

### Step 4: Add Details

The profile will pre-fill common tags, but you can add an Operator Profile if you know the entity responsible for the installation.

*[Screenshot: Tag editing interface]*

### Step 5: Submit

Tap **Submit** to add the device to your upload queue. You'll see the node change color to purple, indicating it's pending submission.

*[Screenshot: Confirmation and purple pin]*

**Congratulations!** You've just documented your first surveillance device. The data will sync to OpenStreetMap automatically when you have internet connectivity, and the node will turn blue once submitted. (This can take a long time on OSM, potentially over an hour. Do not re-submit nodes which appear to be failing without first checking your submitted changesets in the OSM console online.)

---

## Core Features

### Understanding Pin Colors

DeFlock uses color-coded pins to show device status:

- **Blue**: Confirmed devices from OpenStreetMap
- **Purple**: New devices waiting to upload
- **Grey**: Original device with pending edits
- **Orange**: Device currently being edited
- **Red**: Device queued for deletion

*[Screenshots of different colored pins]*

### Device Types You Can Map

**Cameras:**
- Security cameras (dome, bullet, PTZ)
- Traffic enforcement cameras
- License plate readers (ALPR/ANPR)

**Audio Surveillance:**
- Gunshot detection systems (ShotSpotter, etc.)
- Audio recording devices

**Other Surveillance:**
- Cell site simulators (Stingray devices)
- Facial recognition systems
- Any other automated surveillance infrastructure

**Etc**
- Technically there is nothing stopping you 
  from creating a profile containing the OSM tags 
  which describe park benches or anything else

### Editing Existing Devices

Found an error or want to add more details to an existing device?

1. **Tap the node** on the map
2. **Tap "Edit"** in the popup
3. **Modify position** or direction by dragging the map or slider
4. **Update tags** as needed by selecting a profile (original tags will be replaced)
5. **Submit your changes**

The original pin turns grey and a new purple pin appears, showing your proposed changes.

*[Screenshot: Editing workflow]*

### Working Offline

DeFlock is built for field work, even without internet:

1. **Download map areas** before heading out:
   - Tap **"Download"** to save the current viewable area
   - Select maximum level of detail (17 recommended for accurate placement)
   - View download progress and name your areas in Settings > Offline
   - Downloaded areas will fetch the currently selected tile type

2. **Work normally** while offline—all features work the same

3. **Sync when back online**—your uploads will process automatically

*[Screenshot: Offline area download interface]*
*[Screenshot: Offline settings page]*

### Upload Queue Management

View and manage your pending uploads:

1. Go to **Settings > Upload Queue**
2. See all pending operations (creates, edits, deletions)
3. **Retry failed uploads** or **cancel** if needed

*[Screenshot: Upload queue screen]*

### Suspected Locations

DeFlock can display "suspected locations"; sites where utility permits suggest possible surveillance infrastructure installations. These appear as orange question mark dots on the map.
Only available in select locations; more will be added regularly.

1. **Enable suspected locations**: Under **Settings > Advanced**
2. **Toggle visibility**: Turn on "Show Suspected Locations"
3. **Adjust filtering**: Set minimum distance to hide suspected locations near confirmed devices
4. **Update data**: Tap "Refresh now" to download latest permit data

*[Screenshot: Suspected locations settings]*
*[Screenshot: Map showing question mark markers]*

**What are suspected locations?**
These are derived from utility permit data indicating potential surveillance infrastructure installation sites. The data is collected and hosted by alprwatch.org. While not confirmed surveillance devices, they represent locations worth investigating when you're out mapping.

### Proximity Alerts

Get notified when you approach mapped surveillance devices, even when the app is in the background.

1. **Enable alerts**: Go to **Settings > Proximity Alerts**
2. **Grant notification permission** when prompted
3. **Set alert distance**: Choose how close (25-200 meters) you need to be for alerts
4. **Battery usage**: Note that continuous location monitoring uses extra battery

*[Screenshot: Proximity alerts settings]*
*[Screenshot: Notification example]*

**Types of alerts:**
- **Push notifications**: When app is in background (requires notification permission)
- **In-app banners**: Visual alerts when app is active
- **Audio**: System notification sound

### Location Search

Find specific addresses, businesses, or points of interest on the map.

1. **Tap the search button** to open the search interface
2. **Enter location**: Type an address, business name, or place
3. **Select result**: Choose from the search results to jump to that location on the map

*[Screenshot: Search interface]*

---

## Advanced Features

### Custom Device Profiles

Create your own profiles for recurring device types:

1. Go to **Settings > Device Profiles**
2. Tap **"+"** to create new profile
3. **Name your profile** (e.g., "City Traffic Cam")
4. Select whether this type of device has a directionality component
5. Select whether your profile is eligible to be used for submissions to OSM
6. **Set OSM tags** for this device type (see https://wiki.openstreetmap.org/wiki/Map_features)
7. **Save** and use in future mapping

*[Screenshot: Profile creation interface]*

### Multiple Map Layers

Switch between different map styles for better visibility:

- **OpenStreetMap**: Standard community-maintained maps
- **Satellite**: High-resolution aerial imagery
- **Topographic**: Terrain and elevation data
- **Custom providers**: Add your own tile sources

Access via the **layer switcher** in the bottom-right corner.

*[Screenshot: Layer switcher menu]*

### Operator Profiles

For professional mappers tracking specific surveillance programs:

1. **Settings > Operator Profiles** 
2. **Create profiles** for surveillance operators (police departments, private companies)
3. **Assign operators** when adding devices using "Refine Tags" button before submission

### Advanced Settings

**Proximity Alert Settings:**
- **Alert distance**: 25-200 meters (default: 50m)

**Suspected Location Settings:**
- **Minimum distance**: Filter out suspected locations near confirmed devices (default: 50m)
- **Data updates**: Manual refresh of permit data

**Map Behavior:**
- **Follow-me modes**: Off, north-up, or rotating with movement
- **Network indicator**: Show connection status
- **Max nodes**: Limit number of nodes displayed for performance

*[Screenshot: Advanced settings screen]*

---

## Tips & Best Practices

### Accurate Positioning

- **Use satellite imagery** to verify exact placement
- **Double-check field of view**—the cone should point where the camera looks

### Safety First

- **Never trespass** or put yourself at risk to map a device
- **Stay on public property** and observe from safe distances
- **Be aware of your surroundings** when using your phone in traffic areas

### Quality Contributions

- **Be careful about placement** and direction to ensure precision and accuracy 
- **Use specific profiles** rather than "Generic" when you can identify the manufacturer
- **Include operators** when known (especially for public installations)
- **Verify accuracy** before submitting—incorrect data hurts the project
- **Submit only** new data you can personally verify; do not use Google street view

---

## Troubleshooting

### Common Issues

**"No devices appearing on map"**
- Check your zoom level; zoom in closer to see devices
- Verify internet connection for loading data
- Ensure you are not in offline mode, or have data downloaded for the current area

**"Upload failed"**
- Confirm you're logged into OpenStreetMap
- Check internet connectivity
- Retry from the Upload Queue in settings

**"GPS not accurate"**
- Enable high-accuracy location in device settings
- Wait for GPS lock; a clear view of the sky helps
- Use satellite imagery to verify placement

### Getting Help

- **Documentation**: [deflock.me](https://deflock.me)
- **Community**: Join our Discord (link on website)
- **Issues**: Report bugs on our GitHub repository
- **Email**: Contact us directly via the website

---

## Join the Movement

Every device you map makes surveillance infrastructure a little more visible, a little more accountable. You're contributing to a global database that researchers, journalists, and communities can use to understand the scope of modern surveillance.

**Thank you for helping make surveillance transparent.**

*Ready to start mapping? Download DeFlock today and begin documenting the surveillance infrastructure in your community.*
