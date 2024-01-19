<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" auther="سپهر حلاجی" keywords="html">
    <title>shahardeh site</title>
    <link href="css/css.css" type="text/css" rel="stylesheet">
    <script type="text/javascript">
        function c(){
            window.alert("شما می توانید با شماره 09032874733 با ما در ارتباط باشید")
        }
        function b(){
            window.alert("این سایت قصد دارد که با چهار روش به شما ساختار مقدماتی زبان html را یاد بدهد و طراحی آن توسط سپهر حلاجی انجام شده است")
        }
        function a(){
            if(document.getElementById("aside").hidden){
                document.getElementById("aside").hidden=false;
                document.getElementById("image html").hidden=true;
            }else{
                document.getElementById("aside").hidden=true;
                document.getElementById("image html").hidden=false;
            }
        }
    </script>
</head>
<body dir="rtl" bgcolor="gray">
    <fieldset style="background-color:rgb(224, 224, 224);">
        <div>
            <header style="background-color:white;border-radius: 5px; text-align: right; width:100%;">
                <nov>
                    <table width="100%">
                        <tr>
                            <th style="text-align: right;">
                                <input class="input" style="border:0px;font-size: large;margin-right: 5%;" type="image" name="menu" id="menu" width="70px" height="70px" src="image/menu.png" onclick="a()">
                            </th>
                            <th style="text-align: center;">
                                <b style="margin-right: 40%;">
                                    صفحه اصلی
                                </b>
                            </th>
                            <th style="text-align: left;">
                                <image width="100px" height="100px" id="logo" name="logo" src="image/لوگو هنر.jpg"></image>
                            </th>
                        </tr>
                    </table>
                </nov>
            </header>
            <div style="height:100%; text-align: center;">
                <aside name="aside" class="a1" id="aside" hidden="true" style=" border-radius: 5px;">
                    
                    <table style="height: 20%; width: 100%;background-color: royalblue;">
                        <tr>
                            <th>
                                <br>
                                <label>
                                    منوی کناری
                                </label>
                                <br>
                                <br>
                            </th>
                        </tr>
                    </table>
                    <br>
                    <a href="ideas.html">
                        <image id="idea icon" name="idea icon" src="image/idea.png"></image>
                    </a>
                    <br>
                    <a style="font-size: large;" class="input" href="ideas.html"> ثبت نظر </a>
                    <br>
                    <hr width="99%" size="2%" align="center" color="white">
                    <a href="shahardeh site.html">
                        <image id="home" name="home" src="image/home.png"></image>
                    </a>
                    <br>
                    <a style="font-size: large;" class="input" href="shahardeh site.html"> خانه </a>
                    <br>
                    <hr width="99%" size="2%" align="center" color="white">
                    <input type="image" class="input"  id="phone icon" name="تماس با ما" src="image/phone icon.png" onclick="c()">
                    <br>
                    <input type="button" class="input" style="border:0; font-size: large;" value="تماس با ما" id="تماس با ما" name="تماس با ما" onclick="c()">
                    <br>
                    <br>
                    
                </aside>
                <section id="sec" class="s1">
                    <article>

                    </article>
                </section>
            </div>
        </div>
        <h5>
            <hr width="100%" size="2%" align="center" style="color:rgb(220, 220, 220);">
            <pre style="color:dimgray;">
                مالکیت مادی و معنوی این سایت متعلق به کشور شهارده می باشد.
                طراحی و توسعه از سپهر حلاجی
            </pre>
        </h5>
    </fieldset>
</body>
</html>
