# Changelog

All notable changes to this project will be documented here.

## [v0.1] — 2025-08-11
**Summary:** First working version of the manhua/manhwa/manga classifier.

### Added
- Initial dataset collection using `icrawler` from Bing for 3 categories: manhua, manhwa, manga.
- FastAI-based image classification pipeline with `resnet34` backbone.
- Basic training notebook `v0.1_manhua_manhwa_manga_classifier.ipynb`.
- Preprocessing: image resizing, augmentation, normalization.

### Known Limitations
- Small dataset size → possible overfitting.
- Dataset not cleaned for duplicates.
- No external evaluation set or reproducible seed tracking.
