# SimCore — RisuAI 시뮬레이션 엔진 플러그인

봇에 숫자로 굴러가는 상태(변수·규칙·이벤트·상태창)를 붙이는 RisuAI 플러그인입니다.
이 저장소는 배포 전용입니다. 플러그인 파일과, 원하는 분만 쓰는 다리 파일(`bridge/`)이 올라옵니다.

## 받기

[simcore.plugin.js](https://raw.githubusercontent.com/yuha-665/simcore-release/main/simcore.plugin.js)를 열고 저장(Ctrl+S)하세요.
위 파일 목록에서 `simcore.plugin.js` → **Download raw file**로 받아도 됩니다.

## 설치

리수 설정 → 플러그인 → 가져오기에서 받은 파일을 고르세요.

## 업데이트

**v1.21.5부터는** 새 버전이 나오면 리수 설정 → 플러그인 화면의 SimCore 줄에 **초록색 업데이트 버튼**이 뜹니다. 누르면 바로 바뀝니다.

- v1.21.5보다 옛 판을 쓰고 계시면, 이번 한 번만 위처럼 직접 받아 가져오기 해 주세요. 그다음부터 버튼이 뜹니다.
- 업데이트하면(직접 가져오기도 같습니다) 리수가 플러그인 설정 두 칸(`aux_model_mode`·`module_assets`)을 비웁니다.
  **v1.22.1부터는** 칸이 비어 있으면 지난번에 적어 둔 값을 그대로 이어 씁니다. 기본값으로 돌리려면 기본값(`auto`·`off`)을 직접 적어 주세요.
  그 전 판은 기본값으로 돌아가니, 바꿔 쓰고 계셨다면 다시 맞춰 주세요. 봇에 설치한 시스템·채팅의 상태는 어느 판이든 그대로입니다.
- 버튼이 안 보이면 플러그인 화면을 닫았다가 다시 열어 주세요. 새 판이 올라온 직후 몇 분은 늦게 보일 수 있습니다.

## 🔌 다리 — 이 PC의 Claude Code·Codex로 봇 만들기 (선택, 실험 기능)

SimCore 편집기의 AI 어시스턴트(✨ 창작, 💬 대화, 🛠 봇 제작 등)를 리수의 API 모델 대신 이 PC에 설치된 Claude Code나 Codex로 돌릴 때만 필요합니다.
RP 채팅과 상태 갱신은 그대로 리수 모델입니다.

[SimCore-bridge.zip](https://github.com/yuha-665/simcore-release/raw/main/bridge/SimCore-bridge.zip)을 받아 **압축을 풀고**, 안의 `README.txt`(사용법)를 따라 주세요.

- 리수 데스크톱이나 같은 PC의 셀프호스트(리스바드 포함)에서 됩니다. 웹 리수는 실험적으로 되고, 포켓리스·폰은 안 됩니다.
- 압축 파일 안에서 바로 실행하면 안 됩니다. `cli-bridge.bat`과 `simcore-cli-bridge.js`가 같은 폴더에 있어야 합니다.
- 쓰는 만큼 본인 Claude Code·Codex 구독 사용량이 듭니다.
- 다리는 플러그인과 버전이 따로입니다. 들어 있는 파일의 지문은 `bridge/MANIFEST.txt`에 있습니다.

## 바뀐 내용

버전마다 바뀐 내용은 [올라온 기록](https://github.com/yuha-665/simcore-release/commits/main)과 아카라이브 업데이트 공지에 있습니다.
