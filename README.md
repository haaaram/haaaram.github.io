<head>
        header{
/*             position: relative;
            left: 270px; */
            padding: 10px;
            margin: 25px;
            width: 1200px;
        }
        article{
/*             position: relative;
            left: 300px; */
            background-color: rgb(237, 237, 237);
            width: 1180px;
            padding: 25px;
        }
        #introduce{
            background-color: rgb(214, 253, 217);
            position: absolute;
            top: 168px;
            right: 50px;
            padding: 20px;
        }
        #cute{
            background-color: rgb(242, 255, 240);
            padding:10px;
        }
        #id{
            position:absolute;
            right:10px;
            top: 10px;
        }
    </style>
</head>
<body>
    <header><h1>개구리는 개굴개굴</h1></header>
    <hr>
    <article>
        게시판
        <h2>툼바 신라면 솔직 후기!</h2>
        <p style="color: rgb(131, 130, 130);">2024.11.04. 13:04 | 이웃공개</p>
        <hr>
        <p style="font-size:20px">
            안녕하세요 여러분!<br><br>
            오늘은 새로 나온 툼바 신라면을 먹어볼게요~ <br><br>
            <img src="shin.jpg" alt="">
        </p>
        <p style="color: rgb(131, 130, 130); text-decoration-line: underline;">
            더보기
        </p>
    </article>
    <article>
        <hr>
        <h3>방명록</h3>
        <textarea cols="70" rows="5">방명록을 남겨보세요!</textarea>
        <input type="submit" value="전송">
    </article>
    <aside id="introduce">
        <img src="frog.jpg" width="250px" alt="">
        <h3>하람🍀</h3>
        <div id="cute">
            제 블로그에 오신 것을 <br>환영합니다:>
            <br>서로이웃 받아요^^
        </div>
        <br>
        <div id="cute">
            <h4>카테고리</h4>
            <ul>
                <li>전체글(9)</li>
                <li>공부(2)</li>
                <li>[블챌] 주간일기 챌린지</li>
            </ul>
        </div>
    </aside>
    <div id="id">202001652 김하람</div>
</body>
</html>
