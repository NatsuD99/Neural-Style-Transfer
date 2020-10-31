# Neural Style Transfer using Keras
Neural style transfer is an optimization technique used to take three images:
<ul>
    <li> A content image </li>
    <li> A style reference image (such as an artwork by a famous painter)e </li>
    <li> The input image you want to style </li>
</ul>and blend them together such that the input image is transformed to look like the content image, but “painted” in the style of the style image. An overview of the technical process is that we take the base input image, a content image that we want to match, and the style image that we want to match. We’ll transform the base input image by minimizing the content and style distances (losses) with backpropagation, creating an image that matches the content of the content image and the style of the style image.

## Results
<p align="center">
    <img src="https://user-images.githubusercontent.com/58219175/97775110-03e67500-1b84-11eb-965b-0da5d1d4d565.jpeg">
    <img src="https://user-images.githubusercontent.com/58219175/97775444-aa337a00-1b86-11eb-9be2-3c01ca9cd7c3.jpeg">
</p>
