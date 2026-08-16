# GitHub Pages 배포 방법

이 폴더의 파일을 GitHub 저장소에 올리면 대시보드가 GitHub Pages에서 열립니다.

## 포함 파일

- `index.html`: 대시보드 첫 화면
- `seoul_simple_map_base.png`: 간소화 서울 지도 이미지
- `.nojekyll`: GitHub Pages가 파일을 그대로 제공하도록 하는 설정 파일

## 배포 순서

1. GitHub에서 새 저장소를 만듭니다.
2. 저장소 이름은 예를 들어 `touristification-risk-dashboard`로 설정합니다.
3. 저장소를 Public으로 만듭니다.
4. 이 폴더 안의 `index.html`, `seoul_simple_map_base.png`, `.nojekyll` 파일을 저장소 루트에 업로드합니다.
5. 저장소의 `Settings`로 이동합니다.
6. 왼쪽 메뉴에서 `Pages`를 선택합니다.
7. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
8. Branch는 `main`, folder는 `/root`로 설정하고 `Save`합니다.
9. 1~3분 뒤 GitHub Pages URL이 생성됩니다.

생성되는 주소 형식은 보통 아래와 같습니다.

```text
https://사용자이름.github.io/저장소이름/
```
