# react-seven-segment-display

A React and TypeScript based component that seven-segment display.
숫자를 세그먼트 디스플레이 스타일로 렌더링하는 React 및 TypeScript 기반의 컴포넌트입니다.

## 사용 방법

### 설치
```bash
npm install seven-segment-display
```
또는
```bash
yarn add seven-segment-display
```

### 예제
```tsx
import { ReactSevenSegmentDisplay } from "react-seven-segment-display";

const App = () => <ReactSevenSegmentDisplay value="9" color="red" />;

export default App;
```
### Props

| Name           | Decription                                                 | Type      | Default value |
| -------------- | ---------------------------------------------------------- | --------- | ------------- |
| value          | Value displayed as 1 digit number (0 ~ 9)                  | `number`  |               |
| color          | Color of the display segments when turned on               | `string?` | `"red"`       |
| bakgroundColor | Color of the background                                    | `string?` | ``            |

