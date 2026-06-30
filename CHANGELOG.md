# Change Log
All notable changes to this project will be documented in this file.

## 2026-06-30
### Added
* Instructions for performing backups for Jellyfin and ErsatzTV


## 2026-06-21
### Added
* Instructions for adding open source crowdsec security filtering.
### Updated
* Per-process CPU and Memory visualizations on dashboard.


## 2026-06-20
### Added
* Instructions for adding media directories to spotlight privacy to prevent unnecessary disk activity.
* Instructions for suppressing CPU usage of macOS media scanning processes.
### Updated
* Misspelled words to correct spelling.


## 2026-04-25
### Updated
* Metrics section to include per-process CPU and Memory metrics for macOS.
* Grafana dashboard to include per-process CPU and Memory charts.


## 2025-06-08
### Added
* Three new charts on the grafana dashboard to better show the growth of movies, shows, and episodes over time.
### Updated
* `Video Streams In Progress` and `Connected Devices` charts to ensure equal spacing for each value in the count, 
  enhancing visual clarity and consistency across various connection counts.
* `Video Downloads In Progress` and `Live TV Steams In Progress` to display a minimum of zero when no data is found.
### Removed
* Uptime chart on dashboard to make room for new charts.


## 2025-04-12 (PM)
### Updated
* Added Geo Filtering section.


## 2025-04-12
### Updated
* Automated DNS A record creation.
* Added CHANGELOG.md
* Updated startup script to use `caddy start` over `caddy run`. 


## 2025-04-05
### Updated
* jelly-metrics install instructions to use `go install`.


## 2025-04-01
### Added
* CONTRIBUTING guide.


## 2025-03-27
* Initial Release
 