# PokeClip for OBS — 설치 파일

PokeClip OBS 플러그인의 설치 파일만 올리는 저장소입니다. 소스 코드는 없습니다.
최신 판은 [Releases](https://github.com/3K-PokeClip/pokeclip-obs-releases/releases/latest) 에서 받습니다.

## 설치

| OS | 파일 | 설치 |
| --- | --- | --- |
| Windows | `pokeclip-obs-*-windows-x64-installer.exe` | 실행 → `%ProgramData%\obs-studio\plugins\pokeclip-obs` · 제거는 설정 › 앱 |
| Windows (포터블 OBS·수동) | `pokeclip-obs-*-windows-x64.zip` | 압축을 OBS 폴더에 푼다 — 설치 파일과 함께 쓰지 않는다 |
| macOS | `pokeclip-obs-*-macos-universal.pkg` | 더블클릭 → `~/Library/Application Support/obs-studio/plugins` |

OBS 를 끈 뒤 설치합니다.

## 서명 상태

*   Windows: 서명 없음 — Chrome · SmartScreen 이 경고할 수 있습니다(SmartScreen 은
    「추가 정보 → 실행」).
*   macOS: pkg 서명 · Apple 공증 없음 — 처음 열 때 막히면 시스템 설정 › 개인정보
    보호 및 보안 › 「그래도 열기」.

## 받은 파일 확인

`SHA256SUMS.txt` 와 대조합니다: `shasum -a 256 -c SHA256SUMS.txt`
