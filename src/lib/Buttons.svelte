<script>
    import { fade, scale } from 'svelte/transition';
    import * as Fluent from "fluent-svelte";

    let checked = false;
    let twitterFlyout = false;
    let twitchFlyout = false;
    let githubFlyout = false;

    const openYoutube = () => {
        window.open("https://www.youtube.com/channel/UCKNE5j5lN4jtWe_V7xBensQ");
    }

    const openGithub = () => {
        window.open("https://github.com/iezs");
    }
</script>

<Fluent.Button on:click={openYoutube}>
    youtube
</Fluent.Button>

<Fluent.Button on:click={openGithub}>
    github
</Fluent.Button>