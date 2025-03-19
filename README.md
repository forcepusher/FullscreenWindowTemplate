# FullscreenWindowTemplate    
Unity WebGL template that scales to the entire browser/container window at constant rendering pixel count (think of constant resolution).  
  
1. Copy WebGLTemplates folder into the Assets folder.  
2. Go to Edit -> Project Settings -> Player -> WebGL -> Resolution and Presentation -> WebGL Template.  
3. Select the template. If you still can't see a new template, make sure you've copied the folder correctly.
4. If you're swapping an old version of this template, select other template and reselect this template again.  
5. Enter desired render resolution defined in amount of pixels (1080p is `2138400` = 1920*1080). You can use an expression in a setting like `1920*1080`. By default it's 1280*720 for mobile and 2560*1440 for desktop.
