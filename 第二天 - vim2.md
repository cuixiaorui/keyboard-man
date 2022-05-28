# 第二天 - vim2
在单行中更有效率的移动和插入


## 练习

   this is a test   


welcome come cuixueshe we're very good

```ts
function serializeElement(
  node: TestElement,
  indent: number,
  depth: number
): string {
  const props = Object.keys(node.props)
    .map(key => {
      const value = node.props[key]
      return isOn(key) || value == null
        ? ``
        : value === ``
        ? key
        : `${key}=${JSON.stringify(value)}`
    })
    .filter(Boolean)
    .join(' ');

  const padding = indent ? ` `.repeat(indent).repeat(depth) : ``

  return (
    `${padding}<${node.tag}${props ? ` ${props}` : ``}>` +
    `${serializeInner(node, indent, depth)}` +
    `${padding}</${node.tag}>`
  )
}

```

