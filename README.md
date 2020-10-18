# light
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!--連結 jQuery Mobile -->    
    <link rel="stylesheet" href="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
    <script src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
    <script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>

    <!-- 設定Favicon -->
    <link rel="shortcut icon" href="image/favicon.ico.ico">
    <link rel="bookmark" href="image/favicon.ico.ico">



    <title>燈燈的一天</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- 主頁 -->
    <div data-role="page" id="page00">
 
        <div data-role="header">
            <h1 style='color: rgb(107, 6, 6);'>小燈的一天(首頁)</h1>
        </div><!-- /header -->
 
        <div role="main" class="ui-content">
            <p>Hello 我就是顆燈 \(._.)>></p>
            <img src="image/light.png">
            <a href="#page01">    第1頁    </a>
        </div><!-- /content -->
 
        <div data-role="footer" data-position="fixed">
            <h4>Copyright &copy; 2020 1108211027@gap.wzu.tw DCAM</h4>
        </div><!-- /footer -->
 
    </div><!-- /page -->

    <!-- 第一分頁 -->
    <div data-role="page" id="page01">
 
        <div data-role="header">
            <h1 style='color: rgb(68, 65, 245);'>小燈的一天 p.1</h1>
        </div><!-- /header -->
 
        <div role="main" class="ui-content">
            <p>Good night ~ ~ 要關燈囉囉 ! !  zzz(-"-)zzzzzz</p>
            <img src="image/turn off.png">
            <a href="#page00">   首頁   </a>
            <a href="#page02">   第2頁   </a>
        </div><!-- /content -->
 
        <div data-role="footer" data-position="fixed">
            <h4>Copyright &copy; 2020 1108211027@gap.wzu.tw DCAM</h4>
        </div><!-- /footer -->
 
    </div><!-- /page -->

    <!-- 第二分頁 -->
    <div data-role="page" id="page02">
 
        <div data-role="header">
            <h1 style='color: rgb(238, 34, 204);'>小燈的一天 p.2</h1>
        </div><!-- /header -->
 
        <div role="main" class="ui-content">
            <p>｢ 我不是美食 ! ! m@w@m OMG~ (驚醒)」</p>
            <img src="image/omg.png">
            <a href="#page01">    第1頁   </a>
            <a href="#page03">    第3頁   </a>
        </div><!-- /content -->
 
        <div data-role="footer" data-position="fixed">
            <h4>Copyright &copy; 2020 1108211027@gap.wzu.tw DCAM</h4>
        </div><!-- /footer -->
 
    </div><!-- /page -->


    <!-- 第三分頁 -->
    <div data-role="page" id="page03">
 
        <div data-role="header">
            <h1 style='color: rgb(57, 179, 0);'>小燈的一天 p.3</h1>
        </div><!-- /header -->
 
        <div role="main" class="ui-content">
            <p>原來一切都是一場夢(汗... o~o:::</p>
            <img src="image/hahaha.png">
            <a href="#page02">   第2頁   </a>
            <a href="#page04">    第4頁     </a>
        </div><!-- /content -->
 
        <div data-role="footer" data-position="fixed">
            <h4>Copyright &copy; 2020 1108211027@gap.wzu.tw DCAM</h4>
        </div><!-- /footer -->
 
    </div><!-- /page -->

    
    <!-- 第四分頁 -->
    <div data-role="page" id="page04">
 
        <div data-role="header">
            <h1 style='color: rgb(255, 148, 86);'>小燈的一天 p.4</h1>
        </div><!-- /header -->
 
        <div role="main" class="ui-content">
            <p>來去各地旅遊吧~~</p>
            <img src="image/cat light.png">
            <a href="#page03">   第3頁   </a>
            <a href="#page00">    首頁     </a>
        </div><!-- /content -->
 
        <div data-role="footer" data-position="fixed">
            <h4>Copyright &copy; 2020 1108211027@gap.wzu.tw DCAM</h4>
        </div><!-- /footer -->
 
    </div><!-- /page -->


</body>
</html>
