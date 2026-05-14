# Digital Forensics Image Geolocation Investigation

## Overview

This project documents a digital forensic examination of four JPEG image files from a simulated investigation. The objective was to determine the geographic locations shown in the images by analyzing EXIF metadata, GPS coordinates, file integrity, timestamps, and visual location indicators.

The investigation used a forensic workflow that included evidence intake, hash verification, metadata extraction, geolocation validation, cross-image route correlation, and formal report writing.

## Tools Used

- FTK Imager
- Autopsy
- OSForensics
- Google Maps
- EXIF metadata analysis
- MD5 and SHA-1 hash verification

## Skills Demonstrated

- Digital evidence handling
- Hash verification and evidence integrity validation
- Chain-of-custody-style documentation
- EXIF metadata extraction
- GPS coordinate analysis
- Image geolocation
- Timestamp analysis
- OSINT-style visual verification
- Cross-image route reconstruction
- Formal forensic report writing

## Investigation Summary

Four JPEG images were examined as digital evidence. Each file was reviewed using forensic tools to identify metadata, verify file integrity, and determine whether the images contained embedded location information.

The investigation found that the images contained EXIF metadata consistent with native iPhone captures, including device model, capture timestamps, camera settings, GPS latitude/longitude, altitude, and GPS timestamps.

The recovered coordinates were plotted and compared against visible scene details to validate the likely locations. The results supported a cross-state travel pattern reconstructed from the image metadata and mapping evidence.

## Key Findings

- Verified image integrity using MD5 and SHA-1 hash values.
- Extracted EXIF metadata from JPEG image files.
- Identified device information, timestamps, GPS coordinates, altitude, and camera settings.
- Used Autopsy and OSForensics to validate metadata fields.
- Correlated GPS coordinates with Google Maps.
- Compared visual scene indicators with mapped locations.
- Reconstructed a cross-image route based on metadata and geographic evidence.
- Produced a formal forensic report with methodology, screenshots, findings, and conclusion.

## Repository Contents

```text

screenshots/
├── 01_hash_verification.png
├── 02_autopsy_file_metadata.png
├── 03_osforensics_exif_metadata.png
├── 04_gps_coordinate_mapping.png
└── 05_cross_image_route_correlation.png


