---
title: Home Page
layout: home
nav_order: 1
permalink: /
---

<div>
    <h3>Translate the website:</h3>
    <div class="google-translate-link">
    <b>Google Translate may not translate it to the actual name of it in your language</b>
</div>

<div>
    <h2>Welcome to TWD:S Guides</h2>
    <p>These Tips and Guides are aimed at being easy on new players and for leaders to use it to help their people.</p>
    <p>Please, be aware that some name of the game's feature may change</p>
    <h2>New Players</h2>
    <p>If you are a New Player, please, read first the <a href="newplayers.md">New Players' Must Know" page</a></p>
</div>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        var language = navigator.language || navigator.userLanguage;
        var mainElement = document.querySelector('.google-translate-link');
        mainElement.innerHTML = '<a href="https://redkuni-github-io.translate.goog/Kunis-TWDS-Guides/?_x_tr_sl=en&_x_tr_tl=' + language + '">Google Translate to ' + language + '</a>';
    });
</script>