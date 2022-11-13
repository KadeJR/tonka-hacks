<script>

</script>

<template>
    <b class="title">Trending</b>
    <ul class="trending_dir">
        <li class="trending_item">
            <text class="trending_item_title">Title</text>
        </li>
        <li class="trending_item">
            <text class="trending_item_title">Title</text>
        </li>
        <li class="trending_item">
            <text class="trending_item_title">Title</text>
        </li>
        <li class="trending_item">
            <text class="trending_item_title">Title</text>
        </li>
        <li class="trending_item" style="margin-bottom: 0px;">
            <text class="trending_item_title">Title</text>
        </li>
    </ul>
    <b class="title">Discover</b>
    <ul class="discover_dir">
        <li class="discover_item">
            <text class="discover_item_title">Topic</text>
        </li>
        <li class="discover_item">
            <text class="discover_item_title">Topic</text>
        </li>
        <li class="discover_item">
            <text class="discover_item_title">Topic</text>
        </li>
        <li class="discover_item">
            <text class="discover_item_title">Topic</text>
        </li>
        <li class="discover_item">
            <text class="discover_item_title">Topic</text>
        </li>
    </ul>
</template>

<style>
    b.title {
        color: #1e8337;
        font-size: 40px;
    }

    ul.trending_dir {
        padding: 0;
        list-style-type: none;
    }

    text.trending_item_title {
        font-size: 25px;
        color: #1e8337;
    }

    @keyframes trending_item_hover {
        from{background-color: #222222;}
        to{background-color: #2b2b2b;}
    }

    li.trending_item {
        color: #1e8337;
        margin-bottom: 8px;
        font-size: 25px;
        text-align: left;
        background-color: #222222;
        border-radius: 5px;
        padding: 5px;
        display: inline-flex;
        width: 95%;
    }

    li.trending_item:hover {
        background-color: #2b2b2b;
        animation-name: trending_item_hover;
        animation-duration: 100ms;
    }

    li.trending_item:active {
        background-color: #222222;
    }

    ul.discover_dir {
        padding: 0;
        list-style-type: none;
    }

    @keyframes discover_item_hover{
        from{background-color: #222222;}
        to{background-color: #2b2b2b;}
    }

    li.discover_item {
        width: 95%;
        display: inline-flex;
        background-color: #222222;
        padding: 5px;
        border-radius: 5px;
        text-align: center;
        margin-bottom: 8px;
    }

    li.discover_item:hover {
        background-color: #2b2b2b;
        animation-name: discover_item_hover;
        animation-duration: 100ms;
    }

    li.discover_item:active {
        background-color: #222222;
    }

    text.discover_item_title {
        font-size: 25px;
        color: #1e8337;
    }
</style>