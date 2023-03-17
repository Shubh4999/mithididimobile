# Customizing Chrome Default Page

In this Pen, I am going to be customizing the Chrome's default page.

A Pen by Shubh Khandelwal on CodePen.
Original Url:
[https://codepen.io/ShubhKhandelwal69/pen/ZEMRwMx](https://codepen.io/ShubhKhandelwal69/pen/ZEMRwMx)

[License](https://codepen.io/license/pen/ZEMRwMx).


# index.html

```html
<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>CodePen - Customizing Chrome Default Page</title>
  <link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<!DOCTYPE html>
<html lang="en">

  <head>
<meta charset="UTF-8">

    <title>Title</title>
  <link rel="stylesheet" href="./style.css">

  </head>
<body>

<!-- partial:index.partial.html -->

<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,500;0,700;0,900;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet"><link rel="stylesheet" href="./style.css">

</head>

<body>

<!-- partial:index.partial.html -->

  <div id="main-wrapper" class="fancy-scrollbar">

    <div id="main">

      <div id="content">

        <div id="links-container"  style="padding-left: 30%; padding-right: 30%;">

          <a href="https://gmail.com">Gmail</a>

   <a href="http://theanimecentresupport.blogspot.com">My site</a>
          <a href="https://codepen.io/ShubhKhandelwal69/pen/ZEMRwMx">Code of This Project</a>

        </div>

      <div class="mycontainer" style="padding-left: 30%; padding-right: 30%; padding-top: 1%;">

        <div id="header-container">

          <div class='parent'>

            <div class='child'><main>

              <div class="atom">

                  <div class="electron"></div>

                  <div class="electron-alpha"></div>

                  <div class="electron-omega"></div>

              </div>

          </main></div>

            <div class="social-buttons">

  

              <a href="mailto:shubhusa49@gmail.com" class="social-button--mail" aria-label="Mail">

                <i class="fa-solid fa-envelope"></i>

              </a>

              <a href="https://www.instagram.com/" class="social-button social-button--instagram" aria-label="Instagram">

                <i class="fab fa-instagram"></i>

              </a>

              <a href="https://www.youtube.com/" class="social-button social-button--youtube" aria-label="YouTube">

                <i class="fab fa-youtube"></i>

              </a>

              <a href="https://www.facebook.com/" class="social-button social-button--facebook" aria-label="Facebook">

                <i class="fab fa-facebook-f"></i>

              </a>

              <a href="https://t.me/TheAnimeCentreDiscussions" class="social-button social-button--telegram" aria-label="Telegram">

                <i class="fa-brands fa-telegram"></i>

                </a>

              <a href="https://www.twitter.com/" class="social-button social-button--twitter" aria-label="Twitter">

                <i class="fa-brands fa-twitter"></i>

              </a>

            </div></div>

            </div>

        

          

        

 

        

<div id="search-container" style="margin-top: 5%;">

          <div id="search-input-container">

            <img src="https://assets.codepen.io/1468070/Google+G+Icon.png" alt="" />

            <input type="text" placeholder="Search anything" id="search" />

          </div>

          <button id="image-button" onclick="googleSearch();" type="button">

            <i class="fa-regular fa-search"></i>

          </button>

          <button id="mic-button" type="button">

            <i class="fa-regular fa-microphone"></i>

          </button>

     

      

          </div>

          

          

 

        <div id="apps-container">

          <a href="123series.world">

            <img src="https://iili.io/HXL1c4p.png" style="height: 24px; width: 24px;">

            <div class="label">

              <span class="name">123series</span>

              <span class="url">123series.world</span>

            </div>

          </a>

          <a href="https://chat.openai.com">

            <svg width="26" height="26" viewBox="0 0 41 41" fill="#10A37F" xmlns="http://www.w3.org/2000/svg" stroke-width="1.5" class="h-6 w-6"><path d="M37.5324 16.8707C37.9808 15.5241 38.1363 14.0974 37.9886 12.6859C37.8409 11.2744 37.3934 9.91076 36.676 8.68622C35.6126 6.83404 33.9882 5.3676 32.0373 4.4985C30.0864 3.62941 27.9098 3.40259 25.8215 3.85078C24.8796 2.7893 23.7219 1.94125 22.4257 1.36341C21.1295 0.785575 19.7249 0.491269 18.3058 0.500197C16.1708 0.495044 14.0893 1.16803 12.3614 2.42214C10.6335 3.67624 9.34853 5.44666 8.6917 7.47815C7.30085 7.76286 5.98686 8.3414 4.8377 9.17505C3.68854 10.0087 2.73073 11.0782 2.02839 12.312C0.956464 14.1591 0.498905 16.2988 0.721698 18.4228C0.944492 20.5467 1.83612 22.5449 3.268 24.1293C2.81966 25.4759 2.66413 26.9026 2.81182 28.3141C2.95951 29.7256 3.40701 31.0892 4.12437 32.3138C5.18791 34.1659 6.8123 35.6322 8.76321 36.5013C10.7141 37.3704 12.8907 37.5973 14.9789 37.1492C15.9208 38.2107 17.0786 39.0587 18.3747 39.6366C19.6709 40.2144 21.0755 40.5087 22.4946 40.4998C24.6307 40.5054 26.7133 39.8321 28.4418 38.5772C30.1704 37.3223 31.4556 35.5506 32.1119 33.5179C33.5027 33.2332 34.8167 32.6547 35.9659 31.821C37.115 30.9874 38.0728 29.9178 38.7752 28.684C39.8458 26.8371 40.3023 24.6979 40.0789 22.5748C39.8556 20.4517 38.9639 18.4544 37.5324 16.8707ZM22.4978 37.8849C20.7443 37.8874 19.0459 37.2733 17.6994 36.1501C17.7601 36.117 17.8666 36.0586 17.936 36.0161L25.9004 31.4156C26.1003 31.3019 26.2663 31.137 26.3813 30.9378C26.4964 30.7386 26.5563 30.5124 26.5549 30.2825V19.0542L29.9213 20.998C29.9389 21.0068 29.9541 21.0198 29.9656 21.0359C29.977 21.052 29.9842 21.0707 29.9867 21.0902V30.3889C29.9842 32.375 29.1946 34.2791 27.7909 35.6841C26.3872 37.0892 24.4838 37.8806 22.4978 37.8849ZM6.39227 31.0064C5.51397 29.4888 5.19742 27.7107 5.49804 25.9832C5.55718 26.0187 5.66048 26.0818 5.73461 26.1244L13.699 30.7248C13.8975 30.8408 14.1233 30.902 14.3532 30.902C14.583 30.902 14.8088 30.8408 15.0073 30.7248L24.731 25.1103V28.9979C24.7321 29.0177 24.7283 29.0376 24.7199 29.0556C24.7115 29.0736 24.6988 29.0893 24.6829 29.1012L16.6317 33.7497C14.9096 34.7416 12.8643 35.0097 10.9447 34.4954C9.02506 33.9811 7.38785 32.7263 6.39227 31.0064ZM4.29707 13.6194C5.17156 12.0998 6.55279 10.9364 8.19885 10.3327C8.19885 10.4013 8.19491 10.5228 8.19491 10.6071V19.808C8.19351 20.0378 8.25334 20.2638 8.36823 20.4629C8.48312 20.6619 8.64893 20.8267 8.84863 20.9404L18.5723 26.5542L15.206 28.4979C15.1894 28.5089 15.1703 28.5155 15.1505 28.5173C15.1307 28.5191 15.1107 28.516 15.0924 28.5082L7.04046 23.8557C5.32135 22.8601 4.06716 21.2235 3.55289 19.3046C3.03862 17.3858 3.30624 15.3413 4.29707 13.6194ZM31.955 20.0556L22.2312 14.4411L25.5976 12.4981C25.6142 12.4872 25.6333 12.4805 25.6531 12.4787C25.6729 12.4769 25.6928 12.4801 25.7111 12.4879L33.7631 17.1364C34.9967 17.849 36.0017 18.8982 36.6606 20.1613C37.3194 21.4244 37.6047 22.849 37.4832 24.2684C37.3617 25.6878 36.8382 27.0432 35.9743 28.1759C35.1103 29.3086 33.9415 30.1717 32.6047 30.6641C32.6047 30.5947 32.6047 30.4733 32.6047 30.3889V21.188C32.6066 20.9586 32.5474 20.7328 32.4332 20.5338C32.319 20.3348 32.154 20.1698 31.955 20.0556ZM35.3055 15.0128C35.2464 14.9765 35.1431 14.9142 35.069 14.8717L27.1045 10.2712C26.906 10.1554 26.6803 10.0943 26.4504 10.0943C26.2206 10.0943 25.9948 10.1554 25.7963 10.2712L16.0726 15.8858V11.9982C16.0715 11.9783 16.0753 11.9585 16.0837 11.9405C16.0921 11.9225 16.1048 11.9068 16.1207 11.8949L24.1719 7.25025C25.4053 6.53903 26.8158 6.19376 28.2383 6.25482C29.6608 6.31589 31.0364 6.78077 32.2044 7.59508C33.3723 8.40939 34.2842 9.53945 34.8334 10.8531C35.3826 12.1667 35.5464 13.6095 35.3055 15.0128ZM14.2424 21.9419L10.8752 19.9981C10.8576 19.9893 10.8423 19.9763 10.8309 19.9602C10.8195 19.9441 10.8122 19.9254 10.8098 19.9058V10.6071C10.8107 9.18295 11.2173 7.78848 11.9819 6.58696C12.7466 5.38544 13.8377 4.42659 15.1275 3.82264C16.4173 3.21869 17.8524 2.99464 19.2649 3.1767C20.6775 3.35876 22.0089 3.93941 23.1034 4.85067C23.0427 4.88379 22.937 4.94215 22.8668 4.98473L14.9024 9.58517C14.7025 9.69878 14.5366 9.86356 14.4215 10.0626C14.3065 10.2616 14.2466 10.4877 14.2479 10.7175L14.2424 21.9419ZM16.071 17.9991L20.4018 15.4978L24.7325 17.9975V22.9985L20.4018 25.4983L16.071 22.9985V17.9991Z" fill="currentColor"></path></svg>

            <div class="label">

              <span class="name">Chat GPT</span>

              <span class="url">chat.openai.com</span>

            </div>

          </a>

          <a href="https://rewards.bing.com/">

            <?xml version="1.0" ?><!DOCTYPE svg  PUBLIC '-//W3C//DTD SVG 1.1//EN'  'http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd'><svg height="512px" style="enable-background:new 0 0 512 512;" version="1.1" viewBox="0 0 512 512" width="512px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><g id="_x32_16-microsoft"><g><rect height="215.65" style="fill:#F25022;" width="215.648" x="30.905" y="30.904"/><rect height="215.65" style="fill:#7FBA00;" width="215.648" x="265.446" y="30.904"/><rect height="215.651" style="fill:#00A4EF;" width="215.648" x="30.905" y="265.444"/><rect height="215.651" style="fill:#FFB900;" width="215.648" x="265.446" y="265.444"/></g></g><g id="Layer_1"/></svg>

            <div class="label">

              <span class="name">Microsoft Rewards</span>

              <span class="url">rewards.bing.com/</span>

            </div>

          </a>

          <a href="https://youtube.com">

            <?xml version="1.0" ?><!DOCTYPE svg  PUBLIC '-//W3C//DTD SVG 1.1//EN'  'http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd'><svg height="512px" style="enable-background:new 0 0 512 512;" version="1.1" viewBox="0 0 512 512" width="512px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><g id="_x33_95-youtube"><g><path d="M476.387,144.888c-5.291-19.919-20.878-35.608-40.67-40.933C399.845,94.282,256,94.282,256,94.282    s-143.845,0-179.719,9.674c-19.791,5.325-35.378,21.013-40.668,40.933c-9.612,36.105-9.612,111.438-9.612,111.438    s0,75.334,9.612,111.438c5.29,19.92,20.877,34.955,40.668,40.281C112.155,417.719,256,417.719,256,417.719    s143.845,0,179.717-9.674c19.792-5.326,35.379-20.361,40.67-40.281c9.612-36.104,9.612-111.438,9.612-111.438    S485.999,180.994,476.387,144.888z" style="fill:#FF0000;"/><polygon points="208.954,324.723 208.954,187.93 329.18,256.328   " style="fill:#FFFFFF;"/></g></g><g id="Layer_1"/></svg>

            <div class="label">

              <span class="name">YouTube</span>

              <span class="url">youtube.com/</span>

            </div>

          </a>

          <a href="https://spotify.com">

            <?xml version="1.0" encoding="UTF-8" standalone="no"?><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="48px" height="48px" viewBox="0 0 48 48" version="1.1"><title>Spotify-color</title><g id="Icons" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g id="Color-" transform="translate(-200.000000, -460.000000)" fill="#00DA5A"><path d="M238.16 481.36c-7.68-4.56-20.52-5.04-27.84-2.76-1.2.36-2.4-.36-2.76-1.44-.36-1.2.36-2.4 1.44-2.76 8.52-2.52 22.56-2.04 31.44 3.24 1.08.6 1.44 2.04.84 3.12-.6.84-2.04 1.2-3.12.6m-.24 6.72c-.6.84-1.68 1.2-2.52.6-6.48-3.96-16.32-5.16-23.88-2.76-.96.24-2.04-.24-2.28-1.2-.24-.96.24-2.04 1.2-2.28 8.76-2.64 19.56-1.32 27 3.24.72.36 1.08 1.56.48 2.4m-2.88 6.6c-.48.72-1.32.96-2.04.48-5.64-3.48-12.72-4.2-21.12-2.28-.84.24-1.56-.36-1.8-1.08-.24-.84.36-1.56 1.08-1.8 9.12-2.04 17.04-1.2 23.28 2.64.84.36.96 1.32.6 2.04M224 460c-13.2 0-24 10.8-24 24s10.8 24 24 24 24-10.8 24-24-10.68-24-24-24" id="Spotify"/></g></g><metadata><rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#" xmlns:dc="http://purl.org/dc/elements/1.1/"><rdf:Description about="https://iconscout.com/legal#licenses" dc:title="spotify,color" dc:description="spotify,color" dc:publisher="Iconscout" dc:date="2017-09-14" dc:format="image/svg+xml" dc:language="en"><dc:creator><rdf:Bag><rdf:li>Alexis Doreau</rdf:li></rdf:Bag></dc:creator></rdf:Description></rdf:RDF></metadata></svg>

            <div class="label">

              <span class="name">Spotify</span>

              <span class="url">spotify.com</span>

            </div>

          </a>

         

          <a href="https://netflix.com">

          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path fill="#AD080F" d="m10.17 13.46-.01 5.06c0 4.81-.01 5.08-.06 5.08-.18 0-1.7.1-2.21.15-.33.03-1 .1-1.48.16-.49.06-.89.1-.9.09 0-.01-.01-5.41-.01-12.01V0l4.67 13.46zM18.49.01h-4.63l-.01 5.31v5.329l4.63 13.341c.02-.01.02-5.42.02-12.01L18.49.01z"/><path fill="#DF0D12" d="M18.48 23.99h-.04c-.08 0-.24-.01-.43-.03-1.07-.13-2.48-.26-3.62-.31-.37-.02-.68-.04-.69-.04 0 0-.29-.84-.84-2.41-.53-1.53-1.31-3.77-2.32-6.68l-.37-1.06L5.5 0h4.65l.2.57.88 2.53 7.25 20.89z"/></svg>

            <div class="label">

              <span class="name">Netflix</span>

              <span class="url">netflix.com</span>

            </div>

          </a>

        

          <a href="#">

            <i class="fa-brands fa-github"></i>

            <div class="label">

              <span class="name">Github</span>

              <span class="url">github.com</span>

            </div>

          </a>

          <a href="#">

            <i class="fa-brands fa-xbox"></i>

            <div class="label">

              <span class="name">Xbox</span>

              <span class="url">xbox.com</span>

            </div>

          </a>

        </div>

      </div>

  </div>

  </div>

</div>

<!-- partial -->

  <script>

    function googleSearch()

    {

        var text=document.getElementById("search").value;

        var cleanQuery = text.replace(" ","+",text);

        var url='http://www.google.com/search?q='+cleanQuery;

    

        window.location.href=url;

    }

    </script>

  <script src='https://codepen.io/Hyperplexed/pen/xxYJYjM/54407644e24173ad6019b766443bf2a6.js'></script>

</body>

<!-- partial -->

  

</body>

</html>
<!-- partial -->
  
</body>
</html>


# style.css

```css
@import url('https://fonts.googleapis.com/css?family=Pacifico');
:root {
  --body-color: 48 48 58;
  
  --font-color: 255 255 255;
  --highlight-color: 0 0 0;
  
  --theme-background: 20 20 20;
  
  --theme-light: 0 0 0;
  --theme-medium: 0 0 0;
  --theme-dark: 0 0 0;
}

body {
  background-color: rgb(var(--body-color));
  margin: 0px;
}

body::-webkit-scrollbar {
  width: 4px;
}

body::-webkit-scrollbar-track {
  background-color: rgb(var(--theme-background));
}

body::-webkit-scrollbar-thumb {
  background: rgba(255, 255, 255, 0.15);
}

* {
  box-sizing: border-box;
}

h1, h2, h3, h4, input, select, button, span, a, p {
  color: rgb(var(--font-color));
  font-family: "Noto Sans", sans-serif;
  font-size: 1rem;
  font-weight: 400;
  margin: 0px;
}

button, a, input {  
  outline: none;
}

.highlight {
  color: rgb(var(--highlight-color));
}

.fancy-scrollbar::-webkit-scrollbar {
  height: 4px;
  width: 4px;
}

.fancy-scrollbar::-webkit-scrollbar-track {
  background-color: transparent;
}

.fancy-scrollbar::-webkit-scrollbar-thumb {
  background: rgba(255, 255, 255, 0.15);
}

.no-scrollbar::-webkit-scrollbar {
  height: 0px;
  width: 0px;
}

#phone {
  background-color: rgb(var(--theme-background));
  box-shadow: rgba(0, 0, 0, 0.2) 0px 8px 24px;
  height: 851px;
  width: 393px;  
  margin: 100px auto;
  position: relative;
  overflow: hidden;
}

#main-wrapper {
  height: 100%;
  overflow: auto;
}

#main {
  height: 100%;
}

#content {
  padding: 1rem;
}

#links-container {
  display: flex;
  align-items: center;
  justify-content: space-around;
  gap: 0.75rem;
}

#links-container > a {
  color: rgb(255 255 255 / 80%);
  font-size: 0.75rem;
  text-decoration: none;
}

#links-container > a:is(:hover, :focus) {
  text-decoration: underline; 
}

#header-container {
  width: 100%;
  position: relative;
  margin-top: 1rem;
}

#logo {
  display: flex;
  width: 100%; 
  border-radius: 0.5rem;
  border-bottom-left-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

#user-menu-button {
  height: 47%;
  position: absolute;
  right: 0rem;
  bottom: 0rem;
  background-color: transparent;
  margin-right: 3.52%;
  margin-bottom: 2.70%;
  padding: 0rem;
  border: none;
  border-radius: 100%;
}

#user-menu-button > img {
  display: flex;
  height: 100%;
  border-radius: inherit;
}

#search-container {
  display: flex;
  gap: 0.2rem;
  margin-top: 0.2rem;  
}

#search-input-container > input,
#search-container > button {
  background-color: rgb(255 255 255 / 10%);
  color: rgb(255 255 255 / 80%);
  font-size: 1rem;
  border: none;
}

#search-input-container:has(input:focus),
#search-container > button:focus {
  background-color: rgb(255 255 255 / 16%);
}

#search-container > button {
  width: 3.5rem;
  border-radius: 0.2rem;
  cursor: pointer;
}

#search-container > #image-button {  
  border-bottom-right-radius: 0.5rem;
}

#search-input-container {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  background-color: rgb(255 255 255 / 10%);
  padding-left: 1rem;
  border-radius: 0.2rem;
  border-bottom-left-radius: 0.5rem;
}

#search-input-container > img {
  height: 1.5rem;
}

#search-input-container > input {
  width: 100%;
  height: 3.25rem;
  background-color: transparent;
  padding: 1rem;  
  padding-left: 0rem;
}

#apps-container {
  display: grid;
  gap: 0.2rem;
  grid-template-columns: repeat(2, 50%);  
  margin: 3rem 0rem;
}

#apps-container > a {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  background-color: rgb(255 255 255 / 10%);
  padding: 1rem 0.75rem;
  border-radius: 0.2rem;
  text-decoration: none;
}

#apps-container > a > i {
  height: 2rem; 
  width: 2rem; 
  flex-shrink: 0;
  font-size: 1.5rem;
  line-height: 2rem; 
  text-align: center;
}

#apps-container > a > .label {
  width: calc(100% - 2.5rem);
  display: flex;
  flex-direction: column;
  align-self: flex-start;
  overflow: hidden;
}

#apps-container > a > .label > :is(.name, .url) {
  width: 100%;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow: hidden;
}

#apps-container > a > .label > .name {
  font-size: 0.8rem;
}

#apps-container > a > .label > .url {
  font-size: 0.7rem;
  color: rgb(255 255 255 / 50%);
}

#apps-container > a:is(:hover, :focus) {
  background-color: rgb(255 255 255 / 16%);
}

#apps-container > a:first-child {
  border-top-left-radius: 0.5rem;
}

#apps-container > a:nth-child(2) {  
  color: rgb(255, 0, 0);
  border-top-right-radius: 0.5rem;
}

#apps-container > a:nth-child(3) {  
  color: rgb(28, 204, 91);
}

#apps-container > a:nth-child(4) {  
  color: rgb(28, 147, 228);
}

#apps-container > a:nth-child(5) {  
  color: rgb(242, 85, 90);
}

#apps-container > a:nth-child(7) {  
  border-bottom-left-radius: 0.5rem;
}

#apps-container > a:last-child {
  color: rgb(15, 118, 14);
  border-bottom-right-radius: 0.5rem; 
}

#discover-container {
  width: 100%;
}

#discover-toggles {
  width: 80%;
  display: flex; 
  background-color: rgb(255 255 255 / 7.5%);
  margin: auto;
  border-radius: 0.5rem;
}

#discover-toggles > button {
  flex-grow: 1;
  background-color: transparent;
  padding: 0.75rem;
  border: none;
  border-radius: 0.5rem;
  outline: none;
  font-size: 0.8rem;
  cursor: pointer;
}

#discover-toggles > button:first-child {
  border-top-right-radius: 0.5rem;
  border-bottom-right-radius: 0.5rem;
  background-color: rgb(255 255 255 / 10%);
}

#discover-toggles > button:last-child {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

#discover-feed {
  margin-top: 0.5rem;
}

.discover-card {
  display: flex;
  flex-direction: column;
  gap: 0.25rem;
  text-decoration: none;
}

.discover-card > img {
  width: 100%;
  aspect-ratio: 1.6 / 1;
  object-fit: cover;
  border-radius: 0.5rem;
  border-bottom-left-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.discover-card > .discover-card-info {
  display: flex;
  flex-direction: column;
  gap: 0.25rem;
  background-color: rgb(255 255 255 / 10%);
  padding: 0.75rem;
  border-radius: 0.5rem;
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem;
}

.discover-card > .discover-card-info > .title {
  font-size: 0.8rem;
}

.discover-card > .discover-card-info > .desc {
  font-size: 0.7rem;
  color: rgb(255 255 255 / 50%);
}

@media(max-width: 500px) {
  body {
    overflow: auto;  
  }
  
  #phone {
    height: 100vh;
    display: flex;
    width: 100%;
    margin: 0px auto;
  }
  
  #main-wrapper {
    width: 100%;
    flex-grow: 1;
  }
}

.social-buttons {
  display: flex;
  flex-wrap: wrap;
  justify-content: right;
  gap: 8px;

}
.social-button {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  outline: none;
  width: 30px;
  height: 30px;
  text-decoration: none;
  border-radius: 100%;
  background: #fff;
  text-align: center;
}
.social-button::after {
  content: '';
  position: absolute;
  top: -1px;
  left: 50%;
  display: block;
  width: 0;
  height: 0;
  border-radius: 100%;
  transition: 0.3s;
}
.social-button:focus, .social-button:hover {
  color: #fff;
}
.social-button:focus::after, .social-button:hover::after {
  width: calc(100% + 2px);
  height: calc(100% + 2px);
  margin-left: calc(-50% - 1px);
}
.social-button i, .social-button svg {
  position: relative;
  z-index: 1;
  transition: 0.3s;
}
.social-button i {
  font-size: 20px;
}
.social-button svg {
  height: 40%;
  width: 40%;
}
.social-button--instagram {
  color: #3f729b; /* adjust the color to match your design */
  background-color: white;
  border: none;
  padding: 0;
  margin: 0 5px;
  font-size: 24px; /* adjust the font size to match the other icons */
}
.social-button--youtube {
  color: #ff0000; /* adjust the color to match your design */
  background-color: white;
  border: none;
  padding: 0;
  margin: 0 5px;
  font-size: 24px; /* adjust the font size to match the other icons */
}
.social-button--mail {
  color: #0072c6;
}
.social-button--mail::after {
  background: #0072c6;
}
.social-button--facebook {
  color: #3b5999;
}
.social-button--facebook::after {
  background: #3b5999;
}
.social-button--telegram {
  color: #0088cc;
}
.social-button--telegram::after {
  background: #0088cc;
}
.social-button--linkedin {
  color: #0077b5;
}
.social-button--linkedin::after {
  background: #0077b5;
}
.social-button--twitter {
  color: #55acee;
}
.social-button--twitter::after {
  background: #55acee;
}
.social-button--instagram {
  color: #e4405f;
}
.social-button--instagram::after {
  background: #e4405f;
}
.social-button--npmjs {
  color: #c12127;
}
.social-button--npmjs::after {
  background: #c12127;
}

/* animated logo effect */

:root {
  --atom-size: 180px;
  --atom-color-hex: #00d8ff;
  --atom-color-rgb: 0, 216, 255;
  --nucleus-size: calc(var(--atom-size) / 5);
  --electron-color-hex: #99f8ff;
  --electron-size : calc(var(--atom-size) / 25);
  --electron-orbit-size : calc(var(--atom-size) / 2.5);
  --electron-speed : 1.2s;
  --electron-speed-alpha : 1s;
  --electron-speed-omega : .8s;
}


*, *:before, *::after { box-sizing: border-box; }


/* Atom */
.atom {
  position: relative;
  width: var(--atom-size);
  height: var(--atom-size);
  animation: 8s atom infinite cubic-bezier(1, .25, 0, .75);
}
@keyframes atom {
  0% {    transform: rotate(0deg) scale(1); }
  12.5% { transform: rotate(-45deg) scale(.9); }
  25% {   transform: rotate(-90deg) scale(1); }
  37.5% { transform: rotate(-135deg) scale(.9); }
  50% {   transform: rotate(-180deg) scale(1); }
  62.5% { transform: rotate(-225deg) scale(.9); }
  75% {   transform: rotate(-270deg) scale(1); }
  87.5% { transform: rotate(-315deg) scale(.9); }
  100% {  transform: rotate(-360deg) scale(1); }
}

/* Nucleus */
.atom::before {
  content: '';
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  width: var(--nucleus-size);
  height: var(--nucleus-size);
  margin-top: calc(var(--nucleus-size) / -2);
  margin-left: calc(var(--nucleus-size) / -2);
  background: var(--electron-color-hex); /* var(--atom-color-hex); */
  border-radius: 100%;
  box-shadow: 0 0 3px 0 var(--atom-color-hex);
  animation: 2s nucleus infinite cubic-bezier(.65, 0, .35, 1);
}
@keyframes nucleus {
  0% { transform: scale(1); }
  25% { transform: scale(.9); }
  50% { transform: scale(1); }
  75% { transform: scale(.85); }
  100% { transform: scale(1); }
}

/* Electron Orbit */
.atom > [class^="electron"] {
  border-top: solid rgba(var(--atom-color-rgb), .5) 1px;
  border-right: solid rgba(var(--atom-color-rgb), .35) 2px;
  border-bottom: solid rgba(var(--atom-color-rgb), .2) 4px;
  border-left: solid rgba(var(--atom-color-rgb), 0) 2px;
  border-radius: 100%;
  width: 100%;
  height: var(--electron-orbit-size);
  position: absolute;
  top: 50%;
  margin-top: calc(var(--electron-orbit-size) / -2);
  animation: var(--electron-speed) electron-orbit infinite linear;
}
.atom > .electron-alpha {
  transform: rotate(60deg);
  animation: var(--electron-speed-alpha) electron-orbit infinite linear;
}
.atom > .electron-omega {
  transform: rotate(-60deg);
  animation: var(--electron-speed-omega) electron-orbit infinite linear;
}
@keyframes electron-orbit {
  0% {
      border-top: solid rgba(var(--atom-color-rgb), .5) 1px;
      border-right: solid rgba(var(--atom-color-rgb), .35) 2px;
      border-bottom: solid rgba(var(--atom-color-rgb), .2) 4px;
      border-left: solid rgba(var(--atom-color-rgb), 0) 2px;
  }
  25% {
      border-top: solid rgba(var(--atom-color-rgb), .35) 1px;
      border-right: solid rgba(var(--atom-color-rgb), .2) 2px;
      border-bottom: solid rgba(var(--atom-color-rgb), 0) 4px;
      border-left: solid rgba(var(--atom-color-rgb), .5) 2px;
  }
  50% {
      border-top: solid rgba(var(--atom-color-rgb), .2) 1px;
      border-right: solid rgba(var(--atom-color-rgb), 0) 2px;
      border-bottom: solid rgba(var(--atom-color-rgb), .5) 4px;
      border-left: solid rgba(var(--atom-color-rgb), .35) 2px;
  }
  75% {
      border-top: solid rgba(var(--atom-color-rgb), 0) 1px;
      border-right: solid rgba(var(--atom-color-rgb), .5) 2px;
      border-bottom: solid rgba(var(--atom-color-rgb), .35) 4px;
      border-left: solid rgba(var(--atom-color-rgb), .2) 2px;
  }
  100% {
      border-top: solid rgba(var(--atom-color-rgb), .5) 1px;
      border-right: solid rgba(var(--atom-color-rgb), .35) 2px;
      border-bottom: solid rgba(var(--atom-color-rgb), .2) 4px;
      border-left: solid rgba(var(--atom-color-rgb), 0) 2px;
  }
}

/* Electron Unit */
.atom [class^="electron"]::after {
  content: '';
  display: block;
  width: var(--electron-size);
  height: var(--electron-size);
  background: var(--electron-color-hex);
  border-radius: 50%;
  margin-top: calc(var(--electron-size) / -2);
  position: absolute;
  top: 50%;
  left: calc(var(--electron-size) / -1);
  transform: scale(1);
  animation: calc(var(--electron-speed) * 2) electron infinite ease-in-out;
}
.atom .electron-alpha::after { animation: calc(var(--electron-speed-alpha) * 2) electron infinite ease-in-out; }
.atom .electron-omega::after { animation: calc(var(--electron-speed-omega) * 2) electron infinite ease-in-out; }
@keyframes electron {
  0% {
      left: calc(var(--electron-size) / -1);
      transform: scale(1);
  }
  12.5% {
      top: 100%;
      transform: scale(1.5);
  }
  25% {
      left: 100%;
      transform: scale(1);
  }
  37.5% {
      top: 0%;
      transform: scale(.25);
  }
  50% {
      left: calc(var(--electron-size) / -1);
      transform: scale(1);
  }
  62.5% {
      top: 100%;
      transform: scale(1.5);
  }
  75% {
      left: 100%;
      transform: scale(1);
  }
  87.5% {
      top: 0%;
      transform: scale(.25);
  }
  100% {
      left: calc(var(--electron-size) / -1);
      transform: scale(1);
  }
}

/* Shadow */
main { position: relative; }
main::after {
  content: '';
  display: block;
  position: absolute;
  top: 115%;
  left: 0;
  width: var(--atom-size);
  height: var(--nucleus-size);
  background-image: radial-gradient(closest-side, rgba(0, 0, 0, .5), rgba(0, 0, 0, 0));
  border-radius: 100%;
  transform: scale(1, .8);
  animation: 8s shadow infinite cubic-bezier(1, .25, 0, .75);
}
@keyframes shadow {
  0% {    transform: scale(1, .8) translateY(0); }
  12.5% { transform: scale(.7, .7) translateY(-20px); }
  25% {   transform: scale(1, .8) translateY(0); }
  37.5% { transform: scale(.7, .7) translateY(-20px); }
  50% {   transform: scale(1, .8) translateY(0); }
  62.5% { transform: scale(.7, .7) translateY(-20px); }
  75% {   transform: scale(1, .8) translateY(0); }
  87.5% { transform: scale(.7, .7) translateY(-20px); }
  100% {  transform: scale(1, .8) translateY(0); }
}

/* Credits */
footer {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 4rem;
  display: grid;
  place-items: center;
}
a {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Droid Sans", "Helvetica Neue", Arial, sans-serif;;
  font-size: smaller;
  font-weight: lighter;
  text-decoration: none;
  padding: .6rem .8rem;
  border-radius: .3rem;
  color: rgba(255, 255, 255, .25);
  background: rgba(0, 0, 0, 0);
  transition: all .35s ease-in-out;
}
a:hover {
  color: rgba(255, 255, 255, 1);
  background: rgba(0, 0, 0, .5);
}
.parent {
  border: 1px solid black;
  margin: 1rem;
  padding: 2rem 2rem;
  text-align: center;
}
.child {
  display: inline-block;
  padding: 1rem 1rem;
  vertical-align: middle;
}


button {
  border: none;
  cursor: pointer;
  background-color: transparent;
  outline: none;
}

svg {
  height: 1.6rem;
  width: 1.6rem;
}

.text-truncate {
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
}

.dropdown-container {
  margin-top: 30vh;
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 34rem;
}

.dropdown-title-icon,
.dropdown-arrow {
  display: inline-flex;
}

.dropdown-title {
  margin: 0 auto 0 1.8rem;
  text-transform: capitalize;
}

.dropdown-button {
  font-family: "Roboto", sans-serif;
  font-weight: 400;
  font-size: 1.7rem;
  display: flex;
  align-items: center;
  padding: 0 1.8rem;
}

.dropdown-button svg {
  transition: all var(--transition-time) var(--transition-timing);
  fill: var(--text-color);
}

.dropdown-button svg,
.dropdown-button span {
  pointer-events: none;
}

.dropdown-button:hover,
.dropdown-button:focus {
  color: var(--text-active);
}

.dropdown-button:hover svg,
.dropdown-button:focus svg {
  fill: var(--text-active);
}

.main-button {
  height: 5.2rem;
  border-radius: var(--border-radius);
  color: var(--text-color);
  background-color: var(--primary-bg-color);
  border: 0.1rem solid var(--border-color);
  transition: all var(--transition-time) var(--transition-timing);
}

.main-button:focus {
  border: 0.1rem solid var(--primary-color);
  box-shadow: 0 0 0 0.2rem rgba(44, 98, 246, 0.4);
}

.main-button .dropdown-arrow {
  transition: transform var(--transition-time) var(--transition-timing);
  transform: rotate(var(--rotate-arrow));
  margin-left: 1.8rem;
}

.list-button {
  height: var(--list-button-height);
  transition: color var(--transition-time) var(--transition-timing);
  color: var(--text-color);
  overflow: hidden;
  cursor: none;
}

.dropdown-list-container {
  overflow: hidden;
  max-height: var(--dropdown-height);
  transition: max-height var(--transition-time) var(--transition-timing);
}

.dropdown-list-wrapper {
  margin-top: 1rem;
  padding: 1rem;
  background-color: var(--primary-bg-color);
  border-radius: var(--border-radius);
  border: 0.1rem solid var(--border-color);
  position: relative;
}

ul.dropdown-list {
  position: relative;
  list-style-type: none;
}

ul.dropdown-list::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  z-index: 0;
  opacity: 0;
  height: var(--list-button-height);
  background-color: var(--button-hover-bg-color);
  transition: all var(--transition-time) linear;
  transform: translateY(var(--translate-value));
  border-radius: var(--border-radius);
  pointer-events: none;
}
ul.dropdown-list:hover::before,
ul.dropdown-list:hover ~ .floating-icon {
  opacity: 1;
}

li.dropdown-list-item {
  display: flex;
  flex-direction: column;
  position: relative;
  z-index: 1;
  opacity: var(--list-opacity);
  transition: opacity 0.8s var(--transition-timing);
}

.floating-icon {
  height: calc(var(--floating-icon-size) * 1px);
  width: calc(var(--floating-icon-size) * 1px);
  position: absolute;
  top: var(--floating-icon-top);
  left: var(--floating-icon-left);
  background-color: var(--border-color);
  border-radius: 1rem;
  pointer-events: none;
  opacity: 0;
  transition: opacity var(--transition-time) var(--transition-timing);
  z-index: 2;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

.floating-icon svg {
  fill: var(--text-active);
}

@-webkit-keyframes blinkH1 {
  0%   {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;
  }
  19%   {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;
  }
  20% {
      color: #9E9E9E;
    text-shadow: none;  
  }
  21% {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;  
  }
  60% {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;  
  }
  61% {
      color: #9E9E9E;
    text-shadow: none;  
  }
  62% {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;  
  }
  63% {
      color: #9E9E9E;
    text-shadow: none;  
  }
  64% {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;  
  }
  100% {
      color: #fff;
    text-shadow: 0px 0px 20px #00aad4;  
  }
}

@-webkit-keyframes blinkH1After {
  0%   {
      color: #00aad4;
  }
  19%   {
      color: #00aad4;
  }
  20% {
      color: transparent; 
  }
  21% {
      color: #00aad4;  
  }
  60% {
      color: #00aad4;  
  }
  61% {
      color: transparent; 
  }
  62% {
      color: #00aad4;  
  }
  63% {
      color: transparent; 
  }
  64% {
      color: #00aad4;  
  }
  100% {
      color: #00aad4;  
  }
}

@-webkit-keyframes blinkH1Before {
  0%   {
      background: #00aad4;
  }
  19%   {
      background: #00aad4;
  }
  20% {
      background: transparent; 
  }
  21% {
      background: #00aad4;  
  }
  60% {
      background: #00aad4;  
  }
  61% {
      background: transparent; 
  }
  62% {
      background: #00aad4;  
  }
  63% {
      background: transparent; 
  }
  64% {
      background: #00aad4;  
  }
  100% {
      background: #00aad4;  
  }
}

.searchContainer {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.box {
  width: 45%;
  height: 200px;
  background-color: #f2f2f2;
  border: 1px solid #ccc;
  box-sizing: border-box;
}
