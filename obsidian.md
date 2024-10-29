
# Obsidian



- Markdown 기반 문서 관리 도구
- 매우 빠른 속도
- 높은 자유도 제공
- 다양한 플러그인 제공
- 오랜 적응 시간 필요

![](https://obsidian.md/images/screenshot-1.0-hero-combo.png)



# 추천 플러그인

- obsidian의 플러그인은 `설정 > 커뮤니티 플러그인 > 탐색` 에서 탐색 할 수 있음
- 설치 완료 후 `설정 > 커뮤니티 플러그인 > 설치된 플러그인` 에서 활성화


## 문서 작성 확장 플러그인

### Marp Slide

- https://github.com/samuele-cozzi/obsidian-marp-slides
- markdown을 활용하여 Slide를 작성 할 수 있도록 하는 도구

![](https://github.com/samuele-cozzi/obsidian-marp-slides/raw/main/docs/pictures/CreateSlides.gif)

### Diagrams

- https://github.com/zapthedingbat/drawio-obsidian
- draw.io를 통해 obsidian에서 다이어그램을 그릴 수 있도록 하는 도구

![](https://github.com/zapthedingbat/drawio-obsidian/blob/main/docs/image/screenshot1.png?raw=true)


### latex-ocr

- https://github.com/lucasvanmol/obsidian-latex-ocr
- 이미지로 이루어진 수식 파일을 AI OCR를 통해 latex 수식으로 변환
- 사용을 위해서는 [huggingface api](https://huggingface.co/) 필요

![latex-ocr](https://github.com/lucasvanmol/obsidian-latex-ocr/blob/master/images/demo.gif?raw=true)


### Reference Map

- https://github.com/anoopkcn/obsidian-reference-map
- semantic scholar의 corpusId를 통해 obsidian에서 논문을 검색하고 Reference Map을 생성할 수 있는 플러그인

![](https://github.com/anoopkcn/obsidian-reference-map/blob/master/images/orm-demo.png?raw=true)

## AI 기반 확장 플러그인


### copilot

- https://github.com/logancyang/obsidian-copilot
- Obsidian 내부의 오픈소스 LLM 인터페이스

[demo video](https://www.youtube.com/watch?v=WxcBEXkQoSE)


### github-copilot

- https://github.com/Pierrad/obsidian-github-copilot
- obsidian과 [github copilot](github_copilot)과의 통합
- 작성중인 노트를 ai(gpt4.0) 기반으로 자동 완성
- 사용시 [github-copilot api]() 필요

![demo video](https://github.com/Pierrad/obsidian-github-copilot/blob/master/.github/assets/example.gif?raw=true)




### textgenerator-plugin
 
- https://github.com/nhaouari/obsidian-textgenerator-plugin


[demo video](https://www.youtube.com/watch?v=OergqWCdFKc)


### smart-connections


- https://github.com/brianpetro/obsidian-smart-connections
- ai 기반 노트 연결 플러그인
- 다양한 LLM(gpt, local 모델 등)을 통해 존재하는 노트의 상관 관계를 graph 기반의 link로 시각화

**주요 기능**
- **Smart View**: 현재 작성중인 노트를 바탕으로 AI 임베딩을 활용해 관련 노트를 실시간으로 제안
	- ![](https://github.com/brianpetro/obsidian-smart-connections/blob/main/assets/SCv2-Smart-View-dark.gif?raw=true)
- **Smart Chat**: 현재 작성중인 노트를 기반으로 하는 AI 대화로, 노트 작성과 브레인스토밍을 혁신적으로 지원. 
	- ![](https://github.com/brianpetro/obsidian-smart-connections/blob/main/assets/smart-connections-chat-who-am-i.gif?raw=true)
