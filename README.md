# 🧠 **People Tracking & Heatmap Generator using YOLOv8**

This project uses **YOLOv8** to detect and track people in a video, count **IN** and **OUT** movements across defined lines, and generate a **motion heatmap** overlay. The output includes a **video with heatmap overlay** and a **final heatmap image**.

---

## 📌 **Features**

- ✅ Real-time object detection and tracking using **YOLOv8**
- 🎯 IN and OUT counting across user-defined lines
- 🌡️ Heatmap generation based on object motion intensity
- 🖼️ Final heatmap image saved with last video frame
- 🎥 Export of processed video with heatmap overlay

---

## 📁 **File Structure**

├── tracked_heatmap_output.avi # Output video with heatmap overlay
├── final_heatmap_image.jpg # Last frame + accumulated heatmap
├── your_script.py or .ipynb # Main code
├──a file of Your detection method,Line coordinates,Logic explanation for IN/OUT


---

## 🛠️ **Requirements**

- Python ≥ 3.8  
- [YOLOv8 (Ultralytics)](https://docs.ultralytics.com/)  
- OpenCV

**Install via pip:**

! pip install ultralytics opencv-python-headless



🚀 Usage (Google Colab)

1.Clone or upload the script to Colab

2.Install dependencies:

!pip install ultralytics opencv-python-headless

3.Upload your input video:

from google.colab import files
files.upload()

4.Run the script to process video and generate results

5.Download output files:

from google.colab import files
files.download("tracked_heatmap_output.avi")
files.download("final_heatmap_image.jpg")


📊 Use Cases

Crowd analytics in public spaces

Retail store footfall tracking

Event entrance/exit monitoring

Surveillance & motion analysis

📷 Output Previews

Video: Bounding boxes with real-time tracking and heatmap overlay

Image: Final frame with cumulative heatmap blended

🧑‍💻 Author
**Tariful Islam Tarif**
Data Scientist & AI Engineer









