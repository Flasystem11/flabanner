<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>web-banner</title>
    <style>
       * {
                margin: 0;
                padding: 0;
            }
            li,
            ol,
            ul {
                list-style: none;
            }
            img {
                border: 0;
            }
            a {
                text-decoration: none;
            }

            .wrap {
                width: 980px;
            }
            .video {
                width="980" height="500";
                padding: 12px 0 12px 0; }
            .visual {
                width: 100%;
                height: 100%;
            }
            .visual:after {content:""; display:block; clear:both}
            .visual > div {
                float: left;
            }
            .left {
                width: 680px;
                height: 300px;
                position: relative;
            }
            .slide {
                position: absolute;
                top: 0;
                left: 0;
                display: none;
            }
            .right {
                width: 300px;
                height: 300px;
            }
            .thum {
                width: 100px;
                height: 100px;
                float: left;
            }
            .thum01 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum01.jpg");
            }
            .thum02 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum02.jpg");
            }
            .thum03 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum03.jpg");
            }
            .thum04 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum04.jpg");
            }
            .thum05 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum05.jpg");
            }
            .thum06 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum06.jpg");
            }
            .thum07 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum07.jpg");
            }
            .thum08 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum08.jpg");
            }
            .thum09 {
                background: url("http://gi.esmplus.com/all1592/mainbanner/thum09-200805.jpg");
            }
            .on {
                display: block;
            }
            .active{
                background-position: 0 -100px;
            }
            .banner {line-height:1}
            .banner h2 img {width:100%; height:100%}
            .web_banner:after {content:""; display:block; clear:both}
            .web_banner li {float:left; margin-left:10px}
            .web_banner li:first-child {margin-left:0}
            .web_banner li a {display:block}
            .web_banner img {width:100%; height:100%}
    </style>
</head>
<body>
    <div class="wrap">
        <div class="visual">
            <div class="left">
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/3"
                    class="slide slide01 on" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_01.jpg" alt="축하화환"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/4"
                    class="slide slide02" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_02.jpg" alt="근조화환"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/9"
                    class="slide slide03" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_03.jpg" alt="관엽식물"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/6"
                    class="slide slide04" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_04.jpg" alt="서양란"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/5"
                    class="slide slide05" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_05.jpg" alt="동양란"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/10"
                    class="slide slide06" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_06.jpg" alt="공기정화식물"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/8"
                    class="slide slide07" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_07.jpg" alt="꽃다발"></a>
                <a
                    href="http://ktjflower.co.kr/goods/goods_list/sel_menu/7"
                    class="slide slide08" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_08.jpg" alt="꽃바구니"></a>
                <a  
                    href="http://www.ktjflower.co.kr/goods/goods_search/s_keyword/%EC%BB%B5%ED%94%8C%EB%9E%9C%ED%8A%B8"
                    class="slide slide09" target="_top"><img src="http://gi.esmplus.com/all1592/mainbanner/pro_09_200330.jpg" alt="컵플랜트"></a>
            </div>
            
            <div class="right">
                <div class="thum-box">
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/3"
                        class="thum thum01 active" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/4"
                        class="thum thum02" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/9"
                        class="thum thum03" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/6"
                        class="thum thum04" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/5"
                        class="thum thum05" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/10"
                        class="thum thum06" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/8"
                        class="thum thum07" target="_top"></a>
                    <a
                        href="http://ktjflower.co.kr/goods/goods_list/sel_menu/7"
                        class="thum thum08" target="_top"></a>
                    <a
                        href="http://www.ktjflower.co.kr/goods/goods_search/s_keyword/%EC%BB%B5%ED%94%8C%EB%9E%9C%ED%8A%B8"
                        class="thum thum09" target="_top"></a>
                </div>
            </div>
        </div>

        <div class="banner">
            <h2><img src="http://gi.esmplus.com/all1592/mainbanner/plan_title.jpg" alt=""></h2>
            <ul class="web_banner">
                <li><a href="http://ktjflower.co.kr//page/print_page/seq/16" target="_parent"><img src="http://gi.esmplus.com/all1592/mainbanner/plan_banner_01.jpg" alt="돈세다 잠드소서"></a></li>
                <li><a href="http://ktjflower.co.kr//page/print_page/seq/29" target="_parent"><img src="http://gi.esmplus.com/all1592/mainbanner/plan_banner_02.gif" alt="인사이동 기획전"></a></li>
                <li><a href="http://ktjflower.co.kr//page/print_page/seq/34" target="_parent"><img src="http://gi.esmplus.com/all1592/mainbanner/plan_banner_04.jpg" alt="집들이 기획전"></a></li>
            </ul>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
    <script>
        $(document).ready(function () {
                //hover 효과
                var i;
                    $('.thum').each(function (index) {
                        $(this).attr('data-index', index);
                    }).mouseenter(function () {
                        i = $(this).attr('data-index');
                        $('.thum').removeClass('active');
                        $('.thum').eq(i).addClass('active');
                        $('.slide').removeClass('on');
                        $('.slide').eq(i).addClass('on');
                        clearInterval(playSlide);
                    }).mouseleave(function(){
                      slideShow();
                    });
                //slide

                var index = 0;
                var playSlide = null;
                function slideShow(){
                   playSlide = setInterval(function(){
                       index++;
                       if(index > 9){
                           index=1;
                       }
                       $('.thum').removeClass('active');
                        $('.thum').eq(index-1).addClass('active');
                        $('.slide').removeClass('on');
                        $('.slide').eq(index-1).addClass('on');
                    }, 4000);
                }
                slideShow();
            });//end
    </script>
</body>
</html>
