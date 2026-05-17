# 앱 띠배너 원격 설정

배너 파일은 **별도 공개 저장소**에서 관리합니다.

- 저장소: https://github.com/LeeHwaYoung4017/calculator_loan_add

## 파일

| 파일 | 설명 |
|------|------|
| `banner.json` | 배너 on/off, 이미지 파일명, 링크 URL |
| `banner.png` | 배너 이미지 (권장 1080×180 px) |

## banner.json 예시

```json
{
  "enabled": true,
  "image": "banner.png",
  "link": "https://your-link.com"
}
```

`main` 브랜치에 푸시하면 앱을 다시 실행할 때 반영됩니다. (APK 재빌드 불필요)

`enabled`가 `false`이거나 이미지 로드에 실패하면 배너 영역은 표시되지 않습니다.
