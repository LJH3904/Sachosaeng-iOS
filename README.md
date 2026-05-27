# 사초생（サチョセン）· Sachosaeng

> 社会人1年目のための職場の悩み集合知投票プラットフォーム | iOS
> 

<p align="left">
<img src="[https://img.shields.io/badge/App_Store-リリース済み-0D96F6?style=flat&logo=apple&logoColor=white](https://img.shields.io/badge/App_Store-%E3%83%AA%E3%83%AA%E3%83%BC%E3%82%B9%E6%B8%88%E3%81%BF-0D96F6?style=flat&logo=apple&logoColor=white)"/>
</p>

![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat&logo=swift&logoColor=white)

![Xcode](https://img.shields.io/badge/Xcode-15.0-147EFB?style=flat&logo=xcode&logoColor=white)

![iOS](https://img.shields.io/badge/iOS-16.0+-000000?style=flat&logo=apple&logoColor=white)

![SwiftUI](https://img.shields.io/badge/SwiftUI-0075FF?style=flat&logo=swift&logoColor=white)

---

## 📌 プロジェクト概要

- *사초생（サチョセン）**は、社会人1年目が職場で感じる主観的な悩みを投票システムで解決策を探す集合知プラットフォームです。
同世代の社会人から共感と実用的なアドバイスを得ることができます。
- **開発期間**: 2024年6月 〜 サービス終了
- **チーム構成**: iOS 1名・Android 1名・デザイナー 1名・マーケター 1名・PM 1名・バックエンド 2名
- **所属**: Prography（プログラフィー）9期チームプロジェクト

---

## 👤 担当範囲（イ・ジェヒョン / iOS 単独担当）

> iOSパートを1人で全て担当 — 設計からApp Storeリリースまで全工程を実施
> 

### アプリ全体設計

- **SwiftUI + UIKit** ハイブリッドアーキテクチャの設計・実装
- MVVMパターン適用、ViewModel によるUI状態管理
- REST API通信のためのネットワークレイヤー設計（URLSessionベース）
- 認証トークン管理および自動リフレッシュ処理

### 主要機能の実装

- **投票画面**: カテゴリ別投票一覧、投票参加・結果確認UI
- **情報案内**: 投票関連コンテンツの表示
- **ブックマーク**: 投票保存・一覧管理
- **マイページ**: プロフィール編集、興味設定、お問い合わせ
- **設定画面**: バージョン案内、OSSライセンス、プライバシーポリシー、退会

### 品質・リリース対応

- **Lottie** アニメーションによるUX向上
- KakaoSDK ソーシャルログイン連携
- TestFlight によるベータテスト実施
- App Store 審査対応・リリースまで全工程を単独で実施

---

## 🛠 技術スタック

| カテゴリ | 使用技術 |
| --- | --- |
| **言語 / IDE** | Swift 5.9, Xcode 15.0.1 |
| **UI** | SwiftUI, UIKit, Lottie |
| **認証** | KakaoSDK, Firebase |
| **クラウド** | Google Cloud |
| **協業ツール** | Figma, GitHub, Notion, TestFlight |

---
##📱 実装画面
![ios 6.7형.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b518ec18-e96b-4a6f-8124-e85cbc32181c/b7ff710a-503b-42f5-ab06-4fcc1f5e9ea8/ios_6.7%E1%84%92%E1%85%A7%E1%86%BC.png)

![6.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b518ec18-e96b-4a6f-8124-e85cbc32181c/7ec321e2-694c-42bb-afa1-570735100c8a/6.png)

![ios 6.7형2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b518ec18-e96b-4a6f-8124-e85cbc32181c/2c80105e-8626-42c5-a91b-7f2714f4e390/ios_6.7%E1%84%92%E1%85%A7%E1%86%BC2.png)
---
## 🏗 アーキテクチャ

```
MVVM（SwiftUI + UIKit ハイブリッド）
```

```
📦 Sachosaeng
├── 🗂 Config            # 環境設定ファイル
├── 🗂 Resource          # アセット・フォント
├── 🗂 Extension         # Swift Extension
│   ├── ColorExtension
│   ├── FontExtension
│   ├── ViewExtension
│   └── ViewModifier
├── 🗂 Utility           # 共通ユーティリティ
├── 🗂 Service           # ネットワーク・サービスレイヤー
│   ├── NetworkService   # REST API通信
│   ├── UserService
│   ├── AuthService
│   └── VersionService
├── 🗂 Model             # データモデル
├── 🗂 ViewModel         # 状態管理
└── 🗂 View              # UIレイヤー
    ├── SignView
    ├── HomeView
    └── BookmarkView
```

---

## ⚙️ 実行方法

環境設定ファイルはセキュリティ上、別途リクエストが必要です。

```
必要ファイル:
- Config.xcconfig
```

1. 上記ファイルを `Config/` フォルダに追加
2. `Sachosaeng.xcodeproj` を開く
3. ビルドして実行

---

## 👥 チーム構成

| 役割 | 担当 |
| --- | --- |
| iOS | イ・ジェヒョン [@LJH3904](https://github.com/LJH3904) |
| Android | Sachosaeng-Android チーム |
| Design / PM / Marketing / Backend | Prography 9期メンバー |

> 本プロジェクトは協業コミュニティ **Prography（プログラフィー）9期** のチームプロジェクトです。
iOSパートはイ・ジェヒョンが単独で全て担当しました。
> 

---

## 📄 License

© 2024 Prography 9th Team5


# 사초생 · Sachosaeng

> 사회초년생을 위한 직장생활 고민 투표 플랫폼 | iOS
> 

<p align="left">
<img src="[https://img.shields.io/badge/App_Store-출시완료-0D96F6?style=flat&logo=apple&logoColor=white](https://img.shields.io/badge/App_Store-%EC%B6%9C%EC%8B%9C%EC%99%84%EB%A3%8C-0D96F6?style=flat&logo=apple&logoColor=white)"/>
</p>

![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat&logo=swift&logoColor=white)

![Xcode](https://img.shields.io/badge/Xcode-15.0-147EFB?style=flat&logo=xcode&logoColor=white)

![iOS](https://img.shields.io/badge/iOS-16.0+-000000?style=flat&logo=apple&logoColor=white)

![SwiftUI](https://img.shields.io/badge/SwiftUI-0075FF?style=flat&logo=swift&logoColor=white)

---

## 📌 프로젝트 소개

**사초생**은 사회초년생이 직장생활에서 겪는 주관적인 고민을 투표 시스템으로 해결책을 찾는 집단지성 플랫폼입니다.
또래의 직장인들로부터 공감과 실질적인 정보를 얻을 수 있습니다.

- **개발 기간**: 2024.06 ~ 서비스 종료
- **팀 구성**: iOS 1인 · Android 1인 · 디자이너 1인 · 마케터 1인 · PM 1인 · 백엔드 2인
- **소속**: 프로그라피(Prography) 9기 팀 프로젝트

---

## 👤 본인 담당 범위 (이제현 / iOS 전담)

> iOS 파트 1인 전담 — 기획부터 App Store 출시까지 전 과정 수행
> 

### 앱 전체 설계

- **SwiftUI + UIKit** 혼합 아키텍처 설계 및 구현
- MVVM 패턴 적용, ViewModel 기반 상태 관리
- REST API 통신을 위한 네트워크 레이어 설계 (URLSession 기반)
- 인증 토큰 관리 및 자동 갱신 처리

### 주요 기능 구현

- **투표 화면**: 카테고리별 투표 목록, 투표 참여 및 결과 확인 UI
- **정보 안내**: 투표 연관 콘텐츠 표시
- **북마크**: 투표 저장 및 목록 관리
- **마이페이지**: 프로필 수정, 관심사 설정, 1:1 문의
- **설정**: 버전 안내, 오픈소스 라이브러리, 개인정보 처리방침, 탈퇴

### 품질 및 배포

- **Lottie** 애니메이션 적용으로 UX 향상
- KakaoSDK 소셜 로그인 연동
- TestFlight를 통한 베타 테스트 진행
- App Store 심사 및 출시 전 과정 단독 수행

---

## 🛠 기술 스택

| 분류 | 사용 기술 |
| --- | --- |
| **언어 / IDE** | Swift 5.9, Xcode 15.0.1 |
| **UI** | SwiftUI, UIKit, Lottie |
| **인증** | KakaoSDK, Firebase |
| **클라우드** | Google Cloud |
| **협업** | Figma, GitHub, Notion, TestFlight |

---

##📱 실행화면 
![ios 6.7형.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b518ec18-e96b-4a6f-8124-e85cbc32181c/b7ff710a-503b-42f5-ab06-4fcc1f5e9ea8/ios_6.7%E1%84%92%E1%85%A7%E1%86%BC.png)

![6.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b518ec18-e96b-4a6f-8124-e85cbc32181c/7ec321e2-694c-42bb-afa1-570735100c8a/6.png)

![ios 6.7형2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b518ec18-e96b-4a6f-8124-e85cbc32181c/2c80105e-8626-42c5-a91b-7f2714f4e390/ios_6.7%E1%84%92%E1%85%A7%E1%86%BC2.png)
---

## 🏗 아키텍처

```
MVVM (SwiftUI + UIKit 혼합)
```

```
📦 Sachosaeng
├── 🗂 Config            # 환경 설정 파일
├── 🗂 Resource          # 에셋 · 폰트
├── 🗂 Extension         # Swift Extension
│   ├── ColorExtension
│   ├── FontExtension
│   ├── ViewExtension
│   └── ViewModifier
├── 🗂 Utility           # 공용 유틸리티
├── 🗂 Service           # 네트워크 · 서비스 레이어
│   ├── NetworkService   # REST API 통신
│   ├── UserService
│   ├── AuthService
│   └── VersionService
├── 🗂 Model             # 데이터 모델
├── 🗂 ViewModel         # 상태 관리
└── 🗂 View              # UI 레이어
    ├── SignView
    ├── HomeView
    └── BookmarkView
```

---

## ⚙️ 실행 방법

환경 설정 파일은 보안상 별도 요청이 필요합니다.

```
필요 파일:
- Config.xcconfig
```

1. 위 파일을 `Config/` 폴더에 추가
2. `Sachosaeng.xcodeproj` 실행
3. 빌드 및 실행

---

## 👥 팀 구성

| 역할 | 담당 |
| --- | --- |
| iOS | 이제현 [@LJH3904](https://github.com/LJH3904) |
| Android | Sachosaeng-Android 팀 |
| Design / PM / Marketing / Backend | 프로그라피 9기 팀원 |

> 본 프로젝트는 협업 동아리 **프로그라피(Prography) 9기** 팀 프로젝트입니다.
iOS 파트는 이제현이 단독으로 전담하였습니다.
> 

---

## 📄 License

© 2024 Prography 9th Team5
