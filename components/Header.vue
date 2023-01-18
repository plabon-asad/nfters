<template>
    <nav>
        <div class="logo">
            <img src="~/assets/img/logo.png" alt="Logo">
        </div>
        <ul class="links">
            <li><a href="">Marketplace</a></li>
            <li><a href="">Resource</a></li>
            <li><a href="">About</a></li>

            <li><input type="text" placeholder="Search"></li>
            <li><a href="" class="btn btn-primary fill">Upload</a></li>
            <li><a href="" class="btn btn-primary outline">Connect Wallet</a></li>
        </ul>
        
    </nav>

</template>

<style lang="scss" scoped>
nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 80px;
}

.links {
    display: flex;
    gap: 20px;
}
</style>