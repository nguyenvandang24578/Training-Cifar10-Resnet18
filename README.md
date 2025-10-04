# 🧠 CIFAR-10 Classification using ResNet-18

Dự án này huấn luyện mô hình **ResNet-18** để phân loại ảnh trong bộ dữ liệu **CIFAR-10** gồm 10 lớp:  
`['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']`.

---

## 🚀 1. Giới thiệu

Mục tiêu: Xây dựng mô hình nhận dạng ảnh nhỏ (32x32) bằng mạng CNN mạnh mẽ ResNet-18.  
Mô hình được huấn luyện bằng **PyTorch** với các bước tiền xử lý cơ bản (normalize, augmentations).

---

## ⚙️ 2. Cấu trúc thư mục
"📁 cifar10-resnet18/
│
├── train.py # Script huấn luyện mô hình
├── test.py # Script đánh giá mô hình
├── model.py # Định nghĩa ResNet18
├── utils.py # Hàm vẽ đồ thị acc/loss
├── results/
│ ├── accuracy_loss.png
│ ├── best_model.pth
│ └── logs.csv
└── README.md"

## 📊 4. Kết quả
Độ chính xác đạt được

Train Accuracy: ~92%

Validation Accuracy: ~88%

Test Accuracy: ~87%
## 📈 Biểu đồ Accuracy
<p align="center"> <img src="Image/accuracy.png" width="650" alt="Accuracy Graph"/> </p>

Hình 1: Biểu đồ thể hiện quá trình thay đổi Accuracy các epoch.

## 📈 Biểu đồ Loss
<p align="center"> <img src="Image/loss.png" width="650" alt="Loss Graph"/> </p>
Hình 2: Biểu đồ thể hiện quá trình thay đổi Loss qua các epoch.

## 🧩 Confusion Matrix
<p align="center"> <img src="results/confusion_matrix.png" width="650" alt="Confusion Matrix"/> </p>

Hình 3: Ma trận nhầm lẫn thể hiện mức độ chính xác của mô hình trên từng lớp CIFAR-10.
