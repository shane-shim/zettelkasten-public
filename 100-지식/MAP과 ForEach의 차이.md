# MAP과 ForEach의 차이

#100-지식

```javascript
const numbers = [1, 2, 3, 4, 5];

// map() 사용 예
const doubled = numbers.map(number => number * 2);
// doubled: [2, 4, 6, 8, 10]

// forEach() 사용 예
let sum = 0;
numbers.forEach(number => {
  sum += number;
});
// map은 리턴을 반환하고 forEach는 리턴을 반환하지 않는다. 
```
GTM 소스코드 로직 이해 


```javascript
function getTotalQuantity(products) {
  let result = 0; 
  products.forEach(function(product) {
    result += product.quantity;
  });
  return result;
}
```
- 
  변수 `result`는 합계를 누적하기 위해 `0`으로 초기화되었습니다.
- `map` 함수 내에서 `product += product.quantity`를 사용하고 있는데, 여기서 `product`는 `products` 배열의 각 항목을 가리킵니다. `product`에 직접 더하는 것이 아니라, `product.quantity`를 `result`에 더해야 합니다.
- `map`은 이 작업에 적합한 메서드가 아닙니다. `map`은 배열의 각 요소를 변환하고 새 배열을 반환하는데 사용됩니다. 값들의 합을 구하기 위해서는 `forEach` 또는 단순 반복문이 더 적절합니다.
- `//products의 존재를 모르겠다.`라는 주석은 `products`가 무엇인지에 대한 혼동을 나타냅니다. `products`는 각 제품이 `quantity` 속성을 가진 제품 객체의 배열이어야 합니다.
- `// +=의 의미는 증감인가?`라는 주석은 `+=` 연산자가 증가를 의미하는지 묻습니다. `+=` 연산자는 오른쪽의 값을 왼쪽 변수에 더하고 그 결과를 왼쪽 변수에 할당합니다.
