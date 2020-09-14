<script>
	import Navigation from './UI/Navigation.svelte'
	import Home from './UI/Home.svelte'
	import Project from './Projects/Project.svelte'


	// CMS API Data

	const spaceId = "9nyvyabx2uaf"
	const environmentId = "master-01"
	const accessToken = "HYpJA1_KcUZj9CHtU310evXhjdFpV9ogTxrMlLEPqtc"

	const url = `https://api.contentful.com/spaces/${spaceId}/environments/${environmentId}/entries?access_token=${accessToken}`

	console.log(url)


</script>

<Navigation />
<Project />