<template>
    <div>
        <h1>About Website</h1>
        <p>This is an app that displays the funny jokes..</p>

    </div>

</template>

<script>
export default {
    head() {
        return {
            title: 'About the Website',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'Best place for funny jokes'
                }
            ]
        }
    }
};
</script>

<style>

</style>