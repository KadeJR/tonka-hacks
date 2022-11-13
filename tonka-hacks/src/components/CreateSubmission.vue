<script>
    function submissionHidden() {
        document.getElementById("CreateSubmission").style.visibility="hidden";
    }
</script>

<template>
    <div class="post_container">
        <header class="title_header">
            <input class="title_input" placeholder="Enter Title"/>
        </header>
        <div class="image_container">
            <div class="add_img_button">
                <svg xmlns="http://www.w3.org/2000/svg" width="65" height="65" fill="#2222222" class="bi bi-plus-circle-fill" viewBox="0 0 16 16">
                    <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3z"/>
                </svg>
            </div>
            <img class="added_img" src=""/>
        </div>
        <div class="button"><text class="button_text" @click="submissionHidden()">Cancel</text></div>
        <div class="button"><text class="button_text" style="margin-left: 40px;">Post</text></div>
    </div>
</template>

<style>

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