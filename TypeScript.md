# Typescript
- 编译
- 强类型
- 真正面向对象

编译: `tsc hello.ts`


# 类型
void 空 
- 一般用于返回值

enum 枚举
```typescript
enum GENDER{
    MALE,
    FEMALE
}

let sex: GENDER;
sex = GENDER.MALE
```
any 变体变量

数组
```typescript
let list: any[] = [1, true, 'abc'];
let list: number[];
```

## 类型推测
根据初始化的值推测类型

## 联合类型

```typescript
let a: string|number;
a = 'abc';
a = 123;
```

# 函数类型
- 参数
- 返回值
```typescript
function sum(a: number, b: number): number{
    return a + b;
}
```

# 外部变量声明
`declare var 变量名`



