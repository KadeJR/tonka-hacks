<script setup>
    import ContentCard from "./ContentCard.vue";
</script>

<template>
    <div class="content_container">
        <ul class="content_dir">
            <li class="content_item"><ContentCard/></li>

        </ul>
    </div>
</template>

<style>
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

    

    
</style>