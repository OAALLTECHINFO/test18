
<script>
	import { TextBox,TextBlock,ToggleSwitch,ListItem,Button,AutoSuggestBox  } from "fluent-svelte";
</script>


<style>
    @import url("https://unpkg.com/fluent-svelte/theme.css");

    /* Some base styles to get things looking right. */
    :global(body) {
        background-color: var(--fds-solid-background-base);
        color: var(--fds-text-primary);
    }
	div.relative {
  position: relative;
  left:710px;
	Top:100px;
	width:500px;
}
		div.new {
  position: relative;
  left:1250px;
	Top:550px;
	width:500px;
}
			div.Text {
				position: relative;
				font-family: "Segoe UI";
				font-size:128px;
				font-weight: 600;
				Top:200px;
				left:600px;
				height: 5688px
}

</style>

<div class="relative">
<AutoSuggestBox placeholder="Search"/>
</div>
<div class="new">
	<Button variant="accent" >Subscribe</Button>
</div>
<div class="Text">
	    <p>The<br>OA</p>
</div>