# StreamMerger Native App

StreamMerger is an optional macOS companion app for StreamRec. It uses FFmpeg locally to
merge recording segments and reports conversion progress to the extension. Recorded media
is not uploaded to a StreamRec server. Depending on the recording and Mac, native merging
can be more than twice as fast as browser-based conversion. Windows support is planned.

## Download

- **Apple Silicon (M1/M2/M3/M4 and later):** [StreamMerger-v1.6.18-arm64.dmg](https://github.com/eddyslab/streamrec-chrome/releases/download/v1.6.18/StreamMerger-v1.6.18-arm64.dmg)
- **Intel Mac:** [StreamMerger-v1.6.18-x86_64.dmg](https://github.com/eddyslab/streamrec-chrome/releases/download/v1.6.18/StreamMerger-v1.6.18-x86_64.dmg)
- [Release notes and SHA-256 checksums](https://github.com/eddyslab/streamrec-chrome/releases/tag/v1.6.18)

## Install or upgrade

This optional installation is intended for users comfortable with Terminal.

1. Download and open the DMG for your Mac.
2. Open Terminal and run:

   ```bash
   bash /Volumes/StreamMerger/setup.sh
   ```

3. Wait until Terminal reports that StreamMerger is ready.
4. Close and reopen the StreamRec popup.
5. Confirm that the extension shows **Native App** as connected.

Installing this version replaces an existing `/Applications/StreamMerger.app` and registers
the Native Messaging host for both Chrome and Firefox. Only one installation is needed even
if both browser extensions are installed.

Restart Chrome or Firefox only if the extension still reports that the Native App is not
connected after StreamMerger is running.

---

# StreamMerger Native App 설치 안내

StreamMerger는 StreamRec의 선택적 macOS 보조 앱입니다. FFmpeg을 사용해 녹화 세그먼트를
로컬에서 병합하고 변환 진행 상태를 확장에 전달합니다. 녹화 미디어를 StreamRec 서버로
업로드하지 않습니다. 녹화 내용과 Mac 환경에 따라 브라우저 변환보다 2배 이상 빠른
병합 속도를 제공할 수 있습니다. 현재 macOS만 지원하며 Windows는 추후 지원할 예정입니다.

## 다운로드

- **Apple Silicon Mac:** [StreamMerger-v1.6.18-arm64.dmg](https://github.com/eddyslab/streamrec-chrome/releases/download/v1.6.18/StreamMerger-v1.6.18-arm64.dmg)
- **Intel Mac:** [StreamMerger-v1.6.18-x86_64.dmg](https://github.com/eddyslab/streamrec-chrome/releases/download/v1.6.18/StreamMerger-v1.6.18-x86_64.dmg)
- [릴리스 안내 및 SHA-256 체크섬](https://github.com/eddyslab/streamrec-chrome/releases/tag/v1.6.18)

## 설치 또는 업그레이드

이 선택적 설치 기능은 Terminal 사용에 익숙한 사용자를 위한 보조 기능입니다.

1. Mac 아키텍처에 맞는 DMG를 다운로드하여 엽니다.
2. Terminal을 열고 다음 명령을 실행합니다.

   ```bash
   bash /Volumes/StreamMerger/setup.sh
   ```

3. Terminal에 StreamMerger 연결 준비가 확인됐다는 메시지가 나올 때까지 기다립니다.
4. StreamRec 팝업을 닫았다가 다시 엽니다.
5. 확장 화면에서 **Native App**이 연결 상태로 표시되는지 확인합니다.

이 버전을 설치하면 기존 `/Applications/StreamMerger.app`이 교체되고 Chrome과 Firefox용
Native Messaging Host가 모두 등록됩니다. 두 브라우저 확장을 모두 사용해도 한 번만 설치하면
됩니다.

StreamMerger가 실행 중인데도 확장에서 Native App 미연결로 표시되는 경우에만 Chrome 또는
Firefox를 다시 시작하세요.
