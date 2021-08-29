<template>
  <div>
    <header>
      <img src="img/background.png" class="header-img" />
      <nav class="menu">
        <ul class="menu-ul">
          <li class="menu-li">
            <a href="#"
              ><p class="menu-p">
                はじめに<br /><span class="en">About</span>
              </p></a
            >
          </li>
          <li class="menu-li">
            <a href="#news">
              <p class="menu-p">新着情報<br /><span class="en">News</span></p>
            </a>
          </li>
          <li class="menu-li">
            <a href="#">
              <p class="menu-p">
                ストーリー<br /><span class="en">Story</span>
              </p>
            </a>
          </li>
          <li class="menu-li">
            <a href="#">
              <p class="menu-p">
                クラスター<br /><span class="en">Cluster</span>
              </p>
            </a>
          </li>
          <li class="menu-li">
            <a href="#video">
              <p class="menu-p">動画<br /><span class="en">Video</span></p></a
            >
          </li>
          <li class="menu-li">
            <a href="#photo">
              <p class="menu-p">フォト<br /><span class="en">Photo</span></p></a
            >
          </li>
        </ul>
      </nav>
    </header>
    <div class="background">
      <div class="background-color">
        <div class="about main">
          <figure class="about-figure"></figure>
          <div class="about-text">参団説明文</div>
        </div>
      </div>
      <div class="background-color">
        <div class="section main">
          <h2 id="news" class="section-title">
            <span class="section-span">What's New</span>
          </h2>
          <div class="whats-new">
            <p>お知らせ欄</p>
          </div>
        </div>
      </div>
      <div class="background-color">
        <div class="section main">
          <div class="sns">
            <div class="twitter">
              <h2 class="section-title">
                <span class="section-span">Twitter</span>
              </h2>
              <div class="twitter-embed">
                <a
                  data-width="375"
                  data-height="420"
                  class="twitter-timeline"
                  data-chrome="noheader nofooter"
                  data-lang="ja"
                  href="https://twitter.com/dassochu_150th"
                  >Tweets by dassochu_150th</a
                >
                <script
                  async
                  src="https://platform.twitter.com/widgets.js"
                  charset="utf-8"
                ></script>
              </div>
            </div>
            <div class="others">
              <h2 class="section-title">
                <span class="section-span">SNS</span>
              </h2>
              <div class="others-img">
                <a
                  href="https://www.youtube.com/channel/UC4k91Gh_IhqyIWcw_mhgfLA/"
                  target="_blank"
                >
                  <img src="img/banner/YouTube.png" />
                </a>
                <a href="#" target="_blank">
                  <img src="img/banner/Cluster.png" />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="background-color">
        <div class="section main">
          <h2 id="video" class="section-title">
            <span class="section-span">Video</span>
          </h2>
          <div class="video">
            <div class="video-div">
              <span class="video-tag" style="background-color: #ca0915"
                >最新動画</span
              >
              <img src="img/thumbnail/thumbnail.webp" class="video-img" />
              <p class="video-text">説明文</p>
            </div>
            <div class="video-div">
              <span class="video-tag" style="background-color: #18ca09"
                >最新動画</span
              >
              <img src="img/thumbnail/thumbnail.webp" class="video-img" />
              <p class="video-text">説明文</p>
            </div>
            <div class="video-div">
              <span class="video-tag" style="background-color: #cac209"
                >最新動画</span
              >
              <img src="img/thumbnail/thumbnail.webp" class="video-img" />
              <p class="video-text">説明文</p>
            </div>
          </div>
          <div class="video-others">
            <a
              href="https://www.youtube.com/channel/UC4k91Gh_IhqyIWcw_mhgfLA/videos"
              class="video-others-text"
              >その他の動画はこちらから</a
            >
          </div>
        </div>
      </div>
      <div class="background-color">
        <div class="section main">
          <h2 id="photo" class="section-title">
            <span class="section-span">Photo</span>
          </h2>
          <div class="photo">
            <div class="photo-div">
              <img src="img/thumbnail/thumbnail.webp" class="photo-img" />
            </div>
            <div class="photo-div">
              <img src="img/thumbnail/thumbnail.webp" class="photo-img" />
            </div>
            <div class="photo-div">
              <img src="img/thumbnail/thumbnail.webp" class="photo-img" />
            </div>
            <br />
            <div class="photo-div">
              <img src="img/thumbnail/thumbnail.webp" class="photo-img" />
            </div>
            <div class="photo-div">
              <img src="img/thumbnail/thumbnail.webp" class="photo-img" />
            </div>
            <div class="photo-div">
              <img src="img/thumbnail/thumbnail.webp" class="photo-img" />
            </div>
          </div>
          <div class="photo-others">
            <a href="#" class="photo-others-text">その他の写真はこちらから</a>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <div class="footer-copyright">
        <p>©Dassochu2021</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

/* all */

* {
  font-family: sans-serif;
}

p {
  margin: 0 auto;
}

a,
a:hover {
  text-decoration: none;
}

/* header */

.header-img {
  width: 100%;
  max-height: 95%;
}

/* menu */

.menu {
  margin: 0 auto;
  background-color: rgba(153, 14, 14, 0.95);
  position: relative;
}

.menu-ul {
  width: 1000px;
  margin: 0 auto;
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}

.menu-li {
  display: inline-block;
  vertical-align: top;
  text-align: center;
  width: 150px;
  height: 100px;
  position: relative;
}

.menu-li a {
  width: 100%;
  height: 100%;
  color: #fff;
  vertical-align: middle;
  z-index: 5;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
  transition-duration: 0.5s;
}

.menu-p {
  font-size: 145%;
  font-weight: bold;
}

.en {
  color: #fff;
  display: inline-block;
  padding: 0.2em 0 0;
  font-size: 80%;
  font-family: pressio-condensed, sans-serif;
  font-weight: 400;
  font-style: normal;
}

/* background */

.background {
  background: url('/img/background.png');
  background-repeat: repeat;
  background-position: center top;
  z-index: 0;
  position: relative;
}

.background::before {
  content: '';
  background: inherit;
  -webkit-filter: blur(1px);
  -moz-filter: blur(1px);
  -o-filter: blur(1px);
  -ms-filter: blur(1px);
  filter: blur(1px);
  position: absolute;
  top: -0.1px;
  left: -0.1px;
  right: -0.1px;
  bottom: -0.1px;
  z-index: -1;
}

.background-color {
  background-color: rgba(9, 9, 102, 0.6);
}

/* main */

.main {
  width: 1000px;
  margin: 0 auto;
}

/* about */

.about {
  padding: 2em 0 3.5em;
}

.about-figure {
  width: 380px;
  height: 198px;
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  display: inline-block;
  margin: 1em 1.8em 0 1.5em;
  vertical-align: top;
  background-image: url('/icon.png');
}

.about-text {
  width: calc(100% - 460px);
  display: inline-block;
  padding: 0;
  color: #fff;
}

/* section */

.section {
  padding: 2em 0 3.5em;
}

.section-title {
  text-align: center;
  display: block;
  font-size: 330%;
  color: rgb(202, 9, 21);
}

.section-span {
  font-family: headline-gothic-atf, sans-serif;
  font-weight: 600;
  font-style: normal;
  letter-spacing: 0.05em;
}

/* whats-new */

.whats-new {
  border-radius: 5px;
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  background-color: #fff;
  filter: drop-shadow(2px 2px 4px rgba(0, 0, 0, 0.3));
  padding: 30px;
}

/* sns */

.sns {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-items: center;
}

.twitter {
  width: calc(50% - 1em);
  height: 500px;
}

.twitter-embed {
  text-align: center;
}
.others {
  width: calc(50% - 1em);
  height: 500px;
}

.others-img {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.others-img img {
  margin: 1em auto;
}

/* video */

.video {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-items: center;
}
.video-div {
  width: calc(33.4% - 1em);
  text-align: center;
}

.video-tag {
  color: #fff;
  padding: 5px 20px;
}
.video-img {
  width: 100%;
  height: auto;
  margin: 20px 0;
}
.video-text {
  color: #fff;
}

.video-others {
  margin-top: 1.5em;
  text-align: right;
}

.video-others-text,
.video-others-text:hover {
  font-size: 15pt;
  color: #fff;
  border-bottom: double 6px #fff;
}

/* photo */

.photo {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
  align-items: center;
}

.photo-div {
  width: calc(33.4% - 1em);
  text-align: center;
  margin: 0.5em auto;
}

.photo-img {
  width: 100%;
  height: auto;
}

.photo-others {
  margin-top: 1.5em;
  text-align: right;
}

.photo-others-text,
.photo-others-text:hover {
  font-size: 15pt;
  color: #fff;
  border-bottom: double 6px #fff;
}

/* footer */

footer {
  padding: 1em 0;
  background: #4c4c4c;
}

.footer-copyright {
  color: #fff;
  font-size: 14pt;
  font-weight: 400;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
