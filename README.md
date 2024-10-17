# frontend_day33__reference_code-

1. 공통
    - [ ]  완성된 day32 폴더를 활용하여 day33을 완성해 주세요.
2. 게시글작성
    - [ ]  src/components/boards-write/index.tsx 경로의 게시글작성과 관련된 컴포넌트를 리팩토링 해보세요.
        - [ ]  제목, 내용, 글쓴이 3개의 input 들을 하나의 state로 통합해 주세요.
        - [ ]  해당 input에 입력시 state를 변경해주는 함수 3개 역시 마찬가지로 하나의 함수로 통합해 주세요.
3. 나만의컨텐츠목록[오픈API]
    - [ ]  src/app/openapis/page.tsx 경로에 오픈API를 사용하여 나만의컨텐츠목록을 보여주세요. (피그마 화면 없음. 디자인 자유)
    => 오픈API 종류에는 제한을 두지 않습니다.(ex, 강아지목록, 고양이목록 등)
    => 디자인 및 무한스크롤, 페이지내이션 등 어떠한 기능에도 제한을 두지 않으므로 자유롭게 만들어 주세요.
    => 페이지에서 직접 코드를 작성하기 보단, src/components/openapis-list/index.ts 의 경로에 컴포넌트를 만들고 조립해 주세요.
4. 컴포넌트[리팩토링]
    - [ ]  나만의컨텐츠[오픈API] 컴포넌트의 파일을 보완해 주세요.
    => 타입에러가 감지되어 빨간 밑줄이 그어지는 부분에 타입스크립트를 적용하여 문제를 해결해 주세요.
    => 유지보수가 쉽도록 파일을 hook.ts, index.tsx, queries.ts, styles.module.css , types.ts 로 분리해 주세요.
