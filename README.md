# shamthaj.github.io
/* Resets default browser margins */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
}

body {
    background-color: #f8f9fa;
    color: #333;
    line-height: 1.6;
}

/* Navigation Menu */
nav {
    display: flex;
    justify-content: space-between;
    padding: 1.5rem 5%;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-weight: 700;
    font-size: 1.2rem;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 2rem;
}

.nav-links a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #007bff;
}

/* Hero Section */
.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 6rem 5%;
    background-color: #fff;
    flex-wrap: wrap;
    gap: 2rem;
}

.hero-content {
    max-width: 600px;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: #111;
    line-height: 1.2;
}

.hero h2 {
    font-size: 1.5rem;
    font-weight: 400;
    color: #666;
    margin-bottom: 1.5rem;
}

.hero-image img {
    border-radius: 50%;
    width: 300px;
    height: 300px;
    object-fit: cover;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

/* Gallery Section */
.gallery-section {
    padding: 5rem 5%;
}

.gallery-section h2 {
    text-align: center;
    margin-bottom: 3rem;
    font-size: 2.2rem;
}

.gallery-grid {
    display: grid;
    /* Automatically creates a responsive grid that shrinks/grows */
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.gallery-item {
    background: #fff;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.1);
}

.gallery-item img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    display: block;
}

.gallery-item h3 {
    padding: 1.5rem;
    font-size: 1.2rem;
    text-align: center;
}

/* Footer Section */
footer {
    text-align: center;
    padding: 4rem 5%;
    background-color: #111;
    color: #fff;
}

footer h2 {
    margin-bottom: 1rem;
}

footer p {
    color: #aaa;
    margin-bottom: 2.5rem;
}

.button {
    display: inline-block;
    padding: 0.8rem 2rem;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    font-weight: bold;
    transition: background-color 0.3s;
}

.button:hover {
    background-color: #0056b3;
}
