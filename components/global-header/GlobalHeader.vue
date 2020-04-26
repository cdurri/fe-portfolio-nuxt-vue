<template>
    <nav class="navbar has-background-white-bis navbar--global" role="navigation" aria-label="main navigation">
        <div class="navbar-brand navbar-brand-global">
            <a class="navbar-item" href="#">
                <figure class="image">
                    <img class="is-rounded" src="~/assets/cian_icon_bw.jpg" height="96">
                </figure>
            </a>

             <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu navbar-menu--global">
            <div class="navbar-end is-size-6 has-text-weight-semibold">
                <a class="navbar-item link--hover">
                    HOME
                </a>

                <a class="navbar-item link--hover">
                    PROJECTS
                </a>

                <a class="navbar-item link--hover">
                    SKILLS
                </a>

                <a class="navbar-item link--hover">
                    ABOUT
                </a>

                <a class="navbar-item link--hover">
                    CONTACT
                </a>
            </div>
        </div>
    </nav>
</template>

<style scoped lang="scss">
@import '~assets/scss/main.scss';


    .navbar-item {
        @media screen and (max-width: $tablet - 1px) {
            .image {
                height: 64px;
                width: 64px;
            }
         }
        
        img {
            max-height: 96px;
        }
        &.link--hover:hover {
            color: $orange;
        }
    }

    .navbar--global {
        position: relative;
        padding: 20px 100px;
    }

    .navbar-brand-global {
        position: absolute;
        top: 20px;
        left: 10px;
    }
</style>