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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
                                    <a href="javascript:void(0)" class="upvote-link" @click="isUpvoted('android')">
                                        <v-icon class="text-xs-center up_icon">arrow_drop_up</v-icon>
                                        <div class="counter">1</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
            <v-flex xs12 sm4 class="card-wrapper">
                <v-card>
                    <v-img
                            src="https://assets.materialup.com/uploads/428b8741-73c5-4de2-b351-b9231c8612d1/teaser.png"
                            aspect-ratio="1.5"
                    ></v-img>

                    <v-card-title primary-title>
                        <div class="w-100">
                            <div class="d-inline-block curator_img_wrapper">
                                <div class="curator_img_48">
                                    <img src="https://bhavikji.com/images/home/bhavik1_200x200.jpg" class="img-fluid"/>
                                </div>
                            </div>
                            <div class="d-inline-block article_headline">
                                <h5>Minimal Landscapes</h5>
                                <h6 class="text-small text-regular">by
                                    <span class="text-capitalize">Mark van Bommel</span></h6>
                            </div>
                            <div class="d-inline-block like_btn">
                                <div class="upvote">
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
        methods: {
            isUpvoted (item) {
                console.log(this.parent())
            }
        }
    }
</script>