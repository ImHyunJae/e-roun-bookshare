# 📚 e로운 독서생활 (e-Pyeonhan Bookshare)

> **"우리 단지 이웃과 나누는 지혜, e로운 독서생활"** > e편한세상 주민들을 위한 간편 바코드 북쉐어링 웹앱입니다.

---

## ✨ 핵심 기능
- **간편 로그인**: 별도 가입 없이 닉네임 설정만으로 이용 (Firebase Anonymous Auth)
- **도서 등록**: ISBN 바코드를 스캔하여 자동 도서 정보 등록 (Kakao API)
- **도서 대여**: 최대 2주 대여 기간 설정 및 실시간 상태 확인
- **반납 인증**: 사진 촬영을 통한 반납 인증 및 개인정보(이전 사진) 자동 삭제 로직
- **도서 목록**: 단지 내 대여 가능한 도서 실시간 필터링

## 🛠 기술 스택
- **Frontend**: Next.js 14+ (App Router), Tailwind CSS
- **Backend**: Firebase (Firestore, Storage, Auth)
- **Deployment**: Vercel
- **Libraries**: html5-qrcode, Firebase SDK

## 🚀 시작하기 (Local Setup)

1. 환경 변수 설정 (`.env.local`)
   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_key
   NEXT_PUBLIC_KAKAO_API_KEY=your_key
   ...
