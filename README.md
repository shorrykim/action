This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## 깃헙 액션 설정 및 PR 세팅 테스트 레포

해야할 것:

1. 깃헙 세팅
  - [ ] PR 승인권자 설정
  - [ ] rejected 하나라도 있을 때, 수동 머지 불가
  - [ ] master branch 특정 환경에서 PR 불가 및 허용
2. PR 자동화
  - [ ] Reviewers, Asignees 자동 설정
  - [ ] Labels 자동 설정 (당장은 hotfix 뿐이지만 이후에 추가된다면 분기처리는 어떻게 할지 고려해야함)
  - [ ] 추가 커밋 발생 시, Reviews 필요하다는 알림 재전송
3. 테스트코드 자동화
  - [ ] 테스트 라이브러리 학습
  - [ ] 테스트 라이브러리 자동화
