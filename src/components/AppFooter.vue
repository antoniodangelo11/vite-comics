<script></script>

<template>
    <footer>
        <section class="footer_up">
            <div class="options">
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <p>DIGITAL COMICS</p>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <p>DC MERCHANDISE</p>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <p>SUBSCRIPTION</p>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <p>COMIC SHOP LOCATOR</p>
                </div>
                <div>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <p>DC POWER VISA</p>
                </div>
            </div>
        </section>
        <section class="footer_mid">
            <div class="contacts">
                <div>
                    <div class="column">
                        <ul>
                            <li class="title">DC COMICS</li>
                            <li>
                                <a href="">Characters</a>
                            </li>
                            <li>
                                <a href="">Comics</a>
                            </li>
                            <li>
                                <a href="">Movies</a>
                            </li>
                            <li>
                                <a href="">TV</a>
                            </li>
                            <li>
                                <a href="">Games</a>
                            </li>
                            <li>
                                <a href="">Videos</a>
                            </li>
                            <li>
                                <a href="">News</a>
                            </li>
                        </ul>

                        <ul>
                            <li class="title">SHOP</li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC Collectibles</a>
                            </li>
                        </ul>
                    </div>

                    <div>
                        <ul>
                            <li class="title">DC</li>
                            <li>
                                <a href="">Terms Of Use</a>
                            </li>
                            <li>
                                <a href="">Privacy policy (New)</a>
                            </li>
                            <li>
                                <a href="">Ad Choices</a>
                            </li>
                            <li>
                                <a href="">Advertising</a>
                            </li>
                            <li>
                                <a href="">Jobs</a>
                            </li>
                            <li>
                                <a href="">Subscriptions</a>
                            </li>
                            <li>
                                <a href="">Talent Workshops</a>
                            </li>
                            <li>
                                <a href="">CPSC Certificates</a>
                            </li>
                            <li>
                                <a href="">Ratings</a>
                            </li>
                            <li>
                                <a href="">Shop Help</a>
                            </li>
                            <li>
                                <a href="">Contact Us</a>
                            </li>
                        </ul>
                    </div>

                    <div>
                        <ul>
                            <li class="title">SITES</li>
                            <li>
                                <a href="">DC</a>
                            </li>
                            <li>
                                <a href="">MAD Magazine</a>
                            </li>
                            <li>
                                <a href="">DC Kids</a>
                            </li>
                            <li>
                                <a href="">DC Universe</a>
                            </li>
                            <li>
                                <a href="">DC Power Visa</a>
                            </li>
                        </ul>
                    </div>
                </div>

                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </section>
        <section class="footer_bot">
            <div class="socials">

                <button>SIGN-UP NOW!</button>


                <div>
                    <h3>FOLLOW US</h3>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </section>
    </footer>
</template>

<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;

.footer_up {
    background-color: rgb(2, 130, 249);
}

.options {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10rem;

    div {
        display: flex;
        align-items: center;
        padding-inline: 1.5rem;

        img {
            width: 40px;
        }

        p {
            color: rgb(255, 255, 255);
            white-space: nowrap;
            padding-inline: 1.2rem;
            font-size: .9rem;
        }
    }


}

.footer_mid {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    overflow: hidden;
}

.contacts {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 23.2rem;

    div {
        display: flex;

        .column {
            display: flex;
            flex-direction: column;
        }
    }

    .title {
        color: rgb(255, 255, 255);
        margin-bottom: .5rem;
        margin-top: .5rem;
        font-weight: bold;
    }

    li {
        list-style: none;

        a {
            text-decoration: none;
            color: rgb(120, 124, 132);
            font-size: .7rem;
        }
    }
}

.footer_bot {
    background-color: rgb(48, 48, 48);
}


.socials {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 8rem;


    button {
        background-color: transparent;
        color: rgb(255, 255, 255);
        border: 2px solid rgb(12, 119, 234);
        padding: .7rem;
        font-size: 1rem;
    }


    div {
        display: flex;
        align-items: center;
        gap: 1.2rem;

        h3 {
            color: rgb(12, 119, 234);
            font-size: 20px;
        }
    }
}
</style>
