# Assignment 1. Image sensing and digital image by @Sadig Akhund

## Task 1.
In order to carry out this project, I chose my Razer Viper Ultimate (Cyberpunk 2077 edition) mouse as an object. All the original images are located at "<i>/img</i>" directory. For the following tasks, I will be using "<i>/out</i>" directory as an output path.

## Task 2.
I am using Samsung S22+ for capturing the images. Optics of this device features a triple-lens rear camera setup that includes a 50-megapixel primary sensor, a 12-megapixel ultra-wide sensor, and a 12-megapixel telephoto sensor. The lenses have a fixed aperture of f/1.8, f/2.2, and f/2.4 respectively, and support optical image stabilization (OIS). Moreover, it has several sensors that work together to capture high-quality photos. The primary sensor is a 50-megapixel ISOCELL GN2 sensor that features Dual Pixel Pro autofocus and is capable of capturing 4K videos at 60 frames per second (fps). The ultra-wide sensor is a 12-megapixel Sony IMX563 sensor with a 120-degree field of view, while the telephoto sensor is also a 12-megapixel sensor with 3x optical zoom and up to 30x digital zoom. When it comes to the resolution of images, there are wide range of resolutions, including up to 8K video recording at 24fps, 4K video recording at 60fps, and 1080p video recording at up to 240fps. Photos captured by the device can have resolutions of up to 8192 x 6144 pixels. The Samsung S22+ supports several encoding formats, including HEVC (H.265), H.264, and VP9. 

## Task 3. 
For this task I used the method from class (dot product with 0.299, 0.587, 0.114 coefficients). See: "<i>/out/grayscale</i>" for results.

## Task 4.
I chose 4 as the number of colors and converted images using rounding method. See: "<i>/out/discretized</i>" for results.

## Task 5. 
For this task I set threshold to 127 and maxval to 255 to get black and white images. See: "<i>/out/bw</i>" for results.

## Task 6.
Here, I converted images from RGB to HSL. Then multiplied each corresponding letters to the specified coefficients. See: "<i>/out/hsl</i>" for results.

## Task 7. 
Using the method of ciede2000, I iterated over each pixel and highlighted the ones that are close to the specified pixel. Additionally, I resized the images and added multi-threading to boost the speed. See: "<i>/out/close_colors/background</i>" for closeness of pixel from background and "<i>/out/close_colors/objects</i>" for closeness of pixel from objects.

