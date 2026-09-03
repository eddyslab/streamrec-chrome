# StreamRec for Chrome

StreamRec records supported MediaSource (MSE) web streams directly in Chrome without screen
capture and saves recordings locally on the user's device.

- [Install StreamRec from the Chrome Web Store](https://chromewebstore.google.com/detail/streamrec/capiflgkfohikdadgmhknjafmjehembc)
- **Optional Native App — macOS only:** StreamMerger can make segment merging more than
  twice as fast as browser-based conversion, depending on the recording and Mac. StreamRec
  works without it. Windows support is planned.
  [Download StreamMerger for macOS](#download-the-optional-native-app)
- **선택 기능 Native App — macOS 전용:** StreamMerger는 녹화 내용과 Mac 환경에 따라
  세그먼트 병합 속도를 브라우저 변환 대비 2배 이상 높일 수 있습니다. 설치하지
  않아도 StreamRec은 동작하며, Windows는 추후 지원할 예정입니다.
  [macOS용 StreamMerger 다운로드](#native-app-다운로드)

## Features

- Direct MediaSource stream recording
- Local downloads through Chrome
- Single-track and multi-track handling
- Browser-based segment conversion
- Optional local StreamMerger Native App integration
- Recording and conversion progress display

Only record content that you own or are authorized to record. StreamRec is not designed to
bypass DRM, subscription controls, or other access restrictions.

## Requirements

- Chrome 120 or later
- The StreamMerger Native App is optional and installed separately

## Download the optional Native App

StreamMerger improves local merging of recording segments with FFmpeg. Browser-based
conversion remains available when StreamMerger is not installed or connected. StreamMerger
is currently available only for macOS; Windows support is planned. Depending on the recording
and Mac, native merging can be more than twice as fast as browser-based conversion.

Choose the installer for your Mac:

- **Apple Silicon (M1/M2/M3/M4 and later):** [Download StreamMerger v1.4.16 for arm64](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-arm64.dmg)
- **Intel Mac:** [Download StreamMerger v1.4.16 for x86_64](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-x86_64.dmg)
- [Release notes and checksums](https://github.com/eddyslab/streamrec/releases/tag/v1.4.16)

StreamMerger is shared by the Chrome and Firefox versions of StreamRec. If it is already
installed for Firefox, you do not need to install a second copy for Chrome. See the
[Native App installation guide](NATIVE_APP.md) for installation and troubleshooting.

## Native App 다운로드

StreamMerger는 FFmpeg을 사용해 녹화 세그먼트를 로컬에서 병합하는 선택 기능입니다.
StreamMerger가 설치되어 있지 않거나 연결되지 않은 경우에는 브라우저 병합을 사용합니다.
현재 macOS만 지원하며 Windows는 추후 지원할 예정입니다. 녹화 내용과 Mac 환경에 따라
네이티브 병합은 브라우저 변환보다 2배 이상 빠를 수 있습니다.

- **Apple Silicon Mac:** [StreamMerger v1.4.16 arm64 다운로드](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-arm64.dmg)
- **Intel Mac:** [StreamMerger v1.4.16 x86_64 다운로드](https://github.com/eddyslab/streamrec/releases/download/v1.4.16/StreamMerger-v1.4.16-x86_64.dmg)
- [릴리스 안내 및 체크섬](https://github.com/eddyslab/streamrec/releases/tag/v1.4.16)

Chrome과 Firefox는 하나의 StreamMerger를 공유합니다. Firefox용으로 이미 설치했다면
Chrome용으로 다시 설치할 필요가 없습니다. 설치 방법은 [Native App 설치 안내](NATIVE_APP.md)를
확인해 주세요.

## Support and privacy

- [Support](SUPPORT.md)
- [Privacy Policy](PRIVACY.md)
