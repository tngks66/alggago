## 2018 capstone design ##

- topic : intelligence alggagi robot 

- introduction : 

1. 안녕
2. 안녕
3. 안녕

<br>

  dil = new IplImage(src.Size, BitDepth.U8, 3);

  IplConvKernel element = new IplConvKernel(4, 4, 2, 2, ElementShape.Custom, new int[3, 3]);
  Cv.Dilate(src, dil, element, 3);
  return dil;

....
