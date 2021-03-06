# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.9] - 2020-03-04

### Added

- `scrollToField(...pathChunks)` - Plugins can use this method to navigate the record form.
- `saveCurrentItem()` - Plugins can use this method to trigger a record save action without pushing the save button.
- `notice(message)` and `alert(message)` - Use these methods to display UI consistent notifications and alerts.
- `itemStatus` - Information about the publishing status of the record the plugin is attached to.
- `isSubmitting` - Information about the record's form submitting status.
