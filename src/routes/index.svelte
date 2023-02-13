<script>
    import {Router, Route} from 'svelte-routing'
    import AboutMe from '../components/about-me.svelte';
    import Datamatiker from '../components/datamatiker.svelte';
    import Gymnasium from '../components/gymnasium.svelte';
    import Home from '../components/home.svelte';

    export let url = "";
</script>


<Router {url}>
    <div>
        <Route path="/" component={Home}/>
        <Route path="/gymnasium" component={Gymnasium}/>
        <Route path="/about-me" component={AboutMe}/>
        <Route path="/datamatiker" component={Datamatiker}/>
    </div>
</Router>