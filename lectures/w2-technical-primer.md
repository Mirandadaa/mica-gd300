# Technical Primer

## Frame, Beat, Shot, Scene, Sequence
Movements or visual changes happen between frames. Changes also happen in a bigger or longer structure. Here, we look at different units we use in film. 

![Units](../images/w1/units.jpg)

A **frame** is the smallest unit of film (or animation or video). It is a still image that is used to construct moving images.

A **shot** is made up of frames. In live action film, a shot begins when the camera begins recording and ends when the camera stops recording. Whenever there is a cut --- an abrupt change in visuals, we call it a shot. A typical movie is made up of hundreds or thousands of shots but we don't normally notice that change because filmmakers use a lot of techniques to reveal or hide the connection of different shots. 

A *beat* is a subjective term to indicate a short length of time. You will hear some people use it but again, it is subjective so how long a *beat* is different for everyone. 

A **scene** is mainly used in live action production. It is a collection of shots (sometimes, a scene can be a single shot) that happens in the same location or time. In motion graphics, because we are not bound to any physical location or time, the boundary from a scene to scene is blurry. Often times, a designer uses a visual transition to smooth out the change. 

A **sequence** is a narrative unit and usually made up of several scenes. A sequence itself can be thought of a self-contained story on its own.

Knowing these units will not only help you communicate when working on your project alone or with other people, but also let you think about and question the medium itself. Watch [the opening sequence of Touch of Evil (1958)](https://www.youtube.com/watch?v=Yg8MqjoFvy4) by Orson Wells or Snake Eyes by Brian De Palma as inspirations.


## Resolutions
If you are only going to present your work on computer screen, it can be as tall or wide as you want, but if you are thinking of publishing for TV, DVD, etc., then you will have to follow the standards. For our purpose, you only have to deal with 2 different High Definition resolution --- 720p and 1080p. 

![Resolution comparison](../images/w1/resolutions.png)


### 720p
720p has a screen size of 1280 pixels wide and 720 pixels tall (1280 x 720px), and it has a 16 by 9 aspect ratio.

### 1080p
1080p has a screen size of 1920 pixels wide and 1080 pixels tall (1920 x 1080px), and it alo has a 16 by 9 aspect ratio. Some say it's a *2K* video by counting the pixels horizontally.

### What is the 'p' at the end?
There are 2 different types of scanning methods to draw a picture on a screen. *Interlaced* video displays either *odd* or *even* scan lines at a time. The switching of the lines are fast, so we don't usually perceive it, but this method falls short when objects on a screen move fast.

*P* means that it's *progressive*. It means the full picture is displayed at any time. Simply put, Progressive has a lot more image data, therefore, it provides a better video quality than interlaced video.

If you only work with computer-generated images and video, you don't have to worry about your video being interlaced or progressive. However, if you work with a video camera, you will want to check the specification to see which method it supports.

### 4K resolution
4K video has about 4000 pixels or more horizontally, for example, 3840 x 2160px. Youtube already supports 4K videos. In the near future, we will all enjoy *Ultra HD* videos. More pixels mean better quality, right? But, if your monitor screen resolution is less than 4K, then playing 4K videos will not make any difference. And, to play 4K videos, it requires a powerful processor.


## Frame rates
If you've been following along, you know that the frames must be played in succession at an adequate speed. That speed is determined by frame rate. We use the unit, *fps* for frames per second. Have you seen a really old film footage where people move awkwardly fast as if some was pushing down fast forward button? That's because back in the days, film was shot at a different speed.

Remember that as the frame rate gets higher, you will achieve smoother movements. But, you can't just get higher and higher. It requires more time to produce animation and technologically, there is a certain limit on how many frames your computer can play in a second.

In the United States, we use 24fps for film and 30fps for TV. The standards are different in other countries. Many European countries use 25fps. Why 30fps for TV? That is because AC electricity runs at 60 times per second or 60Hz. Cut that in half gives us 30Hz or 30fps. It is a way of keeping time in the old days. In Europe, AC runs at 50Hz, therefore, 25fps.

### Ones, Twos, Threes and so on
Traditionally, the full animation is when it is produced at 24 or 30fps, meaning every frame is animated. This is a lot of work, especially, for TV shows that need to release a new episode every week. Think about it. If you make a 10-minute long animation at 30fps, that mean you have to animate 18000 drawings. So, a lot of studios create limited animation by skipping every other frame or so. When we say animate *on ones*, it means every frame is animated. *On twos* means every other frame is animated. And *on threes* and *on fours* and so on...

### 23.976fps or 29.97fps?
You will often see frame rates having a weird decimal number. We know that a frame is a drawing or a picture, then how can there be 23.976 drawings per second? There is no 0.976 drawings. It is to keep up with [NTSC standard](https://en.wikipedia.org/wiki/NTSC) and a way to sync a timecode with picture frames. More information is in [this video](https://www.youtube.com/watch?v=3GJUM6pCpew&feature=youtu.be).

These strange standards were introduced when color TV sets were replacing B&W sets when everyone was happy with 30fps. But because color signal had more information, they had to make room for it by reducing approximately 0.03fps.

I think it is a wonderful, albeit horrible, story that shows how difficult it is to change the standards even though we know that the old is not good enough. TVs are used by billions of people every day, and there are millions of cameras and other equipment set to support the old standard. You can't just change it in one day. 

Then, what frame rate do we choose? The decision should not only based on what is available to you as a creator, but also who your audience is and how your work will be viewed. This kind of considerations should be all planned in advance because changing the settings like resolution and frame rate in the middle of the production is something you will definitely want to avoid.

## Audio 
If you have sound effects or music track in your work, try to get the best quality audio files. An *mp3* file is fine but it's a lossy format whereas *aiff* or *wav* is lossless and will give you better quality sound.


## Codecs
A digital image is made up of pixels, and a digital video is made up of a series of these images. It sounds simple, but once you get to the practical side of making videos, it's not that simple. When you export your work into a video, you will *encode* the video, and when you open the video in a video player, it will *decode* it. Why do we have to go through this process? Can't we just collect the raw images and display them as a video? It's the same reason as why we have many image formats such as jpg, gif, png, etc. Showing raw images is impractical. It's just too much data to transmit. So, different types of codecs have been developed to encode and decode data to make files smaller while keeping the quality.

We will look at a few video codecs that we will be using in the class below.

### Animation
This is a *lossless* codec, meaning that you don't lose any quality by using this codec. Think of TIFF or TGA image files. So, that's good news, and that's all I want. Not quite. Even after encoding, the file size will be very big, and many casual machines will not be able to play the video in real time because the data it contains is huge. If you need to back up the original copy of your work, this could be a good option.

### Apple ProRes 4:2:2
When you encode videos with ProRes 4:2:2, you still lose the quality a bit (it's *lossy*), but it's not that noticeable. In fact, this is a great codec to use while in production. 

### H.264
If you are publishing to the web, this is *the* codec you want to use. It is supported by virtually every computer and device. There is obviously a compromise in quality, but the file size will be manageable for real time streaming. Use this codec only when you are exporting at the end of the production. It is not a good format to use while working and editing.

### Other Codecs
Depending on the studio's or client's requirement, you may need to use different codecs than the ones mentioned above. Usually, you should get an instruction either from your producer, director or editor. You can also search for which codec works best for any given task.




## Further Learning
- A quick [5 minute video](https://www.youtube.com/watch?v=GhWki9a7s18) explaining what a codec is.
