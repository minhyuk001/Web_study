## app.get ( localhost:8080/(이동장소) )
```javascript
app.get('/', function(요청, 응답){    // 경로가 '/'이라면 메인 페이지
    응답.send('Main Home Page')
})
```
```javascript
app.get('/sub1', function(요청, 응답){    // 경로가 '/sub1'이므로 해당 페이지로 접속
    응답.send('Sub1 Home Page')
})
```

## Html 파일 서버로 보내기
```javascript
app.get('/', function(요청, 응답){    // 경로가 '/sub1'이므로 해당 페이지로 접속
    응답.sendFile(__dirname + '/index.html')    // 경로에 있는 index.html을 파일로 전송
})
```

## Html Design
Bootstarp 사이트 이용하기
