# Image-Compression-K-MEANs-
---
<img width="1259" height="1044" alt="spike" src="https://github.com/user-attachments/assets/f215e375-fbe9-44e0-b29c-5dfc448a1456" />

This is my dog who passed away in 2020 and this is one of my favorite photo of her. I noticed the colorful (rich) the colors were and used it to build a quick K-means image compression.

I applied K-means to reduce the number of colors by clustering pixels in RGB color and replacing each pixel with its cluster’s centroid color. I initialized the centroids, then iteratively assigned pixels to the nearest centroid and recomputed the centroids until convergence. In the end, I compressed the image using the most 16 colors while preserving the overall look.
