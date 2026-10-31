# Dune II native preview downloads

Initial native Windows x64 Dune II build based on OpenDUNE, with strict
Direct3D 12 renderer selection and scalable windows. No DOS emulator is used.

- [Windows ZIP](nax-dune-windows-x64.zip?raw=true)
- [Corresponding source ZIP, including SDL2](nax-dune-corresponding-source.zip?raw=true)
- [SHA256 checksums](SHA256SUMS)

Download and extract the Windows ZIP, then follow its README to import your
original Dune II CD data and run scripts/play-dune.ps1. Game assets are not
included. The package includes licenses and a GPU verification script.

Verified: cross-compilation to Windows x64, native Linux intro rendering,
scenario 1 loading for all three houses, and six importer tests.
Windows 11 GPU, audio, controls, and full campaign testing remain outstanding.
This is an experimental preview, not a validated Windows release.

Utopia is not playable in this preview. The source package includes its data
importer; a native Utopia engine has not been implemented.
