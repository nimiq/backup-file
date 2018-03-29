# Account Backup

This is a Account Access (aka Wallet) File Format designed for usability.

- File format PNG
	- Identicon is easily recognizable and distinguishable in Finder/Explorer/Gallery Previews
	- Compatible with restricted file systems like iOS
	- Compatible with restricted file sharing like Whatsapp
	- Compatible with native share events
	- Wallet transfer from device to device just by displaying and scanning the backup
	- Sharable as screenshot
- Private Key Stored as QR Code in the PNG
	- Compatible Standard
	- robust against image transformations of third-party apps 
- Private Key encrypted 
	- 6 digit pin
	- hard key derivation function (~10k rounds of argon2)