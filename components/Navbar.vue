<template>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">
                <nuxt-link class="navbar-brand" to="/">
                    КаркасЦентр
                </nuxt-link>
                

                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav mr-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <nuxt-link active-class="activ" exact class="nav-link" aria-current="page" to="/">
                                Главная
                            </nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link active-class="activ" class="nav-link" aria-current="page" to="/about">
                                О нас
                            </nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link  active-class="activ" class="nav-link" aria-current="page" to="/users">
                                Пользователи
                            </nuxt-link>
                        </li>

                        <li class="nav-item">
                            <nuxt-link  active-class="activ" class="nav-link" aria-current="page" to="/login">
                                Login
                            </nuxt-link>
                        </li>
                        
                    </ul>
                
                </div>
            </div>
        </nav>
    </header>
</template>