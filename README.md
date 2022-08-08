# golang_backend_stack

## webframework

### If you Need PERFORMANCE only
It based on fasthttp
- fiber https://github.com/gofiber/fiber/blob/master/.github/README_ko.md

### net/http standard library based 
둘 중 하나 선택. 대동소이. 취향차이
- gin https://github.com/gin-gonic/gin
- echo https://github.com/labstack/echo

### DB
+ postsql (recommend)
+ mysql

postgres, mysql 비교
https://techblog.woowahan.com/6550/

#### ORM
golang에서 orm은 다른 언어에서 orm보다 기능적과 사용성 측면에서 부실하다과 느낄 수 있음

- sqlc (recommand) https://github.com/kyleconroy/sqlc
  + sqlc는 orm은 아니지만 작성한 쿼리를 파싱하여 go code로 변환해줌
  + go-migrate와 함께 쓰면 좋다. https://github.com/golang-migrate/migrate
- GORM https://gorm.io/index.html
  - orm의 고인물이지만 문서가 부실함
- entgo https://entgo.io
  - facebook이 스폰서
  - gorm과 entgo중에 추천하라면 entgo가 문서가 더 잘 되어있었다.
  
### TEST
testify https://github.com/stretchr/testify

### RPC
grpc https://grpc.io

### container
docker https://www.docker.com

### container orchestration
kubernetes https://kubernetes.io
