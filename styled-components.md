# styled-components

## 描述  

+ [![NPM](https://img.shields.io/npm/v/styled-components.svg)](https://www.npmjs.com/package/styled-components)
+ [github](https://www.styled-components.com/)  
+ [官网](https://www.styled-components.com/)



## 组件嵌套  

```jsx

    const StyleA = style.span`
        color: red;
    `
    const StyleB = style.div`
        ${StyleA}{
            color: blue;
        }
    `

```