# vim16

删除函数

## 知识点
- % 
- vim-intent-object

## 练习
```
function test() {
  console.log("test");
}

function getName(
	name = "haha", 
	age = 18
) {
  const a = "1";
  const b = "2";

  const arr = ["1", "2", "3"];

  if (a == b) {
    console.log("hahah");
  }
}

```