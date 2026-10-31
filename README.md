# Dune II native preview downloads

Initial native Windows x64 Dune II build based on OpenDUNE, with strict
Direct3D 12 renderer selection and scalable windows. No DOS emulator is used.

- [Windows ZIP](nax-dune-windows-x64.zip?raw=true)
- [Corresponding source ZIP, including SDL2](nax-dune-corresponding-source.zip?raw=true)
- [SHA256 checksums](SHA256SUMS)

Download and extract the complete Windows ZIP, then double-click **Start-Dune.cmd**.
Select your original `Dune-II-The-Building-of-a-Dynasty_DOS_EN_ISO-Version.zip`
when prompted. The launcher imports the CD data using Windows PowerShell; no
Python installation is needed to play. Use Start-Dune.cmd for later launches.
Game assets are not included. The package includes licenses and a GPU verification script.

Startup fix: data is checked before launching, stale data paths are repaired,
existing saves/settings are preserved, and missing PAKs produce clear instructions.
Ten tool integration tests pass; the real uploaded CD was imported and all 16
resource hashes verified. Windows file-picker/GUI testing remains outstanding.

Verified: cross-compilation to Windows x64, native Linux intro rendering,
scenario 1 loading for all three houses, and ten importer/startup tests.
Windows 11 GPU, audio, controls, and full campaign testing remain outstanding.
This is an experimental preview, not a validated Windows release.

Utopia is not playable in this preview. The source package includes its data
importer; a native Utopia engine has not been implemented.
