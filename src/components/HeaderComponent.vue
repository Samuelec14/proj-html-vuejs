<script>

export default {
    name: "HeaderComponent",
    data() {
    return{

    }
    },
    methods: {

    }
}
</script>

<template>

    <header>

                <!-- CONTACTS HEADER SECTION -->
            <section id="contacts-heading-sec">
                <div class="container">
                    <div class="row">

                        <div class="col">
                            LINKS 
                        </div>

                        <div class="col text-end">
                            LOGIN
                        </div>

                    </div>
                </div>
            </section>

            <!-- LOGO AND SEARCHBAR HEADER SECTION -->
            <section id="searchbar-sec">
                <div class="container">
                    <div class="row align-items-center">

                        <div class="col">
                            LOGO
                        </div>

                        <div class="col text-end">
                            SEARCHBAR
                        </div>

                    </div>
                </div>
            </section>

            <!-- NAVBAR AND CART HEADER SECTION -->
            <section id="navbar-sec">
                <div class="container">
                    <div class="row">

                        <div class="col-8">
                            NAVBAR
                        </div>

                        <div class="col-4 text-end">
                            CHART
                        </div>

                    </div>
                </div>
            </section>

    </header>

</template>

<style lang="scss" scoped>

header{
    // debug
    min-height: 200px;


    #contacts-heading-sec{
        border-bottom: 1px solid rgb(48, 48, 51);
        line-height: 55px;
    }

    #searchbar-sec{
        border-bottom: 1px solid rgb(48, 48, 51);
        

        .row{
            height: 150px;
        }
    }

    #navbar-sec{
        line-height: 70px;
    }
}

</style>