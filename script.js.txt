function dragBall(event) {
    const ball = document.getElementById('stress-ball');
    ball.style.left = event.pageX + 'px';
}

function breathePanda() {
    const panda = document.getElementById('panda');
    panda.classList.toggle('breathe-in');
}

setInterval(breathePanda, 2000); // Panda breathes every 2 seconds
