# Neural_Style_Transfer

If you want to try out the code, follow these steps by uploading **two images** into your Colab environment:

### 1. **Content Image**
- This is the image you want to apply a style to.
- Replace the following line of code:
  ```python
  content_image = np.array(Image.open("bird2.jpg").resize((img_size, img_size)))
  with the actual name of your content image.```

### 2. **Style Image**
- This is the image whose style will be transferred to the content image.
-  Replace the following line of code:
  ```python
  style_image = np.array(Image.open("cathedral_style.jpg").resize((img_size, img_size)))
  with the actual name of your style image.```

