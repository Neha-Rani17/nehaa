const openBtn = document.getElementById("openBtn");
const message = document.getElementById("message");

openBtn.addEventListener("click", function () {

    message.classList.toggle("show");

    if (message.classList.contains("show")) {
        openBtn.innerHTML = "Close Message 💗";
    } else {
        openBtn.innerHTML = "Open My Message 💌";
    }

});


/* Floating Hearts */

const heartsContainer = document.querySelector(".hearts");

const heartTypes = ["❤️", "💗", "💕", "💖", "💓"];

function createHeart() {

    const heart = document.createElement("div");

    heart.classList.add("heart");

    heart.innerHTML =
        heartTypes[Math.floor(Math.random() * heartTypes.length)];

    heart.style.left =
        Math.random() * 100 + "%";

    heart.style.fontSize =
        (Math.random() * 20 + 12) + "px";

    heart.style.animationDuration =
        (Math.random() * 5 + 5) + "s";

    heartsContainer.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 10000);
}


/* Create hearts continuously */

setInterval(createHeart, 500);