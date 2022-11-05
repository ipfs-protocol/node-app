1. npm init
2. npm install --save express cors dotenv morgan bcrypt jsonwebtoken cookie-parser express-session
3. npm install --save-dev nodemon
4. server.js 생성

ACCESS 토큰 발행
```
node
require('crypto').randomBytes(64).toString('hex')
```