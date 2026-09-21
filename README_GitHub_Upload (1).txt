GitHub upload instructions for Unibot

The original project archive is about 69 MB, so it has been split into 24 MB parts.

Files:
- unibot_github_part01.zip.part
- unibot_github_part02.zip.part
- unibot_github_part03.zip.part

To reconstruct the original ZIP on Windows PowerShell, put all parts in the same folder and run:

cmd /c copy /b unibot_github_part01.zip.part+unibot_github_part02.zip.part+unibot_github_part03.zip.part unibot.zip

Then extract unibot.zip normally.

Important: these parts are pieces of ONE ZIP file; do not extract each part separately.
