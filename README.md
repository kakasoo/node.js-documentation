# 공식문서 (230628 v.18.16.1 기준)

# 시작 하기 전

내 개인적인 공부를 위해 문서를 번역하는데, 번역한 것을 공유하면 좋을 거 같아 기록한다.  
영어를 어떻게 옮길지 애매한 부분이나, 또는 영어에서 생략된 단어 등은 괄호 `()` 로 기재한다.  
가령 자바스크립트 런타임 (엔진) 과 같이 생략해도 문제없지만 괜한 혼란이 생길 수 있는 부분.



공식 문서 번역이라고 했지만 결국 내 공부를 위한 것이기 때문에 내 생각도 기록한다.  
다만 다른 사람이 읽으면 헷갈릴 수 있기 때문에 내 생각은 `이탤릭체`로 기록한다.  
내가 이해하기 쉽게 정리할 것이지만 공식문서이니 만큼 되도록 내 생각은 배제할 생각이긴 하다.  
  
`링크의 경우 문서에 참조되어 있는 경우라면 남기지만, 공식문서와 번역이 혼동될 수 있으면 제거`한다.  
가령, 이 문서에 오류가 있다면 이슈 트래커로 남겨달라는 내용이 있다면 이슈 페이지 링크는 제거한다.  
여기서 말하는 이 문서는 공식문서인데, 번역된 문서에 대한 이슈로 착각할 수 있기 때문.  

`문서에 대한 설명은 첫 About this documentation 부분을 제외하고는 모두 제거`한다.  
여기는 Node.js 내부 인터페이스와 구현에 대한, 그리고 사용법에 대한 것만 번역해서 올린다.  

> [Node.js Usage and example #Example](https://nodejs.org/dist/latest-v18.x/docs/api/synopsis.html#example) 부분을 번역한다면
>
> An example of a [web server](https://nodejs.org/dist/latest-v18.x/docs/api/http.html) written with Node.js which responds with `'Hello, World!'`:
> 
> 
> Commands in this document start with `$` or `>` to replicate how they would appear in a user's terminal. Do not include the `$` and `>` characters. They are there to show the start of each command.
> 
> Lines that don't start with `$` or `>` character show the output of the previous command.
> 
> First, make sure to have downloaded and installed Node.js. See [Installing Node.js via package manager](https://nodejs.org/en/download/package-manager/) for further install information.
> 

위와 같은 문장이 있을 때에는 ‘$’나 ‘>’ 기호는 명령어가 아니라는 사실을 굳이 적지 않을 것이다.  
내가 공부하고 싶은 것은 영어가 아니라 Node.js 자체이기 때문이고, 거기에 시간 낭비하고 싶지 않다.  
`내용을 생략함으로써 맥락이 단절되는 부자연스러운 부분은 내 멋대로 문장을 의역해서 이어 붙인다.`  

마지막으로, `Node.js 내부 구현 중 운영체제마다 달라지는 구현 부분은 모두 제거`한다.  
실제로 그러한 부분들이 존재한다면 그 위치는 기록하겠지만 이 번역의 목적과는 다르기 때문이다.
