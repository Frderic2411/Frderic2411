style.css (CSS pour le design)



body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #2c3e50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header .logo h1 {
    margin: 0;
    font-size: 2.5em;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 40px 20px;
}

#voitures .car-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

#voitures .car-item {
    background-color: #fff;
    padding: 20px;
    margin: 10px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    width: 250px;
    text-align: center;
}

#voitures .car-item img {
    max-width: 100%;
    border-radius: 8px;
}

footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
