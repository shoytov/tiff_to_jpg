# Simple script for convert tiff files to jpeg

You need to pass a path to directory with tiff files. The script recursive process nested directories.

## Usage

### Install dependencies
```
pip install -r requirements.txt
```

### Run the script
```
python main.py path_do_dir_with_tiff_images
```

## Dependencies
- Pillow==9.3.0
- python-magic==0.4.27
- tqdm==4.64.1
