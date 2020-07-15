### Hi there, I'm [Sahil !](https://sahilodes)🙋‍♂️<img src="https://raw.githubusercontent.com/boyknowstech/boyknowstech/master/svg/pronouns/hehim.svg" >

<a href="https://twitter.com/sahilkathoke">
  <img align="left" alt="Sahil Kathoke| Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="https://www.linkedin.com/in/sahil7066367404/">
  <img align="left" alt="Linkedin" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a href="https://www.instagram.com/boyknowstech/">
  <img align="left" alt="Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a href="https://www.hackerrank.com/sahilkathoke1999">
  <img align="left" alt="hackerrank" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/hackerrank.svg" />
</a>

![](https://visitor-badge.glitch.me/badge?page_id=boyknowstech.boyknowstech)


******************* 

### I'm 21 years old Self-taught Full-Stack developer from India.
<br />

#### - 🥀 Learning Angular  <code><img height="20" src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/frameworks/angular.svg"></code>,JavaScript <code> <img height="20" src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/languages/js.svg"> </code> & Web <code><img height="20" src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/misc/web.svg"></code>.

#### - 🔭 Tech FanBoi, 

#### - 🛸 Into The Sea of InterNet 

#### - 💬 Connect? Here 👉🏼[<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/social/twitter.svg" >](https://twitter.com/sahilkathoke/) [<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/social/linkedin.svg" >](https://www.linkedin.com/sahil7066367404)


*******************

**I am Into , 🙏**

**Web Development,Competetive Programming, Desktop Application, Machine Learning & Digital Marketing 😼**

**Languages and Tools:**  
<p align="center">

<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/languages/html.svg" alt="html" style="vertical-align:top; margin:4px">    
<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/languages/csharp.svg" alt="csharp" style="vertical-align:top; margin:4px">
<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/languages/js.svg" alt="js" style="vertical-align:top; margin:4px">
<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/languages/python.svg" alt="python" style="vertical-align:top; margin:4px">
<img src="https://github.com/boyknowstech/boyknowstech/blob/master/svg/dev/tools/visualstudio_code.svg" alt="vscode" style="vertical-align:top; margin:4px">

</p>


<br>

[![Github Stats By Anurag](https://github-readme-stats.vercel.app/api?username=boyknowstech&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github.com/anuraghazra/github-readme-stats)



# Dynamic Github Profile
> Refresh this page to see different Images

![](https://bingimages.herokuapp.com/unsplash1)

# What?
we can  show dynamic Images on our github profile special repository ```githubhandle/githubhandle```
by creating an API which returns different images

example: 
> using unsplash random images
```md
https://source.unsplash.com/random/800x400
``` 
will show a random image like this

![](https://bingimages.herokuapp.com/unsplash2)

## Ideas
we can use this and create various different kind of profiles, some examples of that are: -
- Based on Time, we can create something like dynamic wallpapers in mac
- Based on Festivals, we can greet our profile visitor and make something special on special occasions
- Based on Birthdays, we can let our visitors know about our birthdays and create special effects on our profile
- Based on Daily Wallpapers or Quotes, you can show a daily quote on your github profile
- Based on News that you follow
- Based On random Thing that you like 
    - example ```https://source.unsplash.com/random/800x400?star ```
- Based on Your Latest Instagram post
# How? 
> for creating dynamic effect you have to host a server which returns your content

Code Snippet for creating route in Express.js
```js
app.get("/unsplash", (req, res) => {
  request("https://source.unsplash.com/random/800x200")
    .on("response", response => {
      response.headers['Cache-Control'] = 'max-age=0, no-cache, no-store, must-revalidate'
    })
    .pipe(res);
})
```








#### Thank You-🙏🏼


***********************************


  
