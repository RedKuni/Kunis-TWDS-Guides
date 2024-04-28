---
title: Home
layout: home
---

<script>
    document.addEventListener('DOMContentLoaded', function() {
        var language = navigator.language || navigator.userLanguage;
        document.body.innerHTML += '<p>Your browser language is: ' + language + '</p>';
    });
</script>
