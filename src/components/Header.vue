<script>
export default {
    data() {
        return {
            headerLinks: [
                {
                    text: "CHARACTER",
                    link: "#",
                    active: "false",
                },

                {
                    text: "COMICS",
                    link: "#",
                    active: "false",
                },

                {
                    text: "MOVIES",
                    link: "#",
                    active: "false",
                },

                {
                    text: "TV",
                    link: "#",
                    active: "false",
                },

                {
                    text: "GAMES",
                    link: "#",
                    active: "false",
                },

                {
                    text: "COLLECTIBLES",
                    link: "#",
                    active: "false",
                },

                {
                    text: "VIDEOS",
                    link: "#",
                    active: "false",
                },

                {
                    text: "FANS",
                    link: "#",
                    active: "false",
                },

                {
                    text: "NEWS",
                    link: "#",
                    active: "false",
                },

                {
                    text: "SHOP",
                    link: "#",
                    active: "false",
                },
            ]
        }
    }
}
</script>

<template>
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="logo">
            <ul>
                <li v-for="(link, index) in headerLinks" :key="index">
                    <a :href="link.link">{{ link.text }}</a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    background-color: #f5f5f5;
}
</style>