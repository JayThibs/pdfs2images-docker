# Converting PDFs to Images for Every Page using Docker

I created this dockerfile since it is nearly impossible to get the proper packages for *PDF to Image* to work on Windows. Particularly, poppler has a tough time with Windows. This dockerfile also works to grab multiple PDFs in a folder and extract every page as an image using multiprocessing.
