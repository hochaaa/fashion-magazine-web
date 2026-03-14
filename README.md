# Fashion Magazine

## 프로젝트 소개

인스타그램 피드 형식의 UI를 기반으로 올해의 패션 트렌드, 올해의 컬러, 스타일링 팁에 대해 소개하는 패션 매거진 웹입니다.

평소 패션 매거진과 정보들을 자주 찾아보던 경험에서 출발해,  
관심 있는 분야를 주제로 직접 웹 프로젝트를 구현해보고자 시작했습니다.

빠른 시간 안에 진행하기 위해, 인스타그램 promal_mag(프로멀 매거진)님의 자료를 사용했습니다. (https://www.instagram.com/promal_mag/)

## 기술 스택

### Frontend
- React
- TypeScript
- React Router
- Zustand
- CSS

### Backend
- Node.js
- Express

### Database
- PostgreSQL
- Prisma ORM

### Authentication
- JWT
- bcrypt

## 주요 기능

- 회원가입 / 로그인 / 회원 탈퇴
- 이메일 / 닉네임 중복 검사
- 피드 게시글 조회
- 게시글 저장(북마크)
- 저장한 게시글 목록 조회
- 패션 매거진 페이지 구성 (올해의 컬러, 올해의 트렌드, 스타일링 팁)
- 게시글, 페이지 댓글 작성 / 조회

## 프로젝트 구조

client/
├ components
├ pages
├ store
└ assets

server/
├ routes
├ middleware
├ prisma
└ app.mjs

## 실행 방법

### Frontend

```bash
cd client
npm install
npm run dev

### Backend

cd server
npm install
npm run dev
