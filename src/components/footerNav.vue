<template>
<<<<<<< HEAD
<<<<<<< HEAD
    <footer class="footer-nav-wrap">
        <nav class="flex-space-around footer-nav">
            <block-btn v-for="item in nav" :icon="item.icon" :name="item.name" :to="item.to"></block-btn>
        </nav>
    </footer>
=======
=======
>>>>>>> 200acd83eba2c8e2b16851d8fda8a3ee4e3657f9
    <div>
        <router-view></router-view>
        <footer class="footer-nav-wrap">
            <nav class="flex-space-around footer-nav">
                <block-btn v-for="item in nav" :icon="item.icon" :name="item.name" :to="item.to"></block-btn>
            </nav>
        </footer>
    </div>
<<<<<<< HEAD
>>>>>>> 7c6bba66ebdc46888a8e7b270da403a03b171902
=======
>>>>>>> 200acd83eba2c8e2b16851d8fda8a3ee4e3657f9
</template>
<style lang="scss">
    .footer-nav-wrap{
        position:fixed;
        bottom:0;
        width:750px;
        box-shadow: 0 -1px 4px #d7d6d6;
        .footer-nav {
            height:98px;
            background:#fff;
        }
    }
</style>
<script type="text/babel">
    import blockBtn from './blockBtn'
    export default {
        data() {
            return {
                nav: {
                    special:{
                        icon:{
<<<<<<< HEAD
<<<<<<< HEAD
                            iconClass: 'icon-special'
=======
                            iconClass: 'icon-special-offer'
>>>>>>> 7c6bba66ebdc46888a8e7b270da403a03b171902
=======
                            iconClass: 'icon-special-offer'
>>>>>>> 200acd83eba2c8e2b16851d8fda8a3ee4e3657f9
                        }
                        ,to: {
                            name:"bound"
                        }
                        ,name: "特卖"
                    }
                    ,shops:{
                        icon:{
                            iconClass: 'icon-shops'
                        }
                        ,to: {
                            name:"shopList"
                        }
                        ,name: "附近商家"
                    }
                    ,message:{
                        icon:{
                            iconClass: 'icon-message'
                        }
                        ,to: {
                            name:"bound"
                        }
                        ,name: "消息"
                    }
                    ,user:{
                        icon:{
                            iconClass: 'icon-user'
                        }
                        ,to: {
                            name: "user",
                            query: {token:1}
                        }
                        ,name: "会员中心"
                    }
                }
            }
        }
        ,components:{
            blockBtn
        }
    }
</script>
