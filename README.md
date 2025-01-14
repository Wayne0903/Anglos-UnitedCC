/* General reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
}

/* Header and Navigation */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.navbar h1 {
    font-size: 24px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
}

/* Hero Section */
#hero {
    text-align: center;
    background-color: #007bff;
    color: white;
    padding: 50px 20px;
}

#hero h2 {
    font-size: 32px;
    margin-bottom: 20px;
}

#hero p {
    font-size: 20px;
}

/* About Section */
#about {
    padding: 40px 20px;
    background-color: white;
    text-align: center;
}

#about h2 {
    font-size: 28px;
    margin-bottom: 20px;
}

#about p {
    font-size: 18px;
    max-width: 800px;
    margin: 0 auto;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
