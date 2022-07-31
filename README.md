### Router-React-Project

### Deployment Vercel: https://router-project-indol.vercel.app/

### React에서 Router와 Firebase를 활용해서 SPA 페이지를 만들었습니다.

> Router v5로 진행했다는점을 알려드립니다.

```
- 초기화면: Firebase에서 card를 GET으로 가져온다.
- add를 통해 새로운 card를 만들어서 firebase에 POST로 보낸다.
- Sort버튼을 통해 최신순으로 정렬할 수 있다.
- card detail 페이지에서 댓글을 볼 수 있고 댓글을 달 수도 있다. ( 삭제는 안되므로 주의☠️ )
- 모든 로딩 시에는 로딩스피너가 나타나 로딩중이라는것을 알려준다.
```
### Technology
- React
    - useState
    - useEffect
    - useCallback
    - Custom hook
    - useRef
    - useReducer
- Router
    - useParams
    - NavLink
    - Link
    - Prompt
    - useHistory
    - useLocation
    - useRouteMatch
    - Redirect
