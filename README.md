# React-dashed-box

![react-dashed-box logo](./logo.png?raw=true)

Dashed Box Component written in React.

## Installation

```sh
$ npm install react-dashed-box --save
```

## Usage

```jsx
import DashedBox from 'react-dashed-box';

class ExampleApp extends React.Component {
  render() {
    return <DashedBox height={100} width={100} text="click to add" />
  }
}
```

## Properties

| property  | type    | description         |
|-----------|---------|---------------------|
| className | string  | the class name      |
| height    | number  | the height of box   |
| width     | number  | the width of box    |
| text      | string  | the text of box     |
| onClick   | func    | fired when clicked  |

## License

MIT
