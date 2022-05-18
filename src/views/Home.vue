<template>
  <div class="container">
    <div id="name-container">
      <img id="avatar" src="./../assets/images/av.png" alt="avatar" />
      <h1>LiiUM</h1>
    </div>
    <div class="title-desc-container">
      <a id="github" href="https://github.com/L11UM" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/github.svg" />Developer</a
      >
      <span>/</span>
      <a id="sspai" href="" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/sspai.svg" />Writer</a
      >
      <span>/</span>
      <a id="blog" href="" target="_blank" rel="noopener noreferrer"
        ><img class="title-font" src="./../assets/images/zeit.svg" />Blogger</a
      >
    </div>
    <div class="article">
      <h2>WHO AM I</h2>
      <p>
        I'm <i>LiiUM</i> 
        Welcome to my personal site
      </p>

      <h2>Work In Progress:</h2>
      <ul>
        <li><em><a href="instagram.com/iosociety" target="_blank">io.society</a></em></li>
        
        
          
          
        
        <li>🔭 <b>Fields of interest:</b> Neural Networks//Software Development</li>
      </ul>

      <h2>Tools</h2>
      <ul>
        <li>⚫ Custom PC: 1080Ti, Ryzen 5 3600 </li>
        <li>🔵 Apple M1 Chip with 8-Core CPU and 7-Core GPU</li>
      </ul>
      <h2>Contacts</h2>
      <ul>
        <li>
          <b>Email</b>
          <a href="mailto:liambt20@gmail.com">liambt20#gmail.com</a><i> (Preferred)</i>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="css" scoped>
#name-container {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
}
#avatar {
  width: 42px;
  height: 42px;
  border-radius: 50%;
  margin-right: 12px;
}
#copyright:hover {
  border: none;
}
.title-font {
  width: 16px;
  height: 16px;
  margin-right: 4px;
}
.title-desc-container {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  margin: 8px 0;
}
.title-desc-container a {
  display: flex;
  align-items: center;
}
.title-desc-container span {
  margin: 0px 4px;
}
.title-desc-container #github {
  color: #24292e;
}
.title-desc-container #sspai {
  color: #ca2c2a;
}
.title-desc-container #blog {
  color: #0070f3;
}
</style>
