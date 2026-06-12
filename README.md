# Celebrity Recognition — A Comparative Study

A comparative study of celebrity recognition using two different approaches: **AWS Rekognition** (a cloud-based service) and the **VGG deep learning model**. The project evaluates both methods on accuracy, confidence scores, and practical trade-offs.

## Tech Used

- Python
- AWS Rekognition
- VGG (VGGFace) model
- Keras / TensorFlow
- NumPy, Matplotlib

## Project Structure

```
Celebrity_Recognition_Final_Code.ipynb                       # Main notebook with both approaches
Step By Step Guide for Project "Insights into Celebrity Reco.pdf   # Detailed walkthrough guide
```

## How to Run

1. Install dependencies:
   ```bash
   pip install tensorflow keras numpy matplotlib boto3
   ```
2. Configure AWS credentials if using the Rekognition portion (requires an AWS account with Rekognition access).
3. Open the notebook:
   ```bash
   jupyter notebook Celebrity_Recognition_Final_Code.ipynb
   ```
4. Run all cells to reproduce the comparison results.
