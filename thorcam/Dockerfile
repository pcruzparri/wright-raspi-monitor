FROM Windows
RUN ["curl", "-fsSL", "https://www.thorlabs.de/software/THO/ThorCam/ThorCam_V3.7.0.6/Thorlabs%20Scientific%20Imaging%20Software%20x64.exe", "-o", "./thorcam_installer.exe"]
RUN ["thorcam_installer.exe", "/passive"]
RUN ["PATH," "%PATH%;", "C:\Program Files\Thorlabs\Scientific Imaging"]
CMD ["start", "ThorCam"]

