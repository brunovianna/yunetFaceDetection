## Face detection with yunet

### Face detection in OpenFrameworks using dnn

It turns out that doing face detection in 2025 is much more efficient with neural networks than cascades.
So here is an OF example that uses opencv's facedetectoryn (for yunet).

In Linux, you might need the 2022 version of the model, which is compatible to opencv 4.6 used in my OF 0.12.
Here is a [link](https://github.com/opencv/opencv_zoo/blob/088c3571ec70df15100a5e4c26894d95951e92e9/models/face_detection_yunet/face_detection_yunet_2022mar.onnx). Place it in the bin/data folder.

In windows, the [face_detection_yunet_2023mar.onnx](https://github.com/opencv/opencv_zoo/tree/main/models/face_detection_yunet) file worked fine, since the opencv version seems to be 4.11
