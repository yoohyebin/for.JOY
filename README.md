# 🎞️ 사진에 음성을 더한 육아일기 for. JOY
<p align="center">
    <img width="500" alt="image" src="https://github.com/user-attachments/assets/053cbba8-3762-48e0-8280-312f181020f3">
</p>

>**개발기간: 2023.04 ~ 2023.05**

## 📖 프로젝트 소개
- for. JOY는 정적인 사진에 음성을 더해 추억을 더 생동감 있게 기록할 수 있는 육아일기 앱입니다. 
- 사용자는 앱에서 사진을 촬영하거나 앨범에서 선택한 후, 그 사진에 음성을 녹음해 저장할 수 있습니다.
- 저장된 사진과 음성은 태그 및 연도별로 분류되어 쉽게 확인할 수 있습니다.
  
## ☺️ 멤버 소개
| **Helia** | **NewYork** | **Ash** | **Sun** | **Olive** | **Joy** |
| :------: |  :------: | :------: | :------: | :------: | :------: |
| iOS Developer | iOS Developer | iOS Developer | iOS Developer | Designer | Project Manager |

---

## 🔧 Stacks 

### Environment
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=Xcode&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)               

### Development
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=Swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0086c8?style=for-the-badge&logo=Swift&logoColor=white)
![Realm](https://img.shields.io/badge/Realm-39477F?style=for-the-badge&logo=Realm&logoColor=white)

### Communication
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)


### Framework
**AVFoundation**
- 오디오 및 비디오 콘텐츠를 처리하고 조작하는 데 사용되는 프레임워크입니다.
- 사용자의 음성을 녹음하고 재생하는 기능에 활용되었습니다.

**PhotoKit**
- 사진 및 비디오 라이브러리에 접근하고 이를 조작하는 기능을 제공하는 프레임워크입니다.
- 사진을 촬영하고 불러오는 데 사용되었습니다.
---
## ⭐ Main Feature
### 사진 촬영 및 불러오기
- 사용자는 사진을 직접 촬영하거나 저장된 사진을 불러올 수 있습니다.
- 선택된 사진은 이동 및 크기 조절을 통해 편집이 가능합니다.

### 음성 녹음
- 선택된 사진을 보며 해당 사진에 대한 음성을 녹음할 수 있습니다.
- 녹음이 완료되면 제목, 태그, 날짜를 선택하여 저장할 수 있습니다.

### 앨범 기능
- 사용자가 만든 사진과 음성 기록은 앨범 형태로 정리되어 앱 메인 화면에서 확인할 수 있습니다.
- 각 사진에 저장된 음성 녹음을 재생할 수 있으며, 연도별로 앨범이 형성됩니다.
- 태그를 활용한 필터링 기능을 지원합니다.
---

## 🐈‍⬛ Git Branch
[Git 전략](https://github.com/yoohyebin/for.JOY/wiki)

## 📂 Project Structure
```
├─ Views
│  ├─ AddDoneView.swift
│  ├─ Album
│  │  ├─ AlbumView.swift
│  │  └─ PhotoSelectButton.swift
│  ├─ Camera
│  │  ├─ ImageCropView.swift
│  │  └─ ImagePickerView.swift
│  ├─ CarouselView.swift
│  ├─ GalleryView.swift
│  ├─ Info
│  │  ├─ EditInfoView.swift
│  │  ├─ InfoTagView.swift
│  │  └─ InfoView.swift
│  ├─ LottieView.swift
│  ├─ MainView.swift
│  └─ Voice
│     ├─ SoundVisualizer
│     │  ├─ BarView.swift
│     │  └─ SoundVisualizer.swift
│     ├─ TimerView.swift
│     └─ VoiceView.swift
├─ Model
│  ├─ Images.swift
│  ├─ Info.swift
│  ├─ Memory.swift
│  ├─ Tag.swift
│  ├─ Texts.swift
│  └─ VoiceViewModel.swift
├─ Data
│  ├─ Memory.swift
│  └─ RealmManager.swift
├─ Extensions
│  ├─ Colors+.swift
│  ├─ Date+.swift
│  ├─ Font+.swift
│  ├─ UIImage+.swift
│  ├─ UIScreen+.swift
│  └─ View+.swift
├─ Services
│  ├─ AudioPlayerManager.swift
│  ├─ DataManager.swift
│  ├─ PageManager.swift
│  └─ RealmManager.swift
├─ Utils
│  ├─ MicrophoneMonitor.swift
│  ├─ NavigationBarColorModifier.swift
│  ├─ OffsetReader.swift
│  └─ PermissionHandler.swift
└─ Resource
   ├─ Assets.xcassets
   └─ LottieFiles
```
---

## 👩🏻‍💻 Role
- 서비스 기획
- 데이터 구조 설계 및 데이터베이스 구축
- 카메라 및 사진 기능 구현
- UI 및 인터랙션 구현

## 💡 Learnings and Insights
- 서비스 기획 과정에서 팀원들의 다양한 의견을 하나로 조율하는 것이 쉽지 않다는 점을 깨달았습니다.
- 의견을 효과적으로 제시하고 소통하는 방법을 익히며 팀 내 협업 능력을 향상시킬 수 있었습니다.
