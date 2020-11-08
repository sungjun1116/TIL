# 추가: HTTPS 서버 제공

- Teachable machine의 이미지 인식 기능은 https 통신 환경에서만 활성화가 됩니다. 본 수업에서는 https 환경을 만드는 방법을 소개합니다.
- web cam은 privacy와 관련된 내밀한 데이터기 때문에 많은 브라우저들에서 파일을 직접여는 방식(ctrl + o)으로는 코드를 활용할 수가 없다.
- 직접 서버를 통해 서비스를 할 수 있어야하고 https환경으로 해야한다.
- github page와 같은 https를 제공하는 곳에 업로드 해도 된다.
- 웹서버 준비과정

    ```
    npm install -g local-web-server
    ws --https --port 9999 --open 

    ```

- 보안상 에러가 뜨면 고급 버튼에서 무시하고 진행과 같은 항목을 체크한다.
- 동영상 강의

    [https://youtu.be/XBbRsQ2w2Hs](https://youtu.be/XBbRsQ2w2Hs)