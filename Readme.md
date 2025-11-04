## Face detection with yunet


It turns out that doing face detection in 2025 is much more efficient with neural networks than cascades.
So here is an OF example that uses opencv's facedetectoryn (for yunet).

You must download the ***2022*** version of the model, which is compatible to opencv 0.4.6 used in OF 0.12.
Here is a [link](https://github.com/opencv/opencv_zoo/blob/088c3571ec70df15100a5e4c26894d95951e92e9/models/face_detection_yunet/face_detection_yunet_2022mar.onnx).