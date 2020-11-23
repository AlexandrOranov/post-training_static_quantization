# post-training_static_quantization
An example of the post-training static quantization of the resnet18 for captcha recognition

# Note: don't forget to fuse model's modules correctly (important for accuracy)
# and change "forward()" (or the model won't work).
At the time of the initial commit, quantized models don't support GPU.
