<template>
  <div class="home">
    <!--<img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->

    <div class="container-fluid">
        <div class="row">
            <div class="col-md-9 col-12">
                <ul class="arc_list">
                    <li>
                        <div class="row arc_box">
                            <div class="col-md-4">
                                <img src="../assets/images/test.png" alt="">
                            </div>
                            <div class="col-md-8">
                                <h5>文章标题</h5>
                                <p class="arc_sub">文章发布时间:2019年</p>
                                <p class="arc_text">
                                    文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介
                                </p>
                                <button class="btn btn-primary btn-sm">阅读全文</button>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="row arc_box">
                            <div class="col-md-4">
                                <img src="../assets/images/test.png" alt="">
                            </div>
                            <div class="col-md-8">
                                <h5>文章标题</h5>
                                <p class="arc_sub">文章发布时间:2019年</p>
                                <p class="arc_text">
                                    文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介
                                </p>
                                <button class="btn btn-primary btn-sm">阅读全文</button>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="row arc_box">
                            <div class="col-md-4">
                                <img src="../assets/images/test.png" alt="">
                            </div>
                            <div class="col-md-8">
                                <h5>文章标题</h5>
                                <p class="arc_sub">文章发布时间:2019年</p>
                                <p class="arc_text">
                                    文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介
                                </p>
                                <button class="btn btn-primary btn-sm">阅读全文</button>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="row arc_box">
                            <div class="col-md-4">
                                <img src="../assets/images/test.png" alt="">
                            </div>
                            <div class="col-md-8">
                                <h5>文章标题</h5>
                                <p class="arc_sub">文章发布时间:2019年</p>
                                <p class="arc_text">
                                    文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介文章简介
                                </p>
                                <button class="btn btn-primary btn-sm">阅读全文</button>
                            </div>
                        </div>
                    </li>
                </ul>

            </div>
            <div class="col-12 col-md-3">
                <div class="list-group">
                    <a href="#" class="list-group-item list-group-item-action flex-column align-items-start">
                        <div class="d-flex w-100 justify-content-between">
                            <h5 class="mb-1">List group item heading</h5>
                            <small>3 days ago</small>
                        </div>
                        <p class="mb-1">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
                        <small>Donec id elit non mi porta.</small>
                    </a>
                    <a href="#" class="list-group-item list-group-item-action flex-column align-items-start">
                        <div class="d-flex w-100 justify-content-between">
                            <h5 class="mb-1">List group item heading</h5>
                            <small class="text-muted">3 days ago</small>
                        </div>
                        <p class="mb-1">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
                        <small class="text-muted">Donec id elit non mi porta.</small>
                    </a>
                    <a href="#" class="list-group-item list-group-item-action flex-column align-items-start">
                        <div class="d-flex w-100 justify-content-between">
                            <h5 class="mb-1">List group item heading</h5>
                            <small class="text-muted">3 days ago</small>
                        </div>
                        <p class="mb-1">Donec id elit non mi porta gravida at eget metus. Maecenas sed diam eget risus varius blandit.</p>
                        <small class="text-muted">Donec id elit non mi porta.</small>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="foot">
        <small>power by 杨少鑫</small>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
<style lang="less">
    .arc_list{
        li{
            padding: 15px;
            &:not(:last-child) {
                border-bottom: 1px dashed #ebebeb;
            }
            img{
                width: 100%;
            }
            .arc_box{
                div{
                    margin-top: 15px;
                }
            }
        }
    }
    .foot{
        height: 80px;
        line-height: 80px;
        text-align: center;
        background-color: #ebebeb;
        border-top:1px solid #ccc;
    }
</style>
