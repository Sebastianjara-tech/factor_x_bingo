0. If you had 2025.0.x or 2025.1.0 installed before with some other fix, go here:

	%appdata%\Maxon

and remove the folder named "Maxon Cinema 4D 2025_" with 4 bytes after the underscore, e.g.:

	"Maxon Cinema 4D 2025_AB23FFCD"


1. Download and install:
https://mx-app-blob-prod.maxon.net/mx-package-production/installer/windows/maxon/cinema4d/releases/2025.1.1/Cinema4D_2025_2025.1.1_Win.exe


1a. If this is the 1st time you installed 2025.1.1, or if you didn't use my 2025.1.0 release:

	Launch C4D, wait for the License Manager window to pop up with an Error, and close it



2. Put both provided DLLs into
	C:\Program Files\Maxon Cinema 4D 2025\resource\modules\io_usd.module\libs\win64

	overwrite when prompted


2a. If you have RS subscription, try using DLLs in folder '01',
	otherwise use DLLs in folder '00'


3. You can remove the Redshift folder from C4D install dir root



n1z