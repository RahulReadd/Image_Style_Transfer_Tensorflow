
# Image Style Transfer using Convolutional Neural Networks

This project focuses on leveraging Convolutional Neural Networks (CNNs) to perform image style transfer. The goal is to combine the content of one image with the artistic style of another to generate a new image that retains the content structure while adopting the stylistic features of a reference image.

### Neural Network Approach
- Utilization of a pre-trained VGG (VGG-19) network to represent images through feature maps across various layers.
- Higher layers of the network retain global content information, while lower layers preserve local pixel details.

### Content and Style Extraction
- Content extraction involves utilizing higher-layer features to capture semantic information regarding the image.
- Style is modeled as texture using correlations between feature responses in multiple layers of the network.

### Image Style Transfer Process
- Extraction of content from a photograph and style from a painting based on deep neural network features.
- Generation of a new image that encapsulates both content and style representations.
### Future Directions and Considerations
- Understanding what makes certain image representations effective for synthesis.
- Enhancing control in style transfer procedures for better manipulation and color preservation.

### Getting Started:
- Make a copy of the google colab notebook.
- Update the content_img_url and style_img_url to change the content image and style image
- Run the code cells
- Adjust the tunable hyperparameters to get desirable outputs: style_weight, content_weight, num_epoch, steps_per_epoch

### Contributors:
**Rahul Kumar Padhy** [Linkedin](https://www.linkedin.com/in/rahul-padhy-a71006201/)
### License:
This project is licensed under the MIT License.

### Acknowledgments:
Special thanks to Dashtoon team for this unnique project idea. 
Feel free to contribute, provide feedback, or add new features to make this Image Style Transfer project even more awesome!
