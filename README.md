# Neural Style Transfer using Keras
Neural style transfer is an optimization technique used to take three images:
<ul>
    <li> A content image </li>
    <li> A style reference image (such as an artwork by a famous painter)e </li>
    <li> The input image you want to style </li>
</ul>and blend them together such that the input image is transformed to look like the content image, but “painted” in the style of the style image. An overview of the technical process is that we take the base input image, a content image that we want to match, and the style image that we want to match. We’ll transform the base input image by minimizing the content and style distances (losses) with backpropagation, creating an image that matches the content of the content image and the style of the style image.
