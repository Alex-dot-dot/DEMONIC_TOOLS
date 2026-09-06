# Restructure branch

This branch contains a non-destructive reorganization of the repository to make benign utilities easier to find.

What I changed:
- Copied selected benign scripts into tools/benign, tools/termux, and tools/misc.
- Placed a copy of a duplicate ip-flooder into duplicates/ for review.
- Added inventory.csv listing files and a basic classification.
- Added tools/README.md explaining the structure.

Important:
- No files on the default branch were modified or deleted.
- All "dark" tools (phishing, flooders, ddos, stresser, deauth, etc.) were left intact in place as requested.

Next steps you can take:
- Review duplicates/ and delete any originals you don't need.
- If you want the dark tools quarantined, tell me and I can move them intact into tools/dangerous/ on a follow-up commit.
