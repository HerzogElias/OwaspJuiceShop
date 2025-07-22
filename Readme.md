Readme 

# Table of Contents 


## Perrquites 

## Quickstart 



## Usage 
You can also Start your own Owasp Juice Shop Instance on your Compouter. 


1. Install Perequireties 
``` bash
sudo apt install nodejs
sudo apt install npm
```

1. Clone the following Repository 
``` bash
git clone https://github.com/juice-shop/juice-shop.git
```


2. Navigate to the Correct Directory. 
```bash
cd juice-shop
```


3. Start the Juice Shop 
``` bash
npm start 
```

4. Open your Juice Shop on your Browser with:
```bash
127.0.0.1:3000
```



## Possible Attacs 
### XSS Song 
1. Navigate to Serchnavigation: 
<img src="/XSS_Suchleiste.png">

2. Put this following Iframe on the Search Field: 
```bash
<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/771984076&color=%23ff5500&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>
```

3. Reload your Page. 

4. Now you can see a Box where you can play and stop the loaded Music. 

### Admin Login with SQL Injection 
### Every else No Safty example
