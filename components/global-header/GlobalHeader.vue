<template>
    <nav class="navbar has-background-white-bis" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <a class="navbar-item" href="#">
                <figure class="image is-96x96">
                    <img class="is-rounded" src="~/assets/cian_icon_bw.jpg" height="96">
                </figure>
            </a>

             <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </a>

            <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-start">
                    <a class="navbar-item">
                        HOME
                    </a>

                    <a class="navbar-item">
                        PROJECTS
                    </a>

                    <a class="navbar-item">
                        SKILLS
                    </a>

                    <a class="navbar-item">
                        ABOUT
                    </a>

                    <a class="navbar-item">
                        CONTACT
                    </a>
                </div>
            </div>

        </div>
    </nav>
</template>

<style scoped lang="scss">
    .navbar-item {
        img {
            max-height: 96px;
        }
    }
</style>