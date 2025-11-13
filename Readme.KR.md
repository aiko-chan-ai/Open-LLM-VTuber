![](./assets/banner.kr.jpg)

<h1 align="center">Open-LLM-VTuber</h1>
<h3 align="center">

[![GitHub release](https://img.shields.io/github/v/release/t41372/Open-LLM-VTuber)](https://github.com/t41372/Open-LLM-VTuber/releases) 
[![license](https://img.shields.io/github/license/t41372/Open-LLM-VTuber)](https://github.com/t41372/Open-LLM-VTuber/blob/master/LICENSE) 
[![CodeQL](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber/actions/workflows/codeql.yml/badge.svg)](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber/actions/workflows/codeql.yml)
[![Ruff](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber/actions/workflows/ruff.yml/badge.svg)](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber/actions/workflows/ruff.yml)
[![Docker](https://img.shields.io/badge/t41372%2FOpen--LLM--VTuber-%25230db7ed.svg?logo=docker&logoColor=blue&labelColor=white&color=blue)](https://hub.docker.com/r/t41372/open-llm-vtuber) 
[![QQ Group](https://img.shields.io/badge/QQ_Group-792615362-white?style=flat&logo=qq&logoColor=white)](https://qm.qq.com/q/ngvNUQpuKI)
[![QQ Channel](https://img.shields.io/badge/QQ_Channel_(dev)-pd93364606-white?style=flat&logo=qq&logoColor=white)](https://pd.qq.com/s/tt54r3bu)


[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/yi.ting)
[![](https://dcbadge.limes.pink/api/server/3UDA8YFDXx)](https://discord.gg/3UDA8YFDXx)

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/Open-LLM-VTuber/Open-LLM-VTuber)

[英文 README](https://github.com/t41372/Open-LLM-VTuber/blob/main/README.md) | [中文 README](https://github.com/t41372/Open-LLM-VTuber/blob/main/README.cn.md) | 한국어 README

[문서](https://open-llm-vtuber.github.io/docs/quick-start) | [![Roadmap](https://img.shields.io/badge/Roadmap-GitHub_Project-yellow)](https://github.com/orgs/Open-LLM-VTuber/projects/2)

<a href="https://trendshift.io/repositories/12358" target="_blank"><img src="https://trendshift.io/api/badge/repositories/12358" alt="t41372%2FOpen-LLM-VTuber | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

</h3>


> 자주 발생하는 문제 문서 (중국어로 작성됨): https://docs.qq.com/pdf/DTFZGQXdTUXhIYWRq
>
> 사용자 설문조사: https://forms.gle/w6Y6PiHTZr1nzbtWA
>
> 调查问卷(中文): https://wj.qq.com/s2/16150415/f50a/



> :warning: 이 프로젝트는 아직 초기 단계에 있으며, 현재 **활발히 개발 중**입니다.

> :warning: 서버를 원격으로 실행하고 다른 기기(예: 컴퓨터에서 서버를 실행하고 휴대폰에서 접속)를 통해 접근하려면 `https` 설정이 필요합니다. 이는 프론트엔드의 마이크 기능이 보안된 환경(https 또는 localhost) 에서만 동작하기 때문입니다. 자세한 내용-> [MDN Web Doc](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia).따라서 원격 기기(즉, localhost가 아닌 환경)에서 페이지에 접근하려면 리버스 프록시를 사용해 https를 설정해야 합니다.


## ⭐️ 이 프로젝트는 무엇인가요?


**Open-LLM-VTuber**는 **실시간 음성 대화**와 **시각적 인식**을 지원할 뿐만 아니라, 생동감 있는 **Live2D 아바타**를 갖춘 **음성 상호작용 AI 동반자**입니다. 모든 기능은 컴퓨터에서 완전히 오프라인으로 실행할 수 있습니다!

개인적인 AI 동반자로 활용할 수 있습니다 — `virtual girlfriend`, `boyfriend`, `cute pet` 등 원하는 어떤 캐릭터든 기대에 맞출 수 있습니다. 이 프로젝트는 `Windows`, `macOS`, `Linux`를 완전히 지원하며, **웹 버전**과 **데스크톱 클라이언트**의 두 가지 사용 모드를 제공합니다. 특히 **투명 배경 데스크톱 펫 모드**를 지원하여, AI 동반자가 화면 어디에서든 함께할 수 있습니다.

장기 메모리 기능은 일시적으로 제거되었지만(곧 다시 제공될 예정), 채팅 로그의 **지속 저장** 덕분에 이전에 끝내지 못한 대화를 **중단 없이 이어갈 수 있으며**, 소중한 상호작용 순간을 잃지 않을 수 있습니다.

백엔드 지원 측면에서, 다양한 LLM 추론, 텍스트-투-스피치, 음성 인식 솔루션을 통합했습니다. AI 동반자를 맞춤 설정하고 싶다면, [Character Customization Guide](https://open-llm-vtuber.github.io/docs/user-guide/live2d)를 참고하여 AI 동반자의 외형과 성격을 커스터마이즈할 수 있습니다.

이 프로젝트가 `Open-LLM-Companion`이나 `Open-LLM-Waifu`가 아닌 `Open-LLM-Vtuber`라는 이름을 가진 이유는, 초기 개발 목표가 **Windows 외 플랫폼에서도 오프라인으로 실행 가능한 오픈소스 솔루션을 활용**하여 **폐쇄형 AI Vtuber인 `neuro-sama`를 재현**하는 것이었기 때문입니다.

이 프로젝트는 `v1.0.0` 버전 이후 **코드 리팩토링**을 거쳤으며, 현재 활발히 개발 중으로 **곧 다양한 흥미로운 기능들이 추가될 예정**입니다! 🚀업데이트 계획은 [Roadmap](https://github.com/users/t41372/projects/1/views/5)에서 확인할 수 있습니다.


### 👀 데모
| ![](assets/i1.jpg) | ![](assets/i2.jpg) |
|:---:|:---:|
| ![](assets/i3.jpg) | ![](assets/i4.jpg) |


## ✨ 기능 & 주요 특징

- 🖥️ **크로스 플랫폼 지원**: `macOS`, `Linux`, `Windows`와 완벽하게 호환됩니다. NVIDIA GPU와 비-NVIDIA GPU 모두 지원하며, CPU 실행이나 클라우드 API를 활용한 고사양 작업 수행 옵션도 제공합니다. 일부 구성 요소는 macOS에서 GPU 가속을 지원합니다.

- 🔒 **오프라인 모드 지원**: 로컬 모델을 사용하여 완전히 오프라인에서 실행할 수 있으며, 인터넷 연결이 필요하지 않습니다. 대화 내용은 사용자의 기기에만 저장되어 개인 정보와 보안이 보호됩니다.

- 💻 **매력적이고 강력한 웹 및 데스크톱 클라이언트**: 웹 버전과 데스크톱 클라이언트 두 가지 사용 모드를 제공하며, 풍부한 상호작용 기능과 개인화 설정을 지원합니다. 데스크톱 클라이언트는 창 모드와 데스크톱 펫 모드를 자유롭게 전환할 수 있어, AI 동반자가 항상 곁에 함께할 수 있습니다.

- 🎯 **고급 상호작용 기능**:
  - 👁️ 시각 인식 : 카메라, 화면 녹화, 스크린샷을 지원하여 AI 동반자가 사용자의 모습과 화면을 볼 수 있습니다.
  - 🎤 헤드폰 없이도 음성 인식 가능: AI가 자신의 목소리를 듣지 않고, 음성을 처리할 수 있습니다.
  - 🫱 터치 피드백: 클릭이나 드래그로 AI 동반자와 상호작용할 수 있습니다.
  - 😊 Live2D 표정: 백엔드에서 감정 매핑을 설정하여 모델의 표정을 제어할 수 있습니다.
  - 🐱 펫 모드: 투명 배경, 항상 위, 마우스 클릭 통과를 지원하며, AI 동반자를 화면 어디로든 자유롭게 이동할 수 있습니다.
  - 💭 AI의 내면 표현: AI가 말하지 않아도 AI의 표정, 생각, 행동을 확인할 수 있습니다.
  - 🗣️ AI 능동 발화 기능 (사용자가 말하지 않아도 AI 가 먼저 발화)
  - 💾 채팅 로그 지속 저장: 언제든 이전 대화로 전환할 수 있습니다.
  - 🌍 TTS 번역 지원: (예 AI는 일본어 음성으로 말하면서 중국어로 채팅할 수 있습니다.)

- 🧠 **광범위한 모델 지원**:
  - 🤖 Large Language Models (LLM): Ollama, OpenAI (and any OpenAI-compatible API), Gemini, Claude, Mistral, DeepSeek, Zhipu AI, GGUF, LM Studio, vLLM, etc.
  - 🎙️ Automatic Speech Recognition (ASR): sherpa-onnx, FunASR, Faster-Whisper, Whisper.cpp, Whisper, Groq Whisper, Azure ASR, etc.
  - 🔊 Text-to-Speech (TTS): sherpa-onnx, pyttsx3, MeloTTS, Coqui-TTS, GPTSoVITS, Bark, CosyVoice, Edge TTS, Fish Audio, Azure TTS, etc.

- 🔧 **높은 커스터마이징 자유도**:
  - ⚙️ **간단한 모듈 구성**: 간단한 설정 파일 수정만으로 다양한 기능 모듈을 전환할 수 있으며, 코드 수정은 필요하지 않습니다.
  - 🎨 ***캐릭터 커스터마이징**: 커스텀 Live2D 모델을 가져와 AI 동반자에게 고유한 외형을 부여할 수 있습니다. Prompt를 수정하여 AI 동반자의 성격을 설정하고, **음성 클로닝**을 통해 원하는 목소리를 입힐 수 있습니다.
  - 🧩 **유연한 Agent 구현**: Agent 인터페이스를 상속하고 구현하여 HumeAI EVI, OpenAI Her, Mem0 등 다양한 Agent 아키텍처를 통합할 수 있습니다.
  - 🔌 우수한 확장성: 모듈식 설계를 통해 자신만의 LLM, ASR, TTS 등 모듈을 쉽게 추가할 수 있으며, 언제든 새로운 기능을 확장할 수 있습니다.


## 👥 User Reviews
> Thanks to the developer for open-sourcing and sharing the girlfriend for everyone to use
> 
> This girlfriend has been used over 100,000 times


## 🚀 Quick Start

Please refer to the [Quick Start](https://open-llm-vtuber.github.io/docs/quick-start) section in our documentation for installation.



## ☝ Update
> :warning: `v1.0.0` has breaking changes and requires re-deployment. You *may* still update via the method below, but the `conf.yaml` file is incompatible and most of the dependencies needs to be reinstalled with `uv`. For those who came from versions before `v1.0.0`, I recommend deploy this project again with the [latest deployment guide](https://open-llm-vtuber.github.io/docs/quick-start).

Please use `uv run update.py` to update if you installed any versions later than `v1.0.0`.

## 😢 Uninstall  
Most files, including Python dependencies and models, are stored in the project folder.

However, models downloaded via ModelScope or Hugging Face may also be in `MODELSCOPE_CACHE` or `HF_HOME`. While we aim to keep them in the project's `models` directory, it's good to double-check.  

Review the installation guide for any extra tools you no longer need, such as `uv`, `ffmpeg`, or `deeplx`.  

## 🤗 Want to contribute?
Checkout the [development guide](https://docs.llmvtuber.com/docs/development-guide/overview).


# 🎉🎉🎉 Related Projects

[ylxmf2005/LLM-Live2D-Desktop-Assitant](https://github.com/ylxmf2005/LLM-Live2D-Desktop-Assitant)
- Your Live2D desktop assistant powered by LLM! Available for both Windows and MacOS, it senses your screen, retrieves clipboard content, and responds to voice commands with a unique voice. Featuring voice wake-up, singing capabilities, and full computer control for seamless interaction with your favorite character.






## 📜 Third-Party Licenses

### Live2D Sample Models Notice

This project includes Live2D sample models provided by Live2D Inc. These assets are licensed separately under the Live2D Free Material License Agreement and the Terms of Use for Live2D Cubism Sample Data. They are not covered by the MIT license of this project.

This content uses sample data owned and copyrighted by Live2D Inc. The sample data are utilized in accordance with the terms and conditions set by Live2D Inc. (See [Live2D Free Material License Agreement](https://www.live2d.jp/en/terms/live2d-free-material-license-agreement/) and [Terms of Use](https://www.live2d.com/eula/live2d-sample-model-terms_en.html)).

Note: For commercial use, especially by medium or large-scale enterprises, the use of these Live2D sample models may be subject to additional licensing requirements. If you plan to use this project commercially, please ensure that you have the appropriate permissions from Live2D Inc., or use versions of the project without these models.


## Contributors
Thanks our contributors and maintainers for making this project possible.

<a href="https://github.com/Open-LLM-VTuber/Open-LLM-VTuber/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Open-LLM-VTuber/Open-LLM-VTuber" />
</a>


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=t41372/open-llm-vtuber&type=Date)](https://star-history.com/#t41372/open-llm-vtuber&Date)






