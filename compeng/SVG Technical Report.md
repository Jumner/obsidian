# SVG Technical Report
---
## Abstract
SVG or **S**calable **V**ector **G**raphics are an image format that stores the information as **instructions** to create the image instead of the image itself. They require **much less space** and are able to be scaled up infinitely without getting pixelated [^1]. The single downside is you can't use it for pictures.

## Rationale
This topic is very important for **logos** as you never know what resolution someone will view your logo with. Plus, it looks very unprofessional to have a pixelated logo. Therefore it is important that logos are able to be scaled up and down to any size. SVGs simply provide a new way of thinking about image formats. Why store the instructions to create an image of a specific size only for it to be resized later when you can store the information to create the image in the first place; at any size.

## Summary

### A. What is it?
> Scalable Vector Graphics are a image format that is unlike any others. It is a **vector image format** which means it stores the instructions to create an image. It creates images out of lines and shapes rather than massive grids of pixels. Because of this, they take up much less space.

### B. When was it discovered?
> The SVG image format was released in **1999** [^2]. This was after it was chosen out of a lineup of other vector formats. This is likely because of its refined usage of **XML** [^2].

### C. Who invented it?
> The SVG image format was invented by a group of companies called the SVG Working Group [^1]. The group was created by W3C in **1998** and was intended to replace an older format.

### D. What are possible future applications
> Because of how well thought out the SVG image format was, it is still being used to this day; over **2 decades later**. The concepts that SVG is based on have been used in other ways. An example of this is parametric modeling. 3d modelling is usually stored as a bunch of triangles. But instead, parametric modeling is stored as instructions to create the object. A combination of basic shapes. They can then be converted to a bunch of triangles for other applications. This is how 3d printing works. To come full circle, SVG's are used frequently for 3d modelling. Even I have inserted an SVG and extruded it up to make an emblem. Overall, there are lots of possible future applications just considering how many applications its had so far.

## Extensions and Limitations
Though the SVG image format is amazing and has tons of applications. It is not without its flaws. 
- **SVG is slower**
Because your browser must build the image, very complex images may take a long time to be built and then rasterized [^3].
- **Other image formats cannot be perfectly converted to SVG**
You cannot **directly convert** another image format to SVG because they **do not contain the same information**. New information must be created in order to convert it. This is because other formats use a grid of colours which doesn't allow you to extract shapes and lines. Another program must **interpret the image** and try and recreate it.
- **SVG is only effective for simple images**
With more complex SVGs, not only do they take longer to load. But they also need to be made by hand or with expensive software. This makes complex images unrealistic.


# Part B
---

1. **What is SVG?**
The SVG or **S**calable **V**ector **G**raphics image format is a vector image format. This means that it stores **instructions** to create the image instead of a grid of colours. This gives the advantage that you can create the image at any size and it will not be pixelated. In comparison, if you zoom into a png, you will see the **individual pixels** and the effect will be ruined. 

2. **Identify some browser issues regarding SVG**
The SVG image format is not perfect and because it is instructions, they can be **interpreted differently**. This issue is exasperated by the fact that it is **handled by the browser**. If your website has an SVG with animations but someone is viewing it with a browser that does not yet support animations, the **SVG will be broken**. 

3. **What is SVG used for?**
The main use for the SVG image format is logos simply because they are viewed in so many sizes. You could have a bunch of different sized bitmap images or a single SVG that is scaled to the right size and then **converted to bitmap** when its displayed. Think about a grid of colours. Scaling it down in half is fine. Just average 4 pixels together into 1. But what about scaling a 64x64 px image to 27x27px. The image will look blury and distorted. **SVG does not have this issue**.

4. **What are some of the advantages to using SVG over Flash or .jpg files?**
The Jpeg image format is a **bitmap** image format. This means that it stores its information as a grid of colours. However, it's also **compressed** to remove unnecessary information. The advantages are that SVG images can be displayed at any size **without getting blurry or distorted**. Where as .jpg images should be displayed at their native resolute to look best.

5. **Are there any disadvantages to using SVG?**
Of course there are. No image format it perfect. That is why there are so many. The main disadvantage is that **images must be simple** and that it takes time for the computer to rasterize the svg into a bitmap that is then sent to the GPUs frame buffer. Compared to .jpg where the whole image is sent to the GPU where is it decompressed almost instantly then sent to the frame buffer.

6. **State two (2) specific applications where SVG could be used, or is being used.**
	1. Svg are used for nearly every **website logo**. I can see an application for application icons as well as they are stored as a bunch of differently sized images 
	2. For 3d modelling as I stated earlier. You design something 2d as an svg then revolve or extrude it to create a 3d object. **3d parametric modeling** would be nothing without SVGs and vector graphics.

7. **Did you run into any browser issues regarding SVG?**
Thankfully, **I did not**. There is a lot of work making sure that all the browsers are implementing SVG features in a consistent manner. However, it is **no guarantee**. I'm sure if I were making a logo for a large website, it probably cause me a great headache making sure it works on all browsers. 

# Part D: Personal Course Reflection
---

## The Course as a whole

#### What worked
As you know. I love this course! This was by far my favorite in all of high school and I will remember it forever. You take what should be a dull course and made it super **exiting and fun**. As always, it was certainly **not easy** and that's what makes it so good. A good example was the **Z80**s. For learning assembly, being thrown into the **deep end** works really well. I know I am certainly an outlier but that one week **taught me more than I could have imagined**. And I think it was also helpful for my classmates as they had to learn it from me or figure it out themselves. Probably also good practice for them because **I am not the best teacher**. Either way, that unit was amazing and from what I could tell, most people agree. As for the rest of the units, they were pretty much the same. It's just that the Z80 unit showed how great this course really is.

#### What didn't work
One thing I didn't like was that we didn't get to do the hacking unit. I was looking forward to that and was pretty **disappointed that Covid prevented it**.
Now one actual criticism. As someone who tries hard in your class and I don't think its a stretch to say I have the best understanding out of anyone. **It is very punishing** to write a test, hand it in first. Then get 100 because **I understood the material**. And then see people fall for the tricky questions only to be saved by others **passing them the answer key**. I would at least ask that you **don't hand out the answer key** until everyone is done. It just makes me feel robbed to have people getting marks that they really don't deserve. Especially when I work hard to make sure I have a solid understanding.

#### Were your learning objectives met by this course?
**Absolutely!** I was super happy that most of the course was **in person** because the **teamwork** required to get through this course is pretty significant. The **social aspect is great** and **I got a lot better at teaching**. Again mostly in the machine language and assembler units. **I was expecting a challenge and I got a challenge**. I just want to **thank you** for making this course so rewarding. I have never been more glad that I took this course instead of computer science in grade 10.

## The Performance Task

#### What worked
The performance task was **a lot of fun** and it was cool making SVGs by hand. I had no idea they were **XML** based as most image formats are in **binary**. I think its really important for **web design** to understand SVGs. I know I used them in my **personal website** for some nice designs but never really understood how they worked. I just thought it was pretty cool to cover SVGs.

#### What didn't work
The performance task was a lot of fun but I felt like it was **too much writing and not enough computer engineering**. I would love if it was more **open ended**. I feel like it was a bit **underwhelming**. I found the grade 10 performance task much better. But I think you could have done a super open ended project. **You could have made it anything** in the course or anything computer engineering related. Then just make a write up explaining what you did why and what challenges you experienced. Because I would have **killed** to **pull out the Z80s** and write some more **complex programs**, or have some fun with the **breadboards**, or write about **ghost proofs**, or write about **my turing extension**. I feel like it could have been **so much better**.

#### Were your learning objectives met by this performance task?
I certainly learned a lot about SVGs but I feel like it was a **missed opportunity**. Plus its hard to cheat when asked **general questions**. Again, not gonna name names but I saw a lot of google searches for android robot svg and I'm pretty sure that **didn't help their learning**.

## Bibliography

[^1]: W3C. (2010). SCALABLE VECTOR GRAPHICS (SVG). W3C SVG Working Group. Retrieved January 21, 2022, from https://www.w3.org/Graphics/SVG/ 

[^2]: Mozilla. (2021, December 23). Introduction - SVG: Scalable Vector Graphics | MDN. Retrieved January 21, 2022, from https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Introduction

[^3]: Why is SVG so slow! | The Future Web. (2013, August 10). Frozeman. Retrieved January 21, 2022, from http://frozeman.de/blog/2013/08/why-is-svg-so-slow/
