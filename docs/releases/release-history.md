# Release history

## [v1.0.4 <small>November 22, 2022</small>](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/releases/tag/v1.0.4)

### Compatibility

Product | Version
--------- | -------
Splunk platform versions | 9.x, 8.x
Splunk Enterprise Security version | [7.x, 6.x](https://splunkbase.splunk.com/app/263)
Crowdstrike Device Add-on Version | [3.x](https://splunkbase.splunk.com/app/5570)

### What's Changed

- Added ES managed configuration
- Fixed incorrect mac field (Thanks [@PaddlingCode](https://github.com/PaddlingCode)) - [#30](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/30)

**Full Changelog**: [v1.0.3...v1.0.4](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/compare/v1.0.3...v1.0.4)

## [v1.0.3 <small>September 20, 2022</small>](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/releases/tag/v1.0.3)

### Compatibility

Product | Version
--------- | -------
Splunk platform versions | 9.x, 8.x
Splunk Enterprise Security version | [7.x, 6.x](https://splunkbase.splunk.com/app/263)
Crowdstrike Device Add-on Version | [3.x](https://splunkbase.splunk.com/app/5570)

### What's Changed

- added cleanup search to remove old/stale devices ([#18](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/18)).
- added search macro for device retention period ([#18](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/18)).
- updated collection to include last seen field ([#18](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/18)).
- updated lookup generating search to include last time seen ([#18](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/18)).

## v1.0.2 <small>September 8,2022</small>

### Compatibility

Product | Version
--------- | -------
Splunk platform versions | 9.x, 8.x
Splunk Enterprise Security version | [7.x, 6.x](https://splunkbase.splunk.com/app/263)
Crowdstrike Device Add-on Version | [3.x](https://splunkbase.splunk.com/app/5570)

### What's Changed

- added `first_seen`, `last_seen`, and `last_updated` to category field ([#8](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/8)).
- added `site_name` to existing `bunit` field ([#13](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/13)).
- Changed app logo background to transparent.
- Updated saved search to preserve hosts with multiple IP/MAC addresses ([#11](https://github.com/ZachChristensen28/SA-CrowdstrikeDevices/issues/11)).

## v1.0.1 <small>August 25, 2022</small>

- Hotfix for missing `_key` field in saved search.

## v1.0.0 <small>August 25, 2022</small>

- Initial Release
