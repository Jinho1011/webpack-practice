# Webpack을 알아봅시다

## [Concepts](https://webpack.js.org/concepts/)
웹팩은 자바스크립트 응용 프로그램을 위한 **정적 모듈 번들러**입니다. 웹팩이 프로그램을 처리할 때, 내부에서 의존성 그래프를 만들고 모든 모듈을 합쳐 번들로 제공합니다.

- Entry
- Output
- Loaders
- Plugins
- Mode
- Browser Compatibility

### Entry
- entry point는 웹팩이 어떤 모듈이 번들링해야 하는 지를 알려줍니다. 웹팩은 entry point가 어떤 모듈 또는 라이브러리에 의존하는지 알아냅니다. 

### Output
- output 속성은 웹팩이 생성한 번들을 어디에 어떤 이름으로 내보내는지를 알려주며 `./dist/main.js`가 기본값입니다.

### Loaders
- 웹팩은 오직 javascript와 JSON 파일만을 이해할 수 있습니다. Loaders는 웹팩이 다른 형식의 파일을 처리할 수 있도록 하며, 그것들이 프로젝트에서 사용 가능하고 의존성 그래프에 추가될 수 있도록 모듈 형식으로 변환합니다.

### Plugins
- Loaders가 특정한 유형의 모듈을 변환하는 데만 사용된다면, Plugins는 번들 최적화, asset 관리 또는 환경 변수 주입 등의 광범위한 작업을 수행합니다.


~~나머지는 다음 기회에~~