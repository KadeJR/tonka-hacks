<script setup>
  import NavBar from "./components/NavBar.vue";
  import Trending from "./components/Trending.vue";
  import ContentCard from "./components/ContentCard.vue";
  import CreateSubmission from "./components/CreateSubmission.vue";

  function submissionVisible() {
    document.getElementById("CreateSubmission").style.visibility="visible";
  }

  function submissionHidden() {
        document.getElementById("CreateSubmission").style.visibility="hidden";
    }
  
  function addImage() {
      document.getElementById("image").src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Shaqi_jrvej.jpg/1200px-Shaqi_jrvej.jpg";
  }
</script>

<template>
    <header class="nav_bar">
      <NavBar/>
    </header>

    <header class="content">
      <div class="content_container">
        <div class="content_box">
        <header class="user_header">
            <text class="user_name">Sustain Media User</text> <text class="user_id">@sustain_media_user</text>
        </header>

        <header class="title_header">
            <text class="title_text">Post Title</text>
        </header>


        <div>
            <img class="post_img" src="https://natureconservancy-h.assetsadobe.com/is/image/content/dam/tnc/nature/en/photos/WOPA160517_D056-resized.jpg?crop=864%2C0%2C1728%2C2304&wid=600&hei=800&scl=2.88"/>
        </div>
        <div class="interaction_button_container">
            <div class="interaction_button"  style="padding-top: 10px; padding-bottom: 3px; padding-left: 8px; padding-right: 5px;">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-heart-fill" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"/>
                    </svg>
            </div>
            <div class="interaction_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-chat-fill" viewBox="0 0 16 16">
                    <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
                </svg>
            </div>
            <div class="interaction_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-box-arrow-up" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M3.5 6a.5.5 0 0 0-.5.5v8a.5.5 0 0 0 .5.5h9a.5.5 0 0 0 .5-.5v-8a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 1 0-1h2A1.5 1.5 0 0 1 14 6.5v8a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 14.5v-8A1.5 1.5 0 0 1 3.5 5h2a.5.5 0 0 1 0 1h-2z"/>
                    <path fill-rule="evenodd" d="M7.646.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8.5 1.707V10.5a.5.5 0 0 1-1 0V1.707L5.354 3.854a.5.5 0 1 1-.708-.708l3-3z"/>
                </svg>
            </div>
            <div class="interaction_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-bookmarks-fill" viewBox="0 0 16 16">
                    <path d="M2 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v11.5a.5.5 0 0 1-.777.416L7 13.101l-4.223 2.815A.5.5 0 0 1 2 15.5V4z"/>
                    <path d="M4.268 1A2 2 0 0 1 6 0h6a2 2 0 0 1 2 2v11.5a.5.5 0 0 1-.777.416L13 13.768V2a1 1 0 0 0-1-1H4.268z"/>
                </svg>
            </div>
        </div>
    </div>
        <ul class="content_dir">
            <li class="content_item">
              <div class="content_box">
        <header class="user_header">
            <text class="user_name">Sustain Media User</text> <text class="user_id">@sustain_media_user</text>
        </header>

        <header class="title_header">
            <text class="title_text">Post Title</text>
        </header>


        <div>
            <img class="post_img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Shaqi_jrvej.jpg/1200px-Shaqi_jrvej.jpg"/>
        </div>
        <div class="interaction_button_container">
            <div class="interaction_button"  style="padding-top: 10px; padding-bottom: 3px; padding-left: 8px; padding-right: 5px;">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-heart-fill" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"/>
                    </svg>
            </div>
            <div class="interaction_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-chat-fill" viewBox="0 0 16 16">
                    <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
                </svg>
            </div>
            <div class="interaction_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-box-arrow-up" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M3.5 6a.5.5 0 0 0-.5.5v8a.5.5 0 0 0 .5.5h9a.5.5 0 0 0 .5-.5v-8a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 1 0-1h2A1.5 1.5 0 0 1 14 6.5v8a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 14.5v-8A1.5 1.5 0 0 1 3.5 5h2a.5.5 0 0 1 0 1h-2z"/>
                    <path fill-rule="evenodd" d="M7.646.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8.5 1.707V10.5a.5.5 0 0 1-1 0V1.707L5.354 3.854a.5.5 0 1 1-.708-.708l3-3z"/>
                </svg>
            </div>
            <div class="interaction_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-bookmarks-fill" viewBox="0 0 16 16">
                    <path d="M2 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v11.5a.5.5 0 0 1-.777.416L7 13.101l-4.223 2.815A.5.5 0 0 1 2 15.5V4z"/>
                    <path d="M4.268 1A2 2 0 0 1 6 0h6a2 2 0 0 1 2 2v11.5a.5.5 0 0 1-.777.416L13 13.768V2a1 1 0 0 0-1-1H4.268z"/>
                </svg>
            </div>
        </div>
    </div>
            </li>

        </ul>
    </div>
    </header>

    <div class="post_button" @click="submissionVisible()">
        <text class="post_button_text">Post</text>
    </div>

    <header class="create_submission_visibility" id="CreateSubmission">
      <div class="post_container">
        <header class="title_header">
            <input class="title_input" placeholder="Enter Title"/>
        </header>
        <div class="image_container">
            <div class="add_img_button" @click="addImage()">
                <svg xmlns="http://www.w3.org/2000/svg" width="65" height="65" fill="#2222222" class="bi bi-plus-circle-fill" viewBox="0 0 16 16">
                    <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3z"/>
                </svg>
            </div>
            <img class="added_img" src="" id="image"/>
        </div>
        <div class="button" @click="submissionHidden()"><text class="button_text">Cancel</text></div>
        <div class="button" @click="submissionHidden()"><text class="button_text" style="margin-left: 40px;">Post</text></div>
    </div>
    </header>

    <header class="trending">
      <Trending/>
    </header>
</template>

<style>
body {
  background-color: #202020;
  font-family: Arial, Helvetica, sans-serif;
}

header.nav_bar {
  height: 95%;
  width: 20%;
  background-color: #272727;
  border-radius: 10px; 
  padding: 10px;
  text-align: center;
  position: absolute;
}

header.content {
  height: 95%;
  width: 52.3%;
  position: absolute;
  padding: 10px;
  left: 23%;
  z-index: 0;
  align-items: center;
  overflow-y: auto;
}

header.trending {
  height: 95%;
  width: 20%;
  background-color: #272727;
  border-radius: 10px; 
  padding: 10px;
  text-align: center;
  position: absolute;
  left: 78%;
}

div.content_container {
        align-items: center;
    }

ul.content_dir {
        list-style-type: none;
        padding: 0px;
    }

li.content_item {
        padding: 0px
    } 

@keyframes post_button_hover {
  from{background-color: #1e8337;}
  to{background-color: #29af4a;}
}

div.post_button {
  background-color: #1e8337;
  width: 10%;
  height: 20px;
  text-align: center;
  padding: 10px;
  border-radius: 5px;
  position: absolute;
  top: 88%;
  left: 63.5%;
}  

div.post_button:hover {
  animation-name: post_button_hover;
  animation-duration: 100ms;
  background-color: #29af4a;
  position: absolute;
  z-index: 4;
}

div.post_button:active {
  background-color: #1e8337;
}

text.post_button_text {
  font-size: 20px;
  color: #222222;
} 

header.create_submission_visibility {
  z-index: 10;
  visibility: hidden;
}

::-webkit-scrollbar {
  width: 10px;
  border-radius: 100%;
}

::-webkit-scrollbar-track {
  background: #222222;
  border-radius: 5px;
}

::-webkit-scrollbar-thumb {
  background: #2b2b2b;
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: #3b3b3b;
  border-radius: 5px;
}

div.post_container {
        height: 95%;
        width: 52.3%;
        position: absolute;
        padding: 10px;
        left: 23%;
        background-color: #222222;
        border-color: #2b2b2b;
        border-width: 5px;
        border-style: solid;
        border-radius: 10px;
    }

    header.title_header {
        width: 100%;
        display: inline-flex;
        text-align: center;
        align-items: center;
        padding: 5px;
    }

    input.title_input {
        width: 85%;
        height: 40px;
        text-align: center;
        border-style: none;
        border-color: none;
        border-width: 0px;
        background-color: #2b2b2b;
        margin: 10px;
        margin-top: 0px;
        margin-bottom: 0px;
        border-radius: 10px;
        font-size: 25px;
        color: white;
    }

    div.image_container {
        border-width: 5px;
        border-color: #2b2b2b;
        border-style: solid;
        border-radius: 10px;
        align-items: center;
        height: 70%;
    }

    div.add_img_button {
        width: 65px;
        height: 65px;
        padding: 5px;
        margin-top: 25%;
        margin-left: 48%;
        border-radius: 100%;
        background-color: #2b2b2b;
    }

    div.add_img_button:hover {
        z-index: 11;
        background-color: #53535365;
    }

    div.add_img_button:active {
        background-color: #2b2b2b;
    }

    img.added_img {
      width: 80%;
      bottom: 22%;
      left: 12%;
      position: absolute;
    }

    @keyframes button_hover {
        from{background-color: #1e8337;}
        to{background-color: #2ec75477;}
    }
    
    div.button {
        background-color: #1e8337;
        width: 20%;
        display: inline-flex;
        padding: 10px;
        text-align: center;
        margin-left: 20%;
        border-radius: 10px;
        align-items: center;
        margin-top: 30px;
    }
    div.button:hover {
        background-color: #2ec75477;
    }

    div.button:active {
        background-color: #1e8337;
    }

    text.button_text {
        font-size: 30px;
        color: white;
        align-self: center;
        margin-left: 23px;
    }

    div.cancel_button {

    }

</style>
