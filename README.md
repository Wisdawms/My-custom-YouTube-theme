<h2> After installing <a href="https://chromewebstore.google.com/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle">Enhancer for YouTube</a> extension, go to its settings and paste this code in the 'Custom Theme' box after checking it: </h2>

<pre>
  <code>
:root { --dimmer-text: #484054; --hover-background: #232225; --main-background: #121112; --main-color: #3e3847; --main-text: #725e4b; --second-background: #19191a; --shadow: 0 1px .5px rgba(23, 22, 23, .2); }

[class="yt-spec-button-shape-next yt-spec-button-shape-next--text yt-spec-button-shape-next--mono yt-spec-button-shape-next--size-s"]:hover,
[class="yt-spec-button-shape-next yt-spec-button-shape-next--text yt-spec-button-shape-next--mono yt-spec-button-shape-next--size-s yt-spec-button-shape-next--icon-button yt-spec-button-shape-next--override-small-size-icon"]:hover {
background-color: var(--hover-background) !important;
}

*[role="text"]::selection{
    color: var(--main-text) !important;
    background-color: transparent !important;
}

/* --main-color: #3e3847*/

span[class="yt-core-attributed-string--highlight-text-decorator"]{
background-color: var(--hover-background) !important;
}

* {
font-family: 'Source Code Pro';
font-size: 16px;
}

#voice-search-button {
display: none;
}
#search::placeholder{
color: var(--main-color) !important;
}
button:hover > * > * > * path{
transition: 0.5s fill ease;
}
button:hover > * > * > * path{
fill: var(--main-color);
}

path {
fill: var(--main-text);
}

#description.ytd-watch-metadata{
background: #19191a;
}
#input-container{
background-color: rgb(25, 25, 26) !important;
}

*[role="text"]{
color: var(--dimmer-text);
}

button > div> span[role="text"]{
color: var(--main-text);
}
  </code>
</pre>

<h3>Screenshots:</h3><br>
<img src="https://i.imgur.com/LIFFRCb.png" alt="Screenshot demonstration #1"><br>
<img src="https://i.imgur.com/Yw0kocU.png" alt="Screenshot demonstration #2"><br>
<img src="https://i.imgur.com/gBjccMO.png" alt="Screenshot demonstration #3"><br>
