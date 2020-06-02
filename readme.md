1-Animation scroll :
Ancienne méthode non optimisée jQuery : ``
-CSS on ajoute la classe au balises "a".

-JS : 
    $(".presentation").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#presentation");
    });
    $(".damien").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#damien");
    });
    $(".coaching").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#coaching");
    });
    $(".grecs").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#grecs");
    });
    $(".atelierscales").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#atelierscales");
    });
    $(".regisseur").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#regisseur");
    });
    $(".damien").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#damien");
    });

    $(".competences").click(function(e) {
        e.preventDefault();
        $.scrollify.move("#competences");
    });
            
2-Détection si dans le view port : 
ajoute une classe quand viewport
    sources : http://www.sitepoint.com/scroll-based-animations-jquery-css3/
            https://gist.github.com/Metaviolet/eedf50d65b3fcb4961d4

3-Détection si élément présent dans le viewport : 
Alternative js :
enter-view.js : http://www.cssscript.com/demo/javascript-library-to-detects-if-elements-are-in-view/
