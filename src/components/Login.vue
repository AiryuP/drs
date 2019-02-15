<template>
    <div class="login">
        <div class="xtName">IStorM DRaaS灾备服务</div>
        <div class="loginBox">
            <div class="lbTop clearfloat">
                <div class="psdLg">密码登录</div>
                <div class="yzmLg">验证码登录</div>
            </div>
            <div class="lbBot">

            </div>
        </div>
        <div class="xtMiaoshu">
            <div class="msTop">专业混合云灾备管理提供商</div>
            <div class="msBot">
                <p>适应各种场景</p>
                <p>符合BCM要求</p>
            </div>
        </div>
        <div class="footer">
            通过 ISO27001:2013 信息安全认证
        </div>
    </div>
</template>

<script>
export default {
    name: 'login',
    data(){
        return{
            msg: '登录页',
        }
    }
}
</script>

<style scoped lang="scss">
$color:rgba(0, 0, 0, 0.589);
div {color:$color;}
    .login{
        width: 100%;
        height: 100%;
        overflow: hidden;
        background: url('../assets/images/bg.jpg') no-repeat;
        background-size: 100%;
        position: relative;
        .xtName{
            color: #fff;
            font-size: 26px;
            margin: 10px 0 0 10px;
        }
        .xtMiaoshu{
            position: absolute;
            top: 40%;
            left: 200px;
            .msTop{
                font-size: 30px;
                color: #fff;
                font-weight: 400;
                margin-bottom: 40px;
            }
            .msBot{
                color: #fff;
                font-size: 20px;
                font-weight: 400;
                p{
                    margin-top: 10px;
                }
            }
        }
        .loginBox{
            width: 320px;
            height: 380px;
            background-color: $color;
            position: absolute;
            top: 30%;
            right: 20vw;
            border: 1px solid rgba(99, 154, 206, 0.664);
            border-radius: 10px;
            .lbTop{
                width: 80%;
                height: 50px;
                // background-color: red;
                margin: 0 auto;
                margin-top: 20px;
                div{
                    width: 50%;
                    float: left;
                    color: #fff;
                    text-align: center;
                    font-size: 20px;
                    border-bottom: 1px solid #ccc;
                    padding-bottom: 10px;
                }
                .psdLg{
                   border-bottom: 1px solid red;

                }
            }
            .lbBot{
                width: 80%;
                height: 70%;
                margin: 0 auto;
                // background-color: aqua;

            }
        }
        .footer{
            width: 100%;
            text-align: center;
            margin: 0 auto;
            color: #fff;
            position: absolute;
            bottom: 0px;
        }
    }
       /*清除浮动代码*/
   .clearfloat:after{display:block;clear:both;content:"";visibility:hidden;height:0}
   .clearfloat{zoom:1}

</style>