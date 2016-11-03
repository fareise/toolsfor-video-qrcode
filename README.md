# toolsfor-video-qrcode
Tools for transferring video and generating qrcode from urls.

#Generating qrcode

Interface: /users/qr

Required: url*;width;height

Data returned:

1.Data url of the qrcode image, you could use it in the "src" attribute of <img/>.

You could also make it be able to be downloaded by adding <a> tag, specify the "href" attribute to be the url and add "download" attribute.

2.width and height, you could use them to specifying the size of the image.

You could see the example in test.html.

#Transferring video

Interface: /users/formup

You could see the example in testvideo.html



