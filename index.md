---
title: Home
layout: home
---

<div class="translate"></div>
<div>
    <h2>Welcome to TWD:S Guides<h2>
    <p>These Tips and Guides are aimed at being easy on new players and for leaders to use it to help their people.</p>
    <br />
    <h3>New Players</h3>
    <p>If you are a New Player, please, read the tips in "New Players' Must Know" page</p>
</div>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        var language = navigator.language || navigator.userLanguage;
        var mainElement = document.querySelector('.main-content main .translate');
        mainElement.innerHTML = '<h3>Translate the website:</h3><a href="https://redkuni-github-io.translate.goog/Kunis-TWDS-Guides/?_x_tr_sl=en&_x_tr_tl=' + language + '">Google Translate to ' + language + '</a>';
    });
</script>