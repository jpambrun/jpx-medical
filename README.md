# jpx-medical

Fork of Mozilla's JPEG2000 decoder from PDF.js adding support for 16 bit signed grayscale images found in the medical domain.

## Usage

```
  jpxImage.parse(jpxData);
  var width = jpxImage.width;
  var height = jpxImage.height;
  var pixelData = tileComponents.items;
```

With jpxData an Uint8Array containing the jp2 stream and pixelData the decoded to an Int16Array image.
