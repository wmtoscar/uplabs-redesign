<template>
    <v-container>
        <v-layout row wrap>
            <v-flex xs8 sm8 md8>
                <div>
                    <h3>Today</h3>
                </div>
                <div>
                    September 28th
                </div>
            </v-flex>
            <v-flex xs4 sm4 md4>
                <div class="text-xs-right">
                    <a href="javascript:void(0)" class="text-uppercase basic_link">Customize your feed</a>
                </div>
            </v-flex>
        </v-layout>
        <v-layout row wrap>
            <!--motion-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/823e6c88-e701-4f15-8c70-8fc1315a3289/preview.gif"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/007/513/preview/19224954_251960585280949_1401053376035655372_n.jpg?1507619728" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>HASH Platform Photographer Preview Page Animation</h5>
                                <h6 class="text-small text-regular">by
                                    <a
                                            href="javascript:void(0)"><span class="text-capitalize">Sochnik
                                        Studios</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote motion">
                                    <a href="javascript:void(0)" class="upvote-link">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">690</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <!--android-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/67c2c1e2-b807-4a59-8a2d-f3251f97f2a2/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/075/549/preview/O7DvvRVl_400x400.jpg?1507707144" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Airbnb UI kit</h5>
                                <h6 class="text-small text-regular">by
                                    <a href="javascript:void(0)"><span class="text-capitalize">divan raj</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote upvoted android">
                                    <a href="javascript:void(0)" class="upvote-link"
                                       @click="isUpvoted('android')">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">191</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <!--web-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/9dfdc491-2587-4af4-b2a5-0853a7859793/preview.gif"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/046/085/preview/UTPKkrOi_400x400.jpg?1507621590" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Sign In Screen for Web Application</h5>
                                <h6 class="text-small text-regular">by
                                    <a href="javascript:void(0)"><span class="text-capitalize">Zanjo</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote web">
                                    <a href="javascript:void(0)" class="upvote-link">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">290</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <!--ios-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/b8134dda-a0a5-40f2-8a15-a29642da4c15/animated_teaser.gif"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/014/117/preview/TcZxZKU2_400x400.jpg?1507620119" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Share round</h5>
                                <h6 class="text-small text-regular">by
                                    <a href="javascript:void(0)"><span class="text-capitalize">Johnyvino</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote ios">
                                    <a href="javascript:void(0)" class="upvote-link">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">490</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <!--branding-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/77170bf7-5784-4faf-8355-88a54305076c/preview.jpg"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/227/904/preview/Untitled-1.jpg?1523263773" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Helvetica Banner</h5>
                                <h6 class="text-small text-regular">by
                                    <a href="javascript:void(0)"><span class="text-capitalize">tonmoy</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote branding">
                                    <a href="javascript:void(0)" class="upvote-link">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">90</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <!--3d-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/e5123820-d54b-460e-9c91-b035f177c50c/preview.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/401/641/thumb/open-uri20180910-4-16ia4zv?1536589886" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Floating Islands Branding</h5>
                                <h6 class="text-small text-regular">by
                                    <a href="javascript:void(0)"><span class="text-capitalize">tonmoy</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote 3d">
                                    <a href="javascript:void(0)" class="upvote-link">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">90</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <!--illustration-->
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/f3fd6368-5deb-4444-8c35-d538cbc32c73/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://s3.amazonaws.com/assets.materialup.com/users/pictures/000/025/776/thumb/IMG_0234.jpg?1536734812" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Subscribers</h5>
                                <h6 class="text-small text-regular">by
                                    <a href="javascript:void(0)"><span class="text-capitalize">Juilen</span></a></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote illustration">
                                    <a href="javascript:void(0)" class="upvote-link">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">90</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</template>
<script>
    export default {
        data(){
            return {
                x: null,
            }
        },
        methods: {

            isUpvoted: function () {
                console.log(!this.isOpenedClass);
                return {
                    x : item
                }
            }
        }
    }
</script>
