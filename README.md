# SakeSaySo Community Repository

Welcome to the [SakeSaySo Community Repository](https://github.com/sakesayso/community), the official place for user-contributed content for the [SakeSaySo app](https://sakesayso.com). Here, every word is a sip towards fluency. Kanpai to our Japanese language adventure!

## Contribute SakeScript

Your contributions are the essence of our community's growth and learning. We encourage you to share your unique insights and experiences with the SakeSaySo audience. Here's how you can contribute:

- **Familiarize with SakeScript**: Before submitting your content, please review the [SakeScript Format Specification](https://github.com/sakesayso/sakescript). This ensures your contributions align seamlessly with the SakeSaySo app's structure and style.
- **Create and Share**: Craft your SakeScript content.
- **Submit a Pull Request**: Once ready, submit it via a pull request for the community to enjoy.

### Directory Layout

This repository is organized into two main sections: fiction and non-fiction, each containing a range of categories represented by the stories' first specific [tag from the SakeScript spec](https://github.com/sakesayso/sakescript?tab=readme-ov-file#recommended-content-tags). Each story is available both as individual files and a ZIP archive. Below is an overview of our directory structure:

```
.
├── fiction/
│   ├── adv/              # Adventure and exploration themed stories
│   ├── sfi/              # Science fiction and futurism themed stories
│   │   ├── [uuid]/       # Individual story files
│   │   │   ├── cover.jpg
│   │   │   ├── main.json
│   │   │   └── manifest.json
│   │   └── [uuid].zip    # Corresponding SakeScript ZIP archive
│   └── ...               # Other fictional categories
└── non-fiction/
    ├── pol/              # Politics and society themed stories
    ├── tec/              # Technology and internet themed stories
    │   ├── [uuid]/       # Individual story files
    │   │   ├── cover.jpg
    │   │   ├── main.json
    │   │   └── manifest.json
    │   └── [uuid].zip    # Corresponding SakeScript ZIP archive
    └── ...               # Other non-fiction categories
```

File Naming and Format
- ZIP Files: Each ZIP file is named using a unique identifier (UUID) specific to the story.
- Raw Files: Within each story's directory (identified by UUID), you will find individual files. These include optionally `cover.jpg` and mandatory JSON files in v1.0: `main.json` and `manifest.json`.
- Cover Image: We recommend using JPEG format for cover images to minimize file size. To convert a PNG image from e.g. DALL·E to JPEG, you can use ImageMagick with the following command:  `convert cover.png -resize 1080x -quality 92 cover.jpg`.

## Licensing

All contributions to this repository, unless otherwise noted, are licensed under the [Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/4.0/). This means:

- **Indulge and Remix**: Feel free to use, adapt, and build upon the contributed works.
- **Attribute and Share**: When using others' contributions, give credit and share your enhancements under the same terms.
