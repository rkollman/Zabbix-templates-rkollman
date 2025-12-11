# Changelog

Alle belangrijke wijzigingen aan dit project worden in dit bestand gedocumenteerd.


## [7.0-7]

### Changed
- Changed operational data in triggers to {ITEM.VALUE} instead of {ITEM.LASTVALUE}

## [7.0-6]

### Fixed
- Group Kollman/ITHO was not added right. Fixed this.

## [7.0-5]

### Added
- Menu URL's added to all triggers, easy to navigate to the WPU5G dashboard.
- Renamed the template to WPU5G because of the introduction of ITHO HRU300 Duo Daalderop by MQTT template (which still has to be released).
- Added an extra group to the template (Kollman/ITHO)

### Changed
- Changed some triggers to only run when a problem is detected 3 times in a row.

---

## [7.0-0] - 2025-07-16

### Added
- Initiële commit van WPU5G-template map onder Zabbix-templates-rkollman.  
- Bestand(en) toegevoegd: template(s) voor monitoring van ITHO WPU5G warmtepomp.  
- README / documentatie toegevoegd met uitleg over het gebruik van het template.  

### Changed
- —  

### Fixed
- —  

### Removed
- —  

