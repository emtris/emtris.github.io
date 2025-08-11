* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #0f172a;
    color: white;
    scroll-behavior: smooth;
}

/* Thanh điều hướng */
header {
    position: fixed;
    width: 100%;
    background: rgba(0, 0, 0, 0.6);
    padding: 15px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.logo {
    font-size: 24px;
    font-weight: 700;
}
.logo span {
    color: #38bdf8;
}

nav ul {
    display: flex;
    gap: 20px;
}
nav ul li {
    list-style: none;
}
nav ul li a {
    text-decoration: none;
    color: white;
    transition: color 0.3s;
}
nav ul li a:hover {
    color: #38bdf8;
}

/* Hero */
.hero {
    height: 100vh;
    background: linear-gradient(to right, #1e293b, #0f172a);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    animation: fadeIn 1.5s ease-in-out;
}
.hero h2 span {
    color: #38bdf8;
}
.hero .btn {
    margin-top: 20px;
    padding: 10px 20px;
    background: #38bdf8;
    color: black;
    text-decoration: none;
    border-radius: 8px;
    transition: 0.3s;
}
.hero .btn:hover {
    background: white;
}

/* About */
.about, .contact {
    padding: 80px 50px;
    background: #1e293b;
    animation: slideUp 1s ease-in-out;
}
.about h2, .contact h2 {
    margin-bottom: 20px;
    color: #38bdf8;
}

/* Form */
form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}
form input, form textarea {
    padding: 10px;
    border: none;
    border-radius: 5px;
}
form button {
    padding: 10px;
    background: #38bdf8;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}
form button:hover {
    background: white;
}

/* Footer */
footer {
    text-align: center;
    padding: 15px;
    background: #0f172a;
}

/* Animation */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
}
@keyframes slideUp {
    from { opacity: 0; transform: translateY(50px); }
    to { opacity: 1; transform: translateY(0); }
}
