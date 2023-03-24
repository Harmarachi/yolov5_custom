## <div align="center">Documentation</div>

Step to run.

<details open>
<summary>Install</summary>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
```

</details>


<details>
<summary>Dataset</summary>
Unzip the mini dataset 'testermix.zip' and move it to the parent directoryof this repo on your computer
</details>

<details>
<summary>Training</summary>

```bash
python traincustom.py --img 640 --batch 2 --epochs 3 --data dataset.yaml --weights yolov5s.pt
```

</details>

