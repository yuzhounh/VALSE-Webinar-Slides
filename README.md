# VALSE Webinar Slides (2020 archive)

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-D4A017.svg)](LICENSE)

Historical Python download scripts for VALSE webinar slide pages and attachments collected in 2020.

The original archive recorded 150 items (about 1.20 GB) and listed a Baidu Netdisk copy at <https://pan.baidu.com/s/1_U0X9wOp5GR6Dwwp7c8McQ> with extraction code `c5nv`. The scripts use plain HTTP endpoints that may have moved or stopped responding; review the URLs and the target directory before running. No link, endpoint, or download was revalidated during this documentation update.

## Scripts

- `valse_slides_1.py`: scans article pages 269–356 and downloads linked PDF files.
- `valse_slides_2.py`: requests attachment IDs 1–79.
- `contents 1.txt` and `contents 2.txt`: historical file lists.

Both scripts use only the Python 3 standard library and write downloaded files into the current working directory. They do not implement retries, request timeouts, checksums, or rate limiting.

## Related Project

- [VALSE-Webinar-Slides-2](https://github.com/yuzhounh/VALSE-Webinar-Slides-2): later 2020 downloader for the webinar slide index, recorded as 320 items.

## License

See the existing [GNU General Public License, version 3](LICENSE).
