# StreamMerger Native App

StreamMerger is an optional macOS companion app for StreamRec. It uses FFmpeg locally to
merge recording segments and reports conversion progress to the extension. Recorded media
is not uploaded to a StreamRec server.

## Download

- **Apple Silicon (M1/M2/M3/M4 and later):** [StreamMerger-v1.4.16-arm64.dmg](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-arm64.dmg)
- **Intel Mac:** [StreamMerger-v1.4.16-x86_64.dmg](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-x86_64.dmg)
- [Release notes and SHA-256 checksums](https://github.com/eddyslab/streamrec/releases/tag/v1.4.16)

## Install or upgrade

1. Download and open the DMG for your Mac.
2. Double-click **Install StreamMerger.command**.
3. Enter your macOS administrator password if requested.
4. Close and reopen the StreamRec popup.
5. Confirm that StreamMerger appears in the macOS menu bar and is detected by StreamRec.

Installing this version replaces an existing `/Applications/StreamMerger.app` and registers
the Native Messaging host for both Chrome and Firefox. Only one installation is needed even
if both browser extensions are installed.

Restart Chrome or Firefox only if the extension still reports that the Native App is not
connected after StreamMerger is running.

---

# StreamMerger Native App 설치 안내

StreamMerger는 StreamRec의 선택적 macOS 보조 앱입니다. FFmpeg을 사용해 녹화 세그먼트를
로컬에서 병합하고 변환 진행 상태를 확장에 전달합니다. 녹화 미디어를 StreamRec 서버로
업로드하지 않습니다.

## 다운로드

- **Apple Silicon Mac:** [StreamMerger-v1.4.16-arm64.dmg](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-arm64.dmg)
- **Intel Mac:** [StreamMerger-v1.4.16-x86_64.dmg](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-x86_64.dmg)
- [릴리스 안내 및 SHA-256 체크섬](https://github.com/eddyslab/streamrec/releases/tag/v1.4.16)

## 설치 또는 업그레이드

1. Mac 아키텍처에 맞는 DMG를 다운로드하여 엽니다.
2. **Install StreamMerger.command**를 더블 클릭합니다.
3. 요청되면 macOS 관리자 비밀번호를 입력합니다.
4. StreamRec 팝업을 닫았다가 다시 엽니다.
5. macOS 메뉴 막대에 StreamMerger가 표시되고 확장에서 연결된 상태인지 확인합니다.

이 버전을 설치하면 기존 `/Applications/StreamMerger.app`이 교체되고 Chrome과 Firefox용
Native Messaging Host가 모두 등록됩니다. 두 브라우저 확장을 모두 사용해도 한 번만 설치하면
됩니다.

StreamMerger가 실행 중인데도 확장에서 Native App 미연결로 표시되는 경우에만 Chrome 또는
Firefox를 다시 시작하세요.
