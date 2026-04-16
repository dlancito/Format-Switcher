# **What Is This?**

Format Switcher is a Firefox extension, loaded as a temporary add on that cycles through common media formats (MP4, MOV, AVI, M4V, M4A) on DOJ Epstein document URLs to reveal videos/audio that may be mislabeled as PDFs. It only accesses public records and does not store or transmit data.

# **Why I made this**

The DOJ's released Epstein files are hosted as a public document library, but not all media files are correctly formatted. This tool makes it easier to browse and surface media files by switching the format at the end of the link (MP4, MOV, AVI, M4V, M4A) for EFTA URLs, especially ones that end with ".pdf".

# **Installation**

1. Download this repo as a ZIP
2. Extract it
3. Open Firefox and type "about:debugging" in the search bar
4. Click "This Firefox" > "Load Temporary Add on"
5. Select the "manifest.json" file
6. Pin the extension by clicking the puzzle piece icon in the Firefox toolbar and selecting "Pin to Toolbar" for easier access while browsing

# **How to use with the Epstein files library**

1. Go to the DOJ Epstein files library (linked below)
2. Scroll down to the search bar and type "no images produced"
3. Browse the dataset results
4. Right click any link and open it in a new tab
5. Click the pinned extension icon to cycle through formats for that URL

Pinning the extension to your toolbar means it is always one click away without needing to open the extensions menu each time.

# **Formats**

mp4 > mov > avi > m4v > m4a > repeat

If a format doesn’t work, it likely means the file does not have a video or audio version in those formats.

# **Disclaimer**

This extension is intended solely for browsing publicly released government documents. I am not affiliated with the DOJ or any government agency. All files accessed using this tool are part of the official public record released by the U.S. Department of Justice.

This tool does not download, store, or transmit any data. It only modifies the current tab’s URL.

# **Legal**

All documents accessed via this extension are publicly available through official U.S. government sources. This extension does not bypass any access controls or paywalls.

# **Source**

Epstein files publicly released by the DOJ:
[https://www.justice.gov/epstein](https://www.justice.gov/epstein)

# **Credit**

No need to credit me. I made this so people can more easily look through and investigate the files.

# **Additional Resources**

While this extension helps with browsing, **u/Cind3rr** on [r/Epstein](https://www.reddit.com/r/Epstein) created a manual scrape of the video files for **DataSet 10**.

**[Link to Reddit Thread](https://www.reddit.com/r/Epstein/comments/1r5vj5f/all_video_files_easy_for_those_who_want_to/)**

* Provides a JSON list of known EFTA video files
* Useful for cross-referencing with this extension’s results
