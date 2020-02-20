<template>
<section class="postPopup">
    <div class="postPopupCancel">
        <div class="postPopupExit">
            <img src="images/cancel.png" alt="">
        </div>

    </div>
    <div class="postPopupContainer">
        <div class="postPopupbox">
            <div class="postPopupImg">

                <img src="images/1.jpg" alt="">

            </div>



        </div>

        <div class="postPopupContent">

            <div class="postPopupTitle">
                <h2>title</h2>
                <h3>2020-01-20</h3>
                <div>
                    <img src="images/cloud2.png" alt="">
                    <div>0</div>
                    
                </div>
            </div>
            <div class="postPopupContext">

                asdjfklasjdfl;ajsld;fja;lsdjf
                asdjfkl;ajsdk;lfkjas;lfkjdas;lf
                ajsdlf;kjas;ldfjk;lasdjkfl;


            </div>



        </div>
    </div>

</section>

</template>

<script>
export default {};
</script>
<style lang="">

  * {
        box-sizing: border-box;
        letter-spacing: .01em;
    }

    .postPopup {
        position: fixed;
        top: 0;
        left: 0;

        height: 100vh;
        width: 100%;
        padding-right: 1em;
        padding-left: 1em;

        background-color: rgba(0, 0, 0, .8);
        text-align: center;



    }

    .postPopupContainer {
        width: 80%;
        min-height: 34em;
      
        display: flex;
        max-width: 65em;
        margin: 0 auto;
        margin-top: 2%;
        height:94%;



    }

    .postPopupbox {
        flex-basis: 55%;
        max-width: 57%;
        position: relative;
        display: block;
        background-color: #f8f8f8;

    }

    .postPopupImg {
        position: absolute;
        top: 0;
        left: 0;
        z-index: 0;
        height: 100%;
        width: 100%;
      
        overflow: hidden;

    }

    .postPopupImg>img {
        width: 100%;
    }

    .postPopupContent {
        flex-direction: column;
   
        flex-basis: 50%;
        padding-left: 2em;
        padding-right: 2em;
    }

    .postPopupContainer,
    .postPopupbox,
    .postPopupbox,
    .postPopupImg,
    .postPopupContent {
        display: flex;
     background-color:white;

    }
 
    .postPopupTitle {
        width: 100%;
        text-align: center;
        border-bottom: 1px solid rgba(0, 0, 0, .1);
        height: 199px;
        padding-top: 41px;
    }

    .postPopupContext {
        width: 100%;
        height: 100%;
 
        text-align: center;

    }

    .postPopupTitle>div>img {
        width: 16px;
    }

    .postPopupTitle>div {

        padding-left: 243px;
    }

    .postPopupCancel {
        position: fixed;
        z-index: 999;
        height: 2.25rem;
        width: 2rem;
        border: none;
        margin-left: 91%;
    }

    .postPopupCancel>.postPopupExit {
        position: absolute;
        top: 1em;
        background-color: white;
        display: block;
        height: 32px;
    }

    .postPopup>.postPopupCancel>.postPopupExit>img {
        width: 100%;

    }


</style>