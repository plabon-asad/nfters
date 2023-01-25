<template>
    <section class="top-collections">
        <div class="container spacing-y">
            <div class="row">
                <div class="col">
                    <div class="left-collection">
                        <img class="big-img" src="~/assets/img/card1.png" alt="Card">
                        <div class="card-list">
                            <div class="user">
                                <img src="~/assets/img/user.png" alt="User">
                                <div class="info">
                                    <h4>The Futr Abstr</h4>
                                    <span>10 in the stock</span>
                                </div>
                            </div>
                            <div class="bid">
                                <div class="bid-title">Highest Bid</div>
                                <div class="amount">
                                    <svg width="13" height="22" viewBox="0 0 13 22" fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <g clip-path="url(#clip0_0_213)">
                                            <path
                                                d="M12.671 11.4564L6.50004 15.3231L0.325043 11.4564L6.50004 0.589722L12.671 11.4564ZM6.50004 16.5647L0.325043 12.6981L6.50004 21.9231L12.675 12.6981L6.50004 16.5647Z"
                                                fill="#3A3A3A" />
                                        </g>
                                        <defs>
                                            <clipPath id="clip0_0_213">
                                                <rect width="13" height="21.3333" fill="white"
                                                    transform="translate(0 0.589722)" />
                                            </clipPath>
                                        </defs>
                                    </svg>

                                    <strong>0.25 ETH</strong>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col">
                    <div class="left-collection">
                        <img class="big-img" src="~/assets/img/card1.png" alt="Card">
                        <div class="card-list">
                            <div class="user">
                                <img src="~/assets/img/user.png" alt="User">
                                <div class="info">
                                    <h4>The Futr Abstr</h4>
                                    <span>10 in the stock</span>
                                </div>
                            </div>
                            <div class="bid">
                                <div class="bid-title">Highest Bid</div>
                                <div class="amount">
                                    <svg width="13" height="22" viewBox="0 0 13 22" fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <g clip-path="url(#clip0_0_213)">
                                            <path
                                                d="M12.671 11.4564L6.50004 15.3231L0.325043 11.4564L6.50004 0.589722L12.671 11.4564ZM6.50004 16.5647L0.325043 12.6981L6.50004 21.9231L12.675 12.6981L6.50004 16.5647Z"
                                                fill="#3A3A3A" />
                                        </g>
                                        <defs>
                                            <clipPath id="clip0_0_213">
                                                <rect width="13" height="21.3333" fill="white"
                                                    transform="translate(0 0.589722)" />
                                            </clipPath>
                                        </defs>
                                    </svg>

                                    <strong>0.25 ETH</strong>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="left-collection">
                        <img class="big-img" src="~/assets/img/card1.png" alt="Card">
                        <div class="card-list">
                            <div class="user">
                                <img src="~/assets/img/user.png" alt="User">
                                <div class="info">
                                    <h4>The Futr Abstr</h4>
                                    <span>10 in the stock</span>
                                </div>
                            </div>
                            <div class="bid">
                                <div class="bid-title">Highest Bid</div>
                                <div class="amount">
                                    <svg width="13" height="22" viewBox="0 0 13 22" fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <g clip-path="url(#clip0_0_213)">
                                            <path
                                                d="M12.671 11.4564L6.50004 15.3231L0.325043 11.4564L6.50004 0.589722L12.671 11.4564ZM6.50004 16.5647L0.325043 12.6981L6.50004 21.9231L12.675 12.6981L6.50004 16.5647Z"
                                                fill="#3A3A3A" />
                                        </g>
                                        <defs>
                                            <clipPath id="clip0_0_213">
                                                <rect width="13" height="21.3333" fill="white"
                                                    transform="translate(0 0.589722)" />
                                            </clipPath>
                                        </defs>
                                    </svg>

                                    <strong>0.25 ETH</strong>

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
.left-collection {
    img.big-img {
        margin-bottom: 32px;
    }
}

.card-list {
    display: flex;
    justify-content: space-between;
    max-width: 400px;

    .user {
        display: flex;
        gap: 1em;

        img {
            width: 48px;
            height: 48px;
            border-radius: 100%;
        }

        .info {
            h4 {
                font-size: 20px;
            }

            span {
                font-size: 14px;
                color: gray;
            }
        }
    }

    .bid {
        .bid-title {
            font-size: 12px;
            margin-bottom: 5px;
        }

        .amount {
            svg {
                margin-right: 10px;
                vertical-align: middle;
            }

            strong {
                font-size: 16px;
            }
        }
    }
}
</style>