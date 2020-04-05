# DataWorkshop-Matrix3
DL project coded during Matrix 3 by DataWorkshop

CNN models - ideas to improve:
- check, if any why the following predictions give the same accuracy...?
- do something more with data, for example 

def preproc_img(img):
  hsv = color.rgb2hsv(img)
  hsv[:, :, 2] = exposure.equalize.adapthist(hsv[:, :, 2])
  img = color.rgb2hsv(hsv)
  return img
  
 or https://github.com/joshwadd/Deep-traffic-sign-classification
 (rotation, translation, etc)
