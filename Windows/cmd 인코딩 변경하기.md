- Windows의 기본 시스템 인코딩은 [cp949](https://ko.wikipedia.org/wiki/%EC%BD%94%EB%93%9C_%ED%8E%98%EC%9D%B4%EC%A7%80_949)로 설정되어 있다.
- 이로 인해 cmd 창에서 파일을 읽거나 웹 크롤링을 할 때 인코딩으로 인한 문제가 자주 발생하는데, 이를 방지하기 위해선 cmd 창에서 아래처럼  인코딩을 UTF-8로 변경하면 된다.

``` cmd
  chcp 65001
```
