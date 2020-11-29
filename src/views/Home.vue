<template>
  <div class="home-page">
    <div class="banner">
      <div class="container">
        <h1 class="logo-font">Medium Clone</h1>
        <p>Get close in personal with great ideas</p>
      </div>
    </div>
    <div class="container page">
      <div class="row">
        <div class="col-md-9">
          <div class="feed-toggle">
            <ul class="nav nav-pills outline-active">
              <li class="nav-item">
                <a href="" class="nav-link disable">Your feeds</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link active">Global Feeds</a>
              </li>
            </ul>
          </div>
          <div class="article-preview">
            <div class="article-meta">
              <a href="profile.html"
                ><img src="http://i.imgur.com/Qr71crq.jpg"
              /></a>
              <div class="info">
                <a href="" class="author">Kriss Kawa</a>
                <span class="date">February 20th</span>
              </div>
              <button class="btn btn-outline-primary btn-sm pull-xs-right">
                <i class="ion-heart"></i> 28
              </button>
            </div>
            <a href="" class="preview-link">
              <h1>How to build robust and dynamic React Native apps</h1>
              <p>Learn about basics of React Native app development</p>
              <span>Read more...</span>
            </a>
          </div>

          <div class="article-preview">
            <div class="article-meta">
              <a href="profile.html"
                ><img src="http://i.imgur.com/N4VcUeJ.jpg"
              /></a>
              <div class="info">
                <a href="" class="author">Gaza Lang</a>
                <span class="date">March 20th</span>
              </div>
              <button class="btn btn-outline-primary btn-sm pull-xs-right">
                <i class="ion-heart"></i> 10
              </button>
            </div>
            <a href="" class="preview-link">
              <h1>The mark of good web developer.</h1>
              <p>This is the description for the post.</p>
              <span>Read more...</span>
            </a>
          </div>
        </div>
        <div class="col-md-3">
        <div class="sidebar">
          <p><strong>Popular Tas</strong></p>
          <div class="tag-list">
            <a href="" class="tag-pill tag-default">Android</a>
            <a href="" class="tag-pill tag-default">Website</a>
            <a href="" class="tag-pill tag-default">Software Engineer</a>
            <a href="" class="tag-pill tag-default">TTD</a>
            <a href="" class="tag-pill tag-default">Angular</a>
            <a href="" class="tag-pill tag-default">Vue</a>
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
