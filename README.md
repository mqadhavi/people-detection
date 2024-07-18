# people-detection
#pertama
python installed min Python 3.11.5

#kedua install library
pip install -r requirements.txt

#cara menjalankan, buka command dan masuk ke directory
#jalankan untuk gambar dan video
python detection.py --model yolov8n.onnx --source data\images\contoh1.jpg
python detection.py --model yolov8n.onnx --source data\videos\video2.mov

#jalankan untuk webcam
python detection.py --model yolov8n.onnx --source 0
