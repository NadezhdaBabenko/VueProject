<template>
    <div class="menu col-10">
        <nav class="menu__block navbar navbar-expand-lg navbar-dark">
            <button class="menu__btn navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="menu__row collapse navbar-collapse" id="navbarNav">
                <ul class="menu__list navbar-nav">
                    <li class="menu__item nav-item active">
                        <a class="menu__link nav-link" href="#">Features <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="menu__item nav-item">
                        <a class="menu__link nav-link" href="#">works</a>
                    </li>
                    <li class="menu__item nav-item">
                        <a class="menu__link nav-link" href="#">our team</a>
                    </li>
                    <li class="menu__item nav-item">
                        <a class="menu__link nav-link" href="#">testimonials</a>
                    </li>
                    <li class="menu__item nav-item">
                        <a class="menu__link nav-link" href="#">download</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<style lang="scss">
    .menu {
        &__link {
            font-size: 13px;
            text-transform: uppercase;
            font-weight: bold;
        }
    }
</style>
