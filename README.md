# EnhancedNST
Enhanced Neural Style Transfer

Applies **Neural Style Transfer** on images with **semantic segmentation masks** so only selected objects are stylized while backgrounds remain unchanged.  
Uses **VGG19** for feature extraction and **DeepLabV3** for object segmentation.  

Run:
```python
run_style_transfer("content.jpg", "style.jpg")

