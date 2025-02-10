## 기본 세팅
1. 파일생성 ( 프로젝트 )
2. `npm init` ( 프로젝트 package.json 설정 )
3. `npm install express` ( 기본 툴 다운로드 )
4. `npm install -g nodemon` ( 서버 자동 재부팅 기능 다운로드 )
5. `server.js` ( 기본 서버 호스트 세팅 )
```javascript
const express = require('express');
const app = express();
                            // 기본 서버
app.listen(8080, function(){         // 포트 8080
    console.log('Listening on 8080')      // 정상적으로 서버 열리면 로그 출력
});
```
