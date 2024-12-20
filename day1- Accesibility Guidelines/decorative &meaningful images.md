# Decorative and Meaningful Images

### Screen readers ignore decorative images and only detect the meaningful images. So we need to distinct whether our image is decorative or meaningful.

#### Ways to declare an image as Decorative
- Giving an image a empty alt attribute 

- using an image with CSS background-image property.

- using aria-hidden = 'true' 

#### Ways to declare an meaningful image
- For img tag using descriptive alt attribute makes the image meaningful.

-  Using role= 'image' and descriptive aria-label property for background image, fonts and svg images make them descriptive.
