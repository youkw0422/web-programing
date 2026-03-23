<!DOCTYPE html>
<html lang="ko">
<head>
    <title>20230835 유경원</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--이름-->
    <h1>유경원</h1>
    <!--자기소개-->
    <p>안녕하십니까! 컴공과 23학번 유경원입니다.</p>
    <p>1학년 마치고 군대갔다가 이번에 복학했습니다.</p>
    <p>1년간 잘부탁드립니다.</p>
    <!--군대사진-->
    <img src="7.jpg" alt="군대사진">
    <h2>취미</h2>
    <ul>
        <li>게임하기</li>
        <li>노래듣기</li>
        <li>영화보기</li>
    </ul>
    <script>
        alert('안녕하세요!')
        document.write('<h2>자바스크립트로 출력!</h2>');
    </script>
        <form>
        <fieldset>
            <table>
                <tr>
                    <td><label for="name">아이디</label></td>
                    <td><input id="name" type="text"></td>
                </tr>
                <tr>
                    <td><label for="password">비밀번호</label></td>
                    <td><input id="password" type="password"></td>
                </tr>                
            </table>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="submit">
        </fieldset>
    </form>
    <form>
        <fieldset>
        <table>
            <th>시작 그룹</th>
            <tr>
                <td>
                    <input type="radio" name="group" id="new">
                    <label for="new">새 탭 페이지 열기</label><br>
                    <input type="radio" name="group" id="contin">
                    <label for="contin">중단한 위치에서 게속하기</label><br>
                    <input type="radio" name="group" id="point">
                    <label for="point">특정 페이지 또는 페이지 모음 열기</label>
                </td>
            </tr>
            <th>개인정보 및 보안</th>
            <tr>
                <td>
                    <input type="checkbox" name="secret" id="A">
                    <label for="A">동기화 및 서비스</label><br>
                    <input type="checkbox" name="secret" id="B">
                    <label for="B">로그인 허용</label><br>
                    <input type="checkbox" name="secret" id="C">
                    <label for="C">페이지 미리 로드</label>
                </td>
            </tr>
        </table>
        </fieldset>
    </form>
    <form>
        <fieldset>
            <h1>글 작성하기</h1>
            <b>작성자</b>
            <input type="text"><br>
            <b>아이디</b>
            <input type="text"><br>
            <b>이메일</b>
            <input type="text"><label for="mail">@</label><input type="text"><br>
            <b>휴대폰</b>
            <select>
                <option>010</option>
            </select>
            <label>-</label><input type="text"><label>-</label><input type="text"><br>
            <b>글제목</b>
            <input type="text"><br>
            <b>내용</b>
            &nbsp;&nbsp;&nbsp;&nbsp;<textarea cols="50" rows="20"></textarea><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="submit">
        </fieldset>
    </form>
</body>
</html>
