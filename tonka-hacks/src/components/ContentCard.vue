<script>

</script>

<template>
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
</template>

<style>
    div.content_box {
        display: inline-flex;
        background-color: #2b2b2b;
        flex-direction: column;
        flex-wrap: wrap;
        padding: 30px;
        border-radius: 15px;
    }
    header.user_header {
        margin: 10px;
        margin-top: 0px;
    }

    text.user_name {
        color: white;
        font-size: 25px;
        margin-right: 10px;
    }

    text.user_id { 
        color: grey;
        font-size: 15px;
    }

    header.title_header {
        margin: 10px;
        margin-top: 0px;
        margin-left: 5%;
    }

    text.title_text {
        color: white;
        font-size: 35px;
    }

    img.post_img {
        border-radius: 10px;
        width: 50%;
        margin-left: 5%;
        border-width: 30px;
        border-color: #222222;
        border-style: solid;
    }

    div.interaction_button_container {
        align-items: center;
        display: flex;
        flex-direction: row;
        width: 100%;
        align-self: center;
        margin-top: 3%;
    }

    @keyframes interaction_button_hover {
        from{background-color: #26a84677;}
        to{background-color: #2ec75477;}
    }

    div.interaction_button {
        height: 35px;
        width: 35px;
        border-radius: 5px;
        background-color: #26a84677;
        padding: 8px;
        padding-bottom: 5px;
        padding-right: 4px;
        margin-left: 7.5%;
        margin-top: 30px;
    }

    div.interaction_button:hover {
        background-color: #2ec75477;
        animation-name: interaction_button_hover;
        animation-duration: 100ms;
    }

    div.interaction_button:active {
        background-color: #26a84677;
    }

</style>
