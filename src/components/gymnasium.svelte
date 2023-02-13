<script>
    import Card from "./card.svelte";
    import CardOutsideLink from "./card-outside-link.svelte";
    import HomeButton from "./home-button.svelte";
</script>
<HomeButton/>
<h1>Computer Science</h1>
<h2>Københavns Mediegymnasium</h2>

<div>
    <p></p>
</div>

<div class="card-container">
    <CardOutsideLink img_url="https://github.com/TheRealJackiBoi/fridge-app/blob/main/public/images/Fridge-sticker-final%20-%20small.png?raw=true" img_alt="Fridge Logo" card_text="Fridge Web App" card_description="A web application made with React and Firebase to have an overview of what you have in your fridge" link_to="https://github.com/TheRealJackiBoi/fridge-app    "/>

    <CardOutsideLink img_url="https://github.com/marcinsadowy/Prog-C-eksamensprojekt-Kalaha/blob/master/Eksamensprojekt_Kalaha/data/Kalaha%20board.png?raw=true" img_alt="Kalaha Board" card_text="Kalaha" card_description="Made the game Kalaha in the Java library Processing" link_to="https://github.com/marcinsadowy/Prog-C-eksamensprojekt-Kalaha"/>

    <CardOutsideLink img_url="https://github.com/TheRealJackiBoi/musik-festival-frontend/blob/main/public/images/LymeLight.png?raw=true" img_alt="Logo for LymeLight" card_text="Musik Festival Frontend" card_description="Our group made a netflix-party but for youtube, this is the frontend made in React" link_to="https://github.com/TheRealJackiBoi/musik-festival-frontend"/>

    <CardOutsideLink img_url="https://github.com/TheRealJackiBoi/musik-festival-frontend/blob/main/public/images/LymeLight.png?raw=true" img_alt="Logo for LymeLight" card_text="Musik Festival Backend" card_description="This is the backend part of the netflix-party for youtube. It's made in express with Firebase datastore" link_to="https://github.com/TheRealJackiBoi/musik-festival-backend"/>
</div>