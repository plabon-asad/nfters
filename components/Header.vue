<template>
    <nav>
        <div class="logo">
            <img src="~/assets/img/logo.png" alt="Logo">
        </div>
        <ul class="links">
            <li><a href="">Marketplace</a></li>
            <li><a href="">Resource</a></li>
            <li><a href="">About</a></li>

            <li>
                <div class="search-with-icon">
                    <form action="">
                        <input class="search" type="text" placeholder="Search">
                        <svg class="search-icon" width="24" height="24" viewBox="0 0 24 24" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M11.5 21.75C5.85 21.75 1.25 17.15 1.25 11.5C1.25 5.85 5.85 1.25 11.5 1.25C17.15 1.25 21.75 5.85 21.75 11.5C21.75 17.15 17.15 21.75 11.5 21.75ZM11.5 2.75C6.67 2.75 2.75 6.68 2.75 11.5C2.75 16.32 6.67 20.25 11.5 20.25C16.33 20.25 20.25 16.32 20.25 11.5C20.25 6.68 16.33 2.75 11.5 2.75Z"
                                fill="#757575" />
                            <path
                                d="M22.0004 22.7499C21.8104 22.7499 21.6204 22.6799 21.4704 22.5299L19.4704 20.5299C19.1804 20.2399 19.1804 19.7599 19.4704 19.4699C19.7604 19.1799 20.2404 19.1799 20.5304 19.4699L22.5304 21.4699C22.8204 21.7599 22.8204 22.2399 22.5304 22.5299C22.3804 22.6799 22.1904 22.7499 22.0004 22.7499Z"
                                fill="#757575" />
                        </svg>
                    </form>

                </div>

            </li>
            <li><a href="" class="btn btn-primary">Upload</a></li>
            <li><a href="" class="btn btn-primary outline">Connect Wallet</a></li>
        </ul>
        <a href="" class="mobile-menu">
            <svg width="30" height="22" viewBox="0 0 30 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <line y1="1" x2="30" y2="1" stroke="#3D00B7" stroke-width="2" />
                <line y1="11" x2="15" y2="11" stroke="#3D00B7" stroke-width="2" />
                <line y1="21" x2="25" y2="21" stroke="#3D00B7" stroke-width="2" />
            </svg>


        </a>

    </nav>

</template>

<style lang="scss" scoped>
nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 80px;

    .logo {
        position: relative;

        &:before {
            content: "";
            position: absolute;
            width: 1px;
            height: 50px;
            background-color: #EFEFEF;
            right: -30px;
            top: -15px;
            background-color: $grayColor;

        }
    }
}

.links {
    display: flex;
    gap: 1em;
    align-items: center;
}

.search-with-icon {
    position: relative;

    form {
        display: flex;
        align-items: center;

        .search {
            margin: 0;
            padding: 10px 20px;
            color: $grayColor;
            font-weight: bold;
            border: 1px solid $grayColor;
            border-radius: 60px;
            display: inline-block;
            transition: 0.3s;

            &:focus-visible {
                border: 1px solid transparent;
                outline: 1px solid darken($color: $grayColor, $amount: 10);
            }
        }

        .search-icon {
            position: absolute;
            right: 10px;
            width: 18px;
            cursor: pointer;
        }
    }
}

// Mobile menu
.mobile-menu {display: none;}

// Responsive code
@media screen and (max-width: 900px) {
    nav {height: 40px;}
    .links {
        display: none;
        li {
            a {
                color: red;
            }
        }
    }

    .mobile-menu {display: block;}

    // 



}
</style>