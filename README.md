﻿# rc-arrow
[中文文档](./README_Zh.md)

An arrow of arbitrary size, arbitrary direction, and arbitrary angle

Example screenshot

|simple|simulate select | 发散箭头 |
| :----:|:----:|:----:|
|![simple][1]|![simulate select][2]|![发散箭头][3]|

## Install
`npm install rc-arrow --save`

```javascript
import Arrow from 'rc-arrow'

class Hw extends Component {
    render() {
        return (
            <Arrow size="20px" color="red"/>
        )
    }
}
```

## Example
[online example](https://ykforerlang.github.io/rc-arrow/example/helloworld/index.html) 

[Example code](https://github.com/ykforerlang/rc-arrow/tree/master/example/helloworld)



## props
| name | type | default | description|
| :----: |:----:  |:----:     |:----:        |
| degree| number| 90| the angle of the arrow |
| offsetDegree| number| 0| the direction of the arrow， 
The default direction is on the right |
| color| string| -| the color of the arrow |
| size| string|10px| the size of the arrow |





---


  [1]: https://raw.githubusercontent.com/ykforerlang/rc-arrow/master/static/arrow1.png
  [2]: https://raw.githubusercontent.com/ykforerlang/rc-arrow/master/static/rc2.gif
  [3]: https://raw.githubusercontent.com/ykforerlang/rc-arrow/master/static/rc5.png