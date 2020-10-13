# Map Crop and Tile Slicer

### Process
1. Takes a desired tile width and height.
2. `refactor()` will trim the image dimension pixel-by-pixel until the width and height are evenly divisible by the target width and height
3. New resized image is saved
4. Final number of output pieces for width and height are calculated and `crop()` slices and saves the images

### Installation

Create and environment

```bash
pip install -r requirements.txt
```

### Usage

```python
1. Source file must be 'image.png' in same directory
2. Define target_w and target_h in main.py
3. $ python main.py
```

## License
[MIT](https://choosealicense.com/licenses/mit/)