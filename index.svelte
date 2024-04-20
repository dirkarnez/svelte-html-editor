<script>
	// Declare a variable to store the markdown data
  let htmlCode = `<h1>HTML< Editor</h1><script>alert("hi!")<\/script>`;
</script>

<textarea bind:value={htmlCode} placeholder="Enter html here"/>

<iframe srcdoc={htmlCode} title="testing"></iframe>

<style>
	iframe {
		width: 100%;
	}
</style>
