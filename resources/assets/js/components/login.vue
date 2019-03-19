<template>
    <section class="hero is-fullheight is-medium">
        <div class="hero-body">
            <div class="container has-text-centered">
                <div class="columns is-centered is-mobile">
                    <div class="column is-two-fifths-desktop is-three-fifths-tablet is-full-mobile">
                        <div class="login-container">
                            <figure class="logo">
                                <img src="/img/logo-m2_primary.png">
                            </figure>
                            <b-field>
                                <b-input placeholder="Username"
                                         icon="account"
                                         rounded>
                                </b-input>
                            </b-field>
                            <b-field>
                                <b-input placeholder="Password"
                                         type="password"
                                         icon="lock"
                                         rounded
                                         password-reveal>
                                </b-input>
                            </b-field>
                            <a class="button is-primary is-fullwidth">Login</a>
                        </div>
                    </div>
                </div>
                <div class="columns is-full is-mobile is-centered">
                    <p>
                        No account, signup here.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>