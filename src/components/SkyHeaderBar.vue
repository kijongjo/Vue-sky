<template>
   <header>
    <a href="">SkyProject</a>
    <nav>
   
        <ul>
            
            <li>
                <a href="">Today</a>
            </li>
            <li>
                <a href=""> Best</a>
            </li>
            <li>
             <span> Login</span>

            </li>
            <li>Write</li>
        </ul>
    </nav>
</header>
</template>


<script>
export default {
    
}
</script>


<style lang="">
 html, body, div, span, applet, object, iframe,

h1, h2, h3, h4, h5, h6, p, blockquote, pre,

a, abbr, acronym, address, big, cite, code,

del, dfn, em, img, ins, kbd, q, s, samp,

small, strike, strong, sub, sup, tt, var,

b, u, i, center,

dl, dt, dd, ol, ul, li,

fieldset, form, label, legend,

table, caption, tbody, tfoot, thead, tr, th, td,

article, aside, canvas, details, embed, 

figure, figcaption, footer, header, hgroup, 

menu, nav, output, ruby, section, summary,

time, mark, audio, video {

    margin: 0;

    padding: 0;

    border: 0;

    font-size: 100%;

    font: inherit;

    vertical-align: baseline;
     box-sizing: border-box;
}
    
    header{font-size:.8em;}
    header >nav >ul{display:flex;
        align-items:center; 
    list-style-type:none;
    padding-right:3em;
      }
    
    header{padding-left:2em;
            padding-right:2em;
         position:fixed;
    top:0;
    left:0;
    z-index:999;
    display:flex;
    align-items:center;
    justify-content:space-between;
    height:4em;
    width:100%;
    padding-right:1em;
    padding-left:1em;
    background-color:#fff;
    border-bottom:1px solid rgba(0,0,0,.1);}

a:link {text-decoration: none; color: black;}
a:visited {text-decoration: none; color: black;}
a:active {text-decoration: none; color: black;}
a:hover {text-decoration: underline; color: black;}
   
    header >nav >ul>li{margin-left:2em;}
   
    nav{display:block;}

</style>





