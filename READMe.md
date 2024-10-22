> **Hướng dẫn training model IR_RGB detection New method**

> **Link tải datasets:**
>
> Bộ FLIR: [https://drive.google.com/file/d/1BTlpXGTtcE9nW0p6PWF1-JuxJCkD6fnv/view?usp=sharing](https://drive.google.com/file/d/1BTlpXGTtcE9nW0p6PWF1-JuxJCkD6fnv/view?usp=sharing)
>
> Bộ VEDAI: [https://pan.baidu.com/s/1UKSI0Go0Ddt62tXNIySz9w](https://pan.baidu.com/s/1UKSI0Go0Ddt62tXNIySz9w) Code：5ett
>
> Bộ KAIST: [https://www.kaggle.com/datasets/adlteam/kaist-dataset?select=set00]()

> **Hướng dẫn chỉnh sửa file training** 
>
> B1: Chỉnh link đường dẫn trong file custom.yaml ở thư mục data/multispectral
>
> Format lệnh train: python train.py --weights yolov5l.pt --cfg data/multispectral/custom.yaml --hpy data/hyp.scratch_VEDAI.yaml --batch-size 8

> Test model
>
> python test.py --weights <path_weights> --cfg data/multispectral/custom.yaml --batch-size 8

> **Cài đặt thư viện**
>
> python >= 3.9
>
> pip install -r requirements.txt

> Note: Format folder data training: datasets/train/image
>
>     --------------------------------------------------------------- labels/
