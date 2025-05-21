# Webhosts
Webhosts can be used to open Sev Essentials with very low effort
## Official
[google sites](https://sites.google.com/lsr7.net/sevessentialshost/home) | [wix](https://sevisadev.wixstudio.com/sev-essentials)
## Un-Official

# Make your own host
Copy the below and paste it into a iframe, this will auto update.
```html
<!DOCTYPE html><html><head><title>Sev Essentials Loader</title><style>body{font-family:"Times New Roman",serif;background-color:#000000;padding:20px;color:#800080;margin:0;overflow:hidden}canvas{position:fixed;top:0;left:0;z-index:-1}h2{color:#ffffff}button{font-size:20px;padding:12px 24px;background-color:#8a2be2;color:white;border:none;border-radius:8px;cursor:pointer;font-family:'Times New Roman',serif}button:hover{background-color:#6a0dad}</style></head><body><button onclick="openMain()">Open</button><script>function openMain(){fetch('https://raw.githubusercontent.com/sevisadev/sev-essentials/main/html%20holder.html').then(response=>{if(!response.ok)throw new Error('Network response was not ok');return response.text()}).then(html=>{const newWindow=window.open('about:blank','_blank');if(newWindow){newWindow.document.write(html);newWindow.document.close();window.close()}else{alert('Pop-up blocked. Please allow pop-ups for this site.')}}).catch(error=>{alert('Failed to load HTML: '+error.message)})}</script></body></html>
```
