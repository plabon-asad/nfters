<template>
    <section class="main-slider">
        <div class="container spacing-y">
            <div class="row">
                <div class="col">
                    <div class="left-content">
                        <h1>Discover, and collect Digital Art NFTs </h1>
                        <p>Digital marketplace for crypto collectibles and non-fungible tokens (NFTs). Buy, Sell, and
                            discover exclusive digital assets.</p>
                        <a href="#" class="btn btn-primary">Explore Now</a>
                        <ul class="links">
                            <li>
                                <strong>98k+</strong><br>
                                <span>Artwork</span>
                            </li>
                            <li>
                                <strong>98k+</strong><br>
                                <span>Artwork</span>
                            </li>
                            <li>
                                <strong>98k+</strong><br>
                                <span>Artwork</span>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <!-- <img src="~/assets/img/badge.png" alt=""> -->
                        <div class="content">
                            <h4 class="title">Plabon Asad</h4>
                            <ul>
                                <li><img src="" alt=""></li>
                                <li><strong>Plabon Asad</strong></li>
                            </ul>
                            <div class="footer">
                                <div class="left">
                                    <p>Current Bid</p>
                                    <div class="amount">
                                        <svg width="13" height="22" viewBox="0 0 13 22" fill="none"
                                            xmlns="http://www.w3.org/2000/svg">
                                            <g clip-path="url(#clip0_0_143)">
                                                <path
                                                    d="M12.671 11.3796L6.50006 15.2463L0.325058 11.3796L6.50006 0.512939L12.671 11.3796ZM6.50006 16.4879L0.325058 12.6213L6.50006 21.8463L12.6751 12.6213L6.50006 16.4879Z"
                                                    fill="white" />
                                            </g>
                                            <defs>
                                                <clipPath id="clip0_0_143">
                                                    <rect width="13" height="21.3333" fill="white"
                                                        transform="translate(0 0.512939)" />
                                                </clipPath>
                                            </defs>
                                        </svg>
                                        <h4>0.25 ETH</h4>

                                    </div>
                                </div>
                                <div class="right">
                                    <p>Ends in</p>
                                    <div class="time">
                                        <span><strong>12</strong>h</span>
                                        <span><strong>12</strong>h</span>
                                        <span><strong>12</strong>h</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>

<style lang="scss" scoped>
.card {
    // background-image: url("~/assets/img/card1.png");
    width: 400px;
    height: 440px;
    background: $darkGray;
    border-radius: 24px;
    padding: 26px;
    color: white;
}

.main-slider {
    .left-content {
        position: relative;

        &:before {
            position: absolute;
            content: "";
            width: 196px;
            height: 154px;
            bottom: 0;
            left: -50px;
            background-image: url('~/assets/img/dots.png');
            z-index: -1;
        }

        h1 {
            font-weight: bold;
            font-size: 40px;
            text-transform: uppercase;
            margin-bottom: 22px;
        }

        p {
            margin-bottom: 40px;
            color: $darkGray;
            font-size: 20px;
            font-weight: 400;
        }

        ul.links {
            display: flex;
            gap: 1em;
            margin-top: 30px;
            margin-bottom: 20px;

            li {
                strong {
                    font-size: 40px;
                    font-weight: 700;
                }

                span {
                    font-size: 20px;
                    font-weight: 400;
                    color: $darkGray;
                }
            }
        }

    }

}
</style>