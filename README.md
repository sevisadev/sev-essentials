# Sev Essentials
## Description
A html based site with tools, games, proxys, and more.
## How to use
**Easy:** You can use [webhost](https://github.com/sevisadev/sev-essentials/blob/main/more/webhost.md) if not unavalible, webhosts are much easier to use.

**Medium one:** Copy and paste the below into your search bar.
```html
data:text/html;charset=utf-8,%3C!DOCTYPE%20html%3E%3Chtml%3E%3Chead%3E%3Ctitle%3ESev%20Essentials%20Loader%3C%2Ftitle%3E%3Cstyle%3Ebody%7Bfont-family%3A%22Times%20New%20Roman%22%2Cserif%3Bbackground-color%3A%23000000%3Bpadding%3A20px%3Bcolor%3A%23800080%3Bmargin%3A0%3Boverflow%3Ahidden%7Dcanvas%7Bposition%3Afixed%3Btop%3A0%3Bleft%3A0%3Bz-index%3A-1%7Dh2%7Bcolor%3A%23ffffff%7Dbutton%7Bfont-size%3A20px%3Bpadding%3A12px%2024px%3Bbackground-color%3A%238a2be2%3Bcolor%3Awhite%3Bborder%3Anone%3Bborder-radius%3A8px%3Bcursor%3Apointer%3Bfont-family%3A'Times%20New%20Roman'%2Cserif%7Dbutton%3Ahover%7Bbackground-color%3A%236a0dad%7D%3C%2Fstyle%3E%3C%2Fhead%3E%3Cbody%3E%3Cbutton%20onclick%3D%22openMain()%22%3EOpen%3C%2Fbutton%3E%3Cscript%3Efunction%20openMain()%7Bfetch('https%3A%2F%2Fraw.githubusercontent.com%2Fsevisadev%2Fsev-essentials%2Fmain%2Fhtml%2520holder.html').then(response%3D%3E%7Bif(!response.ok)throw%20new%20Error('Network%20response%20was%20not%20ok')%3Breturn%20response.text()%7D).then(html%3D%3E%7Bconst%20newWindow%3Dwindow.open('about%3Ablank'%2C'_blank')%3Bif(newWindow)%7BnewWindow.document.write(html)%3BnewWindow.document.close()%3Bwindow.close()%7Delse%7Balert('Pop-up%20blocked.%20Please%20allow%20pop-ups%20for%20this%20site.')%7D%7D).catch(error%3D%3E%7Balert('Failed%20to%20load%20HTML%3A%20'%2Berror.message)%7D)%7D%3C%2Fscript%3E%3C%2Fbody%3E%3C%2Fhtml%3E
```

**Meduim two:** Download the [downloadable file](https://github.com/sevisadev/sev-essentials/blob/main/more/downloadable.html) and open it with your browser.

**Hard:** Copy the below and go to an html runner ([HTML RUNNERS](https://github.com/sevisadev/sev-essentials/blob/main/more/html%20runner.md)) and paste in the copyed code. After pasted, run it then click open.
```html
<!DOCTYPE html><html><head><title>Sev Essentials Loader</title><style>body{font-family:"Times New Roman",serif;background-color:#000000;padding:20px;color:#800080;margin:0;overflow:hidden}canvas{position:fixed;top:0;left:0;z-index:-1}h2{color:#ffffff}button{font-size:20px;padding:12px 24px;background-color:#8a2be2;color:white;border:none;border-radius:8px;cursor:pointer;font-family:'Times New Roman',serif}button:hover{background-color:#6a0dad}</style></head><body><button onclick="openMain()">Open</button><script>function openMain(){fetch('https://raw.githubusercontent.com/sevisadev/sev-essentials/main/html%20holder.html').then(response=>{if(!response.ok)throw new Error('Network response was not ok');return response.text()}).then(html=>{const newWindow=window.open('about:blank','_blank');if(newWindow){newWindow.document.write(html);newWindow.document.close();window.close()}else{alert('Pop-up blocked. Please allow pop-ups for this site.')}}).catch(error=>{alert('Failed to load HTML: '+error.message)})}</script></body></html>
```
