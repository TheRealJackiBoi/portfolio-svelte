<script>
    
    import {Link} from "svelte-routing"

    export let img_url = ""
    export let img_alt = ""
    export let card_text = ""
    export let card_description = ""
    export let link_to = "/"

</script>
<div class="card">
    <a href={link_to}>
        <div class="card-img-container">
            <img src={img_url} alt={img_alt}>
        </div>

        <div class="card-text">
            <h3>{card_text}</h3>
            <p>{card_description}</p>
        </div>
    </a>
</div>


<style>
    .card {
        overflow: hidden;

        width: 12rem;
        height: 20rem;

        margin: 1em;

        
        border-radius: 8px;
        background: var(--main-background-color);
        box-shadow:  20px 20px 60px #c4c4c6;
        
        transition: transform 0.3s ease;
    }

    .card:hover {
        transform: translate(0, -1em);
    }
    
    .card h3 {
        columns: var(--black);
    }

    .card-img-container {
        width: 100%;
        height: 50%;
    }

    .card-img-container img {
        width: 100%;
        height: 100%;
    }

    .card-text {
        display: flex;
        flex-direction: column;
        
        width: 100%;
        height: 50%;

        text-align: center;
        align-items: center;
        justify-content: center;

        overflow-y: auto;
    }   

    .card-text h3 {        
        margin: 0;
        margin-top: 1em;
    }

    .card-text p {
        text-align: left;
        margin: 1em;
    }
    
</style>