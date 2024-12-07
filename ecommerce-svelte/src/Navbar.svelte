<script  src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous">
    let src = "bl.png";
</script>


<nav class="navbar">
    <div class="logo-container">
        <a href="#"><img id="navbar-logo" {src}/></a>
    </div>
    
    <ul class="link-list">
        <li><a href="#">Home</a></li>
        <li><a href="#">Novità</a></li>
        <li><a href="#">Prodotti</a></li>
        <li><a href="#">Login</a></li>
        <li><a href="#">Carrello</a></li>

    </ul>
</nav>


<style>

 ul, li, a {
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
    box-sizing: border-box;
}

/* Navbar principale */
.navbar {
    display: flex;
    align-items: start;
    justify-content: space-between;
    padding: 10px 20px;
    background-color: #333;
    color: white;
}

/* Logo */
.logo-container {
    width: 100px;
    height: auto;
}

.logo-container img {
    width: 100%;
    height: auto;
}

/* Link principali */
.link-list {
    display: flex;
    /* gap: 15px; */
}

.link-list li {
    margin: 0;
    padding: 10px 15px;
    /* background-color: #444; */
    color: white;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.link-list li:hover {
    background-color: #555;
}

.link-list a {
    color: white;
    font-size: 16px;
}

/* Icone */
.navbar-icons a {
    color: white;
    font-size: 1.5em;
    margin-left: 20px;
    transition: color 0.3s ease;
}


/* Media Queries per Responsività */
@media (max-width: 768px) {
    .link-list {
        display: none; /* Nasconde i link su dispositivi piccoli */
    }

    .navbar-icons {
        margin-left: auto;
    }
}

</style>