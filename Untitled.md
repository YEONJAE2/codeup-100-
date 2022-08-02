# 안녕하세요 24살 한재연 입니다.
## 자바 코드 올리기

---

```java
package sec01.exam8;

public class SwitchStringExample {

	public static void main(String[] args) {
		String position = "과장";
		
		switch(position) { // case 자리에 문자열 올 수 있음
		case "부장":
			System.out.println("700만원");
			break;
		case "과장":
			System.out.println("500만원");
			break;
		default:
			System.out.println("300만원");
		}
		
	}

}
```
