# Pix2HDR--A pixel-wise acquisition and deep learning-based synthesis approach for high-speed HDR videos

Code will be updated later.

This is the video demonstration for the paper **Pix2HDR--A pixel-wise acquisition and deep learning-based synthesis approach for high-speed HDR videos**. 

Due to our PE-CMOS resolution size, the HDR videos are trimmed into 128x128. We also list the corresponding subframes (64x64) on the left side for comparison. 

Unless otherwise notified, the layout and frame rates of the videos will be consistent with the following image:

<img src="https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/739ceb31-3451-4ede-9d4b-56886aaa295c" width=500px>

Videos will be displayed at their original speed (1000FPS) or slowed down by 330 times (30FPS).


## Wearing glasses beside the window

Original speed (1000FPS):

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/3c68c893-80cd-422a-afac-b62e4ac5e606

## Rotating fan
Original speed (1000FPS):

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/dac473a1-3488-4f75-8141-0e5acfe27ea5

330x slower (30FPS):

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/cdf9548f-aa2f-4636-a7cd-c1bdea634afb

## Pouring water
Original speed (1000FPS): 

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/5bce82c2-c2a7-4ab1-96ab-d8a2dc5eb6f6

330x slower (30FPS):

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/631519f6-e35d-4fe8-b329-348a8b246fc2

## Dropping cork
Original speed (1000FPS): 

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/43eb766a-c556-4764-a9e0-23f1fe96c687

330x slower (30FPS):

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/26af3a61-5e1f-42e8-8690-6f26f4f8eb3b




## Extending dynamic range
To quantify the dy namic range enhancement from our method, we set the PE-CMOS pixels in 3 different configurations, with min-max pixel exposure ratios of 1:4, 1:8, and 1:16 using MPVE sampling pattern with pixels at 500, 250, 125, 63, and 32 Hz.

<img src="https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/d000791d-05eb-44a0-a9dc-6c4d11ece2e8" width=500px>

While the dynamic range is enhanced by larger exposure ratios, the speeds of recovered HDR videos remain at 1000FPS. Video demos are shown below.

Original speed (1000FPS), comparison of 1:4, 1:8, and 1:16:

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/4fe7bcd0-f920-4156-ba04-caf382f7de1c

330x slower (30FPS):

https://github.com/BradiWang/Pix2hdr_videos/assets/71883997/8dd96937-5510-4d86-b9bc-9bfd0f8cfe21
