# VPS Explorer Changelog

<<<<<<< HEAD
## [1.1.1] - 2025-11-13

### Fixed

- Fixed issue with file upload and download not working correctly

=======
>>>>>>> contributions/merge-1763039199604
## [1.1.0] - 2025-11-11

### Added

- Initial release of VPS Explorer extension
- Browse files and directories on remote VPS servers via SSH
- Upload files from local machine to VPS
- Download files from VPS to local Downloads folder
- Create new directories on VPS
- Delete files and directories from VPS
- Rename files and directories on VPS
- Sort files by name, modified time, size, and kind
- Secure password handling via environment variables
- Support for files and folders with spaces in names
- Visual feedback with icons and metadata (permissions, size, modified time)

### Security

- Implemented secure password authentication using environment variables
- Passwords passed to expect scripts via `VPS_SSH_PASSWORD` environment variable
- Temporary scripts are created with owner-only permissions (0o700)
- Automatic cleanup of temporary authentication scripts

<<<<<<< HEAD
=======

>>>>>>> contributions/merge-1763039199604
## [Initial Version] - 2025-11-11
