# for-my-bb
galentine
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>My BB 💖</title>
<style>
/* 🌸 Soft Pink Gradient Background */
body {
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg, #ffe6f0, #ffd1dc);
    overflow:hidden;
    text-align:center;
    color:#ff4d6d;
}

/* Container Styling */
.container {
    position:relative;
    z-index:2;
}

/* Heading & Text */
h1 {
    font-size:2.8rem;
    margin-bottom:0.5rem;
}
p {
    font-size:1.2rem;
    margin-bottom:20px;
}

/* Buttons Styling */
button {
    padding:15px 35px;
    font-size:1.2rem;
    margin:10px;
    border:none;
    border-radius:50px;
    cursor:pointer;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition:0.3s;
    font-weight:bold;
}

#yesBtn {
    background:white;
    color:#ff4d6d;
}

#noBtn {
    background:#ff4d6d;
    color:white;
    position:absolute;
}

/* Images */
img {
    width:180px;
    border-radius:20px;
    margin:10px;
    box-shadow:0 10px 20px rgba(0,0,0,0.2);
}

/* Celebration Text */
.celebrate {
    font-size:3rem;
    animation: pop 0.5s ease-in-out forwards;
}

/* Pop Animation */
@keyframes pop {
    0% { transform:scale(0); }
    100% { transform:scale(1); }
}

/* Floating Hearts Animation */
.heart {
    position: absolute;
    width: 20px;
    height: 20px;
    background: #ff4d6d;
    opacity: 0.8;
    transform: rotate(45deg);
    animation: float 5s linear infinite;
    z-index:1;
}

.heart:before,
.heart:after {
    content:"";
    position:absolute;
    width:20px;
    height:20px;
    background:#ff4d6d;
    border-radius:50%;
}

.heart:before { top:-10px; left:0; }
.heart:after { left:10px; top:0; }

@keyframes float {
    0% { transform: translateY(0) rotate(
