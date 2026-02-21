# Mahendra Bondre

## About Me
Welcome to my GitHub profile! Here, you can explore my projects and skills. Feel free to reach out if you have any questions or just want to connect!

---

## Skills
- **Languages:** JavaScript, Python, Java
- **Frameworks:** React, Node.js, Django
- **Tools:** Git, Docker, Webpack

---

<style>
    body {
        font-family: 'Roboto', sans-serif;
        background-color: #121212;
        color: #ffffff;
        overflow: hidden;
    }
    h1 { font-size: 48px; color: #00ff00; text-align: center; animation: pulse 2s infinite; }
    h2 { font-size: 36px; color: #0000ff; text-align: center; border: 2px solid #ff0000; padding: 20px; box-shadow: 0 0 20px #ff0000; }
    .section { margin: 20px auto; padding: 20px; border-radius: 15px; animation: slidein 1s; }
    @keyframes pulse { 0% { transform: scale(1); } 50% { transform: scale(1.1); } 100% { transform: scale(1); } }
    @keyframes slidein { from { opacity: 0; transform: translateY(-20px); } to { opacity: 1; transform: translateY(0); } }
</style>

<div class='section'>
    <h1>Welcome to My Profile</h1>
</div>

<div class='section'>
    <h2>About Me</h2>
    <p>I'm a passionate developer who loves coding and creating innovative solutions.</p>
</div>

<div class='section'>
    <h2>Skills</h2>
    <ul>
        <li>JavaScript</li>
        <li>Python</li>
        <li>Java</li>
    </ul>
</div>

<script>
    // Add robotic voice reading for sections
    const sections = document.querySelectorAll('.section');
    sections.forEach(section => {
        section.addEventListener('mouseover', () => {
            const utterance = new SpeechSynthesisUtterance(section.querySelector('h2').innerText);
            window.speechSynthesis.speak(utterance);
        });
    });
</script>
