# Unet-Skin-lesion
Phân vùng ảnh da liễu bằng mạng CNN kiến trúc U-net:

![unet](https://user-images.githubusercontent.com/49630112/90757777-43811d00-e308-11ea-9261-f41f99bb7cff.png)
 
Dữ liệu sử dụng được tải về từ bộ Skin Cancer MNIST: HAM10000 (kaggle) gồm 200 mẫu (kèm label, được lưu trong tập PH2 Dataset images), trong đó 10% được sử dụng làm tập validation. Tập test gồm 100 ảnh chưa được gán label. Vì file PH2 Dataset images quá lớn nên đã được chia nhỏ thành các file dataset_1 đến dataset_6.

Kết quả phân vùng : 
- Ảnh gốc :

![2](https://user-images.githubusercontent.com/49630112/90756206-4713a480-e306-11ea-8078-6ce9d817aede.jpg)

- Ảnh sau khi phân vùng (segmented image) :

![1](https://user-images.githubusercontent.com/49630112/90756213-48dd6800-e306-11ea-8d3f-78ce21aaae49.jpg)

