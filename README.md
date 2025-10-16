<!doctype html >
<html dir='true'>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="viewport" content="">
    <LINK REL="SHORTCUT ICON" HREF="https://irp.cdn-website.com/-resellers-preview/chris@carpediemcg.com/favicon/j5u94g4svl0rdtk0l8a2mopovf.png">
    <title>Site Editor | skilcraftllc</title>
    <script type="text/javascript">
    // function to load scripts async
    var scriptsToLoadWhenIdle = [];
    function registerScriptToLoadWhenIdle(scripts){
        scriptsToLoadWhenIdle.push(scripts);
    }
</script><!-- Inject secured cdn script -->
    <style>
        #innerElementsWrapper {
            display: none;
        }
    </style>

    <link rel="apple-touch-icon" href="https://du-cdn.multiscreensite.com/mobile-tablet-homescreen-icons/homescreen/wl/120_home-icon_wl.png">
<link rel="apple-touch-icon" sizes="152x152" href="https://du-cdn.multiscreensite.com/mobile-tablet-homescreen-icons/homescreen/wl/152_home-icon_wl.png">
<link rel="apple-touch-icon" sizes="180x180" href="https://du-cdn.multiscreensite.com/mobile-tablet-homescreen-icons/homescreen/wl/180_home-icon_wl.png">
<link rel="apple-touch-icon" sizes="167x167" href="https://du-cdn.multiscreensite.com/mobile-tablet-homescreen-icons/homescreen/wl/167_home-icon_wl.png">
<script>
        var dCurrentScreen = 'editor';
        var editorLoadStartTime = 1760630056137;
    </script>
    <script>
        if (!window.requestIdleCallback) {
            window.requestIdleCallback = function (fn) {
                setTimeout(fn, 0);
            }
        }
    </script>
    <!-- Fonts Include -->
    <!-- loadCSS function fonts.jsp-->
<script id="d-js-load-css">
/**
 * There are a few <link> tags with CSS resource in them that are preloaded in the page
 * in each of those there is a "onload" handler which invokes the loadCSS callback
 * defined here.
 * We are monitoring 3 main CSS files - the runtime, the global and the page.
 * When each load we check to see if we can append them all in a batch. If threre
 * is no page css (which may happen on inner pages) then we do not wait for it
 */
(function () {
  let cssLinks = {};
  function loadCssLink(link) {
    link.onload = null;
    link.rel = "stylesheet";
    link.type = "text/css";
  }
  
    function checkCss() {
      const pageCssLink = document.querySelector("[id*='CssLink']");
      const widgetCssLink = document.querySelector("[id*='widgetCSS']");

        if (cssLinks && cssLinks.runtime && cssLinks.global && (!pageCssLink || cssLinks.page) && (!widgetCssLink || cssLinks.widget)) {
            const storedRuntimeCssLink = cssLinks.runtime;
            const storedPageCssLink = cssLinks.page;
            const storedGlobalCssLink = cssLinks.global;
            const storedWidgetCssLink = cssLinks.widget;

            storedGlobalCssLink.disabled = true;
            loadCssLink(storedGlobalCssLink);

            if (storedPageCssLink) {
                storedPageCssLink.disabled = true;
                loadCssLink(storedPageCssLink);
            }

            if(storedWidgetCssLink) {
                storedWidgetCssLink.disabled = true;
                loadCssLink(storedWidgetCssLink);
            }

            storedRuntimeCssLink.disabled = true;
            loadCssLink(storedRuntimeCssLink);

            requestAnimationFrame(() => {
                setTimeout(() => {
                    storedRuntimeCssLink.disabled = false;
                    storedGlobalCssLink.disabled = false;
                    if (storedPageCssLink) {
                      storedPageCssLink.disabled = false;
                    }
                    if (storedWidgetCssLink) {
                      storedWidgetCssLink.disabled = false;
                    }
                    // (SUP-4179) Clear the accumulated cssLinks only when we're
                    // sure that the document has finished loading and the document 
                    // has been parsed.
                    if(document.readyState === 'interactive') {
                      cssLinks = null;
                    }
                }, 0);
            });
        }
    }
  

  function loadCSS(link) {
    try {
      var urlParams = new URLSearchParams(window.location.search);
      var noCSS = !!urlParams.get("nocss");
      var cssTimeout = urlParams.get("cssTimeout") || 0;

      if (noCSS) {
        return;
      }
      if (link.href && link.href.includes("d-css-runtime")) {
        cssLinks.runtime = link;
        checkCss();
      } else if (link.id === "siteGlobalCss") {
        cssLinks.global = link;
        checkCss();
      } 
      
      else if (link.id && link.id.includes("CssLink")) {
        cssLinks.page = link;
        checkCss();
      } else if (link.id && link.id.includes("widgetCSS")) {
        cssLinks.widget = link;
        checkCss();
      }
      
      else {
        requestIdleCallback(function () {
          window.setTimeout(function () {
            loadCssLink(link);
          }, parseInt(cssTimeout, 10));
        });
      }
    } catch (e) {
      throw e
    }
  }
  window.loadCSS = window.loadCSS || loadCSS;
})();
</script>
<link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400;1,700;1,900&family=Abril+Fatface:ital,wght@0,400&family=Alef:ital,wght@0,400;0,700&family=Alfa+Slab+One:ital,wght@0,400&family=Alike:ital,wght@0,400&family=Allura:ital,wght@0,400&family=Amaranth:ital,wght@0,400;0,700;1,400;1,700&family=Amatic+SC:ital,wght@0,400;0,700&family=Amiko:ital,wght@0,400;0,600;0,700&family=Antic+Didone:ital,wght@0,400&family=Anton:ital,wght@0,400&family=Arvo:ital,wght@0,400;0,700;1,400;1,700&family=Bad+Script:ital,wght@0,400&family=Belgrano:ital,wght@0,400&family=Bree+Serif:ital,wght@0,400&family=Butcherman:ital,wght@0,400&family=Cabin:ital,wght@0,400..700;1,400..700&family=Cairo:ital,wght@0,200..1000;1,200..1000&family=Cardo:ital,wght@0,400;0,700;1,400&family=Contrail+One:ital,wght@0,400&family=Cookie:ital,wght@0,400&family=Courgette:ital,wght@0,400&family=Creepster:ital,wght@0,400&family=Crete+Round:ital,wght@0,400;1,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Crimson+Text:ital,wght@0,400;0,600;0,700;1,400;1,600;1,700&family=Dancing+Script:ital,wght@0,400..700;1,400..700&family=Droid+Sans:ital,wght@0,400;0,700&family=Droid+Serif:ital,wght@0,400;0,700&family=Duru+Sans:ital,wght@0,400&family=Eater:ital,wght@0,400&family=EB+Garamond:ital,wght@0,400..800;1,400..800&family=Exo:ital,wght@0,100..900;1,100..900&family=Exo+2:ital,wght@0,100..900;1,100..900&family=Fjalla+One:ital,wght@0,400&family=Flamenco:ital,wght@0,300;0,400&family=Fugaz+One:ital,wght@0,400&family=Glegoo:ital,wght@0,400;0,700&family=Gloria+Hallelujah:ital,wght@0,400&family=Great+Vibes:ital,wght@0,400&family=Gudea:ital,wght@0,400;0,700;1,400&family=Inconsolata:ital,wght@0,200..900;1,200..900&family=Indie+Flower:ital,wght@0,400&family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Josefin+Slab:ital,wght@0,100..700;1,100..700&family=Jura:ital,wght@0,300..700;1,300..700&family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=Lobster:ital,wght@0,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Lobster+Two:ital,wght@0,400;0,700;1,400;1,700&family=Lora:ital,wght@0,400..700;1,400..700&family=Lusitana:ital,wght@0,400;0,700&family=Mate+SC:ital,wght@0,400&family=Maven+Pro:ital,wght@0,400..900;1,400..900&family=Mogra:ital,wght@0,400&family=Monoton:ital,wght@0,400&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Nosifer:ital,wght@0,400&family=Noto+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Old+Standard+TT:ital,wght@0,400;0,700;1,400&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Oswald:ital,wght@0,200..700;1,200..700&family=Oxygen:ital,wght@0,300;0,400;0,700&family=Pacifico:ital,wght@0,400&family=Patua+One:ital,wght@0,400&family=Paytone+One:ital,wght@0,400&family=Permanent+Marker:ital,wght@0,400&family=Play:ital,wght@0,400;0,700&family=Playball:ital,wght@0,400&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Poiret+One:ital,wght@0,400&family=Prociono:ital,wght@0,400&family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=PT+Serif:ital,wght@0,400;0,700;1,400;1,700&family=Puritan:ital,wght@0,400;0,700;1,400;1,700&family=Quattrocento:ital,wght@0,400;0,700&family=Racing+Sans+One:ital,wght@0,400&family=Raleway:ital,wght@0,100..900;1,100..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Roboto+Condensed:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&family=Roboto+Slab:ital,wght@0,100..900;1,100..900&family=Rokkitt:ital,wght@0,100..900;1,100..900&family=Sanchez:ital,wght@0,400;1,400&family=Shrikhand:ital,wght@0,400&family=Signika:ital,wght@0,300..700;1,300..700&family=Slabo+13px:ital,wght@0,400&family=Slabo+27px:ital,wght@0,400&family=Source+Sans+Pro:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700;1,900&family=Spinnaker:ital,wght@0,400&family=Stalemate:ital,wght@0,400&family=Teko:ital,wght@0,300;0,400;0,500;0,600;0,700&family=Titillium+Web:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&family=Ubuntu+Mono:ital,wght@0,400;0,700;1,400;1,700&family=UnifrakturMaguntia:ital,wght@0,400&family=Varela+Round:ital,wght@0,400&family=Vollkorn:ital,wght@0,400..900;1,400..900&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Yanone+Kaffeesatz:ital,wght@0,200..700;1,200..700&family=Yesteryear:ital,wght@0,400&family=Julius+Sans+One:ital,wght@0,400&family=Palanquin:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700&family=Asap:ital,wght@0,100..900;1,100..900&family=Istok+Web:ital,wght@0,400;0,700;1,400;1,700&family=Muli:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Quicksand:ital,wght@0,300..700;1,300..700&family=Work+Sans:ital,wght@0,100..900;1,100..900&family=Enriqueta:ital,wght@0,400;0,500;0,600;0,700&family=Special+Elite:ital,wght@0,400&family=Petit+Formal+Script:ital,wght@0,400&family=Parisienne:ital,wght@0,400&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Alegreya:ital,wght@0,400..900;1,400..900&family=Archivo+Narrow:ital,wght@0,400..700;1,400..700&family=Arimo:ital,wght@0,400..700;1,400..700&family=Bitter:ital,wght@0,100..900;1,100..900&family=Catamaran:ital,wght@0,100..900;1,100..900&family=Caudex:ital,wght@0,400;0,700;1,400;1,700&family=Codystar:ital,wght@0,300;0,400&family=Cuprum:ital,wght@0,400..700;1,400..700&family=Dynalight:ital,wght@0,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Emblema+One:ital,wght@0,400&family=Itim:ital,wght@0,400&family=Karla:ital,wght@0,200..800;1,200..800&family=Laila:ital,wght@0,300;0,400;0,500;0,600;0,700&family=Merienda:ital,wght@0,300..900;1,300..900&family=Noticia+Text:ital,wght@0,400;0,700;1,400;1,700&family=Noto+Serif:ital,wght@0,100..900;1,100..900&family=Overlock:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&family=Plaster:ital,wght@0,400&family=Quattrocento+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Satisfy:ital,wght@0,400&family=Titan+One:ital,wght@0,400&family=Questrial:ital,wght@0,400&family=Cinzel:ital,wght@0,400..900;1,400..900&family=Abel:ital,wght@0,400&family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Francois+One:ital,wght@0,400&family=Hind:ital,wght@0,300;0,400;0,500;0,600;0,700&family=Merriweather+Sans:ital,wght@0,300..800;1,300..800&family=Comfortaa:ital,wght@0,300..700;1,300..700&family=Ubuntu+Condensed:ital,wght@0,400&family=Acme:ital,wght@0,400&family=PT+Sans+Narrow:ital,wght@0,400;0,700&family=Passion+One:ital,wght@0,400;0,700;0,900&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Heebo:ital,wght@0,100..900;1,100..900&family=Fira+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Dosis:ital,wght@0,200..800;1,200..800&family=ABeeZee:ital,wght@0,400;1,400&family=Alegreya+Sans:ital,wght@0,100;0,300;0,400;0,500;0,700;0,800;0,900;1,100;1,300;1,400;1,500;1,700;1,800;1,900&family=Londrina+Sketch:ital,wght@0,400&family=Nobile:ital,wght@0,400;0,500;0,700;1,400;1,500;1,700&family=Mada:ital,wght@0,200..900;1,200..900&family=Oranienbaum:ital,wght@0,400&family=Fredoka:ital,wght@0,300..700;1,300..700&family=Prata:ital,wght@0,400&family=Vidaloka:ital,wght@0,400&family=Cabin+Sketch:ital,wght@0,400;0,700&family=Montserrat+Alternates:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Zilla+Slab:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Ovo:ital,wght@0,400&family=Unna:ital,wght@0,400;0,700;1,400;1,700&family=Sail:ital,wght@0,400&family=Chelsea+Market:ital,wght@0,400&family=Cutive+Mono:ital,wght@0,400&family=Wire+One:ital,wght@0,400&family=Rye:ital,wght@0,400&family=Elsie:ital,wght@0,400;0,900&family=Rozha+One:ital,wght@0,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Droid+Sans+Mono:ital,wght@0,400&family=Alice:ital,wght@0,400&family=Delius:ital,wght@0,400&family=Domine:ital,wght@0,400..700;1,400..700&family=Handlee:ital,wght@0,400&family=Kameron:ital,wght@0,400;0,700&family=Kreon:ital,wght@0,300..700;1,300..700&family=Marmelad:ital,wght@0,400&family=Molengo:ital,wght@0,400&family=Philosopher:ital,wght@0,400;0,700;1,400;1,700&family=Pinyon+Script:ital,wght@0,400&family=Poly:ital,wght@0,400;1,400&family=Reenie+Beanie:ital,wght@0,400&family=Rosario:ital,wght@0,300..700;1,300..700&family=Sofia:ital,wght@0,400&family=Tangerine:ital,wght@0,400;0,700&family=Volkhov:ital,wght@0,400;0,700;1,400;1,700&family=Sorts+Mill+Goudy:ital,wght@0,400;1,400&family=Assistant:ital,wght@0,200..800;1,200..800&family=Rubik:ital,wght@0,300..900;1,300..900&family=Varela:ital,wght@0,400&family=DM+Serif+Text:ital,wght@0,400;1,400&family=DM+Sans:ital,wght@0,100..1000;1,100..1000&family=Barlow:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Be+Vietnam:ital,wght@0,100;0,200;0,300;0,400;0,600;0,700;0,800;0,900&family=Biryani:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900&family=Darker+Grotesque:ital,wght@0,300..900;1,300..900&family=Lexend+Deca:ital,wght@0,100..900;1,100..900&family=Manjari:ital,wght@0,100;0,400;0,700&family=DM+Serif+Display:ital,wght@0,400;1,400&family=Stardos+Stencil:ital,wght@0,400;0,700&family=Staatliches:ital,wght@0,400&family=Yeseva+One:ital,wght@0,400&family=Libre+Caslon+Text:ital,wght@0,400;0,700;1,400&family=Overpass:ital,wght@0,100..900;1,100..900&family=Bebas+Neue:ital,wght@0,400&family=Sen:ital,wght@0,400..800;1,400..800&family=Inter:ital,wght@0,100..900;1,100..900&family=Lateef:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800&family=Amiri:ital,wght@0,400;0,700;1,400;1,700&family=El+Messiri:ital,wght@0,400..700;1,400..700&family=Harmattan:ital,wght@0,400;0,500;0,600;0,700&family=Tajawal:ital,wght@0,200;0,300;0,400;0,500;0,700;0,800;0,900&family=Almarai:ital,wght@0,300;0,400;0,700;0,800&family=Markazi+Text:ital,wght@0,400..700;1,400..700&family=Mirza:ital,wght@0,400;0,500;0,600;0,700&family=Katibeh:ital,wght@0,400&family=Cedarville+Cursive:ital,wght@0,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Give+You+Glory:ital,wght@0,400&family=Gothic+A1:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900&family=Jost:ital,wght@0,100..900;1,100..900&family=Homemade+Apple:ital,wght@0,400&family=Ramabhadra:ital,wght@0,400&family=Shadows+Into+Light:ital,wght@0,400&family=Space+Mono:ital,wght@0,400;0,700;1,400;1,700&family=Spartan:ital,wght@0,100;0,200;0,300;0,400;0,600;0,700;0,800;0,900&family=Sulphur+Point:ital,wght@0,300;0,400;0,700&family=Alata:ital,wght@0,400&family=Krona+One:ital,wght@0,400&family=Rock+Salt:ital,wght@0,400&family=Lacquer:ital,wght@0,400&family=Epilogue:ital,wght@0,100..900;1,100..900&family=Sacramento:ital,wght@0,400&family=Bevan:ital,wght@0,400;1,400&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Averia+Serif+Libre:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&family=Albert+Sans:ital,wght@0,100..900;1,100..900&family=Space+Grotesk:ital,wght@0,300..700;1,300..700&family=Outfit:ital,wght@0,100..900;1,100..900&family=Aboreto:ital,wght@0,400&family=Arapey:ital,wght@0,400;1,400&family=Marcellus:ital,wght@0,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="preload" href="https://irp.cdn-website.com/fonts/css2?family=Red+Hat+Display:ital,wght@0,300..900;1,300..900&family=Red+Hat+Text:ital,wght@0,300..700;1,300..700&family=Hedvig+Letters+Serif:ital,wght@0,400&amp;subset=latin-ext&amp;display=swap"  as="style" fetchpriority="low" onload="loadCSS(this)" /><link rel="stylesheet" type="text/css" href="https://static.cdn-website.com/mnlt/production/5860/_dm/s/rt/dist/css/css-font-package.min.css" />
</head>

<body data-product="ONE" style="opacity:1" data-role="editorBody"
      class="editorBody  D1EditorLoaded  wlSubUser siteFromScratch">
<!-- Prefetch fonts -->
<span class="prefetch-font regular"></span>
<span class="prefetch-font light"></span>
<span class="prefetch-font semi-bold"></span>
<span class="prefetch-font bold"></span>
<!-- Preview -->
<script>

    function initLoadingPromises() {
        if (!('DF' in window)) {
            window.DF = {
                locked: false,
                parallaxPromise: $.Deferred(),
                previewInjections: {
                    editorPromise: $.Deferred(),
                    previewPromise: $.Deferred()
                }
            };
        }
    }

</script>
<div class="DM_DIRECT dmShellinnerWrapper  siteFromScratch">
    <style>
         --font-size-h1: 48px;  --logo-url: url(https://irp.cdn-website.com/-resellers-preview/chris@carpediemcg.com/logo/npq43qj6qn05e0dsimm9o1mu52.png);  --backgroundImage: none;  --text-on-button: #ffffff;  --editorTopBarHover: rgb(2,158,229);  --font-size-h6: 16px;  --font-size-h4: 24px;  --font-size-h5: 20px;  --font-size-he-1: 16px;  --font-size-h2: 40px;  --font-size-plain-text: 16px;  --font-size-h3: 32px;  --font-size-body-text: 13px;  --font-size-body: 14px;  --font-size-he-4: 12px;  --font-size-italic: 14px;  --font-size-he-2: 14px;  --font-size-he-3: 13px;  --d-font: Label Sans;  --button-color: #03a9f4;  --font-size-bodySubtitle: 14px;  --header-color: #2c3e50;  --font-size-display-2: 24px;  --header-border-color: #1e2b38;  --font-size-display-1: 32px;  --font-size-tiny-text: 12px;  --backgroundColor: #f7f7f7;  --font-size-display-4: 10px;  --font-size-display-3: 20px;  --d-one-blue: #407ab0;  --font-size-footer: 12px;  --visible-button-hover-color: rgb(2,153,222);  --font-size-tiny: 13px;  --editor-header-color: #2c3e50;  --link-color: #8c8c8c;  --button-visible-font-color: #ffffff;  --text-on-dark: ;  --header-text-color: #ffffff;  --oneHeaderColor: #2c3e50;  --d-title-font: Label Sans;  --font-size-pageDescription: 16px;  --oneButtonColorHalfTransparent: rgba(3,169,244,0.5);  --oneDevicesFontIconColor: #2c3e50;  --editor-left-panel-width: 98px;  --d-one-orange: #f56033;  --button-hover-color: #F86F4C;  --text-on-light: #2094c9; 

        body {
            padding: 0;
            margin: 0;
        }

        .placeholder-container {
            display: flex;
            flex-direction: column;
            width: var(--editor-left-panel-width, 98px);
        }

        .icon-container:first-of-type {
            margin-top: 2px;
        }

        
            .icon-container {
                border-bottom: 1px solid #f2f2f2;
                height: 63px !important;
                width: 100% !important;
                display: flex !important;
                justify-content: center;
                align-items: center;
                flex-direction: column;
            }

            .line {
                height: 10px;
                width: 60px;
                margin-top: 10px;
                border-radius: 1px;
            }

            .circle {
                width: 25px;
                height: 25px;
                border-radius: 50%;
            }
        

        /* This is the important animation */
        .load-placeholder {
            overflow: hidden;
            position: relative;
            background-color: #e6eaec;
            animation: 2s blink infinite;
        }

        @keyframes loadsimulate {
            0% {
                background-position: -140% 0;
            }
            100% {
                background-position: 310% 0;
            }
        }

        @keyframes blink {
            0% {
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
            100% {
                opacity: 1;
            }
        }

        .load-placeholder::before {
            content: "";
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
        }

        .topbar-container {
            display: flex;
            flex-direction: row-reverse;
            height: 100%;
            align-items: center;
            background-color: #2f373a;
        }

        .topbar-container.new-branding {
            background-color: var(--header-color);
            box-shadow: 0 2px 4px rgb(64 65 71 / 30%);
        }

        .topbar-container .empty-button {
            margin: 0 15px;
            width: 74px;
            height: 15px;
            border-radius: 1px;
            background-color: #e6eaec;
            opacity: 0.8;
        }

        .topbar-container .publish-button {
            width: 122.2px;
            margin: 0 15px;
            color: var(--text-on-button);
            background-color: var(--button-color);
            border-radius: 12px;
            height: 26px;
            opacity: 0.8;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .topbar-container .button-placeholder {
            height: 50px;
            width: 50px;
            border-left: 1px solid black;
            display: flex;
            justify-content: center;
            align-items: center;
            box-sizing: border-box;
        }

        .topbar-container .button-placeholder.wide {
            width: 100.89px;
        }

        .topbar-container .button-placeholder.pages {
            width: 130px;
        }

        .topbar-container .empty-button.spaced {
            margin-inline-end: auto;
        }

        .topbar-container .button-placeholder.right-border {
            border-right: 1px solid black;
        }

        .topbar-container .button-placeholder .empty-placeholder.orange {
            background-color: var(--button-color);
        }

        .topbar-container .empty-button.orange {
            background-color: var(--button-color);
        }

        .topbar-container .button-placeholder .empty-placeholder {
            width: 25px;
            height: 25px;
            background-color: #e6eaec;
            border-radius: 50%;
            opacity: 0.8;
        }

        .topbar-container .left-side-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 522px;
            margin-inline-end: auto;
        }

    </style>

    <div id="Wrapper" leftpanelpinned="false" data-device="desktop"
         becomeprovisible='false'>
        <div id='edContainer' class='withPanels'>
            <div id='edTopBar'>
                <div class="topbar-container new-branding">
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder wide">
                        <div class="empty-button"></div>
                    </div>
                    <div class="publish-button"></div>
                    <div class="button-placeholder wide right-border">
                        <div class="empty-button"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="button-placeholder">
                        <div class="empty-placeholder"></div>
                    </div>
                    <div class="left-side-container">
                        <div class="empty-button orange spaced"></div>
                        <div class="button-placeholder pages">
                            <div class="empty-button"></div>
                        </div>
                        <div class="button-placeholder">
                            <div class="empty-placeholder orange"></div>
                        </div>
                        <div class="button-placeholder">
                            <div class="empty-placeholder"></div>
                        </div>
                        <div class="button-placeholder right-border">
                            <div class="empty-placeholder"></div>
                        </div>

                    </div>
                </div>
            </div>
            <div id="site-annotations"></div>
            <div id='edInnerContainer'>
                <div id='edLeftPanel'  >
                    <div class="placeholder-container">
                        <div class="icon-container">
                            <div class="circle load-placeholder"></div>
                            <div class="line load-placeholder"></div>
                        </div>
                        <div class="icon-container">
                            <div class="circle load-placeholder"></div>
                            <div class="line load-placeholder"></div>
                        </div>
                        <div class="icon-container">
                            <div class="circle load-placeholder"></div>
                            <div class="line load-placeholder"></div>
                        </div>
                        <div class="icon-container">
                            <div class="circle load-placeholder"></div>
                            <div class="line load-placeholder"></div>
                        </div>
                        <div class="icon-container">
                            <div class="circle load-placeholder"></div>
                            <div class="line load-placeholder"></div>
                        </div>
                        <div class="icon-container">
                            <div class="circle load-placeholder"></div>
                            <div class="line load-placeholder"></div>
                        </div>
                    </div>

                </div>
                <div id='edPreview' className='fullPreview'>
                    <div id="previewWrapper" hidden>
    <div id="PreviewPaneWrapper" class="PreviewPaneWrapperMobile"
         device="desktop" device-type="iphone">
        <div class="PreviewPaneInnerWrapper desktop" data-device="desktop"
             id="_preview_w">

            <div class="desktopCircle"></div>
            <div class="desktopCircle"></div>
            <div class="tabletOnlyCircle"></div>
            <div class="device-camera"></div>
            <div class="device-speaker"></div>

            <iframe 
                    class="NEEPreviewInside" src="" id="_preview" tabIndex='-1'></iframe>
            <script>
                async function setIframeSrc() {
                    async function waitUntil(condition) {
                        while (!condition()) {
                            await new Promise(resolve => setTimeout(resolve, 100));
                        }
                    }

                    await waitUntil(() => Boolean(window.$));
                    var source = "https://editor.carpediemcg.com/site/102ec7d9/skilcraft-solutions-cell?preview=true&nee=true&showOriginal=true&dm_checkSync=1&dm_try_mode=true&t=1760630056280&dm_device=desktop"
                    // TODO: Better way to replace blog prefix
                    if (source && source.indexOf('/blog/') !== -1) {
                        source = source.replace('/blog/', '/');
                    }
                    var iframe = document.getElementById('_preview');
                    if (-1 == navigator.userAgent.indexOf("MSIE")) {
                        iframe.src = source;
                    } else {
                        iframe.location = source;
                    }
                }

                setTimeout(setIframeSrc, 0);
            </script>

            <!-- <div class="mobileOnlyCircle"></div> -->
            <div class="home-button"></div>
            <div class="off-button"></div>
            <div class="silent-button"></div>
            <div class="up-button"></div>
            <div class="down-button"></div>
        </div>
        <div class="PreviewPaneInnerWrapper tablet" data-device="tablet">
            <div class="tabletCircle"></div>
            <iframe 
                    class="NEEPreviewInside" src="" id="_preview" tabIndex='-1'></iframe>
        </div>
        <div class="PreviewPaneInnerWrapper mobile" data-device="mobile">
            <iframe 
                    class="NEEPreviewInside" src="" id="_preview" tabIndex='-1'></iframe>
            <div class="home-button"></div>
            <div class="off-button"></div>
            <div class="silent-button"></div>
            <div class="up-button"></div>
            <div class="down-button"></div>
        </div>
    </div>

    <div style="clear: both"></div>

</div>

</div>
            </div>
        </div>

        <script type="text/javascript">
    const urlSearchParams = new URL(window.location).searchParams;
    const shouldShowLoader = urlSearchParams.has('pageStructure');
    const generateSiteQueryParam = urlSearchParams.get('generateSiteFirstVisit')

    if (shouldShowLoader) {
        const css = `
            #generate-site-loader {
                width: 100vw;
                height: 100vh;
                position: fixed;
                top: 0;
                left: 0;
                background-color: #F5F5F7;
                z-index: 999;

                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                gap: 24px;
            }

            .progress-container {
                width: 300px;
                height: 5px;
                background-color: #E4E4E6;
                border-radius: 12px;
                overflow: hidden;
                position: relative;
            }

            .progress-bar {
                height: 5px;
                border-radius: 12px;
                background-color: #8D5DF5;
                transition: width 0.4s ease;
            }

            .progress-bar-from-zero {
                width: 0%;
            }

            .progress-bar-first-open {
                width: 80%;
            }

            .progress-text {
                color: #272B35;
                font-size: 20px;
                font-weight: 550;
                line-height: 26px;
                letter-spacing: 0;
                font-family: "Label sans", Roboto;
                -webkit-font-smoothing: antialiased;
            }
        `;

        const style = document.createElement('style');
        style.id = 'generate-site-loader-style';
        style.textContent = css;
        document.head.appendChild(style);

        const generateSiteLoader = document.createElement('div');
        generateSiteLoader.id = 'generate-site-loader';

        const progressContainer = document.createElement('div');
        progressContainer.className = 'progress-container';

        const progressBar = document.createElement('div');
        progressBar.className = 'progress-bar';
        progressBar.classList.add(generateSiteQueryParam === 'true' ? 'progress-bar-first-open' : 'progress-bar-from-zero');

        const progressText = document.createElement('div');
        progressText.className = 'progress-text';
        progressText.id = 'progressText';
        progressText.textContent = 'Taking you to your generated site'

        progressContainer.appendChild(progressBar);
        generateSiteLoader.appendChild(progressText);
        generateSiteLoader.appendChild(progressContainer);

        const container = document.querySelector('#edContainer');
        container.prepend(generateSiteLoader);

        let progress = generateSiteQueryParam === 'true' ? 82 : 0;

        function updateProgress() {
            if (progress < 97) {
                progress += 3;
                progressBar.style.width = progress + '%';
            }
        }

        setInterval(updateProgress, 1000);
    }
</script>
<div id="oneDarkScreen"></div>

        <div id="inlineHTMLEditor" style="display:none">
	<div class="titleContainer dragCursor"> <span class="mode html active">HTML</span><span class="mode css">CSS</span><span class="widgetDragHandle"></span><div class="help Flex-main--1fk Flex-row--2lh" data-auto="flex" style="display: flex; align-items: center; justify-content: center;"><span class="Icon-main--3xm"  data-name="icon-help_popup" data-auto="icon" style="color: rgb(242, 242, 242);"><svg width="15" height="15" style="fill: rgb(242, 242, 242);"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#help_popup"></use></svg></span></div> <div class="widgetCloseBtn WidgetWrapper-close--AHR Flex-main--1fk Flex-row--2lh" data-auto="flex" style="display: flex; align-items: center; justify-content: center;"><span class="Icon-main--3xm htmlCloser" data-name="icon-close_popup" data-auto="icon" style="color: rgb(242, 242, 242);"><svg width="15" height="15" style="fill: rgb(242, 242, 242);"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#close_popup"></use></svg></span></div></div>
	<div class="mainWrapper">
		<div class="bodyContainer">
			<div class="cssDevices">
				<span id="allDevices" class="selected"> GENERAL CSS FOR ALL DEVICES</span>
				<span id="specificDevice">DEVICE SPECIFIC CSS</span>
			</div>

			<div class="warning">
				<span id="warningMark">
					<svg width="16" height="16"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-exclamation-sign"></use></svg>
				</span>
				<span id="boldMsg">	Use with caution!</span>
				<span>
						Make sure you read the <a id="dmMtHtmlHelp" href="javascript: void(0)">documentation.</a>
				</span>
				</div>
			<div class="warning text-editor">
				<span>
					For HTML compliance, the text HTML only supports&nbsp;
					<a id="dmMtTextEditorCustomCode">specific tags</a>.
				</span>
				<span>We recommend that you add styling to the CSS; unsupported tags will be removed.</span>
			</div>
			<div id="htmlArea" class="areaEditor">{{elementHTML}}</div>
			<div id="cssArea" class="areaEditor small">{{elementCSS}}</div><div id="deviceCssArea" class="areaEditor small">{{elementDeviceCSS}}</div>
		</div>
		<div class="footerContainer">
			<div id="buttonArea">
				<div class="devModeButton L" id="developerModeTopBarButton">Dev Mode</div>
				<div class="combinedBtns">
					<div class="revertButton displayNone">Undo</div>
					<div class="updateButton">Update</div>
				</div>
			</div>
		</div>
	</div>
</div>
<script type="text/javascript" src="https://static.cdn-website.com/libs/jquery/2.1.1/jquery.min.js"></script>
<script type="text/javascript" src="https://static.cdn-website.com/libs/jqueryui/1.11.4/jquery-ui.min.js"></script>
<script type="text/javascript">
function setLoaderSize(height, width, loader) {
	loader = loader || $("body");var cols = loader.find(".coloumns");
	if (cols != null) {cols.css("height", height + "px").css("width", width + "px");} 
	else {for (var i = 1; i < 13; i++) {loader.find("#" +'coloumn' + i).height(height);loader.find("#" +'coloumn' + i).width(width);}}
}

function setLoaderColor(colorString, loader) {
	loader = loader || $("body");var cols = loader.find(".coloumns");
	if (cols != null) {cols.css("background-color", colorString);}
	else {for (var i = 1; i < 13; i++) {loader.find("#" +'coloumn' + i).css("background", colorString);}}}

function showDefaultLoader(loader, wnd){
	var loaderHeight = loader.height() || 32;
	setLoaderSize(10, 3, loader);setLoaderColor("black", loader);loader.closest("body").css("height","100%");
	loader.css("position", "absolute").css("display", "block").css("z-index", "100000").css("left", ($(wnd).width()/ 2) + "px").css("top", (($(wnd).height() - loaderHeight) / 2) + "px");
	loader.closest("body").css("height","");loader.find("#imageZone").show();}
</script>

<div id="disabledImageZone" style="display:none;z-index:-1">
    	<style type='text/css'>
	#imageZone{position:absolute;margin:auto;}
	.coloumns{border-radius:3px;background-color:rgb(249,152,13);/*border:1px solid #999;*/ height:18px;width:6px;-webkit-animation-name:loader;-webkit-animation-duration:1s;-webkit-animation-iteration-count:infinite;-webkit-animation-direction:linear;-moz-animation-name:loader;-moz-animation-duration:1s;-moz-animation-iteration-count:infinite;-moz-animation-direction:linear;opacity:.25;-webkit-transform:scale(0.7);-webkit-transform-origin:50% 180%;-moz-transform:scale(0.7);-moz-transform-origin:50% 180%;position:absolute;}
	#coloumn1{-webkit-transform:rotate(0deg);-webkit-animation-delay:-.914s;-moz-transform:rotate(0deg);-moz-animation-delay:-.914s;}
	#coloumn2{-webkit-transform:rotate(30deg);-webkit-animation-delay:-.831s;-moz-transform:rotate(30deg);-moz-animation-delay:-.831s;}
	#coloumn3{-webkit-transform:rotate(60deg);-webkit-animation-delay:-.747s;-moz-transform:rotate(60deg);-moz-animation-delay:-.747s;}
	#coloumn4{-webkit-transform:rotate(90deg);-webkit-animation-delay:-.664s;-moz-transform:rotate(90deg);-moz-animation-delay:-.664s;}
	#coloumn5{-webkit-transform:rotate(120deg);-webkit-animation-delay:-.581s;-moz-transform:rotate(120deg);-moz-animation-delay:-.581s;}
	#coloumn6{-webkit-transform:rotate(150deg);-webkit-animation-delay:-.498s;-moz-transform:rotate(150deg);-moz-animation-delay:-.498s;}
	#coloumn7{-webkit-transform:rotate(180deg);-webkit-animation-delay:-.415s;-moz-transform:rotate(180deg);-moz-animation-delay:-.415s;}
	#coloumn8{-webkit-transform:rotate(210deg);-webkit-animation-delay:-.332s;-moz-transform:rotate(210deg);-moz-animation-delay:-.332s;}
	#coloumn9{-webkit-transform:rotate(240deg);-webkit-animation-delay:-.249s;-moz-transform:rotate(240deg);-moz-animation-delay:-.249s;}
	#coloumn10{-webkit-transform:rotate(270deg);-webkit-animation-delay:-.166s;-moz-transform:rotate(270deg);-moz-animation-delay:-.166s;}
	#coloumn11{-webkit-transform:rotate(300deg);-webkit-animation-delay:-.083s;-moz-transform:rotate(300deg);-moz-animation-delay:-.083s;}
	#coloumn12{-webkit-transform:rotate(330deg);-moz-transform:rotate(330deg);}
	@-webkit-keyframes loader {0%{opacity:1;}100%{opacity:.25;}}
	@-moz-keyframes loader {0%{opacity:1;}100%{opacity:.25;}}
</style>
<div id='imageZone'>
<div id='coloumn1' class='coloumns'></div><div id='coloumn2' class='coloumns'></div><div id='coloumn3' class='coloumns'></div><div id='coloumn4' class='coloumns'></div><div id='coloumn5' class='coloumns'></div><div id='coloumn6' class='coloumns'></div><div id='coloumn7' class='coloumns'></div><div id='coloumn8' class='coloumns'></div><div id='coloumn9' class='coloumns'></div><div id='coloumn10' class='coloumns'></div><div id='coloumn11' class='coloumns'></div><div id='coloumn12' class='coloumns'></div>
</div>
</div>
<!--     SVG includes -->
        <svg display="none" width="0" height="0" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<defs>
<symbol id="icon-theme" viewBox="0 0 1024 1024">
	<title>theme</title>
	<path class="path1" d="M710.592 423.040h-39.52c-10.496-30.72-27.2-63.744-50.368-98.816s-44.448-54.048-64.032-56.704c-10.848-1.472-24.064-2.592-39.936-3.648s-29.536-1.536-40.96-1.536h-23.68v564.256c0 12.224 2.112 22.912 6.528 32.192s12.928 16.608 25.824 22.144c7.872 2.944 19.808 6.144 36.416 9.312 16.288 3.264 30.24 5.408 41.76 6.784v39.616h-401.088v-39.616c9.824-1.024 23.584-2.336 41.28-4.384 17.728-1.728 29.76-4.032 36.256-6.784 13.184-5.344 22.080-12.608 26.432-21.792 4.384-9.024 6.528-19.872 6.528-32.448l0.032-569.376h-23.808c-11.456 0-25.152 0.512-40.96 1.536s-29.248 2.208-39.808 3.648c-19.648 2.656-40.864 21.6-64.064 56.736-23.232 35.2-39.936 68.16-50.368 98.912h-39.616l0.064-205.728h697.088v205.696zM873.728 763.84l136.448-628.224h-0.128c1.472-20.032-17.984-46.848-38.208-50.784l-7.232-1.472c-20.416-3.84-48.384 13.76-54.4 32.96h-0.256l-103.424 634.336 67.2 13.184zM946.24 776.576v-51.136h-202.816v51.136h-64.16v160.128h330.88v-160.128h-63.904zM758.112 915.36h-66.784v-118.976h66.784v118.976zM702.688 647.808v59.904h284.256l-0.064-59.904h-284.192zM762.048 694.048h-47.872l0.064-34.88h47.872l-0.064 34.88z"></path>
</symbol>
<symbol id="icon-plus-sign" viewBox="0 0 1024 1024">
	<title>plus-sign</title>
	<path class="path1" d="M694.848 548.576v-73.152q0-14.848-10.848-25.728t-25.728-10.848h-146.272v-146.272q0-14.848-10.848-25.728t-25.728-10.848h-73.152q-14.848 0-25.728 10.848t-10.848 25.728v146.272h-146.272q-14.848 0-25.728 10.848t-10.848 25.728v73.152q0 14.848 10.848 25.728t25.728 10.848h146.272v146.272q0 14.848 10.848 25.728t25.728 10.848h73.152q14.848 0 25.728-10.848t10.848-25.728v-146.272h146.272q14.848 0 25.728-10.848t10.848-25.728zM877.728 512q0 119.424-58.848 220.288t-159.712 159.712-220.288 58.848-220.288-58.848-159.712-159.712-58.848-220.288 58.848-220.288 159.712-159.712 220.288-58.848 220.288 58.848 159.712 159.712 58.848 220.288z"></path>
</symbol>
<symbol id="icon-page" viewBox="0 0 1024 1024">
	<title>page</title>
	<path class="path1" d="M885.12 0h-746.048c-13.984 0-25.792 11.552-25.792 25.728v972.544c0 14.016 11.776 25.664 25.728 25.664h746.144c14.016 0 25.568-11.552 25.568-25.664l0.064-972.544c-0.128-14.176-11.68-25.728-25.664-25.728zM781.888 927.104h-540.064c-14.24 0-25.728-11.552-25.728-25.728v-804.896c0-14.112 11.36-25.728 25.728-25.728h257.312c-0.416 1.632-1.024 2.944-1.024 4.608l0.064 313.28c0 24.032 19.584 43.552 43.552 43.552h265.952v469.024c0 14.4-11.648 25.888-25.792 25.888z"></path>
</symbol>
<symbol id="icon-briefcase" viewBox="0 0 1024 1024">
	<title>briefcase</title>
	<path class="path1" d="M365.728 146.272h292.576v-73.152h-292.576v73.152zM1024 512v274.272q0 37.728-26.848 64.576t-64.576 26.848h-841.152q-37.728 0-64.576-26.848t-26.848-64.576v-274.272h384v91.424q0 14.848 10.848 25.728t25.728 10.848h182.848q14.848 0 25.728-10.848t10.848-25.728v-91.424h384zM585.152 512v73.152h-146.272v-73.152h146.272zM1024 237.728v219.424h-1024v-219.424q0-37.728 26.848-64.576t64.576-26.848h201.152v-91.424q0-22.848 16-38.848t38.848-16h329.152q22.848 0 38.848 16t16 38.848v91.424h201.152q37.728 0 64.576 26.848t26.848 64.576z"></path>
</symbol>
<symbol id="icon-smart-site" viewBox="0 0 1024 1024">
	<title>smart-site</title>
	<path class="path1" d="M710.007 754.688l-12.322-18.842-23.927-36.659-59.358-90.419v-0.068l-1.673-2.526c-3.584-4.642-9.216-7.646-15.531-7.646-0.614 0-1.195 0-1.809 0.068-1.195 0.273-2.389 0.478-3.584 0.717-74.479 13.38-84.992-21.163-159.334-7.851-0.068 0-0.137 0-0.205 0.034-0.99 0.171-1.946 0.341-2.935 0.546-6.656 1.638-12.39 5.666-16.077 11.196l-0.068-0.034-99.465 151.791c-2.116 3.14-3.345 6.963-3.345 11.059 0 10.889 8.875 19.763 19.729 19.763h363.657c10.923 0 19.797-8.875 19.797-19.763 0-3.686-0.99-7.168-2.799-10.138-0.239-0.444-0.41-0.853-0.751-1.229zM798.583 729.839c-0.478-0.649-0.853-1.263-1.263-1.877l-146.193-223.13c-0.068-0.137-0.137-0.239-0.205-0.341-1.331-1.98-2.662-3.959-3.857-5.973-20.651-32.802-32.597-71.612-32.597-113.186v-120.081c0-9.148 0.853-18.057 2.526-26.726 2.935-15.735 8.533-30.515 16.213-43.93 0.99-1.707 2.014-3.413 3.004-5.018 2.321-3.857 3.721-8.363 3.721-13.21 0-14.029-11.401-25.395-25.463-25.395h-204.937c-13.995 0-25.395 11.366-25.395 25.395 0 4.779 1.263 9.216 3.55 13.005 0.137 0.205 0.273 0.375 0.341 0.58 0.99 1.536 1.946 3.072 2.799 4.676 7.68 13.449 13.278 28.194 16.282 43.93 1.604 8.67 2.458 17.613 2.458 26.726v120.115c0 41.574-11.878 80.316-32.529 113.084-1.399 2.355-2.935 4.71-4.54 6.997l-145.715 222.413c0 0.034-0.068 0.068-0.068 0.137-10.069 14.848-15.94 32.734-15.94 51.985 0 51.439 41.745 93.116 93.184 93.116h416.119c51.473 0 93.184-41.677 93.184-93.116 0-18.5-5.393-35.703-14.677-50.176zM720.077 829.44h-416.154c-27.409 0-49.527-22.118-49.527-49.459 0-8.465 2.185-16.486 6.007-23.484 0-0.034 0-0.068 0-0.068 1.263-2.355 2.799-4.574 4.403-6.656l130.867-199.782c0.341-0.717 0.717-1.399 1.126-2.048 0.068-0.068 0.068-0.102 0.068-0.102l11.878-18.091 5.052-7.748c14.131-22.289 24.815-46.899 31.539-73.182 5.12-20.309 7.919-41.574 7.919-63.488v-165.41c0-14.029 11.401-25.361 25.395-25.361h66.662c14.063 0 25.463 11.332 25.463 25.361v165.41c0 21.948 2.731 43.213 7.919 63.488 6.656 26.283 17.408 50.859 31.471 73.182l5.052 7.748 10.547 16.043c0.717 0.922 1.331 1.946 1.946 2.97 0.205 0.444 0.478 0.853 0.614 1.297l130.799 199.714c1.673 2.116 3.209 4.301 4.471 6.656 0 0 0 0.034 0 0.068 3.789 6.997 5.939 15.019 5.939 23.484 0 27.307-22.153 49.459-49.459 49.459z"></path>
</symbol>
<symbol id="icon-shopping-cart" viewBox="0 0 1024 1024">
	<title>shopping-cart</title>
	<path class="path1" d="M365.728 877.728q0 30.272-21.44 51.712t-51.712 21.44-51.712-21.44-21.44-51.712 21.44-51.712 51.712-21.44 51.712 21.44 21.44 51.712zM877.728 877.728q0 30.272-21.44 51.712t-51.712 21.44-51.712-21.44-21.44-51.712 21.44-51.712 51.712-21.44 51.712 21.44 21.44 51.712zM950.848 256v292.576q0 13.728-9.152 24.288t-23.424 12.288l-596.576 69.728q0.576 4 2.56 12.288t3.424 15.136 1.44 12.576q0 9.152-13.728 36.576h525.728q14.848 0 25.728 10.848t10.848 25.728-10.848 25.728-25.728 10.848h-585.152q-14.848 0-25.728-10.848t-10.848-25.728q0-8 6.272-22.56t16.864-34.016 11.712-21.728l-101.152-470.272h-116.576q-14.848 0-25.728-10.848t-10.848-25.728 10.848-25.728 25.728-10.848h146.272q9.152 0 16.288 3.712t11.424 8.864 7.424 14.016 4.288 15.136 3.136 16.864 2.56 14.56h686.272q14.848 0 25.728 10.848t10.848 25.728z"></path>
</symbol>
<symbol id="icon-settings" viewBox="0 0 1024 1024">
	<title>settings</title>
	<path class="path1" d="M66.56 569.568c0-40.256 0-80 0-120.128 20.64-7.392 41.216-14.624 61.76-22.112 54.848-19.776 78.848-75.168 55.232-128.448-7.904-18.176-16.704-35.872-25.344-53.696-3.040-5.888-3.136-9.728 2.048-14.784 24.512-24 48.704-48.128 72.64-72.64 4.672-4.672 8.16-5.216 13.888-2.336 18.4 9.152 36.736 18.24 55.552 26.304 52.544 23.104 108.032-1.408 127.232-55.872 6.464-18.4 12.928-36.64 19.776-54.656 1.152-2.88 4.928-6.72 7.552-6.72 38.208-0.544 76.416-0.256 114.816-0.256 7.648 20.896 14.912 41.568 22.272 62.112 19.584 54.208 74.944 78.4 127.872 55.36 18.752-8.256 37.088-17.408 55.488-26.432 5.312-2.528 8.608-2.144 13.024 2.144 24.256 24.768 48.768 49.344 73.44 73.44 4.928 4.928 4.672 8.448 1.984 13.824-9.056 18.4-18.24 36.736-26.304 55.488-22.848 52 1.632 107.584 55.424 126.976 20.576 7.488 41.152 14.624 62.464 22.272 0 19.84 0 39.616 0 59.456s0 39.552 0 60.352c-20.576 7.488-41.024 14.816-61.6 22.080-55.552 20.128-79.296 74.88-55.424 129.12 7.712 17.792 16.16 35.296 24.768 52.608 3.136 6.272 3.328 10.24-2.24 15.616-24.32 23.744-48.128 47.68-71.808 71.936-5.024 5.024-8.704 5.568-14.816 2.528-18.208-8.96-36.512-17.888-55.296-26.144-50.56-22.176-105.792 0.896-125.632 52.704-8.256 21.376-15.488 43.104-23.424 65.28-38.528 0-76.672 0.192-114.816-0.256-2.528 0-6.272-3.936-7.488-6.72-6.912-18.144-13.184-36.352-19.776-54.656-19.52-54.848-74.784-79.040-128.416-55.488-18.368 7.84-36.32 16.96-54.368 25.632-5.856 2.88-9.344 2.432-13.92-2.24-24-24.512-48.128-48.768-72.704-72.64-5.152-5.024-5.024-8.8-2.112-14.816 8.992-17.92 17.792-36 25.856-54.528 23.104-52.8-1.216-108.032-55.68-127.552-20.704-7.392-41.184-14.848-61.92-22.112zM348.864 516.416c2.080 87.808 80.704 166.4 181.632 155.264 82.88-9.056 153.728-83.776 143.392-180.928-8.864-82.816-83.68-152.864-181.088-143.616-81.664 7.68-150.976 88.192-143.936 169.28z"></path>
</symbol>
<symbol id="icon-grumpy_menu" viewBox="0 0 1024 1024">
	<title>grumpy_menu</title>
	<path class="path1" d="M107.281 198.656v129.297h809.472v-129.297h-809.472zM107.281 576.683h809.472v-129.331h-809.472v129.331zM107.281 825.344h809.472v-129.297h-809.472v129.297z"></path>
</symbol>
<symbol id="icon-phone2" viewBox="0 0 1024 1024">
	<title>phone2</title>
	<path class="path1" d="M316.448 176c-11.872 0-21.76 9.888-21.76 21.76v741.312c0 12.064 9.792 21.856 21.76 21.856h391.008c11.872 0 21.76-9.888 21.76-21.856v-741.312c0-11.872-9.792-21.76-21.76-21.76h-391.008zM656.768 746.144c0 11.968-9.696 21.76-21.664 21.76h-246.176c-11.872 0-21.664-9.888-21.664-21.76v-485.152c0-11.872 9.792-21.76 21.664-21.76h246.272c11.872 0 21.76 9.792 21.76 21.76l-0.192 485.152z"></path>
</symbol>
<symbol id="icon-pc" viewBox="0 0 1024 1024">
	<title>pc</title>
	<path class="path1" d="M988.928 726.528c12.384 0 22.464-9.888 22.464-22.208v-553.952c0-12.32-10.080-22.368-22.464-22.368h-953.952c-12.384 0-22.368 10.080-22.368 22.368v554.048c0 12.32 9.984 22.208 22.368 22.208h302.144c12.32 0 22.464 10.24 22.464 22.56v55.936c0 12.32-10.144 22.368-22.464 22.368l-190.272-0.032c-12.224 0-22.304 10.080-22.304 22.368v64.384c0 12.32 10.080 22.368 22.304 22.368h730.208c12.384 0 22.368-10.080 22.368-22.368v-64.448c0-12.32-9.984-22.368-22.368-22.368h-198.528c-12.48 0-22.464-10.080-22.464-22.368v-55.936c0-12.32 9.984-22.56 22.464-22.56h310.4zM129.984 637.44c-12.32 0-22.368-9.888-22.368-22.208v-392.064c0-12.48 10.080-22.368 22.368-22.368h760.928c12.384 0 22.464 9.888 22.464 22.368v392c0 12.32-10.080 22.368-22.464 22.368l-760.928-0.096z"></path>
</symbol>
<symbol id="icon-tablet" viewBox="0 0 1024 1024">
	<title>tablet</title>
	<path class="path1" d="M208 125.248c-11.552 0-21.056 9.504-21.056 21.056l0.032 792.48c0 11.552 9.504 21.152 21.056 21.152h607.968c11.552 0 21.056-9.6 21.056-21.152l-0.032-792.576c0-11.456-9.504-20.96-21.056-20.96h-607.968zM752.832 859.776c0 11.456-9.504 21.056-21.056 21.056h-439.936c-11.456 0-20.96-9.504-20.96-21.056v-655.872c0-11.552 9.504-21.152 20.96-21.152h440.16c11.552 0 21.056 9.504 21.056 21.152l-0.224 655.872zM559.168 752.704c0 11.552-9.504 21.056-21.056 21.056l-52.32-0.032c-11.552 0-20.96-9.504-20.96-21.056v-52.224c0-11.552 9.408-21.056 20.96-21.056h52.352c11.552 0 21.056 9.408 21.056 21.056l-0.032 52.256z"></path>
</symbol>
<symbol id="icon-question-sign" viewBox="0 0 1024 1024">
	<title>question-sign</title>
	<path class="path1" d="M512 786.272v-109.728q0-8-5.152-13.152t-13.152-5.152h-109.728q-8 0-13.152 5.152t-5.152 13.152v109.728q0 8 5.152 13.152t13.152 5.152h109.728q8 0 13.152-5.152t5.152-13.152zM658.272 402.272q0-50.272-31.712-93.152t-79.136-66.272-97.152-23.424q-138.848 0-212 121.728-8.576 13.728 4.576 24l75.424 57.152q4 3.424 10.848 3.424 9.152 0 14.272-6.848 30.272-38.848 49.152-52.576 19.424-13.728 49.152-13.728 27.424 0 48.864 14.848t21.44 33.728q0 21.728-11.424 34.848t-38.848 25.728q-36 16-66.016 49.44t-30.016 71.712v20.576q0 8 5.152 13.152t13.152 5.152h109.728q8 0 13.152-5.152t5.152-13.152q0-10.848 12.288-28.288t31.136-28.288q18.272-10.272 28-16.288t26.272-20 25.44-27.424 16-34.56 7.136-46.272zM877.728 512q0 119.424-58.848 220.288t-159.712 159.712-220.288 58.848-220.288-58.848-159.712-159.712-58.848-220.288 58.848-220.288 159.712-159.712 220.288-58.848 220.288 58.848 159.712 159.712 58.848 220.288z"></path>
</symbol>
<symbol id="icon-w_html" viewBox="0 0 1024 1024">
	<title>w_html</title>
	<path class="path1" d="M547.806 347.75c1.331-3.55 5.461-6.417 9.25-6.417h43.52c3.755 0 5.734 2.867 4.403 6.383l-124.894 328.602c-1.365 3.482-5.53 6.349-9.284 6.349h-43.213c-3.755 0-5.734-2.867-4.403-6.417l124.621-328.499zM808.926 528.794c0 3.755-2.697 8.329-5.939 10.172l-156.706 88.064c-3.277 1.843-5.939 0.273-5.939-3.516v-45.090c0-3.755 2.697-8.329 5.939-10.172l86.289-48.606c3.277-1.877 3.277-4.881 0-6.69l-86.255-48.162c-3.277-1.843-5.973-6.417-5.973-10.172v-45.227c0-3.755 2.697-5.325 5.939-3.516l156.706 88.064c3.277 1.843 5.939 6.417 5.939 10.172v24.678zM215.074 504.149c0-3.755 2.697-8.329 5.939-10.172l156.706-88.064c3.277-1.843 5.939-0.273 5.939 3.516v45.227c0 3.755-2.697 8.329-5.973 10.172l-86.255 48.162c-3.277 1.843-3.277 4.847 0 6.69l86.289 48.606c3.277 1.843 5.939 6.417 5.939 10.172v45.090c0 3.755-2.697 5.325-5.939 3.516l-156.706-88.064c-3.277-1.843-5.939-6.417-5.939-10.172v-24.678z"></path>
</symbol>
<symbol id="icon-star" viewBox="0 0 1024 1024">
	<title>star</title>
	<path class="path1" d="M950.848 369.728q0 12.576-14.848 27.424l-207.424 202.272 49.152 285.728q0.576 4 0.576 11.424 0 12-6.016 20.288t-17.44 8.288q-10.848 0-22.848-6.848l-256.576-134.848-256.576 134.848q-12.576 6.848-22.848 6.848-12 0-18.016-8.288t-6.016-20.288q0-3.424 1.152-11.424l49.152-285.728-208-202.272q-14.272-15.424-14.272-27.424 0-21.152 32-26.272l286.848-41.728 128.576-260q10.848-23.424 28-23.424t28 23.424l128.576 260 286.848 41.728q32 5.152 32 26.272z"></path>
</symbol>
</defs>
</svg><!--     End SVG includes -->

        <!--Upgrade tooltips -->
        <script type="text/x-handlebars" id="upgrade-tooltip-tmpl">
	<div class="plansTip">
			<div class="plansTipHeader"><div class="lockText">{{dm-translate title}}</div></div>
			<div class="plansTipBody">
				{{#each upgrades}}
					<div class="upgradeRow">
						<span class="upgradeRowText">
							{{dm-translate this}}
						</span>
					</div>
				{{/each}}
			</div>
		</div>
</script>
<script type="text/x-handlebars" id="upgrade-overlay-tmpl">
	<div class="upgradeOverlay">
		<div class="{{classNames}}">
			<div class="txt">{{buttonText}}</div>
		</div>
	</div>
</script><div id="_editor" class="dudaoneFloatedSpot neeWrapper"></div>
        <!-- hidden panel to slide right when activated -->
        <div id="dudaoneInnerShellSlidePanel" class="dudaoneSlidePanel"></div>
        <div id="dudaoneInnerShellContactLibrarySlidePanel" class="dudaoneSlidePanel"></div>

        <link rel="stylesheet" type="text/css" href="https://static.cdn-website.com/mnlt/production/5860/editor/dist/css/duda-css-ed-package.min.css" />
<div id='innerElementsWrapper'>

            <div class="smartInnerPanel dmNoMark" id="smartInnerPanel">
    <div class="newRulePage">
	    <div id="rulesWizardContainer" class="newDudaGeneralStyles">
			<script type="text/x-handlebars" data-template-name="rule-wizard@application">
			    {{outlet}}
			    {{partial "footer"}}
			</script>
		</div>
    </div>
</div>
</div>

        <div id="editModePanel" style="display:none;">
            <div id="toggleEditMode">
                <div class="inner">
                    <svg viewBox="0 0 32 32">
                        <path d="M6.806 31.619c0.49-1.602 1.232-3.858 2.226-7.122 4.33-0.699 6.122 0.558 8.872-4.454-2.232 0.698-4.923-1.294-4.778-2.157 0.144-0.864 6.261 0.622 10.264-5.181-5.046 1.134-6.662-1.365-6.011-1.742 1.502-0.872 5.963-0.362 8.341-2.725 1.226-1.216 1.798-4.174 1.301-5.23-0.6-1.274-4.251-3.174-6.264-2.997-2.013 0.179-5.17 7.822-6.106 7.762s-1.123-3.422 0.51-6.549c-1.723 0.778-4.88 3.198-5.87 5.267-1.845 3.85 0.173 12.677-0.474 12.992-0.648 0.314-2.826-4.053-3.475-6.032-0.888 3.034-0.909 6.074 1.686 10.112-0.979 2.65-1.514 5.699-1.595 7.25-0.038 1.242 1.157 1.507 1.373 0.806z"/>
                    </svg>
                </div>
            </div>
        </div>
        <link href="https://irp.cdn-website.com/fonts/css2?family=Roboto:wght@500&family=Source+Sans+Pro:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700;1,900&display=swap" rel="stylesheet">

<!--Duda One CSS Include-->
<script type="text/async" id="1392365447">PGxpbmsgcmVsPSJzdHlsZXNoZWV0IiB0eXBlPSJ0ZXh0L2NzcyIgaHJlZj0iaHR0cHM6Ly9zdGF0aWMuY2RuLXdlYnNpdGUuY29tL21ubHQvcHJvZHVjdGlvbi81ODYwL2VkaXRvci9kaXN0L2Nzcy9kdWRhLWNzcy1lZC13aWRnZXRzLm1pbi5jc3MiIC8+Cg==</script>
<!--End of Duda One CSS Include-->
<!--Page load improvement - Better CSS includes-->
<link type="text/css" rel="stylesheet"
      href="/editor/customUser/css/ed.hidden.css.jsp?version=2025-10-16T12_48_49&ts=1753977062752&accountId=824747&siteAlias=102ec7d9">
<link type="text/css" rel="stylesheet"
      href="/_dm/s/rt/css/font-icons/dm-static-font/style.css?version=2025-10-16T12_48_49"/>
<link rel="stylesheet" type="text/css" href="/editor/stylesheets/ed.editor.colors.css?version=2025-10-16T12_48_49"/>

<!-- Load css variables for whitelabling -->
<style>
  :root {
   --font-size-h1: 48px;  --logo-url: url(https://irp.cdn-website.com/-resellers-preview/chris@carpediemcg.com/logo/npq43qj6qn05e0dsimm9o1mu52.png);  --backgroundImage: none;  --text-on-button: #ffffff;  --editorTopBarHover: rgb(2,158,229);  --font-size-h6: 16px;  --font-size-h4: 24px;  --font-size-h5: 20px;  --font-size-he-1: 16px;  --font-size-h2: 40px;  --font-size-plain-text: 16px;  --font-size-h3: 32px;  --font-size-body-text: 13px;  --font-size-body: 14px;  --font-size-he-4: 12px;  --font-size-italic: 14px;  --font-size-he-2: 14px;  --font-size-he-3: 13px;  --d-font: Label Sans;  --button-color: #03a9f4;  --font-size-bodySubtitle: 14px;  --header-color: #2c3e50;  --font-size-display-2: 24px;  --header-border-color: #1e2b38;  --font-size-display-1: 32px;  --font-size-tiny-text: 12px;  --backgroundColor: #f7f7f7;  --font-size-display-4: 10px;  --font-size-display-3: 20px;  --d-one-blue: #407ab0;  --font-size-footer: 12px;  --visible-button-hover-color: rgb(2,153,222);  --font-size-tiny: 13px;  --editor-header-color: #2c3e50;  --link-color: #8c8c8c;  --button-visible-font-color: #ffffff;  --text-on-dark: ;  --header-text-color: #ffffff;  --oneHeaderColor: #2c3e50;  --d-title-font: Label Sans;  --font-size-pageDescription: 16px;  --oneButtonColorHalfTransparent: rgba(3,169,244,0.5);  --oneDevicesFontIconColor: #2c3e50;  --editor-left-panel-width: 98px;  --d-one-orange: #f56033;  --button-hover-color: #F86F4C;  --text-on-light: #2094c9; 
    --editor-left-panel-width: 98px;
  
  }
</style>
<!-- Set the branding colors global to support polyfilling cssVariables -->
<script>
    window.brandingColors = {"faviconUrl":"https://irp.cdn-website.com/-resellers-preview/chris@carpediemcg.com/favicon/j5u94g4svl0rdtk0l8a2mopovf.png","header-color":"#2c3e50","button-color":"#03a9f4","button-hover-color":"#03a9f4","text-on-light":"#2094c9","text-on-button":"#ffffff","logo-url":"https://irp.cdn-website.com/-resellers-preview/chris@carpediemcg.com/logo/npq43qj6qn05e0dsimm9o1mu52.png","header-border-color":"#1e2b38","header-text-color":"#ffffff"};
</script>
<style>
  /* branding colors definition */
  :root {  --button-color: #03a9f4;   --button-hover-color:
#03a9f4;   --text-on-light: #2094c9;    --text-on-button: #ffffff;   --header-color: #2c3e50;   --header-border-color:
#1e2b38;   --header-text-color: #ffffff;  }
</style>
<style id="wlCustomCss">
    </style>
<!-- CSS fix for IE11 -->
<!-- external -->

<!-- <script src="//cdn.mindtouch.us/f1.js" ></script> -->
<!--***************** END COMMON JS *************************************-->

<!-- End of Duda One JS Include-->

<!--***************** COMMON SCRIPTS GOES HERE*****************************-->
<!-- common include file -->
<script src="/editor/nee/utils/nee.b64.js"></script>
<script type="text/javascript" src="/common/commonStringsScript.jsp?lang=en&v=2025-10-16T12_48_49"></script>
<script type="text/javascript" src="/editor/nee/utils/common/modules/module.storage.js"></script>
<script type="text/javascript" src="/editor/nee/utils/common/modules/module.cookies.js"></script>
<script type="text/javascript" src="/common/commonPropsScript.jsp?config="></script>
<script type="text/javascript" src="/common/scripts/dm.trackstats.jsp?v=2025-10-16T12_48_49"></script>
<script type="text/javascript" src="/editor/scripts/jquery-cookie.js"></script>
<script type="text/javascript" src="/editor/scripts/dm.deferred.js"></script>
<script type="text/javascript" src="//apis.google.com/js/api.js"></script>

<script>
/**
 * PT tips module
 */
(function($){
	
	var configs = {
			buildVersion : ''
	};
	
	$.extend({ptConfigs : configs});
	
}(jQuery));

</script>
<script type="text/javascript">
    /** See source for details */
    window.envInfo = {
        
        environment: "direct",
        
        production: true
    }
</script><!-- start analytics section -->
<script src="https://static.cdn-website.com/mnlt/production/5860/editor/dist/scripts/common.head.js.min.js" ></script>
<script type="text/javascript">
    window.plansData = {
        encodedPlans: "eyI0NCI6eyJwbGFuSWQiOjQ0LCJncmFkZSI6NywibmFtZSI6IlRJRVJfRF9FQ1dJRCIsImZlYXR1cmVzIjpbIkFERF9QQUdFIiwiWU9VVFVCRSIsIlBPV0VSRURfQlkiLCJQVVNIX05PVElGSUNBVElPTlMiLCJDTElFTlRTIiwiRUNPTU1FUkNFX1hfTEFSR0UiLCJTRUVfRlVMTF9TVEFUUyIsIklDT04iLCJHT09HTEVfQ0FMRU5EQVIiLCJDTElDS19UT19DQUxMIiwiQ1VTVE9NX1dJREdFVCIsIlVTRV9DVVNUT01fRE9NQUlOIiwiV09SRFBSRVNTX0ZFRUQiLCJFQ09NTUVSQ0VfTEFSR0UiLCJBRFZBTkNFRF9FRElUT1IiLCJDT1VOVERPV04iLCJSRU1PVkVfRk9PVEVSIiwiQ0xJQ0tfVE9fU01TIiwiTkFWX0xJTktTIiwiU0hBUkUiLCJDT0xMRUNUSU9OUyIsIklOU0lURSIsIkVESVRfQkFDS0dST1VORCIsIkVDT01NRVJDRV9NRURJVU0iLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTE9HSU5fQkFSIiwiVEFCTEUiLCJJTUFHRV9TTElERVIiLCJCRUZPUkVfQU5EX0FGVEVSIiwiRElTUVVTIiwiQ0xJQ0tfVE9fTUFQIiwiT1BFTl9UQUJMRSIsIlBBWVBBTCIsIlNJR05VUCIsIlBBU1NXT1JEX1BST1RFQ1RFRF9QQUdFUyIsIkdFT19MT0NBVElPTiIsIkhJREVfUEFHRV9QRVJfREVWSUNFIiwiRUNPTU1FUkNFX1NNQUxMIiwiVkNJVEEiLCJQT1BVUFMiLCJNVUxUSUxJTkdVQUwiLCJCTE9HIiwiQ09VUE9OIiwiUkVTVEFVUkFOVF9NRU5VX1JFU1AiLCJDVVNUT01fSFRNTCIsIlNPQ0lBTF9IVUIiLCJGSUxFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJOQVRJVkVfU1RPUkUiLCJZRUxQIiwiRFlOQU1JQ19QQUdFUyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiRkFDRUJPT0tfTElLRSIsIlVSTF9SRURJUkVDVCIsIk1FTUJFUlNISVAiLCJOT19BRFMiXSwiaXNGcmVlIjpmYWxzZSwiY2FuUmVzZWxsZXJQdWJsaXNoIjp0cnVlLCJ0eXBlIjoiRFVEQU9ORSIsInBhcmVudElkIjo0MywiY2hpbGRyZW4iOltdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjozNCwiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCIyMiI6eyJwbGFuSWQiOjIyLCJncmFkZSI6NywibmFtZSI6IkJVU0lORVNTX1BMVVNfRUxJVEVfTkFUSVZFX1NUT1JFIiwiZmVhdHVyZXMiOlsiQUREX1BBR0UiLCJZT1VUVUJFIiwiUE9XRVJFRF9CWSIsIlBVU0hfTk9USUZJQ0FUSU9OUyIsIkNMSUVOVFMiLCJTRUVfRlVMTF9TVEFUUyIsIklDT04iLCJHT09HTEVfQ0FMRU5EQVIiLCJDTElDS19UT19DQUxMIiwiQ1VTVE9NX1dJREdFVCIsIlVTRV9DVVNUT01fRE9NQUlOIiwiV09SRFBSRVNTX0ZFRUQiLCJBRFZBTkNFRF9FRElUT1IiLCJDT1VOVERPV04iLCJSRU1PVkVfRk9PVEVSIiwiQ0xJQ0tfVE9fU01TIiwiTkFWX0xJTktTIiwiU0hBUkUiLCJDT0xMRUNUSU9OUyIsIklOU0lURSIsIkVESVRfQkFDS0dST1VORCIsIlRXSVRURVIiLCJDU1NfRURJVE9SIiwiT1BFTklOR19IT1VSUyIsIlRSVUVfTE9DQUxfUkVWSUVXUyIsIlJFU1RBVVJBTlRfTUVOVSIsIlBSRU1JVU1fSU1BR0VTX0VOQUJMRUQiLCJXSElURV9MQUJFTCIsIkhJREVfUEVSX0RFVklDRSIsIkJBQ0tVUFMiLCJOQVRJVkVfQk9PS0lORyIsIkxPR0lOX0JBUiIsIlRBQkxFIiwiSU1BR0VfU0xJREVSIiwiQkVGT1JFX0FORF9BRlRFUiIsIkRJU1FVUyIsIkNMSUNLX1RPX01BUCIsIk9QRU5fVEFCTEUiLCJQQVlQQUwiLCJTSUdOVVAiLCJQQVNTV09SRF9QUk9URUNURURfUEFHRVMiLCJHRU9fTE9DQVRJT04iLCJISURFX1BBR0VfUEVSX0RFVklDRSIsIkVDT01NRVJDRV9TTUFMTCIsIlZDSVRBIiwiUE9QVVBTIiwiQkxPRyIsIk1VTFRJTElOR1VBTCIsIkNPVVBPTiIsIlJFU1RBVVJBTlRfTUVOVV9SRVNQIiwiQ1VTVE9NX0hUTUwiLCJTT0NJQUxfSFVCIiwiRklMRSIsIkNMSUNLX1RPX0VNQUlMIiwiTkFUSVZFX1NUT1JFIiwiWUVMUCIsIkRZTkFNSUNfUEFHRVMiLCJGQUNFQk9PS19DT01NRU5UUyIsIkZBQ0VCT09LX0xJS0UiLCJVUkxfUkVESVJFQ1QiLCJNRU1CRVJTSElQIiwiTk9fQURTIl0sImlzRnJlZSI6ZmFsc2UsImNhblJlc2VsbGVyUHVibGlzaCI6dHJ1ZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6MjEsImNoaWxkcmVuIjpbXSwiYWx0ZXJuYXRpdmVQYXJlbnRJZCI6bnVsbCwiYWx0ZXJuYXRpdmVDaGlsZElkIjoxMCwidG9vbHRpcFNldHRpbmdzIjpudWxsfSwiMzMiOnsicGxhbklkIjozMywiZ3JhZGUiOjQsIm5hbWUiOiJUSUVSX0MiLCJmZWF0dXJlcyI6WyJBRERfUEFHRSIsIllPVVRVQkUiLCJQT1dFUkVEX0JZIiwiUFVTSF9OT1RJRklDQVRJT05TIiwiQ0xJRU5UUyIsIlNFRV9GVUxMX1NUQVRTIiwiSUNPTiIsIkdPT0dMRV9DQUxFTkRBUiIsIkNMSUNLX1RPX0NBTEwiLCJDVVNUT01fV0lER0VUIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIlJFTU9WRV9GT09URVIiLCJDTElDS19UT19TTVMiLCJOQVZfTElOS1MiLCJTSEFSRSIsIkNPTExFQ1RJT05TIiwiSU5TSVRFIiwiRURJVF9CQUNLR1JPVU5EIiwiVFdJVFRFUiIsIkNTU19FRElUT1IiLCJPUEVOSU5HX0hPVVJTIiwiVFJVRV9MT0NBTF9SRVZJRVdTIiwiUkVTVEFVUkFOVF9NRU5VIiwiUFJFTUlVTV9JTUFHRVNfRU5BQkxFRCIsIldISVRFX0xBQkVMIiwiSElERV9QRVJfREVWSUNFIiwiQkFDS1VQUyIsIkxPR0lOX0JBUiIsIlRBQkxFIiwiSU1BR0VfU0xJREVSIiwiQkVGT1JFX0FORF9BRlRFUiIsIkRJU1FVUyIsIkNMSUNLX1RPX01BUCIsIk9QRU5fVEFCTEUiLCJQQVlQQUwiLCJTSUdOVVAiLCJQQVNTV09SRF9QUk9URUNURURfUEFHRVMiLCJHRU9fTE9DQVRJT04iLCJISURFX1BBR0VfUEVSX0RFVklDRSIsIkVDT01NRVJDRV9TTUFMTCIsIlZDSVRBIiwiUE9QVVBTIiwiTVVMVElMSU5HVUFMIiwiQkxPRyIsIkNPVVBPTiIsIlJFU1RBVVJBTlRfTUVOVV9SRVNQIiwiQ1VTVE9NX0hUTUwiLCJTT0NJQUxfSFVCIiwiRklMRSIsIkNMSUNLX1RPX0VNQUlMIiwiTkFUSVZFX1NUT1JFIiwiWUVMUCIsIkRZTkFNSUNfUEFHRVMiLCJGQUNFQk9PS19DT01NRU5UUyIsIkZBQ0VCT09LX0xJS0UiLCJVUkxfUkVESVJFQ1QiLCJNRU1CRVJTSElQIiwiTk9fQURTIl0sImlzRnJlZSI6ZmFsc2UsImNhblJlc2VsbGVyUHVibGlzaCI6dHJ1ZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6MzIsImNoaWxkcmVuIjpbMzRdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjpudWxsLCJhbHRlcm5hdGl2ZUNoaWxkSWQiOjQzLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCIzNCI6eyJwbGFuSWQiOjM0LCJncmFkZSI6NiwibmFtZSI6IlRJRVJfRCIsImZlYXR1cmVzIjpbIkFERF9QQUdFIiwiWU9VVFVCRSIsIlBPV0VSRURfQlkiLCJQVVNIX05PVElGSUNBVElPTlMiLCJDTElFTlRTIiwiU0VFX0ZVTExfU1RBVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJVU0VfQ1VTVE9NX0RPTUFJTiIsIldPUkRQUkVTU19GRUVEIiwiQURWQU5DRURfRURJVE9SIiwiQ09VTlRET1dOIiwiUkVNT1ZFX0ZPT1RFUiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTE9HSU5fQkFSIiwiVEFCTEUiLCJJTUFHRV9TTElERVIiLCJCRUZPUkVfQU5EX0FGVEVSIiwiRElTUVVTIiwiQ0xJQ0tfVE9fTUFQIiwiT1BFTl9UQUJMRSIsIlBBWVBBTCIsIlNJR05VUCIsIlBBU1NXT1JEX1BST1RFQ1RFRF9QQUdFUyIsIkdFT19MT0NBVElPTiIsIkhJREVfUEFHRV9QRVJfREVWSUNFIiwiRUNPTU1FUkNFX1NNQUxMIiwiVkNJVEEiLCJQT1BVUFMiLCJNVUxUSUxJTkdVQUwiLCJCTE9HIiwiQ09VUE9OIiwiUkVTVEFVUkFOVF9NRU5VX1JFU1AiLCJDVVNUT01fSFRNTCIsIlNPQ0lBTF9IVUIiLCJGSUxFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJOQVRJVkVfU1RPUkUiLCJZRUxQIiwiRFlOQU1JQ19QQUdFUyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiRkFDRUJPT0tfTElLRSIsIlVSTF9SRURJUkVDVCIsIk1FTUJFUlNISVAiLCJOT19BRFMiXSwiaXNGcmVlIjpmYWxzZSwiY2FuUmVzZWxsZXJQdWJsaXNoIjp0cnVlLCJ0eXBlIjoiRFVEQU9ORSIsInBhcmVudElkIjozMywiY2hpbGRyZW4iOltdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjpudWxsLCJhbHRlcm5hdGl2ZUNoaWxkSWQiOjQ0LCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCIxIjp7InBsYW5JZCI6MSwiZ3JhZGUiOjAsIm5hbWUiOiJERUZBVUxUIiwiZmVhdHVyZXMiOlsiVEFCTEUiLCJDVVNUT01fSFRNTCIsIkNPVU5URE9XTiIsIkFOQUxZVElDUyIsIlNIQVJFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJCRUZPUkVfQU5EX0FGVEVSIiwiR09PR0xFX0NBTEVOREFSIiwiVFdJVFRFUiIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiVkNJVEEiLCJTRU5EX0VNQUlMIiwiV09SRFBSRVNTX0ZFRUQiXSwiaXNGcmVlIjp0cnVlLCJjYW5SZXNlbGxlclB1Ymxpc2giOmZhbHNlLCJ0eXBlIjoiTU9CSUxFIiwicGFyZW50SWQiOm51bGwsImNoaWxkcmVuIjpbMl0sImFsdGVybmF0aXZlUGFyZW50SWQiOm51bGwsImFsdGVybmF0aXZlQ2hpbGRJZCI6bnVsbCwidG9vbHRpcFNldHRpbmdzIjpudWxsfSwiMiI6eyJwbGFuSWQiOjIsImdyYWRlIjowLCJuYW1lIjoiRlJFRSIsImZlYXR1cmVzIjpbIlRBQkxFIiwiQ1VTVE9NX0hUTUwiLCJDT1VOVERPV04iLCJBTkFMWVRJQ1MiLCJTSEFSRSIsIkNMSUNLX1RPX0VNQUlMIiwiQkVGT1JFX0FORF9BRlRFUiIsIlNFRV9GVUxMX1NUQVRTIiwiR09PR0xFX0NBTEVOREFSIiwiVFdJVFRFUiIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJWQ0lUQSIsIkZBQ0VCT09LX0xJS0UiLCJTRU5EX0VNQUlMIiwiV09SRFBSRVNTX0ZFRUQiXSwiaXNGcmVlIjp0cnVlLCJjYW5SZXNlbGxlclB1Ymxpc2giOmZhbHNlLCJ0eXBlIjoiTU9CSUxFIiwicGFyZW50SWQiOjEsImNoaWxkcmVuIjpbM10sImFsdGVybmF0aXZlUGFyZW50SWQiOm51bGwsImFsdGVybmF0aXZlQ2hpbGRJZCI6bnVsbCwidG9vbHRpcFNldHRpbmdzIjpudWxsfSwiMyI6eyJwbGFuSWQiOjMsImdyYWRlIjoxLCJuYW1lIjoiUFJFTUlVTSIsImZlYXR1cmVzIjpbIkFEU0VOU0UiLCJXSElURV9MQUJFTCIsIkJBQ0tVUFMiLCJUQUJMRSIsIkFOQUxZVElDUyIsIkJFRk9SRV9BTkRfQUZURVIiLCJDTElDS19UT19NQVAiLCJQVVNIX05PVElGSUNBVElPTlMiLCJTRUVfRlVMTF9TVEFUUyIsIkdPT0dMRV9DQUxFTkRBUiIsIkNMSUNLX1RPX0NBTEwiLCJPUEVOX1RBQkxFIiwiUEFZUEFMIiwiR0VPX0xPQ0FUSU9OIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJWQ0lUQSIsIlNFTkRfRU1BSUwiLCJXT1JEUFJFU1NfRkVFRCIsIkNPVVBPTiIsIkNVU1RPTV9IVE1MIiwiQ09VTlRET1dOIiwiQ09OU1RBTlRfQ09OVEFDVCIsIkNMSUNLX1RPX1NNUyIsIkdPT0dMRV9DSEVDS09VVCIsIlNIQVJFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJZRUxQIiwiVFdJVFRFUiIsIk5PX1BST01fTElOSyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiT1BFTklOR19IT1VSUyIsIlJFU1RBVVJBTlRfTUVOVSIsIkZBQ0VCT09LX0xJS0UiLCJTRU5EX0JVU0lORVNTX0lORk8iLCJOT19BRFMiXSwiaXNGcmVlIjpmYWxzZSwiY2FuUmVzZWxsZXJQdWJsaXNoIjp0cnVlLCJ0eXBlIjoiTU9CSUxFIiwicGFyZW50SWQiOjIsImNoaWxkcmVuIjpbXSwiYWx0ZXJuYXRpdmVQYXJlbnRJZCI6bnVsbCwiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCI1Ijp7InBsYW5JZCI6NSwiZ3JhZGUiOjAsIm5hbWUiOiJGUkVFIiwiZmVhdHVyZXMiOlsiQUREX1BBR0UiLCJZT1VUVUJFIiwiUE9XRVJFRF9CWSIsIlBVU0hfTk9USUZJQ0FUSU9OUyIsIkNMSUVOVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTkFUSVZFX0JPT0tJTkciLCJMT0dJTl9CQVIiLCJUQUJMRSIsIklNQUdFX1NMSURFUiIsIkJFRk9SRV9BTkRfQUZURVIiLCJESVNRVVMiLCJDTElDS19UT19NQVAiLCJPUEVOX1RBQkxFIiwiUEFZUEFMIiwiU0lHTlVQIiwiUEFTU1dPUkRfUFJPVEVDVEVEX1BBR0VTIiwiR0VPX0xPQ0FUSU9OIiwiSElERV9QQUdFX1BFUl9ERVZJQ0UiLCJFQ09NTUVSQ0VfU01BTEwiLCJWQ0lUQSIsIlBPUFVQUyIsIkJMT0ciLCJNVUxUSUxJTkdVQUwiLCJDT1VQT04iLCJSRVNUQVVSQU5UX01FTlVfUkVTUCIsIkNVU1RPTV9IVE1MIiwiU09DSUFMX0hVQiIsIkZJTEUiLCJDTElDS19UT19FTUFJTCIsIk5BVElWRV9TVE9SRSIsIllFTFAiLCJEWU5BTUlDX1BBR0VTIiwiRkFDRUJPT0tfQ09NTUVOVFMiLCJGQUNFQk9PS19MSUtFIiwiVVJMX1JFRElSRUNUIiwiTUVNQkVSU0hJUCIsIk5PX0FEUyJdLCJpc0ZyZWUiOnRydWUsImNhblJlc2VsbGVyUHVibGlzaCI6ZmFsc2UsInR5cGUiOiJEVURBT05FIiwicGFyZW50SWQiOm51bGwsImNoaWxkcmVuIjpbNl0sImFsdGVybmF0aXZlUGFyZW50SWQiOm51bGwsImFsdGVybmF0aXZlQ2hpbGRJZCI6bnVsbCwidG9vbHRpcFNldHRpbmdzIjpudWxsfSwiNiI6eyJwbGFuSWQiOjYsImdyYWRlIjoxLCJuYW1lIjoiQlVTSU5FU1MiLCJmZWF0dXJlcyI6WyJBRERfUEFHRSIsIllPVVRVQkUiLCJQT1dFUkVEX0JZIiwiUFVTSF9OT1RJRklDQVRJT05TIiwiQ0xJRU5UUyIsIlNFRV9GVUxMX1NUQVRTIiwiSUNPTiIsIkdPT0dMRV9DQUxFTkRBUiIsIkNMSUNLX1RPX0NBTEwiLCJDVVNUT01fV0lER0VUIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIlJFTU9WRV9GT09URVIiLCJDTElDS19UT19TTVMiLCJOQVZfTElOS1MiLCJTSEFSRSIsIkNPTExFQ1RJT05TIiwiSU5TSVRFIiwiRURJVF9CQUNLR1JPVU5EIiwiVFdJVFRFUiIsIkNTU19FRElUT1IiLCJPUEVOSU5HX0hPVVJTIiwiVFJVRV9MT0NBTF9SRVZJRVdTIiwiUkVTVEFVUkFOVF9NRU5VIiwiUFJFTUlVTV9JTUFHRVNfRU5BQkxFRCIsIldISVRFX0xBQkVMIiwiSElERV9QRVJfREVWSUNFIiwiQkFDS1VQUyIsIk5BVElWRV9CT09LSU5HIiwiTE9HSU5fQkFSIiwiVEFCTEUiLCJJTUFHRV9TTElERVIiLCJCRUZPUkVfQU5EX0FGVEVSIiwiRElTUVVTIiwiQ0xJQ0tfVE9fTUFQIiwiT1BFTl9UQUJMRSIsIlBBWVBBTCIsIlNJR05VUCIsIlBBU1NXT1JEX1BST1RFQ1RFRF9QQUdFUyIsIkdFT19MT0NBVElPTiIsIkhJREVfUEFHRV9QRVJfREVWSUNFIiwiRUNPTU1FUkNFX1NNQUxMIiwiVkNJVEEiLCJQT1BVUFMiLCJCTE9HIiwiTVVMVElMSU5HVUFMIiwiQ09VUE9OIiwiUkVTVEFVUkFOVF9NRU5VX1JFU1AiLCJDVVNUT01fSFRNTCIsIlNPQ0lBTF9IVUIiLCJGSUxFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJOQVRJVkVfU1RPUkUiLCJZRUxQIiwiRFlOQU1JQ19QQUdFUyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiRkFDRUJPT0tfTElLRSIsIlVSTF9SRURJUkVDVCIsIk1FTUJFUlNISVAiLCJOT19BRFMiXSwiaXNGcmVlIjpmYWxzZSwiY2FuUmVzZWxsZXJQdWJsaXNoIjpmYWxzZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6NSwiY2hpbGRyZW4iOls3XSwiYWx0ZXJuYXRpdmVQYXJlbnRJZCI6bnVsbCwiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOnsidGl0bGUiOiJ1aS50aXJlLnRpdGxlIiwidXBncmFkZXMiOlsidWkudXBncmFkZS4xIiwidWkudXBncmFkZS4yIiwidWkudXBncmFkZS4zIiwidWkudXBncmFkZS41Il19fSwiNyI6eyJwbGFuSWQiOjcsImdyYWRlIjoyLCJuYW1lIjoiQlVTSU5FU1NfUExVUyIsImZlYXR1cmVzIjpbIkFERF9QQUdFIiwiWU9VVFVCRSIsIlBPV0VSRURfQlkiLCJQVVNIX05PVElGSUNBVElPTlMiLCJDTElFTlRTIiwiU0VFX0ZVTExfU1RBVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJVU0VfQ1VTVE9NX0RPTUFJTiIsIldPUkRQUkVTU19GRUVEIiwiQURWQU5DRURfRURJVE9SIiwiQ09VTlRET1dOIiwiUkVNT1ZFX0ZPT1RFUiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTkFUSVZFX0JPT0tJTkciLCJMT0dJTl9CQVIiLCJUQUJMRSIsIklNQUdFX1NMSURFUiIsIkJFRk9SRV9BTkRfQUZURVIiLCJESVNRVVMiLCJDTElDS19UT19NQVAiLCJPUEVOX1RBQkxFIiwiUEFZUEFMIiwiU0lHTlVQIiwiUEFTU1dPUkRfUFJPVEVDVEVEX1BBR0VTIiwiR0VPX0xPQ0FUSU9OIiwiSElERV9QQUdFX1BFUl9ERVZJQ0UiLCJFQ09NTUVSQ0VfU01BTEwiLCJWQ0lUQSIsIlBPUFVQUyIsIkJMT0ciLCJNVUxUSUxJTkdVQUwiLCJDT1VQT04iLCJSRVNUQVVSQU5UX01FTlVfUkVTUCIsIkNVU1RPTV9IVE1MIiwiU09DSUFMX0hVQiIsIkZJTEUiLCJDTElDS19UT19FTUFJTCIsIk5BVElWRV9TVE9SRSIsIllFTFAiLCJEWU5BTUlDX1BBR0VTIiwiRkFDRUJPT0tfQ09NTUVOVFMiLCJGQUNFQk9PS19MSUtFIiwiVVJMX1JFRElSRUNUIiwiTUVNQkVSU0hJUCIsIk5PX0FEUyJdLCJpc0ZyZWUiOmZhbHNlLCJjYW5SZXNlbGxlclB1Ymxpc2giOnRydWUsInR5cGUiOiJEVURBT05FIiwicGFyZW50SWQiOjYsImNoaWxkcmVuIjpbMjBdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjpudWxsLCJhbHRlcm5hdGl2ZUNoaWxkSWQiOm51bGwsInRvb2x0aXBTZXR0aW5ncyI6eyJ0aXRsZSI6InVpLnRpcmUudGl0bGUiLCJ1cGdyYWRlcyI6WyJ1aS51cGdyYWRlLjEiLCJ1aS51cGdyYWRlLjIiLCJ1aS51cGdyYWRlLjMiLCJ1aS51cGdyYWRlLjUiXX19LCI4Ijp7InBsYW5JZCI6OCwiZ3JhZGUiOjQsIm5hbWUiOiJCVVNJTkVTU19QTFVTX0VDT01NRVJDRV9NRURJVU0iLCJmZWF0dXJlcyI6WyJBRERfUEFHRSIsIllPVVRVQkUiLCJQT1dFUkVEX0JZIiwiUFVTSF9OT1RJRklDQVRJT05TIiwiQ0xJRU5UUyIsIlNFRV9GVUxMX1NUQVRTIiwiSUNPTiIsIkdPT0dMRV9DQUxFTkRBUiIsIkNMSUNLX1RPX0NBTEwiLCJDVVNUT01fV0lER0VUIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIlJFTU9WRV9GT09URVIiLCJDTElDS19UT19TTVMiLCJOQVZfTElOS1MiLCJTSEFSRSIsIkNPTExFQ1RJT05TIiwiSU5TSVRFIiwiRURJVF9CQUNLR1JPVU5EIiwiRUNPTU1FUkNFX01FRElVTSIsIlRXSVRURVIiLCJDU1NfRURJVE9SIiwiT1BFTklOR19IT1VSUyIsIlRSVUVfTE9DQUxfUkVWSUVXUyIsIlJFU1RBVVJBTlRfTUVOVSIsIlBSRU1JVU1fSU1BR0VTX0VOQUJMRUQiLCJXSElURV9MQUJFTCIsIkhJREVfUEVSX0RFVklDRSIsIkJBQ0tVUFMiLCJOQVRJVkVfQk9PS0lORyIsIkxPR0lOX0JBUiIsIlRBQkxFIiwiSU1BR0VfU0xJREVSIiwiQkVGT1JFX0FORF9BRlRFUiIsIkRJU1FVUyIsIkNMSUNLX1RPX01BUCIsIk9QRU5fVEFCTEUiLCJQQVlQQUwiLCJTSUdOVVAiLCJQQVNTV09SRF9QUk9URUNURURfUEFHRVMiLCJHRU9fTE9DQVRJT04iLCJISURFX1BBR0VfUEVSX0RFVklDRSIsIkVDT01NRVJDRV9TTUFMTCIsIlZDSVRBIiwiUE9QVVBTIiwiQkxPRyIsIk1VTFRJTElOR1VBTCIsIkNPVVBPTiIsIlJFU1RBVVJBTlRfTUVOVV9SRVNQIiwiQ1VTVE9NX0hUTUwiLCJTT0NJQUxfSFVCIiwiRklMRSIsIkNMSUNLX1RPX0VNQUlMIiwiTkFUSVZFX1NUT1JFIiwiWUVMUCIsIkRZTkFNSUNfUEFHRVMiLCJGQUNFQk9PS19DT01NRU5UUyIsIkZBQ0VCT09LX0xJS0UiLCJVUkxfUkVESVJFQ1QiLCJNRU1CRVJTSElQIiwiTk9fQURTIl0sImlzRnJlZSI6ZmFsc2UsImNhblJlc2VsbGVyUHVibGlzaCI6dHJ1ZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6bnVsbCwiY2hpbGRyZW4iOls5XSwiYWx0ZXJuYXRpdmVQYXJlbnRJZCI6MjAsImFsdGVybmF0aXZlQ2hpbGRJZCI6bnVsbCwidG9vbHRpcFNldHRpbmdzIjp7InRpdGxlIjoidWkudXBncmFkZS50b29sdGlwLnRpdGxlIiwidXBncmFkZXMiOlsidWkudXBncmFkZS42IiwidWkudXBncmFkZS44IiwidWkudXBncmFkZS45IiwidWkuZWQuc3RvcmUucGxhbjguZ2lmdENhcmQua2V5IiwidWkudXBncmFkZS4xMCJdfX0sIjkiOnsicGxhbklkIjo5LCJncmFkZSI6NiwibmFtZSI6IkJVU0lORVNTX1BMVVNfRUNPTU1FUkNFX0xBUkdFIiwiZmVhdHVyZXMiOlsiQUREX1BBR0UiLCJZT1VUVUJFIiwiUE9XRVJFRF9CWSIsIlBVU0hfTk9USUZJQ0FUSU9OUyIsIkNMSUVOVFMiLCJTRUVfRlVMTF9TVEFUUyIsIklDT04iLCJHT09HTEVfQ0FMRU5EQVIiLCJDTElDS19UT19DQUxMIiwiQ1VTVE9NX1dJREdFVCIsIlVTRV9DVVNUT01fRE9NQUlOIiwiV09SRFBSRVNTX0ZFRUQiLCJFQ09NTUVSQ0VfTEFSR0UiLCJBRFZBTkNFRF9FRElUT1IiLCJDT1VOVERPV04iLCJSRU1PVkVfRk9PVEVSIiwiQ0xJQ0tfVE9fU01TIiwiTkFWX0xJTktTIiwiU0hBUkUiLCJDT0xMRUNUSU9OUyIsIklOU0lURSIsIkVESVRfQkFDS0dST1VORCIsIkVDT01NRVJDRV9NRURJVU0iLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTkFUSVZFX0JPT0tJTkciLCJMT0dJTl9CQVIiLCJUQUJMRSIsIklNQUdFX1NMSURFUiIsIkJFRk9SRV9BTkRfQUZURVIiLCJESVNRVVMiLCJDTElDS19UT19NQVAiLCJPUEVOX1RBQkxFIiwiUEFZUEFMIiwiU0lHTlVQIiwiUEFTU1dPUkRfUFJPVEVDVEVEX1BBR0VTIiwiR0VPX0xPQ0FUSU9OIiwiSElERV9QQUdFX1BFUl9ERVZJQ0UiLCJFQ09NTUVSQ0VfU01BTEwiLCJWQ0lUQSIsIlBPUFVQUyIsIkJMT0ciLCJNVUxUSUxJTkdVQUwiLCJDT1VQT04iLCJSRVNUQVVSQU5UX01FTlVfUkVTUCIsIkNVU1RPTV9IVE1MIiwiU09DSUFMX0hVQiIsIkZJTEUiLCJDTElDS19UT19FTUFJTCIsIk5BVElWRV9TVE9SRSIsIllFTFAiLCJEWU5BTUlDX1BBR0VTIiwiRkFDRUJPT0tfQ09NTUVOVFMiLCJGQUNFQk9PS19MSUtFIiwiVVJMX1JFRElSRUNUIiwiTUVNQkVSU0hJUCIsIk5PX0FEUyJdLCJpc0ZyZWUiOmZhbHNlLCJjYW5SZXNlbGxlclB1Ymxpc2giOnRydWUsInR5cGUiOiJEVURBT05FIiwicGFyZW50SWQiOjgsImNoaWxkcmVuIjpbMTBdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjoyMSwiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOnsidGl0bGUiOiJ1aS51cGdyYWRlLnRvb2x0aXAudGl0bGUiLCJ1cGdyYWRlcyI6WyJ1aS51cGdyYWRlLmFkdmFuY2VkLmV2ZXJ5dGhpbmciLCJ1aS51cGdyYWRlLjciLCJ1aS51cGdyYWRlLjExIiwidWkudXBncmFkZS4xMiIsInVpLnVwZ3JhZGUuZmlsdGVycyJdfX0sIjMwIjp7InBsYW5JZCI6MzAsImdyYWRlIjowLCJuYW1lIjoiRlJFRV9USUVSIiwiZmVhdHVyZXMiOlsiQUREX1BBR0UiLCJZT1VUVUJFIiwiUE9XRVJFRF9CWSIsIlBVU0hfTk9USUZJQ0FUSU9OUyIsIkNMSUVOVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTE9HSU5fQkFSIiwiVEFCTEUiLCJJTUFHRV9TTElERVIiLCJCRUZPUkVfQU5EX0FGVEVSIiwiRElTUVVTIiwiQ0xJQ0tfVE9fTUFQIiwiT1BFTl9UQUJMRSIsIlBBWVBBTCIsIlNJR05VUCIsIlBBU1NXT1JEX1BST1RFQ1RFRF9QQUdFUyIsIkdFT19MT0NBVElPTiIsIkhJREVfUEFHRV9QRVJfREVWSUNFIiwiRUNPTU1FUkNFX1NNQUxMIiwiVkNJVEEiLCJQT1BVUFMiLCJCTE9HIiwiQ09VUE9OIiwiUkVTVEFVUkFOVF9NRU5VX1JFU1AiLCJDVVNUT01fSFRNTCIsIlNPQ0lBTF9IVUIiLCJGSUxFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJOQVRJVkVfU1RPUkUiLCJZRUxQIiwiRFlOQU1JQ19QQUdFUyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiRkFDRUJPT0tfTElLRSIsIlVSTF9SRURJUkVDVCIsIk1FTUJFUlNISVAiLCJOT19BRFMiXSwiaXNGcmVlIjp0cnVlLCJjYW5SZXNlbGxlclB1Ymxpc2giOmZhbHNlLCJ0eXBlIjoiRFVEQU9ORSIsInBhcmVudElkIjpudWxsLCJjaGlsZHJlbiI6WzMxXSwiYWx0ZXJuYXRpdmVQYXJlbnRJZCI6bnVsbCwiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCIyMCI6eyJwbGFuSWQiOjIwLCJncmFkZSI6MywibmFtZSI6IkJVU0lORVNTX1BMVVNfTkFUSVZFX1NUT1JFIiwiZmVhdHVyZXMiOlsiQUREX1BBR0UiLCJZT1VUVUJFIiwiUE9XRVJFRF9CWSIsIlBVU0hfTk9USUZJQ0FUSU9OUyIsIkNMSUVOVFMiLCJTRUVfRlVMTF9TVEFUUyIsIklDT04iLCJHT09HTEVfQ0FMRU5EQVIiLCJDTElDS19UT19DQUxMIiwiQ1VTVE9NX1dJREdFVCIsIlVTRV9DVVNUT01fRE9NQUlOIiwiV09SRFBSRVNTX0ZFRUQiLCJBRFZBTkNFRF9FRElUT1IiLCJDT1VOVERPV04iLCJSRU1PVkVfRk9PVEVSIiwiQ0xJQ0tfVE9fU01TIiwiTkFWX0xJTktTIiwiU0hBUkUiLCJDT0xMRUNUSU9OUyIsIklOU0lURSIsIkVESVRfQkFDS0dST1VORCIsIlRXSVRURVIiLCJDU1NfRURJVE9SIiwiT1BFTklOR19IT1VSUyIsIlRSVUVfTE9DQUxfUkVWSUVXUyIsIlJFU1RBVVJBTlRfTUVOVSIsIlBSRU1JVU1fSU1BR0VTX0VOQUJMRUQiLCJXSElURV9MQUJFTCIsIkhJREVfUEVSX0RFVklDRSIsIkJBQ0tVUFMiLCJOQVRJVkVfQk9PS0lORyIsIkxPR0lOX0JBUiIsIlRBQkxFIiwiSU1BR0VfU0xJREVSIiwiQkVGT1JFX0FORF9BRlRFUiIsIkRJU1FVUyIsIkNMSUNLX1RPX01BUCIsIk9QRU5fVEFCTEUiLCJQQVlQQUwiLCJTSUdOVVAiLCJQQVNTV09SRF9QUk9URUNURURfUEFHRVMiLCJHRU9fTE9DQVRJT04iLCJISURFX1BBR0VfUEVSX0RFVklDRSIsIkVDT01NRVJDRV9TTUFMTCIsIlZDSVRBIiwiUE9QVVBTIiwiQkxPRyIsIk1VTFRJTElOR1VBTCIsIkNPVVBPTiIsIlJFU1RBVVJBTlRfTUVOVV9SRVNQIiwiQ1VTVE9NX0hUTUwiLCJTT0NJQUxfSFVCIiwiRklMRSIsIkNMSUNLX1RPX0VNQUlMIiwiTkFUSVZFX1NUT1JFIiwiWUVMUCIsIkRZTkFNSUNfUEFHRVMiLCJGQUNFQk9PS19DT01NRU5UUyIsIkZBQ0VCT09LX0xJS0UiLCJVUkxfUkVESVJFQ1QiLCJNRU1CRVJTSElQIiwiTk9fQURTIl0sImlzRnJlZSI6ZmFsc2UsImNhblJlc2VsbGVyUHVibGlzaCI6dHJ1ZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6NywiY2hpbGRyZW4iOlsyMV0sImFsdGVybmF0aXZlUGFyZW50SWQiOm51bGwsImFsdGVybmF0aXZlQ2hpbGRJZCI6OCwidG9vbHRpcFNldHRpbmdzIjpudWxsfSwiNDIiOnsicGxhbklkIjo0MiwiZ3JhZGUiOjMsIm5hbWUiOiJUSUVSX0JfRUNXSUQiLCJmZWF0dXJlcyI6WyJBRERfUEFHRSIsIllPVVRVQkUiLCJQT1dFUkVEX0JZIiwiUFVTSF9OT1RJRklDQVRJT05TIiwiQ0xJRU5UUyIsIlNFRV9GVUxMX1NUQVRTIiwiSUNPTiIsIkdPT0dMRV9DQUxFTkRBUiIsIkNMSUNLX1RPX0NBTEwiLCJDVVNUT01fV0lER0VUIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIlJFTU9WRV9GT09URVIiLCJDTElDS19UT19TTVMiLCJOQVZfTElOS1MiLCJTSEFSRSIsIkNPTExFQ1RJT05TIiwiSU5TSVRFIiwiRURJVF9CQUNLR1JPVU5EIiwiRUNPTU1FUkNFX01FRElVTSIsIlRXSVRURVIiLCJDU1NfRURJVE9SIiwiT1BFTklOR19IT1VSUyIsIlRSVUVfTE9DQUxfUkVWSUVXUyIsIlJFU1RBVVJBTlRfTUVOVSIsIlBSRU1JVU1fSU1BR0VTX0VOQUJMRUQiLCJXSElURV9MQUJFTCIsIkhJREVfUEVSX0RFVklDRSIsIkJBQ0tVUFMiLCJMT0dJTl9CQVIiLCJUQUJMRSIsIklNQUdFX1NMSURFUiIsIkJFRk9SRV9BTkRfQUZURVIiLCJESVNRVVMiLCJDTElDS19UT19NQVAiLCJPUEVOX1RBQkxFIiwiUEFZUEFMIiwiU0lHTlVQIiwiUEFTU1dPUkRfUFJPVEVDVEVEX1BBR0VTIiwiR0VPX0xPQ0FUSU9OIiwiSElERV9QQUdFX1BFUl9ERVZJQ0UiLCJFQ09NTUVSQ0VfU01BTEwiLCJWQ0lUQSIsIlBPUFVQUyIsIk1VTFRJTElOR1VBTCIsIkJMT0ciLCJDT1VQT04iLCJSRVNUQVVSQU5UX01FTlVfUkVTUCIsIkNVU1RPTV9IVE1MIiwiU09DSUFMX0hVQiIsIkZJTEUiLCJDTElDS19UT19FTUFJTCIsIk5BVElWRV9TVE9SRSIsIllFTFAiLCJEWU5BTUlDX1BBR0VTIiwiRkFDRUJPT0tfQ09NTUVOVFMiLCJGQUNFQk9PS19MSUtFIiwiVVJMX1JFRElSRUNUIiwiTUVNQkVSU0hJUCIsIk5PX0FEUyJdLCJpc0ZyZWUiOmZhbHNlLCJjYW5SZXNlbGxlclB1Ymxpc2giOnRydWUsInR5cGUiOiJEVURBT05FIiwicGFyZW50SWQiOm51bGwsImNoaWxkcmVuIjpbNDNdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjozMiwiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCIzMSI6eyJwbGFuSWQiOjMxLCJncmFkZSI6MSwibmFtZSI6IlRJRVJfQSIsImZlYXR1cmVzIjpbIkFERF9QQUdFIiwiWU9VVFVCRSIsIlBPV0VSRURfQlkiLCJQVVNIX05PVElGSUNBVElPTlMiLCJDTElFTlRTIiwiU0VFX0ZVTExfU1RBVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJVU0VfQ1VTVE9NX0RPTUFJTiIsIldPUkRQUkVTU19GRUVEIiwiQURWQU5DRURfRURJVE9SIiwiQ09VTlRET1dOIiwiUkVNT1ZFX0ZPT1RFUiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTE9HSU5fQkFSIiwiVEFCTEUiLCJJTUFHRV9TTElERVIiLCJCRUZPUkVfQU5EX0FGVEVSIiwiRElTUVVTIiwiQ0xJQ0tfVE9fTUFQIiwiT1BFTl9UQUJMRSIsIlBBWVBBTCIsIlNJR05VUCIsIlBBU1NXT1JEX1BST1RFQ1RFRF9QQUdFUyIsIkdFT19MT0NBVElPTiIsIkhJREVfUEFHRV9QRVJfREVWSUNFIiwiRUNPTU1FUkNFX1NNQUxMIiwiVkNJVEEiLCJQT1BVUFMiLCJCTE9HIiwiQ09VUE9OIiwiUkVTVEFVUkFOVF9NRU5VX1JFU1AiLCJDVVNUT01fSFRNTCIsIlNPQ0lBTF9IVUIiLCJGSUxFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJOQVRJVkVfU1RPUkUiLCJZRUxQIiwiRFlOQU1JQ19QQUdFUyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiRkFDRUJPT0tfTElLRSIsIlVSTF9SRURJUkVDVCIsIk1FTUJFUlNISVAiLCJOT19BRFMiXSwiaXNGcmVlIjpmYWxzZSwiY2FuUmVzZWxsZXJQdWJsaXNoIjp0cnVlLCJ0eXBlIjoiRFVEQU9ORSIsInBhcmVudElkIjozMCwiY2hpbGRyZW4iOlszMl0sImFsdGVybmF0aXZlUGFyZW50SWQiOm51bGwsImFsdGVybmF0aXZlQ2hpbGRJZCI6bnVsbCwidG9vbHRpcFNldHRpbmdzIjpudWxsfSwiMjEiOnsicGxhbklkIjoyMSwiZ3JhZGUiOjUsIm5hbWUiOiJCVVNJTkVTU19QTFVTX0FEVkFOQ0VEX05BVElWRV9TVE9SRSIsImZlYXR1cmVzIjpbIkFERF9QQUdFIiwiWU9VVFVCRSIsIlBPV0VSRURfQlkiLCJQVVNIX05PVElGSUNBVElPTlMiLCJDTElFTlRTIiwiU0VFX0ZVTExfU1RBVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJVU0VfQ1VTVE9NX0RPTUFJTiIsIldPUkRQUkVTU19GRUVEIiwiQURWQU5DRURfRURJVE9SIiwiQ09VTlRET1dOIiwiUkVNT1ZFX0ZPT1RFUiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJUV0lUVEVSIiwiQ1NTX0VESVRPUiIsIk9QRU5JTkdfSE9VUlMiLCJUUlVFX0xPQ0FMX1JFVklFV1MiLCJSRVNUQVVSQU5UX01FTlUiLCJQUkVNSVVNX0lNQUdFU19FTkFCTEVEIiwiV0hJVEVfTEFCRUwiLCJISURFX1BFUl9ERVZJQ0UiLCJCQUNLVVBTIiwiTkFUSVZFX0JPT0tJTkciLCJMT0dJTl9CQVIiLCJUQUJMRSIsIklNQUdFX1NMSURFUiIsIkJFRk9SRV9BTkRfQUZURVIiLCJESVNRVVMiLCJDTElDS19UT19NQVAiLCJPUEVOX1RBQkxFIiwiUEFZUEFMIiwiU0lHTlVQIiwiUEFTU1dPUkRfUFJPVEVDVEVEX1BBR0VTIiwiR0VPX0xPQ0FUSU9OIiwiSElERV9QQUdFX1BFUl9ERVZJQ0UiLCJFQ09NTUVSQ0VfU01BTEwiLCJWQ0lUQSIsIlBPUFVQUyIsIkJMT0ciLCJNVUxUSUxJTkdVQUwiLCJDT1VQT04iLCJSRVNUQVVSQU5UX01FTlVfUkVTUCIsIkNVU1RPTV9IVE1MIiwiU09DSUFMX0hVQiIsIkZJTEUiLCJDTElDS19UT19FTUFJTCIsIk5BVElWRV9TVE9SRSIsIllFTFAiLCJEWU5BTUlDX1BBR0VTIiwiRkFDRUJPT0tfQ09NTUVOVFMiLCJGQUNFQk9PS19MSUtFIiwiVVJMX1JFRElSRUNUIiwiTUVNQkVSU0hJUCIsIk5PX0FEUyJdLCJpc0ZyZWUiOmZhbHNlLCJjYW5SZXNlbGxlclB1Ymxpc2giOnRydWUsInR5cGUiOiJEVURBT05FIiwicGFyZW50SWQiOjIwLCJjaGlsZHJlbiI6WzIyXSwiYWx0ZXJuYXRpdmVQYXJlbnRJZCI6bnVsbCwiYWx0ZXJuYXRpdmVDaGlsZElkIjo5LCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCI0MyI6eyJwbGFuSWQiOjQzLCJncmFkZSI6NSwibmFtZSI6IlRJRVJfQ19FQ1dJRCIsImZlYXR1cmVzIjpbIkFERF9QQUdFIiwiWU9VVFVCRSIsIlBPV0VSRURfQlkiLCJQVVNIX05PVElGSUNBVElPTlMiLCJDTElFTlRTIiwiU0VFX0ZVTExfU1RBVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJVU0VfQ1VTVE9NX0RPTUFJTiIsIldPUkRQUkVTU19GRUVEIiwiRUNPTU1FUkNFX0xBUkdFIiwiQURWQU5DRURfRURJVE9SIiwiQ09VTlRET1dOIiwiUkVNT1ZFX0ZPT1RFUiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJFQ09NTUVSQ0VfTUVESVVNIiwiVFdJVFRFUiIsIkNTU19FRElUT1IiLCJPUEVOSU5HX0hPVVJTIiwiVFJVRV9MT0NBTF9SRVZJRVdTIiwiUkVTVEFVUkFOVF9NRU5VIiwiUFJFTUlVTV9JTUFHRVNfRU5BQkxFRCIsIldISVRFX0xBQkVMIiwiSElERV9QRVJfREVWSUNFIiwiQkFDS1VQUyIsIkxPR0lOX0JBUiIsIlRBQkxFIiwiSU1BR0VfU0xJREVSIiwiQkVGT1JFX0FORF9BRlRFUiIsIkRJU1FVUyIsIkNMSUNLX1RPX01BUCIsIk9QRU5fVEFCTEUiLCJQQVlQQUwiLCJTSUdOVVAiLCJQQVNTV09SRF9QUk9URUNURURfUEFHRVMiLCJHRU9fTE9DQVRJT04iLCJISURFX1BBR0VfUEVSX0RFVklDRSIsIkVDT01NRVJDRV9TTUFMTCIsIlZDSVRBIiwiUE9QVVBTIiwiTVVMVElMSU5HVUFMIiwiQkxPRyIsIkNPVVBPTiIsIlJFU1RBVVJBTlRfTUVOVV9SRVNQIiwiQ1VTVE9NX0hUTUwiLCJTT0NJQUxfSFVCIiwiRklMRSIsIkNMSUNLX1RPX0VNQUlMIiwiTkFUSVZFX1NUT1JFIiwiWUVMUCIsIkRZTkFNSUNfUEFHRVMiLCJGQUNFQk9PS19DT01NRU5UUyIsIkZBQ0VCT09LX0xJS0UiLCJVUkxfUkVESVJFQ1QiLCJNRU1CRVJTSElQIiwiTk9fQURTIl0sImlzRnJlZSI6ZmFsc2UsImNhblJlc2VsbGVyUHVibGlzaCI6dHJ1ZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6NDIsImNoaWxkcmVuIjpbNDRdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjozMywiYWx0ZXJuYXRpdmVDaGlsZElkIjpudWxsLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9LCIxMCI6eyJwbGFuSWQiOjEwLCJncmFkZSI6OCwibmFtZSI6IkJVU0lORVNTX1BMVVNfRUNPTU1FUkNFX1hfTEFSR0UiLCJmZWF0dXJlcyI6WyJBRERfUEFHRSIsIllPVVRVQkUiLCJQT1dFUkVEX0JZIiwiUFVTSF9OT1RJRklDQVRJT05TIiwiQ0xJRU5UUyIsIkVDT01NRVJDRV9YX0xBUkdFIiwiU0VFX0ZVTExfU1RBVFMiLCJJQ09OIiwiR09PR0xFX0NBTEVOREFSIiwiQ0xJQ0tfVE9fQ0FMTCIsIkNVU1RPTV9XSURHRVQiLCJVU0VfQ1VTVE9NX0RPTUFJTiIsIldPUkRQUkVTU19GRUVEIiwiRUNPTU1FUkNFX0xBUkdFIiwiQURWQU5DRURfRURJVE9SIiwiQ09VTlRET1dOIiwiUkVNT1ZFX0ZPT1RFUiIsIkNMSUNLX1RPX1NNUyIsIk5BVl9MSU5LUyIsIlNIQVJFIiwiQ09MTEVDVElPTlMiLCJJTlNJVEUiLCJFRElUX0JBQ0tHUk9VTkQiLCJFQ09NTUVSQ0VfTUVESVVNIiwiVFdJVFRFUiIsIkNTU19FRElUT1IiLCJPUEVOSU5HX0hPVVJTIiwiVFJVRV9MT0NBTF9SRVZJRVdTIiwiUkVTVEFVUkFOVF9NRU5VIiwiUFJFTUlVTV9JTUFHRVNfRU5BQkxFRCIsIldISVRFX0xBQkVMIiwiSElERV9QRVJfREVWSUNFIiwiQkFDS1VQUyIsIk5BVElWRV9CT09LSU5HIiwiTE9HSU5fQkFSIiwiVEFCTEUiLCJJTUFHRV9TTElERVIiLCJCRUZPUkVfQU5EX0FGVEVSIiwiRElTUVVTIiwiQ0xJQ0tfVE9fTUFQIiwiT1BFTl9UQUJMRSIsIlBBWVBBTCIsIlNJR05VUCIsIlBBU1NXT1JEX1BST1RFQ1RFRF9QQUdFUyIsIkdFT19MT0NBVElPTiIsIkhJREVfUEFHRV9QRVJfREVWSUNFIiwiRUNPTU1FUkNFX1NNQUxMIiwiVkNJVEEiLCJQT1BVUFMiLCJCTE9HIiwiTVVMVElMSU5HVUFMIiwiQ09VUE9OIiwiUkVTVEFVUkFOVF9NRU5VX1JFU1AiLCJDVVNUT01fSFRNTCIsIlNPQ0lBTF9IVUIiLCJGSUxFIiwiQ0xJQ0tfVE9fRU1BSUwiLCJOQVRJVkVfU1RPUkUiLCJZRUxQIiwiRFlOQU1JQ19QQUdFUyIsIkZBQ0VCT09LX0NPTU1FTlRTIiwiRkFDRUJPT0tfTElLRSIsIlVSTF9SRURJUkVDVCIsIk1FTUJFUlNISVAiLCJOT19BRFMiXSwiaXNGcmVlIjpmYWxzZSwiY2FuUmVzZWxsZXJQdWJsaXNoIjp0cnVlLCJ0eXBlIjoiRFVEQU9ORSIsInBhcmVudElkIjo5LCJjaGlsZHJlbiI6W10sImFsdGVybmF0aXZlUGFyZW50SWQiOjIyLCJhbHRlcm5hdGl2ZUNoaWxkSWQiOm51bGwsInRvb2x0aXBTZXR0aW5ncyI6eyJ0aXRsZSI6InVpLnVwZ3JhZGUudG9vbHRpcC50aXRsZSIsInVwZ3JhZGVzIjpbInVpLnVwZ3JhZGUudW5saW1pdGVkLmV2ZXJ5dGhpbmciLCJ1aS51cGdyYWRlLnVubGltaXRlZC4xIiwidWkudXBncmFkZS51bmxpbWl0ZWQuMiIsInVpLnVwZ3JhZGUudW5saW1pdGVkLjMiLCJ1aS51cGdyYWRlLnVubGltaXRlZC40Il19fSwiMzIiOnsicGxhbklkIjozMiwiZ3JhZGUiOjIsIm5hbWUiOiJUSUVSX0IiLCJmZWF0dXJlcyI6WyJBRERfUEFHRSIsIllPVVRVQkUiLCJQT1dFUkVEX0JZIiwiUFVTSF9OT1RJRklDQVRJT05TIiwiQ0xJRU5UUyIsIlNFRV9GVUxMX1NUQVRTIiwiSUNPTiIsIkdPT0dMRV9DQUxFTkRBUiIsIkNMSUNLX1RPX0NBTEwiLCJDVVNUT01fV0lER0VUIiwiVVNFX0NVU1RPTV9ET01BSU4iLCJXT1JEUFJFU1NfRkVFRCIsIkFEVkFOQ0VEX0VESVRPUiIsIkNPVU5URE9XTiIsIlJFTU9WRV9GT09URVIiLCJDTElDS19UT19TTVMiLCJOQVZfTElOS1MiLCJTSEFSRSIsIkNPTExFQ1RJT05TIiwiSU5TSVRFIiwiRURJVF9CQUNLR1JPVU5EIiwiVFdJVFRFUiIsIkNTU19FRElUT1IiLCJPUEVOSU5HX0hPVVJTIiwiVFJVRV9MT0NBTF9SRVZJRVdTIiwiUkVTVEFVUkFOVF9NRU5VIiwiUFJFTUlVTV9JTUFHRVNfRU5BQkxFRCIsIldISVRFX0xBQkVMIiwiSElERV9QRVJfREVWSUNFIiwiQkFDS1VQUyIsIkxPR0lOX0JBUiIsIlRBQkxFIiwiSU1BR0VfU0xJREVSIiwiQkVGT1JFX0FORF9BRlRFUiIsIkRJU1FVUyIsIkNMSUNLX1RPX01BUCIsIk9QRU5fVEFCTEUiLCJQQVlQQUwiLCJTSUdOVVAiLCJQQVNTV09SRF9QUk9URUNURURfUEFHRVMiLCJHRU9fTE9DQVRJT04iLCJISURFX1BBR0VfUEVSX0RFVklDRSIsIkVDT01NRVJDRV9TTUFMTCIsIlZDSVRBIiwiUE9QVVBTIiwiTVVMVElMSU5HVUFMIiwiQkxPRyIsIkNPVVBPTiIsIlJFU1RBVVJBTlRfTUVOVV9SRVNQIiwiQ1VTVE9NX0hUTUwiLCJTT0NJQUxfSFVCIiwiRklMRSIsIkNMSUNLX1RPX0VNQUlMIiwiTkFUSVZFX1NUT1JFIiwiWUVMUCIsIkRZTkFNSUNfUEFHRVMiLCJGQUNFQk9PS19DT01NRU5UUyIsIkZBQ0VCT09LX0xJS0UiLCJVUkxfUkVESVJFQ1QiLCJNRU1CRVJTSElQIiwiTk9fQURTIl0sImlzRnJlZSI6ZmFsc2UsImNhblJlc2VsbGVyUHVibGlzaCI6dHJ1ZSwidHlwZSI6IkRVREFPTkUiLCJwYXJlbnRJZCI6MzEsImNoaWxkcmVuIjpbMzNdLCJhbHRlcm5hdGl2ZVBhcmVudElkIjpudWxsLCJhbHRlcm5hdGl2ZUNoaWxkSWQiOjQyLCJ0b29sdGlwU2V0dGluZ3MiOm51bGx9fQ==",
        encodedPlanFeaturesMetadata: "eyIzMiI6eyJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7Im1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjIiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5zdGFydGVyIiwicHJvZHVjdHNMaW1pdCI6IjEwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJmYWxzZSIsImlzU3Vic2NyaXB0aW9uQWN0aXZlIjoiZmFsc2UiLCJ2YXJpYXRpb25zTGltaXQiOiI4IiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6ImZhbHNlIn0sIkNPTExFQ1RJT05TIjp7ImNvbGxlY3Rpb25zLmxpbWl0IjoiMjAiLCJjb2xsZWN0aW9uLnJvd3MubGltaXQiOiIyMDAwIn0sIkVDT01NRVJDRV9TTUFMTCI6eyJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4xIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNCIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkudXBncmFkZS4yMCJ9LCJDTElFTlRTIjp7ImNsaWVudHMubGltaXQiOiIzIn0sIkJMT0ciOnsicG9zdHMubGltaXQiOiItMSJ9LCJJTlNJVEUiOnsidHJpYWxfb25seSI6ImZhbHNlIn19LCIzMyI6eyJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7ImlzUHJlbWl1bUZpbHRlclNvcnRBY3RpdmUiOiJ0cnVlIiwibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMTAiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5hZHZhbmNlZCIsInByb2R1Y3RzTGltaXQiOiIxMDAwIiwiaXNEaWdpdGFsUHJvZHVjdHNFeGlzdHMiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRUYXhlc0F2YWlsYWJsZSI6InRydWUiLCJpc1N1YnNjcmlwdGlvbkFjdGl2ZSI6InRydWUiLCJ2YXJpYXRpb25zTGltaXQiOiIzMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0FjdGl2ZSI6InRydWUiLCJpc0F1dG9tYXRlZFNoaXBwaW5nQXZhaWxhYmxlIjoidHJ1ZSJ9LCJDT0xMRUNUSU9OUyI6eyJjb2xsZWN0aW9ucy5saW1pdCI6IjMwIiwiY29sbGVjdGlvbi5yb3dzLmxpbWl0IjoiMTAwMDAifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIkNMSUVOVFMiOnsiY2xpZW50cy5saW1pdCI6IjEwIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifSwiQkxPRyI6eyJwb3N0cy5saW1pdCI6Ii0xIn19LCIzNCI6eyJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7ImlzUHJlbWl1bUZpbHRlclNvcnRBY3RpdmUiOiJ0cnVlIiwibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMjUiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5lbGl0ZSIsInByb2R1Y3RzTGltaXQiOiIyMDAwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJ0cnVlIiwiaXNTdWJzY3JpcHRpb25BY3RpdmUiOiJ0cnVlIiwidmFyaWF0aW9uc0xpbWl0IjoiNDAwIiwiaXNEaWdpdGFsUHJvZHVjdHNBY3RpdmUiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6InRydWUifSwiQ09MTEVDVElPTlMiOnsiY29sbGVjdGlvbnMubGltaXQiOiI1MCIsImNvbGxlY3Rpb24ucm93cy5saW1pdCI6IjEwMDAwMCJ9LCJFQ09NTUVSQ0VfU01BTEwiOnsiZXh0ZXJuYWxQbGFuS2V5IjoiZWNvbW1lcmNlLmVjd2lkLnBsYW4uMSIsImFkZEJ1dHRvblRleHRLZXkiOiJ1aS5lY29tbWVyY2UuMTQiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnVwZ3JhZGUuMjAifSwiQ0xJRU5UUyI6eyJjbGllbnRzLmxpbWl0IjoiMjUifSwiSU5TSVRFIjp7InRyaWFsX29ubHkiOiJmYWxzZSJ9LCJCTE9HIjp7InBvc3RzLmxpbWl0IjoiLTEifX0sIjUiOnsiTkFUSVZFX0JPT0tJTkciOnsiaXNOYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImFwcG9pbnRtZW50VHlwZXNMaW1pdCI6IjUwIiwic3RhZmZNZW1iZXJzTGltaXQiOiIxIn0sIkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiUE9XRVJFRF9CWSI6eyJ0ZW1wbGF0ZSI6ImZpbGU6Ly8vZWRpdG9yL3dpZGdldFRlbXBsYXRlcy8vcG93ZXJlZEJ5L3Bvd2VyZWRCeS5mcmVlLnRtcGwuaHRtIiwicHVibGlzaGVkU2l0ZUNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciIsInRleHQzIjoiZHVkYW9uZS5wb3dlcmVkYnkuZnJlZS50ZXh0LjMiLCJ0ZXh0NCI6ImR1ZGFvbmUucG93ZXJlZGJ5LmZyZWUudGV4dC40IiwidGV4dDEiOiJkdWRhb25lLnBvd2VyZWRieS5mcmVlLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuZnJlZS50ZXh0LjIiLCJudW1iZXJPZlRleHRzIjoiNCIsImNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciBoaWRlSW5FZGl0b3IiLCJhbHdheXNIaWRlRm9yUmVzZWxsZXJzIjoidHJ1ZSJ9LCJOQVRJVkVfU1RPUkUiOnsibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMiIsImlzTGl2ZVN0b3JlIjoiZmFsc2UiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5kZW1vIiwicHJvZHVjdHNMaW1pdCI6IjEwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJmYWxzZSIsInZhcmlhdGlvbnNMaW1pdCI6IjgiLCJpc0F1dG9tYXRlZFNoaXBwaW5nQXZhaWxhYmxlIjoiZmFsc2UifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifX0sIjYiOnsiQ1VTVE9NX1dJREdFVCI6eyJhbGxvdy5hbGwuZHVkYS53aWRnZXRzIjoidHJ1ZSJ9LCJOQVRJVkVfQk9PS0lORyI6eyJpc05hdGl2ZUJvb2tpbmdBdmFpbGFibGUiOiJ0cnVlIiwiYXBwb2ludG1lbnRUeXBlc0xpbWl0IjoiNTAiLCJzdGFmZk1lbWJlcnNMaW1pdCI6IjEifSwiUE9XRVJFRF9CWSI6eyJ0ZW1wbGF0ZSI6ImZpbGU6Ly8vZWRpdG9yL3dpZGdldFRlbXBsYXRlcy8vcG93ZXJlZEJ5L3Bvd2VyZWRCeS5wcm8udG1wbC5odG0iLCJwdWJsaXNoZWRTaXRlQ2xhc3MiOiJwb3dlcmVkQnlXcmFwcGVyIiwidGV4dDMiOiJkdWRhb25lLnBvd2VyZWRieS5wcm8udGV4dC4zIiwidGV4dDEiOiJkdWRhb25lLnBvd2VyZWRieS5wcm8udGV4dC4xIiwidGV4dDIiOiJkdWRhb25lLnBvd2VyZWRieS5wcm8udGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjMiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7Im1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjIiLCJpc0xpdmVTdG9yZSI6ImZhbHNlIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5zdG9yZS51cGdyYWRlLmxpdmUuZGVtbyIsInByb2R1Y3RzTGltaXQiOiIxMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0V4aXN0cyI6InRydWUiLCJpc0F1dG9tYXRlZFRheGVzQXZhaWxhYmxlIjoiZmFsc2UiLCJ2YXJpYXRpb25zTGltaXQiOiI4IiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6ImZhbHNlIn0sIkVDT01NRVJDRV9TTUFMTCI6eyJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4xIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNCIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkudXBncmFkZS4yMCJ9LCJJTlNJVEUiOnsidHJpYWxfb25seSI6ImZhbHNlIn19LCI3Ijp7IkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiTkFUSVZFX0JPT0tJTkciOnsiaXNOYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImFwcG9pbnRtZW50VHlwZXNMaW1pdCI6IjUwIiwic3RhZmZNZW1iZXJzTGltaXQiOiIxIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7Im1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjIiLCJpc0xpdmVTdG9yZSI6ImZhbHNlIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5zdG9yZS51cGdyYWRlLmxpdmUuZGVtbyIsInByb2R1Y3RzTGltaXQiOiIxMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0V4aXN0cyI6InRydWUiLCJpc0F1dG9tYXRlZFRheGVzQXZhaWxhYmxlIjoiZmFsc2UiLCJ2YXJpYXRpb25zTGltaXQiOiI4IiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6ImZhbHNlIn0sIkVDT01NRVJDRV9TTUFMTCI6eyJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4xIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNCIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkudXBncmFkZS4yMCJ9LCJJTlNJVEUiOnsidHJpYWxfb25seSI6ImZhbHNlIn19LCI4Ijp7IkVDT01NRVJDRV9NRURJVU0iOnsicGxhbkRlc2NyaXB0aW9uIjoidWkuc3RvcmUucGxhbkRlc2NyaXB0aW9uLkVDT01NRVJDRV9NRURJVU0iLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNSIsImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjIiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE2In0sIk5BVElWRV9CT09LSU5HIjp7ImFwcG9pbnRtZW50VHlwZXNMaW1pdCI6IjUwIiwic3RhZmZNZW1iZXJzTGltaXQiOiIxIiwiaXNOYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImlzTmF0aXZlQm9va2luZ1B1Ymxpc2hpbmdBdmFpbGFibGUiOiJ0cnVlIn0sIkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiUE9XRVJFRF9CWSI6eyJ0ZW1wbGF0ZSI6ImZpbGU6Ly8vZWRpdG9yL3dpZGdldFRlbXBsYXRlcy9wb3dlcmVkQnkvcG93ZXJlZEJ5LmJ1c2luZXNzLnRtcGwuaHRtIiwicHVibGlzaGVkU2l0ZUNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciIsInRleHQxIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4xIiwidGV4dDIiOiJkdWRhb25lLnBvd2VyZWRieS5idXNpbmVzcy50ZXh0LjIiLCJudW1iZXJPZlRleHRzIjoiMiIsImNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciBoaWRlSW5FZGl0b3IiLCJhbHdheXNIaWRlRm9yUmVzZWxsZXJzIjoidHJ1ZSJ9LCJOQVRJVkVfU1RPUkUiOnsibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMiIsImlzTGl2ZVN0b3JlIjoidHJ1ZSIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkuc3RvcmUudXBncmFkZS5saXZlLnN0YXJ0ZXIiLCJwcm9kdWN0c0xpbWl0IjoiMTAwIiwiaXNEaWdpdGFsUHJvZHVjdHNFeGlzdHMiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRUYXhlc0F2YWlsYWJsZSI6ImZhbHNlIiwiaXNTdWJzY3JpcHRpb25BY3RpdmUiOiJmYWxzZSIsInZhcmlhdGlvbnNMaW1pdCI6IjgiLCJpc0F1dG9tYXRlZFNoaXBwaW5nQXZhaWxhYmxlIjoiZmFsc2UifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifX0sIjkiOnsiRUNPTU1FUkNFX01FRElVTSI6eyJwbGFuRGVzY3JpcHRpb24iOiJ1aS5zdG9yZS5wbGFuRGVzY3JpcHRpb24uRUNPTU1FUkNFX01FRElVTSIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE1IiwiZXh0ZXJuYWxQbGFuS2V5IjoiZWNvbW1lcmNlLmVjd2lkLnBsYW4uMiIsImFkZEJ1dHRvblRleHRLZXkiOiJ1aS5lY29tbWVyY2UuMTYifSwiTkFUSVZFX0JPT0tJTkciOnsiaXNQYWlkTmF0aXZlQm9va2luZ0F2YWlsYWJsZSI6InRydWUiLCJhcHBvaW50bWVudFR5cGVzTGltaXQiOiI1MCIsInN0YWZmTWVtYmVyc0xpbWl0IjoiMyIsImlzTmF0aXZlQm9va2luZ0F2YWlsYWJsZSI6InRydWUiLCJpc05hdGl2ZUJvb2tpbmdQdWJsaXNoaW5nQXZhaWxhYmxlIjoidHJ1ZSJ9LCJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIkVDT01NRVJDRV9MQVJHRSI6eyJwbGFuRGVzY3JpcHRpb24iOiJ1aS5zdG9yZS5wbGFuRGVzY3JpcHRpb24uRUNPTU1FUkNFX0xBUkdFIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5lY29tbWVyY2UuMTciLCJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4zIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xOCJ9LCJQT1dFUkVEX0JZIjp7InRlbXBsYXRlIjoiZmlsZTovLy9lZGl0b3Ivd2lkZ2V0VGVtcGxhdGVzL3Bvd2VyZWRCeS9wb3dlcmVkQnkuYnVzaW5lc3MudG1wbC5odG0iLCJwdWJsaXNoZWRTaXRlQ2xhc3MiOiJwb3dlcmVkQnlXcmFwcGVyIiwidGV4dDEiOiJkdWRhb25lLnBvd2VyZWRieS5idXNpbmVzcy50ZXh0LjEiLCJ0ZXh0MiI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMiIsIm51bWJlck9mVGV4dHMiOiIyIiwiY2xhc3MiOiJwb3dlcmVkQnlXcmFwcGVyIGhpZGVJbkVkaXRvciIsImFsd2F5c0hpZGVGb3JSZXNlbGxlcnMiOiJ0cnVlIn0sIk5BVElWRV9TVE9SRSI6eyJpc1ByZW1pdW1GaWx0ZXJTb3J0QWN0aXZlIjoidHJ1ZSIsIm1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjEwIiwiaXNMaXZlU3RvcmUiOiJ0cnVlIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5zdG9yZS51cGdyYWRlLmxpdmUuYWR2YW5jZWQiLCJwcm9kdWN0c0xpbWl0IjoiMTAwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJ0cnVlIiwiaXNTdWJzY3JpcHRpb25BY3RpdmUiOiJ0cnVlIiwidmFyaWF0aW9uc0xpbWl0IjoiMzAwIiwiaXNEaWdpdGFsUHJvZHVjdHNBY3RpdmUiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6InRydWUifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifX0sIjEwIjp7IkVDT01NRVJDRV9NRURJVU0iOnsicGxhbkRlc2NyaXB0aW9uIjoidWkuc3RvcmUucGxhbkRlc2NyaXB0aW9uLkVDT01NRVJDRV9NRURJVU0iLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNSIsImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjIiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE2In0sIk5BVElWRV9CT09LSU5HIjp7ImlzUGFpZE5hdGl2ZUJvb2tpbmdBdmFpbGFibGUiOiJ0cnVlIiwiYXBwb2ludG1lbnRUeXBlc0xpbWl0IjoiNTAiLCJzdGFmZk1lbWJlcnNMaW1pdCI6IjEwIiwiaXNOYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImlzTmF0aXZlQm9va2luZ1B1Ymxpc2hpbmdBdmFpbGFibGUiOiJ0cnVlIn0sIkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiRUNPTU1FUkNFX0xBUkdFIjp7InBsYW5EZXNjcmlwdGlvbiI6InVpLnN0b3JlLnBsYW5EZXNjcmlwdGlvbi5FQ09NTUVSQ0VfTEFSR0UiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNyIsImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjMiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE4In0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7ImlzUHJlbWl1bUZpbHRlclNvcnRBY3RpdmUiOiJ0cnVlIiwibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMjUiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5lbGl0ZSIsInByb2R1Y3RzTGltaXQiOiIyMDAwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJ0cnVlIiwiaXNTdWJzY3JpcHRpb25BY3RpdmUiOiJ0cnVlIiwidmFyaWF0aW9uc0xpbWl0IjoiNDAwIiwiaXNEaWdpdGFsUHJvZHVjdHNBY3RpdmUiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6InRydWUifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIkVDT01NRVJDRV9YX0xBUkdFIjp7InBsYW5EZXNjcmlwdGlvbiI6InVpLnN0b3JlLnBsYW5EZXNjcmlwdGlvbi5FQ09NTUVSQ0VfWF9MQVJHRSIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkuZGlyZWN0LnVwZ3JhZGUudG8ueGxhcmdlLm1lc3NhZ2UiLCJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi40IiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmRpcmVjdC5hZGQueGxhcmdlLnN0b3JlIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifX0sIjQyIjp7IkVDT01NRVJDRV9NRURJVU0iOnsicGxhbkRlc2NyaXB0aW9uIjoidWkuc3RvcmUucGxhbkRlc2NyaXB0aW9uLkVDT01NRVJDRV9NRURJVU0iLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNSIsImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjIiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE2In0sIkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiUE9XRVJFRF9CWSI6eyJ0ZW1wbGF0ZSI6ImZpbGU6Ly8vZWRpdG9yL3dpZGdldFRlbXBsYXRlcy9wb3dlcmVkQnkvcG93ZXJlZEJ5LmJ1c2luZXNzLnRtcGwuaHRtIiwicHVibGlzaGVkU2l0ZUNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciIsInRleHQxIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4xIiwidGV4dDIiOiJkdWRhb25lLnBvd2VyZWRieS5idXNpbmVzcy50ZXh0LjIiLCJudW1iZXJPZlRleHRzIjoiMiIsImNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciBoaWRlSW5FZGl0b3IiLCJhbHdheXNIaWRlRm9yUmVzZWxsZXJzIjoidHJ1ZSJ9LCJOQVRJVkVfU1RPUkUiOnsibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMiIsImlzTGl2ZVN0b3JlIjoidHJ1ZSIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkuc3RvcmUudXBncmFkZS5saXZlLnN0YXJ0ZXIiLCJwcm9kdWN0c0xpbWl0IjoiMTAwIiwiaXNEaWdpdGFsUHJvZHVjdHNFeGlzdHMiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRUYXhlc0F2YWlsYWJsZSI6ImZhbHNlIiwiaXNTdWJzY3JpcHRpb25BY3RpdmUiOiJmYWxzZSIsInZhcmlhdGlvbnNMaW1pdCI6IjgiLCJpc0F1dG9tYXRlZFNoaXBwaW5nQXZhaWxhYmxlIjoiZmFsc2UifSwiQ09MTEVDVElPTlMiOnsiY29sbGVjdGlvbnMubGltaXQiOiIyMCIsImNvbGxlY3Rpb24ucm93cy5saW1pdCI6IjIwMDAifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIkNMSUVOVFMiOnsiY2xpZW50cy5saW1pdCI6IjMifSwiSU5TSVRFIjp7InRyaWFsX29ubHkiOiJmYWxzZSJ9LCJCTE9HIjp7InBvc3RzLmxpbWl0IjoiLTEifX0sIjQzIjp7IkVDT01NRVJDRV9NRURJVU0iOnsicGxhbkRlc2NyaXB0aW9uIjoidWkuc3RvcmUucGxhbkRlc2NyaXB0aW9uLkVDT01NRVJDRV9NRURJVU0iLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNSIsImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjIiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE2In0sIkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiRUNPTU1FUkNFX0xBUkdFIjp7InBsYW5EZXNjcmlwdGlvbiI6InVpLnN0b3JlLnBsYW5EZXNjcmlwdGlvbi5FQ09NTUVSQ0VfTEFSR0UiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNyIsImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjMiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE4In0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7ImlzUHJlbWl1bUZpbHRlclNvcnRBY3RpdmUiOiJ0cnVlIiwibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMTAiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5hZHZhbmNlZCIsInByb2R1Y3RzTGltaXQiOiIxMDAwIiwiaXNEaWdpdGFsUHJvZHVjdHNFeGlzdHMiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRUYXhlc0F2YWlsYWJsZSI6InRydWUiLCJpc1N1YnNjcmlwdGlvbkFjdGl2ZSI6InRydWUiLCJ2YXJpYXRpb25zTGltaXQiOiIzMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0FjdGl2ZSI6InRydWUiLCJpc0F1dG9tYXRlZFNoaXBwaW5nQXZhaWxhYmxlIjoidHJ1ZSJ9LCJDT0xMRUNUSU9OUyI6eyJjb2xsZWN0aW9ucy5saW1pdCI6IjMwIiwiY29sbGVjdGlvbi5yb3dzLmxpbWl0IjoiMTAwMDAifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIkNMSUVOVFMiOnsiY2xpZW50cy5saW1pdCI6IjEwIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifSwiQkxPRyI6eyJwb3N0cy5saW1pdCI6Ii0xIn19LCI0NCI6eyJFQ09NTUVSQ0VfTUVESVVNIjp7InBsYW5EZXNjcmlwdGlvbiI6InVpLnN0b3JlLnBsYW5EZXNjcmlwdGlvbi5FQ09NTUVSQ0VfTUVESVVNIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5lY29tbWVyY2UuMTUiLCJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4yIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNiJ9LCJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIkVDT01NRVJDRV9MQVJHRSI6eyJwbGFuRGVzY3JpcHRpb24iOiJ1aS5zdG9yZS5wbGFuRGVzY3JpcHRpb24uRUNPTU1FUkNFX0xBUkdFIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5lY29tbWVyY2UuMTciLCJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4zIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xOCJ9LCJQT1dFUkVEX0JZIjp7InRlbXBsYXRlIjoiZmlsZTovLy9lZGl0b3Ivd2lkZ2V0VGVtcGxhdGVzL3Bvd2VyZWRCeS9wb3dlcmVkQnkuYnVzaW5lc3MudG1wbC5odG0iLCJwdWJsaXNoZWRTaXRlQ2xhc3MiOiJwb3dlcmVkQnlXcmFwcGVyIiwidGV4dDEiOiJkdWRhb25lLnBvd2VyZWRieS5idXNpbmVzcy50ZXh0LjEiLCJ0ZXh0MiI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMiIsIm51bWJlck9mVGV4dHMiOiIyIiwiY2xhc3MiOiJwb3dlcmVkQnlXcmFwcGVyIGhpZGVJbkVkaXRvciIsImFsd2F5c0hpZGVGb3JSZXNlbGxlcnMiOiJ0cnVlIn0sIk5BVElWRV9TVE9SRSI6eyJpc1ByZW1pdW1GaWx0ZXJTb3J0QWN0aXZlIjoidHJ1ZSIsIm1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjI1IiwiaXNMaXZlU3RvcmUiOiJ0cnVlIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5zdG9yZS51cGdyYWRlLmxpdmUuZWxpdGUiLCJwcm9kdWN0c0xpbWl0IjoiMjAwMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0V4aXN0cyI6InRydWUiLCJpc0F1dG9tYXRlZFRheGVzQXZhaWxhYmxlIjoidHJ1ZSIsImlzU3Vic2NyaXB0aW9uQWN0aXZlIjoidHJ1ZSIsInZhcmlhdGlvbnNMaW1pdCI6IjQwMCIsImlzRGlnaXRhbFByb2R1Y3RzQWN0aXZlIjoidHJ1ZSIsImlzQXV0b21hdGVkU2hpcHBpbmdBdmFpbGFibGUiOiJ0cnVlIn0sIkNPTExFQ1RJT05TIjp7ImNvbGxlY3Rpb25zLmxpbWl0IjoiNTAiLCJjb2xsZWN0aW9uLnJvd3MubGltaXQiOiIxMDAwMDAifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIkNMSUVOVFMiOnsiY2xpZW50cy5saW1pdCI6IjI1In0sIkVDT01NRVJDRV9YX0xBUkdFIjp7InBsYW5EZXNjcmlwdGlvbiI6InVpLnN0b3JlLnBsYW5EZXNjcmlwdGlvbi5FQ09NTUVSQ0VfWF9MQVJHRSIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkuZGlyZWN0LnVwZ3JhZGUudG8ueGxhcmdlLm1lc3NhZ2UiLCJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi40IiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmRpcmVjdC5hZGQueGxhcmdlLnN0b3JlIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifSwiQkxPRyI6eyJwb3N0cy5saW1pdCI6Ii0xIn19LCIyMCI6eyJOQVRJVkVfQk9PS0lORyI6eyJhcHBvaW50bWVudFR5cGVzTGltaXQiOiI1MCIsInN0YWZmTWVtYmVyc0xpbWl0IjoiMSIsImlzTmF0aXZlQm9va2luZ0F2YWlsYWJsZSI6InRydWUiLCJpc05hdGl2ZUJvb2tpbmdQdWJsaXNoaW5nQXZhaWxhYmxlIjoidHJ1ZSJ9LCJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7Im1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjIiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5zdGFydGVyIiwicHJvZHVjdHNMaW1pdCI6IjEwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJmYWxzZSIsImlzU3Vic2NyaXB0aW9uQWN0aXZlIjoiZmFsc2UiLCJ2YXJpYXRpb25zTGltaXQiOiI4IiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6ImZhbHNlIn0sIkVDT01NRVJDRV9TTUFMTCI6eyJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4xIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNCIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkudXBncmFkZS4yMCJ9LCJJTlNJVEUiOnsidHJpYWxfb25seSI6ImZhbHNlIn19LCIyMSI6eyJOQVRJVkVfQk9PS0lORyI6eyJpc1BhaWROYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImFwcG9pbnRtZW50VHlwZXNMaW1pdCI6IjUwIiwic3RhZmZNZW1iZXJzTGltaXQiOiIzIiwiaXNOYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImlzTmF0aXZlQm9va2luZ1B1Ymxpc2hpbmdBdmFpbGFibGUiOiJ0cnVlIn0sIkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiUE9XRVJFRF9CWSI6eyJ0ZW1wbGF0ZSI6ImZpbGU6Ly8vZWRpdG9yL3dpZGdldFRlbXBsYXRlcy9wb3dlcmVkQnkvcG93ZXJlZEJ5LmJ1c2luZXNzLnRtcGwuaHRtIiwicHVibGlzaGVkU2l0ZUNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciIsInRleHQxIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4xIiwidGV4dDIiOiJkdWRhb25lLnBvd2VyZWRieS5idXNpbmVzcy50ZXh0LjIiLCJudW1iZXJPZlRleHRzIjoiMiIsImNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciBoaWRlSW5FZGl0b3IiLCJhbHdheXNIaWRlRm9yUmVzZWxsZXJzIjoidHJ1ZSJ9LCJOQVRJVkVfU1RPUkUiOnsiaXNQcmVtaXVtRmlsdGVyU29ydEFjdGl2ZSI6InRydWUiLCJtYXhDdXN0b21pemF0aW9uc1BlckNhdGFsb2ciOiIxMCIsImlzTGl2ZVN0b3JlIjoidHJ1ZSIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkuc3RvcmUudXBncmFkZS5saXZlLmFkdmFuY2VkIiwicHJvZHVjdHNMaW1pdCI6IjEwMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0V4aXN0cyI6InRydWUiLCJpc0F1dG9tYXRlZFRheGVzQXZhaWxhYmxlIjoidHJ1ZSIsImlzU3Vic2NyaXB0aW9uQWN0aXZlIjoidHJ1ZSIsInZhcmlhdGlvbnNMaW1pdCI6IjMwMCIsImlzRGlnaXRhbFByb2R1Y3RzQWN0aXZlIjoidHJ1ZSIsImlzQXV0b21hdGVkU2hpcHBpbmdBdmFpbGFibGUiOiJ0cnVlIn0sIkVDT01NRVJDRV9TTUFMTCI6eyJleHRlcm5hbFBsYW5LZXkiOiJlY29tbWVyY2UuZWN3aWQucGxhbi4xIiwiYWRkQnV0dG9uVGV4dEtleSI6InVpLmVjb21tZXJjZS4xNCIsInVwZ3JhZGVCdXR0b25UZXh0S2V5IjoidWkudXBncmFkZS4yMCJ9LCJJTlNJVEUiOnsidHJpYWxfb25seSI6ImZhbHNlIn19LCIyMiI6eyJOQVRJVkVfQk9PS0lORyI6eyJpc1BhaWROYXRpdmVCb29raW5nQXZhaWxhYmxlIjoidHJ1ZSIsImFwcG9pbnRtZW50VHlwZXNMaW1pdCI6IjUwIiwic3RhZmZNZW1iZXJzTGltaXQiOiIxMCIsImlzTmF0aXZlQm9va2luZ0F2YWlsYWJsZSI6InRydWUiLCJpc05hdGl2ZUJvb2tpbmdQdWJsaXNoaW5nQXZhaWxhYmxlIjoidHJ1ZSJ9LCJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7ImlzUHJlbWl1bUZpbHRlclNvcnRBY3RpdmUiOiJ0cnVlIiwibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMjUiLCJpc0xpdmVTdG9yZSI6InRydWUiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5lbGl0ZSIsInByb2R1Y3RzTGltaXQiOiIyMDAwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJ0cnVlIiwiaXNTdWJzY3JpcHRpb25BY3RpdmUiOiJ0cnVlIiwidmFyaWF0aW9uc0xpbWl0IjoiNDAwIiwiaXNEaWdpdGFsUHJvZHVjdHNBY3RpdmUiOiJ0cnVlIiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6InRydWUifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifX0sIjMwIjp7IkNVU1RPTV9XSURHRVQiOnsiYWxsb3cuYWxsLmR1ZGEud2lkZ2V0cyI6InRydWUifSwiUE9XRVJFRF9CWSI6eyJ0ZW1wbGF0ZSI6ImZpbGU6Ly8vZWRpdG9yL3dpZGdldFRlbXBsYXRlcy8vcG93ZXJlZEJ5L3Bvd2VyZWRCeS5mcmVlLnRtcGwuaHRtIiwicHVibGlzaGVkU2l0ZUNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciIsInRleHQzIjoiZHVkYW9uZS5wb3dlcmVkYnkuZnJlZS50ZXh0LjMiLCJ0ZXh0NCI6ImR1ZGFvbmUucG93ZXJlZGJ5LmZyZWUudGV4dC40IiwidGV4dDEiOiJkdWRhb25lLnBvd2VyZWRieS5mcmVlLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuZnJlZS50ZXh0LjIiLCJudW1iZXJPZlRleHRzIjoiNCIsImNsYXNzIjoicG93ZXJlZEJ5V3JhcHBlciBoaWRlSW5FZGl0b3IiLCJhbHdheXNIaWRlRm9yUmVzZWxsZXJzIjoidHJ1ZSJ9LCJOQVRJVkVfU1RPUkUiOnsibWF4Q3VzdG9taXphdGlvbnNQZXJDYXRhbG9nIjoiMiIsImlzTGl2ZVN0b3JlIjoiZmFsc2UiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnN0b3JlLnVwZ3JhZGUubGl2ZS5kZW1vIiwicHJvZHVjdHNMaW1pdCI6IjEwMCIsImlzRGlnaXRhbFByb2R1Y3RzRXhpc3RzIjoidHJ1ZSIsImlzQXV0b21hdGVkVGF4ZXNBdmFpbGFibGUiOiJmYWxzZSIsInZhcmlhdGlvbnNMaW1pdCI6IjgiLCJpc0F1dG9tYXRlZFNoaXBwaW5nQXZhaWxhYmxlIjoiZmFsc2UifSwiRUNPTU1FUkNFX1NNQUxMIjp7ImV4dGVybmFsUGxhbktleSI6ImVjb21tZXJjZS5lY3dpZC5wbGFuLjEiLCJhZGRCdXR0b25UZXh0S2V5IjoidWkuZWNvbW1lcmNlLjE0IiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS51cGdyYWRlLjIwIn0sIkNPTExFQ1RJT05TIjp7ImNvbGxlY3Rpb25zLmxpbWl0IjoiMSIsImNvbGxlY3Rpb24ucm93cy5saW1pdCI6IjEwMCJ9LCJDTElFTlRTIjp7ImNsaWVudHMubGltaXQiOiIxIn0sIklOU0lURSI6eyJ0cmlhbF9vbmx5IjoiZmFsc2UifSwiQkxPRyI6eyJwb3N0cy5saW1pdCI6IjIwIn19LCIzMSI6eyJDVVNUT01fV0lER0VUIjp7ImFsbG93LmFsbC5kdWRhLndpZGdldHMiOiJ0cnVlIn0sIlBPV0VSRURfQlkiOnsidGVtcGxhdGUiOiJmaWxlOi8vL2VkaXRvci93aWRnZXRUZW1wbGF0ZXMvcG93ZXJlZEJ5L3Bvd2VyZWRCeS5idXNpbmVzcy50bXBsLmh0bSIsInB1Ymxpc2hlZFNpdGVDbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIiLCJ0ZXh0MSI6ImR1ZGFvbmUucG93ZXJlZGJ5LmJ1c2luZXNzLnRleHQuMSIsInRleHQyIjoiZHVkYW9uZS5wb3dlcmVkYnkuYnVzaW5lc3MudGV4dC4yIiwibnVtYmVyT2ZUZXh0cyI6IjIiLCJjbGFzcyI6InBvd2VyZWRCeVdyYXBwZXIgaGlkZUluRWRpdG9yIiwiYWx3YXlzSGlkZUZvclJlc2VsbGVycyI6InRydWUifSwiTkFUSVZFX1NUT1JFIjp7Im1heEN1c3RvbWl6YXRpb25zUGVyQ2F0YWxvZyI6IjIiLCJpc0xpdmVTdG9yZSI6ImZhbHNlIiwidXBncmFkZUJ1dHRvblRleHRLZXkiOiJ1aS5zdG9yZS51cGdyYWRlLmxpdmUuZGVtbyIsInByb2R1Y3RzTGltaXQiOiIxMDAiLCJpc0RpZ2l0YWxQcm9kdWN0c0V4aXN0cyI6InRydWUiLCJpc0F1dG9tYXRlZFRheGVzQXZhaWxhYmxlIjoiZmFsc2UiLCJ2YXJpYXRpb25zTGltaXQiOiI4IiwiaXNBdXRvbWF0ZWRTaGlwcGluZ0F2YWlsYWJsZSI6ImZhbHNlIn0sIkNPTExFQ1RJT05TIjp7ImNvbGxlY3Rpb25zLmxpbWl0IjoiMSIsImNvbGxlY3Rpb24ucm93cy5saW1pdCI6IjEwMCJ9LCJFQ09NTUVSQ0VfU01BTEwiOnsiZXh0ZXJuYWxQbGFuS2V5IjoiZWNvbW1lcmNlLmVjd2lkLnBsYW4uMSIsImFkZEJ1dHRvblRleHRLZXkiOiJ1aS5lY29tbWVyY2UuMTQiLCJ1cGdyYWRlQnV0dG9uVGV4dEtleSI6InVpLnVwZ3JhZGUuMjAifSwiQ0xJRU5UUyI6eyJjbGllbnRzLmxpbWl0IjoiMSJ9LCJJTlNJVEUiOnsidHJpYWxfb25seSI6ImZhbHNlIn0sIkJMT0ciOnsicG9zdHMubGltaXQiOiIyMCJ9fX0="
    };
</script>
<script type="text/javascript">

    function loadCSS(link) {
        try {
            var urlParams = new URLSearchParams(window.location.search);
            var noCSS = !!urlParams.get('nocss');
            var cssTimeout = urlParams.get('cssTimeout') || 0;

            if (noCSS) {
                return;
            }
            requestIdleCallback(function () {
                window.setTimeout(function () {
                    link.onload = null;
                    link.rel = 'stylesheet';
                    link.type = 'text/css'
                }, parseInt(cssTimeout, 10));
            });
        } catch (e) {/* Never fail - this is just a tool for measurements */
        }
    }

    if (window.initUIPerms) {
        window.initUIPerms('eyJEQVNIQk9BUkRfUExBTl9DT0xVTU4iOmZhbHNlLCJTQVZFX0FTX1RFTVBMQVRFIjpmYWxzZSwiU1RBVFNfRU1BSUxfU0VMRl9TVUJTQ1JJQkUiOmZhbHNlLCJDUkVBVEVfU0lURSI6ZmFsc2UsIlBBUlRORVJfUE9SVEFMIjpmYWxzZSwiU0lURV9UWVBFX0RBU0hCT0FSRF9JTkRJQ0FUT1IiOmZhbHNlLCJXUiI6ZmFsc2UsIkFQSSI6ZmFsc2UsIkRFTEVURV9TSVRFIjpmYWxzZSwiTUFOQUdFX1NUQUZGIjpmYWxzZSwiTU9CSUxFX0JGUyI6ZmFsc2UsIkFDVElWSVRZX0xPRyI6ZmFsc2UsIkVESVRfQlJBTkRJTkciOmZhbHNlLCJNQU5BR0VfQVBQIjpmYWxzZSwiRF9BV0FSRSI6ZmFsc2UsIkZJTFRFUl9BTkRfVEFHIjpmYWxzZSwiQUNDT1VOVF9TRVRUSU5HUyI6ZmFsc2UsIlNJVEVfUEFZTUVOVFMiOmZhbHNlLCJTSE9XX0hFTFAiOnRydWUsIk1BTkFHRV9DQVRFR09SWSI6ZmFsc2UsIkVESVRPUl9DVVNUT01fRE9NQUlOIjpmYWxzZSwiV0lER0VUU19CVUlMREVSX1RPT0wiOmZhbHNlLCJDUkVBVEVfRkxFWF9TSVRFUyI6ZmFsc2UsIkNPTU1VTklDQVRJT04iOmZhbHNlLCJNQU5BR0VfQ1VTVE9NRVJTIjpmYWxzZSwiUEFZTUVOVFMiOmZhbHNlfQ==');
    }
    window.accountPlans = "W3sidHlwZSI6IkNVU1RPTV9MSVRFX1BMVVMiLCJmZWF0dXJlcyI6WyJHb29nbGVTcGVlZE9wdGltaXphdGlvbiIsIlByZW1pdW1JbWFnZXMiLCJEZXZNb2RlQWNjZXNzIiwiTXVsdGlMYW5ndWFnZSIsIlVubGltaXRlZExhbmRpbmdQYWdlcyIsIlNtYWxsUHJvZHVjdFN0b3JlIiwiV0xDbGllbnRBY2Nlc3MiLCJXTFNhbGVzTWFya2V0aW5nTWF0ZXJpYWwiLCJDb25maWd1cmFibGVQcmljZVBsYW5zIiwiUm9sZXNBbmRQZXJtaXNzaW9ucyIsIkNsaWVudFN0YXRzQW5kQW5hbHl0aWNzIiwiVGVhbUFzc2V0c1NoYXJpbmciLCJQcm9GdWxmaWxsbWVudENoYW5uZWwiLCJGcmVlU2l0ZVNTTCIsIlNpdGVCYWNrdXAiLCJTaXRlRXhwb3J0IiwiQVBJQWNjZXNzIiwiV2lkZ2V0QnVpbGRlciIsIkRhdGFCaW5kaW5nIiwiRHluYW1pY1BhZ2VzIiwiU2l0ZUFubm90YXRpb25zIiwiQ29udGVudENvbGxlY3Rpb25Gb3JtIiwiWmVuZGVzay1UYWxrLVdlZWtkYXkiLCJaZW5kZXNrLVRhbGstV2Vla2VuZCIsIlplbmRlc2stQ2hhdC1XZWVrZGF5IiwiWmVuZGVzay1DaGF0LVdlZWtlbmQiLCJaZW5kZXNrLUNvbnRhY3RGb3JtIiwiSW1hZ2VDb2xsZWN0aW9ucyIsIkludGVybmFsQ29sbGVjdGlvbnMiLCJFeHRlcm5hbEludGVncmF0aW9uQ29sbGVjdGlvbnMiLCJFeHRlcm5hbENvbGxlY3Rpb25zIiwiTG9jYWxCdXNpbmVzc1NjaGVtYSIsIlB1Ymxpc2hQYWdlIiwiQ3VzdG9tRW1haWxEb21haW4iLCJDbGllbnRCaWxsaW5nIiwiQ3VzdG9tV0xEb21haW4iLCJaYXBpZXJCbG9nIiwiWmFwaWVyQ29tbWVudHMiLCJaYXBpZXJGb3JtIiwiWmFwaWVyU3RvcmUiLCJaYXBpZXJOYXRpdmVTdG9yZSIsIlphcGllck1lbWJlcnNoaXAiLCJaYXBpZXJGb3JtQ29udGVudExpYnJhcnkiLCJaYXBpZXJDb2xsZWN0aW9ucyIsIlphcGllckNyZWF0ZVNpdGUiLCJaYXBpZXJDcmVhdGVDbGllbnQiLCJDdXN0b21CcmFuZGluZyIsIjJmYUZvck93bmVyIiwiMmZhRm9yU3RhZmYiLCJHb29nbGVCdXNpbmVzc1Byb2ZpbGVTeW5jIiwiQUlBZHZhbmNlZENvbnRlbnRHZW5lcmF0aW9uIiwiQUlQYWdlc0FuZFNlY3Rpb25zQ29udGVudEdlbmVyYXRpb24iLCJVbmxpbWl0ZWRDbGllbnRzV2l0aFNpdGVBbm5vdGF0aW9ucyIsIk1jcEJhc2ljIiwiQ3VzdG9tQXNzZXRzVGVtcGxhdGVzIiwiQ3VzdG9tQXNzZXRzU2VjdGlvbnMiXSwibnVtT2ZGcmVlU2l0ZXMiOjQsIm51bU9mU3RhZmZVc2VycyI6MjUsImdyYWRlIjo5LCJzaXRlQ29udHJhY3RzIjpbeyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxMS4wLCJwcmljZU5vVGF4IjoxMS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA0NiIsInByaWNlVG90YWwiOjExLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDQ2IiwicHJpY2VUb0Rpc3BsYXkiOiIxMSIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjI1JSIsInByaWNlIjoxMDguMCwicHJpY2VOb1RheCI6MTA4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNDciLCJwcmljZVRvdGFsIjoxMDguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjkwNDciLCJwcmljZVRvRGlzcGxheSI6IjkiLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTkuMCwicHJpY2VOb1RheCI6MTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA0OCIsInByaWNlVG90YWwiOjE5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDQ4IiwicHJpY2VUb0Rpc3BsYXkiOiIxOSIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE3JSIsInByaWNlIjoxOTIuMCwicHJpY2VOb1RheCI6MTkyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA0OSIsInByaWNlVG90YWwiOjE5Mi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA0OSIsInByaWNlVG9EaXNwbGF5IjoiMTYiLCJwbGFuSWQiOjh9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MzMuMCwicHJpY2VOb1RheCI6MzMuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA1MiIsInByaWNlVG90YWwiOjMzLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDUyIiwicHJpY2VUb0Rpc3BsYXkiOiIzMyIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE1JSIsInByaWNlIjozNDguMCwicHJpY2VOb1RheCI6MzQ4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA1MyIsInByaWNlVG90YWwiOjM0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA1MyIsInByaWNlVG9EaXNwbGF5IjoiMjkiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NjMuMCwicHJpY2VOb1RheCI6NjMuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgVW5saW1pdGVkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNTYiLCJwcmljZVRvdGFsIjo2My4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA1NiIsInByaWNlVG9EaXNwbGF5IjoiNjMiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjElIiwicHJpY2UiOjY0OC4wLCJwcmljZU5vVGF4Ijo2NDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBVbmxpbWl0ZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA1NyIsInByaWNlVG90YWwiOjY0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA1NyIsInByaWNlVG9EaXNwbGF5IjoiNTQiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE5LjAsInByaWNlTm9UYXgiOjE5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNjAiLCJwcmljZVRvdGFsIjoxOS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA2MCIsInByaWNlVG9EaXNwbGF5IjoiMTkiLCJwbGFuSWQiOjIwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTclIiwicHJpY2UiOjE5Mi4wLCJwcmljZU5vVGF4IjoxOTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDYxIiwicHJpY2VUb3RhbCI6MTkyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDYxIiwicHJpY2VUb0Rpc3BsYXkiOiIxNiIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MzMuMCwicHJpY2VOb1RheCI6MzMuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA2NCIsInByaWNlVG90YWwiOjMzLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDY0IiwicHJpY2VUb0Rpc3BsYXkiOiIzMyIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxNyUiLCJwcmljZSI6MzQ4LjAsInByaWNlTm9UYXgiOjM0OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNjUiLCJwcmljZVRvdGFsIjozNDguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjkwNjUiLCJwcmljZVRvRGlzcGxheSI6IjI5IiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo2My4wLCJwcmljZU5vVGF4Ijo2My4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDY4IiwicHJpY2VUb3RhbCI6NjMuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjkwNjgiLCJwcmljZVRvRGlzcGxheSI6IjYzIiwicGxhbklkIjoyMn0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIxJSIsInByaWNlIjo2NDguMCwicHJpY2VOb1RheCI6NjQ4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA2OSIsInByaWNlVG90YWwiOjY0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA2OSIsInByaWNlVG9EaXNwbGF5IjoiNTQiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjI5OS4wLCJwcmljZU5vVGF4IjoyOTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDA3IiwicHJpY2VUb3RhbCI6Mjk5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDA3IiwicHJpY2VUb0Rpc3BsYXkiOiIyOTkiLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6OC4wLCJwcmljZU5vVGF4Ijo4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFN0YW5kYXJkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDUwIiwicHJpY2VUb3RhbCI6OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA1MCIsInByaWNlVG9EaXNwbGF5IjoiOCIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjg0LjAsInByaWNlTm9UYXgiOjg0LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgU3RhbmRhcmQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNTEiLCJwcmljZVRvdGFsIjo4NC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA1MSIsInByaWNlVG9EaXNwbGF5IjoiNyIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyMi4wLCJwcmljZU5vVGF4IjoyMi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBBZHZhbmNlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA1NCIsInByaWNlVG90YWwiOjIyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDU0IiwicHJpY2VUb0Rpc3BsYXkiOiIyMiIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjEyJSIsInByaWNlIjoyNDAuMCwicHJpY2VOb1RheCI6MjQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgQWR2YW5jZWQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNTUiLCJwcmljZVRvdGFsIjoyNDAuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjkwNTUiLCJwcmljZVRvRGlzcGxheSI6IjIwIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjUyLjAsInByaWNlTm9UYXgiOjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFVubGltaXRlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA1OCIsInByaWNlVG90YWwiOjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDU4IiwicHJpY2VUb0Rpc3BsYXkiOiI1MiIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMCUiLCJwcmljZSI6NTQwLjAsInByaWNlTm9UYXgiOjU0MC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFVubGltaXRlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA1OSIsInByaWNlVG90YWwiOjU0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA1OSIsInByaWNlVG9EaXNwbGF5IjoiNDUiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjguMCwicHJpY2VOb1RheCI6OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDYyIiwicHJpY2VUb3RhbCI6OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA2MiIsInByaWNlVG9EaXNwbGF5IjoiOCIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjo4NC4wLCJwcmljZU5vVGF4Ijo4NC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNjMiLCJwcmljZVRvdGFsIjo4NC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA2MyIsInByaWNlVG9EaXNwbGF5IjoiNyIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MjIuMCwicHJpY2VOb1RheCI6MjIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA2NiIsInByaWNlVG90YWwiOjIyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDY2IiwicHJpY2VUb0Rpc3BsYXkiOiIyMiIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjoyNDAuMCwicHJpY2VOb1RheCI6MjQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA2NyIsInByaWNlVG90YWwiOjI0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA2NyIsInByaWNlVG9EaXNwbGF5IjoiMjAiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjUyLjAsInByaWNlTm9UYXgiOjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjkwNzAiLCJwcmljZVRvdGFsIjo1Mi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyOTA3MCIsInByaWNlVG9EaXNwbGF5IjoiNTIiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjU0MC4wLCJwcmljZU5vVGF4Ijo1NDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDcxIiwicHJpY2VUb3RhbCI6NTQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDcxIiwicHJpY2VUb0Rpc3BsYXkiOiI0NSIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTU5LjAsInByaWNlTm9UYXgiOjE1OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBDdXN0b20gTGl0ZSBQbHVzIFNpdGUgRm9yIExpZmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA1OTAwMyIsInByaWNlVG90YWwiOjE1OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA1OTAwMyIsInByaWNlVG9EaXNwbGF5IjoiMTU5IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjExLjAsInByaWNlTm9UYXgiOjExLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEN1c3RvbSBMaXRlIFBsdXMgTW9udGhseSBTaXRlIFBsYW4iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyOTA3MiIsInByaWNlVG90YWwiOjExLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDcyIiwicHJpY2VUb0Rpc3BsYXkiOiIxMSIsInBsYW5JZCI6M30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjI1JSIsInByaWNlIjoxMDguMCwicHJpY2VOb1RheCI6MTA4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEN1c3RvbSBMaXRlIFBsdXMgWWVhcmx5IFNpdGUgUGxhbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI5MDczIiwicHJpY2VUb3RhbCI6MTA4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI5MDczIiwicHJpY2VUb0Rpc3BsYXkiOiI5IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE1OS4wLCJwcmljZU5vVGF4IjoxNTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiRG0gQ3VzdG9tIExpdGUgUGx1cyBTaXRlIEZvciBMaWZlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNTkwMDMiLCJwcmljZVRvdGFsIjoxNTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNTkwMDMiLCJwcmljZVRvRGlzcGxheSI6IjE1OSIsInBsYW5JZCI6M31dLCJudW1Bbm5vdGF0aW9uc1RvdGFsQ3VzdG9tZXJzTGltaXQiOjEwMCwibnVtT2ZJbnRlcm5hbENvbGxlY3Rpb25zIjoxMDAsIm51bU9mSW50ZXJuYWxDb2xsZWN0aW9uUm93cyI6NTAwLCJtYXhBbGxvd2VkUHVibGlzaGVkV2lkZ2V0cyI6bnVsbCwibWF4QWxsb3dlZEN1c3RvbVRlbXBsYXRlcyI6bnVsbCwibWF4QWxsb3dlZEN1c3RvbVNlY3Rpb25zIjpudWxsLCJzZWxmU2VydmljZVBsYW4iOmZhbHNlfSx7InR5cGUiOiJDVVNUT01fTElURSIsImZlYXR1cmVzIjpbIkdvb2dsZVNwZWVkT3B0aW1pemF0aW9uIiwiUHJlbWl1bUltYWdlcyIsIkRldk1vZGVBY2Nlc3MiLCJNdWx0aUxhbmd1YWdlIiwiVW5saW1pdGVkTGFuZGluZ1BhZ2VzIiwiU21hbGxQcm9kdWN0U3RvcmUiLCJXTENsaWVudEFjY2VzcyIsIldMU2FsZXNNYXJrZXRpbmdNYXRlcmlhbCIsIkNvbmZpZ3VyYWJsZVByaWNlUGxhbnMiLCJSb2xlc0FuZFBlcm1pc3Npb25zIiwiQ2xpZW50U3RhdHNBbmRBbmFseXRpY3MiLCJUZWFtQXNzZXRzU2hhcmluZyIsIlByb0Z1bGZpbGxtZW50Q2hhbm5lbCIsIkZyZWVTaXRlU1NMIiwiU2l0ZUJhY2t1cCIsIlNpdGVFeHBvcnQiLCJBUElBY2Nlc3MiLCJXaWRnZXRCdWlsZGVyIiwiRGF0YUJpbmRpbmciLCJEeW5hbWljUGFnZXMiLCJTaXRlQW5ub3RhdGlvbnMiLCJDb250ZW50Q29sbGVjdGlvbkZvcm0iLCJaZW5kZXNrLVRhbGstV2Vla2RheSIsIlplbmRlc2stVGFsay1XZWVrZW5kIiwiWmVuZGVzay1DaGF0LVdlZWtkYXkiLCJaZW5kZXNrLUNoYXQtV2Vla2VuZCIsIlplbmRlc2stQ29udGFjdEZvcm0iLCJJbWFnZUNvbGxlY3Rpb25zIiwiSW50ZXJuYWxDb2xsZWN0aW9ucyIsIkV4dGVybmFsSW50ZWdyYXRpb25Db2xsZWN0aW9ucyIsIkV4dGVybmFsQ29sbGVjdGlvbnMiLCJMb2NhbEJ1c2luZXNzU2NoZW1hIiwiUHVibGlzaFBhZ2UiLCJDdXN0b21FbWFpbERvbWFpbiIsIkNsaWVudEJpbGxpbmciLCJDdXN0b21XTERvbWFpbiIsIlphcGllckJsb2ciLCJaYXBpZXJDb21tZW50cyIsIlphcGllckZvcm0iLCJaYXBpZXJTdG9yZSIsIlphcGllck5hdGl2ZVN0b3JlIiwiWmFwaWVyTWVtYmVyc2hpcCIsIlphcGllckZvcm1Db250ZW50TGlicmFyeSIsIlphcGllckNvbGxlY3Rpb25zIiwiWmFwaWVyQ3JlYXRlU2l0ZSIsIlphcGllckNyZWF0ZUNsaWVudCIsIkN1c3RvbUJyYW5kaW5nIiwiMmZhRm9yT3duZXIiLCIyZmFGb3JTdGFmZiIsIkdvb2dsZUJ1c2luZXNzUHJvZmlsZVN5bmMiLCJBSUFkdmFuY2VkQ29udGVudEdlbmVyYXRpb24iLCJBSVBhZ2VzQW5kU2VjdGlvbnNDb250ZW50R2VuZXJhdGlvbiIsIlVubGltaXRlZENsaWVudHNXaXRoU2l0ZUFubm90YXRpb25zIiwiTWNwQmFzaWMiLCJDdXN0b21Bc3NldHNUZW1wbGF0ZXMiLCJDdXN0b21Bc3NldHNTZWN0aW9ucyJdLCJudW1PZkZyZWVTaXRlcyI6NCwibnVtT2ZTdGFmZlVzZXJzIjoyNSwiZ3JhZGUiOjgsInNpdGVDb250cmFjdHMiOlt7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjExLjAsInByaWNlTm9UYXgiOjExLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDU4IiwicHJpY2VUb3RhbCI6MTEuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNTgiLCJwcmljZVRvRGlzcGxheSI6IjExIiwicGxhbklkIjo3fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjUlIiwicHJpY2UiOjEwOC4wLCJwcmljZU5vVGF4IjoxMDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA1OSIsInByaWNlVG90YWwiOjEwOC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyODA1OSIsInByaWNlVG9EaXNwbGF5IjoiOSIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxOS4wLCJwcmljZU5vVGF4IjoxOS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDYwIiwicHJpY2VUb3RhbCI6MTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNjAiLCJwcmljZVRvRGlzcGxheSI6IjE5IiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTclIiwicHJpY2UiOjE5Mi4wLCJwcmljZU5vVGF4IjoxOTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDYxIiwicHJpY2VUb3RhbCI6MTkyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDYxIiwicHJpY2VUb0Rpc3BsYXkiOiIxNiIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjozMy4wLCJwcmljZU5vVGF4IjozMy4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDY0IiwicHJpY2VUb3RhbCI6MzMuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNjQiLCJwcmljZVRvRGlzcGxheSI6IjMzIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTUlIiwicHJpY2UiOjM0OC4wLCJwcmljZU5vVGF4IjozNDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDY1IiwicHJpY2VUb3RhbCI6MzQ4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDY1IiwicHJpY2VUb0Rpc3BsYXkiOiIyOSIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo2My4wLCJwcmljZU5vVGF4Ijo2My4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBVbmxpbWl0ZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA2OCIsInByaWNlVG90YWwiOjYzLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDY4IiwicHJpY2VUb0Rpc3BsYXkiOiI2MyIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMSUiLCJwcmljZSI6NjQ4LjAsInByaWNlTm9UYXgiOjY0OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIFVubGltaXRlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDY5IiwicHJpY2VUb3RhbCI6NjQ4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDY5IiwicHJpY2VUb0Rpc3BsYXkiOiI1NCIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTkuMCwicHJpY2VOb1RheCI6MTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA3MiIsInByaWNlVG90YWwiOjE5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDcyIiwicHJpY2VUb0Rpc3BsYXkiOiIxOSIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxNyUiLCJwcmljZSI6MTkyLjAsInByaWNlTm9UYXgiOjE5Mi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwNzMiLCJwcmljZVRvdGFsIjoxOTIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNzMiLCJwcmljZVRvRGlzcGxheSI6IjE2IiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjozMy4wLCJwcmljZU5vVGF4IjozMy4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDc2IiwicHJpY2VUb3RhbCI6MzMuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNzYiLCJwcmljZVRvRGlzcGxheSI6IjMzIiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE3JSIsInByaWNlIjozNDguMCwicHJpY2VOb1RheCI6MzQ4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA3NyIsInByaWNlVG90YWwiOjM0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyODA3NyIsInByaWNlVG9EaXNwbGF5IjoiMjkiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjYzLjAsInByaWNlTm9UYXgiOjYzLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwODAiLCJwcmljZVRvdGFsIjo2My4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyODA4MCIsInByaWNlVG9EaXNwbGF5IjoiNjMiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjElIiwicHJpY2UiOjY0OC4wLCJwcmljZU5vVGF4Ijo2NDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDgxIiwicHJpY2VUb3RhbCI6NjQ4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDgxIiwicHJpY2VUb0Rpc3BsYXkiOiI1NCIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6Mjk5LjAsInByaWNlTm9UYXgiOjI5OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwMDciLCJwcmljZVRvdGFsIjoyOTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwMDciLCJwcmljZVRvRGlzcGxheSI6IjI5OSIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo4LjAsInByaWNlTm9UYXgiOjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgU3RhbmRhcmQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwNjIiLCJwcmljZVRvdGFsIjo4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDYyIiwicHJpY2VUb0Rpc3BsYXkiOiI4IiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiOSUiLCJwcmljZSI6ODQuMCwicHJpY2VOb1RheCI6ODQuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBTdGFuZGFyZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA2MyIsInByaWNlVG90YWwiOjg0LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDYzIiwicHJpY2VUb0Rpc3BsYXkiOiI3IiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjIyLjAsInByaWNlTm9UYXgiOjIyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IEFkdmFuY2VkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDY2IiwicHJpY2VUb3RhbCI6MjIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNjYiLCJwcmljZVRvRGlzcGxheSI6IjIyIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTIlIiwicHJpY2UiOjI0MC4wLCJwcmljZU5vVGF4IjoyNDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBBZHZhbmNlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA2NyIsInByaWNlVG90YWwiOjI0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyODA2NyIsInByaWNlVG9EaXNwbGF5IjoiMjAiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NTIuMCwicHJpY2VOb1RheCI6NTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgVW5saW1pdGVkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDcwIiwicHJpY2VUb3RhbCI6NTIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNzAiLCJwcmljZVRvRGlzcGxheSI6IjUyIiwicGxhbklkIjoxMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIwJSIsInByaWNlIjo1NDAuMCwicHJpY2VOb1RheCI6NTQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgVW5saW1pdGVkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDcxIiwicHJpY2VUb3RhbCI6NTQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDcxIiwicHJpY2VUb0Rpc3BsYXkiOiI0NSIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6OC4wLCJwcmljZU5vVGF4Ijo4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwNzQiLCJwcmljZVRvdGFsIjo4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDc0IiwicHJpY2VUb0Rpc3BsYXkiOiI4IiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjg0LjAsInByaWNlTm9UYXgiOjg0LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA3NSIsInByaWNlVG90YWwiOjg0LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDc1IiwicHJpY2VUb0Rpc3BsYXkiOiI3IiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyMi4wLCJwcmljZU5vVGF4IjoyMi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDc4IiwicHJpY2VUb3RhbCI6MjIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwNzgiLCJwcmljZVRvRGlzcGxheSI6IjIyIiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjI0MC4wLCJwcmljZU5vVGF4IjoyNDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI4MDc5IiwicHJpY2VUb3RhbCI6MjQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDc5IiwicHJpY2VUb0Rpc3BsYXkiOiIyMCIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NTIuMCwicHJpY2VOb1RheCI6NTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyODA4MiIsInByaWNlVG90YWwiOjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI4MDgyIiwicHJpY2VUb0Rpc3BsYXkiOiI1MiIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMCUiLCJwcmljZSI6NTQwLjAsInByaWNlTm9UYXgiOjU0MC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwODMiLCJwcmljZVRvdGFsIjo1NDAuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwODMiLCJwcmljZVRvRGlzcGxheSI6IjQ1IiwicGxhbklkIjoyMn0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJvbmV0aW1lIiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxNTkuMCwicHJpY2VOb1RheCI6MTU5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEN1c3RvbSBMaXRlIFNpdGUgRm9yIExpZmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA1ODAwMyIsInByaWNlVG90YWwiOjE1OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA1ODAwMyIsInByaWNlVG9EaXNwbGF5IjoiMTU5IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjExLjAsInByaWNlTm9UYXgiOjExLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEN1c3RvbSBMaXRlIE1vbnRobHkgU2l0ZSBQbGFuIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwODQiLCJwcmljZVRvdGFsIjoxMS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyODA4NCIsInByaWNlVG9EaXNwbGF5IjoiMTEiLCJwbGFuSWQiOjN9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyNSUiLCJwcmljZSI6MTA4LjAsInByaWNlTm9UYXgiOjEwOC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBDdXN0b20gTGl0ZSBZZWFybHkgU2l0ZSBQbGFuIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjgwODUiLCJwcmljZVRvdGFsIjoxMDguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjgwODUiLCJwcmljZVRvRGlzcGxheSI6IjkiLCJwbGFuSWQiOjN9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTU5LjAsInByaWNlTm9UYXgiOjE1OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBDdXN0b20gTGl0ZSBTaXRlIEZvciBMaWZlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNTgwMDMiLCJwcmljZVRvdGFsIjoxNTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNTgwMDMiLCJwcmljZVRvRGlzcGxheSI6IjE1OSIsInBsYW5JZCI6M31dLCJudW1Bbm5vdGF0aW9uc1RvdGFsQ3VzdG9tZXJzTGltaXQiOjEwMCwibnVtT2ZJbnRlcm5hbENvbGxlY3Rpb25zIjoxMDAsIm51bU9mSW50ZXJuYWxDb2xsZWN0aW9uUm93cyI6NTAwLCJtYXhBbGxvd2VkUHVibGlzaGVkV2lkZ2V0cyI6bnVsbCwibWF4QWxsb3dlZEN1c3RvbVRlbXBsYXRlcyI6bnVsbCwibWF4QWxsb3dlZEN1c3RvbVNlY3Rpb25zIjpudWxsLCJzZWxmU2VydmljZVBsYW4iOmZhbHNlfSx7InR5cGUiOiJBR0VOQ1lfUExVUyIsImZlYXR1cmVzIjpbIkdvb2dsZVNwZWVkT3B0aW1pemF0aW9uIiwiUHJlbWl1bUltYWdlcyIsIkRldk1vZGVBY2Nlc3MiLCJNdWx0aUxhbmd1YWdlIiwiVW5saW1pdGVkTGFuZGluZ1BhZ2VzIiwiU21hbGxQcm9kdWN0U3RvcmUiLCJXTENsaWVudEFjY2VzcyIsIldMU2FsZXNNYXJrZXRpbmdNYXRlcmlhbCIsIkNvbmZpZ3VyYWJsZVByaWNlUGxhbnMiLCJSb2xlc0FuZFBlcm1pc3Npb25zIiwiQ2xpZW50U3RhdHNBbmRBbmFseXRpY3MiLCJUZWFtQXNzZXRzU2hhcmluZyIsIlByb0Z1bGZpbGxtZW50Q2hhbm5lbCIsIkZyZWVTaXRlU1NMIiwiU2l0ZUJhY2t1cCIsIlNpdGVFeHBvcnQiLCJBUElBY2Nlc3MiLCJXaWRnZXRCdWlsZGVyIiwiRGF0YUJpbmRpbmciLCJEeW5hbWljUGFnZXMiLCJTaXRlQW5ub3RhdGlvbnMiLCJDb250ZW50Q29sbGVjdGlvbkZvcm0iLCJaZW5kZXNrLVRhbGstV2Vla2RheSIsIlplbmRlc2stVGFsay1XZWVrZW5kIiwiWmVuZGVzay1DaGF0LVdlZWtkYXkiLCJaZW5kZXNrLUNoYXQtV2Vla2VuZCIsIlplbmRlc2stQ29udGFjdEZvcm0iLCJJbWFnZUNvbGxlY3Rpb25zIiwiSW50ZXJuYWxDb2xsZWN0aW9ucyIsIkV4dGVybmFsSW50ZWdyYXRpb25Db2xsZWN0aW9ucyIsIkV4dGVybmFsQ29sbGVjdGlvbnMiLCJMb2NhbEJ1c2luZXNzU2NoZW1hIiwiUHVibGlzaFBhZ2UiLCJDdXN0b21FbWFpbERvbWFpbiIsIkNsaWVudEJpbGxpbmciLCJDdXN0b21XTERvbWFpbiIsIlphcGllckJsb2ciLCJaYXBpZXJDb21tZW50cyIsIlphcGllckZvcm0iLCJaYXBpZXJTdG9yZSIsIlphcGllck5hdGl2ZVN0b3JlIiwiWmFwaWVyTWVtYmVyc2hpcCIsIlphcGllckZvcm1Db250ZW50TGlicmFyeSIsIlphcGllckNvbGxlY3Rpb25zIiwiWmFwaWVyQ3JlYXRlU2l0ZSIsIlphcGllckNyZWF0ZUNsaWVudCIsIkN1c3RvbUJyYW5kaW5nIiwiMmZhRm9yT3duZXIiLCIyZmFGb3JTdGFmZiIsIkdvb2dsZUJ1c2luZXNzUHJvZmlsZVN5bmMiLCJBSUFkdmFuY2VkQ29udGVudEdlbmVyYXRpb24iLCJBSVBhZ2VzQW5kU2VjdGlvbnNDb250ZW50R2VuZXJhdGlvbiIsIk1jcEJhc2ljIiwiQ3VzdG9tQXNzZXRzVGVtcGxhdGVzIiwiQ3VzdG9tQXNzZXRzU2VjdGlvbnMiXSwibnVtT2ZGcmVlU2l0ZXMiOjQsIm51bU9mU3RhZmZVc2VycyI6MjUsImdyYWRlIjo3LCJzaXRlQ29udHJhY3RzIjpbeyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxMS4wLCJwcmljZU5vVGF4IjoxMS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTAzMiIsInByaWNlVG90YWwiOjExLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDMyIiwicHJpY2VUb0Rpc3BsYXkiOiIxMSIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjI1JSIsInByaWNlIjoxMDguMCwicHJpY2VOb1RheCI6MTA4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwMzMiLCJwcmljZVRvdGFsIjoxMDguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjUwMzMiLCJwcmljZVRvRGlzcGxheSI6IjkiLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTkuMCwicHJpY2VOb1RheCI6MTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTAzNCIsInByaWNlVG90YWwiOjE5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDM0IiwicHJpY2VUb0Rpc3BsYXkiOiIxOSIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE3JSIsInByaWNlIjoxOTIuMCwicHJpY2VOb1RheCI6MTkyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTAzNSIsInByaWNlVG90YWwiOjE5Mi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTAzNSIsInByaWNlVG9EaXNwbGF5IjoiMTYiLCJwbGFuSWQiOjh9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MzMuMCwicHJpY2VOb1RheCI6MzMuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTAzOCIsInByaWNlVG90YWwiOjMzLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDM4IiwicHJpY2VUb0Rpc3BsYXkiOiIzMyIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE1JSIsInByaWNlIjozNDguMCwicHJpY2VOb1RheCI6MzQ4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTAzOSIsInByaWNlVG90YWwiOjM0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTAzOSIsInByaWNlVG9EaXNwbGF5IjoiMjkiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NjMuMCwicHJpY2VOb1RheCI6NjMuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgVW5saW1pdGVkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwNDIiLCJwcmljZVRvdGFsIjo2My4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA0MiIsInByaWNlVG9EaXNwbGF5IjoiNjMiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjElIiwicHJpY2UiOjY0OC4wLCJwcmljZU5vVGF4Ijo2NDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBVbmxpbWl0ZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA0MyIsInByaWNlVG90YWwiOjY0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA0MyIsInByaWNlVG9EaXNwbGF5IjoiNTQiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE5LjAsInByaWNlTm9UYXgiOjE5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwNDYiLCJwcmljZVRvdGFsIjoxOS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA0NiIsInByaWNlVG9EaXNwbGF5IjoiMTkiLCJwbGFuSWQiOjIwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTclIiwicHJpY2UiOjE5Mi4wLCJwcmljZU5vVGF4IjoxOTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDQ3IiwicHJpY2VUb3RhbCI6MTkyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDQ3IiwicHJpY2VUb0Rpc3BsYXkiOiIxNiIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MzMuMCwicHJpY2VOb1RheCI6MzMuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA1MCIsInByaWNlVG90YWwiOjMzLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDUwIiwicHJpY2VUb0Rpc3BsYXkiOiIzMyIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxNyUiLCJwcmljZSI6MzQ4LjAsInByaWNlTm9UYXgiOjM0OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwNTEiLCJwcmljZVRvdGFsIjozNDguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjUwNTEiLCJwcmljZVRvRGlzcGxheSI6IjI5IiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo2My4wLCJwcmljZU5vVGF4Ijo2My4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDU0IiwicHJpY2VUb3RhbCI6NjMuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjUwNTQiLCJwcmljZVRvRGlzcGxheSI6IjYzIiwicGxhbklkIjoyMn0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIxJSIsInByaWNlIjo2NDguMCwicHJpY2VOb1RheCI6NjQ4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA1NSIsInByaWNlVG90YWwiOjY0OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA1NSIsInByaWNlVG9EaXNwbGF5IjoiNTQiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjI5OS4wLCJwcmljZU5vVGF4IjoyOTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDA3IiwicHJpY2VUb3RhbCI6Mjk5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDA3IiwicHJpY2VUb0Rpc3BsYXkiOiIyOTkiLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6OC4wLCJwcmljZU5vVGF4Ijo4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFN0YW5kYXJkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDM2IiwicHJpY2VUb3RhbCI6OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTAzNiIsInByaWNlVG9EaXNwbGF5IjoiOCIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjg0LjAsInByaWNlTm9UYXgiOjg0LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgU3RhbmRhcmQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwMzciLCJwcmljZVRvdGFsIjo4NC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTAzNyIsInByaWNlVG9EaXNwbGF5IjoiNyIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyMi4wLCJwcmljZU5vVGF4IjoyMi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBBZHZhbmNlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA0MCIsInByaWNlVG90YWwiOjIyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDQwIiwicHJpY2VUb0Rpc3BsYXkiOiIyMiIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjEyJSIsInByaWNlIjoyNDAuMCwicHJpY2VOb1RheCI6MjQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgQWR2YW5jZWQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwNDEiLCJwcmljZVRvdGFsIjoyNDAuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjUwNDEiLCJwcmljZVRvRGlzcGxheSI6IjIwIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjUyLjAsInByaWNlTm9UYXgiOjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFVubGltaXRlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA0NCIsInByaWNlVG90YWwiOjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDQ0IiwicHJpY2VUb0Rpc3BsYXkiOiI1MiIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMCUiLCJwcmljZSI6NTQwLjAsInByaWNlTm9UYXgiOjU0MC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFVubGltaXRlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA0NSIsInByaWNlVG90YWwiOjU0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA0NSIsInByaWNlVG9EaXNwbGF5IjoiNDUiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjguMCwicHJpY2VOb1RheCI6OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDQ4IiwicHJpY2VUb3RhbCI6OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA0OCIsInByaWNlVG9EaXNwbGF5IjoiOCIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjo4NC4wLCJwcmljZU5vVGF4Ijo4NC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwNDkiLCJwcmljZVRvdGFsIjo4NC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA0OSIsInByaWNlVG9EaXNwbGF5IjoiNyIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MjIuMCwicHJpY2VOb1RheCI6MjIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA1MiIsInByaWNlVG90YWwiOjIyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDUyIiwicHJpY2VUb0Rpc3BsYXkiOiIyMiIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjoyNDAuMCwicHJpY2VOb1RheCI6MjQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyNTA1MyIsInByaWNlVG90YWwiOjI0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA1MyIsInByaWNlVG9EaXNwbGF5IjoiMjAiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjUyLjAsInByaWNlTm9UYXgiOjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjUwNTYiLCJwcmljZVRvdGFsIjo1Mi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyNTA1NiIsInByaWNlVG9EaXNwbGF5IjoiNTIiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjU0MC4wLCJwcmljZU5vVGF4Ijo1NDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDU3IiwicHJpY2VUb3RhbCI6NTQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDU3IiwicHJpY2VUb0Rpc3BsYXkiOiI0NSIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTU5LjAsInByaWNlTm9UYXgiOjE1OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBBZ2VuY3kgUGx1cyBTaXRlIEZvciBMaWZlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNTUwMDMiLCJwcmljZVRvdGFsIjoxNTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNTUwMDMiLCJwcmljZVRvRGlzcGxheSI6IjE1OSIsInBsYW5JZCI6M30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxMS4wLCJwcmljZU5vVGF4IjoxMS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBBZ2VuY3kgUGx1cyBNb250aGx5IFNpdGUgUGxhbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDU4IiwicHJpY2VUb3RhbCI6MTEuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjUwNTgiLCJwcmljZVRvRGlzcGxheSI6IjExIiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjUlIiwicHJpY2UiOjEwOC4wLCJwcmljZU5vVGF4IjoxMDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiRG0gQWdlbmN5IFBsdXMgWWVhcmx5IFNpdGUgUGxhbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDI1MDU5IiwicHJpY2VUb3RhbCI6MTA4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDI1MDU5IiwicHJpY2VUb0Rpc3BsYXkiOiI5IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE1OS4wLCJwcmljZU5vVGF4IjoxNTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiRG0gQWdlbmN5IFBsdXMgU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDU1MDAzIiwicHJpY2VUb3RhbCI6MTU5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDU1MDAzIiwicHJpY2VUb0Rpc3BsYXkiOiIxNTkiLCJwbGFuSWQiOjN9XSwibnVtQW5ub3RhdGlvbnNUb3RhbEN1c3RvbWVyc0xpbWl0IjoxMDAsIm51bU9mSW50ZXJuYWxDb2xsZWN0aW9ucyI6MTAwLCJudW1PZkludGVybmFsQ29sbGVjdGlvblJvd3MiOjUwMCwibWF4QWxsb3dlZFB1Ymxpc2hlZFdpZGdldHMiOm51bGwsIm1heEFsbG93ZWRDdXN0b21UZW1wbGF0ZXMiOm51bGwsIm1heEFsbG93ZWRDdXN0b21TZWN0aW9ucyI6bnVsbCwic2VsZlNlcnZpY2VQbGFuIjpmYWxzZX0seyJ0eXBlIjoiQkFTSUMiLCJmZWF0dXJlcyI6WyJHb29nbGVTcGVlZE9wdGltaXphdGlvbiIsIlByZW1pdW1JbWFnZXMiLCJEZXZNb2RlQWNjZXNzIiwiTXVsdGlMYW5ndWFnZSIsIlVubGltaXRlZExhbmRpbmdQYWdlcyIsIlNtYWxsUHJvZHVjdFN0b3JlIiwiQ29uZmlndXJhYmxlUHJpY2VQbGFucyIsIkZyZWVTaXRlU1NMIiwiU2l0ZUJhY2t1cCIsIlplbmRlc2stQ29udGFjdEZvcm0iLCIyZmFGb3JPd25lciIsIkFJQWR2YW5jZWRDb250ZW50R2VuZXJhdGlvbiIsIkFJUGFnZXNBbmRTZWN0aW9uc0NvbnRlbnRHZW5lcmF0aW9uIl0sIm51bU9mRnJlZVNpdGVzIjoxLCJudW1PZlN0YWZmVXNlcnMiOjAsImdyYWRlIjoyLCJzaXRlQ29udHJhY3RzIjpbeyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxOS4wLCJwcmljZU5vVGF4IjoxOS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMTAwMSIsInByaWNlVG90YWwiOjE5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIxMDAxIiwicHJpY2VUb0Rpc3BsYXkiOiIxOSIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjI1JSIsInByaWNlIjoxNzEuMCwicHJpY2VOb1RheCI6MTcxLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMDIiLCJwcmljZVRvdGFsIjoxNzEuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMDIiLCJwcmljZVRvRGlzcGxheSI6IjE0LjI1IiwicGxhbklkIjo3fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjI3LjAsInByaWNlTm9UYXgiOjI3LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMDMiLCJwcmljZVRvdGFsIjoyNy4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAwMyIsInByaWNlVG9EaXNwbGF5IjoiMjciLCJwbGFuSWQiOjh9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMCUiLCJwcmljZSI6MjU4LjAsInByaWNlTm9UYXgiOjI1OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMDQiLCJwcmljZVRvdGFsIjoyNTguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMDQiLCJwcmljZVRvRGlzcGxheSI6IjIxLjUwIiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjQxLjAsInByaWNlTm9UYXgiOjQxLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMDUiLCJwcmljZVRvdGFsIjo0MS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAwNSIsInByaWNlVG9EaXNwbGF5IjoiNDEiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxOCUiLCJwcmljZSI6NDAyLjAsInByaWNlTm9UYXgiOjQwMi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMDYiLCJwcmljZVRvdGFsIjo0MDIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMDYiLCJwcmljZVRvRGlzcGxheSI6IjMzLjUwIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjY4LjAsInByaWNlTm9UYXgiOjY4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIFVubGltaXRlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIxMDEyIiwicHJpY2VUb3RhbCI6NjguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMTIiLCJwcmljZVRvRGlzcGxheSI6IjY4IiwicGxhbklkIjoxMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIxJSIsInByaWNlIjo2MzkuMCwicHJpY2VOb1RheCI6NjM5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgVW5saW1pdGVkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMTMiLCJwcmljZVRvdGFsIjo2MzkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMTMiLCJwcmljZVRvRGlzcGxheSI6IjUzLjI1IiwicGxhbklkIjoxMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyNy4wLCJwcmljZU5vVGF4IjoyNy4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIxMDIwIiwicHJpY2VUb3RhbCI6MjcuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMjAiLCJwcmljZVRvRGlzcGxheSI6IjI3IiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIwJSIsInByaWNlIjoyNTguMCwicHJpY2VOb1RheCI6MjU4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMTAyMSIsInByaWNlVG90YWwiOjI1OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAyMSIsInByaWNlVG9EaXNwbGF5IjoiMjEuNTAiLCJwbGFuSWQiOjIwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjQxLjAsInByaWNlTm9UYXgiOjQxLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMjQiLCJwcmljZVRvdGFsIjo0MS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAyNCIsInByaWNlVG9EaXNwbGF5IjoiNDEiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjQwMi4wLCJwcmljZU5vVGF4Ijo0MDIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIxMDI1IiwicHJpY2VUb3RhbCI6NDAyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIxMDI1IiwicHJpY2VUb0Rpc3BsYXkiOiIzMy41MCIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NjguMCwicHJpY2VOb1RheCI6NjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA0MTAxMiIsInByaWNlVG90YWwiOjY4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDQxMDEyIiwicHJpY2VUb0Rpc3BsYXkiOiI2OCIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMSUiLCJwcmljZSI6NjM5LjAsInByaWNlTm9UYXgiOjYzOS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNDEwMTMiLCJwcmljZVRvdGFsIjo2MzkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNDEwMTMiLCJwcmljZVRvRGlzcGxheSI6IjUzLjI1IiwicGxhbklkIjoyMn0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJvbmV0aW1lIiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyOTkuMCwicHJpY2VOb1RheCI6Mjk5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMTAwNyIsInByaWNlVG90YWwiOjI5OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAwNyIsInByaWNlVG9EaXNwbGF5IjoiMjk5IiwicGxhbklkIjo3fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjguMCwicHJpY2VOb1RheCI6OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBTdGFuZGFyZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMTAwOCIsInByaWNlVG90YWwiOjguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMDgiLCJwcmljZVRvRGlzcGxheSI6IjgiLCJwbGFuSWQiOjh9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjo4Ny4wLCJwcmljZU5vVGF4Ijo4Ny4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFN0YW5kYXJkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIxMDA5IiwicHJpY2VUb3RhbCI6ODcuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMDkiLCJwcmljZVRvRGlzcGxheSI6IjcuMjUiLCJwbGFuSWQiOjh9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MjIuMCwicHJpY2VOb1RheCI6MjIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgQWR2YW5jZWQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMTAiLCJwcmljZVRvdGFsIjoyMi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAxMCIsInByaWNlVG9EaXNwbGF5IjoiMjIiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxMiUiLCJwcmljZSI6MjMxLjAsInByaWNlTm9UYXgiOjIzMS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIEFkdmFuY2VkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIxMDExIiwicHJpY2VUb3RhbCI6MjMxLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIxMDExIiwicHJpY2VUb0Rpc3BsYXkiOiIxOS4yNSIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo0OS4wLCJwcmljZU5vVGF4Ijo0OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBVbmxpbWl0ZWQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMTQiLCJwcmljZVRvdGFsIjo0OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAxNCIsInByaWNlVG9EaXNwbGF5IjoiNDkiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjQ2OC4wLCJwcmljZU5vVGF4Ijo0NjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBVbmxpbWl0ZWQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMTUiLCJwcmljZVRvdGFsIjo0NjguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMTUiLCJwcmljZVRvRGlzcGxheSI6IjM5IiwicGxhbklkIjoxMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo4LjAsInByaWNlTm9UYXgiOjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMTAyMiIsInByaWNlVG90YWwiOjguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMjIiLCJwcmljZVRvRGlzcGxheSI6IjgiLCJwbGFuSWQiOjIwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiOSUiLCJwcmljZSI6ODcuMCwicHJpY2VOb1RheCI6ODcuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIxMDIzIiwicHJpY2VUb3RhbCI6ODcuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMjMiLCJwcmljZVRvRGlzcGxheSI6IjcuMjUiLCJwbGFuSWQiOjIwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjIyLjAsInByaWNlTm9UYXgiOjIyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMjYiLCJwcmljZVRvdGFsIjoyMi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMTAyNiIsInByaWNlVG9EaXNwbGF5IjoiMjIiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiOSUiLCJwcmljZSI6MjMxLjAsInByaWNlTm9UYXgiOjIzMS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjEwMjciLCJwcmljZVRvdGFsIjoyMzEuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjEwMjciLCJwcmljZVRvRGlzcGxheSI6IjE5LjI1IiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo0OS4wLCJwcmljZU5vVGF4Ijo0OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDQxMDE0IiwicHJpY2VUb3RhbCI6NDkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNDEwMTQiLCJwcmljZVRvRGlzcGxheSI6IjQ5IiwicGxhbklkIjoyMn0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIwJSIsInByaWNlIjo0NjguMCwicHJpY2VOb1RheCI6NDY4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA0MTAxNSIsInByaWNlVG90YWwiOjQ2OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA0MTAxNSIsInByaWNlVG9EaXNwbGF5IjoiMzkiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE5LjAsInByaWNlTm9UYXgiOjE5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEJhc2ljIE1vbnRobHkgU2l0ZSBQbGFuIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNTEwMDEiLCJwcmljZVRvdGFsIjoxOS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA1MTAwMSIsInByaWNlVG9EaXNwbGF5IjoiMTkiLCJwbGFuSWQiOjN9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyNSUiLCJwcmljZSI6MTcxLjAsInByaWNlTm9UYXgiOjE3MS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBCYXNpYyBZZWFybHkgU2l0ZSBQbGFuIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNTEwMDIiLCJwcmljZVRvdGFsIjoxNzEuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNTEwMDIiLCJwcmljZVRvRGlzcGxheSI6IjE0LjI1IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE1OS4wLCJwcmljZU5vVGF4IjoxNTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiRG0gQmFzaWMgU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDUxMDAzIiwicHJpY2VUb3RhbCI6MTU5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDUxMDAzIiwicHJpY2VUb0Rpc3BsYXkiOiIxNTkiLCJwbGFuSWQiOjN9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTU5LjAsInByaWNlTm9UYXgiOjE1OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBCYXNpYyBTaXRlIEZvciBMaWZlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwNTEwMDMiLCJwcmljZVRvdGFsIjoxNTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwNTEwMDMiLCJwcmljZVRvRGlzcGxheSI6IjE1OSIsInBsYW5JZCI6M30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJvbmV0aW1lIiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxNTkuMCwicHJpY2VOb1RheCI6MTU5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEJhc2ljIFNpdGUgRm9yIExpZmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA1MTAwMyIsInByaWNlVG90YWwiOjE1OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA1MTAwMyIsInByaWNlVG9EaXNwbGF5IjoiMTU5IiwicGxhbklkIjozfV0sIm51bUFubm90YXRpb25zVG90YWxDdXN0b21lcnNMaW1pdCI6MCwibnVtT2ZJbnRlcm5hbENvbGxlY3Rpb25zIjowLCJudW1PZkludGVybmFsQ29sbGVjdGlvblJvd3MiOjAsIm1heEFsbG93ZWRQdWJsaXNoZWRXaWRnZXRzIjpudWxsLCJtYXhBbGxvd2VkQ3VzdG9tVGVtcGxhdGVzIjpudWxsLCJtYXhBbGxvd2VkQ3VzdG9tU2VjdGlvbnMiOm51bGwsInNlbGZTZXJ2aWNlUGxhbiI6dHJ1ZX0seyJ0eXBlIjoiVEVBTSIsImZlYXR1cmVzIjpbIkdvb2dsZVNwZWVkT3B0aW1pemF0aW9uIiwiUHJlbWl1bUltYWdlcyIsIkRldk1vZGVBY2Nlc3MiLCJNdWx0aUxhbmd1YWdlIiwiVW5saW1pdGVkTGFuZGluZ1BhZ2VzIiwiU21hbGxQcm9kdWN0U3RvcmUiLCJXTENsaWVudEFjY2VzcyIsIldMU2FsZXNNYXJrZXRpbmdNYXRlcmlhbCIsIkNvbmZpZ3VyYWJsZVByaWNlUGxhbnMiLCJSb2xlc0FuZFBlcm1pc3Npb25zIiwiQ2xpZW50U3RhdHNBbmRBbmFseXRpY3MiLCJUZWFtQXNzZXRzU2hhcmluZyIsIlByb0Z1bGZpbGxtZW50Q2hhbm5lbCIsIkZyZWVTaXRlU1NMIiwiU2l0ZUJhY2t1cCIsIkRhdGFCaW5kaW5nIiwiRHluYW1pY1BhZ2VzIiwiU2l0ZUFubm90YXRpb25zIiwiQ29udGVudENvbGxlY3Rpb25Gb3JtIiwiWmVuZGVzay1Db250YWN0Rm9ybSIsIkltYWdlQ29sbGVjdGlvbnMiLCJJbnRlcm5hbENvbGxlY3Rpb25zIiwiTG9jYWxCdXNpbmVzc1NjaGVtYSIsIkNsaWVudEJpbGxpbmciLCJDdXN0b21XTERvbWFpbiIsIlphcGllckJsb2ciLCJaYXBpZXJDb21tZW50cyIsIlphcGllckZvcm0iLCJaYXBpZXJTdG9yZSIsIlphcGllck5hdGl2ZVN0b3JlIiwiWmFwaWVyTWVtYmVyc2hpcCIsIkN1c3RvbUJyYW5kaW5nIiwiMmZhRm9yT3duZXIiLCIyZmFGb3JTdGFmZiIsIkFJQWR2YW5jZWRDb250ZW50R2VuZXJhdGlvbiIsIkFJUGFnZXNBbmRTZWN0aW9uc0NvbnRlbnRHZW5lcmF0aW9uIiwiQ3VzdG9tQXNzZXRzVGVtcGxhdGVzIiwiQ3VzdG9tQXNzZXRzU2VjdGlvbnMiXSwibnVtT2ZGcmVlU2l0ZXMiOjEsIm51bU9mU3RhZmZVc2VycyI6NCwiZ3JhZGUiOjMsInNpdGVDb250cmFjdHMiOlt7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE3LjAsInByaWNlTm9UYXgiOjE3LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDYwIiwicHJpY2VUb3RhbCI6MTcuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjIwNjAiLCJwcmljZVRvRGlzcGxheSI6IjE3IiwicGxhbklkIjo3fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjE2OC4wLCJwcmljZU5vVGF4IjoxNjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA2MSIsInByaWNlVG90YWwiOjE2OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA2MSIsInByaWNlVG9EaXNwbGF5IjoiMTQiLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MjUuMCwicHJpY2VOb1RheCI6MjUuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA2MiIsInByaWNlVG90YWwiOjI1LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDYyIiwicHJpY2VUb0Rpc3BsYXkiOiIyNSIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE2JSIsInByaWNlIjoyNTIuMCwicHJpY2VOb1RheCI6MjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA2MyIsInByaWNlVG90YWwiOjI1Mi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA2MyIsInByaWNlVG9EaXNwbGF5IjoiMjEiLCJwbGFuSWQiOjh9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MzkuMCwicHJpY2VOb1RheCI6MzkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA2NiIsInByaWNlVG90YWwiOjM5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDY2IiwicHJpY2VUb0Rpc3BsYXkiOiIzOSIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE1JSIsInByaWNlIjo0MDguMCwicHJpY2VOb1RheCI6NDA4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA2NyIsInByaWNlVG90YWwiOjQwOC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA2NyIsInByaWNlVG9EaXNwbGF5IjoiMzQiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NjkuMCwicHJpY2VOb1RheCI6NjkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgVW5saW1pdGVkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwNzAiLCJwcmljZVRvdGFsIjo2OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA3MCIsInByaWNlVG9EaXNwbGF5IjoiNjkiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjcwOC4wLCJwcmljZU5vVGF4Ijo3MDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBVbmxpbWl0ZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA3MSIsInByaWNlVG90YWwiOjcwOC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA3MSIsInByaWNlVG9EaXNwbGF5IjoiNTkiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjI1LjAsInByaWNlTm9UYXgiOjI1LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwNzQiLCJwcmljZVRvdGFsIjoyNS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA3NCIsInByaWNlVG9EaXNwbGF5IjoiMjUiLCJwbGFuSWQiOjIwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTYlIiwicHJpY2UiOjI1Mi4wLCJwcmljZU5vVGF4IjoyNTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDc1IiwicHJpY2VUb3RhbCI6MjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDc1IiwicHJpY2VUb0Rpc3BsYXkiOiIyMSIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MzkuMCwicHJpY2VOb1RheCI6MzkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA3OCIsInByaWNlVG90YWwiOjM5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDc4IiwicHJpY2VUb0Rpc3BsYXkiOiIzOSIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxNiUiLCJwcmljZSI6NDA4LjAsInByaWNlTm9UYXgiOjQwOC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIEFkdmFuY2VkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwNzkiLCJwcmljZVRvdGFsIjo0MDguMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjIwNzkiLCJwcmljZVRvRGlzcGxheSI6IjM0IiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo2OS4wLCJwcmljZU5vVGF4Ijo2OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDgyIiwicHJpY2VUb3RhbCI6NjkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjIwODIiLCJwcmljZVRvRGlzcGxheSI6IjY5IiwicGxhbklkIjoyMn0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIwJSIsInByaWNlIjo3MDguMCwicHJpY2VOb1RheCI6NzA4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA4MyIsInByaWNlVG90YWwiOjcwOC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA4MyIsInByaWNlVG9EaXNwbGF5IjoiNTkiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjI5OS4wLCJwcmljZU5vVGF4IjoyOTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDA3IiwicHJpY2VUb3RhbCI6Mjk5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDA3IiwicHJpY2VUb0Rpc3BsYXkiOiIyOTkiLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6OC4wLCJwcmljZU5vVGF4Ijo4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFN0YW5kYXJkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDY0IiwicHJpY2VUb3RhbCI6OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA2NCIsInByaWNlVG9EaXNwbGF5IjoiOCIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjg0LjAsInByaWNlTm9UYXgiOjg0LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgU3RhbmRhcmQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwNjUiLCJwcmljZVRvdGFsIjo4NC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA2NSIsInByaWNlVG9EaXNwbGF5IjoiNyIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyMi4wLCJwcmljZU5vVGF4IjoyMi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBBZHZhbmNlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA2OCIsInByaWNlVG90YWwiOjIyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDY4IiwicHJpY2VUb0Rpc3BsYXkiOiIyMiIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjEyJSIsInByaWNlIjoyNDAuMCwicHJpY2VOb1RheCI6MjQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgQWR2YW5jZWQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwNjkiLCJwcmljZVRvdGFsIjoyNDAuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjIwNjkiLCJwcmljZVRvRGlzcGxheSI6IjIwIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjUyLjAsInByaWNlTm9UYXgiOjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFVubGltaXRlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA3MiIsInByaWNlVG90YWwiOjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDcyIiwicHJpY2VUb0Rpc3BsYXkiOiI1MiIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMCUiLCJwcmljZSI6NTQwLjAsInByaWNlTm9UYXgiOjU0MC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFVubGltaXRlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA3MyIsInByaWNlVG90YWwiOjU0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA3MyIsInByaWNlVG9EaXNwbGF5IjoiNDUiLCJwbGFuSWQiOjEwfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjguMCwicHJpY2VOb1RheCI6OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDc2IiwicHJpY2VUb3RhbCI6OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA3NiIsInByaWNlVG9EaXNwbGF5IjoiOCIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjo4NC4wLCJwcmljZU5vVGF4Ijo4NC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgQW5udWFsIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwNzciLCJwcmljZVRvdGFsIjo4NC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA3NyIsInByaWNlVG9EaXNwbGF5IjoiNyIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MjIuMCwicHJpY2VOb1RheCI6MjIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA4MCIsInByaWNlVG90YWwiOjIyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDgwIiwicHJpY2VUb0Rpc3BsYXkiOiIyMiIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjoyNDAuMCwicHJpY2VOb1RheCI6MjQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA4MSIsInByaWNlVG90YWwiOjI0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA4MSIsInByaWNlVG9EaXNwbGF5IjoiMjAiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjUyLjAsInByaWNlTm9UYXgiOjUyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjIwODQiLCJwcmljZVRvdGFsIjo1Mi4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMjA4NCIsInByaWNlVG9EaXNwbGF5IjoiNTIiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjAlIiwicHJpY2UiOjU0MC4wLCJwcmljZU5vVGF4Ijo1NDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDg1IiwicHJpY2VUb3RhbCI6NTQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDg1IiwicHJpY2VUb0Rpc3BsYXkiOiI0NSIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTU5LjAsInByaWNlTm9UYXgiOjE1OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBUZWFtIFNpdGUgRm9yIExpZmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA1MjAwMyIsInByaWNlVG90YWwiOjE1OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA1MjAwMyIsInByaWNlVG9EaXNwbGF5IjoiMTU5IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE3LjAsInByaWNlTm9UYXgiOjE3LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIFRlYW0gTW9udGhseSBTaXRlIFBsYW4iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMjA4NiIsInByaWNlVG90YWwiOjE3LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDg2IiwicHJpY2VUb0Rpc3BsYXkiOiIxNyIsInBsYW5JZCI6M30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIwJSIsInByaWNlIjoxNjguMCwicHJpY2VOb1RheCI6MTY4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIFRlYW0gWWVhcmx5IFNpdGUgUGxhbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIyMDg3IiwicHJpY2VUb3RhbCI6MTY4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIyMDg3IiwicHJpY2VUb0Rpc3BsYXkiOiIxNCIsInBsYW5JZCI6M30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJvbmV0aW1lIiwiZGlzY291bnQiOm51bGwsInByaWNlIjoxNTkuMCwicHJpY2VOb1RheCI6MTU5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIFRlYW0gU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDUyMDAzIiwicHJpY2VUb3RhbCI6MTU5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDUyMDAzIiwicHJpY2VUb0Rpc3BsYXkiOiIxNTkiLCJwbGFuSWQiOjN9XSwibnVtQW5ub3RhdGlvbnNUb3RhbEN1c3RvbWVyc0xpbWl0IjoxMDAsIm51bU9mSW50ZXJuYWxDb2xsZWN0aW9ucyI6MSwibnVtT2ZJbnRlcm5hbENvbGxlY3Rpb25Sb3dzIjoxMCwibWF4QWxsb3dlZFB1Ymxpc2hlZFdpZGdldHMiOm51bGwsIm1heEFsbG93ZWRDdXN0b21UZW1wbGF0ZXMiOm51bGwsIm1heEFsbG93ZWRDdXN0b21TZWN0aW9ucyI6bnVsbCwic2VsZlNlcnZpY2VQbGFuIjp0cnVlfSx7InR5cGUiOiJBR0VOQ1kiLCJmZWF0dXJlcyI6WyJHb29nbGVTcGVlZE9wdGltaXphdGlvbiIsIlByZW1pdW1JbWFnZXMiLCJEZXZNb2RlQWNjZXNzIiwiTXVsdGlMYW5ndWFnZSIsIlVubGltaXRlZExhbmRpbmdQYWdlcyIsIlNtYWxsUHJvZHVjdFN0b3JlIiwiV0xDbGllbnRBY2Nlc3MiLCJXTFNhbGVzTWFya2V0aW5nTWF0ZXJpYWwiLCJDb25maWd1cmFibGVQcmljZVBsYW5zIiwiUm9sZXNBbmRQZXJtaXNzaW9ucyIsIkNsaWVudFN0YXRzQW5kQW5hbHl0aWNzIiwiVGVhbUFzc2V0c1NoYXJpbmciLCJQcm9GdWxmaWxsbWVudENoYW5uZWwiLCJGcmVlU2l0ZVNTTCIsIlNpdGVCYWNrdXAiLCJTaXRlRXhwb3J0IiwiQVBJQWNjZXNzIiwiV2lkZ2V0QnVpbGRlciIsIkRhdGFCaW5kaW5nIiwiRHluYW1pY1BhZ2VzIiwiU2l0ZUFubm90YXRpb25zIiwiQ29udGVudENvbGxlY3Rpb25Gb3JtIiwiWmVuZGVzay1UYWxrLVdlZWtkYXkiLCJaZW5kZXNrLUNoYXQtV2Vla2RheSIsIlplbmRlc2stQ29udGFjdEZvcm0iLCJJbWFnZUNvbGxlY3Rpb25zIiwiSW50ZXJuYWxDb2xsZWN0aW9ucyIsIkV4dGVybmFsSW50ZWdyYXRpb25Db2xsZWN0aW9ucyIsIkxvY2FsQnVzaW5lc3NTY2hlbWEiLCJQdWJsaXNoUGFnZSIsIkN1c3RvbUVtYWlsRG9tYWluIiwiQ2xpZW50QmlsbGluZyIsIkN1c3RvbVdMRG9tYWluIiwiWmFwaWVyQmxvZyIsIlphcGllckNvbW1lbnRzIiwiWmFwaWVyRm9ybSIsIlphcGllclN0b3JlIiwiWmFwaWVyTmF0aXZlU3RvcmUiLCJaYXBpZXJNZW1iZXJzaGlwIiwiWmFwaWVyQ29sbGVjdGlvbnMiLCJDdXN0b21CcmFuZGluZyIsIjJmYUZvck93bmVyIiwiMmZhRm9yU3RhZmYiLCJHb29nbGVCdXNpbmVzc1Byb2ZpbGVTeW5jIiwiQUlBZHZhbmNlZENvbnRlbnRHZW5lcmF0aW9uIiwiQUlQYWdlc0FuZFNlY3Rpb25zQ29udGVudEdlbmVyYXRpb24iLCJNY3BCYXNpYyIsIkN1c3RvbUFzc2V0c1RlbXBsYXRlcyIsIkN1c3RvbUFzc2V0c1NlY3Rpb25zIl0sIm51bU9mRnJlZVNpdGVzIjo4LCJudW1PZlN0YWZmVXNlcnMiOjEwLCJncmFkZSI6NCwic2l0ZUNvbnRyYWN0cyI6W3siY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTcuMCwicHJpY2VOb1RheCI6MTcuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjMwNjQiLCJwcmljZVRvdGFsIjoxNy4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMzA2NCIsInByaWNlVG9EaXNwbGF5IjoiMTciLCJwbGFuSWQiOjd9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMyUiLCJwcmljZSI6MTY4LjAsInByaWNlTm9UYXgiOjE2OC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDY1IiwicHJpY2VUb3RhbCI6MTY4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDY1IiwicHJpY2VUb0Rpc3BsYXkiOiIxNCIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyNS4wLCJwcmljZU5vVGF4IjoyNS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDY2IiwicHJpY2VUb3RhbCI6MjUuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwNjYiLCJwcmljZVRvRGlzcGxheSI6IjI1IiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTglIiwicHJpY2UiOjI1Mi4wLCJwcmljZU5vVGF4IjoyNTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBTdGFuZGFyZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDY3IiwicHJpY2VUb3RhbCI6MjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDY3IiwicHJpY2VUb0Rpc3BsYXkiOiIyMSIsInBsYW5JZCI6OH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjozOS4wLCJwcmljZU5vVGF4IjozOS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDcwIiwicHJpY2VUb3RhbCI6MzkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwNzAiLCJwcmljZVRvRGlzcGxheSI6IjM5IiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTYlIiwicHJpY2UiOjQwOC4wLCJwcmljZU5vVGF4Ijo0MDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDcxIiwicHJpY2VUb3RhbCI6NDA4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDcxIiwicHJpY2VUb0Rpc3BsYXkiOiIzNCIsInBsYW5JZCI6OX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo2OS4wLCJwcmljZU5vVGF4Ijo2OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBVbmxpbWl0ZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA3NCIsInByaWNlVG90YWwiOjY5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDc0IiwicHJpY2VUb0Rpc3BsYXkiOiI2OSIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIyMSUiLCJwcmljZSI6NzA4LjAsInByaWNlTm9UYXgiOjcwOC4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIFVubGltaXRlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDc1IiwicHJpY2VUb3RhbCI6NzA4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDc1IiwicHJpY2VUb0Rpc3BsYXkiOiI1OSIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MjUuMCwicHJpY2VOb1RheCI6MjUuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiTW9udGhseSBTaXRlICsgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA3OCIsInByaWNlVG90YWwiOjI1LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDc4IiwicHJpY2VUb0Rpc3BsYXkiOiIyNSIsInBsYW5JZCI6MjB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiIxOCUiLCJwcmljZSI6MjUyLjAsInByaWNlTm9UYXgiOjI1Mi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJBbm51YWwgU2l0ZSArIFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjMwNzkiLCJwcmljZVRvdGFsIjoyNTIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwNzkiLCJwcmljZVRvRGlzcGxheSI6IjIxIiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjozOS4wLCJwcmljZU5vVGF4IjozOS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJNb250aGx5IFNpdGUgKyBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDgyIiwicHJpY2VUb3RhbCI6MzkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwODIiLCJwcmljZVRvRGlzcGxheSI6IjM5IiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjE4JSIsInByaWNlIjo0MDguMCwicHJpY2VOb1RheCI6NDA4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkFubnVhbCBTaXRlICsgQWR2YW5jZWQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA4MyIsInByaWNlVG90YWwiOjQwOC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMzA4MyIsInByaWNlVG9EaXNwbGF5IjoiMzQiLCJwbGFuSWQiOjIxfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjY5LjAsInByaWNlTm9UYXgiOjY5LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6Ik1vbnRobHkgU2l0ZSArIEVsaXRlIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjMwODYiLCJwcmljZVRvdGFsIjo2OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMzA4NiIsInByaWNlVG9EaXNwbGF5IjoiNjkiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTglIiwicHJpY2UiOjcwOC4wLCJwcmljZU5vVGF4Ijo3MDguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiQW5udWFsIFNpdGUgKyBFbGl0ZSBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDg3IiwicHJpY2VUb3RhbCI6NzA4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDg3IiwicHJpY2VUb0Rpc3BsYXkiOiI1OSIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6Mjk5LjAsInByaWNlTm9UYXgiOjI5OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjMwMDciLCJwcmljZVRvdGFsIjoyOTkuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwMDciLCJwcmljZVRvRGlzcGxheSI6IjI5OSIsInBsYW5JZCI6N30seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjo4LjAsInByaWNlTm9UYXgiOjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgU3RhbmRhcmQgU3RvcmUgQWRkLW9uIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjMwNjgiLCJwcmljZVRvdGFsIjo4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDY4IiwicHJpY2VUb0Rpc3BsYXkiOiI4IiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiOSUiLCJwcmljZSI6ODQuMCwicHJpY2VOb1RheCI6ODQuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBTdGFuZGFyZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA2OSIsInByaWNlVG90YWwiOjg0LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDY5IiwicHJpY2VUb0Rpc3BsYXkiOiI3IiwicGxhbklkIjo4fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjIyLjAsInByaWNlTm9UYXgiOjIyLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IEFkdmFuY2VkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDcyIiwicHJpY2VUb3RhbCI6MjIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwNzIiLCJwcmljZVRvRGlzcGxheSI6IjIyIiwicGxhbklkIjo5fSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMTIlIiwicHJpY2UiOjI0MC4wLCJwcmljZU5vVGF4IjoyNDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBBZHZhbmNlZCBTdG9yZSBBZGQtb24iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA3MyIsInByaWNlVG90YWwiOjI0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMzA3MyIsInByaWNlVG9EaXNwbGF5IjoiMjAiLCJwbGFuSWQiOjl9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NTIuMCwicHJpY2VOb1RheCI6NTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgVW5saW1pdGVkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDc2IiwicHJpY2VUb3RhbCI6NTIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwNzYiLCJwcmljZVRvRGlzcGxheSI6IjUyIiwicGxhbklkIjoxMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjIwJSIsInByaWNlIjo1NDAuMCwicHJpY2VOb1RheCI6NTQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgVW5saW1pdGVkIFN0b3JlIEFkZC1vbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDc3IiwicHJpY2VUb3RhbCI6NTQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDc3IiwicHJpY2VUb0Rpc3BsYXkiOiI0NSIsInBsYW5JZCI6MTB9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6OC4wLCJwcmljZU5vVGF4Ijo4LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBNb250aGx5IFN0YW5kYXJkIFN0b3JlIiwiY29udHJhY3RGdWxsRGVzY3JpcHRpb24iOm51bGwsImlkIjoiMTAwMjMwODAiLCJwcmljZVRvdGFsIjo4LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDgwIiwicHJpY2VUb0Rpc3BsYXkiOiI4IiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjg0LjAsInByaWNlTm9UYXgiOjg0LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgU3RhbmRhcmQgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA4MSIsInByaWNlVG90YWwiOjg0LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDgxIiwicHJpY2VUb0Rpc3BsYXkiOiI3IiwicGxhbklkIjoyMH0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJtb250aGx5IiwiZGlzY291bnQiOm51bGwsInByaWNlIjoyMi4wLCJwcmljZU5vVGF4IjoyMi4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJTaXRlIEZvciBMaWZlICsgTW9udGhseSBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDg0IiwicHJpY2VUb3RhbCI6MjIuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwODQiLCJwcmljZVRvRGlzcGxheSI6IjIyIiwicGxhbklkIjoyMX0seyJjdXJyZW5jeSI6IiYjMzY7IiwicmVjdXJyZW5jZVR5cGUiOiJ5ZWFybHkiLCJkaXNjb3VudCI6IjklIiwicHJpY2UiOjI0MC4wLCJwcmljZU5vVGF4IjoyNDAuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIEFubnVhbCBBZHZhbmNlZCBTdG9yZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDg1IiwicHJpY2VUb3RhbCI6MjQwLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDg1IiwicHJpY2VUb0Rpc3BsYXkiOiIyMCIsInBsYW5JZCI6MjF9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoibW9udGhseSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6NTIuMCwicHJpY2VOb1RheCI6NTIuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiU2l0ZSBGb3IgTGlmZSArIE1vbnRobHkgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA4OCIsInByaWNlVG90YWwiOjUyLjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDIzMDg4IiwicHJpY2VUb0Rpc3BsYXkiOiI1MiIsInBsYW5JZCI6MjJ9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoieWVhcmx5IiwiZGlzY291bnQiOiI5JSIsInByaWNlIjo1NDAuMCwicHJpY2VOb1RheCI6NTQwLjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IlNpdGUgRm9yIExpZmUgKyBBbm51YWwgRWxpdGUgU3RvcmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA4OSIsInByaWNlVG90YWwiOjU0MC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMzA4OSIsInByaWNlVG9EaXNwbGF5IjoiNDUiLCJwbGFuSWQiOjIyfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im9uZXRpbWUiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE1OS4wLCJwcmljZU5vVGF4IjoxNTkuMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiRG0gQWdlbmN5IFNpdGUgRm9yIExpZmUiLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDA1MzAwMyIsInByaWNlVG90YWwiOjE1OS4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDA1MzAwMyIsInByaWNlVG9EaXNwbGF5IjoiMTU5IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6Im1vbnRobHkiLCJkaXNjb3VudCI6bnVsbCwicHJpY2UiOjE3LjAsInByaWNlTm9UYXgiOjE3LjAsInllYXJseVByaWNlIjpudWxsLCJkZXNjcmlwdGlvbiI6IkRtIEFnZW5jeSBNb250aGx5IFNpdGUgUGxhbiIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDIzMDkwIiwicHJpY2VUb3RhbCI6MTcuMCwidGllclR5cGUiOm51bGwsImNvbnRyYWN0IjoiMTAwMjMwOTAiLCJwcmljZVRvRGlzcGxheSI6IjE3IiwicGxhbklkIjozfSx7ImN1cnJlbmN5IjoiJiMzNjsiLCJyZWN1cnJlbmNlVHlwZSI6InllYXJseSIsImRpc2NvdW50IjoiMjMlIiwicHJpY2UiOjE2OC4wLCJwcmljZU5vVGF4IjoxNjguMCwieWVhcmx5UHJpY2UiOm51bGwsImRlc2NyaXB0aW9uIjoiRG0gQWdlbmN5IFllYXJseSBTaXRlIFBsYW4iLCJjb250cmFjdEZ1bGxEZXNjcmlwdGlvbiI6bnVsbCwiaWQiOiIxMDAyMzA5MSIsInByaWNlVG90YWwiOjE2OC4wLCJ0aWVyVHlwZSI6bnVsbCwiY29udHJhY3QiOiIxMDAyMzA5MSIsInByaWNlVG9EaXNwbGF5IjoiMTQiLCJwbGFuSWQiOjN9LHsiY3VycmVuY3kiOiImIzM2OyIsInJlY3VycmVuY2VUeXBlIjoib25ldGltZSIsImRpc2NvdW50IjpudWxsLCJwcmljZSI6MTU5LjAsInByaWNlTm9UYXgiOjE1OS4wLCJ5ZWFybHlQcmljZSI6bnVsbCwiZGVzY3JpcHRpb24iOiJEbSBBZ2VuY3kgU2l0ZSBGb3IgTGlmZSIsImNvbnRyYWN0RnVsbERlc2NyaXB0aW9uIjpudWxsLCJpZCI6IjEwMDUzMDAzIiwicHJpY2VUb3RhbCI6MTU5LjAsInRpZXJUeXBlIjpudWxsLCJjb250cmFjdCI6IjEwMDUzMDAzIiwicHJpY2VUb0Rpc3BsYXkiOiIxNTkiLCJwbGFuSWQiOjN9XSwibnVtQW5ub3RhdGlvbnNUb3RhbEN1c3RvbWVyc0xpbWl0IjoxMDAsIm51bU9mSW50ZXJuYWxDb2xsZWN0aW9ucyI6MTAwLCJudW1PZkludGVybmFsQ29sbGVjdGlvblJvd3MiOjUwMCwibWF4QWxsb3dlZFB1Ymxpc2hlZFdpZGdldHMiOm51bGwsIm1heEFsbG93ZWRDdXN0b21UZW1wbGF0ZXMiOm51bGwsIm1heEFsbG93ZWRDdXN0b21TZWN0aW9ucyI6bnVsbCwic2VsZlNlcnZpY2VQbGFuIjp0cnVlfSx7InR5cGUiOiJFTlRFUlBSSVNFIiwiZmVhdHVyZXMiOlsiR29vZ2xlU3BlZWRPcHRpbWl6YXRpb24iLCJQcmVtaXVtSW1hZ2VzIiwiRGV2TW9kZUFjY2VzcyIsIk11bHRpTGFuZ3VhZ2UiLCJVbmxpbWl0ZWRMYW5kaW5nUGFnZXMiLCJTbWFsbFByb2R1Y3RTdG9yZSIsIldMQ2xpZW50QWNjZXNzIiwiV0xTYWxlc01hcmtldGluZ01hdGVyaWFsIiwiQ29uZmlndXJhYmxlUHJpY2VQbGFucyIsIlJvbGVzQW5kUGVybWlzc2lvbnMiLCJDbGllbnRTdGF0c0FuZEFuYWx5dGljcyIsIlRlYW1Bc3NldHNTaGFyaW5nIiwiUHJvRnVsZmlsbG1lbnRDaGFubmVsIiwiRnJlZVNpdGVTU0wiLCJTaXRlQmFja3VwIiwiU2l0ZUV4cG9ydCIsIkFQSUFjY2VzcyIsIldpZGdldEJ1aWxkZXIiLCJDdXN0b21DU1MiLCJEYXRhQmluZGluZyIsIkR5bmFtaWNQYWdlcyIsIkR5bmFtaWNQYWdlc0V4dGVybmFsIiwiU2l0ZUFubm90YXRpb25zIiwiQ29udGVudENvbGxlY3Rpb25Gb3JtIiwiU3NvIiwiWmVuZGVzay1UYWxrLVdlZWtkYXkiLCJaZW5kZXNrLVRhbGstV2Vla2VuZCIsIlplbmRlc2stQ2hhdC1XZWVrZGF5IiwiWmVuZGVzay1DaGF0LVdlZWtlbmQiLCJaZW5kZXNrLUNvbnRhY3RGb3JtIiwiSW1hZ2VDb2xsZWN0aW9ucyIsIkludGVybmFsQ29sbGVjdGlvbnMiLCJFeHRlcm5hbEludGVncmF0aW9uQ29sbGVjdGlvbnMiLCJFeHRlcm5hbENvbGxlY3Rpb25zIiwiTG9jYWxCdXNpbmVzc1NjaGVtYSIsIlB1Ymxpc2hQYWdlIiwiQ3VzdG9tRW1haWxEb21haW4iLCJDdXN0b21XTERvbWFpbiIsIlphcGllckJsb2ciLCJaYXBpZXJDb21tZW50cyIsIlphcGllckZvcm0iLCJaYXBpZXJTdG9yZSIsIlphcGllck5hdGl2ZVN0b3JlIiwiWmFwaWVyTWVtYmVyc2hpcCIsIlphcGllckZvcm1Db250ZW50TGlicmFyeSIsIlphcGllckNvbGxlY3Rpb25zIiwiWmFwaWVyQ3JlYXRlU2l0ZSIsIlphcGllckNyZWF0ZUNsaWVudCIsIkNsaWVudEJpbGxpbmciLCJDdXN0b21CcmFuZGluZyIsIjJmYUZvck93bmVyIiwiMmZhRm9yU3RhZmYiLCJHb29nbGVCdXNpbmVzc1Byb2ZpbGVTeW5jIiwiQUlBZHZhbmNlZENvbnRlbnRHZW5lcmF0aW9uIiwiQUlQYWdlc0FuZFNlY3Rpb25zQ29udGVudEdlbmVyYXRpb24iLCJVbmxpbWl0ZWRDbGllbnRzV2l0aFNpdGVBbm5vdGF0aW9ucyIsIk1jcEJhc2ljIiwiTWNwRnVsbCIsIkNvbnRlbnRDb2xsZWN0aW9uRm9ybUFjY291bnRDdXN0b21pemF0aW9uIiwiQ3VzdG9tQXNzZXRzVGVtcGxhdGVzIiwiQ3VzdG9tQXNzZXRzU2VjdGlvbnMiXSwibnVtT2ZGcmVlU2l0ZXMiOjAsIm51bU9mU3RhZmZVc2VycyI6MTAwMDAwLCJncmFkZSI6MTAsInNpdGVDb250cmFjdHMiOltdLCJudW1Bbm5vdGF0aW9uc1RvdGFsQ3VzdG9tZXJzTGltaXQiOjEwMCwibnVtT2ZJbnRlcm5hbENvbGxlY3Rpb25zIjoxMDAsIm51bU9mSW50ZXJuYWxDb2xsZWN0aW9uUm93cyI6NTAwLCJtYXhBbGxvd2VkUHVibGlzaGVkV2lkZ2V0cyI6bnVsbCwibWF4QWxsb3dlZEN1c3RvbVRlbXBsYXRlcyI6bnVsbCwibWF4QWxsb3dlZEN1c3RvbVNlY3Rpb25zIjpudWxsLCJzZWxmU2VydmljZVBsYW4iOmZhbHNlfSx7InR5cGUiOiJOT05FIiwiZmVhdHVyZXMiOlsiR29vZ2xlU3BlZWRPcHRpbWl6YXRpb24iLCJVbmxpbWl0ZWRMYW5kaW5nUGFnZXMiLCJTbWFsbFByb2R1Y3RTdG9yZSIsIldMU2FsZXNNYXJrZXRpbmdNYXRlcmlhbCIsIkNvbmZpZ3VyYWJsZVByaWNlUGxhbnMiLCJTaXRlQmFja3VwIiwiWmVuZGVzay1Db250YWN0Rm9ybSJdLCJudW1PZkZyZWVTaXRlcyI6MCwibnVtT2ZTdGFmZlVzZXJzIjowLCJncmFkZSI6MCwic2l0ZUNvbnRyYWN0cyI6W10sIm51bUFubm90YXRpb25zVG90YWxDdXN0b21lcnNMaW1pdCI6MCwibnVtT2ZJbnRlcm5hbENvbGxlY3Rpb25zIjowLCJudW1PZkludGVybmFsQ29sbGVjdGlvblJvd3MiOjAsIm1heEFsbG93ZWRQdWJsaXNoZWRXaWRnZXRzIjpudWxsLCJtYXhBbGxvd2VkQ3VzdG9tVGVtcGxhdGVzIjpudWxsLCJtYXhBbGxvd2VkQ3VzdG9tU2VjdGlvbnMiOm51bGwsInNlbGZTZXJ2aWNlUGxhbiI6dHJ1ZX1d";
    if (window.plansService && window.plansService.init) {
        window.plansService.init(window.plansData);
    }
    window._account = window._account || {
        accountOwnerEmail: 'chris@carpediemcg.com',
        email: "ghogshead@skilcraft.com",
        country: '',
        loginNumber: 20,
        isAccountOwnerHubspotUser: true,
        isApiAvailableForAgency: false,
        isUiChangesApproved: false,
        accountOwnerUuid: '8d12bccac17b4e38b6c2e15d209c7d47',
        uuid: "acf02c6f5e684624b32d26d693519e43",
        agencyFreeSites: 8,
        firstName: decodeURIComponent('Grace').replace(/[+]/g, ' '),
        lastName: decodeURIComponent('Hogshead').replace(/[+]/g, ' '),
        lastLoginDate: 1760628453000,
        isActivated: true,
        isInTrial: false,
        planType: "AGENCY",
        isCustomer: true,
        isStaffMember: false,
        permissionGroupAlias: null,
        permissionGroupTitle: null,
        permissionGroupType: null,
        permissionGroupPermissions: [],
        iSiteLimitEnforced: false,
    };
    window._account.permissionsForAtLeastOneSite = {
        ...(window._account.permissionsForAtLeastOneSite || {}),
        CONTENT_LIBRARY: true,
    }
    var dm_account_locale =1,
        accountCreationDate = new Date(
            1752697169000).toISOString(),
        dm_account_codeLocale = "en",
        insideResellerPreview = "false" === "true" || "false" === "false"
            ? false : "false",
        dm_www_home = "",
        dm_account_name = "ghogshead@skilcraft.com",
        dm_account_email = window._account.email,
        dm_account_fullName = "Grace Hogshead",
        dm_account_fbConnected =false,
        dm_site_owner_email = "",
        dm_site_owner_user_name = "",
        isReseller = false,
        isWLReseller = false,
        isWLAffiliate = false,
        accountPlanType = "AGENCY",
        accountPlanResellerType = "RESELLER_WITH_WL_ENABLED",
        isWLSubUser = true,
        isInvoicedReseller = false,
        isStaffMember = false,
        accountOwner = 'chris@carpediemcg.com',
        isDudaProPaymentAccount = false,
        isDudaProInvoicedPaymentAccount = false,
        isFreeTrialPro = false,
        trialDays = 0,
        accountPermissions = {"DASHBOARD_PLAN_COLUMN":false,"SAVE_AS_TEMPLATE":false,"STATS_EMAIL_SELF_SUBSCRIBE":false,"CREATE_SITE":false,"PARTNER_PORTAL":false,"SITE_TYPE_DASHBOARD_INDICATOR":false,"WR":false,"API":false,"DELETE_SITE":false,"MANAGE_STAFF":false,"MOBILE_BFS":false,"ACTIVITY_LOG":false,"EDIT_BRANDING":false,"MANAGE_APP":false,"D_AWARE":false,"FILTER_AND_TAG":false,"ACCOUNT_SETTINGS":false,"SITE_PAYMENTS":false,"SHOW_HELP":true,"MANAGE_CATEGORY":false,"EDITOR_CUSTOM_DOMAIN":false,"WIDGETS_BUILDER_TOOL":false,"CREATE_FLEX_SITES":false,"COMMUNICATION":false,"MANAGE_CUSTOMERS":false,"PAYMENTS":false},
        wasInTrial = false,
        apiStatus = "",
        daysBeforeFreeTrialEnds = -1,
        isSA = false,
        resellerPreviewHost = "http://editor.carpediemcg.com",
        dm_account_support =false,
        dm_site_vertical = "",
        dm_site_ready = 0,
        dm_not_saved = false,
        dm_site_v3 = false,
        dm_account_sadmin =false,
        dm_account_roles = " ADMIN ",
        dm_account_owner_roles = " ADMIN  AGENCY  PRODUCT_OWNER  WL_RESELLER ",
        dm_forced_wr = false,
        dm_account_withPaymentData = false,
        dm_account_id = 824747,
        dm_account_uuid = "acf02c6f5e684624b32d26d693519e43",
        dm_enable_copy = false,
        product_unique_id = '500238600',
        isProductOwner = false,
        productType = "DEFAULT",
        dashboardProductType = "RESELLER",
        adminUrl = '/admin',
        version = "production_5860",
        build = "2025-10-16T12_48_49",
        mapsProvider = "mapbox",
        dev = false,
        isTestOrDevServer =false,
        showPayment = true,
        forceProEditor = false,
        gwtReady = false,
        dm_anonymus_user = false,
        dm_site_alias = null,
        siteUrl = "",
        siteCategory = null,
        siteSubCategory = null,
        siteName = null,
        isAllocatedAlias = false,
        isRecreate = false,
        originalAlias = null,
        dm_autoSiteAliasActive = false,
        dm_logoHereDefault = "//dd-cdn.multiscreensite.com/defaultImages/logohere.png",
        dm_hosting_providers_url = "/editor/nee/mainTabs/redirect/nee.hostingProviders.json",
        dm_clear_plan_selection = true,
        dm_redirect_url_onCreate = "",
        noLandingPage = false,
        createAccountFirst = false,
        dm_nonRewriteUrlExts = ["pdf","doc","docx","xls","xlsx","ppt","pptx","zip","rar","tar.gz","gz","bz2","mp3","wav","wma","wmv","asf","mp4","flv","mpg","avi","gif","jpg","jpeg","bmp","png","tif","ico","exe","dmg","iso","ttf"],
        showPopupStats,
        useNewSelection = false,
        useNewSelectionContext = true,
        isShowTipsPages = true,
        isShowTipsDesign = true,
        isShowWLResellerWelcome = false && uiPerms.D_AWARE && (!isStaffMember),
        isStripePaymentProvider = true,
        isD1TipShowns = {};
    
    isD1TipShowns['FYS'] =  false;
    
    isD1TipShowns['DELETE'] =  false;
    
    isD1TipShowns['GRAB'] =  false;
    
    isD1TipShowns['TOUR'] =  false;
    
    isD1TipShowns['COPY'] =  false;
    
    isD1TipShowns['HIDE_GLOBALLY'] =  false;
    
    isD1TipShowns['BLOG_EDIT'] =  false;
    
    isD1TipShowns['SMART_EDIT_MODE'] =  false;
    
    isD1TipShowns['SMART_RULE_WIZARD'] =  false;
    
    isD1TipShowns['DEVELOPER_MODE'] =  false;
    
    isD1TipShowns['ANCHOR_EDIT'] =  false;
    
    isD1TipShowns['PREVIEW_SHARE_POPUP'] =  false;
    
    isD1TipShowns['ED_ONBOARDING'] =  false;
    
    isD1TipShowns['FREE_TRIAL_PRO'] =  false;
    
    isD1TipShowns['IMAGE_PICKER_ON_BOARDING_FLAG'] =  false;
    
    isD1TipShowns['WELCOME_DUDA_GO'] =  false;
    
    isD1TipShowns['DATA_BINDING'] =  false;
    
    isD1TipShowns['BLOG_ONBOARDING'] =  true;
    
    isD1TipShowns['INTEGRATIONHUB_ONBOARDING'] =  false;
    
    isD1TipShowns['DYNAMIC_PAGES_WELCOME'] =  false;
    
    isD1TipShowns['DYNAMIC_PAGES_BUILD'] =  false;
    
    isD1TipShowns['DYNAMIC_PAGES_FIRST_COLLECTION'] =  false;
    
    isD1TipShowns['DYNAMIC_PAGES_CREATE_TOOLTIP'] =  false;
    
    isD1TipShowns['STORE_PANEL_TOOLTIP'] =  false;
    
    isD1TipShowns['PRODUCT_GALLERY_NOTIFICATION'] =  false;
    
    isD1TipShowns['STORE_PANEL_NEW_STORE'] =  false;
    
    isD1TipShowns['SITE_LIST'] =  false;
    
    isD1TipShowns['GLOBAL_DESIGN_NEW_TEXT_SETTINGS'] =  false;
    
    isD1TipShowns['TEXT_WIDGET_SAVE_TO_GLOBAL_DESIGN'] =  false;
    
    isD1TipShowns['GLOBAL_COLORS_MESSAGE'] =  false;
    
    isD1TipShowns['GLOBAL_COLORS_ONBOARDING'] =  false;
    
    isD1TipShowns['GLOBAL_DESIGN_ONBOARDING'] =  false;
    
    isD1TipShowns['WIDGET_BINDING_TIP_ACCORDION'] =  false;
    
    isD1TipShowns['WIDGET_BINDING_TIP_TEXT'] =  false;
    
    isD1TipShowns['WIDGET_BINDING_TIP_IMAGE'] =  false;
    
    isD1TipShowns['WIDGET_BINDING_TIP_VIDEO'] =  false;
    
    isD1TipShowns['WIDGET_BINDING_TIP_ELEMENT_PANEL'] =  false;
    
    isD1TipShowns['CUSTOM_CONTENT_BINDING_CATALOG'] =  false;
    
    isD1TipShowns['PAGE_BUILDER_ONBOARDING'] =  false;
    

    isNewPricingAccount = true,
        dm_use_only_mdot_in_redirect = false,
        useNewPaymentPage = true,
        accountLocale = 1,
        paymentInProcess = false;
    failedSubscriptions = [],
        isAccountSubscriptionOnFailedState = false,
        isWLResellerPreview = false;

    

    var trialStartDate = -1;
    var trialEndDate = -1;
    var cancelledSubscription = false;

    

    function navigateTo(url) {
        if (window.location.search.includes('dashboardV1=true') || window.hallDashboard) {
            window.parent.location.assign(url);
        } else {
            window.location.assign(url);
        }
    }

    var openSite = function (siteData, options) {
        options = options || {};
        siteData.WEB_PLATFORM = siteData.webPlatform ? siteData.webPlatform.id : "";
        siteData.DM_PRODUCT_ID = siteData.dmProductType;
        dm_forced_wr = $.dmfw.isForceWR(siteData);

        dm_site_alias = siteData.alias;
        dm_site_v3 = siteData.isV3;
        dm_site_ready = 1;
        productType = siteData.dmProductType;

        var urlSuffix = "";
        if (!options.existingSite) {
            urlSuffix = "?isFirstTime=true";
        }

        if (dm_site_v3) {
            var showTaDone = !options.existingSite && Math.random()
                < 0.0;

            var urlToOpen = "/home/site/" + dm_site_alias;

            if (showTaDone) {
                urlToOpen += "?isFirstTime=true";
            }
            if (options.tabToOpen) {
                urlToOpen += "#" + options.tabToOpen;
            }
            setTimeout(function () {
                navigateTo(urlToOpen);
            }, 100);
        } else {
            // basic editor
            var urlToOpen = "/home/editor#edit@templates@" + dm_site_alias;
            setTimeout(function () {
                navigateTo(urlToOpen);
            }, 100);
        }
    };

    function trackNewUrl(siteUrl) {
        var params = { product: 'RESELLER' };
        var ev = dm_anonymus_user ? WR_NEW_USER_ENTER_URL : WR_EXISTING_USER_ENTER_URL;
        dmTrackEvent(ev, "siteUrl", siteUrl, params);
    }

    function customScrollBar() {
        if (navigator.userAgent.indexOf("Mac OS X") == -1) {
            $('body.j15').addClass('pcCustomScrollbar');
        }
    };

    function fbConnectDone(fbLogin) {
        if (fbLogin && fbLogin.ok) {
            if (dm_site_v3) {

                tempCreateAccountOptions = $.extend({ fbconnect: true }, tempCreateAccountOptions);
                $.dmfw.accountCreatedSuccess(tempCreateAccountOptions);
            } else {
                var l = window.location.href;
                var i = l.indexOf('/new');
                var k = l.indexOf('@templates@') + '@templates@'.length;
                var url = l.replace(l.substring(i, k), '/home#edit@design@');
                window.location = url;
            }
        }
    }

    function removeDmSsoParam() {

        var ssoRegex = /dm_sso=($|[^&])+/;
        var pageUrl = location.pathname + location.search + location.hash;

        if (pageUrl.indexOf("dm_sso=") >= 0) {

            pageUrl = pageUrl.replace(/dm_sso=($|[^&])+/, "").replace(/\?$/, "").replace(
                /([?&])&/, "$1");
            history.replaceState(history.state || {}, "", pageUrl);

        }

    }

    
    removeDmSsoParam();
    </script>

<script>
    function isActualTouchDevice() {
        const ua = navigator.userAgent;
        const macTouch = /macintosh/i.test(ua) &&
            /safari/i.test(ua) &&
            'ontouchstart' in window;
        window.isIOS = macTouch;
        return macTouch || !!(ua.match(
            /Android|BlackBerry|iPhone|iPad|iPod|Opera Mini|IEMobile/i));
    }

    function isActualMobileDevice() {
        return !!(navigator.userAgent.match(
            /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i));
    }

    window.isActualTouchDevice = isActualTouchDevice();
    window.isTouchDevice = (window.commonProps && window.commonProps['editor.emulate.touch'])
        || window.isActualTouchDevice;
    window.isMobileDevice = false;
    window.device = 'DESKTOP'.toLowerCase();
</script>
<script>
    $(document).ready(function () {
        const mixPanelDefaultProps = {"userTypeNew":"Customer","segment2020":"SMA","daysBeforeTrialEnds":-1,"layer":"frontend","usePricingSimplification":true,"isManagedAccount":false,"buildForClients":false,"simplificationMigrationDate":1756803386329,"isUsingFreeMonthAgencyCampaign":false,"editorType":"BOTH","in-extended-trial":false,"abtest.trialGenerateSite_feb2025":"outOfTest","abtest.showNewTour":"variationA","abtest.trialNativeStore":"outOfTest","abtest.flexSiteOnBoardingFirstTimeUser_sept2025":"outOfTest","abtest.welcomeDashboard_august2025":"outOfTest","abtest.flexTemplatesReorder":"variationA","abtest.registration2StepFixed_jan2025":"outOfTest","abtest.trialExtension_june2025":"outOfTest","abtest.showWelcomeVideo":"variationA","abtest.nativeStoreFirst":"variationA","abtest.registrationRedesign_june2025":"outOfTest","abtest.pushToAgency_sept2025":"outOfTest","abtest.emptyDashboard_mar2025":"outOfTest"};
        const moreProperties = {
            accountPlan: window.accountPlanType,
            accountCreationDate: new Date(
                1752697169000).toISOString(),
            accountName: window.dm_account_name,
            trialDuration: 0,
            language: 'en',
            accountOwner: 'chris@carpediemcg.com',
            teamPlusPlan: null,
            agencyLightPlan: null,
            isTest: !!window.accountOwner.includes('duda'),
            isBetaGroup: false,
            loginNumber: 20,
            ...mixPanelDefaultProps,
        }
        if (typeof dmTrackIdentity !== "undefined") {
            dmTrackIdentity({
                uuid: 'acf02c6f5e684624b32d26d693519e43',
                name: window.dm_account_name,
                isReseller: window.isWLReseller,
                isCustomer: window.isWLSubUser,
                isProTrial: window.isFreeTrialPro,
                moreProperties
            });
        }
        ;
    });
</script>

<script type="text/javascript" language="javascript">
    $(document).ready(function () {
        var versionUpdate = (new Date()).getTime();
        var script = document.createElement("script");
        script.type = "text/javascript";
        script.src = "/editor/ed/src/common/paymentService.js?v=" + versionUpdate;
        document.body.appendChild(script);
    });
</script>

<link href="https://cdn.quilljs.com/1.3.6/quill.snow.css" rel="stylesheet">
<script type="text/javascript">
    var _RTE_Element = null;
    $(document).ready(function () {
        function ready() {
            $("#topBarPageNav").styleSelectBox($.noop, { width: 150 });
            var isBlogPost = $.dmx.page && $.dmx.page.pageType === "BLOG_POST";
            // render a minimum multilingual dropdown
            if ($.dmx.site.isMultilingual && !isBlogPost) {
                var language = $.dmx.site.languages.currentLanguage;
                var data = [
                    {
                        value: language.pageUrl,
                        imageSrc: language.flagUrl,
                        selected: true
                    }
                ]
                $("#topBarLanguageNav").styleSelectBox($.noop, { width: 70 }, data);
            }
            $("#previewWrapper").show();

            initLoadingPromises();

            $.onefw.init({ preview: false });
        }

        setTimeout(ready, 0);
    });

    var showCreationLoading = function (siteUrl) {
        var url = "/editor/ed/jsp/ed.super.siteLoading.jsp";
        if (siteUrl) {
            url += "?url=" + siteUrl;
        }
        $.dmLoad('.dmShellinnerWrapper', url, function () {
        });
    };

    var DM_SRV_CONST = {
        DOMAIN_LEN: 253
    };

    var analytics_editor = "one";
</script>
<!-- those must be set before the pt.inclide.jspf file -->
<script>
    $.ptConfigs.buildVersion = '?version=2025-10-16T12_48_49';
    $.ptConfigs.isDev = dev;

    var dm_current_editor = "ONE";

    var dm_show_paste = false;
    var dm_enable_copy = true;

</script>
<script src="//static.filestackapi.com/filestack-js/3.27.0/filestack.min.js"></script>
<script>
    var filestackClient = filestack.init("ADRwU0cjTTKCBEFZ1rzSAz");
</script>
<script>
    $("body").toggleClass('touchDevice', !!window.isTouchDevice).toggleClass('ios', !!window.isIOS);
</script>
<!--***************** END COMMON SCRIPTS *************************************-->

<!-- <script src="//cdn.mindtouch.us/f1.js" ></script> -->

<!--***************** END COMMON JS *************************************-->
<!-- Duda One JS Include-->
<script src="https://static.cdn-website.com/mnlt/production/5860/editor/dist/scripts/duda-js-ed-package.min.js" ></script>
<!-- End of Duda One JS Include-->
<script>
  window.dmServices = {
    ajaxGet: function (url, success, fail) {
      var xhr = new XMLHttpRequest();

      xhr.addEventListener('load', function () {
        var isSuccessful = 200 <= xhr.status && xhr.status < 300;
        if (!isSuccessful) {
          fail('server responded with code "' + xhr.status + '". message: ' + xhr.responseText);
          return;
        }

        try {
          success(JSON.parse(xhr.responseText));
        } catch (e) {
          console.warn('could not parse auth response:', e);
          success({});
        }
      });
      xhr.open('GET', url);
      xhr.setRequestHeader('Authorization', this.auth.authentication.value);
      xhr.send();
    },
    loadDeferreds: {},
    auth: {
      listeners: [],
      authentication: false,
      // The minus 0.1 is because we don't want this time to precede the jwt authentication timeout
      autoAuthInterval: 1000 * 60 * 4.9,
      authenticateServices: function (siteAlias) {
        var authUrl = '/api/ms/auth';

        if (siteAlias) {
          authUrl += '?siteAlias=' + siteAlias;
        }

        dmServices.ajaxGet(
            authUrl,
            function (authDetails) {
              this.authentication = authDetails;
              this.listeners.forEach(function (listener) {
                listener(this.authentication);
              }.bind(this));
            }.bind(this),
            function (errorMessage) {
              console.error(errorMessage);
              this.authentication = false;
            }.bind(this)
        );
      },
      onAuth: function (listener) {
        this.listeners.push(listener);
        listener(this.authentication);
        return function () {
          this.listeners = this.listeners.filter(function (fn) {
            return fn !== listener;
          });
        }.bind(this);
      }
    }
  };

  // TODO -> it's a copy-paste that should be extracted to one place
  // if developer sets product prop to sth huge (like 30 days) to reuse it in
  // postman, result of 1000 * 60 * 100_000 will cause 32-bit int overflow and
  // server will be spammed with refresh requests
  const MAX_REFRESH_PERIOD_MINUTES = 30;
  function tokenRefreshPeriod() {
      const commonPropsTimeout = 10
      // The minus 0.1 is because we don't want this time to precede
      // the jwt authentication timeout
      const expirationTimeout = commonPropsTimeout / 2 - 0.1;
      const refreshPeriodInMinutes = Math.min(expirationTimeout, MAX_REFRESH_PERIOD_MINUTES);
      return 1000 * 60 * refreshPeriodInMinutes;
  }
</script>
<!-- Hang Site Context -->
        <script>
            
            var siteAlias = "102ec7d9";
            dmServices.auth.authenticateServices(siteAlias);
            
            dmServices.loadDeferreds.annotations = new Deferred();
            (function () {
                dmServices.auth.onAuth(authenticationSuccessful);

                function authenticationSuccessful(authDetails) {
                    if (!authDetails) {
                        return;
                    }
                    if (document.querySelector('#site-annotations-script-tag')) {
                        window.annotations.default.authorize(authDetails.value);
                        return;
                    }

                    dmServices.ajaxGet(
                        '/ms/annotations/properties',
                        clientPropsReceived.bind(this, authDetails),
                        function () {
                        }
                    );
                }

                function clientPropsReceived(authDetails, clientProps) {
                    var script = document.createElement('script');
                    script.id = 'site-annotations-script-tag';
                    script.addEventListener('load', () => {
                        dmServices.loadDeferreds.annotations.resolve({
                            authToken: authDetails.value,
                            maxCommentLength: parseInt(clientProps['comment.text.length.max'], 10),
                            clientProps: clientProps
                        });
                        
                    });
                    script.async = true;
                    script.src = ''
                        || clientProps['annotations.resource.url'];
                    document.body.appendChild(script);
                }
            }());
            

            window._microFrontendSrcs = {"booking":"https://ms-cdn.multiscreensite.com/booking/4154/res/js/booking.js","integrationhub":"https://ms-cdn.multiscreensite.com/integrationhub/3804/res/js/integrationhub.js","auth":"https://ms-cdn.multiscreensite.com/auth/1009/res/js/auth.js","collections":"https://ms-cdn.multiscreensite.com/collections/3058/res/js/collections.js","client-billing":"https://ms-cdn.multiscreensite.com/client-billing/1035/res/js/client-billing.js","ai-core":"https://ms-cdn.multiscreensite.com/ai-core/3813/res/js/ai-core.js","diyflow":"https://ms-cdn.multiscreensite.com/diyflow/1342/res/js/diyflow.js","branding":"https://ms-cdn.multiscreensite.com/branding/531/res/js/branding.js","domains":"https://ms-cdn.multiscreensite.com/domains/3367/res/js/domains.js","snipcart-store":"https://ms-cdn.multiscreensite.com/snipcart-store/609/res/js/snipcart-store.js","membership":"https://ms-cdn.multiscreensite.com/membership/1848/res/js/membership.js","dashboards":"https://ms-cdn.multiscreensite.com/dashboards/1477/res/js/dashboards.js"};
            var context = {"supported_languages":[{"clientId":51,"languageName":"Afrikaans","countryCode":"za","languageCode":"af","localeCode":"af","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/za.png","isEnabled":true,"countryName":"South Africa"},{"clientId":78,"languageName":"Azərbaycan dili","countryCode":"az","languageCode":"az","localeCode":"az","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/az.png","isEnabled":true,"countryName":"Azerbaijan"},{"clientId":42,"languageName":"Bahasa Indonesia","countryCode":"id","languageCode":"id","localeCode":"id","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/id.png","isEnabled":true,"countryName":"Indonesia"},{"clientId":74,"languageName":"Bahasa Melayu","countryCode":"ms","languageCode":"ms","localeCode":"ms","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ms.png","isEnabled":true,"countryName":"Malay"},{"clientId":70,"languageName":"Cymraeg","countryCode":"wls","languageCode":"cy","localeCode":"cy","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/wls.png","isEnabled":true,"countryName":"Wales"},{"clientId":17,"languageName":"Dansk","countryCode":"dk","languageCode":"da","localeCode":"da","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/dk.png","isEnabled":true,"countryName":"Denmark"},{"clientId":6,"languageName":"Deutsch","countryCode":"de","languageCode":"de","localeCode":"de","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/de.png","isEnabled":true,"countryName":"Germany"},{"clientId":84,"languageName":"Deutsch","countryCode":"at","languageCode":"de","localeCode":"de-at","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/at.png","isEnabled":true,"countryName":"Austria"},{"clientId":1,"languageName":"English","countryCode":"us","languageCode":"en","localeCode":"en","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/us.png","isEnabled":true,"countryName":"USA"},{"clientId":8,"languageName":"English","countryCode":"gb","languageCode":"en","localeCode":"en-gb","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/gb.png","isEnabled":true,"countryName":"UK"},{"clientId":23,"languageName":"English","countryCode":"au","languageCode":"en","localeCode":"en-au","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/au.png","isEnabled":true,"countryName":"Australia"},{"clientId":24,"languageName":"English","countryCode":"ca","languageCode":"en","localeCode":"en-ca","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ca.png","isEnabled":true,"countryName":"Canada"},{"clientId":86,"languageName":"English","countryCode":"ie","languageCode":"en","localeCode":"en-ie","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ie.png","isEnabled":true,"countryName":"Ireland"},{"clientId":88,"languageName":"English","countryCode":"be","languageCode":"en","localeCode":"en-be","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/be.png","isEnabled":true,"countryName":"Belgium"},{"clientId":2,"languageName":"Español","countryCode":"es","languageCode":"es","localeCode":"es","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/es.png","isEnabled":true,"countryName":"Spain"},{"clientId":26,"languageName":"Español","countryCode":"ar","languageCode":"es","localeCode":"es-ar","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ar.png","isEnabled":true,"countryName":"Argentina"},{"clientId":27,"languageName":"Español","countryCode":"cl","languageCode":"es","localeCode":"es-cl","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/cl.png","isEnabled":true,"countryName":"Chile"},{"clientId":28,"languageName":"Español","countryCode":"co","languageCode":"es","localeCode":"es-co","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/co.png","isEnabled":true,"countryName":"Columbia"},{"clientId":29,"languageName":"Español","countryCode":"cr","languageCode":"es","localeCode":"es-cr","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/cr.png","isEnabled":true,"countryName":"Costa Rica"},{"clientId":30,"languageName":"Español","countryCode":"mx","languageCode":"es","localeCode":"es-mx","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/mx.png","isEnabled":true,"countryName":"Mexico"},{"clientId":77,"languageName":"Euskera","countryCode":"es-eu","languageCode":"eu","localeCode":"eu","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/es-eu.png","isEnabled":true,"countryName":"Galicia"},{"clientId":71,"languageName":"Filipino","countryCode":"ph","languageCode":"tl","localeCode":"tl","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ph.png","isEnabled":true,"countryName":"Philippines "},{"clientId":5,"languageName":"Français","countryCode":"fr","languageCode":"fr","localeCode":"fr","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/fr.png","isEnabled":true,"countryName":"France"},{"clientId":35,"languageName":"Français","countryCode":"ca","languageCode":"fr","localeCode":"fr-ca","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ca.png","isEnabled":true,"countryName":"Canada"},{"clientId":90,"languageName":"Français","countryCode":"be","languageCode":"fr","localeCode":"fr-be","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/be.png","isEnabled":true,"countryName":"Belgium"},{"clientId":87,"languageName":"Gaeilge","countryCode":"ie","languageCode":"ga","localeCode":"ga-ie","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ie.png","isEnabled":true,"countryName":"Ireland"},{"clientId":76,"languageName":"Galician","countryCode":"es-gl","languageCode":"gl","localeCode":"gl","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/es-gl.png","isEnabled":true,"countryName":"Basque"},{"clientId":9,"languageName":"Italiano","countryCode":"it","languageCode":"it","localeCode":"it","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/it.png","isEnabled":true,"countryName":"Italy"},{"clientId":61,"languageName":"Kiswahili","countryCode":"tz","languageCode":"sw","localeCode":"sw","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/tz.png","isEnabled":true,"countryName":"Tanzania"},{"clientId":47,"languageName":"Latviešu","countryCode":"lv","languageCode":"lv","localeCode":"lv","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/lv.png","isEnabled":true,"countryName":"Latvia"},{"clientId":49,"languageName":"Malti","countryCode":"mt","languageCode":"mt","localeCode":"mt","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/mt.png","isEnabled":true,"countryName":"Malta"},{"clientId":80,"languageName":"Māori","countryCode":"nz","languageCode":"mi","localeCode":"mi","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/nz.png","isEnabled":true,"countryName":"New Zealand"},{"clientId":10,"languageName":"Nederlands","countryCode":"nl","languageCode":"nl","localeCode":"nl","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/nl.png","isEnabled":true,"countryName":"Netherlands"},{"clientId":89,"languageName":"Nederlands","countryCode":"be","languageCode":"nl","localeCode":"nl-be","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/be.png","isEnabled":true,"countryName":"Belgium"},{"clientId":85,"languageName":"Português","countryCode":"pt","languageCode":"pt","localeCode":"pt-pt","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/pt.png","isEnabled":true,"countryName":"Portugal"},{"clientId":33,"languageName":"Suomi","countryCode":"fi","languageCode":"fi","localeCode":"fi","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/fi.png","isEnabled":true,"countryName":"Finland"},{"clientId":60,"languageName":"Svenska","countryCode":"se","languageCode":"sv","localeCode":"sv","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/se.png","isEnabled":true,"countryName":"Sweden"},{"clientId":66,"languageName":"Ti\u1EBFng Vi\u1EC7t","countryCode":"vn","languageCode":"vi","localeCode":"vi","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/vn.png","isEnabled":true,"countryName":"Viet Nam"},{"clientId":7,"languageName":"Türkçe","countryCode":"tr","languageCode":"tr","localeCode":"tr","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/tr.png","isEnabled":true,"countryName":"Turkey"},{"clientId":14,"languageName":"bosanski","countryCode":"ba","languageCode":"bs","localeCode":"bs-ba","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ba.png","isEnabled":true,"countryName":"Bosnia and Herzegovina"},{"clientId":15,"languageName":"català","countryCode":"cat","languageCode":"ca","localeCode":"ca","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/cat.png","isEnabled":true,"countryName":"Catalonia,"},{"clientId":31,"languageName":"eesti","countryCode":"ee","languageCode":"et","localeCode":"et","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ee.png","isEnabled":true,"countryName":"Estonia"},{"clientId":39,"languageName":"hrvatski","countryCode":"hr","languageCode":"hr","localeCode":"hr","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/hr.png","isEnabled":true,"countryName":"Croatia"},{"clientId":46,"languageName":"lietuvių","countryCode":"lt","languageCode":"lt","localeCode":"lt","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/lt.png","isEnabled":true,"countryName":"Lithuania"},{"clientId":40,"languageName":"magyar","countryCode":"hu","languageCode":"hu","localeCode":"hu","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/hu.png","isEnabled":true,"countryName":"Hungary"},{"clientId":50,"languageName":"norsk","countryCode":"no","languageCode":"nb","localeCode":"nb","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/no.png","isEnabled":true,"countryName":"Norway"},{"clientId":53,"languageName":"polski","countryCode":"pl","languageCode":"pl","localeCode":"pl","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/pl.png","isEnabled":true,"countryName":"Poland"},{"clientId":4,"languageName":"português","countryCode":"pt","languageCode":"pt","localeCode":"pt","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/pt.png","isEnabled":true,"countryName":"Portugal"},{"clientId":54,"languageName":"português","countryCode":"br","languageCode":"pt","localeCode":"pt-br","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/br.png","isEnabled":true,"countryName":"Brazil"},{"clientId":55,"languageName":"română","countryCode":"ro","languageCode":"ro","localeCode":"ro","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ro.png","isEnabled":true,"countryName":"Romania"},{"clientId":59,"languageName":"shqip","countryCode":"al","languageCode":"sq","localeCode":"sq","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/al.png","isEnabled":true,"countryName":"Albania"},{"clientId":57,"languageName":"slovenčina","countryCode":"sk","languageCode":"sk","localeCode":"sk","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/sk.png","isEnabled":true,"countryName":"Slovakia"},{"clientId":58,"languageName":"slovenščina","countryCode":"si","languageCode":"sl","localeCode":"sl","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/si.png","isEnabled":true,"countryName":"Slovenia"},{"clientId":43,"languageName":"íslenska","countryCode":"is","languageCode":"is","localeCode":"is","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/is.png","isEnabled":true,"countryName":"Iceland"},{"clientId":16,"languageName":"čeština","countryCode":"cz","languageCode":"cs","localeCode":"cs","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/cz.png","isEnabled":true,"countryName":"Czech Republic"},{"clientId":22,"languageName":"Ελληνικά","countryCode":"gr","languageCode":"el","localeCode":"el","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/gr.png","isEnabled":true,"countryName":"Greece"},{"clientId":12,"languageName":"Беларуская","countryCode":"by","languageCode":"be","localeCode":"be","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/by.png","isEnabled":true,"countryName":"Belarus"},{"clientId":81,"languageName":"Македонски","countryCode":"mk","languageCode":"mk","localeCode":"mk","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/mk.png","isEnabled":true,"countryName":"Macedonia"},{"clientId":48,"languageName":"Монгол","countryCode":"mn","languageCode":"mn","localeCode":"mn","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/mn.png","isEnabled":true,"countryName":"Mongolia"},{"clientId":75,"languageName":"Србија","countryCode":"rs","languageCode":"sr","localeCode":"sr-rs","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/rs.png","isEnabled":true,"countryName":"Serbia"},{"clientId":65,"languageName":"Українська","countryCode":"ua","languageCode":"uk","localeCode":"uk","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ua.png","isEnabled":true,"countryName":"Ukraine"},{"clientId":13,"languageName":"български","countryCode":"bg","languageCode":"bg","localeCode":"bg","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/bg.png","isEnabled":true,"countryName":"Bulgaria"},{"clientId":56,"languageName":"русский","countryCode":"ru","languageCode":"ru","localeCode":"ru","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ru.png","isEnabled":true,"countryName":"Russia"},{"clientId":41,"languageName":"հայերեն","countryCode":"am","languageCode":"hy","localeCode":"hy","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/am.png","isEnabled":true,"countryName":"Armenia"},{"clientId":37,"languageName":"עברית","countryCode":"il","languageCode":"he","localeCode":"he","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/il.png","isEnabled":true,"countryName":"Israel"},{"clientId":11,"languageName":"العربية\u200E","countryCode":"sa","languageCode":"ar","localeCode":"ar","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/sa.png","isEnabled":true,"countryName":"Saudi Arabia"},{"clientId":32,"languageName":"فارسی","countryCode":"ir","languageCode":"fa","localeCode":"fa","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ir.png","isEnabled":true,"countryName":"Iran"},{"clientId":79,"languageName":"پښتو","countryCode":"af","languageCode":"ps","localeCode":"ps","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/af.png","isEnabled":true,"countryName":"Afghanistan"},{"clientId":38,"languageName":"हिन्दी","countryCode":"in","languageCode":"hi","localeCode":"hi","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/in.png","isEnabled":true,"countryName":"India"},{"clientId":52,"languageName":"ਪੰਜਾਬੀ","countryCode":"in","languageCode":"pa","localeCode":"pa","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/in.png","isEnabled":true,"countryName":"India"},{"clientId":63,"languageName":"தமிழ்","countryCode":"lk","languageCode":"ta","localeCode":"ta","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/lk.png","isEnabled":true,"countryName":"Sri Lanka"},{"clientId":64,"languageName":"ไทย","countryCode":"th","languageCode":"th","localeCode":"th","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/th.png","isEnabled":true,"countryName":"Thailand"},{"clientId":73,"languageName":"\u10E5\u10D0\u10E0\u10D7\u10E3\u10DA\u10D8","countryCode":"ka","languageCode":"ka","localeCode":"ka","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/ka.png","isEnabled":true,"countryName":"Georgian"},{"clientId":83,"languageName":"\u1797\u17B6\u179F\u17B6\u1781\u17D2\u1798\u17C2\u179A","countryCode":"kh","languageCode":"km","localeCode":"km","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/kh.png","isEnabled":true,"countryName":"Cambodia"},{"clientId":3,"languageName":"\u65E5\u672C\u8A9E","countryCode":"jp","languageCode":"ja","localeCode":"ja","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/jp.png","isEnabled":true,"countryName":"Japan"},{"clientId":67,"languageName":"\u7B80\u4F53\u4E2D\u6587","countryCode":"cn","languageCode":"zh","localeCode":"zh","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/cn.png","isEnabled":true,"countryName":"China"},{"clientId":72,"languageName":"\u7E41\u9AD4\u4E2D\u6587","countryCode":"cn","languageCode":"zh-tw","localeCode":"zh-tw","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/tw.png","isEnabled":true,"countryName":"China"},{"clientId":82,"languageName":"\u7E41\u9AD4\u4E2D\u6587","countryCode":"hk","languageCode":"zh-tw","localeCode":"zh-hk","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/hk.png","isEnabled":true,"countryName":"Hong Kong"},{"clientId":45,"languageName":"\uD55C\uAD6D\uC5B4","countryCode":"kr","languageCode":"ko","localeCode":"ko","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/kr.png","isEnabled":true,"countryName":"Republic of Korea"}],"blogStatus":"IDLE","siteRuntimeFlags":{"APP_INSTALL_BANNER":false,"RESPONSIVE_TABLET":true,"FAST_MIGRATION":false,"PAGE_DL_BLOBS_IN_DYNAMODB":false,"HAS_FLEX":true,"USE_GDPR_COOKIE_MSG":true,"CUSTOM_WIDGET_PREVIEW":false,"HAS_DUDA_COMMERCE":false,"CUSTOM_DOMAIN_CONNECTED":true,"SDL_BLOBS_IN_DYNAMODB":false,"GENERATE_SEO_SCHEMA":true,"HAS_SECURED_STATIC_RESOURCES":false,"PREMIUM_SITES_FOR_FREE_TRILOBITED":false,"NO_DEFAULT_DOMAIN_REDIRECT":false,"FLEX_SITE":false,"NO_INDEX":false,"PAGE_DD_BLOBS_IN_DYNAMODB":false,"FAST_MIGRATION2_HIBU_FIX":false,"USE_SITE_FONT_MANAGEMENT":true,"STRUCTURED_NAV":true,"USE_CUSTOMIZED_COOKIE_MSG":true,"DISABLE_FONT_SWAP":true,"CANONICAL_AND_PRIMARY_AS_IS":false,"FONTS_CONTAINS_ITALIC_FONT":false,"YELL_FM_REMOVE_ANALYTICS_SCRIPT_FIX":false,"FORCE_HTTPS":false,"DM_MOBILE_RESTRICT_LIVEURL":false,"HAS_NEW_HAMBURGER_ICON":false,"FAST_MIGRATION2_EDITABLE":false,"HTML_4":false,"DO_NOT_GEN_SSL":true,"PWA":true,"ALREADY_FATWIRE_FOOTER_LINKS":false,"HAS_SNIPCART_ACCOUNT":false,"TEXT_EDITOR_MIGRATION":true,"FAST_MIGRATION_HIBU_MOBILE":false,"TEXT_EDITOR_AUTO_MIGRATION":false,"RETURN_X_FRAME_OPTIONS_HEADERS_OFF":false,"FULLY_MEMBERSHIP_GUARDED":false,"DIY_SITE":false,"PROCESSED_FOR_ZOMBIE_PAGES":false,"MULTILINGUAL_NO_URL_RULES":false,"IS_MULTILINGUAL_SITE":false,"CREATED_USING_CLEAN_TEXT_MODIFIER":true,"PWA_CACHE_PAGES":false,"PAYMENT_VALIDATOR_SKIP":false,"DONT_SERVE_PAGESPEED_OPTIMIZED_VERSION":false,"FAST_MIGRATION2":false,"DISABLE_LAZY_LOADING":false,"DISABLE_TRACKING":true,"RETURN_X_FRAME_OPTIONS_HEADERS_ON":false,"DEX_MIGRATION_HTTPS_FIX":false},"sso":{"ts":1760630236192,"urlParams":[{"name":"dm_sso","value":"0!eyJ2ZXJzaW9uIjowLCJyZXFVdWlkIjoiYjU0MGFkMzNmMzExNGJhYTk2MTEwYTI4MzE3YTFlMWQiLCJjbGllbnRBZGRyZXNzIjoiNzQuODMuMjIxLjI1In0"},{"name":"continueOnAuthOK","value":"true"}],"sessionID":"3036E8AEA107B4D6989589785E5BD7BB"},"isFastMigration2Site":false,"site_fonts":{"fonts":[{"uid":"0f9726ca","fontType":1,"name":"Arial","weights":[],"defaultFont":true},{"uid":"2b482b74","fontType":1,"name":"Helvetica","weights":[],"defaultFont":true},{"uid":"d570a26a","fontType":1,"name":"Tahoma","weights":[],"defaultFont":true},{"uid":"5dbfde6e","fontType":1,"name":"Georgia","weights":[],"defaultFont":true},{"uid":"6cc6b332","fontType":2,"name":"Alegreya","weights":[{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"342b3e48","fontType":2,"name":"Amiri","weights":[{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"0cd43085","fontType":2,"name":"Barlow","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"e2dabca0","fontType":2,"name":"Bebas Neue","weights":[],"defaultFont":true},{"uid":"37600e96","fontType":2,"name":"Be Vietnam","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"97949373","fontType":2,"name":"Comfortaa","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"d1d9d3d8","fontType":2,"name":"Dancing Script","weights":[{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"3d637b25","fontType":2,"name":"DM Sans","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null},{"weight":1000,"webUrl":null}],"defaultFont":true},{"uid":"2ca0c5eb","fontType":2,"name":"DM Serif Display","weights":[],"defaultFont":true},{"uid":"e38ccc49","fontType":2,"name":"Droid Sans","weights":[{"weight":400,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"2405afeb","fontType":2,"name":"Droid Sans Mono","weights":[{"weight":400,"webUrl":null}],"defaultFont":true},{"uid":"161e6f18","fontType":2,"name":"Droid Serif","weights":[{"weight":400,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"ac95fc2b","fontType":2,"name":"Epilogue","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"75f91638","fontType":2,"name":"Fjalla One","weights":[],"defaultFont":true},{"uid":"ea647f2d","fontType":2,"name":"Heebo","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"3761a22e","fontType":2,"name":"Inter","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"f5585f9b","fontType":2,"name":"Jost","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"89e510a3","fontType":2,"name":"Lato","weights":[{"weight":100,"webUrl":null},{"weight":300,"webUrl":null},{"weight":700,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"6bf36c81","fontType":2,"name":"Lora","weights":[{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"dda08ba7","fontType":2,"name":"Merriweather","weights":[{"weight":300,"webUrl":null},{"weight":700,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"d0018930","fontType":2,"name":"Montserrat","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"de19b68e","fontType":2,"name":"Muli","weights":[{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"6a23d052","fontType":2,"name":"Noto Sans","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"84f084db","fontType":2,"name":"Noto Serif","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"79ac8593","fontType":2,"name":"Nunito Sans","weights":[{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null},{"weight":1000,"webUrl":null}],"defaultFont":true},{"uid":"681e5285","fontType":2,"name":"Old Standard TT","weights":[{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"d85da69c","fontType":2,"name":"Open Sans","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null}],"defaultFont":true},{"uid":"f3f34d18","fontType":2,"name":"Oswald","weights":[{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"cf5ead48","fontType":2,"name":"Playfair Display","weights":[{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"166e8dc3","fontType":2,"name":"Petit Formal Script","weights":[],"defaultFont":true},{"uid":"ee8946d1","fontType":2,"name":"Poppins","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"453c85a7","fontType":2,"name":"Prata","weights":[],"defaultFont":true},{"uid":"696ae0b3","fontType":2,"name":"Prompt","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"ac130e00","fontType":2,"name":"PT Sans","weights":[{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"a8fe654b","fontType":2,"name":"Quicksand","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"fca8f296","fontType":2,"name":"Raleway","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"edb7888c","fontType":2,"name":"Roboto","weights":[{"weight":100,"webUrl":null},{"weight":300,"webUrl":null},{"weight":500,"webUrl":null},{"weight":700,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"ac3d6c13","fontType":2,"name":"Roboto Mono","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"aa4163de","fontType":2,"name":"Roboto Slab","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"8d4bddaa","fontType":2,"name":"Rubik","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"4c85e84a","fontType":2,"name":"Rock Salt","weights":[],"defaultFont":true},{"uid":"a227d802","fontType":2,"name":"Shadows Into Light","weights":[],"defaultFont":true},{"uid":"9ad4b46f","fontType":2,"name":"Slabo 27px","weights":[],"defaultFont":true},{"uid":"b14016dd","fontType":2,"name":"Source Sans Pro","weights":[{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"5e24c3b7","fontType":2,"name":"Spartan","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"602d35c8","fontType":2,"name":"Sulphur Point","weights":[{"weight":300,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"88f1c3c1","fontType":2,"name":"Ubuntu","weights":[{"weight":300,"webUrl":null},{"weight":500,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"a08bbbbf","fontType":2,"name":"Vidaloka","weights":[],"defaultFont":true},{"uid":"a67f4e89","fontType":2,"name":"Work Sans","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"74db9b3a","fontType":2,"name":"Yeseva One","weights":[],"defaultFont":true},{"uid":"dd34ba08","fontType":1,"name":"Verdana","weights":[],"defaultFont":true},{"uid":"05237a0b","fontType":2,"name":"Mulish","weights":[{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null},{"weight":1000,"webUrl":null}],"defaultFont":true},{"uid":"3fbd6b4d","fontType":2,"name":"Red Rose","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"b64f7878","fontType":2,"name":"Abril Fatface","weights":[],"defaultFont":true},{"uid":"406bbf70","fontType":2,"name":"Fraunces","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"156e1da2","fontType":2,"name":"Albert Sans","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"5c015f9c","fontType":2,"name":"Libre Baskerville","weights":[{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"b7853c50","fontType":2,"name":"Space Grotesk","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"c89720ff","fontType":2,"name":"Outfit","weights":[{"weight":100,"webUrl":null},{"weight":200,"webUrl":null},{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"a78e06bb","fontType":2,"name":"Aboreto","weights":[],"defaultFont":true},{"uid":"a3319cb6","fontType":2,"name":"Arapey","weights":[],"defaultFont":true},{"uid":"70ef6fb8","fontType":2,"name":"Questrial","weights":[],"defaultFont":true},{"uid":"effb2424","fontType":2,"name":"Marcellus","weights":[],"defaultFont":true},{"uid":"9397c5e9","fontType":2,"name":"Red Hat Display","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null},{"weight":800,"webUrl":null},{"weight":900,"webUrl":null}],"defaultFont":true},{"uid":"0b2777f6","fontType":2,"name":"Red Hat Text","weights":[{"weight":300,"webUrl":null},{"weight":400,"webUrl":null},{"weight":500,"webUrl":null},{"weight":600,"webUrl":null},{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"7a1010ac","fontType":2,"name":"Quattrocento Sans","weights":[{"weight":700,"webUrl":null}],"defaultFont":true},{"uid":"66491340","fontType":2,"name":"Hedvig Letters Serif","weights":[],"defaultFont":true}]},"disableShellLeftPanel":false,"isFastMigrationSite":false,"membership_pages":[],"apps":{"libApps":[{"id":"102","description":"Set an Appointment"}]},"flexContext":{},"hasLogo":true,"native_store":{},"isManagedFonts":true,"site_nav":[{"itemTitle":"Home","itemUrl":"/site/102ec7d9/","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101691684_item","pageAlias":"home","pageID":8268048,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101691684","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Copy of Home","itemUrl":"/site/102ec7d9/copy-of-home","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101473981_item","pageAlias":"copy-of-home","pageID":17394980,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101473981","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Capabilities","itemUrl":"/site/102ec7d9/capabilities","depth":0,"subNav":[{"itemTitle":"Copy of Capabilities","itemUrl":"/site/102ec7d9/copy-of-capabilities","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101549674_item","pageAlias":"copy-of-capabilities","pageID":17607825,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101549674","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Advanced Manufacturing","itemUrl":"/site/102ec7d9/advanced-manufacturing","depth":1,"subNav":[{"itemTitle":"Skilcraft Solutions Cell","itemUrl":"/site/102ec7d9/skilcraft-solutions-cell","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101231027_item","pageAlias":"skilcraft-solutions-cell","pageID":17094632,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101231027","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Spot Welding","itemUrl":"/site/102ec7d9/spot-welding","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101279373_item","pageAlias":"spot-welding","pageID":4945789,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101279373","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"TIG Welding","itemUrl":"/site/102ec7d9/tig-welding","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101769666_item","pageAlias":"tig-welding","pageID":4945797,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101769666","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Laser Punching","itemUrl":"/site/102ec7d9/laser-punching-cutting","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101128841_item","pageAlias":"laser-punching-cutting","pageID":4945802,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101128841","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Hydroforming","itemUrl":"/site/102ec7d9/hydroforming","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101399664_item","pageAlias":"hydroforming","pageID":4945788,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101399664","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Roll Forming and Expanding","itemUrl":"/site/102ec7d9/roll-forming-and-expanding","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101581127_item","pageAlias":"roll-forming-and-expanding","pageID":4945815,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101581127","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Brazing","itemUrl":"/site/102ec7d9/brazing","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101233628_item","pageAlias":"brazing","pageID":4945794,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101233628","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Forming","itemUrl":"/site/102ec7d9/forming","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101563250_item","pageAlias":"forming","pageID":4945774,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101563250","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Machining","itemUrl":"/site/102ec7d9/machining","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101604325_item","pageAlias":"machining","pageID":4945773,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101604325","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Assembly","itemUrl":"/site/102ec7d9/assembly","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101630847_item","pageAlias":"assembly","pageID":4945811,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101630847","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Quality","itemUrl":"/site/102ec7d9/quality","depth":2,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101884884_item","pageAlias":"quality","pageID":4945784,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101884884","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false}],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101687150_item","pageAlias":"advanced-manufacturing","pageID":4945808,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101687150","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"NPI Services","itemUrl":"/site/102ec7d9/npi-services","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101892213_item","pageAlias":"npi-services","pageID":4945793,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101892213","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Manufacturing Engineering","itemUrl":"/site/102ec7d9/manufacturing_engineering","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup01010121806_item","pageAlias":"manufacturing_engineering","pageID":4945776,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_01010121806","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Program Management","itemUrl":"/site/102ec7d9/program-management","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup01010145544_item","pageAlias":"program-management","pageID":4945817,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_01010145544","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Design for Manufacturability","itemUrl":"/site/102ec7d9/review-for-manufacturability","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101286512_item","pageAlias":"review-for-manufacturability","pageID":4945792,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101286512","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Materials","itemUrl":"/site/102ec7d9/materials","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101240509_item","pageAlias":"materials","pageID":4945801,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101240509","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false}],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101436323_item","pageAlias":"capabilities","pageID":4945791,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101436323","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Industries","itemUrl":"/site/102ec7d9/industries","depth":0,"subNav":[{"itemTitle":"Copy of Industries","itemUrl":"/site/102ec7d9/copy-of-industries","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101608449_item","pageAlias":"copy-of-industries","pageID":17740489,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101608449","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Aerospace Engines","itemUrl":"/site/102ec7d9/aerospace-engines","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101426318_item","pageAlias":"aerospace-engines","pageID":4945796,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101426318","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Aerostructures","itemUrl":"/site/102ec7d9/aerostructures","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101579490_item","pageAlias":"aerostructures","pageID":4945805,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101579490","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Avionics and Missions","itemUrl":"/site/102ec7d9/avionics-and-missions","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101354525_item","pageAlias":"avionics-and-missions","pageID":4945809,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101354525","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Space","itemUrl":"/site/102ec7d9/space","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101811770_item","pageAlias":"space","pageID":4945804,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101811770","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Power Generation","itemUrl":"/site/102ec7d9/power-generation","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101859423_item","pageAlias":"power-generation","pageID":4945778,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101859423","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Alternative Energy","itemUrl":"/site/102ec7d9/alternative-energy","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101568926_item","pageAlias":"alternative-energy","pageID":4945806,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101568926","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Medical Devices","itemUrl":"/site/102ec7d9/medical-devices","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101448831_item","pageAlias":"medical-devices","pageID":4945807,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101448831","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Military","itemUrl":"/site/102ec7d9/military","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101649838_item","pageAlias":"military","pageID":4945775,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101649838","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false}],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101927501_item","pageAlias":"industries","pageID":4945782,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101927501","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"About","itemUrl":"/site/102ec7d9/about","depth":0,"subNav":[{"itemTitle":"Leadership","itemUrl":"/site/102ec7d9/leadership","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101815445_item","pageAlias":"leadership","pageID":4945783,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101815445","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Our Commitment to You","itemUrl":"/site/102ec7d9/our-commitment-to-you","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101952998_item","pageAlias":"our-commitment-to-you","pageID":4945772,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101952998","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Supply Chain","itemUrl":"/site/102ec7d9/supply-chain","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101606787_item","pageAlias":"supply-chain","pageID":4945800,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101606787","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Affiliates","itemUrl":"/site/102ec7d9/affiliates","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup01010144983_item","pageAlias":"affiliates","pageID":4945803,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_01010144983","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Certifications","itemUrl":"/site/102ec7d9/certifications","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101981743_item","pageAlias":"certifications","pageID":4945814,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101981743","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"History","itemUrl":"/site/102ec7d9/history","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101469920_item","pageAlias":"history","pageID":4945786,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101469920","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Blog","itemUrl":"/site/102ec7d9/blog","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101257750_item","pageAlias":"blog","pageID":8423846,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101257750","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false}],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101391823_item","pageAlias":"about","pageID":4945798,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101391823","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Careers","itemUrl":"/site/102ec7d9/careers","depth":0,"subNav":[{"itemTitle":"Current Opportunities","itemUrl":"/site/102ec7d9/current-opportunities","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101776268_item","pageAlias":"current-opportunities","pageID":4945795,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101776268","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Working at Skilcraft","itemUrl":"/site/102ec7d9/working-at-skilcraft","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101667202_item","pageAlias":"working-at-skilcraft","pageID":4945780,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101667202","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Why Choose a Career in the Trades","itemUrl":"/site/102ec7d9/why-choose-a-career-in-the-trades","depth":1,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101164426_item","pageAlias":"why-choose-a-career-in-the-trades","pageID":4945769,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101164426","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false}],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101435357_item","pageAlias":"careers","pageID":4945777,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101435357","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Contact","itemUrl":"/site/102ec7d9/contact","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dm_navGroup010101422186_item","pageAlias":"contact","pageID":4945812,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101422186","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Terms & Conditions","itemUrl":"/site/102ec7d9/terms-conditions","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101905599_item","pageAlias":"terms-conditions","pageID":4945785,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101905599","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Supplier Requirements","itemUrl":"/site/102ec7d9/supplier-requirements","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101481429_item","pageAlias":"supplier-requirements","pageID":4945790,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101481429","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Accessibility","itemUrl":"/site/102ec7d9/accessibility","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup010101596347_item","pageAlias":"accessibility","pageID":13320450,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_010101596347","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"Search","itemUrl":"/site/102ec7d9/search","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":["mobile","desktop","tablet"],"pageItemsNavData":null,"elementID":"dm_navGroup01010162527_item","pageAlias":"search","pageID":4945781,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_01010162527","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":true,"pageFromScratch":true,"deleted":false},{"itemTitle":"MORE","itemUrl":"/site/102ec7d9dmMore","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dmMore","pageAlias":"home","pageID":8268048,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_dmMore","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":false,"pageFromScratch":true,"deleted":false},{"itemTitle":"LESS","itemUrl":"/site/102ec7d9dmLess","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"dmLess","pageAlias":"home","pageID":8268048,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmUDNavigationItem_dmLess","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":false,"pageFromScratch":true,"deleted":false},{"itemTitle":"Home","itemUrl":"/site/102ec7d9dmBackHome","depth":0,"subNav":[],"hasDynamicSubNav":false,"hiddenOnDevices":[],"pageItemsNavData":null,"elementID":"backToHome","pageAlias":"home","pageID":8268048,"newWindow":false,"linkDesign":{"iconImageName":"url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')","itemClassName":"dmHome","itemIcon":"https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png","backgroundCSS":["url('https://dudamobile-themes.s3.amazonaws.com/direct/two-tone/icons/black/general_icon.png')"],"backgroundColor":null,"userImage":false},"inNavigationList":false,"pageFromScratch":true,"deleted":false}],"wsPath":"/editor/mvc/ws","site_popups":[{"id":4945779,"alias":"copy-of-make-a-donation","encodedAlias":"Y29weS1vZi1tYWtlLWEtZG9uYXRpb24=","title":"Book a Consultation","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/copy-of-make-a-donation","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":true,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"02cb8cf209144e4d9c79a7df84187c39","siteScopedId":"98668062","pageType":"POPUP","dynamicCollectionName":null,"publicationDate":1675853738000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{"tablet":{"backgroundColor":"#FFFFFF","borderRadius":"5","width":"598","overlayColor":"rgba(247, 247, 247,0.9)","height":"554","animation":"fadeIn"},"desktop":{"backgroundColor":"#FFFFFF","borderRadius":"5","width":"598","overlayColor":"rgba(247, 247, 247,0.9)","height":"554","animation":"fadeIn"},"mobile":{"backgroundColor":"#FFFFFF","borderRadius":"5","width":"266","overlayColor":"rgba(247, 247, 247,0.9)","height":"430","animation":"fadeIn"}},"isDudacommerce":false},{"id":5287620,"alias":"vote-for-us","encodedAlias":"dm90ZS1mb3ItdXM=","title":"Vote For Us","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/vote-for-us","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":true,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"a5f101be458d4e98a47b60a98dee7b79","siteScopedId":"cf0b2ab8","pageType":"POPUP","dynamicCollectionName":null,"publicationDate":1679449768000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{"tablet":{"backgroundColor":"#FFFFFF","borderRadius":"5","width":"686.53125","previousAnimation":"fadeIn","overlayColor":"rgba(0, 0, 0, 0.5)","height":"411","animation":"fadeIn"},"desktop":{"backgroundColor":"#FFFFFF","borderRadius":"5","width":"686.53125","previousAnimation":"fadeIn","overlayColor":"rgba(0, 0, 0, 0.5)","height":"411","animation":"fadeIn"},"mobile":{"backgroundColor":"#FFFFFF","borderRadius":"5","width":"361.46875","previousAnimation":"fadeIn","overlayColor":"rgba(0, 0, 0, 0.5)","height":"564","animation":"fadeIn"}},"isDudacommerce":false}],"site_pages":[{"id":4945769,"alias":"why-choose-a-career-in-the-trades","encodedAlias":"d2h5LWNob29zZS1hLWNhcmVlci1pbi10aGUtdHJhZGVz","title":"Why Choose a Career in the Trades","url":null,"itemUrl":"/site/102ec7d9/why-choose-a-career-in-the-trades","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"d44224ff404c45a8a13253ec5cd84a58","siteScopedId":"9e0f7e88","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755290204000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945771,"alias":"d1-internal-blog-post","encodedAlias":"ZDEtaW50ZXJuYWwtYmxvZy1wb3N0","title":"Blog Layout","url":null,"itemUrl":"/site/102ec7d9/d1-internal-blog-post","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"9bb3ec4f2e174f0f97afc74d89a3ee18","siteScopedId":"04cf4498","pageType":"BLOG_LAYOUT","dynamicCollectionName":null,"publicationDate":1757939803000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945792,"alias":"review-for-manufacturability","encodedAlias":"cmV2aWV3LWZvci1tYW51ZmFjdHVyYWJpbGl0eQ==","title":"Design for Manufacturability","url":null,"itemUrl":"/site/102ec7d9/review-for-manufacturability","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"f6328b164bf44e4eaa71710accbaae57","siteScopedId":"be709475","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945787,"alias":"header","encodedAlias":"aGVhZGVy","title":"header","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/","siteId":314058,"isHeader":true,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"fc52303dc93546269ddb174bc5eb47eb","siteScopedId":"d6d7fdd3","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756322087000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945811,"alias":"assembly","encodedAlias":"YXNzZW1ibHk=","title":"Assembly","url":null,"itemUrl":"/site/102ec7d9/assembly","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"90c589bc18e24843b509ff8404a817b0","siteScopedId":"1bf90d1b","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945773,"alias":"machining","encodedAlias":"bWFjaGluaW5n","title":"Machining","url":null,"itemUrl":"/site/102ec7d9/machining","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"f879dcb0a517400e91935ea3bf1f7288","siteScopedId":"41431cbe","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945804,"alias":"space","encodedAlias":"c3BhY2U=","title":"Space","url":null,"itemUrl":"/site/102ec7d9/space","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"66f33c2375e7498aa21a2080baffa4c2","siteScopedId":"84fbf9a6","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945817,"alias":"program-management","encodedAlias":"cHJvZ3JhbS1tYW5hZ2VtZW50","title":"Program Management","url":null,"itemUrl":"/site/102ec7d9/program-management","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"cf1f80fe7ba0405db73ec67211494186","siteScopedId":"82411573","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945801,"alias":"materials","encodedAlias":"bWF0ZXJpYWxz","title":"Materials","url":null,"itemUrl":"/site/102ec7d9/materials","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"b7ba30ca7ddb479a8b49430b4f28bd3c","siteScopedId":"bb188dbf","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945802,"alias":"laser-punching-cutting","encodedAlias":"bGFzZXItcHVuY2hpbmctY3V0dGluZw==","title":"Laser Punching","url":null,"itemUrl":"/site/102ec7d9/laser-punching-cutting","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"df16bb075f674fbf9af9fa9d19fffad5","siteScopedId":"6d615d1b","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945785,"alias":"terms-conditions","encodedAlias":"dGVybXMtY29uZGl0aW9ucw==","title":"Terms & Conditions","url":null,"itemUrl":"/site/102ec7d9/terms-conditions","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":false,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"7b8bf9e8c363474d806fc0e53db10165","siteScopedId":"d805ea40","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1754939526000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945776,"alias":"manufacturing_engineering","encodedAlias":"bWFudWZhY3R1cmluZ19lbmdpbmVlcmluZw==","title":"Manufacturing Engineering","url":null,"itemUrl":"/site/102ec7d9/manufacturing_engineering","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"b08bcb6b85744f8cb6365c64585bd0f2","siteScopedId":"cc173914","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945799,"alias":"privacy","encodedAlias":"cHJpdmFjeQ==","title":"privacy","url":null,"itemUrl":"/site/102ec7d9/privacy","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"c5611647c4e64079851cdc25058ab4d8","siteScopedId":"5849b0b3","pageType":"PRIVACY_PAGE","dynamicCollectionName":null,"publicationDate":1698942481000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945793,"alias":"npi-services","encodedAlias":"bnBpLXNlcnZpY2Vz","title":"NPI Services","url":null,"itemUrl":"/site/102ec7d9/npi-services","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"aa39bfe6cd57488c99994fd8c0c3ec08","siteScopedId":"ea44d1fc","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945788,"alias":"hydroforming","encodedAlias":"aHlkcm9mb3JtaW5n","title":"Hydroforming","url":null,"itemUrl":"/site/102ec7d9/hydroforming","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"2b6042d253de45709d1507c230ca05ec","siteScopedId":"fc7a9d84","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1754939526000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945781,"alias":"search","encodedAlias":"c2VhcmNo","title":"Search","url":null,"itemUrl":"/site/102ec7d9/search","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":false,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"b6553e978ba041c3994aaf0904d696c2","siteScopedId":"16e1be33","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1754939526000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945783,"alias":"leadership","encodedAlias":"bGVhZGVyc2hpcA==","title":"Leadership","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/leadership","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"4d975214b34d4d99b7287c26ad3b7dff","siteScopedId":"9804eaaf","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1704981463000,"isDraft":true,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945786,"alias":"history","encodedAlias":"aGlzdG9yeQ==","title":"History","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/history","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"f883684d1ac04be690c27a34ae83ee66","siteScopedId":"a227e8a8","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756322087000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945800,"alias":"supply-chain","encodedAlias":"c3VwcGx5LWNoYWlu","title":"Supply Chain","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/supply-chain","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"351a89a4361e475398a12a2391184b5b","siteScopedId":"2b6ef413","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1675853738000,"isDraft":true,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945780,"alias":"working-at-skilcraft","encodedAlias":"d29ya2luZy1hdC1za2lsY3JhZnQ=","title":"Working at Skilcraft","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/working-at-skilcraft","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"a8a15bc65d9748ccb383e8faf81a52db","siteScopedId":"aee90381","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755290204000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945774,"alias":"forming","encodedAlias":"Zm9ybWluZw==","title":"Forming","url":null,"itemUrl":"/site/102ec7d9/forming","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"6d0bfaeaf1854588b6e279881ba751ed","siteScopedId":"2a87b966","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945794,"alias":"brazing","encodedAlias":"YnJhemluZw==","title":"Brazing","url":null,"itemUrl":"/site/102ec7d9/brazing","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"a2dbcbb736b841ed9eb9f2c9b444b451","siteScopedId":"7dda0da5","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945805,"alias":"aerostructures","encodedAlias":"YWVyb3N0cnVjdHVyZXM=","title":"Aerostructures","url":null,"itemUrl":"/site/102ec7d9/aerostructures","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"cad6f4ed2ce74acaa0176ce6ed865007","siteScopedId":"9e215f19","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945782,"alias":"industries","encodedAlias":"aW5kdXN0cmllcw==","title":"Industries","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/industries","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"fd0f8c3ba87e4b2a8eeb3d4416023063","siteScopedId":"1f53304c","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945772,"alias":"our-commitment-to-you","encodedAlias":"b3VyLWNvbW1pdG1lbnQtdG8teW91","title":"Our Commitment to You","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/our-commitment-to-you","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"896da18f3dd94f58b74ff5136ec32791","siteScopedId":"585b33f6","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945808,"alias":"advanced-manufacturing","encodedAlias":"YWR2YW5jZWQtbWFudWZhY3R1cmluZw==","title":"Advanced Manufacturing","url":null,"itemUrl":"/site/102ec7d9/advanced-manufacturing","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"affbcbeb727643beb919cb9a5ba456f6","siteScopedId":"2d93f9db","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945775,"alias":"military","encodedAlias":"bWlsaXRhcnk=","title":"Military","url":null,"itemUrl":"/site/102ec7d9/military","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"ae1f91f0d4b0458c86ac46100d7d5801","siteScopedId":"1886e73d","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945777,"alias":"careers","encodedAlias":"Y2FyZWVycw==","title":"Careers","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/careers","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"5a6ad78988f2426f84da93be42ab73e9","siteScopedId":"86bdee81","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945807,"alias":"medical-devices","encodedAlias":"bWVkaWNhbC1kZXZpY2Vz","title":"Medical Devices","url":null,"itemUrl":"/site/102ec7d9/medical-devices","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"ebe60dce535540de9cbbcca162219d6a","siteScopedId":"badaa6c5","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945796,"alias":"aerospace-engines","encodedAlias":"YWVyb3NwYWNlLWVuZ2luZXM=","title":"Aerospace Engines","url":null,"itemUrl":"/site/102ec7d9/aerospace-engines","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"7d707a569241472f932b583e84437302","siteScopedId":"86b79fc0","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945814,"alias":"certifications","encodedAlias":"Y2VydGlmaWNhdGlvbnM=","title":"Certifications","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/certifications","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"b5e5969dddb340588bb0aa41160b11ab","siteScopedId":"d7bf529a","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755290204000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945812,"alias":"contact","encodedAlias":"Y29udGFjdA==","title":"CONTACT","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/contact","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"8f97dfca9607455d89b893bc5990caad","siteScopedId":"cf432728","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945790,"alias":"supplier-requirements","encodedAlias":"c3VwcGxpZXItcmVxdWlyZW1lbnRz","title":"Supplier Requirements","url":null,"itemUrl":"/site/102ec7d9/supplier-requirements","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":false,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"40e3c42e87554d16baf6f60da4b4e241","siteScopedId":"8e7a0e76","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1754939526000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945778,"alias":"power-generation","encodedAlias":"cG93ZXItZ2VuZXJhdGlvbg==","title":"Power Generation","url":null,"itemUrl":"/site/102ec7d9/power-generation","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"b2eaa5604c0c4d58915b80dc164277bd","siteScopedId":"d033efdb","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945815,"alias":"roll-forming-and-expanding","encodedAlias":"cm9sbC1mb3JtaW5nLWFuZC1leHBhbmRpbmc=","title":"Roll Forming and Expanding","url":null,"itemUrl":"/site/102ec7d9/roll-forming-and-expanding","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"3a55607c792346ec84cb653f3ffa2bd2","siteScopedId":"addce581","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945806,"alias":"alternative-energy","encodedAlias":"YWx0ZXJuYXRpdmUtZW5lcmd5","title":"Alternative Energy","url":null,"itemUrl":"/site/102ec7d9/alternative-energy","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"8454ae03aa8e4042b507c81044e6a123","siteScopedId":"702c56c2","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945809,"alias":"avionics-and-missions","encodedAlias":"YXZpb25pY3MtYW5kLW1pc3Npb25z","title":"Avionics and Missions","url":null,"itemUrl":"/site/102ec7d9/avionics-and-missions","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"6a859fa25208430880a2862e44900672","siteScopedId":"f78f14b3","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945798,"alias":"about","encodedAlias":"YWJvdXQ=","title":"About","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/about","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"e442f98ab6f04c3388b534a4028919d0","siteScopedId":"40183fae","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756322087000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945795,"alias":"current-opportunities","encodedAlias":"Y3VycmVudC1vcHBvcnR1bml0aWVz","title":"Current Opportunities","url":null,"itemUrl":"/site/102ec7d9/current-opportunities","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"390a370a2d98495bb84ce7070be1b73b","siteScopedId":"4964f264","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755114845000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945791,"alias":"capabilities","encodedAlias":"Y2FwYWJpbGl0aWVz","title":"Capabilities","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/capabilities","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"6f5dfb2151e0485b8ba8618fa2e766c8","siteScopedId":"1dd61ec0","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755180397000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945789,"alias":"spot-welding","encodedAlias":"c3BvdC13ZWxkaW5n","title":"Spot Welding","url":null,"itemUrl":"/site/102ec7d9/spot-welding","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"c6659e9e553d49809f18cbd53b9e0011","siteScopedId":"154fc313","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755198947000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945803,"alias":"affiliates","encodedAlias":"YWZmaWxpYXRlcw==","title":"Affiliates","url":null,"itemUrl":"/site/102ec7d9/affiliates","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"aa8559a36f2240beaa26bf3f5d4b9e5c","siteScopedId":"7f73dba6","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755199934000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945797,"alias":"tig-welding","encodedAlias":"dGlnLXdlbGRpbmc=","title":"TIG Welding","url":null,"itemUrl":"/site/102ec7d9/tig-welding","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"0e94de15251545a78da2dd8785a44044","siteScopedId":"72fc65a1","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755199934000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945810,"alias":"custom404page","encodedAlias":"Y3VzdG9tNDA0cGFnZQ==","title":"Page Not Found","url":null,"itemUrl":"/site/102ec7d9/custom404page","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"530a5e8ff8df4f1bbb3ea4dbfe329308","siteScopedId":"bb19789d","pageType":"PAGE_404","dynamicCollectionName":null,"publicationDate":1715197879000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":4945784,"alias":"quality","encodedAlias":"cXVhbGl0eQ==","title":"Quality","url":null,"itemUrl":"/site/102ec7d9/quality","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"c182ebc635ad449eacef33371add95f8","siteScopedId":"e238da66","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756306842000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":8268048,"alias":"home","encodedAlias":"aG9tZQ==","title":"Home","url":null,"itemUrl":"/site/102ec7d9/","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":true,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"dd95a7e8a2be4901a83d4d182367bfe6","siteScopedId":"715ce589","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756306842000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":8423846,"alias":"blog","encodedAlias":"YmxvZw==","title":"Blog","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/blog","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"5a83323b8d30478597fda5a8f85c6c90","siteScopedId":"b276b0e0","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1754939526000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":17394980,"alias":"copy-of-home","encodedAlias":"Y29weS1vZi1ob21l","title":"Copy of Home","url":null,"itemUrl":"/site/102ec7d9/copy-of-home","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"33085204859443fd96ed5904cc965f23","siteScopedId":"64f98f64","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756306842000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":13320450,"alias":"accessibility","encodedAlias":"YWNjZXNzaWJpbGl0eQ==","title":"Accessibility","url":null,"itemUrl":"/site/102ec7d9/accessibility","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":false,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"8b786c11abbf4546959f68b19d8a57c1","siteScopedId":"f36e10a8","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1754939526000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":17094632,"alias":"skilcraft-solutions-cell","encodedAlias":"c2tpbGNyYWZ0LXNvbHV0aW9ucy1jZWxs","title":"Skilcraft Solutions Cell","url":null,"itemUrl":"/site/102ec7d9/skilcraft-solutions-cell","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"fec37d7a74cb4a50bff355d03c218fb7","siteScopedId":"8c0e9243","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755172625000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":17607825,"alias":"copy-of-capabilities","encodedAlias":"Y29weS1vZi1jYXBhYmlsaXRpZXM=","title":"Copy of Capabilities","url":null,"itemUrl":"/site/102ec7d9/copy-of-capabilities","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"434694c264d74420ad68d72d19f8a18d","siteScopedId":"5096ac2c","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":null,"isDraft":true,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},{"id":17740489,"alias":"copy-of-industries","encodedAlias":"Y29weS1vZi1pbmR1c3RyaWVz","title":"Copy of Industries","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/copy-of-industries","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"a51f9ab77b984ba7a82d74ed8d8c5868","siteScopedId":"41024176","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":null,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false}],"accountData":{"uuid":"acf02c6f5e684624b32d26d693519e43","eldSwitchEnabled":false},"siteDesigntimeFlags":{"RUN_AUTOMATIC_FIXER_ON_NEXT_EDITOR_OPEN":false,"NO_PAGES_UUID_VALIDATOR":true,"SHOW_MULTILINGUAL_CONGRATS":false,"TRACK_SITE_CHANGES":true,"SITE_CSS_CLEANUP_VALIDATOR":true,"SKIP_AUTOMATIC_VALIDATION_AND_FIXING":false,"RICH_TEXT_CSS_VALIDATOR":true,"TEMP_PLACEHOLDER":true,"DIY_SITE":false,"FORCE_DIY_ONBOARDING_COMPLETED":false,"AUTOSYNC_PROACTIVELY":false,"DISABLE_GOOGLE_TRANSLATE":false,"GLOBAL_COLORS_AUTOGENERATE_POPUP_SHOWN":false,"MULTIPLE_PRIMARY_LOCATIONS_VALIDATOR":true,"SKIP_PUBLISH_MIGRATED_IMAGES_SCAN_INTERCEPTOR":false,"GLOBAL_PARAGRAPH_SELECTOR_VALIDATOR":true,"GLOBAL_COLORS_AUTOGENERATE_USED":false,"GLOBAL_CLASSES_HAMBURGER_VALIDATOR":true,"BLOG_ONBOARDING_SHOWN":false,"SKIP_CONTENT_ABUSE_DETECTION":false,"MEDIA_REPO_IN_DYNAMO":false,"BLOG_MIGRATION_LABEL_SHOWN":false,"REMOVE_FROM_PHISHING_ADMIN":false,"SERVE_DIY_EDITOR":false},"isFastMigration2SiteEditable":false,"site":{"id":314058,"baseUrl":"http://bfs._dudamobile.com","mobileUrl":"http://www.skilcraft.com","resellerPreviewUrl":"https://editor.carpediemcg.com/preview/102ec7d9?t=1760630056154","sitePreviewUrl":"https://editor.carpediemcg.com/preview/102ec7d9?t=1760630056149","alias":"102ec7d9","siteName":null,"domain":"www.skilcraft.com","displayDomain":"www.skilcraft.com","isPublished":true,"needsRepublish":true,"defaultDomain":"multiscreensite.com","defaultSubDomain":"skilcraftllc","duplicateSubdomainExists":null,"isRedirected":true,"planId":7,"dmProductType":"DM_DIRECT","isV3":true,"isFromScratch":true,"failedBilling":null,"daysBeforeDowngrade":-1,"subscriptionId":176590,"isStripeSubscription":true,"resellerBeforeAfterUrl":null,"resellerSiteFormUrl":"https://editor.carpediemcg.com/site-form/k1ltVdMzNi1GYjs5AMfoxMedOF7zCLcV3WRE9kLCefnuG4pA_rp9BNMiT-rjDitc","dudaOneBetaSite":null,"contractId":"10023064","siteForLife":false,"sslStatus":null,"version":426,"insiteTrialExpired":false,"insiteInPlan":true,"insiteTrialExpirationDate":"","publicationDate":"2025-08-27T19:14:47.000Z","firstPublicationDate":"2022-12-17T00:31:38.000Z","creationDate":"2022-12-05 01:37 PM","apiSite":false,"customTemplateId":null,"baseCustomTemplateId":1000093,"permissions":"eyJNQU5BR0VfTUVNQkVSU0hJUCI6ZmFsc2UsIkNIQU5HRV9QT1NUX0FVVEhPUiI6ZmFsc2UsIlNJVEVfRE9NQUlOIjpmYWxzZSwiVVJMX1JFRElSRUNUUyI6dHJ1ZSwiQ09OTkVDVF9XSURHRVRTIjpmYWxzZSwiR09PR0xFX0FOQUxZVElDUyI6dHJ1ZSwiREVWX01PREUiOnRydWUsIkdPT0dMRV9QQUdFU1BFRUQiOmZhbHNlLCJIRUFERVJfSFRNTCI6dHJ1ZSwiU0lURV9GT09URVIiOmZhbHNlLCJXSURHRVRTX0RFU0lHTiI6dHJ1ZSwiU0lURV9CQUNLVVAiOnRydWUsIlBVUkNIQVNFX0lNQUdFUyI6ZmFsc2UsIkZJUlNUX1BVQkxJU0giOnRydWUsIkFOTk9UQVRJT05TIjp0cnVlLCJDT09LSUVfTk9USUZJQ0FUSU9OIjp0cnVlLCJDT05URU5UX0xJQlJBUllfRVhURVJOQUxfREFUQV9TWU5DIjpmYWxzZSwiQUREX1dJREdFVFMiOnRydWUsIldJREdFVFNfQ09OVEVOVCI6dHJ1ZSwiRURJVF9URUFNX1NFQ1RJT04iOmZhbHNlLCJQUklWQUNZX1NFVFRJTkdTIjp0cnVlLCJTSVRFX0VESVQiOnRydWUsIlBVU0hfTk9USUZJQ0FUSU9OIjpmYWxzZSwiU1RBVFNfVEFCIjp0cnVlLCJEQVRBX0JJTkRJTkciOnRydWUsIkJMT0ciOnRydWUsIlBBR0VTIjp0cnVlLCJVU0VfQVBQIjp0cnVlLCJNQU5BR0VfRE9NQUlOIjpmYWxzZSwiU1dJVENIX1RFTVBMQVRFIjpmYWxzZSwiU0VPIjp0cnVlLCJTVEFUU19FTUFJTCI6dHJ1ZSwiUkVESVJFQ1QiOmZhbHNlLCJDVVNUT01fNDA0Ijp0cnVlLCJTVE9SRV9NQU5BR0VSIjpmYWxzZSwiQ0xJRU5UX01BTkFHRV9GUkVFX0FQUFMiOnRydWUsIlNFT19PVkVSVklFVyI6dHJ1ZSwiQk9PS0lOR19BRE1JTiI6ZmFsc2UsIlZJRVdfSU5fREFTSEJPQVJEIjp0cnVlLCJSRVBVQkxJU0giOnRydWUsIklOU1RBTExfQVBQIjpmYWxzZSwiQUlfQVNTSVNUQU5UIjp0cnVlLCJJTkxJTkVfRURJVElORyI6dHJ1ZSwiSU5TSVRFX0VESVRPUiI6dHJ1ZSwiRE1fREVWX01PREUiOmZhbHNlLCJSRVNFVF9TSVRFIjpmYWxzZSwiVU5QVUJMSVNIIjp0cnVlLCJTSVRFX0lDT05TIjp0cnVlLCJHTE9CQUxfREVTSUdOIjp0cnVlLCJDT05URVhUX01FTlUiOnRydWUsIkJMT0dfTEFZT1VUIjp0cnVlLCJDTElFTlRfTUFOQUdFX1BBSURfQVBQUyI6ZmFsc2UsIkFERF9GTEVYIjp0cnVlLCJDT05URU5UX0xJQlJBUlkiOnRydWUsIkVESVRfQ09OTkVDVEVEX0NPTlRFTlQiOmZhbHNlLCJCT09LSU5HX1VTRVIiOmZhbHNlLCJWSUVXX0FQUCI6ZmFsc2V9","siteStoreId":0,"snowplowStat":true,"isSiteOfChildProduct":false,"blogId":62856,"isNewBlog":true,"blogRssUrl":"http://www.skilcraft.com/feed/rss2","generatedSectionsStyleId":null,"alternateDomains":null,"isCustomDomain":true,"creationMethod":"TEMPLATE","normalizedBaseUrl":null,"originalBaseUrl":null,"suggestedDomain":"m.mycompanyname.com","isSuspended":false,"isDeleted":false,"accountOwner":"chris@carpediemcg.com","accountOwnerUUID":"8d12bccac17b4e38b6c2e15d209c7d47","accountOwnerID":238600,"isOwnerReseller":true,"baseThemeName":"Layout Theme","showAds":false,"showPoweredBy":false,"compatible_platforms":null,"isOwnerTransitional":null,"redirectProvider":null,"colors":["rgb(2, 103, 33)","rgb(48, 169, 42)","rgb(254, 237, 1)","rgb(246, 150, 1)","rgb(239, 41, 41)","rgb(1, 109, 181)","rgb(1, 60, 120)","rgb(0, 0, 0)","rgb(205, 201, 201)","rgb(255, 255, 255)"],"recentColors":["rgba(52, 41, 20, 1)","rgba(0, 0, 0, 0.16)","rgba(0, 0, 0, 0.05)","linear-gradient(135deg, rgba(21, 124, 116, 1) 0%, rgba(217, 217, 217, 1) 100%)","rgba(255, 255, 255, 0.25)","rgb(217, 217, 217)","rgba(241, 231, 231, 1)","rgba(245, 104, 16, 1)","rgba(248, 247, 247, 1)","rgba(161, 165, 191, 1)","rgba(243, 243, 243, 1)","rgba(242, 93, 4, 1)","rgba(248, 244, 244, 1)","rgba(248, 248, 248, 1)","rgba(255, 0, 0, 1)","rgba(52, 52, 20, 1)","rgba(21, 124, 116, 0)","rgba(181, 101, 29, 1)","rgba(21, 31, 109, 1)","rgba(21, 124, 116, 1)"],"dontMobilizeRules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"siteSettings":{"disableAutoSync":false,"useAjaxLoading":true,"generateNavigation":true,"syncWithSiteNavigation":false,"cacheStrategy":"pages.shortCache","analyticsAccount":"G-CJ1C9X2EKQ","googleTagManagerIds":[],"piwikSiteID":null,"brighttagID":null,"seoSiteDescription":"Skilcraft provides complex sheet metal fabrication for a wide range of industries, including aerospace, renewable energy, medical, and military applications.","seoSiteMetaKeywords":"skilcraft, metal fabrication, sheet metal fabrication, complex sheet metal fabrication, aerospace, aerospace engines, airframe, space, renewable energy, medical devices, power generation, military applications, renewable energy, Complex metal fabrication, Custom metal fabrication, Precision metal fabrication, Industrial metal fabrication, Heavy metal fabrication, Metal welding and fabrication, Metal prototyping, Metal assembly, Metal stamping, CNC metal fabrication, Metal fabrication and machining, Large scale metal fabrication, Metal fabrication for industrial equipment, Metal fabrication services, Complex metal fabrication solutions","seoSiteTitle":"Skilcraft | Complex Sheet Metal Fabrication","noIndex":null,"iframesToKeep":null,"scriptsToKeep":null,"headerContent":"","lastSyncDate":"","favIcon":"https://irp.cdn-website.com/102ec7d9/site_favicon_16_1754932767632.ico","homescreenIcon":"https://irp.cdn-website.com/102ec7d9/dms3rep/multi/Skilcraft+logo_Dec+2022+57+x+57+Round.png","startupImage":null,"facebookShareImage":"https://irp.cdn-website.com/102ec7d9/dms3rep/multi/Final+logo+final+December+2022+RGB+-+Social+Image+-+1200+x+630.png","homescreenReminder":false,"autoSyncNav":false,"specificTag":null,"showCookieNotification":true,"cookieNotificationLanguage":0,"visibleNavItemsPerDevice":{"tablet":5,"desktop":4,"mobile":5},"xFrameOptions":{"options":{"returnXFrameHeaders":true,"allowedDomains":null},"defaultOptions":{"returnXFrameHeaders":true,"allowedDomains":null},"byDefault":true},"visibleNavigationItems":5},"customerID":null,"dmReferral":null,"paletteID":-1,"manifestID":10600,"themeID":20600,"isUsingLayout":true,"headerFixed":false,"headerSkinny":false,"importedContentLibrary":true,"isContentLibraryEmpty":false,"status":"OK","layoutID":22,"styleID":5,"vertical":null,"layouts":{"tablet":23,"desktop":6,"mobile":22},"buttonStyle":"BIG_BASIC","opOrigin":"UI","externalUID":null,"metaData":{"facebookID":null,"empty":false},"hasFullBleedRows":true,"isOwnerInsiteCreator":false,"languages":{"defaultLanguage":"en","currentLanguage":null,"otherLanguages":null,"defaultLanguagePagesInfo":null},"isMultilingual":false,"defaultLanguage":{"clientId":1,"languageName":"English","countryCode":"us","languageCode":"en","localeCode":"en","flagUrl":"https://dd-cdn.multiscreensite.com/flags/flags_iso/32/us.png","isEnabled":true,"countryName":"USA"},"useGoogleTranslate":true,"multiLingualNoUrlRules":true,"pageSpeedOptimizationDate":"2025-08-27T19:16:04.510Z","isWidgetBuilderPreviewSite":false,"templateType":null,"sectionId":null,"headerPagesIds":[4945787],"sitePermissionsForPlatformAPI":[null,"INSITE","AI_ASSISTANT","SITE_COMMENTS","ADD_FLEX","REPUBLISH","CLIENT_MANAGE_FREE_APPS","SEO","BACKUPS","USE_APP","SEO_OVERVIEW","EDIT","LIMITED_EDITING","STATS_TAB","DEV_MODE","BLOG","PUBLISH","CONTENT_LIBRARY"],"subCategory":null,"isRepublished":true,"commonTagEnabled":true,"dudaTemplate":null,"dudaOne":true,"flexSite":false,"nonCancelledAddonWithAutoRenewExist":true,"nonCancelledSiteSubscription":true,"hasInsiteRules":true,"isCustomTheme":false,"customThemeName":null},"dudaDomains":["dudamobile.com","duda.co","dud4.co","previewmymobile.com","mobilewebsiteserver.com","dudaone.com","multiscreensite.com","127.0.0.1","multiscreen.d1test.biz","dudasite.com","-mb.d1test.biz","dwhitelabel.com","cdn-website.com","dudasites.com"],"native_booking":{"hasBooking":false},"header":{"id":4945787,"alias":"header","encodedAlias":"aGVhZGVy","title":"header","url":"http://bfs._dudamobile.com","itemUrl":"/site/102ec7d9/","siteId":314058,"isHeader":true,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"fc52303dc93546269ddb174bc5eb47eb","siteScopedId":"d6d7fdd3","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1756322087000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},"page":{"id":17094632,"alias":"skilcraft-solutions-cell","encodedAlias":"c2tpbGNyYWZ0LXNvbHV0aW9ucy1jZWxs","title":"Skilcraft Solutions Cell","url":null,"itemUrl":"/site/102ec7d9/skilcraft-solutions-cell","siteId":314058,"isHeader":false,"isDefault":false,"disableAutoSync":false,"isTemplate":false,"isFromScratchLegacy":false,"isBFS":true,"isPopup":false,"isHomePage":false,"isMembershipRestricted":false,"membershipAccessType":"NONE","indexSEO":null,"head":null,"rules":[{"id":2314187,"priority":1,"urlPattern":"https://www.indeed.com/cmp/Skilcraft/jobs","targetPageAlias":"original"}],"password":null,"availableTranslations":null,"aliasOfEquivalentPageInDefaultLanguage":null,"encodedAliasOfEquivalentPageInDefaultLanguage":null,"uuid":"fec37d7a74cb4a50bff355d03c218fb7","siteScopedId":"8c0e9243","pageType":"FROM_SCRATCH","dynamicCollectionName":null,"publicationDate":1755172625000,"isDraft":false,"isEquivalentPageInDefaultLanguageDraft":false,"popupData":{},"isDudacommerce":false},"isNewBlog":true,"site_store":{"hasCategories":false,"isNewStore":false,"available":false,"dashboardVisited":false,"demoStore":false}};
            $.dmx.set(context);
            initLoadingPromises();
        </script>

        <div id="mediapicker">
	<script type="text/x-handlebars" data-template-name="picker@application">
		{{outlet}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@media/loading">
		{{spinner-loader applyOn=".media"}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@media">
		<div class="overlay">
			<div class="media container newDudaGeneralStyles">
				{{#if controllers.application.duringTransition}}
					{{spinner-loader applyOn=".media"}}
				{{/if}}
				<div class="dm-icon-x closer" {{action close}}></div>
				{{mind-touch id=mindTouchId}}
			    <div class="media-header">
			        <span class="mediaTitle">
			        	{{#if isUploading}}
			        		<span class="linkAlike"{{action goBack}}>{{title}}</span><span class="dm-icon-chevron-right"></span><span>{{uploadableTabName}}</span>
			        	{{else}}
			        	{{title}}
			        	{{/if}}
			        </span>
			    </div>
			    <div class="media-body">
			        {{outlet}}
			    </div>
			    <div class="media-footer">
			        {{#if isUploading}}
			        	<div class="btn primary ptGreyBtn" {{action goBack}}>{{t ui.back}}</div>
			        {{else}}
			        <div class="mediaUploadButton btn">
			        	<span class="icon dm-icon-Gallery"></span>{{#link-to 'media.upload'}}{{upload-button-text mediaType}}{{/link-to}}
					</div>
					<div class="ptOrangeBtn btn primary" {{action endPicking}}>{{t ui.done}}</div>
			        {{/if}}
			    </div>
			<div>
			{{#if itemToRemove}}
				{{partial "removeItemPopup"}}
			{{/if}}
			{{#if isWaitingForServerMultiSize}}
				{{spinner-loader applyOn=".media" block=true}}
			{{/if}}
		</div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_removeItemPopup">
		<div class="overlay">
			<div class="removeItemPopup">
				<div class="dm-icon-x closer" {{action cancelRemove}}></div>
				<div class="removeItemMessage">
					Are you sure you want to remove {{itemToRemove.safeName}}?
					<br/><br/>
					If this image is currently in use on your site, it will no longer appear.</div>
				
				<div class="removeItemButtons">
					<div class="ptOrangeBtn" {{action removeItem}}>{{t ui.remove}}</div>
					<div class="ptGreyBtn" {{action cancelRemove}}>{{t ui.cancel}}</div>
				</div>
			</div>
		</div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@browse/loading">
		{{spinner-loader applyOn=".media"}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@browse">
	    <div class="mediaCtrls">
	    	{{input type="text" class="search" placeholder=searchPlaceholder value=searchQuery}}<div class="dm-icon-x" {{action removeSearch}}></div><div class="dm-icon-search"></div>
	        {{view Picker.ViewTypeSelectView
	            content=layoutTypes
	            optionValuePath="content.id"
	            optionLabelPath="content.name"
	            optionImgSrcPath="content.imgSrc"
	            value=selectedLayoutTypeInput
	            width=46}}



	    </div>
	    <ul class="tabs container">
	        {{#each tabs}}<li class="tab">
	                {{#link-to 'browse.tab' id}}
	                    <div><span {{bind-attr class=":tabIcon icon"}}></span>{{displayName}}</div>

	                {{/link-to}}
	        </li>{{/each}}{{#if wasSearched}}<li>
	        {{#link-to 'browse.search'}}
	        <div>Search Results</div>
	        {{/link-to}}
	        {{/if}}

	    </ul>
	    <div class="panel">
	        {{outlet}}
	    </div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@browse/search">
		{{render 'items' items}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@browse/tab">
	    {{render 'items' items}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@items">
		{{!-- DO NOT DELETE THIS LINE --}}
			{{#if doAllPaginatedItemsHaveSize}}{{/if}}
		{{!-- DO NOT DELETE THIS LINE --}}
		{{#if view.shouldShowLoader}}
			{{spinner-loader applyOn=".media" block=true}}
		{{/if}}
		{{#if paginatedContent}}
			{{partial sortTemplateName}}
		{{/if}}
		{{#if parentController.canItemBeColored}}
			{{partial 'mediaColor'}}
		{{/if}}
	    <ul class="items container">
	    	{{#if paginatedContent}}
    			{{#if view.isList}}
    				{{partial "_dynamicList"}}
    			{{else}}
    				{{#each paginatedContent}}{{render 'item' this}}{{/each}}
    			{{/if}}
	        {{else}}
	        	{{partial emptyContentTemplateName}}
	        {{/if}}
	    </ul>
	    {{#if hasPages}}
	   		{{partial "pagination"}}
	    {{/if}}
		<div style="display:none;">
			{{view.shouldSpinLoader}}
			<ul>
				{{#each nonSizedItems}}
					{{render 'item' this}}
				{{/each}}
			</ul>
		</div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_dynamicList">
		<div {{bind-attr style=view.topPadderStyle}}></div>
		<div {{bind-attr style=view.scrollItemListStyle}}>
		{{#each view.listContent}}{{render 'item' this}}{{/each}}
		</div>
		<div {{bind-attr style=view.bottomPadderStyle}}></div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_selectSort">
		<div class="mediaSort">
	    	<div class="sortLabel">{{t ui.mediaPicker.sort}}: </div>
	        {{view Picker.SortSelectView
	            content=sortSelectOptions
	            optionValuePath="content.id"
	            optionLabelPath="content.name"
	            value=selectedSort
	        	width=80}}<div {{action 'toggleOrder' target=controller.parentController}}class="dm-icon-reorder"></div>
	    </div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_columnsSort">
		<div {{bind-attr class=":mediaSort view.sortClassName"}}>
			{{#each sortSelectOptions}}
				<div {{bind-attr class=":sortColumn id"}}>
					<span class="columnName" {{action 'applyAndToggle' id target=controller.parentController}}>
						{{name}}</span><span {{bind-attr class=":columnArrow :dm-icon-arrow_dropdown"}} {{action 'applyAndToggle' id target=controller.parentController}}></span>
				</div>{{/each}}

	    </div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_emptyContent">
		<p>{{t ui.no}} {{pluralize-noun-t mediaType}} {{t 'ui.media.1'}}</p>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_emptyUploadContent">
		<p>{{assemble-t 'ui.no.' mediaType '.selected'}}<br>{{assemble-t 'ui.click.on.upload.' mediaType ''}}</p>
		<div class="dm-icon-duda-arrow"></div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_emptySiteContent">
		<div class="contentImportWrapper">
			<div class="contentImportText">{{t 'ui.media.7'}}</div>
			<form>
				{{input class="importFromUrl"}}
				<span class="dm-icon-search"></span>
				<div class="error">{{importFromUrlError}}</div>
			</form>
			<div class="contentImportMainImage">
				<span class="dm-icon-duda-arrow"></span>
			</div>
		</div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_emptyContentSearch">
		<p>{{t 'ui.media.5'}}<br>{{t 'ui.media.6'}}</p>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_pagination">
		<div class="pagination">
		  <ul>
		    {{#if prevPage}}
		      <li class="dm-icon-left" {{action selectPage prevPage}}></li>{{else}}<li class="dm-icon-left disabled"></li>{{/if}}<div class="media-pages" {{bind-attr style=view.pagesWidth}}>
	    	    <ul class="movableArea" {{bind-attr style=view.movableAreaStyle}}>
	    		    {{#each pages itemController="page"}}<li {{bind-attr class="active disabled"}} {{action selectPage number}}>{{number}}</li>{{/each}}
	    	    </ul>
		    </div>{{#if nextPage}}<li class="dm-icon-right" {{action selectPage nextPage}}></li>{{else}}<li class="dm-icon-right disabled"></li>
		    {{/if}}
		  </ul>
		</div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@media_item">
		{{partial itemTemplateName}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_thumbnailItem">
		<div class="itemImgWrapper" {{bind-attr title=safeName}}>
		    <div class="itemImg" {{bind-attr style=style}}></div>
		    <div class="itemOverlay" {{action toggleItemSelection controller bubbles=false}}>
		    	{{#if canBeRemoved}}
		    		<div class="dm-icon-x removeItem" {{action requestRemove model  bubbles=false}}></div>
		    	{{/if}}
		    	<div class="itemButtons">
		    	<div class="itemSelector" {{action toggleItemSelection controller bubbles=false}}>{{view.selectButtonText}}</div>{{#if canBePreviewed}}<div class="dm-icon-zoom-in" {{action previewItem model  bubbles=false}}></div>{{/if}}
		    	</div>
		    </div>
		</div>
		<div {{bind-attr class=":itemTabIcon view.itemTabIcon"}}></div><div class="itemDetails" {{bind-attr title=safeName}}>
		    <div class="itemName">{{{view.name}}}</div>
		   	<div class="itemSize">{{#if hasSize}}{{view.sizeString}}{{else}}&nbsp;{{/if}}</div>
		</div>
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_listItem">
		{{#if view.shouldShow}}
			<div {{bind-attr class=":itemTabIcon view.itemTabIcon"}}></div><div class="itemImg" {{bind-attr style=style}}></div><div class="itemName">
			{{{view.name}}}</div><div class="itemSize">
			{{#if hasSize}}{{view.sizeString}}{{else}}N/A{{/if}}</div><div class="itemDate">{{format-date "ll" date}}</div>
		    <div class="itemOverlay" {{action toggleItemSelection controller}}>
		    	{{#if canBeRemoved}}
		    		<div class="dm-icon-x removeItem" {{action requestRemove model  bubbles=false}}></div>
		    	{{/if}}{{#if canBePreviewed}}<div class="dm-icon-zoom-in" {{action previewItem model  bubbles=false}}></div>{{/if}}
		    </div>
		{{/if}}
	</script>

	<script type="text/x-handlebars" data-template-name="picker@_mediaColor">
		<div class="mediaColor">
			{{one-color-picker value='red'}}
		</div>
	</script>


	<script type="text/x-handlebars" data-template-name="picker@media/upload">
	    <iframe seamless id="inkFrame" class="inkFrame"></iframe>
	</script>
</div>
<script type="text/x-handlebars" id="components/rule-icons">
    <div class="icons-wrapper">
    	{{#unless rule.isChild}}
    		{{#each condition in rule.conditions}}
             <svg {{bind-attr class=":condition-icon :icon condition.condition.icon condition.condition.id"}} viewBox="0 0 32 32">
                <use {{bind-attr xlink:href=condition.condition.xlinkIcon}}></use>
             </svg>
    		{{/each}}
            <svg class="rightArrow icon-long-arrow-right" viewBox="0 0 32 32">
                <use xlink:href="#icon-ruls-arrow"></use>
            </svg>
    	{{/unless}}
    	{{#each action in rule.actions}}
            <svg {{bind-attr class=":action-icon :action action.actionIcon action.action.id"}} viewBox="0 0 32 32">
                <use {{bind-attr xlink:href=action.xlinkActionIcon}}></use>
            </svg>
        {{/each}}
    </div>
</script>

<script type="text/x-handlebars" id="components/smart-icon">
    <div class="icon" {{bind-attr title=title rel=item.xlinkIcon}}>
     <svg viewBox="0 0 32 32">
        {{#if item}}
            <use {{bind-attr xlink:href=item.xlinkIcon}}></use>
        {{else}}
            <use {{bind-attr xlink:href=icon}}></use>
        {{/if}}
     </svg>
    </div>
</script>
<script type="text/x-handlebars" data-template-name="rule-wizard@first-time">
	<div class="pageSection top">
		<div class="block"> 
			<h1>{{t 'ui.rules.46'}}</h1>
			<div class="content">{{t 'ui.rules.47'}}</div>
			<svg class="arrow" height="60" width="40" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" >
			  <image x="0" y="0" height="60" width="40"  xlink:href="/editor/smart/images/welcome/arrow.svg" />
			</svg>
			<div class="large-button" {{action 'next' target="controllers.application"}}>{{t 'ui.rules.54'}}</div>
		</div>
	</div>
	<div class="pageSection bottom">
		<div class="dont-show-again">
			{{input id="ruleWizardDontShowFirstTime" type="checkbox" checked=controller.controllers.application.dontShowTip}} <label for="ruleWizardDontShowFirstTime">{{t 'ui.rules.3'}}</label>
		</div>
		<div class="carousel">
			<div class="special">
				<div class="col1">
					<h1>{{t 'ui.rules.69'}}</h1>
					<div>{{t 'ui.rules.70'}}</div>
				</div>
				<div class="col2">
					<div>{{t 'ui.rules.75'}}</div>
					<img class="icon" src="/editor/smart/images/welcome/promotion1.svg">
					<div>{{t 'ui.rules.76'}}</div>
					<img class="icon" src="/editor/smart/images/welcome/promotion2.svg">
				</div>
				<div class="col3">
					<img src="/editor/smart/images/welcome/promotion.png">
				</div>
			</div>
			<div class="holiday">
				<div class="col1">
					<h1>{{t 'ui.rules.71'}}</h1>
					<div>{{t 'ui.rules.72'}}</div>
				</div>
				<div class="col2">
					<div>{{t 'ui.rules.77'}}</div>
					<img class="icon" src="/editor/smart/images/welcome/Holidays1.svg">
					<div>{{t 'ui.rules.78'}}</div>
					<img class="icon" src="/editor/smart/images/welcome/Holidays2.svg">
				</div>
				<div class="col3">
					<img src="/editor/smart/images/welcome/Holidays.png">
				</div>
			</div>
			<div class="first">
				<div class="col1">
					<h1>{{t 'ui.rules.73'}}</h1>
					<div>{{t 'ui.rules.74'}}</div>
				</div>
				<div class="col2">
					<div>{{t 'ui.rules.79'}}</div>
					<img class="icon" src="/editor/smart/images/welcome/visitor1.svg">
					<div>{{t 'ui.rules.80'}}</div>
					<img class="icon" src="/editor/smart/images/welcome/visitor2.svg">
				</div>
				<div class="col3">
					<img src="/editor/smart/images/welcome/visitor.png">
				</div>
			</div>
		</div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@choose-rule">
	<div class="fixedHeader">
	    <span class="mindTouchHelp dm-icon-question-sign F1" id="dmMtChooseRule"></span>
		<h1>{{t 'ui.rules.1'}}</h1>
		<h2>{{t 'ui.rules.66'}}</h2>
		{{#if controller.controllers.application.isInTrial}}
			<h2>{{{t 'ui.rules.127'}}}</h2>
			<div class="inTrialBanner">{{t 'ui.rules.130'}}</div>
		{{/if}}
	</div>
    <div class="padded duda-scroll-bar">
	  {{#each template in rules}}
	  	{{#if template.displayed}}
	  	{{#unless template.isChild}}
		<div {{bind-attr data-rule-id=template.id class=":chooseRuleSection _view.contentIndex template.parentChildClass template.isVisible"}} >
			<a class="moreInfo" href="javascript:;">
				<svg width="14" height="14">
					<use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#info"></use>
				</svg>
			</a>
			<div class="moreInfoTip">
				<a class="close_moreInfoTip" onclick="$(this).parent().fadeOut()">
					<svg width="15" height="15"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#close_popup"></use></svg>
				</a>
				<div class="moreInfoTitle">{{t 'ui.rules.4'}}</div>
				{{#if template.isDBRule}}
					{{template.readable}}
				{{else}}
					{{template.description}}
				{{/if}}
			</div>
			<div class="ruleContent">
				{{#if template.isBfs}}
					<div class="ruleIcon">
						<svg viewBox="0 0 32 32">
							<use xlink:href="#icon-plus"></use>
						</svg>
					</div>
				{{else}}
					<div class="ruleIcon">
						<img {{bind-attr src=template.icon}}/>
					</div>
				{{/if}}					
				<h2><span class="verticalCenter">{{template.name}}</span></h2>
				<div class="description">
					{{{template.title}}}
				</div>
				<div>
					<a class="button btn primary" {{action 'select' template 'similar-rules' target="controllers.application"}}>
						{{#if template.isBfs}}
							{{t 'ui.rules.132'}}
						{{else}}
							{{t 'ui.rules.5'}}
						{{/if}}
					</a>
					{{#unless template.isBfs}}
						<a class="preview-link" {{bind-attr href=template.previewUrl}} target="_blank">{{t 'ui.rules.124'}}</a>
					{{/unless}}
				</div>
			</div>
		</div>
		{{/unless}}
		{{/if}}
	  {{/each}}
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@similar-rules">
	<div class="back" {{action 'back' target="controllers.application"}}><i class="dm-icon-chevron-left"></i> {{t 'ui.rules.42'}}</div>

	<div class="fixedHeader borderBotom">
	    <span class="mindTouchHelp dm-icon-question-sign F1" id="dmMtChooseRule"></span>
		<h1>{{t 'ui.rules.1'}}</h1>
		<h2>{{t 'ui.rules.66'}}</h2>
	</div>
    <div class="scrollableContent duda-scroll-bar">
		<div class="similarRulesParentSection borderBotom" {{bind-attr data-rule-id=model.id}}>
			<div class="parentRuleContent">
				<h2>{{model.name}}</h2>
				<div class="ruleIcon">
					<img {{bind-attr src=model.icon}}/>
				</div>
				<div class="description">
					{{#with model}}
						{{{view RuleWizard.ReadableView readable=readable}}}
					{{/with}}
				</div>
				<img class="ruleThumb" {{bind-attr src=model.thumb}}/>
				<div class="ruleButtons">
					<a class="button btn primary" {{action 'select' model target="controllers.application"}}>{{t 'ui.rules.68'}}</a>
					<a class="preview-link" {{bind-attr href=model.previewUrl}} target="_blank">{{t 'ui.rules.124'}}</a>
				</div>
				
			</div>
		</div>
		<div class="similarRulesChildrenSection">
		<h2>{{t 'ui.rules.67'}}</h2>
		{{#each child in model.childRules}}
			{{#if child.displayed}}
			<div class="ruleContent" {{bind-attr data-rule-id=child.id}}>
				<div class="ruleIcon">
					<img {{bind-attr src=child.icon}}/>
				</div>
				{{#if child.isDBRule}}
				<div class="name">
					{{child.name}}
				</div>
				{{/if}}
				<div class="description">
					{{#with child}}
						{{{view RuleWizard.ReadableView readable=readable}}}
					{{/with}}
				</div>
				<div class="buttonWrapper">
					<a class="button btn primary" {{action 'select' child target="controllers.application"}}>{{t 'ui.rules.68'}}</a>
					<a class="preview-link" {{bind-attr href=child.previewUrl}} target="_blank">{{t 'ui.rules.124'}}</a>					
				</div>
				
			</div>
			<hr class="divider" />
			{{/if}}
		{{/each}}
		</div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@rule-condition">
	{{partial "pageheader"}}	
	{{#if condition.isUrlParamsCondition}}
	    <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtRuleTriggerUrl"></span>
	{{else}}
	    <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtRuleTrigger"></span>
	{{/if}}
	<div class="pageSection fullBleed odd mainSection">
		{{#if condition.isCityCondition}}
			{{view RuleWizard.CitypickerView }}
		{{/if}}
		{{#if condition.isDeviceCondition}}		
			{{view RuleWizard.DevicepickerView }}
		{{/if}}
		{{#if condition.isTimeCondition}}
			{{view RuleWizard.DatepickerView content=model}}
		{{/if}}
		{{#if condition.isVisitsCondition}}
			{{view RuleWizard.VisitsView }}
		{{/if}}
		{{#if condition.isUrlParamsCondition}}
			{{view RuleWizard.UrlParamsView }}
		{{/if}}		
	</div>	
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@show-popup">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.53'}} {{controller.model.action.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{{controller.model.action.subtitle}}}</div>
		</div>
	</div>
		<div class="stepMain">
			<div class='parameterRow bottomMessageRow'>
				<label class='parameterLabel'>{{t 'ui.rules.246'}}</label>
			    {{view RuleWizard.Select
				    width=view.selectPagesWidth name="pageSelect" content=view.sitePages
				    optionLabelPath="content.itemTitle"
				    optionValuePath="content.pageAlias"
			        value=controller.model.firstPage}}				    
			</div>
			<div class='rightSideMessage'>				
				<small>{{t 'ui.rules.253'}}</small>
			</div>
			{{#if controller.controllers.application.hasPopups}}
				<div class='parameterRow'>
					<label for='useExistingPopup' class='parameterLabel'>{{t 'ui.rules.247'}}</label>
					{{view RuleWizard.Select				    	
					   width=view.selectPagesWidth name="popupSelect" content=view.sitePopups
					   optionLabelPath="content.itemTitle"
					   optionValuePath="content.itemValue"
					   value=view.popup}}
				</div>
				{{#if view.hasPopupsInPlan}}
				<div class='orStr'>
					{{t 'ui.rules.252'}}
				</div>
				<div class='parameterRow'>				
					<label class='parameterLabel radioButtonLabel'></label>				
					<a class="btn secondary newPopupButton" {{action 'newPopupInsiteMode' controller.controllers.application.rule target="controllers.application"}} ><span>{{t 'ui.rules.251'}}</span></a>
				</div>
				{{/if}}
			{{/if}}
				<div class="delay parameterRow">
					 <label>{{t 'ui.rules.254'}}:</label>
					<input type="radio" name="duration" id="durationforever"/><label for="durationforever">{{t 'ui.rules.153'}}</label>
					<input type="radio" name="duration" id="durationlimit"/><label for="durationlimit">{{t 'ui.rules.154'}} {{input class="seconds-picker" maxlength=3 value=controller.model.value3}} {{t 'ui.rules.40'}}</label>		
					<div class="error">{{errors.value3.firstObject}}</div>
				</div>
			</div>
		</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@rule-action">
	{{partial "pageheader"}}
    {{#if action.isChangeBackground}}
        <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtRuleChangeBgAction"></span>
    {{else}}
        {{#if action.isInjectScript}}
	        <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtRuleSpecialEffectAction"></span>
        {{else}}
    	    <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtRuleAction"></span>
        {{/if}}
    {{/if}}
	<div class="pageSection fullBleed odd mainSection">
		{{#if action.isAddRow}}
			{{view RuleWizard.AddRowView }}
		{{/if}}			
		{{#if action.isChangeBackground}}
			{{view RuleWizard.ChangeBgView }}
		{{/if}}			
		{{#if action.isInjectScript}}
			{{view RuleWizard.InjectScriptView }}
		{{/if}}	
		{{#if action.isMessage}}
			{{view RuleWizard.MessageView }}
		{{/if}}
		{{#if action.isCustomScript}}
			{{view RuleWizard.CustomScriptView }}
		{{/if}}					
		{{#if action.isShowPopup}}
			{{view RuleWizard.ShowPopupView }}
		{{/if}}	
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@wizard-done">
	{{partial "pageheader"}}
    <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtActivateRule"></span>
	<div class="pageSection pageSectionDone mainSection">
        <div class="stepHeader">
        	<div class="headerLeft"> 
				<h2>{{t 'ui.rules.6'}}</h2>
			</div>
        	<div class="headerRight"> 
				<div class="sub-title">{{t 'ui.rules.7'}}</div>
			</div>
		</div>
		<div class="stepMain">
			{{#if controller.controllers.application.isTrialExpired}}
            <div class="insiteTrialExpired">
                <span class="dm-icon-warning-sign"></span>
                {{t 'ui.rules.126'}} &nbsp;
                <a class="upgrade"><span>{{t 'ui.nee.framework.4'}}</span></a>
            </div>
            {{/if}}
            {{#if controller.controllers.application.isTrialNotStarted}}
	            <div class="insiteTrialExpired inTrial">
	                {{t 'ui.rules.139'}}
	            </div>
            {{/if}}
			{{#if controller.controllers.application.isInTrial}}
            <div class="insiteTrialExpired inTrial">
                {{t 'ui.rules.134' countBinding="controller.controllers.application.trialDays"}}
            </div>
			{{/if}}
			<div class="pageSection fullBleed parameter-picker finalizeInsite">
				<div class="parameterRow"> 
					 <label>{{t 'ui.rules.8'}}</label><br/>
					{{input class="ruleName" type="text" value=controller.controllers.application.rule.name}} 
				</div>
				<div class="parameterRow marginBottom"> 
					<div class="showOnce">
						{{input id="ruleWizardShowOnce" type="checkbox" checked=controller.controllers.application.rule.showOnce}} <label for="ruleWizardShowOnce">{{t 'ui.rules.62'}}</label>
					</div>
					<div class="buttons">
						<div class="L">
							<a href="javascript:;" class="previewLink btn secondary" {{action 'preview' controller.controllers.application.rule target="controllers.application"}}>
								{{t 'ui.rules.9'}}</a>
							
						</div>
						<div class="L save">
							<a class="btn primary" {{action 'save' controller.publishAfterSave target="controllers.application"}}>{{t 'ui.rules.10'}}</a>
							{{#if canPublishSite}}
								<br>			
								{{input id="publishAfterSave" type="checkbox" checked=controller.publishAfterSave}} <label for="publishAfterSave"><span><small>{{t 'ui.rules.11'}}</small></span></label> 
							{{/if}}
						</div>
					</div>
				</div>
				{{#if controller.controllers.application.hasUrl}}
					<div class="parameterRow"> 
						<a href="javascript:;" class="copy">{{t 'ui.copy.1'}}</a>
						 <label>{{t 'ui.rules.150'}}</label><br/>
						{{textarea rows=3 readonly="readonly" value=controller.controllers.application.copyUrl}}

					</div>
				{{/if}}
			</div>
		</div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@bfs-add-trigger">
	{{partial "pageheader"}}
    <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtBuildInsite"></span>
	<div class="pageSection fullBleed mainSection bfs-add bfs-add-trigger">
		<div class="stepHeader">
        	<div class="headerLeft"> 
				<h2>{{t 'ui.rules.86'}}</h2>
			</div>
        	<div class="headerRight"> 
				<div class="sub-title">{{t 'ui.rules.122'}}</div>
			</div>
		</div>
	<div class="stepMain">
		<div class="error">{{controller.controllers.application.errorMessage}}</div>
		{{view RuleWizard.AddTriggerView templateName="add-trigger-buttons"}}
	</div>
	{{#if controller.controllers.application.showAlwaysTrigger}}
	<div class="stepFooter">
       	<div class="footerLeft"> 
		<div class='parameterRow'>
			<div>
				{{#if controller.controllers.application.allSelected}}
					<input type="checkbox" id="showAlways" class="SettingsCheckbox" {{action 'toggleTrigger' controller.controllers.application.alwaysTriggerType target=controller.controllers.application id=alwaysTriggerType.id}} checked=checked />
					<label for="showAlways">
						<span class="SettingsCheckboxTextWrapper">{{t 'ui.rules.250'}}</span>
					</label>
				{{else}}
					<input type="checkbox" id="showAlways" class="SettingsCheckbox" {{action 'toggleTrigger' controller.controllers.application.alwaysTriggerType target=controller.controllers.application id=alwaysTriggerType.id}}/>
					<label for="showAlways">
						<span class="SettingsCheckboxTextWrapper">{{t 'ui.rules.250'}}</span>
					</label>
				{{/if}}
			</div>
		</div>
		</div>
    </div>
    {{/if}}
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@bfs-add-action">
	{{partial "pageheader"}}
    <span class="mindTouchHelp dm-icon-question-sign F1 insideWizard" id="dmMtBuildInsite"></span>
	<div class="pageSection fullBleed mainSection bfs-add bfs-add-action">
		<div class="stepHeader">
        	<div class="headerLeft"> 
				<h2>{{t 'ui.rules.87'}}</h2>
			</div>
        	<div class="headerRight"> 
				<div class="sub-title">{{t 'ui.rules.131'}}</div>
			</div>
		</div>
		<div {{bind-attr class=":stepMain controller.containerClass"}}>
			<div class="error">{{controller.controllers.application.errorMessage}}</div>
			{{#each action in controller.controllers.application.actionTypes}}
				<div {{bind-attr class=":multiselect action.icon action.activeClass"}} {{action 'changeAction' action target=controller.controllers.application}}>
					<div class="triggerTip">{{action.tip}}</div>
				    {{action.name}}
				    <div class="radio">
						<input type="radio" name="action" {{bind-attr checked=action.exists}}/> <label><span></span></label>
					</div>
				</div>
			{{/each}}
		</div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@add-trigger">
	<div class="expandRight">{{t 'ui.rules.83'}} <span class="dm-icon-chevron-right"></span></div>
	<div>
		{{#each trigger in controller.controllers.application.triggerTypes}}
				{{view Ember.Checkbox id=trigger.id checked=trigger.exists}} <label {{action 'toggleTrigger' trigger target=controller.controllers.application}} {{bind-attr for=trigger.id}}><span>{{trigger.name}}</span></label>				
		{{/each}}

		<div class="error">{{controller.controllers.application.triggerRemoveError}}</div>		
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@add-trigger-buttons">	
	<div>
		{{#each trigger in controller.controllers.application.triggerTypes}}
			{{#if trigger.isMainStepTrigger}}
				<div {{bind-attr class=":multiselect trigger.icon trigger.activeClass"}} {{action 'toggleTrigger' trigger target=controller.controllers.application}}>
					<div class="triggerTip">{{trigger.tip}}</div>
				    {{trigger.name}}
				</div>
			{{/if}}	
		{{/each}}
	</div>
	<!--
	<div id='selectAll'>
		<div class='parameterRow'>
			<div>
				<input type="checkbox" id='showAlways' class="SettingsCheckbox"{{action 'toggleTrigger' controller.controllers.application.alwaysTriggerType target=controller.controllers.application id=alwaysTriggerType.id}}>
				<label for="showAlways">
					<span class="SettingsCheckboxTextWrapper">All site visitors (don't user a trigger)</span>
				</label>
			</div>
		</div>
	</div>
	-->
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@url-params-input">
	{{#with controller}}
		<div class="stepHeader">
        	<div class="headerLeft"> 
				<h2><span class="stepTitle">{{t 'ui.rules.55'}} {{model.condition.title}}</span></h2>
			</div>
        	<div class="headerRight"> 
				<div class="sub-title">{{{controller.model.condition.subtitle}}}</div>
			</div>
		</div>
		<div class="stepMain">
			<div class="parameterRow">
				 <label>{{t 'ui.rules.140'}}</label><br>
				{{input value=model.value1 placeholder="category=italian&speciality=lasagna"}}<br>
				<small class='description-label'>{{t 'ui.rules.141'}}</small>
				<div class="error">{{errors.value1.firstObject}}</div>
			</div>
			
			
			<a class="toggleLink urlBuilder">{{t 'ui.rules.148'}} <i class="dm-icon-chevron-right"></i></a>
            <div class="toggleContent">
				<div class="parameterRow">
	            	<div class="input-box">
	            		 <label>{{t 'ui.rules.142'}}</label><br>
		            	{{input value=view.campaignSource}}
	            	</div>
	            	<div class="input-box">
	            		 <label>{{t 'ui.rules.143'}}</label><br>
		            	{{input value=view.campaignMedium}}
	            	</div>
	            	<div class="input-box">
	            		 <label>{{t 'ui.rules.144'}}</label><br>
		            	{{input value=view.campaignTerm}}
	            	</div>
	            </div>
				<div class="parameterRow">
	            	<div class="input-box">
	            		 <label>{{t 'ui.rules.145'}}</label><br>
		            	{{input value=view.campaignContent}}
	            	</div>
	            	<div class="input-box">
	            		 <label>{{t 'ui.rules.146'}}</label><br>
		            	{{input value=view.campaignName}}
	            	</div>
	            	<div class="input-box">
	            		<a class="learnMore" target="_blank" href="https://support.google.com/analytics/answer/1033867">{{t 'ui.rules.147'}}</a>
	            	</div>
	            </div>
            </div>
            {{#if view.showCampaignsSelect}}
            <div class="campaignSelect parameterRow">
					<label class="title">{{t 'ui.rules.url.cookie.1'}}:</label>

					{{view Ember.RadioButton name="campaign" selectionBinding="model.value2" value="session" id="session"}}
					<label for="session">
            			{{t 'ui.rules.url.cookie.3'}}
        			</label>
        			
        			{{view Ember.RadioButton name="campaign" selectionBinding="model.value2" value="days" id="days"}}
        			<label for="days">
            			{{t 'ui.rules.url.cookie.4'}}
        			</label> 
            		
            		{{input class="days-picker" maxlength=3 value=model.value3}} {{t 'ui.rules.url.cookie.5' classNames="days"}}
       			
        			{{view Ember.RadioButton name="campaign" selectionBinding="model.value2" value="none" id="none" }}
        			<label for="none">
            			{{t 'ui.rules.url.cookie.2'}}
        			</label>
        			 
        			

			</div>
			{{/if}}
			{{view RuleWizard.AddTriggerView}}
		</div>
	{{/with}}
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@visits-input">
	{{#with controller}}
		<div class="stepHeader">
        	<div class="headerLeft"> 
				<h2><span class="stepTitle">{{t 'ui.rules.55'}} {{model.condition.title}}</span></h2>
			</div>
        	<div class="headerRight"> 
				<div class="sub-title">{{controller.model.condition.subtitle}}</div>
			</div>
		</div>
		<div class="stepMain">
			{{#form-for model}}
				<div class="parameterRow">
					<div {{action "setValueOne"}} class="firstTimeVisitor">
					    <svg class="icon-first-user" viewBox="0 0 32 32">
				            <use xlink:href="#icon-first-user"></use>
				        </svg>
						{{t 'ui.rules.135'}}
					</div>
					<div {{action "setValueMoreThanOne"}} class="returningVisitor">
						{{#input value1}}
						    <svg class="icon-rotate" viewBox="0 0 32 32">
					            <use xlink:href="#icon-rotate"></use>
					        </svg>
							
							{{input-field value1}}<span class="stepMain-nth">{{nth}}</span> {{t 'ui.rules.13'}}
						{{/input}}
						<div class="error">{{errors.value1.firstObject}}</div>
					</div>
				</div>
			{{/form-for}}
			<div class="notes description-label">{{model.condition.notes}}</div>
			{{view RuleWizard.AddTriggerView}}
		</div>
	{{/with}}
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@datepicker">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.55'}} {{content.condition.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{content.condition.subtitle}}</div>
		</div>
	</div>
	<div class="stepMain">
		<div class="parameterRow datepickerRow">
			<label class="expandRight expanded" rel="datepicker">{{t 'ui.rules.52'}} <span class="dm-icon-chevron-right"></span></label>
			<div class="eventData">
				{{view.showEndDate}}
				<div class="startTime L">
					 <label>{{t 'ui.rules.63'}}</label><br>
					<span class="inputWrapper"><span class="dm-icon-calendar"></span> {{input readonly=true class="datepicker" type="text" value=view.startDate size="10"}}</span>
				</div>
				<div {{bind-attr class=":L view.allDay"}}>
					 <label>{{t 'ui.rules.15'}}</label><br>
					{{input class="timepicker" type="text" value=view.startTime size="5"}}
				</div>
				<div {{bind-attr class=":L view.allDay"}}>
					 <label>{{t 'ui.rules.16'}}</label><br>
					{{input class="timepicker" type="text" value=view.endTime size="5"}} 
				</div>
				<div {{bind-attr class=":L view.showEndDateClass"}}>
					 <label>{{t 'ui.rules.64'}}</label><br>
					<span class="inputWrapper">
						<span class="dm-icon-calendar"></span> {{input readonly=true class="datepicker" type="text" value=view.endDate size="10"}}
					</span>
				</div>
				<div {{bind-attr class=":L :showEndDateLink view.showEndDateClass"}}>
					<a href="javascript:;" {{action 'showEndDate'}}>{{t 'ui.rules.65'}}</a>
				</div>
				<div class="error">{{errors.value1.firstObject}}</div> 
				<div class="parameterRow">
					<div class="alldayChkbox L">
						{{input id="ruleWizardAllDay" type="checkbox" checked=view.allDay}} <label for="ruleWizardAllDay"><span>{{t 'ui.rules.17'}}</span></label>
					</div>

					<div class="timeZoneDD L">
						<label class="L">{{t 'ui.rules.18'}}:</label>
						<div class="L"> 
						{{view RuleWizard.TimezoneSelect 
							width=260 name="timezones" content=view.timezones
				            optionLabelPath="content.name"
			                optionValuePath="content.value"
			                value=view.timezone}}
			            </div>
			        </div>
				</div>
			</div>
		</div>
		<div class="parameterRow datepickerRow topBorder">
			<label class="expandRight" rel="datepicker">{{t 'ui.rules.19'}} <span class="dm-icon-chevron-right"></span></label>
			<div>
				{{input class="rrule" type="hidden" value=content.value4}}
				<form class="rruleForm">						
					{{view RuleWizard.Select 
						width=445 height=150 name="freq" content=view.frequencies
			            optionLabelPath="content.label"
		                optionValuePath="content.id"
		                value=view.freq}}

					<div class="wkdaySelect parameterRow">
						{{view Ember.Checkbox id="wkdaySelectMon" checked=view.mon}} <label for="wkdaySelectMon"><span>{{t 'ui.rules.20'}}</span></label>
						{{view Ember.Checkbox id="wkdaySelectTue" checked=view.tue}} <label for="wkdaySelectTue"><span>{{t 'ui.rules.21'}}</span></label>
						{{view Ember.Checkbox id="wkdaySelectWed" checked=view.wed}} <label for="wkdaySelectWed"><span>{{t 'ui.rules.22'}}</span></label>
						{{view Ember.Checkbox id="wkdaySelectThu" checked=view.thu}} <label for="wkdaySelectThu"><span>{{t 'ui.rules.23'}}</span></label>
						{{view Ember.Checkbox id="wkdaySelectFri" checked=view.fri}} <label for="wkdaySelectFri"><span>{{t 'ui.rules.24'}}</span></label>
						{{view Ember.Checkbox id="wkdaySelectSat" checked=view.sat}} <label for="wkdaySelectSat"><span>{{t 'ui.rules.25'}}</span></label>
						{{view Ember.Checkbox id="wkdaySelectSun" checked=view.sun}} <label for="wkdaySelectSun"><span>{{t 'ui.rules.26'}}</span></label>
					</div>

					<div class="bymonthdaySelect parameterRow">
						 <label>{{t 'ui.rules.27'}}: </label>{{input type="text" readonly=true class="multidatepicker" value=view.bymonthday size="500"}}
					</div>
					<div class="repeatEnd parameterRow">
						<label class="L">{{t 'ui.rules.28'}}</span></label> 
						<div class="L">
							<input type="radio" name="repeatend" id="repeatendoff"/><label for="repeatendoff">{{t 'ui.rules.56'}}</label>
							<input type="radio" name="repeatend" id="repeatendon"/><label for="repeatendon">{{t 'ui.rules.29'}} </label>
							<span class="inputWrapper">
								<span class="dm-icon-calendar"></span> {{input readonly=true type="text" class="datepicker" value=view.until}}
							</span>
						</div>
						<div class="error">{{errors.value4.firstObject}}</div>
					</div>
				</form>
			</div>
			<a class="previewCalendar" href="javascript:;" {{action 'previewCalendar'}}>{{t 'ui.rules.60'}}</a>
			<div id="previewFullCalendarContainer"></div>
		</div>
		{{view RuleWizard.AddTriggerView}}
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@devicepicker">
	<div class="stepHeader">
		<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.53'}} {{controller.model.condition.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{controller.model.condition.subtitle}}</div>
		</div>
	</div>
	<div class="stepMain">
		<div class="center">
			<div class="device-picker">
				{{#each device in view.devices}}
					<div {{bind-attr class=":multiselect device.icon device.selected"}} {{action 'toggleDevice' device.id}}>{{device.displayName}}</div>
				{{/each}}
			</div>
		</div>
		{{view RuleWizard.AddTriggerView}}
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@citypicker">
	<div class="stepHeader">
		<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.55'}} {{controller.model.condition.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{controller.model.condition.subtitle}}</div>
		</div>
	</div>
	<div class="stepMain">
		{{#form-for controller.model}}
			{{#input value1}}
	  			{{input-field value1 placeholderTranslation="ui.rules.30" name="location"}}
	  			{{error-field value1}}
			{{/input}}
			<div class="error">{{errors.value2.firstObject}}</div>
		{{/form-for}}

		<div class="mapCanvas"></div>
		<div class="notes description-label">{{controller.model.condition.notes}}</div>
		{{view RuleWizard.AddTriggerView}}
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@addrow">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.53'}} {{controller.model.action.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{{controller.model.action.subtitle}}}</div>
		</div>
	</div>
	<div class="stepMain">
	<div>
		<div class="parameterRow">
			 <label class='parameterLabel'>{{t 'ui.rules.246'}}</label>
		    {{view RuleWizard.Select
			    width=view.selectPagesWidth name="pageSelect" content=view.sitePages
			    optionLabelPath="content.itemTitle"
			    optionValuePath="content.pageAlias"
			    value=controller.model.firstPage}}
		</div>
		{{#if view.isBfs}}
		<div class="parameterRow">    
			{{#if controller.controllers.application.rule.actions.firstObject.action.isAddRow}}
			<div class="chooseAction">
				 <label class='parameterLabel'>{{t 'ui.rules.123'}}:</label>
				{{view RuleWizard.Select 
						width=view.selectPagesWidth height=150 name="section" content=controller.sectionTypes
			            optionLabelPath="content.value"
		                optionValuePath="content.id"
		                value=controller.controllers.application.rule.actions.firstObject.value1	                
		        }}
		    </div>
			{{/if}}
		</div>
		{{/if}}
	</div>		
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@message">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.55'}} {{controller.model.action.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{{controller.model.action.subtitle}}}</div>
		</div>
	</div>
	<div class="stepMain">
		<div class="error">{{errors.value1.firstObject}}</div>
		{{view Ember.ContenteditableView pastePlain=true style=view.bgColorStyle editable=true value=view.msgBody}}
		<div class="toolbar">
			<div class="dm-icon-bold" data-command="bold"></div>
			<div class="dm-icon-italic" data-command="italic"></div>
			<div class="dm-icon-underline" data-command="underline"></div>
			<div class="dm-icon-font colorPicker" data-command="foreColor">
				<div class="currentColor"></div>
				<div class="pickerWrapper"></div>
			</div>
			<div class="colorPicker" data-command="bgColor">
				<div class="bgColor" {{bind-attr style=view.bgColorStyle}}></div>
				<div class="pickerWrapper"></div>
			</div>
			<div class="divider"></div>
			<div class="hasValue" data-command="fontName">
				<select id="ruleWizardSelectFontName">
				{{#each view.fonts}}
					<option value="{{this}}">{{this}}</option>
				{{/each}}
				</select>
			</div>
			<div class="hasValue" data-command="fontSize">
				<select id="ruleWizardSelectFontSize">
					<option value="2">Smaller</option>
					<option value="3">Small</option>
					<option value="4">Medium</option>
					<option value="5">Large</option>
					<option value="6">Larger</option>
				</select>
			</div>
			<div class="divider"></div>
			<div class="dm-icon-link" data-command="createLink"></div>
			<div class="dm-icon-undo" data-command="undo"></div>
			<div class="dm-icon-redo" data-command="redo"></div>
		</div>

	    <div class="preview-position">
    		<a class="previewButton btn secondary" {{action preview}}>{{t 'ui.rules.124'}}</a>
            <a class="toggleLink">{{t 'ui.rules.125'}} <i class="dm-icon-chevron-right"></i></a>

            <div class="toggleContent">
			    <div class="pageSelect parameterRow">
				     <label>{{t 'ui.rules.157'}}:</label>
				    <input type="radio" {{bind-attr checked=controller.pagesHome}}/><label {{action 'setPages' 'home'}}><span>{{t 'ui.rules.136'}}</span></label>
				    <input type="radio" {{bind-attr checked=controller.pagesAll}}/><label  {{action 'setPages' '*'}}><span>{{t 'ui.rules.137'}}</span></label>
			    </div>
				<div class="delay parameterRow">
					 <label>{{t 'ui.rules.152'}}:</label>
					<input type="radio" name="duration" id="durationforever"/><label for="durationforever">{{t 'ui.rules.153'}}</label>
					<input type="radio" name="duration" id="durationlimit"/><label for="durationlimit">{{t 'ui.rules.154'}} {{input class="seconds-picker" maxlength=3 value=controller.model.value3}} {{t 'ui.rules.40'}}</label>		
					<div class="error">{{errors.value3.firstObject}}</div>
				</div>
				<div class="duration parameterRow">
					 <label>{{t 'ui.rules.155'}}:</label>
					<input type="radio" name="hideAfter" id="hideNever"/><label for="hideNever">{{t 'ui.rules.156'}}</label>
					<input type="radio" name="hideAfter" id="hideLimit"/><label for="hideLimit">{{t 'ui.rules.154'}} {{input class="seconds-picker" maxlength=3 value=controller.model.value2}} {{t 'ui.rules.40'}}</label>		
					<div class="error">{{errors.value2.firstObject}}</div>
				</div>
			</div>
    	</div>
	</div>
</script>

<!-- custom script action -->

<script type="text/x-handlebars" data-template-name="rule-wizard@custom-script">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.55'}} {{controller.model.action.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{{controller.model.action.subtitle}}}</div>
		</div>
	</div>
	<div class="stepMain">
		<div class="error">{{errors.value1.firstObject}}</div>
		<div class="js-editor">
		{{ace-editor classNames='func start' readonly='true' value="function ($, dmapi) {/* Write your javascript code here */"}}	
		{{ace-editor classNames='content' value=controller.model.customScript}}
		{{ace-editor classNames='func end' readonly='true' value=" } /* function end */"}}
		</div>
	    <div class="preview-position">
    		<a class="previewButton btn secondary" {{action preview}}>{{t 'ui.rules.124'}}</a>
            <a class="toggleLink">{{t 'ui.rules.125'}} <i class="dm-icon-chevron-right"></i></a>

            <div class="toggleContent">
			    <div class="pageSelect parameterRow">
				     <label>{{t 'ui.rules.157'}}:</label>
				    <input type="radio" {{bind-attr checked=controller.pagesHome}}/><label {{action 'setPages' 'home'}}><span>{{t 'ui.rules.136'}}</span></label>
				    <input type="radio" {{bind-attr checked=controller.pagesAll}}/><label  {{action 'setPages' '*'}}><span>{{t 'ui.rules.137'}}</span></label>
			    </div>
			</div>
    	</div>
		
	</div>
</script>
<!-- custom script action end -->

<script type="text/x-handlebars" data-template-name="rule-wizard@changebg">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.53'}} {{controller.model.action.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{controller.model.action.subtitle}}</div>
		</div>
	</div>
	<div class="stepMain">
	    {{view RuleWizard.EventTypeSelect
		    width=474 name="eventType" content=view.events.content
		    optionLabelPath="content.label"
		    optionValuePath="content.id"
		    value=view.selectedEvent}}

    	{{#if view.custom}}
		    {{#if view.isImageEmpty}}
		    	<div {{action selectNewImage}} class="smallTempPlaceHlderForImage"></div>
		    {{else}}
			    <div class="custom" {{bind-attr class="view.isCustom"}}>
			        <div class="image" {{bind-attr style=view.customStyle}}>
			            <div class="itemOverlay">
			            	<div class="itemButtons">
			            		<div class="dm-icon-zoom-in"></div>
			            	</div>
			            </div>
			        </div>
			    </div>
			{{/if}}
	    {{else}}
		    <div class="bg-slider" {{bind-attr class="view.isNotCustom"}}>
		    	{{#each image in view.images}}
		    		<div>
		    			<div {{bind-attr class=":image image.selectedClass"}} {{bind-attr style=image.style}}>
		    				<div class="itemOverlay">
		    					<div class="itemButtons">
		    						<div {{action 'updateValue1' image.src}} class="itemSelector">{{t 'ui.rules.32'}}</div>
		    						<a {{bind-attr href=image.src}} class="dm-icon-zoom-in"></a>
		    					</div>
		    				</div>
		    			</div>
		    		</div>
		    	{{/each}}
		    </div>
	    {{/if}}


	    <a {{action selectNewImage}} class="button new-image-button">{{t 'ui.rules.33'}}</a>

	    <div class="preview-position topBorder">
	        <div style="float:left">
	            <a class="toggleLink">{{t 'ui.rules.125'}} <i class="dm-icon-chevron-right"></i></a>

	            <div class="toggleContent">
				    <div class="pageSelect">
					     <label>{{t 'ui.rules.157'}}:</label>
					    <input type="radio" {{bind-attr checked=controller.pagesHome}}/><label {{action 'setPages' 'home'}}><span>{{t 'ui.rules.136'}}</span></label>
					    <input type="radio" {{bind-attr checked=controller.pagesAll}}/><label  {{action 'setPages' '*'}}><span>{{t 'ui.rules.137'}}</span></label>
				    </div>
		            <label class="positionLabel">{{t 'ui.rules.34'}}:</label>
		            <div class="bgImageCtrls">
		                <div {{action 'updateValue2' 'cover'}} {{bind-attr class=":bgCtrlButton :bgLayoutButton view.coverClass"}} data-bgattr="background-size" data-bgeffect="cover"
		                     data-bgattrreset="background-repeat" data-bgeffectreset="no-repeat"
		                     data-tooltip="Your site background image will resize itself to fit the screen"
		                     aria-describedby="ui-tooltip-12">
		                    <div class="bgCtrlIcon  centered dm-icon-img_full" style="font-size: 32px;"></div>
		                    <div class="bgCtrlName">{{t 'ui.rules.35'}}</div>
		                </div>
		                <div {{action 'updateValue2' 'repeat'}} {{bind-attr class=":bgCtrlButton :bgLayoutButton view.repeatClass"}} data-bgattr="background-repeat" data-bgeffect="repeat"
		                     data-bgattrreset="background-size" data-bgeffectreset="auto"
		                     {{translateAttr data-tooltip='ui.rules.37'}}
		                     aria-describedby="ui-tooltip-13">
		                    <div class="bgCtrlIcon  centered dm-icon-img_tile"></div>
		                    <div class="bgCtrlName">{{t 'ui.rules.36'}}</div>
		                </div>
		            </div>
		        </div>
	        </div>

	        <a class="previewButton btn secondary" {{action preview}}>{{t 'ui.rules.124'}}</a>
	    </div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@inject-script">
	<div class="stepHeader">
    	<div class="headerLeft"> 
			<h2><span class="stepTitle">{{t 'ui.rules.53'}} {{controller.model.action.title}}</span></h2>
		</div>
    	<div class="headerRight"> 
			<div class="sub-title">{{controller.model.action.subtitle}}</div>
		</div>
	</div>
	<div class="stepMain">
	    <div class="bg-slider">
	    	{{#each script in view.scripts}}
	    		<div>
	    			<div {{bind-attr class="script.selectedClass :image"}}>
	    				{{#if script.hasThumbnail}}
	    					<img {{bind-attr src=script.thumbnail}}/>
	    				{{else}}
	    					<iframe width="240px" height="180px" {{bind-attr class="script.selectedClass" src=script.preview}}>
		    				</iframe>
	    				{{/if}}
	    				<div class="title description-label">{{script.title}}</div>
	    				<div class="itemOverlay">
	    					<div class="itemButtons">
	    						<div {{action 'selectScript' script}} class="itemSelector">{{t 'ui.rules.32'}}</div>
	    						<a {{bind-attr href=script.preview}} target="_blank" class="dm-icon-zoom-in"></a>
	    					</div>
	    				</div>
	    			</div>
	    		</div>
	    	{{/each}}
	    </div>
	    
	    <div class="preview-position topBorder">
    		<a class="previewButton btn secondary" {{action preview}}>{{t 'ui.rules.124'}}</a>
            <a class="toggleLink">{{t 'ui.rules.125'}} <i class="dm-icon-chevron-right"></i></a>

            <div class="toggleContent">
			    <div class="pageSelect">
				     <label>{{t 'ui.rules.157'}}:</label>
				    <input type="radio" {{bind-attr checked=controller.pagesHome}}/><label {{action 'setPages' 'home'}}><span>{{t 'ui.rules.136'}}</span></label>
				    <input type="radio" {{bind-attr checked=controller.pagesAll}}/><label  {{action 'setPages' '*'}}><span>{{t 'ui.rules.137'}}</span></label>
			    </div>
				<div class="duration parameterRow">
					 <label>{{t 'ui.rules.158'}}:</label>
					<input type="radio" name="duration" id="durationforever"/><label for="durationforever">{{t 'ui.rules.38'}}</label>
					<input type="radio" name="duration" id="durationlimit"/><label for="durationlimit">{{t 'ui.rules.39'}} {{input class="seconds-picker" type="text" value=controller.model.value2}} {{t 'ui.rules.40'}}</label>		
				</div>
			</div>
    	</div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@_pageheader">
	<div {{bind-attr class=":pageSection :fullBleed :header controller.controllers.application.ruleStatusClass"}}>
		{{#with controller.controllers.application.rule}}
			<div class="headerTop" {{bind-attr data-rule-id=type}}>
				<div class="headerLeft">
					{{#if isBfs}}
						<div class="ruleIcon">
							<svg viewBox="0 0 32 32">
								<use xlink:href="#icon-plus"></use>
							</svg>
						</div>
					{{else}}
						<div class="ruleIcon">
							<img {{bind-attr src=icon}}/>
						</div>
					{{/if}}					
					<h2>{{typeName}}</h2>
				</div>
				<div class="headerRight">
					{{#with controller.controllers.application}}
						{{#if currentStep.showProgress}}
							<div {{bind-attr class="totalStepsClass :wizardStepsWrapper"}}>
								{{#each step in steps}}  
									{{#if step.showProgress}}
									{{#unless step.hideFromProgress}}
										<div {{action 'gotoStep' step target='controllers.application'}} {{bind-attr class="step.complete step.lastClass step.currentClass :wizardStep"}}>
											{{smart-icon icon=step.icon item=step.item title=step.title}}
										</div>
									{{/unless}}
									{{/if}}
								{{/each}} 
							</div>
						{{/if}}
					{{/with}}
				</div>
			</div>
			<div class="headerSub">
				<div class="headerLeft">
					<h2>{{t 'ui.rules.81'}}</h2>
				</div>
				<div class="headerRight">
					<div class="readable">{{{view RuleWizard.ReadableContainerView}}}</div>
				</div>
			</div>
		{{/with}}
	</div>
	<div id="ruleWizardSuccessOverlay"><span class="dm-icon-saved"></span><br>{{t 'ui.rules.41'}}</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@_footer">
	{{#if currentStep.showFooter}}
		<div class="footer">
			{{#if currentStep.showBack}}
			<div class="back" {{action 'back'}}><i class="dm-icon-chevron-left"></i> {{t 'ui.rules.42'}}</div>
			{{/if}}
			{{#if currentStep.showNext}}
				{{#if inDraftMode}}
					<div class="next btn primary" {{action 'next'}}>{{t 'ui.rules.43'}}</div>
				{{else}}
					<div class="nextLink btn secondary" {{action 'next'}}> {{t 'ui.rules.59'}}</div>
					<div class="next btn primary" {{action 'save'}}>{{t 'ui.rules.44'}}</div>
				{{/if}}
			{{/if}}
		</div>
	{{/if}}
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@error">
	<div class="pageSection">
		<h3>{{t 'ui.rules.45'}}</h3>
		<div>
			{{message}}
		</div>
	</div>
</script>

<script type="text/x-handlebars" data-template-name="rule-wizard@loading">
	<div class="pageSection loading">
	</div>
</script>

      

</div>
    <!--  begin no internet section -->
	<div id="dmNoInternetMaskWrapper">
        <div id="dmNoInternetMask">
            <div id="dmNoInternetMaskText">Uh oh, lost the network connection. Trying to reconnect...</div>
	 </div>
 </div>
 
 <div id="dmNoInternetMaskWrapperNew" style="display: none;">
        <div id="dmNoInternetMaskNew">
            <div id="dmNoInternetPopup">
                <div id="dmNoInternetTitle">Oops, Lost Connection</div>
                <div id="noInternetIcon"></div>
                <div id="dmNoInternetMaskTextNew">Seems like we lost the network connection. Trying to reconnect...</div>
            </div>
     </div>
 </div>
 <!--  end no internet section -->
 
<!-- Ink file picker -->
<script type="text/javascript">
(function(a){if(window.filepicker){return}var b=a.createElement("script");b.type="text/javascript";b.async=!0;b.src=("https:"===a.location.protocol?"https:":"http:")+"//api.filestackapi.com/filestack.js";var c=a.getElementsByTagName("script")[0];c.parentNode.insertBefore(b,c);var d={};d._queue=[];var e="pick,pickMultiple,pickAndStore,read,write,writeUrl,export,convert,store,storeUrl,remove,stat,setKey,constructWidget,makeDropPane".split(",");var f=function(a,b){return function(){b.push([a,arguments])}};for(var g=0;g<e.length;g++){d[e[g]]=f(e[g],d._queue)}window.filepicker=d;filepicker.setKey('ADRwU0cjTTKCBEFZ1rzSAz');})(document); 
</script>

<div id="fb-root"></div>
<script>
    window.fbAppId = '126515034112906';
</script>


<!-- WL Custom Html Begin -->
<!-- WL Custom Html End -->

<script type="text/javascript">
        </script>
    <script type="text/x-handlebars" id="components/spinner-loader">	
</script><script type="text/x-handlebars" id="components/ace-editor">
    <div class="ember-ace-editor-wrapper" {{bind-attr id=aceEditorId}} >
     
    </div>
</script><script type="text/x-handlebars" id="components/one-color-picker">
	<div class='color-picker-box' {{bind-attr style=style}}>
	</div>
	<div picker-wrapper>
	</div>
</script><img style="position:absolute; visibility:hidden;height:0;width:0"
         src="https://px.multiscreensite.com/_blank"/>

    <script>
        registerScriptToLoadWhenIdle('//js.hs-scripts.com/4790854.js');
    </script>
</body>
</html>
