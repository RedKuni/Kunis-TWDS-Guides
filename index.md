---
title: Home
layout: home
---

<script>
    document.addEventListener('DOMContentLoaded', function() {
        var language = navigator.language || navigator.userLanguage;
        var mainElement = document.querySelector('.main-content main');
        mainElement.innerHTML = '<p>Your browser language is: ' + language + '</p>';
    });
</script>