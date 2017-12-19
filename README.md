# Wallet Backup

This is a Wallet File Format designed for usability.

- File format PNG
	- Identicon is easily recognizable and distinguishable in Finder/Explorer/Gallery Previews
	- Compatible with restricted file systems like iOS
	- Compatible with restricted file sharing like Whatsapp
	- Compatible with screenshot etc
- Private Key Stored as QR Code in the PNG
	- Compatible Standard
	- robust against image transformations of third-party apps 
- Private Key encrypted 
	- 6 digit pin
	- hard key derivation function (10k rounds of blake2)