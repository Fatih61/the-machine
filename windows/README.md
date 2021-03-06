# Windows Machine Implementation

---

Although I would have liked to keep things as simple as possible, sadly, there are complications on the Windows side of the fence. 

Here are some pre-requisites:
* Visual Studio 2015 RC (Visual Studio 2013 should work as well).
* Emgu CV 3.0.0-rc1, the 2.4.10 build has a bug with camera capture.
* .NET Framework 4.5.2 (if you don't already have it, when you run the program, Windows should prompt you to automatically download it for you).
* ~~The NAudio library, which is not currently used in the project, but will be used in the future for mp3 playback on the user's request later.~~ Currently this is not required anymore and could be added back in a future version.

Once these pre-requisites are there:
* Clone the repo to a directory.
* Move the assets folder to the directory of the executable.
* Add references to the ~~NAudio~~ (see above) library and Emgu CV library.
* **Note:** make sure that the new project is a WPF project (the old application used to be a Winforms application and is now located in the `deprecated-winforms` branch. That will no longer be maintained and this will be the active branch.

After this, everything else should be set up.

For those who just want to download the file the 64-bit link is below (no 32-bit support yet). In order to run the file, make sure you have 7-zip, extract the files to a folder, and run the file: `machine.exe`.

x64 link: [The Machine](https://mega.nz/#!OZ0mxaQZ!ClG6S7iX8SAtrnxhkPSbPou72iKNpaNbQrdgQpKq4zM).

---

The MIT License applies to this section of the Github repo as well. Please feel free to test out the repo and create issues. Of course, contributions are welcome as well. Starring and watching this repo would be welcome as well.

Thank you for visiting this website.
