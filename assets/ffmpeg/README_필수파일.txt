OPDTools M4A/AAC 내장형 변환에 필요한 FFmpeg 파일을 이 폴더에 넣어주세요.

필수 파일명:
1. ffmpeg.min.js
2. ffmpeg-core.js
3. ffmpeg-core.wasm
4. ffmpeg-core.worker.js

권장 조합:
- @ffmpeg/ffmpeg 0.11.6 dist/ffmpeg.min.js
- @ffmpeg/core 0.11.0 dist/ffmpeg-core.js / ffmpeg-core.wasm / ffmpeg-core.worker.js

GitHub 저장소 구조:
opdrename/assets/ffmpeg/ffmpeg.min.js
opdrename/assets/ffmpeg/ffmpeg-core.js
opdrename/assets/ffmpeg/ffmpeg-core.wasm
opdrename/assets/ffmpeg/ffmpeg-core.worker.js

이 파일들이 없으면 MP3 변환은 계속 사용할 수 있지만 M4A/AAC 변환은 실행되지 않습니다.
