# FullscreenWindowTemplate    
Unity WebGL template that scales to the entire browser/container window at constant rendering pixel count (think of constant resolution, but not quite that).  
It's made to achieve consistent performance on devices with unbalanced (screen-resolution to GPU) hardware combination. Besides, it's simple and designed for easy modding.  
  
1. Copy WebGLTemplates folder into the Assets folder.  
2. Go to Edit -> Project Settings -> Player -> WebGL -> Resolution and Presentation -> WebGL Template.  
3. Select the template. If you still can't see a new template, make sure you've copied the folder correctly.
4. If you're swapping an old version of this template, select other template and reselect this template again.  
5. Enter desired render resolution defined in amount of pixels like `2138400` for 1080p. You get the pixel count number by multiplying the resolution numbers like 1920\*1080 = 2138400. By default it's 1280\*720 for mobile and 2560\*1440 for desktop, so most of the time leaving those settings empty would do the trick.
