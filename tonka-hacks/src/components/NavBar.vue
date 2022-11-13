<script>

</script>

<template>
    <b class="nav_title">Sustain Media</b>
    <ul class="nav_dir">
        <li class="nav_item">
            <text class="nav_item_text">Home</text>
        </li>
        <div class="nav_line_spacer"></div>
        <li class="nav_item">
            <text class="nav_item_text">Trending</text>
        </li>
        <div class="nav_line_spacer"></div>
        <li class="nav_item">
            <text class="nav_item_text">Discover</text>
        </li>
        <div class="nav_spacer"></div>
        <li class="nav_item">
            <text class="nav_item_text">Account</text>
        </li>
        <div class="nav_line_spacer"></div>
        <li class="nav_item">
            <text class="nav_item_text">Settings</text>
        </li>
    </ul>
</template>

<style>
    b.nav_title {
        color: #1e8337;
        font-size: 40px;
        text-shadow: 5px;
    }

    ul.nav_dir {
        padding-left: 0px;
        list-style-type: none;
        align-items: center;
    }

    li.nav_item {
        padding-left: 0px;
    }

    text.nav_item_text {
        color: #1e8337;
        font-size: 30px;
        text-underline-position: below;
        text-underline-offset: 3px;
    }

    div.nav_spacer {
        margin-bottom: 124%;
    }

    div.nav_line_spacer {
        height: 2px;
        width: 100%;
        background-color: #1e8337;
        margin-top: 4px;
        margin-bottom: 4px;
    }

    div.account_item {
        align-items: center;
    }
</style>