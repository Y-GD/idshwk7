# Hiding in Frequency



## 一、Hide the information to the picture



### 1、Prepare the original picture and the information to be hidden

- **orig.png**

  <img src="test.assets/orig.png" alt="image-20200519173642903" style="zoom:50%;" />

- **myinfo.png**

  <img src="test.assets/myinfo.png" alt="image-20200519173805733" style="zoom: 80%;" />





### 2、Use blind watermarking to hide information

```bash
python encode.py --image orig.png --watermark myinfo.png --result result.png
```

- **result.png**

  <img src="test.assets/result.png" alt="result" style="zoom: 50%;" />





## 二、Extract the information from picture

```bash
python decode.py --image result.png --orig orig.png --result watermark_result.png
```

- **watermark_result.png**

  <img src="test.assets/image-20200519175912621.png" alt="image-20200519175912621" style="zoom: 67%;" />

  









