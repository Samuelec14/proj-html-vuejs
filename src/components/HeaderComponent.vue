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
                <div class="my-container">
                    <div class="row">

                        <!-- CONTACTS, LEFT SIDE  -->
                        <div class="col icons-sec">

                            <font-awesome-icon icon="fa-regular fa-envelope"/>
                            Superhit Top movie
                            <span class="text-green fw-semibold">** King Star **</span>
                            <span class="ms-4">

                                <span class="facebook-icon ms-3">
                                    <a href="#">
                                    <font-awesome-icon icon="fa-brands fa-facebook-f"/>
                                    </a>
                                </span>
                                <span class="twitter-icon ms-3">
                                    <a href="#">
                                    <font-awesome-icon icon="fa-brands fa-twitter"/>
                                    </a>
                                </span>
                                <span class="linkedin-icon ms-3">
                                    <a href="#">
                                        <font-awesome-icon icon="fa-brands fa-linkedin-in"/>
                                    </a>
                                </span>
                                <span class="instagram-icon ms-3">
                                    <a href="#">
                                        <font-awesome-icon icon="fa-brands fa-instagram"/>
                                    </a>
                                </span>
                                <span class="google-plus-icon ms-3">
                                    <a href="#">
                                        <font-awesome-icon icon="fa-brands fa-google-plus-g"/>
                                    </a>
                                </span>

                            </span>
                            
                        </div>

                        <!-- LOGIN, RIGHT SIDE  -->
                        <div class="col text-end">
                            <font-awesome-icon icon="fa-solid fa-lock"/>
                            Login
                        </div>

                    </div>
                </div>
            </section>

            <!-- LOGO AND SEARCHBAR HEADER SECTION -->
            <section id="searchbar-sec">
                <div class="my-container">
                    <div class="row align-items-center">
                        
                        <!-- LOGO, LEFT SIDE  -->
                        <div class="col">
                            <div class="logo-container w-50">
                                <img src="../assets/img/cropped-logo.png" alt="">
                            </div>
                        </div>

                        <!-- SEARCHBAR, RIGHT SIDE  -->
                        <div class="col text-end">
                            <div class="searchbar-btn d-flex justify-content-end">
                                <input id="searchbar" class="p-3" type="text" placeholder="Search a Movie...">
                                <div id="sb-btn" class="d-inlineblock">
                                    <button class="p-3">Search</button>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </section>

            <!-- NAVBAR AND CART HEADER SECTION -->
            <section id="navbar-sec">
                <div class="my-container">
                    <div class="row justify-content-between">

                        <!-- NAVBAR, LEFT SIDE  -->
                        <div class="col-auto">
                            <ul class="d-flex">
                                <li class="dropdown">
                                    <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        Home
                                    </button>
                                    <ul class="dropdown-menu dropdown-edit">
                                        <li class="mt-4"><a class="dropdown-item dropdown-item-edit" href="#">Action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Another action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="dropdown">
                                    <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        Celebrity
                                    </button>
                                    <ul class="dropdown-menu dropdown-edit">
                                        <li class="mt-4"><a class="dropdown-item dropdown-item-edit" href="#">Action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Another action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="dropdown">
                                    <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        Movie
                                    </button>
                                    <ul class="dropdown-menu dropdown-edit">
                                        <li class="mt-4"><a class="dropdown-item dropdown-item-edit" href="#">Action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Another action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="dropdown">
                                    <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        Page
                                    </button>
                                    <ul class="dropdown-menu dropdown-edit">
                                        <li class="mt-4"><a class="dropdown-item dropdown-item-edit" href="#">Action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Another action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="dropdown">
                                    <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        Shop
                                    </button>
                                    <ul class="dropdown-menu dropdown-edit">
                                        <li class="mt-4"><a class="dropdown-item dropdown-item-edit" href="#">Action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Another action</a></li>
                                        <li><a class="dropdown-item dropdown-item-edit" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="me-2">
                                    <button>Blog</button>
                                </li>
                                <li>
                                    <button>Contact Us</button>
                                </li>
                            </ul>
                        </div>

                        <!-- CHART, RIGHT SIDE  -->
                        <div class="col-auto text-end">
                            <a href="#"><font-awesome-icon icon="fa-solid fa-bag-shopping"/></a>
                        </div>

                    </div>
                </div>
            </section>

    </header>

</template>

<style lang="scss" scoped>

header{


    #contacts-heading-sec{
        border-bottom: 1px solid rgb(48, 48, 51);
        line-height: 55px;

        .icons-sec{

            .facebook-icon{
                color: #13be13;
                
            }
        }
    }

    #searchbar-sec{
        border-bottom: 1px solid rgb(48, 48, 51);
        
        
        .row{
            height: 150px;
        }
        .searchbar-btn{
            #searchbar{
                background-color: #060F19;
                border: none;
                border-top: 1px solid rgb(48, 48, 51);
                border-bottom: 1px solid rgb(48, 48, 51);
            }
            #sb-btn{

                button{
                    background-color: #13be13;
                    border: none;
                }
            }
        }

    }

    #navbar-sec{
        line-height: 70px;

        ul{
            list-style: none;
            padding: 0;

            li{
                margin-inline-end: 8px;
                cursor: pointer;
            }

            button{
                background-color: unset;
                border: unset;

                &:hover{
                    color: #13be13;
                }
                
            }
            .dropdown-edit{
                line-height: 30px;
                border: unset;
                border-radius: 0;
                background-color: #060F19;
                
                .dropdown-item-edit:hover{
                    color: #060F19;
                }


                li{
                    a{
                        color: white;
                    }
                }
            }
        }
    }
}

</style>