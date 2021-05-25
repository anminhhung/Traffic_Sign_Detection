## 1. Cài đặt thư viện 
```
    pip install -r requirements.txt
```

## 2. Download model
Tải model bằng cách chạy lệnh sau
```
    gdown --id 1Cl6DSeEX279pDf2GswEXbIBkNooK-ICK 
    gdown --id 1sSqjKjSFJfiMoANrJlhze2sirkUA-LZ-
```
Sau đó di chuyển 2 file **yolov4_ver6_best.weights** và **yolov4_ver6.cfg** vào thư mục **models**]

## 3. Run demo
python predict_yolo.py -i <path_image> -o <image_name>
```
    python predict_yolo.py -i images/654.png -o 654.png
```